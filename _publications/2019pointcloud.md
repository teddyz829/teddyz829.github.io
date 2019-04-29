---
title: "Data-driven Upsampling of Point Clouds"
collection: publications
permalink: /publications/2019pointcloud
date: 2019-02-28
venue: 'Computer-Aided Design'
paperurl: 'https://doi.org/10.1016/j.cad.2019.02.006'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

## Abstract

High quality upsampling of sparse 3D point clouds is critically useful for a wide range of geometric operations such as reconstruction, rendering, meshing, and analysis. In this paper, we propose a data-driven algorithm that enables an upsampling of 3D point clouds without the need for hard-coded rules. Our approach uses a deep network with Chamfer distance as the loss function, capable of learning the latent features in point clouds belonging to different object categories. We evaluate our algorithm across different amplification factors, with upsampling learned and performed on objects belonging to the same category as well as different categories. We also explore the desirable characteristics of input point clouds as a function of the distribution of the point samples. Finally, we demonstrate the performance of our algorithm in single-category training versus multi-category training scenarios. The final proposed model is compared against a baseline, optimization-based upsampling method. The results indicate that our algorithm is capable of generating more accurate upsamplings with less Chamfer loss.

[[Arxiv version]](https://arxiv.org/abs/1807.02740){:target="_blank"}  [[Publisher's version]](https://doi.org/10.1016/j.cad.2019.02.006)

If it is useful in your research work, please consider citing this paper:

    @article{ZHANG20191,
     title = "Data-driven Upsampling of Point Clouds",
     journal = "Computer-Aided Design",
     volume = "112",
     pages = "1 - 13",
     year = "2019",
     issn = "0010-4485",
     doi = "https://doi.org/10.1016/j.cad.2019.02.006",
     author = "Wentai Zhang and Haoliang Jiang and Zhangsihao Yang and Soji Yamakawa and Kenji Shimada and Levent Burak Kara"
    }
