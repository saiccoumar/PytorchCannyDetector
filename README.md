### Canny Edge Detection with Pytorch

This is my Edge Detection implementation via pytorch. I was originally using Stefan Pitur's canny edge detection in OpenCV but it was quite slow and CPU intensive so i rewrote it using pytorch. The conversions are near instantaneous on my local machine. The NonMax Suppression and Double Threshold Hysteresis had to be modified a little, but the results are largely the same. Hope this helps - Sai.

See https://github.com/StefanPitur/Edge-detection---Canny-detector/blob/master/README.md for more info on Canny Edge Detection.
