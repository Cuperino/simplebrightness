# Simple Brightness
A simple brightness control frontend for [brightnessctl](https://github.com/Hummer12007/brightnessctl).

## What does it do
This program interfaces with the `brightnessctl` terminal tool to allow changing the brightness of the screen by controlling its backlight.

## Installation
1. First install [brightnessctl](https://github.com/Hummer12007/brightnessctl).
2. Then download `simplebrightness` from this repository.
3. Make sure that `simplebrightness` is marked as an executable on your computer. You can run `chmod +x ./simplebrightness` on the terminal, from inside the `simple-brightness` folder to make it an executable.
4. Run `simplebrightness` (simple double click on the script or run it from a terminal).

## About the code
Simple Brightness is written in Python 3, using Tk, and is licensed under the MIT License, the same license as [brightnessctl](https://github.com/Hummer12007/brightnessctl/blob/master/LICENSE).

## Why did I write this
I was having trouble getting [xbacklight](https://cgit.freedesktop.org/xorg/app/xbacklight) to work in KDE Neon 5.15 and I needed a way to control the laptop's brightness from the terminal. [Brightnessctl](https://github.com/Hummer12007/brightnessctl) did the work, but then I wanted a simple frontend to use in WindowMaker (my desktop of preference for saving battery and older machines). After being unable to find any frontends, I decided to create this one.
