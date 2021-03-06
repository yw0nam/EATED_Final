# EATED Program Final Codes and Report

## Theme: Make a Model that can classify digit using machine learning
This repository is about Recognizing the digit images using Neural net. <br />
All of code is using jupyter notebook and python
## Using data <br />
1. [Mnist dataset](http://yann.lecun.com/exdb/mnist/) <br />
<img src = "https://user-images.githubusercontent.com/39719936/48837585-1a48fb00-edc9-11e8-970a-c9766e89fef6.jpeg" width="60%"></img> <br />
2. [IAM HandWriting database](http://www.fki.inf.unibe.ch/databases/iam-handwriting-database)<br />
<img src="https://user-images.githubusercontent.com/39719936/48837450-bfaf9f00-edc8-11e8-9598-4d613f91efd8.png" width="60%"></img> <br /> 
3. [the chars74K  dataset](http://www.ee.surrey.ac.uk/CVSSP/demos/chars74k/) <br/>
<img src="https://user-images.githubusercontent.com/39719936/48837314-5c257180-edc8-11e8-84dc-1445086a1616.png" width="60%"></img> <br /> 
## Procedures <br />
1. Ploting the images <br />
2. Pre-processing <br />
**(If you want see the ploting images and Pre-processing, please check the code name of "ploting images")**
3. Make model <br />
4. Train the model with trainset <br />
5. Test the model with testset and show accuracy <br />
**(If you want see the accuracies of each model, please check the code name of "Digit")**

## Using Model: Deep Neural Network <br />
<img src = "https://user-images.githubusercontent.com/39719936/48716536-eb147b80-ec5a-11e8-98d5-3c4675de6e3d.png" width = "60%"> </img><br />
Using model is Fully connected Deep neural network. <br />
<br />
There is input layer, output label, and 4 hidden layer. <br />

Input Layer shape = 784 * 512  <br />
Hidden Layer 1 layer shape = 512 * 256  <br />
Hidden Layer 2 layer shape = 256 * 128 <br />
Hidden Layer 3 layer shape = 128 * 64 <br />
Hidden Layer 4 layer shape = 64  * 10 <br />
Output shape = 10 (Label shape) <br />
Number of layers :5 <br />
<br />
Learning rate = 0.001 <br />
Drop out = 0.7  <br />
<br />
Optimize algorithm: Adam optimizer  [here is the paper of optimzer](https://arxiv.org/pdf/1412.6980.pdf) 
<br />
Check accuracy: softmax cross entropy [here is the explane of this](https://kakalabblog.wordpress.com/2017/04/04/cross-entropy-%EC%A0%95%EB%A6%AC/) <br />   



## Accuracy Result <br />

<img src="https://user-images.githubusercontent.com/39719936/48708454-f1e4c380-ec45-11e8-8c19-acd6c9817402.png" width="90%"></img> <br /> 


X axis = The dataset use to train the model <br />
Y axis = The dataset use to test the model <br />

The accuracies has error ±1~2%
## Conclusion and Next plan <br />

As you can see the above graph, the accuracy isn't good. <br />
But this projcet was my first projcet of machine learning, and this project was good exprience for me. <br />
During this project, i learned how to pre-processing and make dataset from images. <br />
Furthermore, I adopt the machine learning with tensorflow, made own dateset, how to upload the files in github. <br />
This technics will be helpful for next my machine learning project. <br />
I plan next project as face recognition or reinforce learning. <br />

## Reference <br />

Sung Kim -Tensorboard code [here is github of him](https://github.com/hunkim) <br />
Professor Yongseok Yoo – Advisor [here is github of him](https://github.com/ys7yoo) <br/>
Making dataset - codes [here is the site](https://medium.com/trackin-datalabs/data-input-%EB%A7%8C%EB%93%A4%EA%B8%B0-74bb5c1ce52f) <br />
