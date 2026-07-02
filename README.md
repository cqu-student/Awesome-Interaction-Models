

> 一份精心策划的交互模型资源列表，包括文本、语音、图像和视频交互领域的顶级文章和开源项目。

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## 目录

- [Survey (综述)](#survey-综述)
- [Speech Interaction (语音交互)](#speech-interaction-语音交互)
- [Video Interaction (视频交互)](#video-interaction-视频交互)
- [Text Interaction (文本交互)](#text-interaction-文本交互)
- [Image Interaction (图像交互)](#image-interaction-图像交互)
- [Multimodal Interaction (多模态交互)](#multimodal-interaction-多模态交互)
- [Contributing](#contributing)
- [License](#license)

---

## Survey (综述)

| Date | Title | Paper | Code | Comment |
|------|-------|-------|------|---------|
| 2024-01 | Agent AI: Surveying the Horizons of Multimodal Interaction | [Paper](https://arxiv.org/abs/2401.03568) | - | 系统性综述Agent AI领域，定义多模态交互式智能体系统，涵盖视觉、语言等环境感知与具身动作生成 |

---

## Speech Interaction (语音交互)

| Date | Title | Paper | Code | Comment |
|------|-------|-------|------|---------|
| 2026-01 | PersonaPlex: Voice and Role Control for Full Duplex Conversational Speech Models | [Paper](https://arxiv.org/abs/2602.06053) | [Code](https://github.com/NVIDIA/personaplex) | 面向实时 speech-to-speech 交互的全双工语音模型，在 Moshi 基础上加入了角色与声音控制 |
| 2025-11 | Thinking While Speaking: Inference-Time Knowledge Transfer for Responsive and Intelligent Conversational Voice Agents | [Paper](https://arxiv.org/abs/2511.07397) | [Code](https://github.com/vysri/conversational-infill) | 提出 conversational infill 方法，小模型即时生成响应隐藏大模型推理延迟，并流式融入推理结果，实现毫秒级首 token 延迟同时逼近前沿模型性能 |
| 2025-07 | Full-Duplex-Bench v1.5: Evaluating Overlap Handling for Full-Duplex Speech Models | [Paper](https://arxiv.org/abs/2507.23159) | [Code](https://github.com/DanielLin94144/Full-Duplex-Bench) | Full-Duplex-Bench 的扩展版本，关注重叠语音处理，覆盖用户打断、听者附和、旁路对话和环境语音等场景 |
| 2025-06 | NTPP: Generative Speech Language Modeling for Dual-Channel Spoken Dialogue via Next-Token-Pair Prediction | [Paper](https://arxiv.org/abs/2506.00975) | [Code](https://github.com/Chaos96/NTPP) | 提出 next-token-pair prediction，用双通道语音数据建模对话双方的同步交互 |
| 2025-05 | SALM-Duplex: Efficient and Direct Duplex Modeling for Speech-to-Speech Language Model | [Paper](https://arxiv.org/abs/2505.15670) | [Code](https://github.com/cchen1436/NeMo/tree/main/examples/speechlm2) | 直接建模用户语音输入与智能体语音输出双流，支持 speech-to-speech 的全双工交互 |
| 2025-03 | Full-Duplex-Bench: A Benchmark to Evaluate Full-duplex Spoken Dialogue Models on Turn-taking Capabilities | [Paper](https://arxiv.org/abs/2503.04721) | [Code](https://github.com/DanielLin94144/Full-Duplex-Bench) | 面向全双工语音对话模型的交互评测基准，关注停顿处理、附和反馈、轮次管理和用户打断等能力 |
| 2025-02 | FlexDuo: A Pluggable System for Enabling Full-Duplex Capabilities in Speech Dialogue Systems | [Paper](https://arxiv.org/abs/2502.13472) | - | 提出可插拔的全双工控制模块，将 duplex control 从语音对话系统中解耦出来 |
| 2024-11 | Freeze-Omni: A Smart and Low Latency Speech-to-speech Dialogue Model with Frozen LLM | [Paper](https://arxiv.org/abs/2411.00774) | [Code](https://github.com/VITA-MLLM/Freeze-Omni) | 用冻结的文本 LLM 连接语音输入和语音输出，在保持智能性的同时实现低延迟 speech-to-speech 对话 |
| 2024-10 | Moshi: a speech-text foundation model for real-time dialogue | [Paper](https://arxiv.org/abs/2410.00037) | [Code](https://github.com/kyutai-labs/moshi) | 提出面向实时对话的 full-duplex 语音对话模型，直接建模语音到语音交互，支持低延迟响应、用户打断、重叠语音与自然轮次管理 |
| 2024-08 | VITA: Towards Open-Source Interactive Omni Multimodal LLM | [Paper](https://arxiv.org/abs/2408.05211) | [Code](https://github.com/VITA-MLLM/VITA) | 开源交互式 omni multimodal LLM，支持视频、图像、文本和音频的统一理解与交互 |
| 2024-08 | Language Model Can Listen While Speaking | [Paper](https://arxiv.org/abs/2408.02622) | - | 提出 listening-while-speaking language model，让模型在生成语音时同时监听用户输入 |
| 2024-05 | A Full-duplex Speech Dialogue Scheme Based On Large Language Models | [Paper](https://arxiv.org/abs/2405.19487) | - | 较早探索基于 LLM 的全双工语音对话方案，通过控制 token 决定等待、响应或打断 |
| 2019-09 | A Study for Improving Device-Directed Speech Detection Toward Frictionless Human-Machine Interaction | [Paper](https://doi.org/10.21437/Interspeech.2019-2840) | - | Interspeech 2019，设备定向语音检测的早期研究，结合声学与文本特征提升唤醒检测精度 |

---

## Video Interaction (视频交互)

| Date | Title | Paper | Code | Comment |
|------|-------|-------|------|---------|
| 2026-06 | LiveStarPro: Proactive Streaming Video Understanding with Hierarchical Memory | [Paper](https://arxiv.org/abs/2606.17798) | [Code](https://github.com/sotayang/LiveStarPro) | 层次化记忆的主动流式视频理解，在连续视频流中自主决策何时发声 |
| 2026-06 | JoyAI-VL-Interaction: Real-Time Vision-Language Interaction Intelligence | [Paper](https://arxiv.org/abs/2606.14777) | [Code](https://github.com/jd-opensource/JoyAI-VL-Interaction) | 视觉驱动的VL交互模型，自主决策静默/响应/委托，实现实时视觉-语言交互智能 |
| 2026-06 | Streaming Interventions: Can Video LLMs Correct Mistakes as They Occur? (Ego-CoMist) | [Paper](https://arxiv.org/abs/2606.09547) | [Page](https://apratimbh.github.io/livecookv2/) | 评估视频LLM在流式场景中实时纠正错误的能力，支持主动干预与交互修正 |
| 2026-06 | Harnessing Streaming Video in the Wild (Streaming Harness) | [Paper](https://arxiv.org/abs/2606.08615) | - | 利用12小时长时记忆进行自然场景流式视频理解 |
| 2026-06 | LyraV (Don't Pause): Streaming Video-Language Synchrony | [Paper](https://arxiv.org/abs/2606.06991) | - | 流式视频-语言同步，无需暂停的实时视频对话交互 |
| 2026-06 | X-Stream: Multi-Stream Understanding as Multiplexers | [Paper](https://arxiv.org/abs/2606.02482) | [Page](https://peiwensun2000.github.io/xstream/) | 将多流视频理解建模为多路复用器，同时处理多路视频输入 |
| 2026-05 | IPIBench: Interactive Proactive Intelligence under Continuous Streams | [Paper](https://arxiv.org/abs/2605.27074) | - | 连续流下的交互式主动智能评测基准 |
| 2026-05 | OmniInteract: Real-World Streaming Interaction Benchmark | [Paper](https://arxiv.org/abs/2605.26485) | [Code](https://github.com/Lucky-Lance/OmniInteract) | 真实世界流式交互评测基准，考察多模态代理的主动交互能力 |
| 2026-05 | VideoSeeker: Agentic Tool Invocation for Instance-level Video | [Paper](https://arxiv.org/abs/2605.16079) | [Page](https://gaotiexinqu.github.io/VideoSeeker/) | 面向实例级视频的智能体工具调用，实现更精细的视频交互检索 |
| 2026-05 | EgoPro-Bench: Personalized Proactive Interaction in Egocentric Video | [Paper](https://arxiv.org/abs/2605.07299) | - | 以自我为中心视频中的个性化主动交互评测基准 |
| 2026-04 | AURA: Always-On Real-Time Video Understanding & Assistance | [Paper](https://arxiv.org/abs/2604.04184) | - | 始终在线的实时视频理解与辅助助手，持续感知并主动响应用户需求 |
| 2026-03 | STRIDE: Diffusion-based When-to-Speak for Streaming Video | [Paper](https://arxiv.org/abs/2603.27593) | [Page](https://interlive-team.github.io/STRIDE) | 基于扩散模型的流式视频何时发声决策，实现自然的交互时机预测 |
| 2026-03 | RIVER Bench: Real-Time Video Interaction Benchmark | [Paper](https://arxiv.org/abs/2603.03985) | [Code](https://github.com/OpenGVLab/RIVER) | 实时视频交互评测基准，评估模型在流式视频中的交互表现 |
| 2026-03 | Proact-VL: Proactive VideoLLM for Real-Time AI Companions (ICML 2026) | [Paper](https://arxiv.org/abs/2603.03447) | - | 面向实时AI伴侣的主动视频语言模型，被ICML 2026接收 |
| 2026-01 | ROMA: Real-time Omni-Multimodal Assistant | [Paper](https://arxiv.org/abs/2601.10323) | [Page](https://eureka-maggie.github.io/ROMA_show) | 实时全模态助手，同时处理音频与视频流实现多模态交互 |
| 2025-12 | OmniAgent: Audio-Guided Active Perception Agent for Omnimodal Audio-Video Understanding | [Paper](https://arxiv.org/abs/2512.23646) | [Code](https://github.com/KD-TAO/OmniAgent) | 首个音频引导的主动感知代理，动态调度工具实现细粒度音视频推理 |
| 2025-12 | MMDuet2: Enhancing Proactive Interaction of Video MLLMs with Multi-Turn Reinforcement Learning | [Paper](https://arxiv.org/abs/2512.06810) | [Code](https://github.com/yellow-binary-tree/MMDuet2) | 通过多轮强化学习提升视频多模态大模型主动交互能力 |
| 2025-07 | ProactiveVideoQA: A Comprehensive Benchmark Evaluating Proactive Interactions in Video Large Language Models | [Paper](https://arxiv.org/abs/2507.09313) | [Code](https://github.com/yellow-binary-tree/ProactiveVideoQA) | 评估视频大语言模型主动交互能力的综合基准 |
| 2024-11 | VideoLLM Knows When to Speak: Enhancing Time-Sensitive Video Comprehension with Video-Text Duet Interaction Format | [Paper](https://arxiv.org/abs/2411.17991) | [Code](https://github.com/yellow-binary-tree/MMDuet) | 提出Video-Text Duet互动格式，让VideoLLM感知说话时机以提升时序视频理解 |

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

## Multimodal Interaction (多模态交互)

| Date | Title | Paper | Code | Comment |
|------|-------|-------|------|---------|
| 2025-03 | Qwen2.5-Omni Technical Report | [Paper](https://arxiv.org/abs/2503.20215) | [Code](https://github.com/QwenLM/Qwen2.5-Omni) | 统一处理文本、图像、音频与视频输入，并支持文本和自然语音流式输出，推动实时多模态交互 |
| 2024-08 | VITA: Towards Open-Source Interactive Omni Multimodal LLM | [Paper](https://arxiv.org/abs/2408.05211) | [Code](https://github.com/VITA-MLLM/VITA) | 面向图像、视频、文本和音频的开源交互式全模态模型，强调自然的人机多模态交互 |
| 2024-02 | AnyGPT: Unified Multimodal LLM with Discrete Sequence Modeling | [Paper](https://arxiv.org/abs/2402.12226) | [Code](https://github.com/OpenMOSS/AnyGPT) | 用离散序列统一建模语音、文本、图像和音乐，支持多轮任意模态对话 |

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
