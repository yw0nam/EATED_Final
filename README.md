# EATED Program Final Codes and Report

## Theme: Make a Model that can classify digit using machine learning
This repository is about Recognizing the digit images using Neural net. <br />
All of code is using jupyter notebook and python
## Using data <br />
1. [Mnist dataset](http://yann.lecun.com/exdb/mnist/) <br />
2. [IAM HandWriting database](http://www.fki.inf.unibe.ch/databases/iam-handwriting-database)<br />
3. [the chars74K  dataset](http://www.ee.surrey.ac.uk/CVSSP/demos/chars74k/)

## Procedures <br />
1. Ploting the images <br />
2. Pre-processing <br />
**(If you want see the ploting images and Pre-processing, please check the code name of ploting images)**
3. Make model <br />
4. Train the model with trainset <br />
5. Test the model with testset and show accuracy <br />
**(If you want see the accuracies of each model, please check the code name of Digit)**

## Using model <br />
<img src = "https://user-images.githubusercontent.com/39719936/48716536-eb147b80-ec5a-11e8-98d5-3c4675de6e3d.png" width = "60%"> </img><br />

First data shape = 784 (image shape) <br />
Layer 1 data shape = 512  <br />
Layer 2 data shape = 256  <br />
Layer 3 data shape = 128  <br />
Layer 4 data shape = 64 <br />
Layer 5 data shape = 10 (Label shape) <br />
Number of layers :5 <br />
<br />
Optimize algorithm: Adam optimizer <br />
Check accuracy: softmax cross entropy <br />



## Accuracy Result <br />

<img src="https://user-images.githubusercontent.com/39719936/48708454-f1e4c380-ec45-11e8-8c19-acd6c9817402.png" width="90%"></img> <br />

## Reference <br />

Sung Kim -Tensorboard code [here is github of him](https://github.com/hunkim) <br />
Professor Yongseok Yoo – Advisor [here is github of him](https://github.com/ys7yoo) <br/>
Making dataset - codes[here is the site](https://medium.com/trackin-datalabs/data-input-%EB%A7%8C%EB%93%A4%EA%B8%B0-74bb5c1ce52f) <br />
