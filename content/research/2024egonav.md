---
title: "EgoNav: Egocentric Scene-aware Human Trajectory Prediction"
date: 2024-08-02T00:00:00-06:00
draft: false
---

**Abstract:**
Wearable collaborative robots stand to assist human wearers who need fall prevention assistance or wear exoskeletons. Such a robot needs to be able to predict the ego motion of the wearer based on egocentric vision and the surrounding scene. In this work, we leveraged body-mounted cameras and sensors to anticipate the trajectory of human wearers through complex surroundings. To facilitate research in ego-motion prediction, we have collected a comprehensive walking scene navigation dataset centered on the user's perspective. We present a method to predict human motion conditioning on the surrounding static scene. Our method leverages a diffusion model to produce a distribution of potential future trajectories, taking into account the user's observation of the environment. We introduce a compact representation to encode the user's visual memory of the surroundings, as well as an efficient sample-generating technique to speed up real-time inference of a diffusion model. We ablate our model and compare it to baselines, and results show that our model outperforms existing methods on key metrics of collision avoidance and trajectory mode coverage.

**Authors:** _Weizhuo(Ken) Wang_, C. Karen Liu, Monroe Kennedy III

**Links:**
- [Website](http://mmego.weizhuowang.com)
- [Paper](https://arxiv.org/pdf/2403.19026)
- [Video](https://www.youtube.com/watch?v=wtjqA_oGn0s)