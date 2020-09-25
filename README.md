# ImageToAscii
Convert an image to ASCII art. Uses ```opencv-python```.

# Customize Variables
- ```PXL_SIZE```: the square root of the amount of pixels that each character represents (a value of 1 means that 1 character will represent 1^2=1 pixel).
  - Should be a common factor of the dimensions of the input image. By defualt, it is set as the greatest common factor.
  
- ```colGrad```: the tuple of the characters used to make the ASCII art, with ```colGrad[0]``` being the darkest value and ```colGrad[-1]``` being the lightest value.

# Examples
![test](https://github.com/SeanJxie/ImageToAscii/blob/master/images/test.png)
![puffin](https://github.com/SeanJxie/ImageToAscii/blob/master/images/puffin.PNG)
