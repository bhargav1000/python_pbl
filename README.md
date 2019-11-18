# Python PBL(Project Based Learning)
A [Steganography](https://en.wikipedia.org/wiki/Steganography) based Python project for 6th semester College PBL event written using Pillow. This script uses LSB Steganography an [Image based steganography](https://www.geeksforgeeks.org/image-steganography-in-cryptography/) method to encode text in an image using the ascii characters of the encoding text and embedding it in the image using the Least Significant Bit (LSB). This method helps send sensitive information using commonplace media such as images and audio. It helps store information in seemingly benign files. 

## Requirements:
- Pillow 1.1.7
- textwrap 0.9.2 or newer

## Getting Started:
### 1. Encoding an Image:
- Navigate to ```images``` folder and paste the image you want to encode. Convert this image to **PNG** format and save as ```hidden.png```, this is your image to be encoded with text. 
- type ```python encode_img.py``` in your console/command prompt and enter the text to be encoded.
- the ```encoded_image.png``` is your secret image containing the encoded text. This image can be sent to the receiving party.

### 2. Decoding an Image:
- Paste the encoded image in the ```images``` folder and type ```python decode_img.py``` in your console/command prompt.
- ```decoded_img.py``` provides the secret text decoded from the encoded image, navigate to the ```images``` folder and open ```decoded_image.png```

Have fun ;)

