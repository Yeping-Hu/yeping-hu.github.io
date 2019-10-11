---
title: "Research"
permalink: /research/
author_profile: true

---

My research consists of <u>behavioral prediction</u>, <u>motion planning</u> and <u>decision making</u>. 

<div style="text-align: justify">My research goal is to develop reliable prediction algorithms that can be used on the autonomous vehicle or other autonomous agents.  A reliable algorithm, from my perspective, should have the following properties: stable, interpretable, and adaptable. In fact, although motion planning and decision making are lower modules of prediction, it is important to consider the integration and relationships among these modules while formulating the prediction problem. Only in this way, can we make sure that the predicted results are useful and can make positive effects on the lower modules of the autonomous driving system. </div>

## Behavioral Prediction

- **Incorporate planning-based method into prediction:** [[paper]](https://arxiv.org/pdf/1907.10170.pdf){:target="_blank"}

  <img src="../images/CVAE_IRL.png" width="800"  >

  <div style="text-align: justify">A deep learning model based on conditional variational auto-encoder (CVAE) and an optimal planning framework based on inverse reinforcement learning (IRL) are dynamically combined to predict both irrational and rational behavior of the vehicles. Benefiting from the the HD semantic information, features for the deep learning model were defined in Frenet frame, which generated much better
    prediction performance in terms of generalization. </div>

- **Explore the multi-modality and interpretability of prediction problems:** [[paper]](https://arxiv.org/pdf/1903.09381.pdf){:target="_blank"}

  <img src="../images/latent_space.png" width="800"  >

  <div style="text-align: justify">As the predicted horizon becomes longer, modeling prediction uncertainties and multi-modal distributions over future sequences will turn into a more challenging task. We addressed this challenge by presenting a multi-modal probabilistic prediction approach. The proposed method is based on a generative model and is capable of jointly predicting sequential motions of each pair of interacting agents. Most importantly, our model is interpretable, which can explain the underneath logic as well as obtain more reliability to use in real applications. A complicate real-world roundabout scenario is utilized to implement and examine the proposed method.</div>

- **Semantic intention and motion prediction:** [[paper1]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8500419){:target="_blank"}[[paper2]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8569943){:target="_blank"}[[video]](https://youtu.be/6A3Hl-mRhbI){:target="_blank"}

  

  <img style="float: left; margin-right: 40px;" src="../images/SIMP.png" width="200" />

  <div style="text-align: justify">We proposed a Semantic-based Intention and Motion Prediction (SIMP) method, which can be adapted to any driving scenarios by using semantic-defined vehicle behaviors. It utilizes a probabilistic framework based on deep neural network to estimate the intentions, final locations, and the corresponding time information for surrounding vehicles. An exemplar real-world scenario was used to implement and examine the proposed method.</div><br clear="left"/>

## Decision Making

- **Strategic decision making:** [[paper](https://arxiv.org/pdf/1904.06025.pdf){:target="_blank"}\]\[[video](https://youtu.be/2CTTFHDW1ec){:target="_blank"}\]

  <img src="../images/merge.png" width="800" />

  <div style="text-align: justify">We proposed an interaction-aware decision making with adaptive strategies (IDAS) approach that can let the autonomous vehicle negotiate the road with other drivers by leveraging their cooperativeness under merging scenarios. A single policy is learned under the multi-agent reinforcement learning (MARL) setting via the curriculum learning strategy, which enables the agent to
    automatically infer other drivers’ various behaviors and make decisions strategically. </div>

