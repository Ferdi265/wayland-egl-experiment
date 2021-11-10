# Wayland EGL Experiment

This repo contains the results of my personal experiments with writing a first
Wayland client that uses EGL (also my first eperiments with EGL).

The experiments are roughly based on an [old Wayland Client Programming Tutorial][1],
but updated to use `xdg_shell` instead of `wl_shell`.

The main purpose of these experiments was to get a basic barebones client
running that can at least create "a window" and render to it.

## Dependencies

- `CMake`
- `libwayland-client`
- `libwayland-egl`
- `libEGL`
- `libGLESv2`
- `wayland-scanner`
- `wayland-protocols`

## Files

- `main.c`: render a yellow window that resizes correctly

[1]: https://jan.newmarch.name/Wayland/EGL/
