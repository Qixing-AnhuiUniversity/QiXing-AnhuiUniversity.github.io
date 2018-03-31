---
layout: post
title: My first blog
date: 2015-3-02
categories: blog
tags: [AI,motot control]
description: 。
---

this is my blog, which mainly focus on Artificail intellenge for motor control. In my post I will discuss how to use AI, such as reinforcement learning, supervised learning and so on in motor control applications. As Deepmind shows their "Deep-Q-learning" can play atari, and their "Alpha Go" can beat human in Go, I think these technologies also can be used in motor control. For example, we can design an AI to learn the best strategy to control the motor, without human effort. 


According to my idea, AI in motol control should include three key points:1,priori. 2,reinforcement learning 3, supervised learning. These are similar to Alpha Go, but in each point there some differences. For example, in supervised learning stage, Alpha Go uses Convolutional Neural Network (CNN) to learn the data, that is because 1)in Go dimentions of data  is extremely large and 2)the data is clean, which mean data contain no noise. 3) it is a classification task. However, in motor control, the features of data are :1) the data's dimention is low, so “dimentional disarster” will not come up. 2) the data contian large sum of noise. 3) it is a regression task. Based on this we should use a new supervised learning algorithm to model the motor. In my second paper (finished but not submitted), I introduce Random Forest to model the motor.

Because these days I am writing my second paper(about motor parameters online estimation based on Deep Reinforcement Learning and Random Forest), I have not much time to improve my blog. Once this paper is submitted, (I think) I will have more time to introduce something interesting in my blog.












