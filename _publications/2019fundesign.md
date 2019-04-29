---
title: "3D Shape Synthesis for Conceptual Design and Optimization Using Variational Autoencoders"
collection: publications
permalink: /publications/2019fundesign
date: 2019-04-16
venue: 'ASME IDETC/CIE'
paperurl: 'https://arxiv.org/abs/1904.07964'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

## Abstract

We propose a data-driven 3D shape design method that can learn a generative model from a corpus of existing designs, and use this model to produce a wide range of new designs. The approach learns an encoding of the samples in the training corpus using an unsupervised variational autoencoder-decoder architecture, without the need for an explicit parametric representation of the original designs. To facilitate the generation of smooth final surfaces, we develop a 3D shape representation based on a distance transformation of the original 3D data, rather than using the commonly utilized binary voxel representation. Once established, the generator maps the latent space representations to the high-dimensional distance transformation fields, which are then automatically surfaced to produce 3D representations amenable to physics simulations or other objective function evaluation modules. We demonstrate our approach for the computational design of gliders that are optimized to attain prescribed performance scores. Our results show that when combined with genetic optimization, the proposed approach can generate a rich set of candidate concept designs that achieve prescribed functional goals, even when the original dataset has only a few or no solutions that achieve these goals.

[[Arxiv version]](https://arxiv.org/abs/1904.07964){:target="_blank"} 

If it is useful in your research work, please consider citing this paper:

```latex
@article{DBLP:journals/corr/abs-1904-07964,  
author    = {Wentai Zhang and Zhangsihao Yang and Haoliang Jiang and Suyash Nigam and Soji Yamakawa and Tomotake Furuhata and Kenji Shimada and Levent Burak Kara},  
title     = {3D Shape Synthesis for Conceptual Design and Optimization Using Variational Autoencoders},    
journal   = {CoRR},  
volume    = {abs/1904.07964},  
year      = {2019},  
url       = {http://arxiv.org/abs/1904.07964},  
archivePrefix = {arXiv},  
eprint    = {1904.07964},  
timestamp = {Fri, 26 Apr 2019 13:18:53 +0200},  
biburl    = {https://dblp.org/rec/bib/journals/corr/abs-1904-07964},  
bibsource = {dblp computer science bibliography, https://dblp.org}  
}
```
