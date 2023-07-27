# MGCN: Multi-View Graph Convolutional Network for Multimedia Recommendation
![GitHub forks](https://img.shields.io/github/forks/demonph10/MGCN?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/demonph10/MGCN?style=social)
![Packagist Stars](https://img.shields.io/packagist/stars/demonph10/MGCN)

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/demonph10/MGCN">
    <img src="image/logo.svg" alt="Logo" width="80" height="80">
  </a>
</div>

## Introduction

This is the Pytorch implementation for our MM 2023 paper:

>MM 2023. Penghang Yu, Zhiyi Tan, Guanming Lu, Bing-Kun Bao(2023). Multi-View Graph Convolutional Network for Multimedia Recommendation
<img src="image/framework.png" width="804px" height="306px"/>

## Enviroment Requirement
- python 3.8
- Pytorch 1.12

## Dataset

We provide three processed datasets: Baby, Sports and Clothing.

Download from Google Drive: [Baby/Sports/Clothing](https://drive.google.com/file/d/1tpP-IQtUubSlVvYpkA61bffPKkhvT62T/view?usp=drive_link)

* Please move your downloaded data into this dir for model training.

## Training
  ```
  cd ./src
  python main.py
  ```

## Citing MGCN
If you find MGCN useful in your research, please consider citing our paper:
***

The code is released for academic research use only. For commercial use, please contact [Penghang Yu](y463213402@gmail.com).


## Acknowledgement
The structure of this code is  based on [MMRec](https://github.com/enoche/MMRec). Thank for their work.