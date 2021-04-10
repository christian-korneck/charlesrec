# charlesrec

A tiny shellscript wrapper around [Charles](https://www.charlesproxy.com/) to quickly record http traffic to a [`.har`](https://en.wikipedia.org/wiki/HAR_(file_format)) file from the shell. (No need to open Charles GUI).

## Setup

- fully configure charles in the GUI (i.e. enable SSL, etc)
- in the script change the path to the `Charles` executable (`CHARLES=<path>`)

## Usage

- (make sure no other Charles instance is running)
- start `charlesrec` to start recording
- press `CTRL + C` to stop recording
- the recording will be saved in the same dir to a file `charles_<timestamp>_<random>.har`


