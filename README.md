# HeightMapPathLossPrediction
## Regression of large-scale path loss parameters using deep neural networks

### Abstract
Path loss exponent and shadowing factor are among important wireless channel parameters. These parameters can be estimated using field measurements or ray-tracing simulations, which are costly and time-consuming. In this work, we take a  deep neural network-based approach, which takes either satellite image or height map of a target region as input and estimates the desired channel parameters. We use the well-known VGG-16 architecture, pre-trained on the ImageNet dataset, as the backbone to extract image features, modify it as a regression network to produce channel parameters, and re-train it on our dataset, which consists of satellite image or height map as input and channel parameters as target values. We demonstrate that deep networks can be successfully utilized in estimating path loss exponent and shadowing factor of a region, simply from the region's satellite image or height map.  

### Method
The VGG-16 model is used for predicting path loss exponent component(n) and shadowing factor(σ).
Trained model weights and VGG-16 model are giving in this google drive link: https://drive.google.com/drive/folders/114YvDyYIZZs5nFH9Ff20K1Y7ejZLrnqc?usp=sharing
and the testing code can be found in this repo as jupyter-notebook file named as Testing_HeightMap.ipynb

![github](https://user-images.githubusercontent.com/50488198/158435603-1ac89b6d-a0d0-44d0-9678-6aa9b19d0264.PNG)

### Results
Prediction of path loss exponent and shadowing factor for test samples can be seen below.

![githubresults](https://user-images.githubusercontent.com/50488198/159015248-72eb96df-f3c3-4bf1-a564-3c8dae8a2325.PNG)

### Authors Info
Mustafa BAL - mstfbal7@gmail.com
Ahmed Nageeb MAREY
Hasan Fehmi Ateş
Tuncer Baykaş
Bahadır Kürşad Güntürk

![Github stats 1](https://github-readme-stats.vercel.app/api?username=MstfBal&show_icons=true&theme=gradient) 
![Github stats 2](https://github-readme-stats.vercel.app/api?username=MstfBal&show_icons=true&theme=radical)


