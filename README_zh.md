<div align="center">

<h1>宗天禹 &nbsp;·&nbsp; Tianyu Zong</h1>

<p>
  <b>中国科学院大学 2027 届计算机博士在读</b> &nbsp;·&nbsp;
  多模态表征学习 &nbsp;|&nbsp; 世界模型与三维视觉 &nbsp;|&nbsp; 具身智能
</p>

<p>
  <a href="https://tianyuzong.github.io"><img src="https://img.shields.io/badge/个人主页-tianyuzong.github.io-1F2937?style=flat-square&logo=githubpages&logoColor=white" alt="个人主页"/></a>
  <a href="https://scholar.google.com/citations?user=21Lsyn2ReN4C"><img src="https://img.shields.io/badge/Google_Scholar-学术主页-4285F4?style=flat-square&logo=googlescholar&logoColor=white" alt="Google Scholar"/></a>
  <a href="https://huggingface.co/UCASzty"><img src="https://img.shields.io/badge/Hugging_Face-UCASzty-FF9D00?style=flat-square&logo=huggingface&logoColor=white" alt="Hugging Face"/></a>
  <a href="https://dblp.org/pid/352/9351.html"><img src="https://img.shields.io/badge/DBLP-论文列表-004F9F?style=flat-square&logo=dblp&logoColor=white" alt="DBLP"/></a>
  <a href="mailto:zongtianyu20@mails.ucas.ac.cn"><img src="https://img.shields.io/badge/Email-zongtianyu20%40mails.ucas.ac.cn-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p>
  <a href="README.md"><b>🌐 English</b></a> &nbsp;|&nbsp; <b>简体中文</b>
</p>

</div>

---

### 👋 个人简介

中国科学院大学计算机科学与技术学院博士在读（预计 2027 年 6 月毕业），导师为[徐俊刚教授](https://people.ucas.edu.cn/~xujg)，获 **2026 年博士研究生国家奖学金**。

研究聚焦**多模态表示学习**、**无监督对比学习**与**视觉语言模型（VLM）**，并拓展至**三维视觉 / 世界模型**与**具身智能（VLA）**。已发表及录用论文 **8 篇**（其中**第一作者 4 篇**：**ACL 2026 Main**、**AAAI 2025 Oral**、**AAAI 2023** 与 **Neural Networks**；共同作者 4 篇：**ACL 2026 Main / Findings**、**AAAI 2026** 与 **ICASSP 2026**）。现于**灵初智能（PsiBot）**担任预训练算法实习生，曾在**生数科技**、**阿里巴巴高德地图**、**启物科技**实习。

- 🔬 **研究方向**：多模态表征与检索 · 无监督对比与自监督学习 · 前馈可重光照 3DGS 与世界模型 · 具身智能与 VLA 模型
- 💼 **当前状态**：预训练算法实习生 @ **灵初智能（PsiBot）**，专注机器人操作关键帧挖掘与多模态时序定位
- 📍 **所在地**：中国 · 北京

---

### 📝 论文发表

#### 第一作者论文

| 会议 / 期刊 | 论文题目与核心成果 | 链接 |
| :--- | :--- | :--- |
| ![ACL 2026 Main](https://img.shields.io/badge/ACL_2026-Main-B31B1B?style=flat-square) | **L2Dir: Integrating L₂-Norm and Directional Alignment for Unsupervised Contrastive Representation Learning in Multimodal Retrieval**<br/><sub>在冻结骨干特征（Qwen2-VL、GME、CLIP）上引入轻量 MLP 联合优化正样本 L₂ 模长与方向；在 MMEB-V2（81 项）与 M-BEIR（14 项）共 95 项任务上验证，CLIP-L 在 M-BEIR 上平均 Recall@10 由 44.8% 提升至 48.4%（+3.6 pts）。</sub> | [Paper](https://aclanthology.org/2026.acl-long.1604/) · [Code](https://github.com/tianyuzong/L2Dir_ACL2026) |
| ![Neural Networks](https://img.shields.io/badge/Neural_Networks-2027-059669?style=flat-square) | **JTCSE: Joint Tensor-Modulus Constraints and Cross-Attention for Unsupervised Contrastive Learning of Sentence Embeddings**<br/><sub>引入交叉注意力与 `[CLS]` 能量加权缓解注意力下沉；在 MTEB 50 项零样本文本检索上平均 MAP@10 较 SimCSE 提升 +2.81 点，总体评测覆盖 140+ 项 MTEB 任务。</sub> | [Paper](https://doi.org/10.1016/j.neunet.2026.109724) · [arXiv](https://arxiv.org/abs/2505.02366) · [Code](https://github.com/tianyuzong/JTCSE) · [Models](https://huggingface.co/UCASzty) |
| ![AAAI 2025 Oral](https://img.shields.io/badge/AAAI_2025-Oral_(Top_4.6%25)-2563EB?style=flat-square) | **TNCSE: Tensor's Norm Constraints for Unsupervised Contrastive Learning of Sentence Embeddings**<br/><sub>引入显式张量模长约束与集成蒸馏；在 7 项 STS 基准上平均 Spearman 达 80.60（较 SimCSE-BERT-base 提升 +4.35 点），覆盖近 100 项零样本任务。</sub> | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/34816) · [arXiv](https://arxiv.org/abs/2503.12739) · [Code](https://github.com/tianyuzong/TNCSE) · [Models](https://huggingface.co/UCASzty) |
| ![AAAI 2023](https://img.shields.io/badge/AAAI_2023-Poster-4F46E5?style=flat-square) | **An Ensemble Distillation Framework for Sentence Embeddings with Multilingual Round-Trip Translation**<br/><sub>提出多语言往返翻译与集成蒸馏框架，将多子模型知识压缩至单一 BERT-base；7 项 STS 平均 Spearman 达 79.27（+3.02 点），推理无额外开销。</sub> | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/26647) |

#### 共同作者论文与预印本

| 会议 / 预印本 | 论文题目与作者 | 链接 |
| :--- | :--- | :--- |
| ![ACL 2026 Main](https://img.shields.io/badge/ACL_2026-Main-B31B1B?style=flat-square) | **FAIRGAMER: Evaluating Social Biases in LLM-Based Video Game NPCs**<br/><sub>Bingkang Shi, Jen-tse Huang, Luo Long, **Tianyu Zong**, Hongzhu Yi, Yuanxiang Wang, Songlin Hu, Xiaodan Zhang, Zhongjiang Yao</sub> | [Paper](https://aclanthology.org/2026.acl-long.2015/) · [arXiv](https://arxiv.org/abs/2508.17825) · [Code](https://github.com/BingkangShi/FairGamer) |
| ![ACL 2026 Findings](https://img.shields.io/badge/ACL_2026-Findings-9333EA?style=flat-square) | **LLaTiSA: Towards Difficulty-Stratified Time Series Reasoning from Visual Perception to Semantics**<br/><sub>Yueyang Ding, HaoPeng Zhang, Rui Dai, Yi Wang, **Tianyu Zong**, Kaikui Liu, Xiangxiang Chu</sub> | [Paper](https://aclanthology.org/2026.findings-acl.1636/) · [arXiv](https://arxiv.org/abs/2604.17295) |
| ![AAAI 2026](https://img.shields.io/badge/AAAI_2026-Main-2563EB?style=flat-square) | **Dynamic Deep Graph Learning for Incomplete Multi-View Clustering with Masked Graph Reconstruction Loss**<br/><sub>Zhenghao Zhang, Jun Xie, Xingchen Chen, Tao Yu, Hongzhu Yi, Kaixin Xu, Yuanxiang Wang, **Tianyu Zong**, et al., Jungang Xu</sub> | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/40091) · [arXiv](https://arxiv.org/abs/2511.11181) |
| ![ICASSP 2026](https://img.shields.io/badge/ICASSP_2026-CCF--B-0284C7?style=flat-square) | **Graph-Guided Contrastive Learning for Incomplete Multi-View Clustering with Consistent Global Graph**<br/><sub>Zhepeng Wang, Zhenghao Zhang, **Tianyu Zong**, Feng Chen, Jun Xie</sub> | [Paper](https://doi.org/10.1109/icassp55912.2026.11461858) |
| ![arXiv 2026](https://img.shields.io/badge/arXiv-2026.10-64748B?style=flat-square) | **Can One Hear Geometry? Gauge-Invariant Spectral Descriptors for Text-to-B-rep Retrieval**<br/><sub>Hongzhu Yi, Hao Liu, Tao Yu, Tiankun Yang, Yujia Yang, Zhenghao Zhang, **Tianyu Zong**, et al., Jungang Xu</sub> | [arXiv](https://arxiv.org/abs/2610.33484) |
| ![arXiv 2026](https://img.shields.io/badge/arXiv-2026.06-64748B?style=flat-square) | **Delta-JEPA: Learning Action-Sensitive World Models via Latent Difference Decoding**<br/><sub>Zhenghao Zhang, Yuanxiang Wang, Zhenyu Guan, Yujia Yang, Bingkang Shi, **Tianyu Zong**, et al., Jungang Xu</sub> | [arXiv](https://arxiv.org/abs/2606.31232) |
| ![arXiv 2026](https://img.shields.io/badge/arXiv-2026.02-64748B?style=flat-square) | **VDE Bench: Evaluating The Capability of Image Editing Models to Modify Visual Documents**<br/><sub>Hongzhu Yi, Yujia Yang, Yuanxiang Wang, Tong Li, Zhenyu Guan, **Tianyu Zong**, et al., Jungang Xu</sub> | [arXiv](https://arxiv.org/abs/2602.00122) |
| ![arXiv 2026](https://img.shields.io/badge/arXiv-2026.01-64748B?style=flat-square) | **RPO: Reinforcement Fine-Tuning with Partial Reasoning Optimization**<br/><sub>Hongzhu Yi, Xinming Wang, Zhenghao Zhang, **Tianyu Zong**, Yuanxiang Wang, et al., Jungang Xu</sub> | [arXiv](https://arxiv.org/abs/2601.19404) · [Code](https://github.com/yhz5613813/RPO) |

---

### 💼 实习经历

| 时间 | 机构 | 方向与主要工作 |
| :--- | :--- | :--- |
| `2026.11 – 至今` | **灵初智能（PsiBot）** | **预训练算法实习生** — 融合运动信号与视觉构建两阶段机器人操作关键帧筛选流水线（候选关键边界覆盖率 79.84% → 95.97%），结合多模态表征优化动作时序定位（F1 58.41% → 65.80%）。 |
| `2026.09 – 2026.10` | **生数科技（ShengShu）** | **视频数据流水线算子开发** — 基于 GroundingDINO + SAM 2.1 + OpenCV/FFmpeg 开发视频 In/Out-painting 算子、GPT-image 场景还原，以及运动/运镜与 13 维画面质量算子。 |
| `2025.10 – 2026.08` | **阿里巴巴 · 高德地图** | **算法研究实习生** — 基于 Hunyuan WorldMirror 与 3DGS 的前馈可重光照三维重建（多光照重建与 NVS 分别提升 +4 dB / +3 dB PSNR，DeepSpeed ZeRO-1）；UE5 + City Sample HDRI 多模态城市场景采集工具；MoCo v3 / MAE 视觉自监督预训练；基于 InternVL3/Qwen3 的业务多模态数据清洗。 |
| `2025.07 – 2025.09` | **启物科技** | **具身智能实习生** — VLA 模型并行推理与实时动作推理（RTC）后端优化（单位时间推理步数提升至 3×）；基于 LeRobot 微调并在 RoboTwin 评测 π₀、SmolVLA、ACT、Diffusion Policy。 |

---

### 🚀 开源项目

<table>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/tianyuzong/L2Dir_ACL2026">L2Dir_ACL2026</a></b><br/>
      <i>ACL 2026 Main</i> 官方代码：面向多模态检索的 L₂ 模长与方向联合对齐对比学习框架（覆盖 95 项任务）。
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/tianyuzong/TNCSE">TNCSE</a> &amp; <a href="https://github.com/tianyuzong/JTCSE">JTCSE</a></b><br/>
      <i>AAAI 2025 Oral</i> 与 <i>Neural Networks</i> 官方代码与 Hugging Face 模型权重（张量模长约束无监督句向量）。
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/tianyuzong/video-subject-mask">video-subject-mask</a></b><br/>
      基于 GroundingDINO + SAM 2.1 的视频主体排序、分割与凸原语掩码随机化工具，用于 DiT 视频补全数据构造。
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/tianyuzong/video-outpaint">video-outpaint</a></b><br/>
      面向扩散 Transformer 视频扩画任务的主体感知裁剪与真实缩放数据构造管线。
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/tianyuzong/ThermoForge-Studio">ThermoForge-Studio</a> &amp; <a href="https://github.com/tianyuzong/strength-studio">strength-studio</a></b><br/>
      面向 Windows 的 AI 驱动本地热/结构多物理场与 CUDA/cuDSS 加速有限元仿真工作台。
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/tianyuzong/coserve-agent">coserve-agent</a></b><br/>
      基于原生 DeepSeek Harness 并集成 CAD/CAE 工具链的 AI 工程工作台。
    </td>
  </tr>
</table>

---

### 🛠️ 技术栈

- **训练框架与集群**：Python · PyTorch · Hugging Face (`Transformers` / `Datasets`) · DeepSpeed (`ZeRO-1/2/3`) · H100/A100 多节点集群运维
- **多模态与视频**：Qwen2-VL · InternVL3 · Qwen3 · CLIP · MoCo v3 · MAE · GroundingDINO · SAM 2.1 · OpenCV · FFmpeg
- **三维视觉与仿真**：3D Gaussian Splatting (`3DGS`) · `gsplat` · 本征分解 · 球谐光照建模 · Unreal Engine 5 (`City Sample`, HDRI)
- **具身智能与强化学习**：LeRobot · π₀ · SmolVLA · ACT · Diffusion Policy · RoboTwin · VLA 并行推理 / RTC · PPO / GRPO / DPO

---

### 🎓 教育背景、荣誉与学术服务

- **教育背景**：中国科学院大学 计算机应用技术博士在读（`2023–2027`）· 中国科学院大学 电子信息硕士（`2020–2023`）· 北方工业大学 电子信息工程学士（`2016–2020`）
- **主要荣誉**：博士研究生国家奖学金（`2026`）· 中国科学院大学三好学生（`2026`）· 连续六年学业奖学金（`2020–2025`）· 第十届全国大学生数学竞赛一等奖
- **审稿服务**：**AAAI**（`2025`, `2026`）、**ACL**（`2026`）、*Neural Networks*、*Neurocomputing*、*Information Processing & Management*
