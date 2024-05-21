### Canny Edge Detection with Pytorch

This is my Edge Detection implementation via pytorch. I was originally using Stefan Pitur's canny edge detection in OpenCV but it was quite slow so i rewrote it using pytorch. The conversions are near instantaneous on my local machine; so fast in fact the communication overhead from passing it to the GPU for conversion is longer than just doing the calculations on the CPU. The NonMax Suppression and Double Threshold Hysteresis had to be modified a little, but the results are largely the same. Hope this helps - Sai.

```
Elapsed Conversion Time: 0.0270 seconds, Device: cpu
Elapsed Conversion Time: 0.6266 seconds, Device: cuda
```

See https://github.com/StefanPitur/Edge-detection---Canny-detector/blob/master/README.md for more info on Canny Edge Detection.
