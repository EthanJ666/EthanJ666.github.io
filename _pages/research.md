---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

## Research

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>ReMix: Optimizing Data Mixtures for Large Scale Imitation Learning</h4>

Increasingly large imitation learning datasets are being collected with the goal of training foundation models for robotics. However, despite the fact that data selection has been of utmost importance in vision and natural language processing, little work in robotics has questioned what data such models should actually be trained on. In this work we investigate how to weigh different subsets or ``domains'' of robotics datasets for robot foundation model pre-training. Concrete, we use distributionally robust optimization (DRO) to maximize worst-case performance across all possible downstream domains. Our method, Re-Mix, addresses the wide range of challenges that arise when applying DRO to robotics datasets including variability in action spaces and dynamics across different datasets. Re-Mix employs early stopping, action normalization, and discretization to counteract these issues. Through extensive experimentation on the largest open-source robot manipulation dataset, the Open X-Embodiment dataset, we demonstrate that data curation can have an outsized impact on downstream performance. Specifically, domain weights learned by Re-Mix outperform uniform weights by 38\% on average and outperform human-selected weights by 32\% on datasets used to train existing generalist robot policies, specifically the RT-X models.
</div>
</div>

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Self-driving Program Based on Adversarial Domain Adaptation Semantic Segmentation and Computer Vision</h4>

As an extension of the traditional deep learning network, semantic segmentation aims to generate a class label for each pixel in the input image, thus grouping up together pixels that possess the same semantic label. It is always one of the key topics in computer vision domain, and it is also a vital concept in building self-driving automobile systems. One problem often met in real-life semantic segmentation problem is that researchers often can't provide a large enough dataset containing all diversely different scenes around the world, causing the model to underfit. In this article we show you how we use VGG16 deep learning model to build a Fully Convolutional Network as to achieve pixel-wise semantic prediction, and how we addressed aforementioned limitation by training the model using video game scenes from GTA5. Since there are style-level discrepancies between the game scenes and the real life scenes, we utilize Adversarial Domain Adaptation to overcome problems caused by such domain shifts and to make the model perform better when working in real life scenes.
</div>
</div>
