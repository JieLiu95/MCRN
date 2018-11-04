# MCRN
This is the official code of "Multiple Connected Residual Network for Image Enhancement on Smartphones", in ECCV Workshop PIRM 2018.
The test code is based on [Organizer provide](https://github.com/aiff22/ai-challenge)

The training code will be available after a few weeks.
### Demo
<p align="center">
  <img src="figs/example.PNG">
</p>
In this figure, (a) is input image obtain by iPhone 3GS, and (b) is enhanced image by MCRN.
## Installation
We train and test the program with one GPU which is GTX 1080Ti.
### Dependencies
TensorFlow 1.8.0
CUDA 9.0
Python 3.5

## Testing
Please run:
```
python test/test.py
```
If you want to test your own dataset, you can replace **dped** file.

## Citation
```
@InProceedings{geometry2018pirm,
author = {Liu, Jie and Jung, Cheolkon},
title = {Multiple Connected Residual Network for Image Enhancement on Smartphones},
booktitle = {European Conference on Computer Vision Workshops},
year = {2018},
}
```
