---
title: "High Degree of Freedom Hand Pose Tracking Using Limited Strain Sensing and Optical Training"
collection: publications
permalink: /publications/2019glove
date: 2019-02-28
venue: 'Journal of Computing and Information Science in Engineering'
paperurl: 'https://teddyz829.github.io/files/2019glove.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

## Abstract

The ability to track human operators' hand usage when working in production plants and factories is critically important for developing realistic  digital factory simulators as well as manufacturing process control.  We propose a proof-of-concept instrumented glove with only a few strain gauge sensors and a micro-controller that continuously tracks and records the hand configuration during actual use. At the heart of our approach is a trainable system that can predict the fourteen joint angles in the hand using only a small set of strain sensors. First, ten strain gauges are  placed at the various joints in the hand to optimize the sensor layout using the English letters in the American Sign Language as a benchmark for assessment. Next, the best sensor configurations for three through ten strain gauges are computed using a support vector machine classifier. Following the layout optimization, our approach learns a mapping between the sensor readouts to the actual joint angles optically captured using a Leap Motion system. Five regression methods including linear, quadratic  and neural regression are then used to train the mapping  between the strain gauge data and the corresponding joint angles. The final proposed model involves four strain gauges mapped to the fourteen joint angles using a two-layer feed-forward neural network.

[[Preprint version]](https://teddyz829.github.io/files/2019glove.pdf){:target="_blank"}

If it is useful in your research work, please consider citing this paper:

<pre>
 @article{zhang2019high,  
  title={High Degree of Freedom Hand Pose Tracking Using Limited Strain Sensing and Optical Training},  
  author={Zhang, Wentai and Yu, Jonelle Z. and Zhu, Fangcheng and Zhu, Yifang and Yang, Zhangsihao and Ulu, Nurcan Gecer and Arisoy, Batuhan and Kara, Levent Burak.},  
  journal={Journal of Computing and Information Science in Engineering},  
  volume={},  
  number={},  
  pages={},  
  doi = {},  
  paperid = {JCISE-18-1249},  
  year={2019},  
  publisher={American Society of Mechanical Engineers},  
 }
</pre>