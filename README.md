<h1 align="center">Worldscape-MoE</h1>

<p align="center">
  <strong>A Unified Mixture-of-Experts Architecture for Scalable Multi-Control Video Generation World Modeling</strong>
</p>

<p align="center">
  Jianjie Fang, Yongyan Xu, Ziyou Wang, Yuchao Huang, Zhaolu Wang, Rongze Tang, Mingyuan Jia, Baining Zhao, Weichen Zhang, Xin Zhang, Haisheng Su, Yu Shang, Chen Gao, Wei Wu, Xinlei Chen, Yong Li
</p>

<p align="center">
  <a href="https://embodiedcity.github.io/Worldscape-MoE/"><img src="https://img.shields.io/badge/Project_Page-6f2dbd?style=flat-square&logo=googlechrome&logoColor=white" alt="Project Page"></a>
  <a href="https://github.com/EmbodiedCity/Worldscape-MoE.code"><img src="https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white" alt="Code"></a>
  <a href="https://www.youtube.com/watch?v=8H3hJ3XDJFk"><img src="https://img.shields.io/badge/Demo_Video-ff0033?style=flat-square&logo=youtube&logoColor=white" alt="Demo Video"></a>
</p>

<p align="center">
  <sub>Paper, arXiv, and model weights will be released soon.</sub>
</p>

## Overview

Worldscape-MoE is a unified world-model training framework for multi-control video generation. It introduces a Mixture-of-Experts design into Diffusion Transformers to learn from heterogeneous supervisory controls, including camera poses, robotic arms, and hand joints, within a single extensible world model.

By combining shared experts for cross-control world knowledge with modality-specific experts for control specialization, Worldscape-MoE aims to scale embodied and interactive world modeling beyond single-control supervision.

## Demo

<p align="center">
  <a href="https://www.youtube.com/watch?v=8H3hJ3XDJFk">
    <img src="assets/demo.gif" alt="Worldscape-MoE demo preview" width="90%">
  </a>
</p>

<p align="center">
  <a href="https://www.youtube.com/watch?v=8H3hJ3XDJFk"><strong>Watch the full demo on YouTube</strong></a>
</p>

## Citation

If you find this project useful, please consider citing:

```bibtex
@misc{fang2026worldscapemoe,
  title        = {Worldscape-MoE: A Unified Mixture-of-Experts Architecture for Scalable Multi-Control Video Generation World Modeling},
  author       = {Fang, Jianjie and Xu, Yongyan and Wang, Ziyou and Huang, Yuchao and Wang, Zhaolu and Tang, Rongze and Jia, Mingyuan and Zhao, Baining and Zhang, Weichen and Zhang, Xin and Su, Haisheng and Shang, Yu and Gao, Chen and Wu, Wei and Chen, Xinlei and Li, Yong},
  year         = {2026},
  note         = {Project page: https://embodiedcity.github.io/Worldscape-MoE/}
}
```
