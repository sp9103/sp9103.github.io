---
layout: post
title:  "Deep Learning based on Human Supervision for Robotic Grasping"
date:   2016-10-12 17:30:00
---
Abstract
 Recently, a few researchers have developed prominent robotic grasp systems using self-supervised deep learning techniques. However, in this paper, we investigate methods of learning a grasp network, comparable to the outstanding methods, based on human supervision. To the best of our knowledge, this is first attempt to train a deep neural network for grasping using direct teaching by a human supervisor. Human annotation can apparently eliminate random trials of the robot that occur in reinforcement learning or selfsupervised learning. However, a large amount of training data is still necessary in the presence of various poses for seen and unseen objects. This requirement makes direct annotation by a human, which is usually conducted using typical kinesthetic teaching, difficult to be employed. To overcome the difficulty of data collection when standard kinesthetic teaching is used, we develop another deep convolutional neural network called the visual inverse kinematics network. This network enables a human supervisor to gather a massive training data set for the grasp network with much less time and human effort. The learned grasp network incorporates visual feedback from an RGB-D camera to continuously produce joint angles so as to achieve a successful grasp.

![_config.yml]({{ site.baseurl }}/PDF/Deep Learning based on Human Supervision for Robotic Grasping.jpg)<br>
