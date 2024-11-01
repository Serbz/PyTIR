This project doesn't have much IDE time behind it.
It's very new, and very much a work in progress.

The idea is that, since it is usually very difficult to focus on anything when trying to capture virtual images in a total internal reflection, you can observe the differences in light that are caused by small particles in the air.
I have created a python script I call PyTIR, and it groups the values of brightness in HSV vertically for an image, and then averages the brightness for those groups. It takes those averages and applies pixel per pixel changes to the original image. It does this so that it can adjust the image in accordance with the first and last groups pixel averages. I plan to do much more with this script and refine it, but I thought it's current output was interesting, as it depicts what is typically termed "Shot Noise" or "Photon Noise" on each layer of luminance observed in my TIR images. This is significant, I thought, and would like to discuss further with you.




I differenced Frame1 at 90% with the original, reduced the contrast, and increased the brightness.


Origina Frame: https://i.imgur.com/MK8MNlA.png

NPI Output 1 from PyTIR: https://i.imgur.com/rcFZYPS.png

Difference: https://i.imgur.com/5KZrvcf.png




Further Examples of Fibonacci patterns using PyTIR:



Curves/Levels edit 1: https://imgur.com/cr0pmO8

Curves/Levels edit 2: https://imgur.com/u5liNI8

Original Frame here: https://imgur.com/c3LArwR

NPI Output 10 from PyTIR: https://imgur.com/htFOYnU

NPI Output 1 from PyTIR: https://imgur.com/P0sEJMp



I've also observed this same thing happening when I reached the diffraction limit of a mirror, 2 non-silicon coated reflective lenses, and the reflective lense of a camera. As I approached the diffraction limit for my setup, various virtual images from the internal reflection shown in the camera.

this is what started my project:

https://imgur.com/ySSY5rq

https://imgur.com/aFjyjcR

https://imgur.com/AURRy0N

https://imgur.com/RbvyU8r 

