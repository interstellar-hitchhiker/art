# Art 
https://interstellar-hitchhiker.github.io/art/

# Abstract Art Generator

This project is a simple web-based tool for generating unique, abstract art pieces. Each generated image is a one-of-a-kind combination of shapes, colors, and patterns, allowing users to create and download their own abstract artwork.

## Features

- Generates random abstract art each time the "Generate Abstract Art" button is clicked.
- Uses random colors, shapes, gradients, circles, and lines to create visually appealing images.
- Allows users to download the generated artwork with a unique filename that includes the current date.

## How It Works

1. **HTML Structure**: The HTML file includes a `<canvas>` element for drawing the artwork and a button to trigger the image generation.

2. **CSS Styling**: The CSS styles center the canvas and the button on the page and provide a background color.

3. **JavaScript Functions**:
    - `getRandomInt(min, max)`: Generates a random integer between `min` and `max` inclusive.
    - `getRandomHexColor()`: Generates a random hexadecimal color code.
    - `generateRandomGradient(ctx, width, height)`: Creates a linear gradient with two random colors.
    - `generateImage()`: Clears the canvas, fills it with a random gradient background, and draws random shapes, circles, and lines to create abstract art.
    - `downloadImage(canvas)`: Converts the canvas content to a PNG file and triggers a download with a unique filename that includes the current date.

## Usage

1. Open the `index.html` file in a web browser.
2. Click the "Generate Abstract Art" button to create a new abstract art piece.
3. The generated image will be displayed on the canvas.
4. The image can be downloaded by clicking on the canvas, and it will be saved with a unique filename including the current date.

License
This project is licensed under the MIT License - see the LICENSE file for details.
