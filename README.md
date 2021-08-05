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

### Ploy Fill with Transparency
Draw any Shape with Transparency, the function is similar to Opencv PolyFill, just it takes a list of tuples, instead of numpy array,
here you have option to control the Transparency of shape as well, 

```python
# call the function
img =fillPolyTrans(img=img, points=points_list, color=(0,255,0), opacity=.5)

```

### rectTrans 

This function allows to draw a rectangle with transparency, similar to opencv rectangle it has opacity 

```python
    # call the function.
        img=rectTrans(img, pt1=(30, 320), pt2=(160, 260), color=(0,255,255),thickness=-1, opacity=0.6)

```


I have youtube Channel with subscribers ![YouTube Channel Subscribers](https://img.shields.io/youtube/channel/subscribers/UCc8Lx22a5OX4XMxrCykzjbA?style=social), If you can increase that counter, go a head do this for me 😃, just kidding as always ;-)  [AiPhle](https://youtube.come/c/aiphle) is all about Computer Vision, AI and Electronics.

hope you found this helpful,  if you want to ask me any thing then here are my social medias. 

## :green_heart: Join Me on Social Media :green_heart:

<a href="https://www.youtube.com/c/aiphile"> <img alt="AiPhile Youtube" src="/icons/youtube-icon.png"  width="40" height="40"></a>
<a href="https://www.facebook.com/AIPhile17">
<img alt="AiPhile Facebook" src="icons/face-book-icon.png"  width="40" height="40">
</a>
<a href="https://www.instagram.com/aiphile17/"> <img alt="AiPhile Insta" src="icons/instagram-icon.png"  width="40" height="40">
</a>
<a href="https://github.com/Asadullah-Dal17"> <img alt="Github" src="icons/github-icon.png"  width="40" height="40">
</a>
