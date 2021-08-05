# utils
> These are the helping function, which will help to avoid reparation of code, 

## Opencv Text Beautification
---
### Text With Background color,having controlled Transparency.

This function Calculates the size of text, using opencv Function, getTextSize, on the base of height and width, we add here the extra padding(x,y) to increase the background, to look it more decent.


```Python
#Call the function
img=textWithBackground(img, 'Colored Background Texts', cv.FONT_HERSHEY_COMPLEX, 1.6, (60,70), textThickness=3, bgColor=(0,255,0), textColor=(0,0, 0), bgOpacity=0.5, pad_x=10, pad_y=10)


```
---
### Draw Text with Blurred background 

The function, calculates the size of input Text and apply some padding (x,y), which is decidable, apply blur to the ROI, and Draws Text upon the blurred background.

```Python
#Call the function
 textBlurBackground(img, 'Blured Background Text', cv.FONT_HERSHEY_COMPLEX, 1.4, (60, 140),3, (0,255, 0), (71,71), 13, 13)

```
---
### *Results Above Function*
---

![output](https://user-images.githubusercontent.com/66181793/128294567-046e6fca-3c59-4104-882e-52499cb9d871.png)


---

###  Different colors 
----
|BLACK|WHITE|BLUE|RED|CYAN|YELLOW|MAGENTA|GRAY|GREEN| PURPLE|ORANGE|PINK|
|-------|--------|------|-----|------|--------|---------|-------|-------|--------|--------|-

<img src='/images/color_image.png' width='800'>

