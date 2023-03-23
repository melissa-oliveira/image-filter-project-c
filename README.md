# Image Filter Project in C

This project was created as part of the CS50 course and includes several image filters, including aging, reflection, blur, grayscale, and edge detection. The project was implemented in C programming language.

## Usage

To use this program, you need to have the CS50 library installed on your machine. Once you have that installed, you can compile the program with the following command:

    clang -ggdb3 -O0 -std=c11 -Wall -Werror -Wextra -Wno-sign-compare -Wno-unused-parameter -Wno-unused-variable -Wshadow -o filter filter.c -lcs50 -lm

To run the program, use the following command:

    ./filter [filter_name] [input_image] [output_image]

The filter_name parameter should be one of the following:

- blur
- grayscale
- reflection
- edges
- sepia

The input_image parameter should be the filename of the image you want to filter. The output_image parameter should be the filename of the resulting image.

## Example

Suppose you want to apply the grayscale filter to an image named input.bmp and save the result as output.bmp. You would run the following command:

    ./filter grayscale input.bmp output.bmp

## Credits

This project was developed based on the problem sets of the CS50 course offered by Harvard University. The bmp.h and bmp.c files were provided by the course staff.
