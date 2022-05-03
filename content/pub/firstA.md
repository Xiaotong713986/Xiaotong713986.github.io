---
title: "Learning to Explore Intrinsic Saliency for Stereoscopic Video"
date: 2022-04-29T13:52:43+08:00
paperDate: "2019"
author: "Qiudan Zhang, Xu Wang*, Shiqi Wang, Shikai Li, Sam Kwong, Jianmin Jiang"
PublishName: "IEEE Conference on Computer Vision and Pattern Recognition (CVPR2019)"
Description: "In this paper, we devise a saliency prediction model for stereoscopic videos that learns to explore saliency inspired by the component-based interactions including spatial, temporal, as well as depth cues. The model first takes advantage of specific structure of 3D residual network (3D-ResNet) to model the saliency driven by spatio-temporal coherence from consecutive frames. Subsequently, the saliency inferred by implicit-depth is automatically derived based on the displacement correlation between left and right views by leveraging a deep convolutional network (ConvNet). Finally, a component-wise refinement network is devised to produce final saliency maps over time by aggregating saliency distributions obtained from multiple components. In order to further facilitate research towards stereoscopic video saliency, we create a new dataset including 175 stereoscopic video sequences with diverse content, as well as their dense eye fixation annotations. Extensive experiments support that our proposed model can achieve superior performance compared to the state-of-the-art methods on all publicly available eye fixation datasets."
PDFLink: ""
CodeLink: ""
Tags: []
Categories: []
Pic: "/firstA/Arch_overview.jpg"
---
# Abstrat
In this paper, we devise a saliency prediction model for stereoscopic videos that learns to explore saliency inspired by the component-based interactions including spatial, temporal, as well as depth cues. The model first takes advantage of specific structure of 3D residual network (3D-ResNet) to model the saliency driven by spatio-temporal coherence from consecutive frames. Subsequently, the saliency inferred by implicit-depth is automatically derived based on the displacement correlation between left and right views by leveraging a deep convolutional network (ConvNet). Finally, a component-wise refinement network is devised to produce final saliency maps over time by aggregating saliency distributions obtained from multiple components. In order to further facilitate research towards stereoscopic video saliency, we create a new dataset including 175 stereoscopic video sequences with diverse content, as well as their dense eye fixation annotations. Extensive experiments support that our proposed model can achieve superior performance compared to the state-of-the-art methods on all publicly available eye fixation datasets.

![Figure 1](/firstA/Arch_overview.jpg)