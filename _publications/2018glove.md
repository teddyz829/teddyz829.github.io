---
title: "High Degree of Freedom Hand Pose Tracking Using Limited Strain Sensing and Optical Training"
collection: publications
permalink: /publications/2018glove
date: 2018-04-16
venue: 'ASME IDETC/CIE'
paperurl: 'http://proceedings.asmedigitalcollection.asme.org/proceeding.aspx?articleid=2713114'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

## Abstract

The ability to track human operators’ hand usage when working in production plants and factories is critically important for developing realistic digital factory simulators as well as manufacturing process control. We propose an instrumented glove with only a few strain gauge sensors and a micro-controller that continuously tracks and records the hand configuration during actual use. At the heart of our approach is a trainable system that can predict the fourteen joint angles in the hand using only a small set of strain sensors. First, ten strain gauges are placed at the various joints in the hand to optimize the sensor layout using the English letters in the American Sign Language as a benchmark for assessment. Next, the best sensor configurations for three through ten strain gauges are computed using a support vector machine classifier. Following the layout optimization, our approach learns a mapping between the sensor readouts to the actual joint angles optically captured using a Leap Motion system. Three regression methods including linear, quadratic and neural regression are then used to train the mapping between the strain gauge data and the corresponding joint angles. The final proposed model involves four strain gauges mapped to the fourteen joint angles using a two-layer feed-forward neural network.

[[Preprint version]](https://teddyz829.github.io/files/2018glove.pdf){:target="_blank"}  [[Publisher's version]](http://proceedings.asmedigitalcollection.asme.org/proceeding.aspx?articleid=2713114){:target="_blank"}

If it is useful in your research work, please consider citing this paper:

<pre>
 @inproceedings{zhang2018high,
  title={High Degree of Freedom Hand Pose Tracking Using Limited Strain Sensing and Optical Training},
  author={Zhang, Wentai and Jonelle, Z Yu and Zhu, Fangcheng and Zhu, Yifang and Ulu, Nurcan Gecer and Arisoy, Batuhan and Kara, Levent Burak},
  booktitle={ASME 2018 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference},
  pages={V01BT02A019--V01BT02A019},
  year={2018},
  organization={American Society of Mechanical Engineers}
 }
</pre>