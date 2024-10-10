This project doesn't have much IDE time behind it.
It's very new, and very much a work in progress.

The idea is that, since it is usually very difficult to focus on anything when trying to capture virtual images in a total internal reflection, you can observe the differences in light that are caused by small particles in the air. 
I have created a python script I call PyTIR, and it groups the values of brightness in HSV vertically of an image, and then averages the brightness for those groups. It takes those averages and applies pixel per pixel changes to the original image. It does this so that it can adjust the image in accordance with the first and last groups pixel averages. I plan to do much more with this script and refine it, but I thought it's current output was interesting.

I differenced Frame1 at 90% with the original, reduced the contrast, and increased the brightness.

Original: https://i.imgur.com/MK8MNlA.png

Frame1 (Output): https://i.imgur.com/rcFZYPS.png

Difference: https://i.imgur.com/5KZrvcf.png
