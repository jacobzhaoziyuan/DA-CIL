

<div align="center">

# DA-CIL: Towards Domain Adaptive Class-Incremental 3D Object Detection

[![BMVC2022](https://img.shields.io/badge/arXiv-2212.02057-blue)](https://arxiv.org/abs/2212.02057)
[![BMVC2022](https://img.shields.io/badge/Conference-BMVC2022-green)](https://bmvc2022.mpi-inf.mpg.de/916/)



</div>

Pytorch implementation of our method for BMVC 2022 paper: "DA-CIL: Towards Domain Adaptive Class-Incremental 3D Object Detection".

## Abstract
Deep learning has achieved notable success in 3D object detection with the advent of large-scale point cloud datasets. However, severe performance degradation in the past trained classes, i.e., catastrophic forgetting, still remains a critical issue for real-world deployment when the number of classes is unknown or may vary. Moreover, existing 3D class-incremental detection methods are developed for the single-domain scenario, which fail when encountering domain shift caused by different datasets, varying environments, etc. In this paper, we identify the unexplored yet valuable scenario, i.e., class-incremental learning under domain shift, and propose a novel 3D domain adaptive class-incremental object detection framework, DA-CIL, in which we design a novel dual-domain copy-paste augmentation method to construct multiple augmented domains for diversifying training distributions, thereby facilitating gradual domain adaptation. Then, multi-level consistency is explored to facilitate dual-teacher knowledge distillation from different domains for domain adaptive class-incremental learning. Extensive experiments on various datasets demonstrate the effectiveness of the proposed method over baselines in the domain adaptive class-incremental learning scenario.

<p align="center">
<img src="https://github.com/jacobzhaoziyuan/DA-CIL/blob/main/assets/archi-bmvc.png" width="1000">
</p>







## Citation
If you find the codebase useful for your research, please cite the paper:
```
@inproceedings{Zhao_2022_BMVC,
author    = {Ziyuan Zhao and Mingxi Xu and Peisheng Qian and Ramanpreet Pahwa and richard chang},
title     = {DA-CIL: Towards Domain Adaptive Class-Incremental 3D Object Detection},
booktitle = {33rd British Machine Vision Conference 2022, {BMVC} 2022, London, UK, November 21-24, 2022},
publisher = {{BMVA} Press},
year      = {2022},
url       = {https://bmvc2022.mpi-inf.mpg.de/0916.pdf}
}

```
