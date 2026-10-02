# My Game

Ein Gamedev Projekt via Raylib in C.

## Build

Arch: `sudo pacman -S --needed base-devel git cmake libx11 libxrandr libxinerama libxcursor libxi mesa`

Ubuntu/Debian: `sudo apt install build-essential git cmake libx11-dev libxrandr-dev libxinerama-dev libxcursor-dev libxi-dev libgl1-mesa-dev`

```bash
cmake -B build
cmake --build build
./build/my_game
```
