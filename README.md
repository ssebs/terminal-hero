```
    ███        ▄████████    ▄████████   ▄▄▄▄███▄▄▄▄    ▄█  ███▄▄▄▄      ▄████████  ▄█       
▀█████████▄   ███    ███   ███    ███ ▄██▀▀▀███▀▀▀██▄ ███  ███▀▀▀██▄   ███    ███ ███       
   ▀███▀▀██   ███    █▀    ███    ███ ███   ███   ███ ███▌ ███   ███   ███    ███ ███       
    ███   ▀  ▄███▄▄▄      ▄███▄▄▄▄██▀ ███   ███   ███ ███▌ ███   ███   ███    ███ ███       
    ███     ▀▀███▀▀▀     ▀▀███▀▀▀▀▀   ███   ███   ███ ███▌ ███   ███ ▀███████████ ███       
    ███       ███    █▄  ▀███████████ ███   ███   ███ ███  ███   ███   ███    ███ ███       
    ███       ███    ███   ███    ███ ███   ███   ███ ███  ███   ███   ███    ███ ███▌    ▄ 
   ▄████▀     ██████████   ███    ███  ▀█   ███   █▀  █▀    ▀█   █▀    ███    █▀  █████▄▄██ 
                           ███    ███                                             ▀         
                      ▄█    █▄       ▄████████    ▄████████  ▄██████▄                       
                      ███    ███     ███    ███   ███    ███ ███    ███                     
                      ███    ███     ███    █▀    ███    ███ ███    ███                     
                    ▄███▄▄▄▄███▄▄  ▄███▄▄▄      ▄███▄▄▄▄██▀ ███    ███                      
                    ▀▀███▀▀▀▀███▀  ▀▀███▀▀▀     ▀▀███▀▀▀▀▀   ███    ███                     
                      ███    ███     ███    █▄  ▀███████████ ███    ███                     
                      ███    ███     ███    ███   ███    ███ ███    ███                     
                      ███    █▀      ██████████   ███    ███  ▀██████▀                      
                                                  ███    ███                                
```

[![GitHub license](https://img.shields.io/github/license/amorriscode/terminal-hero)](https://github.com/amorriscode/terminal-hero/blob/master/LICENSE)

Bringing musical skills and fast fingers to a terminal near you 🤘

- [Getting Started](#getting-started)
  - [Mac / Linux](#mac--linux)
  - [Windows](#windows)
- [Usage](#usage)
- [Songs](#songs)

## Getting Started

### Mac / Linux
- Install Python3.6+
  - [Mac](https://docs.python-guide.org/starting/install3/osx/)
  - [Linux](https://docs.python-guide.org/starting/install3/linux/)
- Initialize terminal-hero:
  ```bash
  $ make init
  ```
- Rock out!
  ```bash
  $ source ./venv/bin/activate
  $ python main.py [songPath]
  ```
### Windows
- Install Python3.6+
  - [Direct](https://www.python.org/downloads/windows/)
  - [Microsoft Store](https://www.serverlab.ca/tutorials/windows/installing-python-3-7-on-windows-10/)
- Initialize terminal-hero:
  ```cmd
  PS> .\Makefile.bat init
  ```
- Rock out!
  ```cmd
  (venv) PS> python main.py [songPath]
  ```

## Usage

```bash
usage: main.py [-h] songPath

Bringing musical skills and fast fingers to a terminal near you 🤘

positional arguments:
  songPath    path to your Frets on Fire song

optional arguments:
  -h, --help  show this help message and exit
```

## Songs

Terminal Hero uses [songs created for Frets on Fire](http://fretsonfire.wikidot.com/song-creation). We do not provide any songs. You can find some on the [Frets of Fire forums](http://fretsonfire.wikidot.com/custom-songs) and they should Just Work™.
