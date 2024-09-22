<div align="center">
<h2><a href="https://arxiv.org/abs/2405.10812">VQDNA: Unleashing the Power of Vector Quantization for Multi-Species Genomic Sequence Modeling</a></h2>

[Siyuan Li](https://lupin1998.github.io/)<sup>\*,1,2</sup>, [Zedong Wang](https://zedongwang.netlify.app/)<sup>\*,1</sup>, [Zicheng Liu](https://pone7.github.io/)<sup>1,2</sup>, [Di Wu](https://scholar.google.com/citations?user=egz8bGQAAAAJ&hl=zh-CN)<sup>1,2</sup>, [Chen Tan](https://chengtan9907.github.io/)<sup>1,2</sup>, [Jiangbin Zheng](https://scholar.google.co.id/citations?user=egz8bGQAAAAJ&hl=zh-CN)<sup>1,2</sup>, [Yufei Huang](https://scholar.google.co.id/citations?user=qmTjdwIAAAAJ&hl=zh-CN)<sup>1,2</sup>, [Stan Z. Li](https://scholar.google.com/citations?user=Y-nyLGIAAAAJ&hl=zh-CN)<sup>†,1</sup>

<sup>1</sup>[Westlake University](https://westlake.edu.cn/), <sup>2</sup>[Zhejiang University](https://www.zju.edu.cn/english/)
</div>

<p align="center">
<a href="https://arxiv.org/abs/2405.10812" alt="arXiv">
    <img src="https://img.shields.io/badge/arXiv-2405.10812-b31b1b.svg?style=flat" /></a>
<a href="https://github.com/Lupin1998/VQDNA/blob/main/LICENSE" alt="license">
    <img src="https://img.shields.io/badge/license-Apache--2.0-%23B7A800" /></a>
</p>

<!-- Introduction -->

## Introduction

Similar to natural language models, pre-trained genome language models are proposed to capture the underlying intricacies within genomes with unsupervised sequence modeling. They have become essential tools for researchers and practitioners in biology. However, the hand-crafted tokenization policies used in these models may not encode the most discriminative patterns from the limited vocabulary of genomic data. In this paper, we introduce VQDNA, a general-purpose framework that renovates genome tokenization from the perspective of genome vocabulary learning. By leveraging vector-quantized codebooks as learnable vocabulary, VQDNA can adaptively tokenize genomes into pattern-aware embeddings in an end-to-end manner. To further push its limits, we propose Hierarchical Residual Quantization (HRQ), where varying scales of codebooks are designed in a hierarchy to enrich the genome vocabulary in a coarse-to-fine manner. Extensive experiments on 32 genome datasets demonstrate VQDNA's superiority and favorable parameter efficiency compared to existing genome language models. Notably, empirical analysis of SARS-CoV-2 mutations reveals the fine-grained pattern awareness and biological significance of learned HRQ vocabulary, highlighting its untapped potential for broader applications in genomics.

<p align="center">
<img src="https://github.com/Westlake-AI/openmixup/assets/44519745/8c6f9cf5-897b-457c-9670-d5df5e809515" width=90% 
class="center">
</p>

## Catalog

We will update the implementation of VQDNA after finishing our new projects of genomic fundational model with techiniques of VQDNA. **Please watch us for the latest release!**
Feel free to open issues if there is some questions on experiments and implementation details.

<!-- ## License

This project is released under the [Apache 2.0 license](LICENSE).

## Acknowledgement

Our implementation is mainly based on the following codebases. We gratefully thank the authors for their wonderful works.

- [OpenMixup](https://github.com/Westlake-AI/openmixup): Open-source toolbox for visual representation learning.
- [MMDetection](https://github.com/open-mmlab/mmdetection): OpenMMLab Detection Toolbox and Benchmark.
- [OpenSTL](https://github.com/chengtan9907/OpenSTL): A Comprehensive Benchmark of Spatio-Temporal Predictive Learning.
- [fairseq](https://github.com/facebookresearch/fairseq): Facebook AI Research Sequence-to-Sequence Toolkit written in Python. -->

## Citation

If you find this repository helpful, please consider citing:
```
@inproceedings{icml2024vqdna,
    title={VQDNA: Unleashing the Power of Vector Quantization for Multi-Species Genomic Sequence Modeling},
    author={Siyuan Li and Zedong Wang and Zicheng Liu and Di Wu and Cheng Tan and Jiangbin Zheng and Yufei Huang and Stan Z. Li},
    booktitle={International Conference on Machine Learning (ICML)},
    year={2024}
}
```

<p align="right">(<a href="#top">back to top</a>)</p>
