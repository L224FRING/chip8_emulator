# Chip-8 Emulator in Rust

A simple Chip-8 emulator written in Rust. This project emulates the Chip-8 virtual machine, allowing you to play Chip-8 games 

## 🧰 Requirements

- Rust (https://www.rust-lang.org/tools/install)
- A CHIP-8 ROM 

## 🚀 Running the Emulator

1. Clone the repository:

   ```bash
   git clone https://github.com/L224FRING/chip8-emulator.git
   cd chip8-emulator
   ```
   
2. Run the emulator with a Chip-8 game file:
   ```bash
   cargo run path/to/GAME_FILE
   ```
   Example:
   ```bash
   cargo run roms/PONG.ch8
   ```
# 🎮 Controls
The Chip-8 uses a 4x4 hexadecimal keypad. This emulator maps those keys to a standard keyboard as follows:
```
CHIP-8 Keypad         Keyboard Mapping

1 2 3 C               1 2 3 4
4 5 6 D      --->     Q W E R
7 8 9 E               A S D F
A 0 B F               Z X C V
```
# 📁 ROMs
You can find free public domain CHIP-8 ROMs online, for example:
    
    https://github.com/dmatlack/chip8/tree/master/roms
   
