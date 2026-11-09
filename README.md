
# Linux — Manim Animation

A short Manim animation about Linux distributions, focusing on three different approaches to choosing a distribution: **Debian, Fedora, and Arch Linux**.

The animation is an original project and was not based on or recreated from another animation.

## Overview

The animation starts with Tux and several Linux distribution logos before introducing the idea of choosing between different distributions.

It presents:

- **Debian** as the stable, reliable choice
- **Fedora** as a current and dependable option
- **Arch Linux** as the highly customizable choice
- A broader comparison of the different distributions
- A final transition into **NixOS**
- A personal closing title

## Animation Sequence

The animation progresses through several sections.

### Introduction

Tux appears alongside the Debian, Arch Linux, and Fedora logos, followed by:

> Why Bother with the rest,  
> when you can work on the best!

The distributions then move across the screen to transition into the main section.

### Choosing a Distribution

The animation introduces:

> The only 3 that you need ...

followed by:

> Pick one.

The three distributions are then presented individually.

### Debian

Debian is presented with:

> Stable, but current.

followed by:

> You won't get updates, and  
> it just works!!!

### Arch Linux

Arch Linux is then presented with:

> You can install anything,  
> and you can break anything!

### General Comparison

The animation then moves away from the individual distributions and presents the idea of choosing based on personal requirements:

> Choose one based on your needs

and:

> They have varying degrees of stability,  
> but they are expansive enough to have a  
> large community each.

This section ends with:

> but, if its hard to decide ...

## Assets

The project uses several image assets that are included directly in the repository:

```text
assets/
├── tux.png
├── debian.png
├── arch.png
├── fedora.png
├── temple.png
└── nixos.png
```
## Running the Animation

Use manim:

```bash
uv sync
```
To render the video:

```bash
manim -pqm main.py linux
```
