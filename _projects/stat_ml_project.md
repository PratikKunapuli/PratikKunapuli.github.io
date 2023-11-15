---
layout: page
title: Reinforcement Learning for Dynamical Systems
description: Class project for ECE 6254 - Statistical Machine Learning
importance: 1
category: classes
---

In this project, we survey a variety of reinforcement learning (RL) techniques and study them in the context of dynamical systems; specifically, we address the cart-pole problem. In general, RL algorithms achieve their goal by observing a system’s state and executing an action based on the expected reward given by the environment. We perform a review of RL literature highlighting existing approaches. For brevity, we limit our survey to literature relevant to dynamical systems. Furthermore, we implement a series of RL algorithms using the OpenAI’s Gym and Pytorch. Specifically, we implement 1) a basic algorithm countering pole motion, 2) policy gradient utilizing a two-layer neural network, 3) deep Q-learning backed by a three-layer neural network, and 4) model predictive control (MPC). To conclude, we compare the individual performance of the the RL techniques against the results of the MPC.

Read the full report [here](/assets/pdf/stat_ml_project.pdf)