---
layout: page
title: ""
---

### Time series classification on Neuron Spiking sequences

The data consisted of spiking sequences of a single neuron in the brain of a rat. Each value corresponded to the time passed since the last spike. The goal was to write a performant binary classification model saying whether the rat was awake or asleep (based on a single neuron!). To this end, we implemented a nearest neighbor algorithm based on the Dynamic Time Warping distance and a Time Series Forest algorithm. 

### Computer vision with Pytorch (classification and segmentation)

We trained an image segmentation model on drone images taken after Hurricane Harvey. The goal was to classify each pixel into one of 26 categories. By using a similar model, help services could get to know the state of an area that was hit by a hurricane even before getting there physically. The below pictures show the original image, and the prediction of our model. 

<div style="display: flex;">
  <div style="flex: 1;">
    <img src="/imgs/mask.png" alt="Mask" width="150" height="150">
  </div>
  <div style="flex: 1;">
    <img src="/imgs/prediction.png" alt="Prediction" width="150" height="150">
  </div>
</div>


### Multi-Agent Reinforcement Learning

We implemented a PettingZoo environment in which two agents interacted in a game of hide-and-seek. We used simple Q-learning algorithms, but started to observe interesting behavior, such as the seeker locking the hider in. A picture representing that behavior is shown below. 

<div style="display: flex;">
  <div style="flex: 1;">
    <img src="/imgs/cornering.png" alt="Cornering behavior" width="150" height="150">
  </div>
</div>

### Graph Neural networks for node classification and link prediction

We used graph neural networks (Graph Attention and Convolution) to explore the Spotify Database. The network consisted of artists that were linked in case they had collaborated on a song. Using this, we set out to predict an artists' genre, their popularity and we even tried to predict future collaborations.  