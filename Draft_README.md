# REVIEW_PAPER
Summaries and implementations of papers on **deep learning**, **quantitative investing** and **parallel distributed processing**.

> **Please note that these reviews are for my future self to look back and remember the materials on this paper without reading it all over again.**
>
> Thank you.

>  **Some reviews are in daft. It will be finished with in a month :)**

# Deep Learning

### Convolutional Neural Network(CNN)

### Generative Adversarial Network(GAN)

- Generative Adversarial Nets 2014

### Recurrent Neural Network(RNN)

### Reinforcement Learning(RL)

- **Policy Gradient Methods for Reinforcement Learning with Function Approximation**. [Paper](https://papers.nips.cc/paper/1713-policy-gradient-methods-for-reinforcement-learning-with-function-approximation.pdf) [Review & Implementation](https://github.com/bohblue2/Policy-Gradient-Methods-for-Reinforcement-Learning-with-Function-Approximation)

  Richard S. Sutton, David McAllester, Satinder Singh, Yishay Mansour, NIPS, 2000

  > Vanilla Policy Gradient

- Simple Statistical Gradient-Following Algorithms for Connectionist Reinforcement Learning. [Paper](https://doi.org/10.1007/BF00992696) [Implementation](https://github.com/bohblue2/Simple-Statistical-Gradient-Following-Algorithms-for-Connectionist-Reinforcement-Learning)

  Ronald J. Williams, Mach Learn, 1992

  > Mente-Carlo Policy Gradient: REINFORCE

- Playing Atari with Deep Reinforcement Learning. [Paper](https://arxiv.org/abs/1312.5602) [Review & Implementation](https://github.com/bohblue2/Playing-Atari-with-Deep-Reinforcement-Learning)

  Volodymyr Mnih, Koray Kavukcuoglu, David Silver, Alex Graves, Ioannis Antonoglou, Daan Wierstra,  Martin Riedmiller, ArXiv, 2013 

- Human-level control through deep reinforcement learning. [Paper](https://www.nature.com/articles/nature14236) [Review & Implementation](https://github.com/bohblue2/Human-level-control-through-deep-reinforcement-learning)

  Volodymyr Mnih, Koray Kavukcuoglu, David Silver, Andrei A. Rusu, Joel Veness, Marc G. Bellemare, Alex Graves, Martin Riedmiller, Andreas K. Fidjeland, Georg Ostrovski, Stig Petersen, Charles Beattie, Amir Sadik, Ioannis Antonoglou, Helen King, Dharshan Kumaran, Daan Wierstra, Shane Legg & Demis Hassabis, Nature, 2015

- Deep Reinforcement Learning with Double Q-learning. [Paper](https://arxiv.org/abs/1509.06461) [Review & Implementation](

  Hado van Hasselt, Arthur Guez, David Silver, NIPS, 2015

- Dueling Network Architectures for Deep Reinforcement Learning. [Paper](https://arxiv.org/abs/1511.06581) [Review & Implementation](

  Ziyu Wang, Tom Schaul, Matteo Hessel, Hado van Hasselt, Marc Lanctot, Nando de Freitas, ArXiv, 2015

  > http://bluediary8.tistory.com/9
  >
  > http://mlg.postech.ac.kr/~readinglist/slides/20161011.pdf

- Prioritized Experience Replay. [Paper](https://arxiv.org/abs/1511.05952) [Review & Implementation](

  Tom Schaul, John Quan, Ioannis Antonoglou, David Silver, ICLR, 2016

- Asynchronous Methods for Deep Reinforcement Learning. [Paper](https://arxiv.org/abs/1602.01783v2) [Review & Implementation](https://github.com/bohblue2/Asynchronous-Methods-for-Deep-Reinforcement-Learning)

  Volodymyr Mnih, Adrià Puigdomènech Badia, Mehdi Mirza, Alex Graves, Tim Harley, Timothy P. Lillicrap, David Silver, Koray Kavukcuoglu, ICML, 2016

  > https://hackernoon.com/intuitive-rl-intro-to-advantage-actor-critic-a2c-4ff545978752
  >
  > http://openresearch.ai/t/a3c-asynchronous-methods-for-deep-reinforcement-learning/25

- Reinforcement Learning through Asynchronous Advantage Actor-Critic on a GPU. [Paper](https://arxiv.org/abs/1611.06256v3) [Review](

  Mohammad Babaeizadeh, Iuri Frosio, Stephen Tyree, Jason Clemons, Jan Kautz, NIPS, 2016

  > https://openreview.net/forum?id=r1VGvBcxl

- Continuous Deep Q-Learning with Model-based Acceleration. [Paper](https://arxiv.org/abs/1603.00748) [Review & Implementation](

  Shixiang Gu, Timothy Lillicrap, Ilya Sutskever, Sergey Levine, ICML, 2016

- Anticipatory Asynchronous Advantage Actor-Critic (A4C)

- Distributional Advantage Actor-Critic (DA2C)

- ACER

- ACKTR

- DPG

- DDPG

- NPG

- TRPO

- GAE

- PPO

- Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments. [Paper](https://papers.nips.cc/paper/7217-multi-agent-actor-critic-for-mixed-cooperative-competitive-environments.pdf) [Review & Implementation](

  Ryan Lowe, Yi Wu, Aviv Tamar, Jean Harb, Pieter Abbeel, Igor Mordatch, NIPS, 2017

  > http://www.modulabs.co.kr/DeepLAB_Paper/15445

- Hierarchical Deep Reinforcement Learning (HDQN) 

### AutoEncoder(AE) 

### Others(Optimization, Regularization, ...) 

- Geometry of energy landscapes and the optimizability of deep neural networks. [Paper](https://arxiv.org/abs/1808.00408) [Review](https://github.com/bohblue2/Geometry-of-energy-landscapes-and-the-optimizability-of-deep-neural-networks)

  Simon Becker, Yao Zhang, Alpha A. Lee, ArXiv, 2018

- Visualizing Data using t-SNE [Paper](http://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf) [Review & Implementation](https://github.com/bohblue2/Visualizing-Data-using-t-SNE)

  Laurens van der Maaten, Geoffrey Hinton, Journal of Machine Learning Research, 2008

- Batchnorm

- Relu

- Accurate, Large Minibatch SGD: Training ImageNet in 1 Hour

  > https://arxiv.org/abs/1706.02677
  >
  > https://hma02.github.io/AllanMa/assets/pdf/2017-7-31-imagenet-in-1h.pdf

- Overview of popular gradient optimization methods.

- L1, L2, Huber Loss



# Deep Learning, Applied to Finance

This category focuses on **stock price (or fundamentals) prediction** from long-term or short-term perspective, **efficient asset management** (**portfolio optimization** and **dynamic asset allocation**) using deep learning.

https://paperswithcode.com/search?q=stock

- Improving Factor-Based Quantitative Investing by Forecasting Company Fundamentals. [Paper](https://arxiv.org/abs/1711.04837) [Review](https://github.com/bohblue2/Improving-Factor-Based-Quantitative-Investing-by-Forecasting-Company-Fundamentals)

  John Alberg, Zachary C. Lipton, ArXiv, 2018

- Convolutional Neural Networks Applied to High-Frequency Market Microstructure Forecasting. [Paper](https://ieeexplore.ieee.org/document/8101595/) [Review](https://github.com/bohblue2/Convolutional-Neural-Networks-Applied-to-High-Frequency-Market-Microstructure-Forecasting)

  J. Doering, M. Fairbank, and S. Markose, CEEC, 2017

- A Deep Reinforcement Learning Framework for the Financial Portfolio Management Problem. [Paper](https://arxiv.org/abs/1706.10059) [Reivew](https://github.com/bohblue2/A-Deep-Reinforcement-Learning-Framework-for-the-Financial-Portfolio-Management-Problem)

  Zhengyo Jiang, Dixing Xu, Jinjun Liang, ArXiv, 2017

  > https://github.com/bohblue2/rl-portfolio-management
  >
  > https://github.com/bohblue2/PGPortfolio
  >
  > https://github.com/qq303067814/Reinforcement-learning-in-portfolio-management-	

- A deep learning framework for financial time series using stacked autoencoders and long-short term memory. [Paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0180944) [Review](https://github.com/bohblue2/A-deep-learning-framework-for-financial-time-series-using-stacked-autoencoders-and-long-short-term-m)

   Wei Bao, Jun Yue, Yulei Rao, PLOS, 2017

- Deep Direct Reinforcement Learning for Financial Signal Representation and Trading. [Paper](https://ieeexplore.ieee.org/document/7407387/) [Review](https://github.com/bohblue2/Deep-Direct-Reinforcement-Learning-for-Financial-Signal-Representation-and-Trading)

   Yue Deng, Feng Bao, Youyong Kong, Zhiquan Ren, and Qionghai Dai, Senior Member, IEEE, 2017

- ##### Stock Price Correlation Coefficient Prediction with ARIMA-LSTM Hybrid Model

   > https://arxiv.org/abs/1808.01560v5
   >
   > https://github.com/imhgchoi/Corr_Prediction_ARIMA_LSTM_Hybrid

- #####  A Machine Learning Framework for Stock Selection 

- 괜찮은 논문이 있어서 올립니다~ Methodology만 가져와도 좋을듯 합니다. (1) paper : <https://arxiv.org/abs/1808.01560v5> source code: <https://github.com/imhgchoi/Corr_Prediction_ARIMA_LSTM_Hybrid> (2) <https://arxiv.org/abs/1806.01743v2>

- https://github.com/fxy96/Stock-Selection-a-Framework> 



# Quantitative Investing

These are for learning domain knowledge.



# Parallel Distributed Processing

I'm studying this field just for fun! it is interesting! isn't it Sir?

> https://towardsdatascience.com/how-to-rapidly-test-dozens-of-deep-learning-models-in-python-cb839b518531

- Impala
- ape-x
- relaax (REinforcement Learning Algorithms, Autoscaling and eXchange (RELAAX))