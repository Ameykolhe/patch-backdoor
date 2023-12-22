# EL-GY-9163: Machine Learning for Cyber-security 
# PatchBackdoor: A stealthy threat to Deep Learning systems in safety-critical environments


NYU Tandon School of Engineering


## Overview

This repository contains all code used for the completion of the Final Project. 
Instead of introducing backdoor logic during training or model editing, we propose aan approach involving the insertion of a meticulously crafted patch, referred to as a backdoor patch, in front of the camera. This patch, fed into the model alongside input images, can be trained to exhibit normal behavior under typical circumstances but produce incorrect predictions when the input image features an attacker-controlled trigger condition. In this work, we perform PatchBackdoor attacks on popular deep learning models such as VGG-16, MobileNet-v2, ResNet- 50) on different datasets (Imagenettete, CIFAR-10) with an impressive attack success ranging from 83% to 99%. Furthermore, we also comment on the attack’s response to defense, specifically pruning.

## Environment
We evaluated the training efficiency of our attack on New York University High Performance Computing resources and Colab Pro, which provides NVIDIA Tesla V100 PCle and NVIDIA Tesla T4 Graphic support.


## How To Run

* Download CIFAR-10, Imagenette datasets.

* Retrieve the models by accessing [Google Drive](https://drive.google.com/drive/folders/19NDLHRXtt8O1cXOoBDEP7DBiv6v37jx9?usp=share_link)

* All notebooks located in src.

* Initiate a Jupyter Notebook session on NYU HPC (or Colab)

* Launch the provided Jupyter notebook within the environment.

* Modify file locations within the notebook to establish connections with the dataset and badnet model.

* Run the notebook to execute the code with the specified configurations.










