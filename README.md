# Color Generator Project

## Overview
This project is a simple color generator built using JavaScript to create random colors. Every time you use the generator, it produces a unique color along with its corresponding RGB color code.

## Features
- Generates a random color with each click.
- Displays the color's RGB code (e.g., `rgb(123, 200, 100)`).
- Changes the background color dynamically.
- Simple and lightweight code implementation.

## How It Works
The generator uses the following logic:
1. A button click triggers the random color generation.
2. The function `getRandomColor()` generates random red, green, and blue values between 0 and 255 using `Math.random()`.
3. The RGB values are formatted into a valid color string.
4. The background color of a designated element is updated, and the RGB code is displayed.
