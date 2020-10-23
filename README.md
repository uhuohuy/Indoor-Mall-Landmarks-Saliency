# Data-driven approach to learning salience models of indoor landmarks by using genetic programming
By Xuke Hu, Lei Ding, Jianga Shang, Hongchao Fan, Tessio Novack, Alexey Noskov, Alexander

## Introduction

This paper addresses the problem of determining the 
most salient landmark from several candidates at decision 
points in landmark-based way-finding. Our method significantly 
outperforms existing methods and achieves around 76% precision.
This accuracy rate is considerably higher than the ones achieved 
by conventional linear models. To learn more, please refer to our paper(https://www.tandfonline.com/doi/full/10.1080/17538947.2019.1701109)

## Code
The code is under "code/" folder. 
The code is implemented by Matlab R2018a.
The algorithm is based on GPTIPS Symbolic Machine Learning Platform 
for MATLAB (https://sites.google.com/site/gptips4matlab/home)

## Data
Our data is under "data/" folder, in which all the scene images with marked landmarks are listed. Detailed information of each landmark is given in landmarkDataSets.xlsx

## Usage
The main function is in Main_fold_5cross_validation.m. Just run this file to get the result.

## Contact
Comments, queries and bug reports are appreciated.
Email: xuke.hu1386@gmail.com or mylovedinglei@gmail.com
