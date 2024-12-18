# `bulletsep` Package

The `bulletsep` package provides a simple and customizable way to create inline bullet-separated lists in LaTeX. It allows you to control the spacing around bullets and supports optional customization via key-value options.

## Features
- Inline bullet-separated lists for clean and professional layouts.
- Customizable spacing around bullets.
- Easy to use and integrate into existing LaTeX projects.

## Installation
1. Save the `bulletsep.sty` file in your project directory or in a location where LaTeX can find it (e.g., a local `texmf` tree).
2. Include the package in your LaTeX document with:
   ```latex
   \usepackage{bulletsep}

## Usage
### Basic Usage:
```
Lorem \bulletsep ipsum \bulletsep dolor \bulletsep sit \bulletsep amet.
```
### Setting Global Spacing:
To set the default spacing for all \bulletsep commands:
```
\usepackage[spacing=.5em plus 2em]{bulletsep}
```
### Adjusting Spacing Locally:
You can override the default spacing for individual bullets:
```
Lorem \bulletsep[.5em plus 2em] ipsum \bulletsep[1em] dolor.
```

