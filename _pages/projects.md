---
permalink: /Projects/
title: ""
excerpt: ""
author_profile: true
fullwidth: true
redirect_from: 
---

## Neural Networks for Stock Price Prediction <br>(_August 2017 - December 2017_)
`python`  `keras` `multimodal` `multitask` `LSTM` `cnn` `deep learning` `financial forecasting` `stocks` `stock market`<br>
* Designed a Multimodal and Multitask Deep Learning Model to predict stock price movement and volatility
* Price History and News headlines were taken as two modalities and used as inputs to two separate LSTMs
* Outputs of both LSTMs were merged and two independent branches of dense layers were used to predict price movement direction and volatility
*  Achieved a prediction accuracy of **74.93%** for predicting price movement direction and MSE of **0.0017** for normalized volatility prediction
* [[_Source code_]](https://github.com/amitojdeep/deep-stock-preds) [[Report]](https://github.com/amitojdeep/deep-stock-preds/blob/master/Deep%20Learning%20for%20Stock%20Price%20Prediction.pdf)

## Deep Convolutional Neural Networks for Traffic Sign Recognition & Detection  <br> (_June 2017 - July 2017_)
`keras` `theano` `deep learning` `gtsrb` `gtsdb` `vgg` `vgg16` <br>
* A custom 2D Convolutional Deep Learning Model inspired by VGG architecture with additional batch normalization layers was designed
*  Majority voting was applied for *ensembling* for increased robustness and accuracy
* *German Traffic Sign Recognition Benchmark* [[_GTSRB_]](http://benchmark.ini.rub.de/?section=gtsrb&subsection=news) dataset was used for comparing with state of the art techniques
* Achieved 99.38% classification accuracy on the 42 categories of traffic signs
* Ranked 7th internationally on the GTSRB benchmark, beating any human performance based approach and being comparable to academic state of the art.
* [[_Source code_]](https://github.com/amitojdeep/traffic-sign-reco) [[Report]](https://github.com/amitojdeep/traffic-sign-reco/blob/master/Training%20Report.pdf)


## ATU: Adaptive Template Update for Constructive Fingerprint Identification <br>(_January 2017 - December 2017_)
`python`  `menpo` `numpy` `scipy` `thin plate spline` `tps` `minutiae` `biometrics` `fingerprint` <br>
* Minutiae points were mosaicked using **Thin Plate Spline transformation**
* It mimiced natural deformation during registration
* High confidence test fingerprints were used to update the database to improve the accuracy 
* Achieved **100% CRR** and **20% EER** for fingerprints of 100 users of *FVC 2004 database*
* [[_Source code_]](https://github.com/amitojdeep/fp-recognition) [[Paper]](https://github.com/amitojdeep/fp-recognition/blob/master/writeup.pdf)

## Semantic Similarity Analyzer and Predictive Typing System <br>(_October 2017- November 2017_)
`python` `keras` `Siamese LSTM` `Manhattan LSTM` `MaLSTM` `Semantic` <br>
* Used **Manhattan LSTM** to predict semantic similarity of two query phrases
* **Google word2vec** was used to generate embeddings of query phrases
* Achieved an accuracy of **80.35%** on *Quora Duplicate Questions Dataset*
* Semantic similarity between current sentence and sentences in corpus was used for predictive typing
* It outperformed state of the art statistical techniques for Predictive Typing
* [[_Source code_]](https://github.com/amitojdeep/predictive-typing) [[Report]] (https://github.com/amitojdeep/predictive-typing/blob/master/report.pdf)

## Multiperson Pose Estimation for Real Time Video <br> (_Ongoing_)
`python` `vgg` `vgg19` `posture estimation` `keras` `android` <br>
* Ongoing project for current semester
* Using VGG 19 outputs of video frame by frame to extract key points and match them using Part Affine Fields
* Implementing the system on android based device for practical application

## Smart AC System
* Designed Smart AC System using 8086 microprocessor, RAM, ROM, PPI, Timer, LCD, address latches & buffers. 
* Project was simulated successfully using Proteus
* [[Source Code]](Smart AC System) [[Report]](https://github.com/amitojdeep/smart-ac/blob/master/mup_report-17.pdf)

## Logic Programming using Prolog
* Logic Programming using SWI Prolog to implement Symbolic Algebra Operations
* Designed Programming logic to implement BITS Academic Regulations in Prolog
* [Project Repo](https://github.com/amitojdeep/logic-assig) with Prolog source code and documentation 

