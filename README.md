# Snapy

A screenshot capture and beautification tool for Windows.

## Features

- **Capture Modes**: Region selection, active window, fullscreen
- **Image Effects**: Padding, inset, border radius, shadow
- **Background Styles**: Gradient presets, wallpaper, custom colors
- **Export**: Copy to clipboard, save to file, auto-save
- **Global Hotkeys**: Configurable shortcuts for each capture mode
- **Dark Mode** support

## Tech Stack

- C++20, Win32 API
- Direct2D (Rendering)
- WIC (Image encoding)
- WndUI Framework

## Build

```bash
cmake -B Build && cmake --build Build --config Release
```

## License

Copyright (c) 2025 bckim — All rights reserved.
