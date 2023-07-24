# CS50 PSET4 - Image Filters

This repository contains the solutions to the CS50 Problem Set 4 - Image Filters. It includes C implementations of four image filters: Grayscale, Sepia, Blur, and Reflection. The filters are designed to manipulate and process BMP images, providing various visual effects.

## Problem Set Description

The problem set involves implementing the following image filters:

1. Grayscale filter: Converts a colored image to a black-and-white image by averaging the RGB components of each pixel.

2. Sepia filter: Applies a warm, brownish tone to the image by manipulating the RGB values of each pixel.

3. Blur filter: Smooths out the image by averaging the colors of neighboring pixels.

4. Reflection filter: Mirrors the image horizontally, creating a reflection effect.

## File Description

### `helpers.h`

The `helpers.h` file contains function prototypes for the image filters implemented in `helpers.c`. The header file includes the following function declarations:

- `void grayscale(int height, int width, RGBTRIPLE image[height][width])`: Converts the input image to grayscale.

- `void sepia(int height, int width, RGBTRIPLE image[height][width])`: Applies the sepia filter to the input image.

- `void reflect(int height, int width, RGBTRIPLE image[height][width])`: Reflects the input image horizontally.

- `void blur(int height, int width, RGBTRIPLE image[height][width])`: Applies a blur effect to the input image.

These functions are used in the main `filter.c` program to process the input BMP image and apply the desired filter.

## Getting Started

To get started with the image filters, you need to clone this repository to your local machine. Follow these steps:

1. Open your terminal or command prompt.

2. Change the current working directory to the location where you want to store the repository.

3. Run the following command to clone the repository:

-`git clone https://github.com/mirankavinda/CS50-PSETS4-FILTERS.git`

4. Once the cloning process is complete, navigate into the repository:

-`cd CS50-PSETS4-FILTERS`

## Compilation

Before you can use the image filters, you need to compile the C source code. To do this, run the following command:

-`make filters`

## Usage

To use the image filters, you can run the `filter` program with the specified input image and the desired filter. Here's the command format:

-`./filter [flag] infile OUTFILE`

Replace `[flag]` with one of the following options: `b` (blur), `g` (grayscale), `r` (reflection), or `s` (sepia). `infile` should be the path to the input BMP image, and `outfile` should be the path to the output BMP file.

## Examples

Here are some examples of running the image filters:

1. To apply the grayscale filter to the `courtyard.bmp` image and save the result as `output.bmp`, run the following command:

-`$ ./filter -g images/yard.bmp out.bmp`

2. To apply the sepia filter to the `stadium.bmp` image and save the result as `output.bmp`, run the following command:

-`$ ./filter -g images/stadium.bmp out.bmp`

3. To apply the blur filter to the `tower.bmp` image and save the result as `output.bmp`, run the following command:

-`$ ./filter -g images/tower.bmp out.bmp`

4. To apply the reflection filter to the `yard.bmp` image and save the result as `output.bmp`, run the following command:

-`$ ./filter -g images/yard.bmp out.bmp`

Feel free to explore and experiment with different input images and filters!

## Credits

The problem set and starter code were provided by CS50, Harvard University. The implementation of the filters is done by Miran.

---
Note: Make sure to replace `mirankavinda` with your GitHub username in the repository URL.



   













