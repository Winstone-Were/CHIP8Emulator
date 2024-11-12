# 🎮 CHIP-8 Emulator

This is a simple CHIP-8 emulator written in C++. It allows you to load and play CHIP-8 ROMs using SDL2 for graphics and input handling.

## ✨ Features

- 🖥️ **Emulates** the CHIP-8 virtual machine
- 📂 **Supports** loading ROMs
- 🔧 **Customizable** video scale and CPU cycle delay
- 🌐 **Cross-platform** graphics and input handling with SDL2

## 📋 Prerequisites

- 🛠️ **C++11** or newer
- ⚙️ **CMake** 3.14 or newer
- 🎨 **SDL2** development library

## 🛠️ Building

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/Winstone-Were/CHIP8Emulato
cd chip8
```

### 1. Create a build directory

```bash
mkdir build && cd build
```

### 2. Run CMake to configure the project

```bash
cmake ..
```

### 3. Build the project

```bash
make
```

## 🚀Usage
After building, you can run the emulator as follows:

```bash
./chip8 <Scale> <Delay> <ROM>
```
<Scale>: The scaling factor for the display. For example, 10 will scale the display to 10 times the original CHIP-8 resolution.
<Delay>: The delay in milliseconds between CPU cycles.
<ROM>: Path to the CHIP-8 ROM file you want to load.

```bash
./chip8 10 5 path/to/rom.ch8
```
## 📂Code Structure
- Source/Chip8.cpp: Implements the CHIP-8 virtual machine.
- Source/Main.cpp: Main entry point of the emulator.
- Source/Platform.cpp: Handles SDL2 setup and input processing.
## 📦 Dependencies
The emulator uses SDL2 for graphics and input. Install SDL2 using the following command (Linux):

```bash
sudo apt-get install libsdl2-dev
```

