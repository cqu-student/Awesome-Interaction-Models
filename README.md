# Awesome Interaction Models

> 一份精心策划的交互模型资源列表，包括文本、图像和视频交互领域的顶级文章和开源项目。

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## 目录

- [Text Interaction (文本交互)](#text-interaction-文本交互)
- [Image Interaction (图像交互)](#image-interaction-图像交互)
- [Video Interaction (视频交互)](#video-interaction-视频交互)
- [Contributing](#contributing)
- [License](#license)

---

## Text Interaction (文本交互)

| Date | Title | Paper | Code | Comment |
|------|-------|-------|------|---------|
| 2017-06 | Attention Is All You Need | [arXiv](https://arxiv.org/abs/1706.03762) | [GitHub](https://github.com/tensorflow/tensor2tensor) | Transformer 架构的奠基论文，引领了 NLP 领域的革新 |
| 2018-10 | BERT: Pre-training of Deep Bidirectional Transformers | [arXiv](https://arxiv.org/abs/1810.04805) | [GitHub](https://github.com/google-research/bert) | 双向预训练模型在 NLP 中的应用 |
| 2019-02 | Language Models are Unsupervised Multitask Learners | [PDF](https://d4mucfpksywv.cloudfront.net/better-language-models/language-models.pdf) | [GitHub](https://github.com/openai/gpt-2) | GPT-2 论文，展示语言模型的多任务学习能力 |
| 2020-05 | Language Models are Few-Shot Learners | [arXiv](https://arxiv.org/abs/2005.14165) | [GitHub](https://github.com/openai/gpt-3) | GPT-3 论文，展示大规模语言模型的少样本学习能力 |

---

## Image Interaction (图像交互)

| Date | Title | Paper | Code | Comment |
|------|-------|-------|------|---------|
| 2020-10 | An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale | [arXiv](https://arxiv.org/abs/2010.11929) | [GitHub](https://github.com/google-research/vision_transformer) | Vision Transformer (ViT) 论文，将 Transformer 应用于视觉任务 |
| 2021-03 | Learning Transferable Visual Models From Natural Language Supervision | [arXiv](https://arxiv.org/abs/2103.14030) | [GitHub](https://github.com/openai/CLIP) | CLIP 模型，开放式视觉语言模型的突破 |
| 2021-05 | Diffusion Models Beat GANs on Image Synthesis | [arXiv](https://arxiv.org/abs/2105.05233) | [GitHub](https://github.com/hojonathanho/diffusion) | 扩散模型在图像生成中超越 GAN 的性能 |
| 2022-04 | High-Resolution Image Synthesis with Latent Diffusion Models | [arXiv](https://arxiv.org/abs/2112.10752) | [GitHub](https://github.com/CompVis/stable-diffusion) | Stable Diffusion 论文，高效的图像生成模型 |

---

## Video Interaction (视频交互)

| Date | Title | Paper | Code | Comment |
|------|-------|-------|------|---------|
| 2016-08 | Temporal Segment Networks: Towards Good Practices for Deep Action Recognition | [arXiv](https://arxiv.org/abs/1608.00859) | [GitHub](https://github.com/yjxiong/temporal-segment-networks) | 视频行为识别的经典方法 |
| 2021-03 | ViViT: A Video Vision Transformer | [arXiv](https://arxiv.org/abs/2103.15808) | [GitHub](https://github.com/google-research/scenic) | 视频的 Vision Transformer 扩展，支持时空建模 |
| 2021-02 | Towards Good Practices for Very Deep Video Understanding | [arXiv](https://arxiv.org/abs/2102.06183) | [GitHub](https://github.com/facebookresearch/SlowFast) | 深度视频理解的最佳实践和 SlowFast 网络 |
| 2022-01 | Revisiting Spatial-Temporal Similarity: A Deep Learning Framework for Traffic Forecasting | [arXiv](https://arxiv.org/abs/2110.04573) | [GitHub](https://github.com/underfitting/revisiting-spatial-temporal-similarity) | 时空建模在视频分析中的应用 |

---

## Contributing

欢迎贡献！请参阅 [CONTRIBUTING.md](CONTRIBUTING.md) 了解详细信息。

### 快速贡献步骤

1. Fork 这个仓库
2. 创建你的特性分支 (`git checkout -b add-new-resource`)
3. 在表格中添加新资源（按时间倒序排列）
4. 提交你的改变 (`git commit -m 'Add: [Resource Title]'`)
5. 推送到分支 (`git push origin add-new-resource`)
6. 开启一个 Pull Request

### 表格字段说明

- **Date**: 论文发表日期或代码发布日期 (YYYY-MM 格式)
- **Title**: 论文或项目的标题
- **Paper**: 论文链接 (如无则留空)
- **Code**: 开源代码链接 (如无则留空)
- **Comment**: 简要描述资源的主要贡献或特点

---

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

本项目采用 [CC0 1.0 Universal License](LICENSE) 许可证。
