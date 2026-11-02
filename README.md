<h1 align="center">Awesome Image Restoration<br>in the Foundation Model Era</h1>

<p align="center">
  A curated reading list on foundation models and agents for image restoration.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Image-Restoration-2563eb?style=flat-square" alt="Topic: Image Restoration">
  <img src="https://img.shields.io/badge/Foundation-Models-7c3aed?style=flat-square" alt="Topic: Foundation Models">
  <img src="https://img.shields.io/badge/Agentic-Restoration-0f766e?style=flat-square" alt="Topic: Agentic Restoration">
</p>

<br>

This list follows the taxonomy of *A Survey on Image Restoration in the Foundation Model Era*. It covers methods that use foundation models for restoration, the development of restoration foundation models, and agents that plan and refine restoration workflows.

Each paper has one primary entry. Foundational models, conventional baselines, and related surveys are identified separately as background.

## Contents

- [Image Restoration with Foundation Models](#image-restoration-with-foundation-models)
- [Foundation Models for Image Restoration](#foundation-models-for-image-restoration)
- [Agentic Image Restoration](#agentic-image-restoration)


## Image Restoration with Foundation Models

### Image Restoration with Vision and Language Models

#### Visual Features and Segmentation Priors

- **DINO-IR** — Multi-task Image Restoration Guided By Robust DINO Features. *Preprint 2023*. [Paper](https://arxiv.org/abs/2312.01677)
- **Super-Resolution in The Right Latent Space: A Frozen Vision-Foundation Substrate**. *Preprint 2026*. [Paper](https://arxiv.org/abs/2610.04781)
- **GramSR: Visual Feature Conditioning for Diffusion-Based Super-Resolution**. *ICPR 2026*. [Paper](https://arxiv.org/abs/2604.25457) · [Code](https://github.com/aimagelab/GramSR)
- **CLD** — RAW-CLIP Fusion: Unleashing Semantic-Aware Denoising for Sensor-Agnostic Low-Light Imaging. *IEEE Trans. Image Process. 2026*. [Paper](https://doi.org/10.1109/TIP.2026.3692025)
- **DiffLI²D** — Unleashing the Potential of the Semantic Latent Space in Diffusion Models for Image Dehazing. *ECCV 2024*. [Paper](https://arxiv.org/abs/2509.20091)
- **SAM priors** — A Dive into SAM Prior in Image Restoration. *Preprint 2023*. [Paper](https://arxiv.org/abs/2305.13620)
- **SAM-Deblur: Let Segment Anything Boost Image Deblurring**. *ICASSP 2024*. [Paper](https://arxiv.org/abs/2309.02270) · [Code](https://github.com/HPLQAQ/SAM-Deblur) · [Project](https://hplqaq.github.io/projects/sam-deblur)
- **Intra and Inter Parser-Prompted Transformers for Effective Image Restoration**. *AAAI 2025*. [Paper](https://arxiv.org/abs/2503.14037)
- **SAM distillation** — Distilling Semantic Priors from SAM to Efficient Image Restoration Models. *CVPR 2024*. [Paper](https://arxiv.org/abs/2403.16368) · [Project](https://github.com/WeiLi-THU/SAM4IR)
- **PTG-RM** — Boosting Image Restoration via Priors from Pre-trained Models. *CVPR 2024*. [Paper](https://arxiv.org/abs/2403.06793)
- **CLIPDenoising** — Transfer CLIP for Generalizable Image Denoising. *CVPR 2024*. [Paper](https://arxiv.org/abs/2403.15132) · [Code](https://github.com/alwaysuu/CLIPDenoising)

#### Degradation and Instruction Conditioning

- **InstructIR: High-Quality Image Restoration Following Human Instructions**. *ECCV 2024*. [Paper](https://arxiv.org/abs/2401.16468) · [Code](https://github.com/mv-lab/InstructIR) · [Project](https://mv-lab.github.io/InstructIR/)
- **DA-CLIP** — Controlling Vision-Language Models for Multi-Task Image Restoration. *ICLR 2024*. [Paper](https://arxiv.org/abs/2310.01018) · [Code](https://github.com/Algolzw/daclip-uir)
- **VL-UR: Vision-Language-guided Universal Restoration of Images Degraded by Adverse Weather Conditions**. *Preprint 2025*. [Paper](https://arxiv.org/abs/2504.08219)
- **LoRA-IR: Taming Low-Rank Experts for Efficient All-in-One Image Restoration**. *Preprint 2024*. [Paper](https://arxiv.org/abs/2410.15385) · [Code](https://github.com/shallowdream204/LoRA-IR)
- **ClearAIR: A Human-Visual-Perception-Inspired All-in-One Image Restoration**. *AAAI 2026*. [Paper](https://arxiv.org/abs/2601.02763) · [Code](https://github.com/House-yuyu/ClearAIR)
- **Leveraging Multimodal Large Language Models for All-in-One Image Restoration via a Mixture of Frequency Experts**. *Preprint 2026*. [Paper](https://arxiv.org/abs/2605.11444)
- **QuReC: All-in-One Image Restoration with Query-Specific Guidance and Local-Global Response Calibration**. *ACM MM 2026*. [Paper](https://arxiv.org/abs/2607.15097) · [Code](https://github.com/zhoushen1/QuReC)
- **MGN-AIR** — Beyond Uniform Restoration: Empowering All-in-One Restoration with Pixel-Level Multimodal Guidance. *ACM MM 2026*. [Paper](https://arxiv.org/abs/2608.09482)
- **SLER-IR: Spherical Layer-wise Expert Routing for All-in-One Image Restoration**. *Preprint 2026*. [Paper](https://arxiv.org/abs/2603.05940) · [Project](https://github.com/PSR666/SLER-IR)
- **TextPromptIR** — Textual prompt guided image restoration. *Eng. Appl. Artif. Intell. 2025*. [Paper](https://arxiv.org/abs/2312.06162) · [Code](https://github.com/MoTong-AI-studio/TextPromptIR)
- **LMDIR** — Training-Free Large Model Priors for Multiple-in-One Image Restoration. *Preprint 2024*. [Paper](https://arxiv.org/abs/2407.13181)
- **TextDegRemoval** — Improving Image Restoration through Removing Degradations in Textual Representations. *CVPR 2024*. [Paper](https://arxiv.org/abs/2312.17334) · [Code](https://github.com/mrluin/TextualDegRemoval)
- **AWRaCLe: All-Weather Image Restoration using Visual In-Context Learning**. *Preprint 2024*. [Paper](https://arxiv.org/abs/2409.00263) · [Code](https://github.com/sudraj2002/AWRaCLe)
- **Vision-Language Gradient Descent-driven All-in-One Deep Unfolding Networks**. *CVPR 2025*. [Paper](https://arxiv.org/abs/2503.16930) · [Code](https://github.com/xianggkl/VLU-Net)
- **RamIR: Reasoning and action prompting with mamba for all-in-one image restoration**. *Appl. Intell. 2025*. [Paper](https://link.springer.com/article/10.1007/s10489-024-06226-y)

#### Language Model Adaptation

- **LM4LV: A Frozen Large Language Model for Low-level Vision Tasks**. *Preprint 2024*. [Paper](https://arxiv.org/abs/2405.15734) · [Code](https://github.com/bytetriper/LM4LV)
- **Beyond Text: Frozen Large Language Models in Visual Signal Comprehension**. *CVPR 2024*. [Paper](https://arxiv.org/abs/2403.07874) · [Code](https://github.com/zh460045050/V2L-Tokenizer)
- **PURE** — Perceive, Understand and Restore: Real-World Image Super-Resolution with Autoregressive Multimodal Generative Models. *ICCV 2025*. [Paper](https://arxiv.org/abs/2503.11073)

### Image Restoration with Generative Priors

#### Pretrained Generative Priors

- **Denoising Diffusion Restoration Models**. *NeurIPS 2022*. [Paper](https://arxiv.org/abs/2201.11793) · [Code](https://github.com/bahjat-kawar/ddrm) · [Project](https://ddrm-ml.github.io/)
- **PULSE: Self-Supervised Photo Upsampling via Latent Space Exploration of Generative Models**. *CVPR 2020*. [Paper](https://arxiv.org/abs/2003.03808)
- **RePaint: Inpainting Using Denoising Diffusion Probabilistic Models**. *CVPR 2022*. [Paper](https://arxiv.org/abs/2201.09865) · [Code](https://github.com/andreas128/RePaint)
- **Zero-Shot Image Restoration Using Denoising Diffusion Null-Space Model**. *Preprint 2022*. [Paper](https://arxiv.org/abs/2212.00490) · [Code](https://github.com/wyhuai/DDNM)
- **Diffusion Posterior Sampling for General Noisy Inverse Problems**. *ICLR 2023*. [Paper](https://arxiv.org/abs/2209.14687) · [Code](https://github.com/DPS2022/diffusion-posterior-sampling)
- **PSLD** — Solving Linear Inverse Problems Provably via Posterior Sampling with Latent Diffusion Models. *NeurIPS 2023*. [Paper](https://arxiv.org/abs/2307.00619)
- **RED-Diff** — A Variational Perspective on Solving Inverse Problems with Diffusion Models. *ICLR 2024*. [Paper](https://arxiv.org/abs/2305.04391) · [Code](https://github.com/NVlabs/RED-diff)
- **Diffusion Priors for Variational Likelihood Estimation and Image Denoising**. *NeurIPS 2024*. [Paper](https://arxiv.org/abs/2410.17521) · [Code](https://github.com/HUST-Tan/DiffusionVI)
- **Denoising Diffusion Models for Plug-and-Play Image Restoration**. *CVPR Workshops 2023*. [Paper](https://arxiv.org/abs/2305.08995) · [Code](https://github.com/yuanzhi-zhu/DiffPIR)
- **Decoupled Data Consistency with Diffusion Purification for Image Restoration**. *Preprint 2024*. [Paper](https://arxiv.org/abs/2403.06054)
- **Improving Diffusion Inverse Problem Solving with Decoupled Noise Annealing**. *CVPR 2025*. [Paper](https://arxiv.org/abs/2407.01521) · [Project](https://daps-inverse-problem.github.io/)
- **Efficient Zero-shot Inpainting with Decoupled Diffusion Guidance**. *ICLR 2026*. [Paper](https://arxiv.org/abs/2512.18365) · [Code](https://github.com/YazidJanati/ding)
- **D-Flow: Differentiating through Flows for Controlled Generation**. *ICML 2024*. [Paper](https://arxiv.org/abs/2402.14017)
- **Parallel Diffusion Models of Operator and Image for Blind Inverse Problems**. *CVPR 2023*. [Paper](https://arxiv.org/abs/2211.10656)
- **Test-Time Degradation Adaptation for Open-Set Image Restoration**. *ICML 2024*. [Paper](https://arxiv.org/abs/2312.02197) · [Code](https://github.com/XLearning-SCU/2024-ICML-TAO)
- **DreamClean: Restoring Clean Image Using Deep Diffusion Prior**. *ICLR 2024*. [Paper](https://proceedings.iclr.cc/paper_files/paper/2024/hash/814c2fe415df792624766894cec09f00-Abstract-Conference.html)

#### Conditional Generative Restoration

- **PromptFix: You Prompt and We Fix the Photo**. *NeurIPS 2024*. [Paper](https://arxiv.org/abs/2405.16785) · [Project](https://www.yongshengyu.com/PromptFix-Page)
- **Exploiting Diffusion Prior for Real-World Image Super-Resolution**. *Int. J. Comput. Vis. 2024*. [Paper](https://arxiv.org/abs/2305.07015) · [Code](https://github.com/IceClear/StableSR)
- **Scaling Up to Excellence: Practicing Model Scaling for Photo-Realistic Image Restoration In the Wild**. *CVPR 2024*. [Paper](https://arxiv.org/abs/2401.13627) · [Code](https://github.com/Fanghua-Yu/SUPIR)
- **DiT4SR: Taming Diffusion Transformer for Real-World Image Super-Resolution**. *ICCV 2025*. [Paper](https://arxiv.org/abs/2503.23580) · [Code](https://github.com/Adam-duan/DiT4SR) · [Project](https://adam-duan.github.io/projects/dit4sr/)
- **Pixel-Aware Stable Diffusion for Realistic Image Super-resolution and Personalized Stylization**. *ECCV 2024*. [Paper](https://arxiv.org/abs/2308.14469) · [Code](https://github.com/yangxy/PASD)
- **DiffBIR: Toward Blind Image Restoration with Generative Diffusion Prior**. *ECCV 2024*. [Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/07690.pdf) · [Code](https://github.com/XPixelGroup/DiffBIR)
- **DNF-SR: Dual-Input and Negative-Aware Feature Fine-Tuning for Real-World Image Super-Resolution**. *CVPR 2026*. [Paper](https://arxiv.org/abs/2609.15120)
- **Multimodal Prompt Perceiver: Empower Adaptiveness, Generalizability and Fidelity for All-in-One Image Restoration**. *CVPR 2024*. [Paper](https://arxiv.org/abs/2312.02918) · [Code](https://github.com/hhb072/MPerceiver-Code)
- **Diff-Plugin: Revitalizing Details for Diffusion-based Low-level Tasks**. *CVPR 2024*. [Paper](https://arxiv.org/abs/2403.00644) · [Project](https://yuhaoliu7456.github.io/Diff-Plugin/)
- **UnSCAR: Universal, Scalable, Controllable, and Adaptable Image Restoration**. *Preprint 2026*. [Paper](https://arxiv.org/abs/2603.07406)
- **DarkDiff: Advancing Low-Light Raw Enhancement by Retasking Diffusion Models for Camera ISP**. *Preprint 2025*. [Paper](https://arxiv.org/abs/2505.23743)
- **Time-Aware One Step Diffusion Network for Real-World Image Super-Resolution**. *CVPR 2026*. [Paper](https://arxiv.org/abs/2508.16557)
- **RestoreVAR: Visual Autoregressive Generation for All-in-One Image Restoration**. *ICLR 2026*. [Paper](https://arxiv.org/abs/2505.18047) · [Code](https://github.com/sudraj2002/RestoreVAR)
- **IR-SDE** — Image Restoration with Mean-Reverting Stochastic Differential Equations. *ICML 2023*. [Paper](https://arxiv.org/abs/2301.11699) · [Code](https://github.com/Algolzw/image-restoration-sde)
- **SeeSR: Towards Semantics-Aware Real-World Image Super-Resolution**. *CVPR 2024*. [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Wu_SeeSR_Towards_Semantics-Aware_Real-World_Image_Super-Resolution_CVPR_2024_paper.pdf) · [Code](https://github.com/cswry/SeeSR)
- **InstructRestore: Region-Customized Image Restoration with Human Instructions**. *Preprint 2025*. [Paper](https://arxiv.org/abs/2503.24357) · [Code](https://github.com/shuaizhengliu/InstructRestore)
- **ReFIR: Grounding Large Restoration Models with Retrieval Augmentation**. *NeurIPS 2024*. [Paper](https://arxiv.org/abs/2410.05601) · [Code](https://github.com/csguoh/ReFIR)
- **ADIR: Adaptive Diffusion for Image Reconstruction**. *BMVC 2025*. [Paper](https://arxiv.org/abs/2212.03221)
- **PFStorer: Personalized Face Restoration and Super-Resolution**. *CVPR 2024*. [Paper](https://arxiv.org/abs/2403.08436)
- **GDPO-SR: Group Direct Preference Optimization for One-Step Generative Image Super-Resolution**. *CVPR 2026*. [Paper](https://arxiv.org/abs/2603.16769) · [Code](https://github.com/Joyies/GDPO)
- **OARS: Process-Aware Online Alignment for Generative Real-World Image Super-Resolution**. *ECCV 2026*. [Paper](https://arxiv.org/abs/2603.12811)

#### Efficient Generative Restoration

- **ResShift: Efficient Diffusion Model for Image Super-resolution by Residual Shifting**. *NeurIPS 2023*. [Paper](https://arxiv.org/abs/2307.12348) · [Code](https://github.com/zsyOAOA/ResShift)
- **Arbitrary-steps Image Super-resolution via Diffusion Inversion**. *CVPR 2025*. [Paper](https://arxiv.org/abs/2412.09013) · [Code](https://github.com/zsyOAOA/InvSR)
- **FideDiff: Efficient Diffusion Model for High-Fidelity Image Motion Deblurring**. *ICLR 2026*. [Paper](https://arxiv.org/abs/2510.01641) · [Code](https://github.com/xyLiu339/FideDiff)
- **SinSR: Diffusion-Based Image Super-Resolution in a Single Step**. *CVPR 2024*. [Paper](https://arxiv.org/abs/2311.14760) · [Code](https://github.com/wyf0912/SinSR)
- **MFSR: MeanFlow Distillation for One Step Real-World Image Super Resolution**. *Preprint 2026*. [Paper](https://arxiv.org/abs/2603.20690) · [Project](https://wrqcodedoge.github.io/mfsr.github.io/)
- **AlloSR²: Rectifying One-Step Super-Resolution to Stay Real via Allomorphic Generative Flows**. *ECCV 2026*. [Paper](https://arxiv.org/abs/2604.19238)
- **DAVI** — Diffusion Prior-Based Amortized Variational Inference for Noisy Inverse Problems. *ECCV 2024*. [Paper](https://arxiv.org/abs/2407.16125) · [Code](https://github.com/mlvlab/DAVI)
- **OSEDiff** — One-Step Effective Diffusion Network for Real-World Image Super-Resolution. *NeurIPS 2024*. [Paper](https://arxiv.org/abs/2406.08177) · [Code](https://github.com/cswry/OSEDiff)
- **PiSA-SR** — Pixel-level and Semantic-level Adjustable Super-resolution: A Dual-LoRA Approach. *CVPR 2025*. [Paper](https://arxiv.org/abs/2412.03017) · [Code](https://github.com/csslc/PiSA-SR)
- **IFCSR: Inference-Free Fidelity-Realism Control for One-Step Diffusion-based Real-World Image Super-Resolution**. *CVPR 2026*. [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Back_IFCSR_Inference-Free_Fidelity-Realism_Control_for_One-Step_Diffusion-based_Real-World_Image_Super-Resolution_CVPR_2026_paper.html)
- **ODTSR** — One-Step Diffusion Transformer for Controllable Real-World Image Super-Resolution. *CVPR 2026*. [Paper](https://arxiv.org/abs/2511.17138)
- **HYPIR** — Harnessing Diffusion-Yielded Score Priors for Image Restoration. *ACM Trans. Graph. 2025*. [Paper](https://arxiv.org/abs/2507.20590) · [Code](https://github.com/XPixelGroup/HYPIR)
- **TinySR: Shallow Diffusion Transformers for Real-World Image Super-Resolution**. *CVPR Findings 2026*. [Paper](https://openaccess.thecvf.com/content/CVPR2026F/html/Dong_TinySR_Shallow_Diffusion_Transformers_for_Real-World_Image_Super-Resolution_CVPRF_2026_paper.html) · [Code](https://github.com/Microtreei/TinySR)
- **FiDeSR: High-Fidelity and Detail-Preserving One-Step Diffusion Super-Resolution**. *CVPR 2026*. [Paper](https://arxiv.org/abs/2603.02692) · [Code](https://github.com/Ar0Kim/FiDeSR)
- **FreqOrtho-SR: Frequency-Guided Orthogonal Expert Learning for Real-World Image Super-Resolution**. *ECCV 2026*. [Paper](https://arxiv.org/abs/2606.28745) · [Code](https://github.com/sonhm3029/FreqOrtho-SR)

### Pretrained Models as Training Supervision

- **GenDeg: Diffusion-based Degradation Synthesis for Generalizable All-In-One Image Restoration**. *CVPR 2025*. [Paper](https://arxiv.org/abs/2411.17687)
- **DiffLoss: unleashing diffusion model as constraint for training image restoration network**. *Preprint 2024*. [Paper](https://arxiv.org/abs/2406.19030) · [Code](https://github.com/JosephTiTan/DiffLoss)
- **CLIP-IQA** — Exploring CLIP for Assessing the Look and Feel of Images. *AAAI 2023*. [Paper](https://arxiv.org/abs/2207.12396) · [Code](https://github.com/IceClear/CLIP-IQA)
- **DeQA-Score** — Teaching Large Language Models to Regress Accurate Image Quality Scores Using Score Distribution. *CVPR 2025*. [Paper](https://arxiv.org/abs/2501.11561)
- **GGT-100K: Generative Ground Truth for Generalizable Real-World Image Restoration**. *Preprint 2026*. [Paper](https://arxiv.org/abs/2605.31039) · [Code](https://github.com/PolyU-VCLab/GGT-100K) · [Project](https://polyu-vclab.github.io/GGT-100K/)
- **Perceive-IR: Learning to Perceive Degradation Better for All-in-One Image Restoration**. *IEEE Trans. Image Process. 2026*. [Paper](https://arxiv.org/abs/2408.15994)
- **Follow-Your-Preference: Towards Preference-Aligned Image Inpainting**. *ICLR 2026*. [Paper](https://arxiv.org/abs/2509.23082) · [Code](https://github.com/shenytzzz/Follow-Your-Preference)
- **SUD²: Supervision by Denoising Diffusion Models for Image Reconstruction**. *Preprint 2023*. [Paper](https://arxiv.org/abs/2303.09642)
- **RGSUD** — Unpaired Image Deraining Using Reward-Guided Self-Reinforcement Strategy. *CVPR 2026*. [Paper](https://arxiv.org/abs/2605.00719)
- **SnowMaster: Comprehensive Real-world Image Desnowing via MLLM with Multi-Model Feedback Optimization**. *CVPR 2025*. [Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Lai_SnowMaster_Comprehensive_Real-world_Image_Desnowing_via_MLLM_with_Multi-Model_Feedback_CVPR_2025_paper.pdf) · [Project](https://alexlai2860.github.io/SnowMaster)
- **Hallucination Score: Towards Mitigating Hallucinations in Generative Image Super-Resolution**. *Preprint 2025*. [Paper](https://arxiv.org/abs/2507.14367)
- **LossAgent: Towards Any Optimization Objectives for Image Processing with LLM Agents**. *Preprint 2024*. [Paper](https://arxiv.org/abs/2412.04090) · [Project](https://github.com/lbc12345/LossAgent)
- **DepictQA** — Depicting Beyond Scores: Advancing Image Quality Assessment through Multi-modal Language Models. *ECCV 2024*. [Paper](https://arxiv.org/abs/2312.08962) · [Project](https://depictqa.github.io)
- **IQA-T1: Tool-based Visual Evidence Reasoning for Image Quality Assessment**. *ECCV 2026*. [Paper](https://arxiv.org/abs/2607.12375) · [Code](https://github.com/zibuyu-02/IQA-T1)

## Foundation Models for Image Restoration

### Pretraining for Image Restoration

#### Multi-Task Pretraining

- **IPT** — Pre-Trained Image Processing Transformer. *CVPR 2021*. [Paper](https://arxiv.org/abs/2012.00364) · [Code](https://github.com/huawei-noah/Pretrained-IPT)
- **TAPE: Task-Agnostic Prior Embedding for Image Restoration**. *ECCV 2022*. [Paper](https://arxiv.org/abs/2203.06074)
- **EDT** — On Efficient Transformer-Based Image Pre-training for Low-Level Vision. *IJCAI 2023*. [Paper](https://ijcai.org/proceedings/2023/121) · [Code](https://github.com/fenglinglwb/EDT)
- **Diffusion-inspired training** — Elucidating and Endowing the Diffusion Training Paradigm for General Image Restoration. *Preprint 2025*. [Paper](https://arxiv.org/abs/2506.21722)

#### Masked Image Modeling

- **RAM** — Restore Anything with Masks: Leveraging Mask Image Modeling for Blind All-in-One Image Restoration. *ECCV 2024*. [Paper](https://arxiv.org/abs/2409.19403) · [Code](https://github.com/DragonisCV/RAM)
- **MAEIP** — Masked Autoencoders as Image Processors. *Preprint 2023*. [Paper](https://arxiv.org/abs/2303.17316) · [Project](https://github.com/DuanHuiyu/MAEIP_CSformer)
- **Dynamic Pre-training: Towards Efficient and Scalable All-in-One Image Restoration**. *Preprint 2024*. [Paper](https://arxiv.org/abs/2404.02154) · [Code](https://github.com/akshaydudhane16/DyNet)

#### Degradation-Aware Pretraining

- **DCPT** — Universal Image Restoration Pre-training via Degradation Classification. *ICLR 2025*. [Paper](https://arxiv.org/abs/2501.15510) · [Code](https://github.com/MILab-PKU/dcpt)
- **ConStyle v2: A Strong Prompter for All-in-One Image Restoration**. *Preprint 2024*. [Paper](https://arxiv.org/abs/2406.18242) · [Code](https://github.com/Dongqi-Fan/ConStyle_v2)
- **BDG** — Bridging Degradation Discrimination and Generation for Universal Image Restoration. *ICLR 2026*. [Paper](https://arxiv.org/abs/2602.00579) · [Code](https://github.com/MILab-PKU/BDG)
- **DegAE: A New Pretraining Paradigm for Low-Level Vision**. *CVPR 2023*. [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Liu_DegAE_A_New_Pretraining_Paradigm_for_Low-Level_Vision_CVPR_2023_paper.html) · [Code](https://github.com/lyh-18/DegAE_DegradationAutoencoder) · [Project](https://xpixel.group/2022/10/20/DegAE.html)

### Unified Restoration Modeling

#### Multi-Task Joint Training

- **UniRestorer: Universal Image Restoration via Adaptively Estimating Image Degradation at Proper Granularity**. *ICLR 2026*. [Paper](https://arxiv.org/abs/2412.20157) · [Code](https://github.com/mrluin/UniRestorer)
- **All-in-One Bad Weather Removal** — All in One Bad Weather Removal Using Architectural Search. *CVPR 2020*. [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_All_in_One_Bad_Weather_Removal_Using_Architectural_Search_CVPR_2020_paper.html)
- **TransWeather: Transformer-Based Restoration of Images Degraded by Adverse Weather Conditions**. *CVPR 2022*. [Paper](https://arxiv.org/abs/2111.14813) · [Code](https://github.com/jeya-maria-jose/TransWeather)
- **IDR** — Ingredient-Oriented Multi-Degradation Learning for Image Restoration. *CVPR 2023*. [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Ingredient-Oriented_Multi-Degradation_Learning_for_Image_Restoration_CVPR_2023_paper.pdf) · [Code](https://github.com/Jinghaoleven/IDR-Ingredients-oriented-Degradation-Reformulation)
- **AirNet** — All-in-One Image Restoration for Unknown Corruption. *CVPR 2022*. [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_All-in-One_Image_Restoration_for_Unknown_Corruption_CVPR_2022_paper.pdf) · [Code](https://github.com/XLearning-SCU/2022-CVPR-AirNet)
- **PromptIR: Prompting for All-in-One Image Restoration**. *NeurIPS 2023*. [Paper](https://arxiv.org/abs/2306.13090) · [Code](https://github.com/va1shn9v/PromptIR)
- **OneRestore: A Universal Restoration Framework for Composite Degradation**. *ECCV 2024*. [Paper](https://arxiv.org/abs/2407.04621) · [Code](https://github.com/gy65896/OneRestore)
- **Towards Effective Multiple-in-One Image Restoration: A Sequential and Prompt Learning Strategy**. *Preprint 2024*. [Paper](https://arxiv.org/abs/2401.03379) · [Code](https://github.com/Xiangtaokong/MiOIR)
- **AllRestorer: All-in-one transformer for image restoration under composite degradations**. *Preprint 2024*. [Paper](https://arxiv.org/abs/2411.10708)

#### Visual In-Context Learning

- **PromptGIP** — Unifying Image Processing as Visual Prompting Question Answering. *ICML 2024*. [Paper](https://arxiv.org/abs/2310.10513) · [Code](https://github.com/lyh-18/PromptGIP)
- **GenLV** — Learning A Low-Level Vision Generalist via Visual Task Prompt. *ACM MM 2024*. [Paper](https://arxiv.org/abs/2408.08601) · [Code](https://github.com/chxy95/GenLV)
- **Painter** — Images Speak in Images: A Generalist Painter for In-Context Visual Learning. *CVPR 2023*. [Paper](https://arxiv.org/abs/2212.02499) · [Code](https://github.com/baaivision/Painter)
- **GenLV scaling** — Exploring Scalable Unified Modeling for General Low-Level Vision. *Preprint 2025*. [Paper](https://arxiv.org/abs/2507.14801)
- **Hidden-Shot: Towards One-Shot Task Generalization for Low-Level Vision Generalist Models**. *Preprint 2026*. [Paper](https://arxiv.org/abs/2607.01535)
- **LaVin-DiT: Large Vision Diffusion Transformer**. *CVPR 2025*. [Paper](https://arxiv.org/abs/2411.11505) · [Code](https://github.com/DerrickWang005/LaVin-DiT)

#### Multi-Task Generative Modeling

- **FoundIR: Unleashing Million-scale Training Data to Advance Foundation Models for Image Restoration**. *ICCV 2025*. [Paper](https://arxiv.org/abs/2412.01427) · [Code](https://github.com/House-Leo/FoundIR)
- **Lumina-OmniLV: A Unified Multimodal Framework for General Low-Level Vision**. *Preprint 2025*. [Paper](https://arxiv.org/abs/2504.04903) · [Code](https://github.com/Andrew0613/Lumina-Omnilv) · [Project](https://andrew0613.github.io/OmniLV_page/)
- **FoundIR-v2: Optimizing Pre-Training Data Mixtures for Image Restoration Foundation Model**. *CVPR 2026*. [Paper](https://arxiv.org/abs/2512.09282) · [Code](https://github.com/cschenxiang/FoundIR-v2)
- **UARE: A Unified Vision-Language Model for Image Quality Assessment, Restoration, and Enhancement**. *CVPR 2026*. [Paper](https://arxiv.org/abs/2512.06750) · [Code](https://github.com/lwq20020127/UARE)
- **SLAIR: Structured Latent Flow Matching for All-in-One Image Restoration**. *ECCV 2026*. [Paper](https://link.springer.com/chapter/10.1007/978-3-032-37517-9_3) · [Code](https://github.com/Fightforql/SLAIR) · [Project](https://fightforql.github.io/SLAIR-page/)
- **Palette: Image-to-Image Diffusion Models**. *Preprint 2021*. [Paper](https://arxiv.org/abs/2111.05826) · [Project](https://iterative-refinement.github.io/palette/)

### Transfer and Adaptation

#### Transfer to New Tasks and Domains

- **AdaptIR** — Parameter Efficient Adaptation for Image Restoration with Heterogeneous Mixture-of-Experts. *NeurIPS 2024*. [Paper](https://arxiv.org/abs/2312.08881) · [Code](https://github.com/csguoh/AdaptIR)
- **PROD + CoLoRA** — Contribution-based Low-Rank Adaptation with Pre-training Model for Real Image Restoration. *ECCV 2024*. [Paper](https://arxiv.org/abs/2408.01099) · [Project](https://janeyeon.github.io/colora/)
- **ProRes: Exploring Degradation-aware Visual Prompt for Universal Image Restoration**. *Preprint 2023*. [Paper](https://arxiv.org/abs/2306.13653) · [Code](https://github.com/leonmakise/ProRes)
- **AdaIR (adapters)** — AdaIR: Exploiting Underlying Similarities of Image Restoration Tasks with Adapters. *Preprint 2024*. [Paper](https://arxiv.org/abs/2404.11475)
- **GRIDS: Grouped Multiple-Degradation Restoration with Image Degradation Similarity**. *ECCV 2024*. [Paper](https://arxiv.org/abs/2407.12273)
- **DDTNet: Degradation Disentanglement and Transfer Network for Test-Time All-in-One De-weathering Adaptation**. *Preprint 2026*. [Paper](https://arxiv.org/abs/2606.16298)
- **Degradation-consistent TTA** — Degradation-Consistent Test-Time Adaptation for All-in-One Image Restoration. *CVPR 2026*. [Paper](https://openaccess.thecvf.com/content/CVPR2026/papers/Tang_Degradation-Consistent_Test-Time_Adaptation_for_All-in-One_Image_Restoration_CVPR_2026_paper.pdf) · [Code](https://github.com/tonia86/DCTTA)

#### Continual Image Restoration

- **RestoreMore** — Learning to Restore More: Continual Capability Expansion for Pretrained Image Restoration Models. *Preprint 2026*. [Paper](https://arxiv.org/abs/2608.30305)
- **Continual weather removal** — Continual All-in-One Adverse Weather Removal with Knowledge Replay on a Unified Network Structure. *Preprint 2024*. [Paper](https://arxiv.org/abs/2403.07292) · [Code](https://github.com/xiaojihh/CL_all-in-one)
- **MINI-Conv** — A Minimalistic Unified Framework for Incremental Learning across Image Restoration Tasks. *NeurIPS 2025*. [Paper](https://openreview.net/pdf/13e99d7ed18b26efa7b85826e1e8a99df5c73f39.pdf)
- **Restoring Without Forgetting: Continual Learning Across Image Degradations**. *Preprint 2026*. [Paper](https://arxiv.org/abs/2608.23799) · [Code](https://github.com/AlifAshrafee/Restoring-Without-Forgetting)

## Agentic Image Restoration

### Task Planning

- **JarvisIR: Elevating Autonomous Driving Perception with Intelligent Image Restoration**. *CVPR 2025*. [Paper](https://arxiv.org/abs/2504.04158) · [Code](https://github.com/LYL1015/JarvisIR) · [Project](https://cvpr2025-jarvisir.github.io/)
- **AgenticIR** — An Intelligent Agentic System for Complex Image Restoration Problems. *ICLR 2025*. [Paper](https://arxiv.org/abs/2410.17809) · [Code](https://github.com/Kaiwen-Zhu/AgenticIR) · [Project](https://kaiwen-zhu.github.io/research/agenticir)
- **MAIR** — Multi-Agent Image Restoration. *Int. J. Comput. Vis. 2026*. [Paper](https://arxiv.org/abs/2503.09403) · [Project](https://villa.jianzhang.tech/publication/200604/)
- **RestoreAgent: Autonomous Image Restoration Agent via Multimodal Large Language Models**. *NeurIPS 2024*. [Paper](https://arxiv.org/abs/2407.18035) · [Project](https://haoyuchen.com/RestoreAgent)
- **OPERA: An Agent for Image Restoration with End-to-End Joint Planning-Execution Optimization**. *Preprint 2026*. [Paper](https://arxiv.org/abs/2605.22104) · [Code](https://github.com/xsyshuishui/Opera)

### Tool Selection

- **TIR-Agent: Training an Explorative and Efficient Agent for Image Restoration**. *ECCV 2026*. [Paper](https://arxiv.org/abs/2603.27742)
- **Restore-R1: Efficient Image Restoration Agents via Reinforcement Learning with Multimodal LLM Perceptual Feedback**. *CVPR Findings 2026*. [Paper](https://arxiv.org/abs/2512.18599)
- **FAPE-IR: Frequency-Aware Planning and Execution Framework for All-in-One Image Restoration**. *CVPR 2026*. [Paper](https://arxiv.org/abs/2511.14099) · [Code](https://github.com/Programmergg/FAPE-IR)
- **ExpertFusion** — Beyond Sequential Tools: A Unified VLM Agent System for Photographic Post-Processing via Dynamic Multi-Expert Fusion. *CVPR 2026*. [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Xiong_Beyond_Sequential_Tools_A_Unified_VLM_Agent_System_for_Photographic_CVPR_2026_paper.html)
- **DiTTo: Scalable Order-aware All-in-One Image Restoration Agent**. *Preprint 2026*. [Paper](https://arxiv.org/abs/2605.30915) · [Project](https://cmlab-korea.github.io/DiTTo/)

### Feedback and Refinement

- **HybridAgent** — Hybrid Agents for Image Restoration. *CVPR 2026*. [Paper](https://arxiv.org/abs/2503.10120)
- **HarnessIR: Harnessing Multimodal Foundation Models for Universal Real-World Image Restoration**. *Preprint 2026*. [Paper](https://arxiv.org/abs/2610.10133) · [Code](https://github.com/PolyU-VCLab/HarnessIR)
- **Q-Agent: Quality-Driven Chain-of-Thought Image Restoration Agent through Robust Multimodal Large Language Model**. *Preprint 2025*. [Paper](https://arxiv.org/abs/2504.07148)
- **RAR** — Restore, Assess, Repeat: A Unified Framework for Iterative Image Restoration. *CVPR 2026*. [Paper](https://arxiv.org/abs/2603.26385) · [Code](https://github.com/saic-fi/RAR) · [Project](https://restore-assess-repeat.github.io/)
- **4KAgent: Agentic Any Image to 4K Super-Resolution**. *NeurIPS 2025*. [Paper](https://arxiv.org/abs/2507.07105) · [Code](https://github.com/taco-group/4KAgent) · [Project](https://4kagent.github.io/)
- **Clarity ChatGPT: An Interactive and Adaptive Processing System for Image Restoration and Enhancement**. *Preprint 2023*. [Paper](https://arxiv.org/abs/2311.11695)
- **VLM-IMI** — Adapting Large VLMs with Iterative and Manual Instructions for Generative Low-light Enhancement. *CVPR Findings 2026*. [Paper](https://arxiv.org/abs/2507.18064) · [Code](https://github.com/sunxiaoran01/VLM-IMI)

### Experience Retrieval

- **SkillIR: Evolving Scene-Aware Skills for Agentic Image Restoration**. *Preprint 2026*. [Paper](https://arxiv.org/abs/2609.21468)
- **SEAR** — Self-evolving Agentic Image Restoration via Deliberate Planning and Intuitive Execution. *ECCV 2026*. [Paper](https://arxiv.org/abs/2606.28971)
- **Causal-AgentIR: Self-Evolving Causal Memory for Adaptive Image Restoration Agents**. *Preprint 2026*. [Paper](https://arxiv.org/abs/2607.21125)
- **EvoIR-Agent: Self-Evolving Image Restoration Agentic System via Experience-Driven Learning**. *Preprint 2026*. [Paper](https://arxiv.org/abs/2605.22208) · [Project](https://github.com/rightleft-123/EvoIRAgent)
- **PaAgent: Portrait-Aware Image Restoration Agent via Subjective-Objective Reinforcement Learning**. *Preprint 2026*. [Paper](https://arxiv.org/abs/2603.17055) · [Project](https://wyjgr.github.io/PaAgent.html)

