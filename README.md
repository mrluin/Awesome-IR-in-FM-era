<h1 align="center">Awesome Image Restoration<br>in the Foundation Model Era</h1>

<p align="center">
  A curated reading list on foundation models and agents for image restoration.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Image-Restoration-2563eb?style=flat-square" alt="Topic: Image Restoration">
  <img src="https://img.shields.io/badge/Foundation-Models-7c3aed?style=flat-square" alt="Topic: Foundation Models">
  <img src="https://img.shields.io/badge/Agentic-Restoration-0f766e?style=flat-square" alt="Topic: Agentic Restoration">
</p>

The main list follows the works reviewed Sections II–IV of *A Survey on Image Restoration in the Foundation Model Era*.



<a id="contents"></a>

## 🗂️ Contents

- [🧩 Image Restoration with Foundation Models](#image-restoration-with-foundation-models)
  - [Vision and Language Models](#image-restoration-with-vision-and-language-models)
  - [Generative Priors](#image-restoration-with-generative-priors)
  - [Training Resources and Quality Signals](#training-resources-and-quality-signals)
- [🧠 Restoration-Oriented Foundation Models](#restoration-oriented-foundation-models)
  - [Pretraining](#pretraining-for-image-restoration)
  - [Unified Restoration Modeling](#unified-restoration-modeling)
  - [Transfer and Adaptation](#transfer-and-adaptation)
- [🤖 Agentic Image Restoration](#agentic-image-restoration)
  - [Task Planning](#task-planning)
  - [Tool Selection](#tool-selection)
  - [Feedback and Refinement](#feedback-and-refinement)
  - [Experience Retrieval](#experience-retrieval)


<a id="image-restoration-with-foundation-models"></a>

## 🧩 Image Restoration with Foundation Models

### Image Restoration with Vision and Language Models

#### Visual Features and Segmentation Priors

- **GramSR: Visual Feature Conditioning for Diffusion-Based Super-Resolution**\
  *ICPR 2026* · [📄 Paper](https://arxiv.org/abs/2604.25457) · [💻 Code](https://github.com/aimagelab/GramSR)

- **RAW-CLIP Fusion: Unleashing Semantic-Aware Denoising for Sensor-Agnostic Low-Light Imaging** (CLD)\
  *IEEE Trans. Image Process. 2026* · [📄 Paper](https://doi.org/10.1109/TIP.2026.3692025)

- **Super-Resolution in The Right Latent Space: A Frozen Vision-Foundation Substrate**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2610.04781)

- **Intra and Inter Parser-Prompted Transformers for Effective Image Restoration**\
  *AAAI 2025* · [📄 Paper](https://arxiv.org/abs/2503.14037)

- **Boosting Image Restoration via Priors from Pre-trained Models** (PTG-RM)\
  *CVPR 2024* · [📄 Paper](https://arxiv.org/abs/2403.06793)

- **Distilling Semantic Priors from SAM to Efficient Image Restoration Models** (SAM distillation)\
  *CVPR 2024* · [📄 Paper](https://arxiv.org/abs/2403.16368) · [🌐 Project](https://github.com/WeiLi-THU/SAM4IR)

- **SAM-Deblur: Let Segment Anything Boost Image Deblurring**\
  *ICASSP 2024* · [📄 Paper](https://arxiv.org/abs/2309.02270) · [💻 Code](https://github.com/HPLQAQ/SAM-Deblur) · [🌐 Project](https://hplqaq.github.io/projects/sam-deblur)

- **Unleashing the Potential of the Semantic Latent Space in Diffusion Models for Image Dehazing** (DiffLI²D)\
  *ECCV 2024* · [📄 Paper](https://arxiv.org/abs/2509.20091)

- **A Dive into SAM Prior in Image Restoration** (SAM priors)\
  *arXiv 2023* · [📄 Paper](https://arxiv.org/abs/2305.13620)

- **Multi-task Image Restoration Guided By Robust DINO Features** (DINO-IR)\
  *arXiv 2023* · [📄 Paper](https://arxiv.org/abs/2312.01677)

#### Degradation and Instruction Conditioning

- **Beyond Uniform Restoration: Empowering All-in-One Restoration with Pixel-Level Multimodal Guidance** (MGN-AIR)\
  *ACM MM 2026* · [📄 Paper](https://arxiv.org/abs/2608.09482)

- **ClearAIR: A Human-Visual-Perception-Inspired All-in-One Image Restoration**\
  *AAAI 2026* · [📄 Paper](https://arxiv.org/abs/2601.02763) · [💻 Code](https://github.com/House-yuyu/ClearAIR)

- **Leveraging Multimodal Large Language Models for All-in-One Image Restoration via a Mixture of Frequency Experts**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2605.11444)

- **QuReC: All-in-One Image Restoration with Query-Specific Guidance and Local-Global Response Calibration**\
  *ACM MM 2026* · [📄 Paper](https://arxiv.org/abs/2607.15097) · [💻 Code](https://github.com/zhoushen1/QuReC)

- **SLER-IR: Spherical Layer-wise Expert Routing for All-in-One Image Restoration**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2603.05940) · [🌐 Project](https://github.com/PSR666/SLER-IR)

- **Textual prompt guided image restoration** (TextPromptIR)\
  *Eng. Appl. Artif. Intell. 2025* · [📄 Paper](https://arxiv.org/abs/2312.06162) · [💻 Code](https://github.com/MoTong-AI-studio/TextPromptIR)

- **VL-UR: Vision-Language-guided Universal Restoration of Images Degraded by Adverse Weather Conditions**\
  *arXiv 2025* · [📄 Paper](https://arxiv.org/abs/2504.08219)

- **AWRaCLe: All-Weather Image Restoration using Visual In-Context Learning**\
  *arXiv 2024* · [📄 Paper](https://arxiv.org/abs/2409.00263) · [💻 Code](https://github.com/sudraj2002/AWRaCLe)

- **Controlling Vision-Language Models for Multi-Task Image Restoration** (DA-CLIP)\
  *ICLR 2024* · [📄 Paper](https://arxiv.org/abs/2310.01018) · [💻 Code](https://github.com/Algolzw/daclip-uir)

- **Improving Image Restoration through Removing Degradations in Textual Representations** (TextDegRemoval)\
  *CVPR 2024* · [📄 Paper](https://arxiv.org/abs/2312.17334) · [💻 Code](https://github.com/mrluin/TextualDegRemoval)

- **InstructIR: High-Quality Image Restoration Following Human Instructions**\
  *ECCV 2024* · [📄 Paper](https://arxiv.org/abs/2401.16468) · [💻 Code](https://github.com/mv-lab/InstructIR) · [🌐 Project](https://mv-lab.github.io/InstructIR/)

- **Language-driven All-in-one Adverse Weather Removal** (Language-driven weather removal)\
  *CVPR 2024* · [📄 Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Yang_Language-driven_All-in-one_Adverse_Weather_Removal_CVPR_2024_paper.html)

- **LoRA-IR: Taming Low-Rank Experts for Efficient All-in-One Image Restoration**\
  *arXiv 2024* · [📄 Paper](https://arxiv.org/abs/2410.15385) · [💻 Code](https://github.com/shallowdream204/LoRA-IR)

- **Training-Free Large Model Priors for Multiple-in-One Image Restoration** (LMDIR)\
  *arXiv 2024* · [📄 Paper](https://arxiv.org/abs/2407.13181)

- **UniProcessor: A Text-induced Unified Low-level Image Processor**\
  *ECCV 2024* · [📄 Paper](https://link.springer.com/chapter/10.1007/978-3-031-72855-6_11) · [💻 Code](https://github.com/IntMeGroup/UniProcessor)

- **Unpaired Photo-realistic Image Deraining with Energy-informed Diffusion Model** (UPID-EDM)\
  *ACM MM 2024* · [📄 Paper](https://arxiv.org/abs/2407.17193)

#### Language Model Adaptation

- **Perceive, Understand and Restore: Real-World Image Super-Resolution with Autoregressive Multimodal Generative Models** (PURE)\
  *ICCV 2025* · [📄 Paper](https://arxiv.org/abs/2503.11073)

- **Beyond Text: Frozen Large Language Models in Visual Signal Comprehension**\
  *CVPR 2024* · [📄 Paper](https://arxiv.org/abs/2403.07874) · [💻 Code](https://github.com/zh460045050/V2L-Tokenizer)

- **LM4LV: A Frozen Large Language Model for Low-level Vision Tasks**\
  *arXiv 2024* · [📄 Paper](https://arxiv.org/abs/2405.15734) · [💻 Code](https://github.com/bytetriper/LM4LV)

### Image Restoration with Generative Priors

#### Pretrained Generative Priors

- **DCDP: Decoupled Data Consistency via Diffusion Purification for Inverse Problems**\
  *ICCP 2026* · [📄 Paper](https://ieeexplore.ieee.org/document/11668875/)

- **Efficient Zero-shot Inpainting with Decoupled Diffusion Guidance**\
  *ICLR 2026* · [📄 Paper](https://arxiv.org/abs/2512.18365) · [💻 Code](https://github.com/YazidJanati/ding)

- **A Simple Combination of Diffusion Models for Better Quality Trade-Offs in Image Denoising** (LCDD)\
  *CVPR Workshops 2025* · [📄 Paper](https://openaccess.thecvf.com/content/CVPR2025W/NTIRE/html/Dornbusch_A_Simple_Combination_of_Diffusion_Models_for_Better_Quality_Trade-Offs_CVPRW_2025_paper.html)

- **Improving Diffusion Inverse Problem Solving with Decoupled Noise Annealing**\
  *CVPR 2025* · [📄 Paper](https://arxiv.org/abs/2407.01521) · [🌐 Project](https://daps-inverse-problem.github.io/)

- **PnP-Flow: Plug-and-Play Image Restoration with Flow Matching**\
  *ICLR 2025* · [📄 Paper](https://arxiv.org/abs/2410.02423) · [💻 Code](https://github.com/annegnx/PnP-Flow)

- **Zero-Shot Low-Light Image Enhancement via Latent Diffusion Models** (LLIEDiff)\
  *AAAI 2025* · [📄 Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32398)

- **A Variational Perspective on Solving Inverse Problems with Diffusion Models** (RED-Diff)\
  *ICLR 2024* · [📄 Paper](https://arxiv.org/abs/2305.04391) · [💻 Code](https://github.com/NVlabs/RED-diff)

- **D-Flow: Differentiating through Flows for Controlled Generation**\
  *ICML 2024* · [📄 Paper](https://arxiv.org/abs/2402.14017)

- **Diffusion Priors for Variational Likelihood Estimation and Image Denoising**\
  *NeurIPS 2024* · [📄 Paper](https://arxiv.org/abs/2410.17521) · [💻 Code](https://github.com/HUST-Tan/DiffusionVI)

- **DMPlug: A Plug-in Method for Solving Inverse Problems with Diffusion Models**\
  *NeurIPS 2024* · [📄 Paper](https://arxiv.org/abs/2405.16749) · [💻 Code](https://github.com/sun-umn/DMPlug)

- **DreamClean: Restoring Clean Image Using Deep Diffusion Prior**\
  *ICLR 2024* · [📄 Paper](https://proceedings.iclr.cc/paper_files/paper/2024/hash/814c2fe415df792624766894cec09f00-Abstract-Conference.html)

- **Fast Diffusion EM: a diffusion model for blind inverse problems with application to deconvolution**\
  *WACV 2024* · [📄 Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Laroche_Fast_Diffusion_EM_A_Diffusion_Model_for_Blind_Inverse_Problems_WACV_2024_paper.pdf)

- **Flow Priors for Linear Inverse Problems via Iterative Corrupted Trajectory Matching** (ICTM)\
  *NeurIPS 2024* · [📄 Paper](https://proceedings.nips.cc/paper_files/paper/2024/hash/698570ae5ec88e07e9f4547f831b4593-Abstract-Conference.html) · [💻 Code](https://github.com/YasminZhang/ICTM)

- **Monte Carlo guided Denoising Diffusion models for Bayesian linear inverse problems.** (MCGDiff)\
  *ICLR 2024* · [📄 Paper](https://proceedings.iclr.cc/paper_files/paper/2024/hash/bfb3c1db0deda449ff4027f77dd48704-Abstract-Conference.html)

- **Principled Probabilistic Imaging using Diffusion Models as Plug-and-Play Priors** (PnP-DM)\
  *NeurIPS 2024* · [📄 Paper](https://arxiv.org/abs/2405.18782) · [💻 Code](https://github.com/zihuiwu/PnP-DM-public) · [🌐 Project](https://imaging.cms.caltech.edu/pnpdm/)

- **Prompt-tuning Latent Diffusion Models for Inverse Problems** (P2L)\
  *ICML 2024* · [📄 Paper](https://proceedings.mlr.press/v235/chung24b.html)

- **Test-Time Degradation Adaptation for Open-Set Image Restoration**\
  *ICML 2024* · [📄 Paper](https://arxiv.org/abs/2312.02197) · [💻 Code](https://github.com/XLearning-SCU/2024-ICML-TAO)

- **Text-guided Explorable Image Super-resolution** (Text-guided explorable SR)\
  *CVPR 2024* · [📄 Paper](https://arxiv.org/abs/2403.01124) · [💻 Code](https://github.com/KVGandikota/Text-guidedSR)

- **Denoising Diffusion Models for Plug-and-Play Image Restoration**\
  *CVPR Workshops 2023* · [📄 Paper](https://arxiv.org/abs/2305.08995) · [💻 Code](https://github.com/yuanzhi-zhu/DiffPIR)

- **Diffusion Posterior Sampling for General Noisy Inverse Problems**\
  *ICLR 2023* · [📄 Paper](https://arxiv.org/abs/2209.14687) · [💻 Code](https://github.com/DPS2022/diffusion-posterior-sampling)

- **GibbsDDRM: A Partially Collapsed Gibbs Sampler for Solving Blind Inverse Problems with Denoising Diffusion Restoration**\
  *ICML 2023* · [📄 Paper](https://arxiv.org/abs/2301.12686) · [💻 Code](https://github.com/sony/gibbsddrm)

- **Parallel Diffusion Models of Operator and Image for Blind Inverse Problems**\
  *CVPR 2023* · [📄 Paper](https://arxiv.org/abs/2211.10656)

- **Solving Linear Inverse Problems Provably via Posterior Sampling with Latent Diffusion Models** (PSLD)\
  *NeurIPS 2023* · [📄 Paper](https://arxiv.org/abs/2307.00619)

- **Zero-Shot Image Restoration Using Denoising Diffusion Null-Space Model**\
  *ICLR 2023* · [📄 Paper](https://arxiv.org/abs/2212.00490) · [💻 Code](https://github.com/wyhuai/DDNM)

- **Denoising Diffusion Restoration Models**\
  *NeurIPS 2022* · [📄 Paper](https://arxiv.org/abs/2201.11793) · [💻 Code](https://github.com/bahjat-kawar/ddrm) · [🌐 Project](https://ddrm-ml.github.io/)

- **RePaint: Inpainting Using Denoising Diffusion Probabilistic Models**\
  *CVPR 2022* · [📄 Paper](https://arxiv.org/abs/2201.09865) · [💻 Code](https://github.com/andreas128/RePaint)

- **PULSE: Self-Supervised Photo Upsampling via Latent Space Exploration of Generative Models**\
  *CVPR 2020* · [📄 Paper](https://arxiv.org/abs/2003.03808)

#### Conditional Generative Restoration

Includes task-specific generative models reviewed alongside methods that reuse pretrained foundation-model priors.

- **DNF-SR: Dual-Input and Negative-Aware Feature Fine-Tuning for Real-World Image Super-Resolution**\
  *CVPR 2026* · [📄 Paper](https://arxiv.org/abs/2609.15120)

- **Edit2Restore: Few-Shot Image Restoration via Parameter-Efficient Adaptation of Pre-trained Editing Models**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2601.03391) · [💻 Code](https://github.com/makinyilmaz/Edit2Restore)

<a id="fill2sr"></a>

- **Fill2SR: Repurposing Inpainting Diffusion Transformers for Real-World Super-Resolution**\
  *ECCV 2026* · [📄 Paper](https://arxiv.org/abs/2609.33582)

- **GDPO-SR: Group Direct Preference Optimization for One-Step Generative Image Super-Resolution**\
  *CVPR 2026* · [📄 Paper](https://arxiv.org/abs/2603.16769) · [💻 Code](https://github.com/Joyies/GDPO)

- **LucidFlux: Caption-Free Photo-Realistic Image Restoration via a Large-Scale Diffusion Transformer**\
  *ICLR 2026* · [📄 Paper](https://openreview.net/forum?id=qrCAGOE483) · [💻 Code](https://github.com/W2GenAI-Lab/LucidFlux) · [🌐 Project](https://w2genai-lab.github.io/LucidFlux/)

- **OARS: Process-Aware Online Alignment for Generative Real-World Image Super-Resolution**\
  *ECCV 2026* · [📄 Paper](https://arxiv.org/abs/2603.12811)

- **RestoreVAR: Visual Autoregressive Generation for All-in-One Image Restoration**\
  *ICLR 2026* · [📄 Paper](https://arxiv.org/abs/2505.18047) · [💻 Code](https://github.com/sudraj2002/RestoreVAR)

- **Time-Aware One Step Diffusion Network for Real-World Image Super-Resolution**\
  *CVPR 2026* · [📄 Paper](https://arxiv.org/abs/2508.16557)

- **UnSCAR: Universal, Scalable, Controllable, and Adaptable Image Restoration**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2603.07406)

- **Acquire and then Adapt: Squeezing out Text-to-Image Model for Image Restoration** (FluxIR)\
  *CVPR 2025* · [📄 Paper](https://arxiv.org/abs/2504.15159)

- **ADIR: Adaptive Diffusion for Image Reconstruction**\
  *BMVC 2025* · [📄 Paper](https://arxiv.org/abs/2212.03221)

- **DarkDiff: Advancing Low-Light Raw Enhancement by Retasking Diffusion Models for Camera ISP**\
  *arXiv 2025* · [📄 Paper](https://arxiv.org/abs/2505.23743)

- **DeblurDiff: Real-World Image Deblurring with Generative Diffusion Models**\
  *NeurIPS 2025* · [📄 Paper](https://arxiv.org/abs/2502.03810) · [💻 Code](https://github.com/kkkls/DeblurDiff)

- **DiT4SR: Taming Diffusion Transformer for Real-World Image Super-Resolution**\
  *ICCV 2025* · [📄 Paper](https://arxiv.org/abs/2503.23580) · [💻 Code](https://github.com/Adam-duan/DiT4SR) · [🌐 Project](https://adam-duan.github.io/projects/dit4sr/)

- **Fine-structure Preserved Real-world Image Super-resolution via Transfer VAE Training** (TVT)\
  *ICCV 2025* · [📄 Paper](https://arxiv.org/abs/2507.20291) · [💻 Code](https://github.com/Joyies/TVT)

- **Improving Conditional Diffusion Models through Re-Noising from Unconditional Diffusion Priors** (Bi-Noising)\
  *WACV 2025* · [📄 Paper](https://openaccess.thecvf.com/content/WACV2025/html/Mei_Improving_Conditional_Diffusion_Models_through_Re-Noising_from_Unconditional_Diffusion_Priors_WACV_2025_paper.html)

- **InstructRestore: Region-Customized Image Restoration with Human Instructions**\
  *arXiv 2025* · [📄 Paper](https://arxiv.org/abs/2503.24357) · [💻 Code](https://github.com/shuaizhengliu/InstructRestore)

- **Towards Enhanced Image Inpainting: Mitigating Unwanted Object Insertion and Preserving Color Consistency** (ASUKA)\
  *CVPR 2025* · [📄 Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Wang_Towards_Enhanced_Image_Inpainting_Mitigating_Unwanted_Object_Insertion_and_Preserving_CVPR_2025_paper.pdf) · [💻 Code](https://github.com/Yikai-Wang/asuka-misato) · [🌐 Project](https://yikai-wang.github.io/asuka/)

- **Unpaired Deblurring via Decoupled Diffusion Model** (UID-Diff)\
  *arXiv 2025* · [📄 Paper](https://arxiv.org/abs/2502.01522)

- **Diff-Plugin: Revitalizing Details for Diffusion-based Low-level Tasks**\
  *CVPR 2024* · [📄 Paper](https://arxiv.org/abs/2403.00644) · [🌐 Project](https://yuhaoliu7456.github.io/Diff-Plugin/)

- **DiffBIR: Toward Blind Image Restoration with Generative Diffusion Prior**\
  *ECCV 2024* · [📄 Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/07690.pdf) · [💻 Code](https://github.com/XPixelGroup/DiffBIR)

<a id="dreamclear"></a>

- **DreamClear: High-Capacity Real-World Image Restoration with Privacy-Safe Dataset Curation**\
  *NeurIPS 2024* · [📄 Paper](https://arxiv.org/abs/2410.18666) · [💻 Code](https://github.com/shallowdream204/DreamClear)

- **Exploiting Diffusion Prior for Real-World Image Super-Resolution**\
  *Int. J. Comput. Vis. 2024* · [📄 Paper](https://arxiv.org/abs/2305.07015) · [💻 Code](https://github.com/IceClear/StableSR)

<a id="multimodal-prompt-perceiver"></a>

- **Multimodal Prompt Perceiver: Empower Adaptiveness, Generalizability and Fidelity for All-in-One Image Restoration**\
  *CVPR 2024* · [📄 Paper](https://arxiv.org/abs/2312.02918) · [💻 Code](https://github.com/hhb072/MPerceiver-Code)

- **PFStorer: Personalized Face Restoration and Super-Resolution**\
  *CVPR 2024* · [📄 Paper](https://arxiv.org/abs/2403.08436)

- **Pixel-Aware Stable Diffusion for Realistic Image Super-resolution and Personalized Stylization**\
  *ECCV 2024* · [📄 Paper](https://arxiv.org/abs/2308.14469) · [💻 Code](https://github.com/yangxy/PASD)

- **PromptFix: You Prompt and We Fix the Photo**\
  *NeurIPS 2024* · [📄 Paper](https://arxiv.org/abs/2405.16785) · [🌐 Project](https://www.yongshengyu.com/PromptFix-Page)

- **ReFIR: Grounding Large Restoration Models with Retrieval Augmentation**\
  *NeurIPS 2024* · [📄 Paper](https://arxiv.org/abs/2410.05601) · [💻 Code](https://github.com/csguoh/ReFIR)

- **Scaling Up to Excellence: Practicing Model Scaling for Photo-Realistic Image Restoration In the Wild**\
  *CVPR 2024* · [📄 Paper](https://arxiv.org/abs/2401.13627) · [💻 Code](https://github.com/Fanghua-Yu/SUPIR)

- **SeeSR: Towards Semantics-Aware Real-World Image Super-Resolution**\
  *CVPR 2024* · [📄 Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Wu_SeeSR_Towards_Semantics-Aware_Real-World_Image_Super-Resolution_CVPR_2024_paper.pdf) · [💻 Code](https://github.com/cswry/SeeSR)

- **Image Restoration with Mean-Reverting Stochastic Differential Equations** (IR-SDE)\
  *ICML 2023* · [📄 Paper](https://arxiv.org/abs/2301.11699) · [💻 Code](https://github.com/Algolzw/image-restoration-sde)

- **I²SB: Image-to-Image Schrödinger Bridge**\
  *ICML 2023* · [📄 Paper](https://arxiv.org/abs/2302.05872) · [💻 Code](https://github.com/NVlabs/I2SB) · [🌐 Project](https://i2sb.github.io/)

- **Towards Robust Blind Face Restoration with Codebook Lookup Transformer** (CodeFormer)\
  *NeurIPS 2022* · [📄 Paper](https://arxiv.org/abs/2206.11253) · [💻 Code](https://github.com/sczhou/CodeFormer) · [🌐 Project](https://shangchenzhou.com/projects/CodeFormer/)

- **GLEAN: Generative Latent Bank for Large-Factor Image Super-Resolution**\
  *CVPR 2021* · [📄 Paper](https://arxiv.org/abs/2012.00739) · [🌐 Project](https://mmlab-ntu.github.io/project/glean/)

- **Image Super-Resolution via Iterative Refinement** (SR3)\
  *arXiv 2021* · [📄 Paper](https://arxiv.org/abs/2104.07636) · [🌐 Project](https://iterative-refinement.github.io/)

- **Towards Real-World Blind Face Restoration With Generative Facial Prior** (GFP-GAN)\
  *CVPR 2021* · [📄 Paper](https://arxiv.org/abs/2101.04061) · [💻 Code](https://github.com/TencentARC/GFPGAN)

#### Efficient Generative Restoration

- **AlloSR²: Rectifying One-Step Super-Resolution to Stay Real via Allomorphic Generative Flows**\
  *ECCV 2026* · [📄 Paper](https://arxiv.org/abs/2604.19238)

- **Efficient One-Step Diffusion Restoration Model with Compact Token Compression and Linear Attention** (SANA-SR)\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2605.23451) · [💻 Code](https://github.com/Seiun-Sky-debug/SANASR)

- **FideDiff: Efficient Diffusion Model for High-Fidelity Image Motion Deblurring**\
  *ICLR 2026* · [📄 Paper](https://arxiv.org/abs/2510.01641) · [💻 Code](https://github.com/xyLiu339/FideDiff)

- **IFCSR: Inference-Free Fidelity-Realism Control for One-Step Diffusion-based Real-World Image Super-Resolution**\
  *CVPR 2026* · [📄 Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Back_IFCSR_Inference-Free_Fidelity-Realism_Control_for_One-Step_Diffusion-based_Real-World_Image_Super-Resolution_CVPR_2026_paper.html)

- **MFSR: MeanFlow Distillation for One Step Real-World Image Super Resolution**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2603.20690) · [🌐 Project](https://wrqcodedoge.github.io/mfsr.github.io/)

- **NanoSD: Edge Efficient Foundation Model for Real Time Image Restoration**\
  *CVPR 2026* · [📄 Paper](https://openaccess.thecvf.com/content/CVPR2026/papers/Sanyal_NanoSD_Edge_Efficient_Foundation_Model_for_Real_Time_Image_Restoration_CVPR_2026_paper.pdf)

- **One-Step Diffusion Transformer for Controllable Real-World Image Super-Resolution** (ODTSR)\
  *CVPR 2026* · [📄 Paper](https://arxiv.org/abs/2511.17138)

- **TinySR: Shallow Diffusion Transformers for Real-World Image Super-Resolution**\
  *CVPR Findings 2026* · [📄 Paper](https://openaccess.thecvf.com/content/CVPR2026F/html/Dong_TinySR_Shallow_Diffusion_Transformers_for_Real-World_Image_Super-Resolution_CVPRF_2026_paper.html) · [💻 Code](https://github.com/Microtreei/TinySR)

- **Arbitrary-steps Image Super-resolution via Diffusion Inversion**\
  *CVPR 2025* · [📄 Paper](https://arxiv.org/abs/2412.09013) · [💻 Code](https://github.com/zsyOAOA/InvSR)

- **Harnessing Diffusion-Yielded Score Priors for Image Restoration** (HYPIR)\
  *ACM Trans. Graph. 2025* · [📄 Paper](https://arxiv.org/abs/2507.20590) · [💻 Code](https://github.com/XPixelGroup/HYPIR)

- **Pixel-level and Semantic-level Adjustable Super-resolution: A Dual-LoRA Approach** (PiSA-SR)\
  *CVPR 2025* · [📄 Paper](https://arxiv.org/abs/2412.03017) · [💻 Code](https://github.com/csslc/PiSA-SR)

- **Diffusion Prior-Based Amortized Variational Inference for Noisy Inverse Problems** (DAVI)\
  *ECCV 2024* · [📄 Paper](https://arxiv.org/abs/2407.16125) · [💻 Code](https://github.com/mlvlab/DAVI)

- **FlowIE: Efficient Image Enhancement via Rectified Flow**\
  *CVPR 2024* · [📄 Paper](https://arxiv.org/abs/2406.00508) · [💻 Code](https://github.com/EternalEvan/FlowIE)

- **One-Step Effective Diffusion Network for Real-World Image Super-Resolution** (OSEDiff)\
  *NeurIPS 2024* · [📄 Paper](https://arxiv.org/abs/2406.08177) · [💻 Code](https://github.com/cswry/OSEDiff)

- **SinSR: Diffusion-Based Image Super-Resolution in a Single Step**\
  *CVPR 2024* · [📄 Paper](https://arxiv.org/abs/2311.14760) · [💻 Code](https://github.com/wyf0912/SinSR)

- **Improving the Stability and Efficiency of Diffusion Models for Content Consistent Super-Resolution** (CCSR)\
  *arXiv 2023* · [📄 Paper](https://arxiv.org/abs/2401.00877) · [💻 Code](https://github.com/csslc/CCSR)

- **ResShift: Efficient Diffusion Model for Image Super-resolution by Residual Shifting**\
  *NeurIPS 2023* · [📄 Paper](https://arxiv.org/abs/2307.12348) · [💻 Code](https://github.com/zsyOAOA/ResShift)

### Training Resources and Quality Signals

Restoration training-supervision works appear below. See [Quality Assessment and Related Benchmarks](docs/supporting-papers.md#quality-assessment-and-related-benchmarks) and [Training Data Generation and Datasets](docs/supporting-papers.md#training-data-generation-and-datasets) for the supporting sources.

#### Training Supervision

- **Follow-Your-Preference: Towards Preference-Aligned Image Inpainting**\
  *ICLR 2026* · [📄 Paper](https://arxiv.org/abs/2509.23082) · [💻 Code](https://github.com/shenytzzz/Follow-Your-Preference)

- **Perceive-IR: Learning to Perceive Degradation Better for All-in-One Image Restoration**\
  *IEEE Trans. Image Process. 2026* · [📄 Paper](https://arxiv.org/abs/2408.15994)

- **Unpaired Image Deraining Using Reward-Guided Self-Reinforcement Strategy** (RGSUD)\
  *CVPR 2026* · [📄 Paper](https://arxiv.org/abs/2605.00719)

- **GenDeg: Diffusion-based Degradation Synthesis for Generalizable All-In-One Image Restoration**\
  *CVPR 2025* · [📄 Paper](https://arxiv.org/abs/2411.17687)

- **Hallucination Score: Towards Mitigating Hallucinations in Generative Image Super-Resolution**\
  *arXiv 2025* · [📄 Paper](https://arxiv.org/abs/2507.14367)

- **IRPO: Boosting Image Restoration via Post-training GRPO**\
  *arXiv 2025* · [📄 Paper](https://arxiv.org/abs/2512.00814) · [🌐 Project](https://github.com/HaoxuanXU1024/IRPO)

- **SnowMaster: Comprehensive Real-world Image Desnowing via MLLM with Multi-Model Feedback Optimization**\
  *CVPR 2025* · [📄 Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Lai_SnowMaster_Comprehensive_Real-world_Image_Desnowing_via_MLLM_with_Multi-Model_Feedback_CVPR_2025_paper.pdf) · [🌐 Project](https://alexlai2860.github.io/SnowMaster)

- **DiffLoss: Unleashing Diffusion Model as Constraint for Training Image Restoration Network**\
  *arXiv 2024* · [📄 Paper](https://arxiv.org/abs/2406.19030) · [💻 Code](https://github.com/JosephTiTan/DiffLoss)

- **LossAgent: Towards Any Optimization Objectives for Image Processing with LLM Agents**\
  *arXiv 2024* · [📄 Paper](https://arxiv.org/abs/2412.04090) · [🌐 Project](https://github.com/lbc12345/LossAgent)

- **SUD²: Supervision by Denoising Diffusion Models for Image Reconstruction**\
  *arXiv 2023* · [📄 Paper](https://arxiv.org/abs/2303.09642)

- **Synthesizing Realistic Image Restoration Training Pairs: A Diffusion Approach** (Diffusion-pair synthesis)\
  *arXiv 2023* · [📄 Paper](https://arxiv.org/abs/2303.06994)

Also reviewed for training-resource roles: [DreamClear](#dreamclear) and [Fill2SR](#fill2sr), each listed once under conditional generative restoration.

<a id="restoration-oriented-foundation-models"></a>

## 🧠 Restoration-Oriented Foundation Models

### Pretraining for Image Restoration

#### Multi-Task Pretraining

- **Elucidating and Endowing the Diffusion Training Paradigm for General Image Restoration** (Diffusion-inspired training)\
  *arXiv 2025* · [📄 Paper](https://arxiv.org/abs/2506.21722)

- **On Efficient Transformer-Based Image Pre-training for Low-Level Vision** (EDT)\
  *IJCAI 2023* · [📄 Paper](https://ijcai.org/proceedings/2023/121) · [💻 Code](https://github.com/fenglinglwb/EDT)

- **TAPE: Task-Agnostic Prior Embedding for Image Restoration**\
  *ECCV 2022* · [📄 Paper](https://arxiv.org/abs/2203.06074)

- **Pre-Trained Image Processing Transformer** (IPT)\
  *CVPR 2021* · [📄 Paper](https://arxiv.org/abs/2012.00364) · [💻 Code](https://github.com/huawei-noah/Pretrained-IPT)

#### Masked Image Modeling

- **Dynamic Pre-training: Towards Efficient and Scalable All-in-One Image Restoration**\
  *arXiv 2024* · [📄 Paper](https://arxiv.org/abs/2404.02154) · [💻 Code](https://github.com/akshaydudhane16/DyNet)

- **Restore Anything with Masks: Leveraging Mask Image Modeling for Blind All-in-One Image Restoration** (RAM)\
  *ECCV 2024* · [📄 Paper](https://arxiv.org/abs/2409.19403) · [💻 Code](https://github.com/DragonisCV/RAM)

- **Context-Aware Pretraining for Efficient Blind Image Decomposition** (CPNet)\
  *CVPR 2023* · [📄 Paper](https://ieeexplore.ieee.org/document/10204969/)

- **Masked Autoencoders as Image Processors** (MAEIP)\
  *arXiv 2023* · [📄 Paper](https://arxiv.org/abs/2303.17316) · [🌐 Project](https://github.com/DuanHuiyu/MAEIP_CSformer)

#### Degradation-Aware Pretraining

- **Bridging Degradation Discrimination and Generation for Universal Image Restoration** (BDG)\
  *ICLR 2026* · [📄 Paper](https://arxiv.org/abs/2602.00579) · [💻 Code](https://github.com/MILab-PKU/BDG)

- **Universal Image Restoration Pre-training via Degradation Classification** (DCPT)\
  *ICLR 2025* · [📄 Paper](https://arxiv.org/abs/2501.15510) · [💻 Code](https://github.com/MILab-PKU/dcpt)

- **ConStyle v2: A Strong Prompter for All-in-One Image Restoration**\
  *arXiv 2024* · [📄 Paper](https://arxiv.org/abs/2406.18242) · [💻 Code](https://github.com/Dongqi-Fan/ConStyle_v2)

- **DegAE: A New Pretraining Paradigm for Low-Level Vision**\
  *CVPR 2023* · [📄 Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Liu_DegAE_A_New_Pretraining_Paradigm_for_Low-Level_Vision_CVPR_2023_paper.html) · [💻 Code](https://github.com/lyh-18/DegAE_DegradationAutoencoder) · [🌐 Project](https://xpixel.group/2022/10/20/DegAE.html)

### Unified Restoration Modeling

#### Multi-Task Joint Training

- **UniRestorer: Universal Image Restoration via Adaptively Estimating Image Degradation at Proper Granularity**\
  *ICLR 2026* · [📄 Paper](https://arxiv.org/abs/2412.20157) · [💻 Code](https://github.com/mrluin/UniRestorer)

- **OneRestore: A Universal Restoration Framework for Composite Degradation**\
  *ECCV 2024* · [📄 Paper](https://arxiv.org/abs/2407.04621) · [💻 Code](https://github.com/gy65896/OneRestore)

- **Towards Effective Multiple-in-One Image Restoration: A Sequential and Prompt Learning Strategy**\
  *arXiv 2024* · [📄 Paper](https://arxiv.org/abs/2401.03379) · [💻 Code](https://github.com/Xiangtaokong/MiOIR)

- **Ingredient-Oriented Multi-Degradation Learning for Image Restoration** (IDR)\
  *CVPR 2023* · [📄 Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Ingredient-Oriented_Multi-Degradation_Learning_for_Image_Restoration_CVPR_2023_paper.pdf) · [💻 Code](https://github.com/Jinghaoleven/IDR-Ingredients-oriented-Degradation-Reformulation)

- **PromptIR: Prompting for All-in-One Image Restoration**\
  *NeurIPS 2023* · [📄 Paper](https://arxiv.org/abs/2306.13090) · [💻 Code](https://github.com/va1shn9v/PromptIR)

- **All-in-One Image Restoration for Unknown Corruption** (AirNet)\
  *CVPR 2022* · [📄 Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_All-in-One_Image_Restoration_for_Unknown_Corruption_CVPR_2022_paper.pdf) · [💻 Code](https://github.com/XLearning-SCU/2022-CVPR-AirNet)

- **TransWeather: Transformer-Based Restoration of Images Degraded by Adverse Weather Conditions**\
  *CVPR 2022* · [📄 Paper](https://arxiv.org/abs/2111.14813) · [💻 Code](https://github.com/jeya-maria-jose/TransWeather)

- **All in One Bad Weather Removal Using Architectural Search**\
  *CVPR 2020* · [📄 Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_All_in_One_Bad_Weather_Removal_Using_Architectural_Search_CVPR_2020_paper.html)

#### Visual In-Context Learning

- **Hidden-Shot: Towards One-Shot Task Generalization for Low-Level Vision Generalist Models**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2607.01535)

- **Exploring Scalable Unified Modeling for General Low-Level Vision** (GenLV scaling)\
  *arXiv 2025* · [📄 Paper](https://arxiv.org/abs/2507.14801)

- **LaVin-DiT: Large Vision Diffusion Transformer**\
  *CVPR 2025* · [📄 Paper](https://arxiv.org/abs/2411.11505) · [💻 Code](https://github.com/DerrickWang005/LaVin-DiT)

- **Learning A Low-Level Vision Generalist via Visual Task Prompt** (GenLV)\
  *ACM MM 2024* · [📄 Paper](https://arxiv.org/abs/2408.08601) · [💻 Code](https://github.com/chxy95/GenLV)

- **Unifying Image Processing as Visual Prompting Question Answering** (PromptGIP)\
  *ICML 2024* · [📄 Paper](https://arxiv.org/abs/2310.10513) · [💻 Code](https://github.com/lyh-18/PromptGIP)

- **Images Speak in Images: A Generalist Painter for In-Context Visual Learning**\
  *CVPR 2023* · [📄 Paper](https://arxiv.org/abs/2212.02499) · [💻 Code](https://github.com/baaivision/Painter)

#### Multi-Task Generative Modeling

- **FoundIR-v2: Optimizing Pre-Training Data Mixtures for Image Restoration Foundation Model**\
  *CVPR 2026* · [📄 Paper](https://arxiv.org/abs/2512.09282) · [💻 Code](https://github.com/cschenxiang/FoundIR-v2)

- **SLAIR: Structured Latent Flow Matching for All-in-One Image Restoration**\
  *ECCV 2026* · [📄 Paper](https://link.springer.com/chapter/10.1007/978-3-032-37517-9_3) · [💻 Code](https://github.com/Fightforql/SLAIR) · [🌐 Project](https://fightforql.github.io/SLAIR-page/)

- **UARE: A Unified Vision-Language Model for Image Quality Assessment, Restoration, and Enhancement**\
  *CVPR 2026* · [📄 Paper](https://arxiv.org/abs/2512.06750) · [💻 Code](https://github.com/lwq20020127/UARE)

- **FoundIR: Unleashing Million-scale Training Data to Advance Foundation Models for Image Restoration**\
  *ICCV 2025* · [📄 Paper](https://arxiv.org/abs/2412.01427) · [💻 Code](https://github.com/House-Leo/FoundIR)

- **Lumina-OmniLV: A Unified Multimodal Framework for General Low-Level Vision**\
  *arXiv 2025* · [📄 Paper](https://arxiv.org/abs/2504.04903) · [💻 Code](https://github.com/Andrew0613/Lumina-Omnilv) · [🌐 Project](https://andrew0613.github.io/OmniLV_page/)

- **Palette: Image-to-Image Diffusion Models**\
  *arXiv 2021* · [📄 Paper](https://arxiv.org/abs/2111.05826) · [🌐 Project](https://iterative-refinement.github.io/palette/)

### Transfer and Adaptation

#### Transfer to New Tasks and Domains

- **DDTNet: Degradation Disentanglement and Transfer Network for Test-Time All-in-One De-weathering Adaptation**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2606.16298)

- **Degradation-Consistent Test-Time Adaptation for All-in-One Image Restoration** (Degradation-consistent TTA)\
  *CVPR 2026* · [📄 Paper](https://openaccess.thecvf.com/content/CVPR2026/papers/Tang_Degradation-Consistent_Test-Time_Adaptation_for_All-in-One_Image_Restoration_CVPR_2026_paper.pdf) · [💻 Code](https://github.com/tonia86/DCTTA)

- **AdaIR: Exploiting Underlying Similarities of Image Restoration Tasks with Adapters**\
  *arXiv 2024* · [📄 Paper](https://arxiv.org/abs/2404.11475)

- **Contribution-based Low-Rank Adaptation with Pre-training Model for Real Image Restoration** (PROD + CoLoRA)\
  *ECCV 2024* · [📄 Paper](https://arxiv.org/abs/2408.01099) · [🌐 Project](https://janeyeon.github.io/colora/)

- **GRIDS: Grouped Multiple-Degradation Restoration with Image Degradation Similarity**\
  *ECCV 2024* · [📄 Paper](https://arxiv.org/abs/2407.12273)

- **Parameter Efficient Adaptation for Image Restoration with Heterogeneous Mixture-of-Experts** (AdaptIR)\
  *NeurIPS 2024* · [📄 Paper](https://arxiv.org/abs/2312.08881) · [💻 Code](https://github.com/csguoh/AdaptIR)

- **ProRes: Exploring Degradation-aware Visual Prompt for Universal Image Restoration**\
  *arXiv 2023* · [📄 Paper](https://arxiv.org/abs/2306.13653) · [💻 Code](https://github.com/leonmakise/ProRes)

For the cross-task adaptation role of [Multimodal Prompt Perceiver](#multimodal-prompt-perceiver), see its primary entry under conditional generative restoration.

#### Continual Image Restoration

- **Learning to Restore More: Continual Capability Expansion for Pretrained Image Restoration Models**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2608.30305)

- **Restoring Without Forgetting: Continual Learning Across Image Degradations**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2608.23799) · [💻 Code](https://github.com/AlifAshrafee/Restoring-Without-Forgetting)

- **Restoring without Forgetting: Filter-Level Continual Image Restoration via Parameter-Space Integrated Gradients** (Filter-level RwF)\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2609.38591)

- **A Minimalistic Unified Framework for Incremental Learning across Image Restoration Tasks** (MINI-Conv)\
  *NeurIPS 2025* · [📄 Paper](https://openreview.net/pdf/13e99d7ed18b26efa7b85826e1e8a99df5c73f39.pdf)

- **Continual All-in-One Adverse Weather Removal with Knowledge Replay on a Unified Network Structure** (Continual weather removal)\
  *arXiv 2024* · [📄 Paper](https://arxiv.org/abs/2403.07292) · [💻 Code](https://github.com/xiaojihh/CL_all-in-one)

- **Review Learning: Advancing All-in-One Ultra-High-Definition Image Restoration Training Method**\
  *arXiv 2024* · [📄 Paper](https://arxiv.org/abs/2408.06709)

<a id="agentic-image-restoration"></a>

## 🤖 Agentic Image Restoration

### Task Planning

- **Derain-Agent: A Plug-and-Play Agent Framework for Rainy Image Restoration**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2603.11866) — Task-specific learned planning precedent.

- **Multi-Agent Image Restoration** (MAIR)\
  *Int. J. Comput. Vis. 2026* · [📄 Paper](https://arxiv.org/abs/2503.09403) · [🌐 Project](https://villa.jianzhang.tech/publication/200604/)

- **OPERA: An Agent for Image Restoration with End-to-End Joint Planning-Execution Optimization**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2605.22104) · [💻 Code](https://github.com/xsyshuishui/Opera)

- **An Intelligent Agentic System for Complex Image Restoration Problems** (AgenticIR)\
  *ICLR 2025* · [📄 Paper](https://arxiv.org/abs/2410.17809) · [💻 Code](https://github.com/Kaiwen-Zhu/AgenticIR) · [🌐 Project](https://kaiwen-zhu.github.io/research/agenticir)

- **JarvisIR: Elevating Autonomous Driving Perception with Intelligent Image Restoration**\
  *CVPR 2025* · [📄 Paper](https://arxiv.org/abs/2504.04158) · [💻 Code](https://github.com/LYL1015/JarvisIR) · [🌐 Project](https://cvpr2025-jarvisir.github.io/)

- **RestoreAgent: Autonomous Image Restoration Agent via Multimodal Large Language Models**\
  *NeurIPS 2024* · [📄 Paper](https://arxiv.org/abs/2407.18035) · [🌐 Project](https://haoyuchen.com/RestoreAgent)

### Tool Selection

Includes agent tool selection and executor-side expert routing or allocation.

- **Beyond Sequential Tools: A Unified VLM Agent System for Photographic Post-Processing via Dynamic Multi-Expert Fusion**\
  *CVPR 2026* · [📄 Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Xiong_Beyond_Sequential_Tools_A_Unified_VLM_Agent_System_for_Photographic_CVPR_2026_paper.html) — Executor-side LoRA allocation.

- **DiTTo: Scalable Order-aware All-in-One Image Restoration Agent**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2605.30915) · [🌐 Project](https://cmlab-korea.github.io/DiTTo/)

- **FAPE-IR: Frequency-Aware Planning and Execution Framework for All-in-One Image Restoration**\
  *CVPR 2026* · [📄 Paper](https://arxiv.org/abs/2511.14099) · [💻 Code](https://github.com/Programmergg/FAPE-IR) — Executor-side expert routing.

- **Restore-R1: Efficient Image Restoration Agents via Reinforcement Learning with Multimodal LLM Perceptual Feedback**\
  *CVPR Findings 2026* · [📄 Paper](https://arxiv.org/abs/2512.18599)

- **TIR-Agent: Training an Explorative and Efficient Agent for Image Restoration**\
  *ECCV 2026* · [📄 Paper](https://arxiv.org/abs/2603.27742)

### Feedback and Refinement

- **Adapting Large VLMs with Iterative and Manual Instructions for Generative Low-light Enhancement** (VLM-IMI)\
  *CVPR Findings 2026* · [📄 Paper](https://arxiv.org/abs/2507.18064) · [💻 Code](https://github.com/sunxiaoran01/VLM-IMI)

- **HarnessIR: Harnessing Multimodal Foundation Models for Universal Real-World Image Restoration**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2610.10133) · [💻 Code](https://github.com/PolyU-VCLab/HarnessIR)

- **Hybrid Agents for Image Restoration**\
  *CVPR 2026* · [📄 Paper](https://arxiv.org/abs/2503.10120)

- **IAMAgent: Toward an Interactive and Adaptive Multi-Agent System for Image Restoration**\
  *IEEE Trans. Image Process. 2026* · [📄 Paper](https://ieeexplore.ieee.org/document/11433514/)

- **Restore, Assess, Repeat: A Unified Framework for Iterative Image Restoration** (RAR)\
  *CVPR 2026* · [📄 Paper](https://arxiv.org/abs/2603.26385) · [💻 Code](https://github.com/saic-fi/RAR) · [🌐 Project](https://restore-assess-repeat.github.io/)

- **4KAgent: Agentic Any Image to 4K Super-Resolution**\
  *NeurIPS 2025* · [📄 Paper](https://arxiv.org/abs/2507.07105) · [💻 Code](https://github.com/taco-group/4KAgent) · [🌐 Project](https://4kagent.github.io/)

- **Q-Agent: Quality-Driven Chain-of-Thought Image Restoration Agent through Robust Multimodal Large Language Model**\
  *arXiv 2025* · [📄 Paper](https://arxiv.org/abs/2504.07148)

- **Clarity ChatGPT: An Interactive and Adaptive Processing System for Image Restoration and Enhancement**\
  *arXiv 2023* · [📄 Paper](https://arxiv.org/abs/2311.11695)

[SkillIR](#skillir) also contributes to feedback and refinement; its primary entry is under experience retrieval.

### Experience Retrieval

- **Causal-AgentIR: Self-Evolving Causal Memory for Adaptive Image Restoration Agents**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2607.21125)

- **EvoIR-Agent: Self-Evolving Image Restoration Agentic System via Experience-Driven Learning**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2605.22208) · [🌐 Project](https://github.com/rightleft-123/EvoIRAgent)

- **PaAgent: Portrait-Aware Image Restoration Agent via Subjective-Objective Reinforcement Learning**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2603.17055) · [🌐 Project](https://wyjgr.github.io/PaAgent.html)

- **Self-evolving Agentic Image Restoration via Deliberate Planning and Intuitive Execution** (SEAR)\
  *ECCV 2026* · [📄 Paper](https://arxiv.org/abs/2606.28971)

<a id="skillir"></a>

- **SkillIR: Evolving Scene-Aware Skills for Agentic Image Restoration**\
  *arXiv 2026* · [📄 Paper](https://arxiv.org/abs/2609.21468)