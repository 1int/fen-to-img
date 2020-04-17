# fen-to-img
This is my fork of fen-to-png project by tikul. Original repo [here.](https://github.com/tikul/fen-to-png)

fen-to-img is a simple CLI for converting FEN strings to image files.

## What's new in this fork

I've added a few features I lacked in the original project:
- migrated to python3 to avoid annoying deprecation messages
- introduced board orientation (changes according to whose move is next)
- improved resources quality (2x size)
- added watermark support 
    
## Install
Clone this repo
```shell
git clone https://github.com/1int/fen-to-img.git
cd fen-to-img
```
Install dependencies
```shell
pip3 install -r requirements.txt
```
## Usage
```
python main.py [-h] [-f format] [-o output file] [-dir output folder] FEN FEN FEN FEN FEN FEN
```
To diplay a help message
```
python main.py -h
```
Visit the [wikipedia page](https://en.wikipedia.org/wiki/Forsyth%E2%80%93Edwards_Notation) to read more about FENs.

## Demo
Original repo:

![rnbqkbnr/pp1ppppp/8/2p5/4P3/5N2/PPPP1PPP/RNBQKB1R b KQkq - 1 2](images/example.png  "rnbqkbnr/pp1ppppp/8/2p5/4P3/5N2/PPPP1PPP/RNBQKB1R b KQkq - 1 2")


This repo:

<img src="https://github.com/1int/fen-to-img/blob/master/images/example-new.png" width="500" height="500" />
