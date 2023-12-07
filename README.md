# GameBoy Fun!

## Welcome
Welcome to my ASM plyground dump. I'm using the GameBoy as a way to improve my Assemblyprogramming skills. Over time all add various programs and games that I make. I hope toto create an OS kernel for it. <- *We will see how this goes*

## Usage
Clone the repo
`git clone https://github.com/0x00ASTRA/GameBoy.git`

Install a GameBoy Emulator and run the '.gb' file you wish to execute.

## Compliling
Compile the Hello program:
```bash
rgbasm -L -o Hello.o Hello.asm
rgblink -o Hello.gb Hello.o
rgbfix -v -p 0xFF Hello.gb
```
