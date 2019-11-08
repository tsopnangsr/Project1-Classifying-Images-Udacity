# Project1-Classifying-Images-Udacity
Classifying Images - Learn how to use a pre-trained CNN image classifier to write a script that identifies whether images are of dogs. If the image is identified as a dog, your program will identify the dog's breed.

## Principle Objectives
Below you will find the principle objectives, a summary of the results, and discussion as to how check_images.py achieved these four objectives.

# Objectives
1. Correctly identify which pet images are of dogs (even if breed is misclassified) and which pet images aren't of dogs.

2. Correctly classify the breed of dog, for the images that are of dogs.

3. Determine which CNN model architecture (ResNet, AlexNet, or VGG), "best" achieve the objectives _1_ and _2_.

4. Consider the time resources required to best achieve objectives _1_ and _2_, and determine if an alternative solution would have given a "good enough" result, given the amount of time each of the algorithms takes to run.

## Prerequisites
install Anaconda
Step by step process here:
https://www.digitalocean.com/community/tutorials/how-to-install-anaconda-on-ubuntu-18-04-quickstart

Install pytorch torchvision using Anaconda
```
conda install pytorch torchvision cudatoolkit=10.1 -c pytorch
```

## Running All the models : vgg, Alexnet, Resnet
To run file run_models_batch.sh in the workspace, open a terminal window (in Unix/Linux/OSX/Lab Workspace) and type the following:
```
sh run_models_batch.sh
```
## Results Table on 40 images dataset

<p align="center"> <img src="running-results.png"/> </p>


Copyright, All right reserved. by Romaric Tsopnang.
