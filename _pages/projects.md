---
permalink: /Projects/
title: ""
excerpt: ""
author_profile: true
fullwidth: true
redirect_from: 
---

## Neural Networks for Stock Price Prediction <br>(_August - December 2017_)
`python`  `keras` `multimodal` `multitask` `LSTM` `cnn` `deep learning` `financial forecasting` `stocks` `stock market`<br>
* Designed a Multimodal and Multitask Deep Learning Model to predict stock price movement and volatility
* Price History and News headlines were taken as two modalities and used as inputs to two separate LSTMs
* Outputs of both LSTMs were merged and two independent branches of dense layers were used to predict price movement direction and volatility
*  Achieve a prediction accuracy of **74.93%** for predicting price movement direction and MSE of **0.0017** for normalized volatility prediction
* Detailed note of methodology followed is presented in the [**_project blog_**](//blog link).<br>[[_Source code_]](//link)

## ATU: Adaptive Template Update for Constructive Fingerprint Identification <br>(_February - December 2017_)
`python`  `menpo` `numpy` `scipy` `thin plate spline` `tps` `minutiae` `biometrics` `fingerprint` <br>
* Minutiae points were mosaicked using **Thin Plate Spline transformation**
* It mimiced natural deformation during registration
* High confidence test fingerprints were used to update the database to improve the accuracy 
* Achieved **100% CRR** and **20% EER** for fingerprints of 100 users of *FVC 2004 database*

## Semantic Similarity Analyzer and Predictive Typing System <br>(_November 2017_)
`python` `keras` `Siamese LSTM` `Manhattan LSTM` `MaLSTM` `Semantic` <br>
* Used **Manhattan LSTM** to predict semantic similarity of two query phrases
* **Google word2vec** was used to generate embeddings of query phrases
* Achieved an accuracy of **80.35%** on *Quora Duplicate Questions Dataset*
* Semantic similarity between current sentence and sentences in corpus was used for predictive typing
* It outperformed atate of the art statistical techniques for Predictive Typing
* Source Code for the project can be found [[_Source code_]](https://github.com/amitojdeep/predictive-typing)

## Multiperson Pose Estimation for Real Time Video <br> (_January 2018 - _)
`python` `vgg` `vgg19` `posture estimation` `keras` <br>
* Ongoing project for current semester
* Using VGG 19 outputs of video frame by frame to extract key points and match them using Part Affine Fields
* Implementing the system on android based device for practical application
