[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Facial-Expression-Recognition-with-CNNs
Facial Expression Recognition with CNNs on TensorFlow-Keras with OpenCV and Python. Flask app was used to get a web-interface to deploy the algorithm.  

![](Outputs/video1.gif)

Video source: https://www.youtube.com/watch?v=5w3cYtJekpw

Algorithm output: https://youtu.be/ojB1LSCKUpM

![](Outputs/video2.gif)

Video source: https://www.youtube.com/watch?v=B0ouAnmsO1Y

Algorithm output: https://youtu.be/jzaEGQrXRtA

# Overview

The video input can be changed to take in webcam by uncommenting one line of code. Real time perfomance depends on the hardware specifications.

# Project Requirements/ Dependencies
TensorFlow-GPU
OpenCV
Seaborn
Matplotlib
Keras
Livelossplot
Flask

# CNN model architecture

# Pipeline

# Results

![Epoch 15](Outputs/Graph_15_epoch.png)

![Epoch 15](Outputs/Graph_25_epoch.png)

![Epoch 15](Outputs/Graph_50_epoch.png)


# Command to run code
```
python main.py
```
# Certification 

Coursera certificate for the project: https://coursera.org/share/cb5b1cee88ad5ded6055c0f0c3adeaa4

# Known Issues/Bugs

The Haar Cascades are not the most robust way of identifying faces. Observed a few false face detections at times near a person's neck. A better approach would be to use DLib library for a faster and more accurate face detection. (http://dlib.net/) Would be working on Dlib library for future projects.

# References
Coursera: https://www.coursera.org/projects/facial-expression-recognition-keras

# Licence
The Repository is Licensed under the MIT License.
```
MIT License

Copyright (c) 2019 Charan Karthikeyan Parthasarathy Vasanthi, Nagireddi Jagadesh Nischal, Sai Manish V

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
