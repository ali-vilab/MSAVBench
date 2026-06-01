
# MSAVBench: Towards Comprehensive and Reliable Evaluation of Multi-Shot Audio-Video Generation

<div align="center">

[![arXiv](https://img.shields.io/badge/arXiv-2605.20183-b31b1b.svg)](https://arxiv.org/abs/2605.20183v1)

**Yujie Wei, Yujin Han, Zhekai Chen, Yongming Li, Kaixun Jiang, Zhihang Liu, Quanhao Li, Zhiwu Qing, Xiang Wang, Zhen Xing, Ruihang Chu, Lingyi Hong, Yefei He, Junjie Zhou, Junqiu Yu, Yang Shi, Difan Zou, Kai Zhu, Shiwei Zhang, Yingya Zhang, Yu Liu, Xihui Liu, Hongming Shan**

</div>

Video generation is rapidly evolving from single-shot synthesis to complex multi-shot audio-video (MSAV) narratives to meet real-world demands. However, evaluating such frontier models remains a fundamental challenge. Existing benchmarks are limited in scope and data diversity, and rely on rigid evaluation pipelines, preventing systematic and reliable assessment of modern MSAV models. To bridge these gaps, we introduce MSAVBench, the first comprehensive benchmark and adaptive hybrid evaluation framework for multi-shot audio-video generation. Our benchmark spans four key dimensions, video, audio, shot, and reference, covering diverse task settings, varying shot counts of up to 15, and challenging non-realistic scenarios. Our evaluation framework improves robustness through an adaptive self-correction mechanism for shot segmentation, instance-wise rubrics for subjective metrics, and tool-grounded evidence extraction for complex judgments. Furthermore, MSAVBench achieves high alignment with human judgments, reaching a Spearman rank correlation of 91.5%. Our systematic evaluation of 19 state-of-the-art closed- and open-source models shows that current systems still struggle with director-level control and fine-grained audio-visual synchronization, while modular or agentic generation pipelines offer a promising path toward narrowing the gap between open- and closed-source models.


## TODO List

- [x] Prompt data
- [ ] Reference assets
- [ ] Evaluation code


## 🌟 Citation

If you find this code useful for your research, please cite our paper:

```bibtex
@article{wei2026msavbench,
  title={MSAVBench: Towards Comprehensive and Reliable Evaluation of Multi-Shot Audio-Video Generation},
  author={Wei, Yujie and Han, Yujin and Chen, Zhekai and Li, Yongming and Jiang, Kaixun and Liu, Zhihang and Li, Quanhao and Qing, Zhiwu and Wang, Xiang and Xing, Zhen and Chu, Ruihang and Hong, Lingyi and He, Yefei and Zhou, Junjie and Yu, Junqiu and Shi, Yang and Zou, Difan and Zhu, Kai and Zhang, Shiwei and Zhang, Yingya and Liu, Yu and Liu, Xihui and Shan, Hongming},
  year={2026},
  eprint={2605.20183},
  archivePrefix={arXiv},
  primaryClass={cs.CV}
}
```
