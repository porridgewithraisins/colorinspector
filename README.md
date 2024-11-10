# TUI Color inspector

A simple TUI color inspector that prints out the colors that you pass as arguments, in all the formats, colored with the
color itself.

Supports all HTML colors, hexadecimal, and RGB.

![screenshot of the app](screenshot.png)

## Usage

Download binary from releases

```
$ colorinspector
Usage: colorinspector <color1> [color2 ...]
Supported formats:
  - HTML color names (e.g., 'red', 'blue')
  - Hex values e.g., '#FF0000', '#f00', case insensitive
  - RGB values e.g., 'rgb(255,0,0)' or '255, 0, 0', space insensitive
```

## Build

`go build colorinspector.go`.
