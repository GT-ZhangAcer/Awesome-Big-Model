# Awesome-Big-Model

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Awesome-DeepLearning/Big-Model-Collection)
![GitHub Repo stars](https://img.shields.io/github/stars/GT-ZhangAcer/Awesome-Big-Model)
![GitHub](https://img.shields.io/github/license/GT-ZhangAcer/Awesome-Big-Model)

📖收集国内外深度学习大模型API、论文、案例与学习资料，欢迎Star🌟

---

**目前只提供了小部分国内大模型论文链接，后续也将持续更新摘要解析等内容，如有补充/勘误，欢迎PR/Issue来一起建设啦~**

> 下方顺序、分类等等等信息暂未调整，待后续完善后决定顺序规则，暂时以个人了解程度为主
---

[API/工具](https://github.com/GT-ZhangAcer/Awesome-Big-Model/README.md#API工具) | [相关论文](https://github.com/GT-ZhangAcer/Awesome-Big-Model/README.md#相关论文) | 大模型应用

## API/工具
* ### 开源/在线体验
  1. 文心大模型NLP通用大模型    - [体验链接](https://wenxin.baidu.com/wenxin/ernie)   
    * > 内含对话、对联、问答、自由生成（Prompt）等基础任务，支持0样本与少样本学习    
  2. 文心大模型跨模态生成       - [体验链接](https://wenxin.baidu.com/wenxin/ernie-vilg)  
    * > 使用中文文本来生成图像，效果还可以    
  3. 浪潮·源1.0              - [申请链接](https://air.inspur.com/home) | [开源主页](https://github.com/Shawn-Inspur/Yuan-1.0)  
    * > 普通开发者可申请对联与对话API，挺能撩，但会骂人  
  4. OpenBMB·EVA对话模型      - [体验链接](https://www.openbmb.org/models/eva)  
    * > 及格偏上水平的对话模型  
  5. OpenBMB·CPM1.0故事生成   - [体验链接](https://www.openbmb.org/models/cpm1)  
    * > 生成虽然不如彩云小梦，但体验相较其它大模型要好一些  
  6. OpenBMB·CPM2.0完形填空   - [体验链接](https://www.openbmb.org/models/cpm2)
    * > 可进行词汇补全  
  7. 鹏城·盘古α通用大模型      - [体验链接](https://pangu-alpha.openi.org.cn/) | [开源链接](https://git.openi.org.cn/PCL-Platform.Intelligence/PanGu-Alpha)  
    * > 支持对话、问答、自由生成（Prompt）等基础任务  
  8. 悟道AI开放平台           - [体验链接](https://open.wudaoai.com/openpower) | [开源组织](https://github.com/BAAI-WuDao)  
    * > 包含标题生成、对话、纠错、润色等挺有意思的功能  
  9. DALL-E                  - [官方开源链接](https://github.com/openai/DALL-E) | [飞桨开发者版本](https://github.com/AgentMaker/Paddle-DALL-E)
    * > 可根据英文生成图像
  10. RuDALL-E              - [官方开源链接](https://github.com/sberbank-ai) | [飞桨开发者版本](https://github.com/AgentMaker/ru-dalle-paddle) | [飞桨开发者版本在线体验](https://aistudio.baidu.com/aistudio/projectdetail/2684828)
    * > DALL-E俄语版，飞桨开发者版本可在线体验中文->翻译为俄语->文本生成图片
   11. CLIP                 - [官方开源链接](https://github.com/openai/CLIP) | [飞桨开发者版本](https://github.com/AgentMaker/Paddle-CLIP) | [飞桨开发者版本在线体验](https://aistudio.baidu.com/aistudio/projectdetail/1644724) | [飞桨官方实现](https://github.com/PaddlePaddle/PASSL)
    * > 将文本与图像一起训练，在Zero-shot上也能有不错的成绩。
    
## 相关论文
目录导航 [百度·文心](https://github.com/GT-ZhangAcer/Awesome-Big-Model/README.md##百度文心) | OpenAI | 浪潮·源 | 智源·悟道 | 清华·OpenBMB | 阿里OFA | 华为·盘古
### 百度·文心
产业级知识增强大模型，包含基础通用大模型及面向重点领域和重点任务的大模型，同时有丰富的工具与平台支撑高效便捷的应用开发，学习效率高，可解释性好，大幅降低AI开发与应用门槛。

```其子系列分为ERNIE、VIMER、PLATO、HELIX四个主要系列，分别对应NLP/跨模态、CV、对话系统、生物计算4个部分。```

子系列导航 [ERNIE系](https://github.com/GT-ZhangAcer/Awesome-Big-Model/README.md#ERNIE系) | [VIMER系](https://github.com/GT-ZhangAcer/Awesome-Big-Model/README.md#VIMER系) | [PLATO系](https://github.com/GT-ZhangAcer/Awesome-Big-Model/README.md#VIMER系) | [HELIX系](https://github.com/GT-ZhangAcer/Awesome-Big-Model/README.md#HELIX系)

* #### ERNIE系
  1. 鹏城-百度·文心 - [End-to-end Adaptive Distributed Training on PaddlePaddle](https://arxiv.org/abs/2112.02752)
  2. ERNIE3.0 - [ERNIE 3.0: Large-scale Knowledge Enhanced Pre-training for Language Understanding and Generation](https://arxiv.org/abs/2107.02137)
  3. ERNIE2.0 - [ERNIE 2.0: A Continual Pre-training Framework for Language Understanding](https://arxiv.org/abs/1907.12412v1)
  4. ERNIE1.0 - [ERNIE: Enhanced Representation through Knowledge Integration](https://arxiv.org/abs/1904.09223)
  5. ERNIE-M - [ERNIE-M: Enhanced Multilingual Representation by Aligning Cross-lingual Semantics with Monolingual Corpora](https://arxiv.org/abs/2012.15674)
  6. ERNIE-Gram - [ERNIE-Gram: Pre-Training with Explicitly N-Gram Masked Language Modeling for Natural Language Understanding](https://aclanthology.org/2021.naacl-main.136)
  7. ERNIE-Doc - [ERNIE-Doc: A Retrospective Long-Document Modeling Transformer](https://arxiv.org/abs/2012.15688)
  8. ERNIE-ViLG - [ERNIE-ViLG: Unified Generative Pre-training for Bidirectional Vision-Language Generation](https://arxiv.org/abs/2112.15283.pdf)
  9. ERNIE-ViL - [ERNIE-ViL: Knowledge Enhanced Vision-Language Representations Through Scene Graph](https://arxiv.org/abs/2006.16934)
  10. ERNIE-UNIMO - [UNIMO: Towards Unified-Modal Understanding and Generation via Cross-Modal Contrastive Learning](https://arxiv.org/pdf/2012.15409.pdf)
* #### VIMER系
  1. VIMER-StrucTexT - [StrucTexT: Structured Text Understanding with Multi-Modal Transformers](https://arxiv.org/abs/2108.02923)
  2. 还有几个，后续看到了再更新吧
* #### PLATO系
  1. PLATO-XL - [PLATO-XL: Exploring the Large-scale Pre-training of Dialogue Generation](https://arxiv.org/abs/2109.09519)
  2. PLATO2.0 - [PLATO-2: Towards Building an Open-Domain Chatbot via Curriculum Learning](https://arxiv.org/abs/2006.16779)
  3. PLATO1.0 - [PLATO: Pre-trained Dialogue Generation Model with Discrete Latent Variable](https://arxiv.org/abs/1910.07931)
* #### HELIX系
  1. HELIX-GEM - [Geometry-enhanced molecular representation learning for property prediction](https://www.nature.com/articles/s42256-021-00438-4)
  2. HELIX-S2F - [Multimodal Pre-Training Model for Sequence-based Prediction of Protein-Protein Interaction](https://proceedings.mlr.press/v165/xue22a.html)


## 大模型应用
后续更新
