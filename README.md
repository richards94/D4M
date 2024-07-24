# 💾 D<sup>4</sup>M: Dataset Distillation via Disentangled Diffusion Model

## 💥 Stellar Features
🎯 Distilling Dataset in an Optimization-Free manner. <br>
🎯 The distillation process is Architecture-Free. (Getting over the Cross-Architecture problem.) <br>
🎯 Distilling large-scale datasets (ImageNet-1K) efficiently. <br>
🎯 The distilled datasets are high-quality and versatile. <br>

## 📚 Introduction
Dataset distillation offers a lightweight synthetic dataset for fast network training with promising test accuracy. 
We advocate for designing an economical dataset distillation framework that is independent of the matching architectures.
With empirical observations, we argue that constraining the consistency of the real and synthetic image spaces will enhance the cross-architecture generalization. 
Motivated by this, we introduce Dataset Distillation via Disentangled Diffusion Model (D<sup>4</sup>M), an efficient framework for dataset distillation. 
Compared to architecture-dependent methods, D<sup>4</sup>M employs latent diffusion model to guarantee consistency and incorporates label information into category prototypes.
The distilled datasets are versatile, eliminating the need for repeated generation of distinct datasets for various architectures.
Through comprehensive experiments, D<sup>4</sup>M demonstrates superior performance and robust generalization, surpassing the SOTA methods across most aspects.

<img src=".\misc\D4M_pipeline.png" alt="method" />

<div align="center">
  <em>
    Overview of D<sup>4</sup>M. For more details, please see our 
    <a href="https://arxiv.org/abs/2407.15138">paper</a>.
  </em>
</div>

## 🔧 Quick Start

## Citation

```
@InProceedings{Su_2024_CVPR,
               author    = {Su, Duo and Hou, Junjie and Gao, Weizhi and Tian, Yingjie and Tang, Bowen},
               title     = {D{\textasciicircum}4M: Dataset Distillation via Disentangled Diffusion Model},
               booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
               month     = {June},
               year      = {2024},
               pages     = {5809-5818}
              }