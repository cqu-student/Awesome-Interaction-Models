

> 一份精心策划的交互模型资源列表，包括文本、语音、图像和视频交互领域的顶级文章和开源项目。

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## 目录

- [Multimodal Interaction (多模态交互)](#multimodal-interaction-多模态交互)
- [Text Interaction (文本交互)](#text-interaction-文本交互)
- [Speech Interaction (语音交互)](#speech-interaction-语音交互)
- [Image Interaction (图像交互)](#image-interaction-图像交互)
- [Video Interaction (视频交互)](#video-interaction-视频交互)
- [Contributing](#contributing)
- [License](#license)

---

## Survey (综述)

| Date | Title | Paper | Code | Comment |
|------|-------|-------|------|---------|
| 2024-01 | Agent AI: Surveying the Horizons of Multimodal Interaction | [Paper](https://arxiv.org/abs/2401.03568) | - | 系统性综述Agent AI领域，定义多模态交互式智能体系统，涵盖视觉、语言等环境感知与具身动作生成 |

---

## Multimodal Interaction (多模态交互)

| Date | Title | Paper | Code | Comment |
|------|-------|-------|------|---------|
| 2025-03 | Qwen2.5-Omni Technical Report | [Paper](https://arxiv.org/abs/2503.20215) | [Code](https://github.com/QwenLM/Qwen2.5-Omni) | 统一处理文本、图像、音频与视频输入，并支持文本和自然语音流式输出，推动实时多模态交互 |
| 2024-08 | VITA: Towards Open-Source Interactive Omni Multimodal LLM | [Paper](https://arxiv.org/abs/2408.05211) | [Code](https://github.com/VITA-MLLM/VITA) | 面向图像、视频、文本和音频的开源交互式全模态模型，强调自然的人机多模态交互 |
| 2024-02 | AnyGPT: Unified Multimodal LLM with Discrete Sequence Modeling | [Paper](https://arxiv.org/abs/2402.12226) | [Code](https://github.com/OpenMOSS/AnyGPT) | 用离散序列统一建模语音、文本、图像和音乐，支持多轮任意模态对话 |

---

## Text Interaction (文本交互)

| Date | Title | Paper | Code | Comment |
|------|-------|-------|------|---------|
| 2025-07 | Teaching Language Models To Gather Information Proactively | [Paper](https://arxiv.org/abs/2507.21389) | [Code](https://github.com/tenghaohuang/Teaching-Language-Models-To-Gather-Information-Proactively) | 训练LLM主动提问收集信息，从被动文本生成器提升为协作思考伙伴 |
| 2025-04 | Proactive Conversational Agents with Inner Thoughts | [Paper](https://arxiv.org/abs/2501.00383) | [Code](https://github.com/xybruceliu/thoughtful-agents) | 提出 Inner Thoughts 框架，让对话代理在多方交流中形成内部想法，并在合适时机主动参与对话 |
| 2025-02 | CollabLLM: From Passive Responders to Active Collaborators | [Paper](https://arxiv.org/abs/2502.00640) | [Code](https://github.com/Wuyxin/collabllm) | 训练语言模型在多轮任务中主动理解用户意图并提出建议，从被动回答者转向主动协作者 |
| 2025-01 | Clarify When Necessary: Resolving Ambiguity Through Interaction with LMs | [Paper](https://arxiv.org/abs/2311.09469) | - | 研究模型何时需要向用户澄清、该问什么问题，以及如何利用用户补充信息完成任务 |
| 2024-10 | Modeling Future Conversation Turns to Teach LLMs to Ask Clarifying Questions | [Paper](https://arxiv.org/abs/2410.13788) | - | 通过建模后续对话结果训练模型在面对歧义请求时主动提出澄清问题 |
| 2024-10 | Proactive Agent: Shifting LLM Agents from Reactive Responses to Active Assistance | [Paper](https://arxiv.org/abs/2410.12361) | [Code](https://github.com/thunlp/ProactiveAgent) | 将 LLM 代理从被动响应转向主动辅助的框架/方法 |
| 2024-09 | ClarQ-LLM: A Benchmark for Models Clarifying and Requesting Information in Task-Oriented Dialog | [Paper](https://arxiv.org/abs/2409.06097) | [Code](https://github.com/ygan/ClarQ-LLM) | 面向任务型对话的澄清问题评测基准，考察模型通过提问补全关键信息的能力 |
| 2024-07 | Towards Human-centered Proactive Conversational Agents | [Paper](https://arxiv.org/abs/2404.12670) | - | 从人本交互角度讨论主动对话代理，强调主动性需要兼顾用户需求、适应性与不过度打扰 |
| 2024-03 | STaR-GATE: Teaching Language Models to Ask Clarifying Questions | [Paper](https://arxiv.org/abs/2403.19154) | [Code](https://github.com/scandukuri/assistant-gate) | 通过自我改进训练模型提出更有用的澄清问题，从而生成更符合用户偏好的回复 |
| 2023-10 | Eliciting Human Preferences with Language Models | [Paper](https://arxiv.org/abs/2310.11589) | [Code](https://github.com/alextamkin/generative-elicitation) | 提出 GATE 框架，让语言模型通过自由文本交互主动引出用户偏好和任务意图 |

---

## Speech Interaction (语音交互)

| Date | Title | Paper | Code | Comment |
|------|-------|-------|------|---------|
| 2026-01 | PersonaPlex: Voice and Role Control for Full Duplex Conversational Speech Models | [Paper](https://arxiv.org/abs/2602.06053) | [Code](https://github.com/NVIDIA/personaplex) | 面向实时 speech-to-speech 交互的全双工语音模型，在 Moshi 基础上加入了角色与声音控制 |
| 2025-07 | Full-Duplex-Bench v1.5: Evaluating Overlap Handling for Full-Duplex Speech Models | [Paper](https://arxiv.org/abs/2507.23159) | [Code](https://github.com/DanielLin94144/Full-Duplex-Bench) | Full-Duplex-Bench 的扩展版本，关注重叠语音处理，覆盖用户打断、听者附和、旁路对话和环境语音等场景 |
| 2025-03 | Full-Duplex-Bench: A Benchmark to Evaluate Full-duplex Spoken Dialogue Models on Turn-taking Capabilities | [Paper](https://arxiv.org/abs/2503.04721) | [Code](https://github.com/DanielLin94144/Full-Duplex-Bench) | 面向全双工语音对话模型的交互评测基准，关注停顿处理、附和反馈、轮次管理和用户打断等能力 |
| 2024-10 | Moshi: a speech-text foundation model for real-time dialogue | [Paper](https://arxiv.org/abs/2410.00037) | [Code](https://github.com/kyutai-labs/moshi) | 提出面向实时对话的 full-duplex 语音对话模型，直接建模语音到语音交互，支持低延迟响应、用户打断、重叠语音与自然轮次管理 |
| 2019-09 | A Study for Improving Device-Directed Speech Detection Toward Frictionless Human-Machine Interaction | [Paper](https://doi.org/10.21437/Interspeech.2019-2840) | - | 研究提升设备定向语音检测精度，判断用户语音是否面向设备，推动无摩擦人机语音交互 |

---

## Image Interaction (图像交互)

| Date | Title | Paper | Code | Comment |
|------|-------|-------|------|---------|
| 2025-07 | Teaching Vision-Language Models to Ask: Resolving Ambiguity in Visual Questions | [Paper](https://arxiv.org/abs/2507.13773) | [Code](https://github.com/jian0805/ClearVQA) | 训练视觉语言模型主动提问以解决视觉问答中的歧义问题 |
| 2023-11 | GLaMM: Pixel Grounding Large Multimodal Model | [Paper](https://arxiv.org/abs/2311.03356) | [Code](https://github.com/mbzuai-oryx/groundingLMM) | 将多模态对话与像素级 grounding 结合，使自然语言回答中的目标可对应到图像中像素级 mask |
| 2023-10 | Ferret: Refer and Ground Anything Anywhere at Any Granularity | [Paper](https://arxiv.org/abs/2310.07704) | [Code](https://github.com/apple/ml-ferret) | 支持点、框、自由形状等任意区域输入，可围绕图中具体区域进行指代和定位 |
| 2023-08 | LISA: Reasoning Segmentation via Large Language Model | [Paper](https://arxiv.org/abs/2308.00692) | [Code](https://github.com/JIA-Lab-research/LISA) | 提出 reasoning segmentation任务，使模型先根据复杂或隐含的自然语言指令推理用户意图，再分割目标 |
| 2023-04 | Visual Instruction Tuning | [Paper](https://arxiv.org/abs/2304.08485) | [Code](https://github.com/haotian-liu/LLaVA) | 提出 LLaVA（Large Language and Visual Assistant），通过视觉指令微调构建通用图像-文本对话助手 |
| 2023-04 | Segment Anything | [Paper](https://arxiv.org/abs/2304.02643) | [Code](https://github.com/facebookresearch/segment-anything) | 提出 promptable segmentation，允许用户通过点、框、mask 等提示告诉模型要分割的目标 |
| 2023-03 | Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models | [Paper](https://arxiv.org/abs/2303.04671) | [Code](https://github.com/microsoft/visual-chatgpt) | 连接 ChatGPT 与视觉基础模型，支持图像问答、绘制、编辑和反馈式交互 |
| 2016-11 | Visual Dialog | [Paper](https://arxiv.org/abs/1611.08669) | [Code](https://github.com/batra-mlp-lab/visdial) | 提出围绕图像进行多轮问答的视觉对话任务，是图像交互研究的早期代表工作 |

---

## Video Interaction (视频交互)

| Date | Title | Paper | Code | Comment |
|------|-------|-------|------|---------|
| 2025-12 | OmniAgent: Audio-Guided Active Perception Agent for Omnimodal Audio-Video Understanding | [Paper](https://arxiv.org/abs/2512.23646) | [Code](https://github.com/KD-TAO/OmniAgent) | 首个音频引导的主动感知代理，动态调度工具实现细粒度音视频推理 |
| 2025-12 | MMDuet2: Enhancing Proactive Interaction of Video MLLMs with Multi-Turn Reinforcement Learning | [Paper](https://arxiv.org/abs/2512.06810) | [Code](https://github.com/yellow-binary-tree/MMDuet2) | 通过多轮强化学习提升视频多模态大模型主动交互能力 |
| 2025-07 | ProactiveVideoQA: A Comprehensive Benchmark Evaluating Proactive Interactions in Video Large Language Models | [Paper](https://arxiv.org/abs/2507.09313) | [Code](https://github.com/yellow-binary-tree/ProactiveVideoQA) | 评估视频大语言模型主动交互能力的综合基准 |
| 2024-11 | VideoLLM Knows When to Speak: Enhancing Time-Sensitive Video Comprehension with Video-Text Duet Interaction Format | [Paper](https://arxiv.org/abs/2411.17991) | [Code](https://github.com/yellow-binary-tree/MMDuet) | 提出Video-Text Duet互动格式，让VideoLLM感知说话时机以提升时序视频理解 |

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
