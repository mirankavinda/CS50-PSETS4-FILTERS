# CS50 PSET4 - Image Filters

This repository contains the solutions to the CS50 Problem Set 4 - Image Filters. In this problem set, we implement various image filters to manipulate and process images using C. The goal is to gain a deeper understanding of image processing concepts and practice working with image files.

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

1. Clone the repository to your local machine using the following command:

https://github.com/mirankavinda/CS50-PSETS4-FILTERS.git

2. [Additional setup instructions if required for the specific programming language or environment.]

## Implementation

The filters are implemented in C, and each filter can be found in the `helpers.c` file.

## Usage

To use the image filters, follow the steps below:

1. Compile the source code using the provided Makefile (if available) or compile the `filter.c` and `helpers.c` files together.

2. Run the program with the specified input image and the desired filter. For example:

./filter [flag] infile outfile


Replace `[flag]` with one of the following options: `b` (blur), `g` (grayscale), `r` (reflection), or `s` (sepia). `infile` should be the path to the input BMP image, and `outfile` should be the path to the output BMP file.

## Examples

[Include some examples of input images and their corresponding filtered outputs.]

## Credits

The problem set and starter code were provided by CS50, Harvard University. The implementation of the filters is done by [Your Name].

## License

[Indicate the license you want to use for your code, e.g., MIT License, GNU General Public License, etc.]

## Acknowledgments

[If you received help or referenced any external resources, acknowledge them here.]
