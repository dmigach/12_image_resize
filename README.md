# Image resizer

This script allows you to resize images.

## Supported formats:

- BMP
- EPS
- ICNS
- IM
- JPEG
- JPEG 2000
- MSP
- PCX
- PNG
- PPM
- SPIDER
- TIFF
- WebP
- XBM

## Prerequisites

The script is written in `Python 3`, so you'll need it's interpretator to run it.

## Install

To install all the necessary libraries to run the script just open your terminal, go to downloaded project directory and type:

    pip install -r requirements.txt

## Usage

To run the script type following in terminal:
    
    python image_resize.py example.png    
    
You can specify desired height/width (or both) **OR** scale. 
    
To get arguments help type

	python image_resize.py -h 
	
#

	-s, --scale SCALE
    -w, --width WIDTH
    -hg, --height HEIGHT
    -o, --output OUTPUT

	
## Examples

    python image_resize.py example.png --scale 2
    
Image will be enlarged twice and saved with same name but with resolution in name (example_2692x1132.png).

    python image_resize.py -w 500 example.png -o output.png
    
Image width will be 500px, output picture named `output.png`.

    python image_resize.py -hg 500 -w 300 example.png
    
You can specify both height and width.

## Support

In case of any difficulties or questions please contact <dmitrygach@gmail.com>.
