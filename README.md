# webpics
Just a script to reduce the file size and adjust the format of multiple images for blogs and websites

This script takes (lists of) jpeg- and png-files as input and
- converts all images to png-files
- converts portrait format images to landscape format images by adding whitespace to the sides
- scales large images down to 1280 horizontal pixels
- compresses the file size to 800kb maximum per image

For MacOS. Needs imagemagick and pngquant but no extra python libraries (system python is enough).
