# monolith-savefile

Python scripts to decode and reencode `9201` and `2E01` entries from monolith save files

## requirements
- python3

## How to use

Download the repo with `https://github.com/OrioPrisco/monolith-savefile` or by using the download zip button  
open a terminal in the extracted/cloned folder  

to decode execute `python3 decode.py` then paste a line of `9201` or `2E01` from a monolith savefile  
to encode execue `python3 encode.py` then paste a decoded file, the send EOF (CTRL+Z ENTER on windows/CTRL+D on unix like oses)  
  
alternatively you can redirect the sandard input and or output  
  
## Options
`encode.py`	: `-i|--input input_file` read from `input_file` instead of stdin  
`decode.py`	: `-d|--debug` to display additional information on stderr  
both	: `-t|--type` to select the type of entries either `9201` or `2E01`  
	`-h|--help` displays an help message
