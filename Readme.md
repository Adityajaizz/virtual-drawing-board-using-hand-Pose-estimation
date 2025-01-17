# Virtual drawing board ✍️

![python](https://forthebadge.com/images/badges/made-with-python.svg)


[![PyTorch](https://img.shields.io/badge/-PyTorch-white?style=flat-square&logo=PyTorch)](https://pytorch.org/)
[![OpenCV](https://img.shields.io/badge/-OpenCV-blueviolet?style=flat-square&logo=OpenCV)](https://opencv.org/)
[![MediaPipe](https://img.shields.io/badge/-MediaPipe-white?style=flat-square&logo=Clyp)](https://mediapipe.dev/)


### Drawing on a virtual canvas using hand pose estimation

![](imgs/demo.gif)


## Libraries used
- PyTorch 
- Mediapipe 
- OpenCV


To test the whiteboard, run `main.py`.

- Clenching a fist with your index finger sticking out allows you to **draw**.

<img src ="imgs/draw.png" width="260px" />

- Closing your hand into a fist allows you to **erase**, where the red box represents the bounds of the eraser.

<img src ="imgs/erase.png" width="260px" />

- Holding your hand with all of your fingers open does nothing.

<img src ="imgs/none.png" width="260px" />
<hr>


