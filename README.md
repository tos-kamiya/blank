# blank

A small collection of scripts for immediately darkening the screen on Linux.

## Requirements

- Bash
- GNOME on Wayland: `gnome-session-inhibit` and `busctl`
- X11: `xset`

## Usage

Darken the screen:

```bash
./blank
```

Temporarily inhibit automatic screen blanking. Use this while watching a video, reading, or otherwise keeping the screen active:

```bash
./awake
```

`awake` is effective only while it is running. Press `Ctrl+C` to stop it. While active, it prints the elapsed time since startup to standard error.

For the Japanese documentation, see [README_ja-JP.md](README_ja-JP.md).

## License

This project is dedicated to the public domain under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).
