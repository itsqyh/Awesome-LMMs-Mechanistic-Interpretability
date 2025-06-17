# 🌟 Awesome LMMs Mechanistic Interpretability
<div align="center">
  <img src="logo.png" alt="Logo" width="300">
  <h1 align="center">Peering into the Black Box of LMMs.</h1>
  
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![](https://img.shields.io/github/last-commit/itsqyh/Awesome-LMMs-Mechanistic-Interpretability?color=green) 

</div>


<div align="center">
  <p style="font-size:20px;"><em>A curated collection of resources focused on the Mechanistic Interpretability (MI) of Large Multimodal Models (LMMs).</em></p>
</div>


📬 **Have a new paper or collaboration idea?** Reach out to me at: **qyhhere@gmail.com** or Pull Request.  
🤝 **Seeking Opportunities:** I'm eager to discuss and collaborate, especially for industry internships in Large Multimodal Models!


## 🔔 News

- [2025-06] We created this repository to maintain a paper list on Awesome-Think-With-Images. Contributions are welcome!


## Table of Contents
- [Surveys](#Surveys)
- [Blog](#Blog)
- [Papers](#Papers)
  - [Sparse Autoencoder](#Sparse-Autoencoder)
  - [Probing](#Probing)
  - [(Beyond) Logit Lens](#Beyond-or-Logit-Lens)
  - [Causal Tracing](#Causal-Tracing)
  - [Neuron Analysis](#Neuron-Analysis)
  - [Steering](#Steering)
  - [Representation](#Representation)
  - [Attention](#Attention)
- [Tool](#Tool)


## 📚 Surveys:
([Back to Table of Contents](#Table-of-Contents))
+ [A Survey on Sparse Autoencoders: Interpreting the Internal Mechanisms of Large Language Models](https://arxiv.org/abs/2503.05613) (Jun. 06, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.05613)
  
+ [A Survey on Mechanistic Interpretability for Multi-Modal Foundation Models](https://arxiv.org/abs/2502.17516) (Feb. 22, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.17516)

+ [Open Problems in Mechanistic Interpretability](https://arxiv.org/abs/2501.16496) (Jan. 27, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.16496)

+ [A Review of Multimodal Explainable Artificial Intelligence: Past, Present and Future](https://arxiv.org/abs/2412.14056) (Dec. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14056)

+ [Explainable and Interpretable Multimodal Large Language Models: A Comprehensive Survey](https://arxiv.org/abs/2412.02104) (Dec. 3, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.02104)



## 📚 Blog:
([Back to Table of Contents](#table-of-contents))
+ [Mechanistic Interpretability Meets Vision Language Models: Insights and Limitations](https://d2jud02ci9yv69.cloudfront.net/2025-04-28-vlm-understanding-29/blog/vlm-understanding/) (Apr. 28, 2025)

+ [Are SAE features from the Base Model still meaningful to LLaVA?](https://www.lesswrong.com/posts/8JTi7N3nQmjoRRuMD/are-sae-features-from-the-base-model-still-meaningful-to-1) (Dec. 6, 2024)

+ [Bridging the VLM and mech interp communities for multimodal interpretability](https://www.lesswrong.com/posts/aa5fzGr8JA3pqvhYC/bridging-the-vlm-and-mech-interp-communities-for-multimodal) (Oct. 28, 2024)

+ [Case Study: Interpreting, Manipulating, and Controlling CLIP With Sparse Autoencoders](https://www.lesswrong.com/posts/iYFuZo9BMvr6GgMs5/case-study-interpreting-manipulating-and-controlling-clip) (Aug. 2, 2025)

+ [Interpreting and Steering Features in Images](https://www.lesswrong.com/posts/Quqekpvx8BGMMcaem/interpreting-and-steering-features-in-images) (Apr. 28, 2025)

+ [Case Study: Interpreting, Manipulating, and Controlling CLIP With Sparse Autoencoders](https://www.lesswrong.com/posts/iYFuZo9BMvr6GgMs5/case-study-interpreting-manipulating-and-controlling-clip) (Apr. 28, 2025)

+ [Laying the Foundations for Vision and Multimodal Mechanistic Interpretability & Open Problems](https://www.lesswrong.com/posts/kobJymvvcvhbjWFKe/laying-the-foundations-for-vision-and-multimodal-mechanistic) (May. 14, 2024)

+ [Towards Multimodal Interpretability: Learning Sparse Interpretable Features in Vision Transformers](https://www.lesswrong.com/posts/bCtbuWraqYTDtuARg/towards-multimodal-interpretability-learning-sparse-2) (Apr. 30, 2024)


## 📚 Papers:

### 📜 Sparse Autoencoder
([Back to Table of Contents](#table-of-contents))

+ **Understanding Feature Mappings in MLLMs** [How Visual Representations Map to Language Feature Space in Multimodal LLMs](https://arxiv.org/pdf/2506.11976) (Jun. 13, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.11976)
  [![Star](https://img.shields.io/github/stars/cvenhoff/vlm-mapping.svg?style=social&label=Star)](https://github.com/cvenhoff/vlm-mapping)

+ **SAE Learning Monosemantic Features in VLMs** [Sparse Autoencoders Learn Monosemantic Features in Vision-Language Models](https://arxiv.org/abs/2504.02821) (Jun. 6, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.02821)
  [![Star](https://img.shields.io/github/stars/ExplainableML/sae-for-vlm.svg?style=social&label=Star)](https://github.com/ExplainableML/sae-for-vlm)

+ **SAE Attributing CLIP's Latent Components** [From What to How: Attributing CLIP's Latent Components Reveals Unexpected Semantic Reliance](https://arxiv.org/abs/2505.20229) (May. 26, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.20229)
  [![Star](https://img.shields.io/github/stars/maxdreyer/attributing-clip.svg?style=social&label=Star)](https://github.com/maxdreyer/attributing-clip)
  
+ **SAE Analyzing Hierarchical Structure in VMs** [Analyzing Hierarchical Structure in Vision Models with Sparse Autoencoders](https://arxiv.org/abs/2505.15970) (May. 21, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.15970)

+ **DiffLens: Dissecting and Mitigating Diffusion Bias** [Dissecting and Mitigating Diffusion Bias via Mechanistic Interpretability](https://arxiv.org/abs/2503.20483) (Mar. 26, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.20483)
  [![Star](https://img.shields.io/github/stars/foundation-model-research/DiffLens.svg?style=social&label=Star)](https://github.com/foundation-model-research/DiffLens)

+ **SAE Reveal Selective Remapping of Visual Concepts** [Sparse autoencoders reveal selective remapping of visual concepts during adaptation](https://arxiv.org/abs/2412.05276) (Mar. 21, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.05276)
  [![Star](https://img.shields.io/github/stars/dynamical-inference/patchsae.svg?style=social&label=Star)](https://github.com/dynamical-inference/patchsae)

+ **SAE-V** [SAE-V: Interpreting Multimodal Models for Enhanced Alignment](https://arxiv.org/abs/2502.17514) (Feb. 22, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.17514)

+ **SAE 4 Scientifically Rigorous Interpretation** [Sparse Autoencoders for Scientifically Rigorous Interpretation of Vision Models](https://arxiv.org/abs/2502.06755) (Feb. 10, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.06755)
  [![Star](https://img.shields.io/github/stars/OSU-NLP-Group/saev.svg?style=social&label=Star)](https://github.com/OSU-NLP-Group/saev)

+ **Universal SAE** [Universal Sparse Autoencoders: Interpretable Cross-Model Concept Alignment](https://arxiv.org/pdf/2502.03714) (Feb. 6, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.03714)

+ **SAE 4 LMM** [Large Multi-modal Models Can Interpret Features in Large Multi-modal Models](https://arxiv.org/abs/2411.14982) (Nov. 22, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.14982)
  [![Star](https://img.shields.io/github/stars/EvolvingLMMs-Lab/multimodal-sae.svg?style=social&label=Star)](https://github.com/EvolvingLMMs-Lab/multimodal-sae)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 📜 Probing
([Back to Table of Contents](#table-of-contents))

+ **Probing MLLMs** [Probing Multimodal Large Language Models for Global and Local Semantic Representations](https://arxiv.org/abs/2402.17304) (Jan. 6, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.17304)

+ **Probing the Role of Positional Information in VLMs** [Probing the Role of Positional Information in Vision-Language Models](https://arxiv.org/abs/2305.10046) (May. 17, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.10046)
  [![Star](https://img.shields.io/github/stars/phiyodr/plxmert.svg?style=social&label=Star)](https://github.com/phiyodr/plxmert)
  
+ **Probing Hallucination in VIT** [Plausible May Not Be Faithful: Probing Object Hallucination in Vision-Language Pre-training](https://arxiv.org/abs/2210.07688) (Feb. 10, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.07688)

+ **Probing Representations of Numbers in VLMs** [Probing Representations of Numbers in Vision and Language Models](https://openreview.net/forum?id=01hQQ16Lc9M) (May. 06, 2023)

+ **Probing VIT** [Are Vision-Language Transformers Learning Multimodal Representations? A Probing Perspective](https://ojs.aaai.org/index.php/AAAI/article/view/21375) (Jun. 28, 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ojs.aaai.org/index.php/AAAI/article/view/21375)

+ **Probing VLMs 4 Visio-Linguistic Compositionality** [Winoground: Probing Vision and Language Models for Visio-Linguistic Compositionality](https://arxiv.org/abs/2204.03162) (Apr. 22, 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2204.03162)
  [![Star](https://img.shields.io/github/stars/phiyodr/plxmert.svg?style=social&label=Star)](https://huggingface.co/datasets/facebook/winoground)

+ **A Probing Perspective of VITs Learning Multimodal Representations** [Are Vision-Language Transformers Learning Multimodal Representations? A Probing Perspective](https://ojs.aaai.org/index.php/AAAI/article/view/21375) (Jun. 28, 2022)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 📜 Beyond or Logit Lens
([Back to Table of Contents](#table-of-contents))

+ **Diffusion Steering Lens Decoding ViTs** [Decoding Vision Transformers: the Diffusion Steering Lens](https://arxiv.org/abs/2504.13763) (Apr. 23, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.13763)
  [![Star](https://img.shields.io/github/stars/rtakatsky/DSLens.svg?style=social&label=Star)](https://github.com/rtakatsky/DSLens)

+ **Beyond Logit Lens** [Beyond Logit Lens: Contextual Embeddings for Robust Hallucination Detection & Grounding in VLMs](https://arxiv.org/abs/2411.19187) (Feb. 19, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.19187)

+ **Diffusion Lens** [Diffusion Lens: Interpreting Text Encoders in Text-to-Image Pipelines](https://arxiv.org/abs/2403.05846) (Oct. 21, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.05846)
  [![Star](https://img.shields.io/github/stars/tokeron/DiffusionLens.svg?style=social&label=Star)](https://github.com/tokeron/DiffusionLens)

+ **Attention Lens** [Devils in Middle Layers of Large Vision-Language Models: Interpreting, Detecting and Mitigating Object Hallucinations via Attention Lens](https://www.arxiv.org/abs/2411.16724) (Nov. 23, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2411.16724)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 📜 Causal Tracing
([Back to Table of Contents](#table-of-contents))

+ **LLaVA in VQA** [Understanding Multimodal LLMs: the Mechanistic Interpretability of Llava in Visual Question Answering](https://arxiv.org/abs/2411.10950) (Nov. 17, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.10950)
  [![Star](https://img.shields.io/github/stars/zepingyu0512/llava-mechanism.svg?style=social&label=Star)](https://github.com/zepingyu0512/llava-mechanism)

+ **Information Storage and Transfer** [Understanding Information Storage and Transfer in Multi-modal Large Language Models](https://arxiv.org/abs/2406.04236) (June. 06, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.04236)
  [![Star](https://img.shields.io/github/stars/IntelLabs/lvlm-interpret.svg?style=social&label=Star)](https://github.com/IntelLabs/lvlm-interpret)
  
+ **Causal Tracing Tool 4 BLIP** [Towards Vision-Language Mechanistic Interpretability: A Causal Tracing Tool for BLIP](https://arxiv.org/abs/2308.14179) (Aug. 27, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.14179)
  [![Star](https://img.shields.io/github/stars/vedantpalit/Towards-Vision-Language-Mechanistic-Interpretability.svg?style=social&label=Star)](https://github.com/vedantpalit/Towards-Vision-Language-Mechanistic-Interpretability)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 📜 Steering 
([Back to Table of Contents](#table-of-contents))
+ **Diffusion Steering Lens Decoding ViTs** [Decoding Vision Transformers: the Diffusion Steering Lens](https://arxiv.org/abs/2504.13763) (Apr. 23, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.13763)
  [![Star](https://img.shields.io/github/stars/rtakatsky/DSLens.svg?style=social&label=Star)](https://github.com/rtakatsky/DSLens)

+ **DiffLens: Dissecting and Mitigating Diffusion Bias** [Dissecting and Mitigating Diffusion Bias via Mechanistic Interpretability](https://arxiv.org/abs/2503.20483) (Mar. 26, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.20483)
  [![Star](https://img.shields.io/github/stars/foundation-model-research/DiffLens.svg?style=social&label=Star)](https://github.com/foundation-model-research/DiffLens)

+ **LMM Concept Explainability** [A Concept-Based Explainability Framework for Large Multimodal Models](https://arxiv.org/abs/2406.08074) (Nov. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.08074)
  [![Star](https://img.shields.io/github/stars/mshukor/xl-vlms.svg?style=social&label=Star)](https://github.com/mshukor/xl-vlms)
  
+ **Concept Sliders** [Concept Sliders: LoRA Adaptors for Precise Control in Diffusion Models](https://link.springer.com/chapter/10.1007/978-3-031-73661-2_10) (Nov. 10, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://link.springer.com/chapter/10.1007/978-3-031-73661-2_10)
  [![Star](https://img.shields.io/github/stars/CompVis/attribute-conl.svg?style=social&label=Star)](https://sliders.baulab.info/)

+ **Latent Space Steering Reducing Hallucinations in VLMs** [Reducing Hallucinations in Vision-Language Models via Latent Space Steering](https://arxiv.org/abs/2410.15778) (Oct. 22, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.15778)
  [![Star](https://img.shields.io/github/stars/shengliu66/VTI.svg?style=social&label=Star)](https://github.com/shengliu66/VTI)
  
+ **Attribute Control** [Continuous, Subject-Specific Attribute Control in T2I Models by Identifying Semantic Directions](https://arxiv.org/abs/2403.17064) (Mar. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.17064)
  [![Star](https://img.shields.io/github/stars/CompVis/attribute-control.svg?style=social&label=Star)](https://github.com/CompVis/attribute-control)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 📜 Representation
([Back to Table of Contents](#table-of-contents))

+ **Understanding Feature Mappings in VLMs** [How Visual Representations Map to Language Feature Space in Multimodal LLMs](https://arxiv.org/pdf/2506.11976) (Jun. 13, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.11976)
  [![Star](https://img.shields.io/github/stars/cvenhoff/vlm-mapping.svg?style=social&label=Star)](https://github.com/cvenhoff/vlm-mapping)

+ **Embedding Shift Dissection on CLIP** [Embedding Shift Dissection on CLIP: Effects of Augmentations on VLM's Representation Learning](https://arxiv.org/abs/2503.23495) (Apr. 10, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.23495)
  [![Star](https://img.shields.io/github/stars/ashimdahal/clip-shift-analysis.svg?style=social&label=Star)](https://github.com/ashimdahal/clip-shift-analysis)

+ **Fine-tuning Representation Shift** [Analyzing Fine-tuning Representation Shift for Multimodal LLMs Steering](https://arxiv.org/abs/2501.03012) (Jan. 6, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.03012)
  [![Star](https://img.shields.io/github/stars/mshukor/xl-vlms.svg?style=social&label=Star)](https://github.com/mshukor/xl-vlms)

+ **Decomposing and Interpreting Image Representations** [Decomposing and Interpreting Image Representations via Text in ViTs Beyond CLIP](https://arxiv.org/abs/2406.01583) (Oct. 21, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01583)
  [![Star](https://img.shields.io/github/stars/SriramB-98/vit-decompose.svg?style=social&label=Star)](https://github.com/SriramB-98/vit-decompose)

+ **Implicit Multimodal Alignment** [Implicit Multimodal Alignment: On the Generalization of Frozen LLMs to Multimodal Inputs](https://arxiv.org/abs/2405.16700) (Oct. 5, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.16700)
  [![Star](https://img.shields.io/github/stars/mshukor/ima-lmms.svg?style=social&label=Star)](https://github.com/mshukor/ima-lmms)

+ **Interp and Editing VLR to Mitigate Hallucinations** [Interpreting and Editing Vision-Language Representations to Mitigate Hallucinations](https://arxiv.org/abs/2410.02762) (Oct. 5, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.02762)
  [![Star](https://img.shields.io/github/stars/nickjiang2378/vl-interp.svg?style=social&label=Star)](https://github.com/nickjiang2378/vl-interp)

+ **Text-Based Decomposition** [Interpreting CLIP's Image Representation via Text-Based Decomposition](https://arxiv.org/abs/2310.05916) (Mar. 29, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.05916)
  [![Star](https://img.shields.io/github/stars/yossigandelsman/clip_text_span.svg?style=social&label=Star)](https://github.com/yossigandelsman/clip_text_span)

+ **Interpreting CLIP with Sparse Linear Concept Embeddings** [Interpreting CLIP with Sparse Linear Concept Embeddings (SpLiCE)](https://arxiv.org/abs/2402.10376) (Feb. 16, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.10376)
  [![Star](https://img.shields.io/github/stars/AI4LIFE-GROUP/SpLiCE.svg?style=social&label=Star)](https://github.com/AI4LIFE-GROUP/SpLiCE)

+ **A Probing Perspective of VITs Learning Multimodal Representations** [Are Vision-Language Transformers Learning Multimodal Representations? A Probing Perspective](https://ojs.aaai.org/index.php/AAAI/article/view/21375) (Jun. 28, 2022)


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 📜 Neuron Analysis
([Back to Table of Contents](#table-of-contents))

+ **ViTs Don't Need Trained Registers** [Vision Transformers Don't Need Trained Registers](https://arxiv.org/abs/2506.08010) (Jun. 10, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.08010)
  [![Star](https://img.shields.io/github/stars/nickjiang2378/test-time-registers.svg?style=social&label=Star)](https://github.com/nickjiang2378/test-time-registers/tree/main)

+ **Interpreting the Second-Order Effects of Neurons in CLIP** [Interpreting the Second-Order Effects of Neurons in CLIP](https://arxiv.org/abs/2406.04341) (Feb. 12, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.04341)
  [![Star](https://img.shields.io/github/stars/yossigandelsman/second_order_lens.svg?style=social&label=Star)](https://github.com/yossigandelsman/second_order_lens)

+ **Multi-Modal Neurons** [Finding and Editing Multi-Modal Neurons in Pre-Trained Transformers](https://arxiv.org/abs/2311.07470) (Jun. 11, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.07470)
  [![Star](https://img.shields.io/github/stars/opanhw/MM_Neurons.svg?style=social&label=Star)](https://github.com/opanhw/MM_Neurons)

+ **Multimodal In-Context Learning** [What Makes Multimodal In-Context Learning Work?](https://arxiv.org/abs/2404.15736) (April. 25, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.15736)
  [![Star](https://img.shields.io/github/stars/folbaeni/multimodal-icl.svg?style=social&label=Star)](https://github.com/folbaeni/multimodal-icl)

+ **Modality-Specific Neurons in MLLMs** [MINER: Mining the Underlying Pattern of Modality-Specific Neurons in Multimodal Large Language Models](https://arxiv.org/abs/2410.04819) (Oct. 7, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.04819)
  [![Star](https://img.shields.io/github/stars/huang-kc/MINER.svg?style=social&label=Star)](https://github.com/huang-kc/MINER)

+ **What Do VLMs NOTICE?** [What Do VLMs NOTICE? A Mechanistic Interpretability Pipeline for Gaussian-Noise-free Text-Image Corruption and Evaluation](https://arxiv.org/abs/2406.16320) (Oct. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16320)
  [![Star](https://img.shields.io/github/stars/wrudman/NOTICE.svg?style=social&label=Star)](https://anonymous.4open.science/r/NOTICE-ARR-Submission/README.md)

+ **Multimodal Neurons in Pretrained Text-Only Transformers** [Multimodal Neurons in Pretrained Text-Only Transformers](https://arxiv.org/abs/2308.01544) (Aug. 18, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.01544)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 📜 Attention
([Back to Table of Contents](#table-of-contents))

+ **Spatial Reasoning 4 VLMs** [Why Is Spatial Reasoning Hard for VLMs? An Attention Mechanism Perspective on Focus Areas](https://arxiv.org/abs/2503.01773) (Mar. 4, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.01773)
  [![Star](https://img.shields.io/github/stars/shiqichen17/AdaptVis.svg?style=social&label=Star)](https://github.com/shiqichen17/AdaptVis)

+ **Attention Lens** [Devils in Middle Layers of Large Vision-Language Models: Interpreting, Detecting and Mitigating Object Hallucinations via Attention Lens](https://www.arxiv.org/abs/2411.16724) (Nov. 23, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2411.16724)


## 📚 Tool
([Back to Table of Contents](#table-of-contents))

+ **Prisma** [Prisma : An Open Source Toolkit for Mechanistic Interpretability in Vision and Video](https://arxiv.org/abs/2504.19475) (Apr. 28, 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.19475)
  [![Star](https://img.shields.io/github/stars/Prisma-Multimodal/ViT-Prisma.svg?style=social&label=Star)](https://github.com/Prisma-Multimodal/ViT-Prisma)

+ **LLaVA-Intrepret** [Towards Interpreting Visual Information Processing in Vision-Language Models](https://arxiv.org/abs/2410.07149) (Oct. 09, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.07149)
  [![Star](https://img.shields.io/github/stars/clemneo/llava-interp.svg?style=social&label=Star)](https://github.com/clemneo/llava-interp)

+ **LVLM-Intrepret** [LVLM-Intrepret: An Interpretability Tool for Large Vision-Language Models](https://arxiv.org/abs/2404.03118) (June. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.03118)
  [![Star](https://img.shields.io/github/stars/IntelLabs/lvlm-interpret.svg?style=social&label=Star)](https://github.com/IntelLabs/lvlm-interpret)

+ **ViT Prisma** [ViT Prisma: A Mechanistic Interpretability Library for Vision Transformers](https://github.com/soniajoseph/vit-prisma) (2023)
  [![Star](https://img.shields.io/github/stars/soniajoseph/vit-prisma.svg?style=social&label=Star)](https://github.com/soniajoseph/vit-prisma)

+ **Causal Tracing Tool 4 BLIP** [Towards Vision-Language Mechanistic Interpretability: A Causal Tracing Tool for BLIP](https://arxiv.org/abs/2308.14179) (Aug. 27, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.14179)
  [![Star](https://img.shields.io/github/stars/vedantpalit/Towards-Vision-Language-Mechanistic-Interpretability.svg?style=social&label=Star)](https://github.com/vedantpalit/Towards-Vision-Language-Mechanistic-Interpretability)


