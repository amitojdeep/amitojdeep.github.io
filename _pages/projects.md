---
permalink: /Projects/
title: "Research Projects"
excerpt: ""
author_profile: true
fullwidth: true
redirect_from: 
---

Some of the projects that I have done in recent times are briefly described here along with links to their blog posts, reports and github repositories.

## Yoga Activity Estimation for Real Time Video <br> (_December 2017 - August 2018_)
`python` `posture estimation` `keras` `LSTM` `CNN`<br>
* The system takes estimated poses from [Openpose](https://github.com/CMU-Perceptual-Computing-Lab/openpose) and uses them to train a deep learning model for yoga posture estimation
* Achieved **99.32%** accuracy on initial data  
* Realtime implementation achieved **98.92%** accuracy
* Submitted for publication
* [_Demo_](https://drive.google.com/drive/folders/1Xc0h5e6ntYcYL13JCwfHP1PuwtrBKbpM?usp=sharing)

## Deep Convolutional Neural Networks for Traffic Sign Recognition & Detection  <br> (_June 2017 - July 2017_)
`keras` `theano` `deep learning` `gtsrb` `gtsdb` `vgg` `vgg16` <br>
* A custom 2D Convolutional Deep Learning Model inspired by VGG architecture with additional batch normalization layers was designed
*  Majority voting was applied for **ensembling** for increased robustness and accuracy
* *German Traffic Sign Recognition Benchmark* [[_GTSRB_]](http://benchmark.ini.rub.de/?section=gtsrb&subsection=news) dataset was used for comparison with state of the art techniques
* Achieved **99.38%** classification accuracy on the 43 categories of traffic signs
* Ranked **7th internationally** on the GTSRB benchmark, beating any human performance based approach and achieving results comparable to academic state of the art
* My [blog post](https://amitojdeep.github.io/amitoj-blogs/2017/12/29/traffic-sign-reco.html) explaining the model, ensembling and results along with some suggested approaches for further research
* [_Source code_](https://github.com/amitojdeep/traffic-sign-reco) [[_Report_]](https://github.com/amitojdeep/traffic-sign-reco/raw/master/Training%20Report.pdf)

## Neural Networks for Stock Price Prediction <br>(_August 2017 - December 2017_)
`python`  `keras` `multimodal` `multitask` `LSTM` `cnn` `deep learning` `financial forecasting` `stocks` `stock market`<br>
* Designed a Multimodal and Multitask Deep Learning Model to predict stock price movement and volatility
* Price History and News headlines were taken as two modalities and used as inputs to two separate LSTMs
* Outputs of both LSTMs were merged and two independent branches of dense layers were used to predict price movement direction and volatility
*  Achieved a prediction accuracy of **74.93%** for predicting price movement direction and MSE of **0.0017** for normalized volatility prediction
* Read my [blog post](https://amitojdeep.github.io/amitoj-blogs/2017/12/30/deep-stock-preds.html) for insights on this work
* [_Source code_](https://github.com/amitojdeep/deep-stock-preds) [[_Report_]](https://github.com/amitojdeep/deep-stock-preds/raw/master/Deep%20Learning%20for%20Stock%20Price%20Prediction.pdf)

## Semantic Similarity Analyzer and Predictive Typing System <br>(_October 2017- November 2017_)
`python` `keras` `Siamese LSTM` `Manhattan LSTM` `MaLSTM` `Semantic` <br>
* Used **Manhattan LSTM** to predict semantic similarity of two query phrases
* **Google word2vec** was used to generate embeddings of query phrases
* Achieved an accuracy of **80.35%** on *Quora Question Pairs Dataset*
* Semantic similarity between current sentence and sentences in the corpus was used for predictive typing
* It outperformed state of the art statistical techniques
* Read my [blog post](https://amitojdeep.github.io/amitoj-blogs/2017/12/31/semantic-similarity.html) for design, implementation and results of the Semantic Similarity Analyzer.
* [_Source code_](https://github.com/amitojdeep/predictive-typing) [[_Report_]](https://github.com/amitojdeep/predictive-typing/raw/master/report.pdf)


## Compiler Construction <br>(_January 2017 - December 2017_)
`compiler`  `programming` `languages` `C` `Data Structures`<br>
* A compiler for a language supportibg arithmetic, string and matrix operations was developed in C using hash tables, trees and stack optimally.
* Completed as a part of Compiler Construction course from Jan - May 2018 at BITS Pilani
* [_Repo_](https://github.com/amitojdeep/compiler-construction)


## ATU: Adaptive Template Update for Constructive Fingerprint Identification <br>(_January 2017 - December 2017_)
`python`  `menpo` `numpy` `scipy` `thin plate spline` `tps` `minutiae` `biometrics` `fingerprint` <br>
* Minutiae points were mosaicked using **Thin Plate Spline transformation**
* It mimiced natural deformation during registration of fingerprints and counter acted them to achieve consitency between different fingerprints of the same user
* High confidence test fingerprints were used to update the database resulting in knowledge augmentation and efficiency 
* Achieved **100% CRR** and **20% EER** for fingerprints of 100 users of *FVC 2004 database*
* [_Source code_](https://github.com/amitojdeep/fp-recognition) [[_Paper_]](https://github.com/amitojdeep/fp-recognition/raw/master/writeup.pdf)

## Smart AC System
* Designed Smart AC System using 8086 microprocessor, RAM, ROM, PPI, Timer, LCD, address latches & buffers. 
* Project was simulated successfully using Proteus
* [Source Code](Smart AC System) [_Report_](https://github.com/amitojdeep/smart-ac/raw/master/mup_report-17.pdf)

## Logic Programming using Prolog
* Logic Programming using SWI Prolog to implement Symbolic Algebra Operations
* Designed Programming logic to implement BITS Academic Regulations in Prolog
* [Project Repo](https://github.com/amitojdeep/logic-assig) with Prolog source code and documentation 

