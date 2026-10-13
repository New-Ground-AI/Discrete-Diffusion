[![arXiv](https://img.shields.io/badge/arXiv-2607.13431-b31b1b)](https://arxiv.org/abs/2607.13431)
[![Hugging Face Paper](https://img.shields.io/badge/🤗%20Paper-2607.13431-yellow)](https://huggingface.co/papers/2607.13431)

# Discrete Diffusion Models: A Unified Framework from Tokenization to Generation

See the [project overview](https://new-ground-ai.github.io/projects/discrete-diffusion/) for a summary of the survey and its resources.

Discrete diffusion has emerged as a compelling alternative to autoregressive generation: it enables parallel decoding and, unlike left-to-right models; it can revise earlier decisions in light of later context. But it comes with a catch that continuous diffusion never faces: in image space, the state space is fixed and Gaussian noise has an obvious geometry. In categorical space, there is no default notion of a "small perturbation."

Our central thesis: the construction of the discrete state space, tokenization, is not a preprocessing detail. It is the primary design axis. It determines the topology of corruption, the difficulty of the denoising task, downstream controllability and validity, and the computational cost.

Please consider to cite our survey paper if it is helpful for you:
```bibtex
@misc{yuan2026discrete,
      title={Discrete Diffusion Models: A Unified Framework from Tokenization to Generation}, 
      author={Ye Yuan and Weien Li and Rui Song and Zeyu Li and Haochen Liu and Xiangyu Kong and Zixuan Dong and Linfeng Du and Zipeng Sun and Weixu Zhang and Jiaxin Huang and Changjiang Han and Yonghan Yang and Zichen Zhao and Xiuyuan Hu and Haolun Wu and Yankai Chen and Fengran Mo and Jikun Kang and Bowei He and Dawn Song and Philip S. Yu and Xue Liu},
      year={2026},
      eprint={2607.13431},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2607.13431}, 
}
```

## Paper Collection

Regenerate this table with:

```bash
python scripts/update_paper_collection_readme.py --input data/paper_collection.xlsx --readme README.md
```

| Venue | Year | Paper Title | Publication Link |
| --- | --- | --- | --- |
| AAAI | 2021 | Majority Opinion Diffusion in Social Networks: An Adversarial Approach | [Link](https://aaai.org/papers/05611-majority-opinion-diffusion-in-social-networks-an-adversarial-approach/) |
| AAAI | 2023 | Conditional Diffusion Based on Discrete Graph Structures for Molecular Graph Generatio | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/25549) |
| AAAI | 2023 | Refined Semantic Enhancement towards Frequency Diffusion for Video Captioning | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/25484) |
| AAAI | 2024 | A Generalized Neural Diffusion Framework on Graphs | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/28716) |
| AAAI | 2024 | Hyperbolic Graph Diffusion Model | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/29512) |
| AAAI | 2024 | KGDM: A Diffusion Model to Capture Multiple Relation Semantics for Knowledge Graph Embedding | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/28732) |
| AAAI | 2024 | Mastering Context-to-Label Representation Transformation for Event Causality Identification with Diffusion Models | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/29840) |
| AAAI | 2024 | ParaGuide: Guided Diffusion Paraphrasers for Plug-and-Play Textual Style Transfer | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/29780) |
| AAAI | 2024 | PoetryDiffusion: Towards Joint Semantic and Metrical Manipulation in Poetry Generation | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/29787) |
| AAAI | 2024 | Text Diffusion with Reinforced Conditioning | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/29316) |
| AAAI | 2024 | Text-Guided Molecule Generation with Diffusion Language Model | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/27761) |
| AAAI | 2025 | FreqTS: Frequency-Aware Token Selection for Accelerating Diffusion Models | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/33008) |
| AAAI | 2025 | HYGENE: A Diffusion-Based Hypergraph Generation Method | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/33833) |
| AAAI | 2025 | LLM-DR: A Novel LLM-Aided Diffusion Model for Rule Generation on Temporal Knowledge Graphs | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/33249) |
| AAAI | 2025 | TEncDM: Understanding the Properties of the Diffusion Model in the Space of Language Model Encodings | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/34696) |
| AAAI | 2025 | Text-Diffusion Red-Teaming of Large Language Models: Unveiling Harmful Behaviors with Proximity Constraints | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/34967) |
| ACL | 2023 | Controllable Conversation Generation with Conversation Structures via Diffusion Models | [Link](https://aclanthology.org/2023.findings-acl.454/) |
| ACL | 2023 | DiffusionBERT: Improving Generative Masked Language Models with Diffusion Models | [Link](https://aclanthology.org/2023.acl-long.248/) |
| ACL | 2023 | SSD-LM: Semi-autoregressive Simplex-based Diffusion Language Model for Text Generation and Modular Control | [Link](https://aclanthology.org/2023.acl-long.647/) |
| ACL | 2024 | DiffuCOMET: Contextual Commonsense Knowledge Diffusion | [Link](https://aclanthology.org/2024.acl-long.264/) |
| ACL | 2024 | Diffusion Guided Language Modeling | [Link](https://aclanthology.org/2024.findings-acl.887/) |
| ACL | 2024 | Lang2Mol-Diff: A Diffusion-Based Generative Model for Language-to-Molecule Translation Leveraging SELFIES Representation | [Link](https://aclanthology.org/2024.langmol-1.15/) |
| ACL | 2024 | Pinpointing Diffusion Grid Noise to Enhance Aspect Sentiment Quad Prediction | [Link](https://aclanthology.org/2024.findings-acl.222/) |
| ACL | 2025 | DiffLM: Controllable Synthetic Data Generation via Diffusion Language Models | [Link](https://aclanthology.org/2025.findings-acl.1061/) |
| ACL | 2025 | DiffPO: Diffusion-styled Preference Optimization for Inference Time Alignment of Large Language Models | [Link](https://aclanthology.org/2025.acl-long.926/) |
| ACL | 2025 | Diffusion Directed Acyclic Transformer for Non-Autoregressive Machine Translation | [Link](https://aclanthology.org/2025.acl-short.64/) |
| ACL | 2025 | EdiText: Controllable Coarse-to-Fine Text Editing with Diffusion Language Models | [Link](https://aclanthology.org/2025.acl-long.1111/) |
| ACL | 2025 | Planning with Diffusion Models for Target-Oriented Dialogue Systems | [Link](https://aclanthology.org/2025.acl-long.993/) |
| ACL | 2025 | ReflectDiffu: Reflect between Emotion-intent Contagion and Mimicry for Empathetic Response Generation via a RL-Diffusion Framework | [Link](https://aclanthology.org/2025.acl-long.1235/) |
| ACL | 2025 | Segment-Level Diffusion: A Framework for Controllable Long-Form Generation with Diffusion Language Models | [Link](https://aclanthology.org/2025.acl-long.210/) |
| ACL | 2025 | TESS 2: A Large-Scale Generalist Diffusion Language Model | [Link](https://aclanthology.org/2025.acl-long.1029/) |
| ACL | 2025 | Unifying Continuous and Discrete Text Diffusion with Non-simultaneous Diffusion Processes | [Link](https://aclanthology.org/2025.acl-long.565/) |
| COLING | 2024 | Few-shot Temporal Pruning Accelerates Diffusion Models for Text Generation | [Link](https://aclanthology.org/2024.lrec-main.637/) |
| COLING | 2025 | Addressing the Training-Inference Discrepancy in Discrete Diffusion for Text Generation | [Link](https://aclanthology.org/2025.coling-main.477/) |
| COLM | 2024 | A Reparameterized Discrete Diffusion Model for Text Generation | [Link](https://openreview.net/forum?id=PEQFHRUFca) |
| COLM | 2025 | Unifying Autoregressive and Diffusion-Based Sequence Generation | [Link](https://openreview.net/forum?id=rgq9BFXSFl) |
| EMNLP | 2023 | A Cheaper and Better Diffusion Language Model with Soft-Masked Noise | [Link](https://aclanthology.org/2023.emnlp-main.289/) |
| EMNLP | 2023 | Complex Event Schema Induction with Knowledge-Enriched Diffusion Model | [Link](https://aclanthology.org/2023.findings-emnlp.319/) |
| EMNLP | 2023 | DeTiME: Diffusion-Enhanced Topic Modeling using Encoder-decoder based LLM | [Link](https://aclanthology.org/2023.findings-emnlp.606.pdf) |
| EMNLP | 2023 | DiffS2UT: A Semantic Preserving Diffusion Model for Textless Direct Speech-to-Speech Translation | [Link](https://aclanthology.org/2023.emnlp-main.709/) |
| EMNLP | 2023 | DiffuSeq-v2: Bridging Discrete and Continuous Text Spaces for Accelerated Seq2Seq Diffusion Models | [Link](https://aclanthology.org/2023.findings-emnlp.660/) |
| EMNLP | 2023 | DiffusionSL: Sequence Labeling via Tag Diffusion Process | [Link](https://aclanthology.org/2023.findings-emnlp.860/) |
| EMNLP | 2023 | RethinkingTMSC: An Empirical Study for Target-Oriented Multimodal Sentiment Classification | [Link](https://aclanthology.org/2023.findings-emnlp.21.pdf) |
| EMNLP | 2023 | ScanDL: A Diffusion Model for Generating Synthetic Scanpaths on Texts | [Link](https://aclanthology.org/2023.emnlp-main.960/) |
| EMNLP | 2024 | An Effective Deployment of Diffusion LM for Data Augmentation in Low-Resource Sentiment Classification | [Link](https://aclanthology.org/2024.emnlp-main.109/) |
| EMNLP | 2024 | Diffusion-NAT: Self-Prompting Discrete Diffusion for Non-Autoregressive Text Generation | [Link](https://aclanthology.org/2024.eacl-long.86.pdf) |
| EMNLP | 2024 | Explicitly Representing Syntax Improves Sentence-to-Layout Prediction of Unexpected Situations | [Link](https://aclanthology.org/2024.tacl-1.15/) |
| EMNLP | 2024 | Predicting the Unpredictable: Uncertainty-Aware Reasoning over Temporal Knowledge Graphs via Diffusion Process | [Link](https://aclanthology.org/2024.findings-acl.343.pdf) |
| EMNLP | 2024 | Speaking in Wavelet Domain: A Simple and Efficient Approach to Speed up Speech Diffusion Model | [Link](https://aclanthology.org/2024.emnlp-main.9/) |
| EMNLP | 2025 | Conditional [MASK] Discrete Diffusion Language Model | [Link](https://aclanthology.org/2025.emnlp-main.450/) |
| EMNLP | 2025 | Diffusion vs. Autoregressive Language Models: A Text Embedding Perspective | [Link](https://aclanthology.org/2025.emnlp-main.213/) |
| EMNLP | 2025 | DiffusionAttacker: Diffusion-Driven Prompt Manipulation for LLM Jailbreak | [Link](https://aclanthology.org/2025.emnlp-main.1128/) |
| EMNLP | 2025 | Flexible-length Text Infilling for Discrete Diffusion Models | [Link](https://aclanthology.org/2025.emnlp-main.1597/) |
| EMNLP | 2025 | LEAF: Large Language Diffusion Model for Time Series Forecasting | [Link](https://aclanthology.org/2025.findings-emnlp.58/) |
| EMNLP | 2025 | Masked Diffusion Captioning for Visual Feature Learning | [Link](https://aclanthology.org/2025.findings-emnlp.1376.pdf) |
| EMNLP | 2025 | Reward-Weighted Sampling: Enhancing Non-Autoregressive Characteristics in Masked Diffusion LLMs | [Link](https://aclanthology.org/2025.emnlp-main.1754/) |
| EMNLP | 2025 | SynC-LLM: Generation of Large-Scale Synthetic Circuit Code with Hierarchical Language Models | [Link](https://aclanthology.org/2025.emnlp-main.877.pdf) |
| EMNLP | 2025 | Unifying Continuous and Discrete Text Diffusion with Non-simultaneous Diffusion Processes | [Link](https://aclanthology.org/2025.acl-long.565.pdf) |
| High-citation | 2015 | Deep Unsupervised Learning using Nonequilibrium Thermodynamics | [Link](https://proceedings.mlr.press/v37/sohl-dickstein15.html) |
| High-citation | 2021 | Argmax Flows and Multinomial Diffusion: Learning Categorical Distributions | [Link](https://proceedings.neurips.cc/paper_files/paper/2021/hash/67d96d458abdef21792e6d8e590244e7-Abstract.html) |
| High-citation | 2021 | Beyond In-Place Corruption: Insertion and Deletionin Denoising Probabilistic Models | [Link](https://openreview.net/forum?id=cAsVBUe1Rnj) |
| High-citation | 2021 | ImageBART: Bidirectional Context with Multinomial Diffusion for Autoregressive Image Synthesis | [Link](https://proceedings.neurips.cc/paper/2021/hash/1cdf14d1e3699d61d237cf76ce1c2dca-Abstract.html) |
| High-citation | 2021 | Structured Denoising Diffusion Models in Discrete State-Spaces | [Link](https://proceedings.neurips.cc/paper/2021/hash/958c530554f78bcd8e97125b70e6973d-Abstract.html) |
| High-citation | 2022 | Antigen-Specific Antibody Design and Optimization with Diffusion-Based Generative Models for Protein Structures | [Link](https://proceedings.neurips.cc/paper_files/paper/2022/hash/3fa7d76a0dc1179f1e98d1bc62403756-Abstract-Conference.html) |
| High-citation | 2022 | Autoregressive Diffusion Models | [Link](https://openreview.net/forum?id=Lm8T39vLDTE) |
| High-citation | 2022 | Categorical SDEs with Simplex Diffusion | [Link](https://arxiv.org/abs/2210.14784) |
| High-citation | 2022 | Concrete Score Matching: Generalized Score Matching for Discrete Data | [Link](https://proceedings.neurips.cc/paper_files/paper/2022/hash/df04a35d907e894d59d4eab1f92bc87b-Abstract-Conference.html) |
| High-citation | 2022 | DiffusER: Discrete Diffusion via Edit-based Reconstruction | [Link](https://arxiv.org/abs/2210.16886) |
| High-citation | 2022 | Diffusion Models for Graphs Benefit From Discrete State Spaces | [Link](https://arxiv.org/abs/2210.01549) |
| High-citation | 2022 | Diffusion-LM Improves Controllable Text Generation | [Link](https://proceedings.neurips.cc/paper_files/paper/2022/hash/1be5bc25d50895ee656b8c2d9eb89d6a-Abstract-Conference.html) |
| High-citation | 2022 | Exploring Discrete Diffusion Models for Image Captioning | [Link](https://arxiv.org/abs/2211.11694) |
| High-citation | 2022 | Global Context With Discrete Diffusion in Vector Quantised Modelling for Image Generation | [Link](https://openaccess.thecvf.com/content/CVPR2022/html/Hu_Global_Context_With_Discrete_Diffusion_in_Vector_Quantised_Modelling_for_CVPR_2022_paper.html) |
| High-citation | 2022 | Improved Masked Image Generation with Token-Critic | [Link](https://link.springer.com/chapter/10.1007/978-3-031-20050-2_5) |
| High-citation | 2022 | Improved Vector Quantized Diffusion Models | [Link](https://arxiv.org/abs/2205.16007) |
| High-citation | 2022 | Score-based Continuous-time Discrete Diffusion Models | [Link](https://arxiv.org/abs/2211.16750) |
| High-citation | 2022 | Training and Inference on Any-Order Autoregressive Models the Right Way | [Link](https://proceedings.neurips.cc/paper_files/paper/2022/hash/123fd8a56501194823c8e0dca00733df-Abstract-Conference.html) |
| High-citation | 2022 | Unified Discrete Diffusion for Simultaneous Vision-Language Generation | [Link](https://arxiv.org/abs/2211.14842) |
| High-citation | 2022 | Unleashing Transformers: Parallel Token Prediction with Discrete Absorbing Diffusion for Fast High-Resolution Image Generation from Vector-Quantized Codes | [Link](https://link.springer.com/chapter/10.1007/978-3-031-20050-2_11) |
| High-citation | 2022 | Vector Quantized Diffusion Model with CodeUnet for Text-to-Sign Pose Sequences Generation | [Link](https://openreview.net/forum?id=RdJY39KRUCX) |
| High-citation | 2023 | 3D Equivariant Diffusion for Target-Aware Molecule Generation and Affinity Prediction | [Link](https://openreview.net/forum?id=kJqXEPXMsE0) |
| High-citation | 2023 | 3DQD: Generalized Deep 3D Shape Prior via Part-Discretized Diffusion Process | [Link](https://ieeexplore.ieee.org/document/10203778) |
| High-citation | 2023 | A Survey of Diffusion Models in Natural Language Processing | [Link](https://arxiv.org/abs/2305.14671) |
| High-citation | 2023 | An overview of diffusion models for text generation | [Link](https://ieeexplore.ieee.org/abstract/document/10159911/keywords#keywords) |
| High-citation | 2023 | Analog Bits: Generating Discrete Data using Diffusion Models with Self-Conditioning | [Link](https://openreview.net/forum?id=3itjR9QxFw) |
| High-citation | 2023 | Autoregressive Diffusion Model for Graph Generation | [Link](https://proceedings.mlr.press/v202/kong23b.html) |
| High-citation | 2023 | Binary Latent Diffusion | [Link](https://openaccess.thecvf.com/content/CVPR2023/html/Wang_Binary_Latent_Diffusion_CVPR_2023_paper.html) |
| High-citation | 2023 | Blackout Diffusion: Generative Diffusion Models in Discrete-State Spaces | [Link](https://proceedings.mlr.press/v202/santos23a.html) |
| High-citation | 2023 | D4Explainer: In-distribution Explanations of Graph Neural Network via Discrete Denoising Diffusion | [Link](https://proceedings.neurips.cc/paper_files/paper/2023/hash/f978c8f3b5f399cae464e85f72e28503-Abstract-Conference.html) |
| High-citation | 2023 | D4Explainer: In-distribution Explanations of Graph Neural Network via Discrete Denoising Diffusion | [Link](https://neurips.cc/virtual/2023/poster/72212) |
| High-citation | 2023 | DiffMol: 3D Structured Molecule Generation with Discrete Denoising Diffusion Probabilistic Models | [Link](https://openreview.net/forum?id=x43ZyXJC9q#all) |
| High-citation | 2023 | DiffPattern: Layout Pattern Generation via Discrete Diffusion | [Link](https://ieeexplore.ieee.org/abstract/document/10248009?casa_token=81ekBCisIEAAAAAA:-fsh0rGUlKqbh2qNjyPAnp84JYRWICarn7wNCuvbluqaPuzREm94LfYvzx8V60u_7Rz3B9whYio) |
| High-citation | 2023 | DiffPattern: Layout Pattern Generation via Discrete Diffusion | [Link](https://ieeexplore.ieee.org/abstract/document/10248009) |
| High-citation | 2023 | DiffSDS: A language diffusion model for protein backbone inpainting under geometric conditions and constraints | [Link](https://arxiv.org/abs/2301.09642) |
| High-citation | 2023 | Diffsound: Discrete Diffusion Model for Text-to-Sound Generation | [Link](https://ieeexplore.ieee.org/abstract/document/10112585?casa_token=0FESaTU_4e8AAAAA:gcJg3x53NaypXVUT-jY7_1CPlyW-FRX-5Y-noJsbfdZ0KKmh5ha5T-VhQqERMSmNgLYgeNBnFgqbjrA) |
| High-citation | 2023 | DiffuSeq: Sequence to Sequence Text Generation with Diffusion Models | [Link](https://openreview.net/forum?id=jQj-_rLVXsj) |
| High-citation | 2023 | Diffusion Language Models Can Perform Many Tasks with Scaling and Instruction-Finetuning | [Link](https://arxiv.org/abs/2308.12219) |
| High-citation | 2023 | Diffusion Models for Non-autoregressive Text Generation: A Survey | [Link](https://arxiv.org/abs/2303.06574) |
| High-citation | 2023 | Diffusion Models: A Comprehensive Survey of Methods and Applications | [Link](https://dl.acm.org/doi/full/10.1145/3626235) |
| High-citation | 2023 | DIFUSCO: Graph-based Diffusion Solvers for Combinatorial Optimization | [Link](https://proceedings.neurips.cc/paper_files/paper/2023/hash/0ba520d93c3df592c83a611961314c98-Abstract-Conference.html) |
| High-citation | 2023 | DiGress: Discrete Denoising diffusion for graph generation | [Link](https://openreview.net/forum?id=UaAD-Nu86WX) |
| High-citation | 2023 | Dirichlet Diffusion Score Model for Biological Sequence Generation | [Link](https://proceedings.mlr.press/v202/avdeyev23a.html) |
| High-citation | 2023 | Discrete Contrastive Diffusion for Cross-Modal Music and Image Generation | [Link](https://openreview.net/forum?id=1-MBdJssZ-S) |
| High-citation | 2023 | Discrete diffusion for co-speech gesture synthesis | [Link](https://dl.acm.org/doi/abs/10.1145/3610661.3616556) |
| High-citation | 2023 | DiSK: A Diffusion Model for Structured Knowledge | [Link](https://arxiv.org/abs/2312.05253) |
| High-citation | 2023 | DiverseMotion: Towards Diverse Human Motion Generation via Discrete Diffusion | [Link](https://arxiv.org/abs/2309.01372) |
| High-citation | 2023 | DLT: Conditioned layout generation with Joint Discrete-Continuous Diffusion Layout Transformer | [Link](https://openaccess.thecvf.com/content/ICCV2023/html/Levi_DLT_Conditioned_layout_generation_with_Joint_Discrete-Continuous_Diffusion_Layout_Transformer_ICCV_2023_paper.html) |
| High-citation | 2023 | Efficient and Degree-Guided Graph Generation via Discrete Diffusion Modeling | [Link](https://proceedings.mlr.press/v202/chen23k.html) |
| High-citation | 2023 | Formulating Discrete Probability Flow Through Optimal Transport | [Link](https://proceedings.neurips.cc/paper_files/paper/2023/hash/e6e706454d72c18582b9c1ff70b11f7d-Abstract-Conference.html) |
| High-citation | 2023 | Generalized Deep 3D Shape Prior via Part-Discretized Diffusion Process | [Link](https://openaccess.thecvf.com/content/CVPR2023/html/Li_Generalized_Deep_3D_Shape_Prior_via_Part-Discretized_Diffusion_Process_CVPR_2023_paper.html) |
| High-citation | 2023 | GraphGUIDE: Interpretable and controllable conditional graph generation with discrete Bernoulli diffusion | [Link](https://openreview.net/forum?id=w4Zb1ov9qNi) |
| High-citation | 2023 | LayoutDiffusion: Improving Graphic Layout Generation by Discrete Diffusion Probabilistic Models | [Link](https://openaccess.thecvf.com/content/ICCV2023/html/Zhang_LayoutDiffusion_Improving_Graphic_Layout_Generation_by_Discrete_Diffusion_Probabilistic_Models_ICCV_2023_paper.html) |
| High-citation | 2023 | LayoutDM: Discrete Diffusion Model for Controllable Layout Generation | [Link](https://openaccess.thecvf.com/content/CVPR2023/html/Inoue_LayoutDM_Discrete_Diffusion_Model_for_Controllable_Layout_Generation_CVPR_2023_paper.html) |
| High-citation | 2023 | MAGVIT: Masked Generative Video Transformer | [Link](https://openaccess.thecvf.com/content/CVPR2023/html/Yu_MAGVIT_Masked_Generative_Video_Transformer_CVPR_2023_paper.html) |
| High-citation | 2023 | MAGVLT: Masked Generative Vision-and-Language Transformer | [Link](https://openaccess.thecvf.com/content/CVPR2023/html/Kim_MAGVLT_Masked_Generative_Vision-and-Language_Transformer_CVPR_2023_paper.html) |
| High-citation | 2023 | MatterGen: a generative model for inorganic materials design | [Link](https://arxiv.org/abs/2312.03687) |
| High-citation | 2023 | Molecular Fragment-based Diffusion Model for Drug Discovery | [Link](https://openreview.net/forum?id=LPdXni4tC8) |
| High-citation | 2023 | Muse: Text-To-Image Generation via Masked Generative Transformers | [Link](https://arxiv.org/abs/2301.00704) |
| High-citation | 2023 | Prostate MRI super-resolution using discrete residual diffusion model | [Link](https://ieeexplore.ieee.org/abstract/document/10385851) |
| High-citation | 2023 | Protein Design with Guided Discrete Diffusion | [Link](https://proceedings.neurips.cc/paper_files/paper/2023/hash/29591f355702c3f4436991335784b503-Abstract-Conference.html) |
| High-citation | 2023 | Regularized Vector Quantization for Tokenized Image Synthesis | [Link](https://openaccess.thecvf.com/content/CVPR2023/html/Zhang_Regularized_Vector_Quantization_for_Tokenized_Image_Synthesis_CVPR_2023_paper.html) |
| High-citation | 2023 | SegRefiner: Towards Model-Agnostic Segmentation Refinement with Discrete Diffusion Process | [Link](https://proceedings.neurips.cc/paper_files/paper/2023/hash/fc0cc55dca3d791c4a0bb2d8ddeefe4f-Abstract-Conference.html) |
| High-citation | 2023 | Sparse Training of Discrete Diffusion Models for Graph Generation | [Link](https://arxiv.org/abs/2311.02142) |
| High-citation | 2023 | TabDDPM: Modelling Tabular Data with Diffusion Models | [Link](https://proceedings.mlr.press/v202/kotelnikov23a.html) |
| High-citation | 2023 | Text-Conditioned Sampling Framework for Text-to-Image Generation with Masked Generative Models | [Link](https://openaccess.thecvf.com/content/ICCV2023/html/Lee_Text-Conditioned_Sampling_Framework_for_Text-to-Image_Generation_with_Masked_Generative_Models_ICCV_2023_paper.html) |
| High-citation | 2023 | Towards Joint Sequence-Structure Generation of Nucleic Acid and Protein Complexes with SE(3)-Discrete Diffusion | [Link](https://arxiv.org/abs/2401.06151) |
| High-citation | 2023 | Unaligned 2D to 3D Translation with Conditional Vector-Quantized Code Diffusion using Transformers | [Link](https://openaccess.thecvf.com/content/ICCV2023/html/Corona-Figueroa_Unaligned_2D_to_3D_Translation_with_Conditional_Vector-Quantized_Code_Diffusion_ICCV_2023_paper.html) |
| High-citation | 2023 | VampNet: Music Generation via Masked Acoustic Token Modeling | [Link](https://arxiv.org/abs/2307.04686) |
| High-citation | 2024 | A Large-Scale Foundation Model for RNA Function and Structure Prediction | [Link](https://www.biorxiv.org/content/10.1101/2024.11.28.625345v1.abstract) |
| High-citation | 2024 | A survey of generative AI for de novo drug design: new frontiers in molecule and protein generation | [Link](https://academic.oup.com/bib/article/25/4/bbae338/7713723?login=false) |
| High-citation | 2024 | A Survey on Diffusion Models for Recommender Systems | [Link](https://arxiv.org/abs/2409.05033) |
| High-citation | 2024 | A Unified Conditional Diffusion Framework for Dual Protein Targets-Based Bioactive Molecule Generation | [Link](https://ieeexplore.ieee.org/abstract/document/10497533) |
| High-citation | 2024 | Advancing graph generation through beta diffusion | [Link](https://openreview.net/forum?id=x1An5a3U9I) |
| High-citation | 2024 | Breaking Determinism: Fuzzy Modeling of Sequential Recommendation Using Discrete State Space Diffusion Model | [Link](https://proceedings.neurips.cc/paper_files/paper/2024/hash/286d67ff96f99c614f75dbcfb72a3e5f-Abstract-Conference.html) |
| High-citation | 2024 | Bridging discrete and continuous state spaces: Exploring the Ehrenfest process in time-continuous diffusion models | [Link](https://arxiv.org/abs/2405.03549) |
| High-citation | 2024 | Categorical Flow Matching on Statistical Manifolds | [Link](https://proceedings.neurips.cc/paper_files/paper/2024/hash/62a58f2130894e44e8a272c563a2c6f1-Abstract-Conference.html) |
| High-citation | 2024 | Cometh: A continuous-time discrete-state graph diffusion model | [Link](https://arxiv.org/abs/2406.06449) |
| High-citation | 2024 | Cons2Plan: Vector Floorplan Generation from Various Conditions via a Learning Framework based on Conditional Diffusion Models | [Link](https://dl.acm.org/doi/abs/10.1145/3664647.3680681) |
| High-citation | 2024 | Context-Guided Diffusion for Out-of-Distribution Molecular and Protein Design | [Link](https://proceedings.mlr.press/v235/klarner24a.html) |
| High-citation | 2024 | Convergence of Score-Based Discrete Diffusion Models: A Discrete-Time Analysis | [Link](https://arxiv.org/abs/2410.02321) |
| High-citation | 2024 | Cross-Modality Diffusion Modeling and Sampling for Speech Recognition | [Link](https://arxiv.org/abs/2402.16627v1) |
| High-citation | 2024 | D Styler: Advancing Arbitrary Style Transfer with Discrete Diffusion Methods | [Link](https://arxiv.org/abs/2408.03558) |
| High-citation | 2024 | D-Flow: Multi-modality Flow Matching for D-peptide Design | [Link](https://arxiv.org/abs/2411.10618) |
| High-citation | 2024 | Decap: Towards generalized explicit caption editing via diffusion mechanism | [Link](https://link.springer.com/chapter/10.1007/978-3-031-72775-7_21) |
| High-citation | 2024 | DePLM: Denoising Protein Language Models for Property Optimization | [Link](https://openreview.net/forum?id=MU27zjHBcW) |
| High-citation | 2024 | Derivative-Free Guidance in Continuous and Discrete Diffusion Models with Soft Value-Based Decoding | [Link](https://arxiv.org/abs/2408.08252) |
| High-citation | 2024 | Di2Pose: Discrete Diffusion Model for Occluded 3D Human Pose Estimation | [Link](https://proceedings.neurips.cc/paper_files/paper/2024/hash/b2e20d7402c9985eae4ba924c65370a8-Abstract-Conference.html) |
| High-citation | 2024 | Diffuse, Sample, Project: Plug-And-Play Controllable Graph Generation | [Link](https://proceedings.mlr.press/v235/sharma24b.html) |
| High-citation | 2024 | Diffusion Language Models Are Versatile Protein Learners | [Link](https://proceedings.mlr.press/v235/wang24ct.html) |
| High-citation | 2024 | Diffusion models in text generation: a survey | [Link](https://peerj.com/articles/cs-1905/) |
| High-citation | 2024 | Diffusion of Thought: Chain-of-Thought Reasoning in Diffusion Language Models | [Link](https://proceedings.neurips.cc/paper_files/paper/2024/hash/be30024e7fa2c29cac7a6dafcbb8571f-Abstract-Conference.html) |
| High-citation | 2024 | Diffusion-NAT: Self-Prompting Discrete Diffusion for Non-Autoregressive Text Generation | [Link](https://aclanthology.org/2024.eacl-long.86/) |
| High-citation | 2024 | Dirichlet Flow Matching with Applications to DNA Sequence Design | [Link](https://proceedings.mlr.press/v235/stark24b.html) |
| High-citation | 2024 | DisCo-Diff: Enhancing Continuous Diffusion Models with Discrete Latents | [Link](https://arxiv.org/abs/2407.03300) |
| High-citation | 2024 | Discrete Conditional Diffusion for Reranking in Recommendation | [Link](https://dl.acm.org/doi/abs/10.1145/3589335.3648313) |
| High-citation | 2024 | Discrete Copula Diffusion | [Link](https://arxiv.org/abs/2410.01949) |
| High-citation | 2024 | Discrete Diffusion Modeling by Estimating the Ratios of the Data Distribution | [Link](https://proceedings.mlr.press/v235/lou24a.html) |
| High-citation | 2024 | Discrete diffusion models with Refined Language-Image Pre-trained representations for remote sensing image captioning | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0167865524002861) |
| High-citation | 2024 | Discrete Flow Matching | [Link](https://proceedings.neurips.cc/paper_files/paper/2024/hash/f0d629a734b56a642701bba7bc8bb3ed-Abstract-Conference.html) |
| High-citation | 2024 | Discrete residual diffusion model for high-resolution prostate MRI synthesis | [Link](https://pubmed.ncbi.nlm.nih.gov/38271725/) |
| High-citation | 2024 | Discrete-state Continuous-time Diffusion for Graph Generation | [Link](https://proceedings.neurips.cc/paper_files/paper/2024/hash/91813e5ddd9658b99be4c532e274b49c-Abstract-Conference.html) |
| High-citation | 2024 | Discriminator guidance for autoregressive diffusion models | [Link](https://proceedings.mlr.press/v238/ekstrom-kelvinius24a.html) |
| High-citation | 2024 | Efficient Generative Modeling with Residual Vector Quantization-Based Tokens | [Link](https://openreview.net/forum?id=f8uPzuMNDq) |
| High-citation | 2024 | Equivariant 3D-conditional diffusion model for molecular linker design | [Link](https://www.nature.com/articles/s42256-024-00815-9) |
| High-citation | 2024 | FairWire: Fair Graph Generation | [Link](https://proceedings.neurips.cc/paper_files/paper/2024/hash/e105d1cabb6ee2495595e2baf25493b5-Abstract-Conference.html) |
| High-citation | 2024 | Fast Sampling via De-randomization for Discrete Diffusion Models | [Link](https://openreview.net/forum?id=m4Ya9RkEEW) |
| High-citation | 2024 | Fast Sampling via Discrete Non-Markov Diffusion Models with Predetermined Transition Time | [Link](https://docs.google.com/spreadsheets/d/1H5IErhaEG3GiabGrsXtLTd_IE2CLaQihVz27EG4Z7qA/edit?gid=1530041925#gid=1530041925) |
| High-citation | 2024 | G2P-DDM: Generating Sign Pose Sequence from Gloss Sequence with Discrete Diffusion Model | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/28441) |
| High-citation | 2024 | Generative AI for Controllable Protein Sequence Design: A Survey | [Link](https://arxiv.org/abs/2402.10516) |
| High-citation | 2024 | Generative Flows on Discrete State-Spaces: Enabling Multimodal Flows with Applications to Protein Co-Design | [Link](https://proceedings.mlr.press/v235/campbell24a.html) |
| High-citation | 2024 | Graph Diffusion Transformers for Multi-Conditional Molecular Generation | [Link](https://proceedings.neurips.cc/paper_files/paper/2024/hash/0f6931a9e339a012a9909306d7c758b4-Abstract-Conference.html) |
| High-citation | 2024 | Graph Generation with Diffusion Mixture | [Link](https://proceedings.mlr.press/v235/jo24b.html) |
| High-citation | 2024 | GRAPH-CONSTRAINED DIFFUSION FOR END-TO-END PATH PLANNING | [Link](https://openreview.net/forum?id=vuK8MhVtuu) |
| High-citation | 2024 | Guided Discrete Diffusion for Electronic Health Record Generation | [Link](https://arxiv.org/abs/2404.12314) |
| High-citation | 2024 | Informed Correctors for Discrete Diffusion Models | [Link](https://arxiv.org/abs/2407.21243) |
| High-citation | 2024 | Jump Your Steps: Optimizing Sampling Schedule of Discrete Diffusion Models | [Link](https://arxiv.org/abs/2410.07761) |
| High-citation | 2024 | Layout-Corrector: Alleviating Layout Sticking Phenomenon in Discrete Diffusion Model | [Link](https://link.springer.com/chapter/10.1007/978-3-031-72754-2_6) |
| High-citation | 2024 | M2D2M: Multi-Motion Generation from Text with Discrete Diffusion Models | [Link](https://link.springer.com/chapter/10.1007/978-3-031-72630-9_2) |
| High-citation | 2024 | Mixed Diffusion for 3D Indoor Scene Synthesis | [Link](https://arxiv.org/abs/2405.21066) |
| High-citation | 2024 | MUDiff: Unified Diffusion for Complete Molecule Generation | [Link](https://proceedings.mlr.press/v231/hua24a.html) |
| High-citation | 2024 | Multi-conditioned Graph Diffusion for Neural Architecture Search | [Link](https://openreview.net/forum?id=5VotySkajV) |
| High-citation | 2024 | Pard: Permutation-Invariant Autoregressive Diffusion for Graph Generation | [Link](https://proceedings.neurips.cc/paper_files/paper/2024/hash/0d89cf183391e12063cb63ff0d75ed95-Abstract-Conference.html) |
| High-citation | 2024 | Promises and pitfalls of generative masked language modeling: Theoretical framework and practical guidelines | [Link](https://proceedings.mlr.press/v235/li24af.html) |
| High-citation | 2024 | QT-Font: High-efficiency Font Synthesis via Quadtree-based Diffusion Models | [Link](https://dl.acm.org/doi/abs/10.1145/3641519.3657451) |
| High-citation | 2024 | Rethinking the Objectives of Vector-Quantized Tokenizers for Image Synthesis | [Link](https://openaccess.thecvf.com/content/CVPR2024/html/Gu_Rethinking_the_Objectives_of_Vector-Quantized_Tokenizers_for_Image_Synthesis_CVPR_2024_paper.html) |
| High-citation | 2024 | RNADiffFold: generative RNA secondary structure prediction using discrete diffusion models | [Link](https://academic.oup.com/bib/article/26/1/bbae618/7907889?login=false) |
| High-citation | 2024 | Scaling up Masked Diffusion Models on Text | [Link](https://arxiv.org/abs/2410.18514) |
| High-citation | 2024 | Simple and Effective Masked Diffusion Language Models | [Link](https://proceedings.neurips.cc/paper_files/paper/2024/hash/eb0b13cc515724ab8015bc978fdde0ad-Abstract-Conference.html) |
| High-citation | 2024 | Simplified and Generalized Masked Diffusion for Discrete Data | [Link](https://proceedings.neurips.cc/paper_files/paper/2024/hash/bad233b9849f019aead5e5cc60cef70f-Abstract-Conference.html) |
| High-citation | 2024 | Sketch-guided Image Inpainting with Partial Discrete Diffusion Process | [Link](https://openaccess.thecvf.com/content/CVPR2024W/NTIRE/html/Sharma_Sketch-guided_Image_Inpainting_with_Partial_Discrete_Diffusion_Process_CVPRW_2024_paper.html) |
| High-citation | 2024 | Steering Masked Discrete Diffusion Models via Discrete Denoising Posterior Prediction | [Link](https://arxiv.org/abs/2410.08134) |
| High-citation | 2024 | TabDiff: a Unified Diffusion Model for Multi-Modal Tabular Data Generation | [Link](https://openreview.net/forum?id=LoSpFLqaHg&noteId=LoSpFLqaHg) |
| High-citation | 2024 | TESS: Text-to-Text Self-Conditioned Simplex Diffusion | [Link](https://aclanthology.org/2024.eacl-long.144/) |
| High-citation | 2024 | Token-level guided discrete diffusion for membrane protein design | [Link](https://openreview.net/forum?id=TIuT6x9H42) |
| High-citation | 2024 | Toward better generalization: Shape feature-enhanced fastener defect detection with diffusion model | [Link](https://ieeexplore.ieee.org/abstract/document/10568203) |
| High-citation | 2024 | Towards Diverse and Efficient Audio Captioning via Diffusion Models | [Link](https://arxiv.org/abs/2409.09401) |
| High-citation | 2024 | Training-free guidance for discrete diffusion models for molecular generation | [Link](https://arxiv.org/abs/2409.07359) |
| High-citation | 2024 | Ultrafast Source Mask Optimization via Conditional Discrete Diffusion | [Link](https://ieeexplore.ieee.org/abstract/document/10419017?casa_token=gUQMbnYBRGAAAAAA:skxJAg8xXqc-B8pBTHfyVh2eBjNZSAJkf7eGWC5PuSvzQspmvFF-0zpXMdupEAQhaJmmcx_TBHw) |
| High-citation | 2024 | Unlocking Guidance for Discrete State-Space Diffusion and Flow Models | [Link](https://arxiv.org/abs/2406.01572) |
| High-citation | 2024 | Unsupervised training of diffusion models for feasible solution generation in neural combinatorial optimization | [Link](https://openreview.net/forum?id=AFfXlKFHXJ) |
| High-citation | 2024 | VQ-CAD: Computer-Aided Design model generation with vector quantized diffusion | [Link](https://www.sciencedirect.com/science/article/abs/pii/S016783962400061X) |
| High-citation | 2024 | Your Absorbing Discrete Diffusion Secretly Models the Conditional Distributions of Clean Data | [Link](https://arxiv.org/abs/2406.03736) |
| High-citation | 2025 | A Generative Foundation Model for Antibody Design | [Link](https://www.biorxiv.org/content/10.1101/2025.09.12.675771v1.abstract) |
| High-citation | 2025 | A Hyperbolic Discrete Diffusion 3D RNA Inverse Folding Model for Functional RNA Design | [Link](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.5c00527) |
| High-citation | 2025 | A Survey on Cache Methods in Diffusion Models: Toward Efficient Multi-Modal Generation | [Link](https://arxiv.org/abs/2510.19755) |
| High-citation | 2025 | A Survey on Diffusion Language Models | [Link](https://arxiv.org/abs/2508.10875) |
| High-citation | 2025 | A Survey on Parallel Text Generation: From Parallel Decoding to Diffusion Language Models | [Link](https://arxiv.org/abs/2508.08712) |
| High-citation | 2025 | A Theoretical Analysis of Discrete Flow Matching Generative Models | [Link](https://arxiv.org/abs/2509.22623) |
| High-citation | 2025 | A2D: Any-Order, Any-Step Safety Alignment for Diffusion Language Models | [Link](https://arxiv.org/abs/2509.23286) |
| High-citation | 2025 | A2D: Any-Order, Any-Step Safety Alignment for Diffusion Language Models | [Link](https://openreview.net/forum?id=URTnuyQJI1) |
| High-citation | 2025 | Absorb and Converge: Provable Convergence Guarantee for Absorbing Discrete Diffusion Models | [Link](https://arxiv.org/abs/2506.02318) |
| High-citation | 2025 | Accelerated Sampling from Masked Diffusion Models via Entropy Bounded Unmasking | [Link](https://arxiv.org/abs/2505.24857) |
| High-citation | 2025 | Accelerating diffusion large language models with slowfast sampling: The three golden principles | [Link](https://openreview.net/forum?id=bFJ8Sdr224) |
| High-citation | 2025 | Accelerating Diffusion LLM Inference via Local Determinism Propagation | [Link](https://arxiv.org/abs/2510.07081) |
| High-citation | 2025 | AdaBlock-dLLM: Semantic-Aware Diffusion LLM Inference via Adaptive Block Size | [Link](https://arxiv.org/abs/2509.26432) |
| High-citation | 2025 | Advancing retrosynthesis with retrieval-augmented graph generation | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/34203) |
| High-citation | 2025 | All-atom inverse protein folding through discrete flow matching | [Link](https://openreview.net/forum?id=8tQdwSCJmA) |
| High-citation | 2025 | An Efficient Diffusion-based Non-Autoregressive Solver for Traveling Salesman Problem | [Link](https://dl.acm.org/doi/abs/10.1145/3690624.3709343) |
| High-citation | 2025 | Anchored Diffusion Language Model | [Link](https://arxiv.org/abs/2505.18456) |
| High-citation | 2025 | Any-Order Flexible Length Masked Diffusion | [Link](https://arxiv.org/abs/2509.01025) |
| High-citation | 2025 | Any-Order GPT as Masked Diffusion Model: Decoupling Formulation and Architecture | [Link](https://arxiv.org/abs/2506.19935) |
| High-citation | 2025 | Attention Is All You Need for KV Cache in Diffusion LLMs | [Link](https://arxiv.org/abs/2510.14973) |
| High-citation | 2025 | Attention Sinks in Diffusion Language Models | [Link](https://arxiv.org/abs/2510.15731) |
| High-citation | 2025 | Audio-Conditioned Diffusion LLMs for ASR and Deliberation Processing | [Link](https://arxiv.org/abs/2509.16622) |
| High-citation | 2025 | Backdoor Attacks on Discrete Graph Diffusion Models | [Link](https://openreview.net/forum?id=f8hwLCAy7R) |
| High-citation | 2025 | BAD: Bidirectional Auto-Regressive Diffusion for Text-to-Motion Generation | [Link](https://ieeexplore.ieee.org/abstract/document/10889942?casa_token=249oCf9ybBUAAAAA:F4x-iD7WfMMJUAtofTtaYDoKyncuClIRwrFk5xy-8oPhrAaWaf3kz1_VldU51cgaRkatmwOX670CkhA) |
| High-citation | 2025 | Beyond Autoregression: An Empirical Study of Diffusion Large Language Models for Code Generation | [Link](https://arxiv.org/abs/2509.11252) |
| High-citation | 2025 | Beyond Autoregression: Discrete Diffusion for Complex Reasoning and Planning | [Link](https://openreview.net/forum?id=NRYgUzSPZz) |
| High-citation | 2025 | Beyond Fixed: Training-Free Variable-Length Denoising for Diffusion Large Language Models | [Link](https://arxiv.org/abs/2508.00819) |
| High-citation | 2025 | Beyond Surface Reasoning: Unveiling the True Long Chain-of-Thought Capacity of Diffusion Large Language Models | [Link](https://arxiv.org/abs/2510.09544) |
| High-citation | 2025 | Bigger Isn't Always Memorizing: Early Stopping Overparameterized Diffusion Models | [Link](https://arxiv.org/abs/2505.16959) |
| High-citation | 2025 | BInD: Bond and Interaction-Generating Diffusion Model for Multi-Objective Structure-Based Drug Design | [Link](https://pubmed.ncbi.nlm.nih.gov/40642896/) |
| High-citation | 2025 | Bit-level discrete diffusion with markov probabilistic models: An improved framework with sharp convergence bounds under minimal assumptions | [Link](https://icml.cc/virtual/2025/poster/44729) |
| High-citation | 2025 | Block Diffusion: Interpolating Between Autoregressive and Diffusion Language Models | [Link](https://arxiv.org/abs/2503.09573) |
| High-citation | 2025 | Blockwise SFT for Diffusion Language Models: Reconciling Bidirectional Attention and Autoregressive Decoding | [Link](https://arxiv.org/abs/2508.19529) |
| High-citation | 2025 | Boundary-Guided Policy Optimization for Memory-efficient RL of Diffusion Large Language Models | [Link](https://arxiv.org/abs/2510.11683) |
| High-citation | 2025 | Breaking AR's Sampling Bottleneck: Provable Acceleration via Diffusion Language Models | [Link](https://arxiv.org/abs/2505.21400) |
| High-citation | 2025 | Breaking AR’s Sampling Bottleneck: Provable Acceleration via Diffusion Language Models | [Link](https://openreview.net/forum?id=to1VYVar9W) |
| High-citation | 2025 | Bringing Stability to Diffusion: Decomposing and Reducing Variance of Training Masked Diffusion Models | [Link](https://arxiv.org/abs/2511.18159) |
| High-citation | 2025 | Can You Detect the Difference? | [Link](https://arxiv.org/abs/2507.10475) |
| High-citation | 2025 | CANDI: Hybrid Discrete-Continuous Diffusion Models | [Link](https://arxiv.org/abs/2510.22510) |
| High-citation | 2025 | Categorical Schrödinger Bridge Matching | [Link](https://arxiv.org/abs/2502.01416) |
| High-citation | 2025 | CDLM: Consistency Diffusion Language Models For Faster Sampling | [Link](https://arxiv.org/abs/2511.19269) |
| High-citation | 2025 | CFP-Gen: Combinatorial Functional Protein Generation via Diffusion Language Models | [Link](https://proceedings.mlr.press/v267/yin25g.html) |
| High-citation | 2025 | CFP-Gen: Combinatorial Functional Protein Generation via Diffusion Language Models | [Link](https://openreview.net/forum?id=EiM163eZyg) |
| High-citation | 2025 | Co-GRPO: Co-Optimized Group Relative Policy Optimization for Masked Diffusion Model | [Link](https://arxiv.org/abs/2512.22288) |
| High-citation | 2025 | CoDA: Coding LM via Diffusion Adaptation | [Link](https://arxiv.org/abs/2510.03270) |
| High-citation | 2025 | Coevolutionary Continuous Discrete Diffusion: Make Your Diffusion Language Model a Latent Reasoner | [Link](https://arxiv.org/abs/2510.03206) |
| High-citation | 2025 | Composable Score-based Graph Diffusion Model for Multi-Conditional Molecular Generation | [Link](https://arxiv.org/abs/2509.09451) |
| High-citation | 2025 | Constrained Discrete Diffusion | [Link](https://openreview.net/forum?id=Es4s9dtCjR) |
| High-citation | 2025 | Continuous-time Discrete-space Diffusion Model for Recommendation | [Link](https://arxiv.org/abs/2511.12114) |
| High-citation | 2025 | Continuously Augmented Discrete Diffusion model for Categorical Generative Modeling | [Link](https://arxiv.org/abs/2510.01329) |
| High-citation | 2025 | Convergence Analysis of Discrete Diffusion Model: Exact Implementation Through Uniformization | [Link](https://global-sci.com/index.php/jml/article/view/13211) |
| High-citation | 2025 | Cross-Domain Graph Data Scaling: A Showcase with Diffusion Models | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/120312) |
| High-citation | 2025 | CtrlDiff: Boosting Large Diffusion Language Models with Dynamic Block Prediction and Controllable Generation | [Link](https://arxiv.org/abs/2505.14455) |
| High-citation | 2025 | d-TreeRPO: Towards More Reliable Policy Optimization for Diffusion Language Models | [Link](https://arxiv.org/abs/2512.09675) |
| High-citation | 2025 | d1: Scaling Reasoning in Diffusion Large Language Models via Reinforcement Learning | [Link](http://arxiv.org/abs/2504.12216) |
| High-citation | 2025 | d2: Improved Techniques for Training Reasoning Diffusion Language Models | [Link](https://arxiv.org/abs/2509.21474) |
| High-citation | 2025 | Ddps: Discrete diffusion posterior sampling for paths in layered graphs | [Link](https://openreview.net/forum?id=DBdkU0Ikzy) |
| High-citation | 2025 | Decoding Large Language Diffusion Models with Foreseeing Movement | [Link](https://arxiv.org/abs/2512.04135) |
| High-citation | 2025 | Decoding quantum low density parity check codes with diffusion | [Link](https://arxiv.org/abs/2509.22347) |
| High-citation | 2025 | Decoding quantum low density parity check codes with diffusion | [Link](https://arxiv.org/pdf/2509.22347) |
| High-citation | 2025 | Demystifying Diffusion Objectives: Reweighted Losses are Better Variational Bounds | [Link](https://arxiv.org/abs/2511.19664) |
| High-citation | 2025 | Di[M]O: Distilling Masked Diffusion Models into One-step Generator | [Link](https://openaccess.thecvf.com/content/ICCV2025/html/Zhu_DiMO_Distilling_Masked_Diffusion_Models_into_One-step_Generator_ICCV_2025_paper.html) |
| High-citation | 2025 | DiffER: categorical diffusion ensembles for single-step chemical retrosynthesis | [Link](https://link.springer.com/article/10.1186/s13321-025-01056-7) |
| High-citation | 2025 | DiffER: Categorical Diffusion for Chemical Retrosynthesis | [Link](https://neurips.cc/virtual/2024/102830) |
| High-citation | 2025 | Diffged: Computing graph edit distance via diffusion-based graph matching | [Link](https://openreview.net/forum?id=3bofUSPhNF) |
| High-citation | 2025 | DiffGRM: Diffusion-based Generative Recommendation Model | [Link](https://arxiv.org/abs/2510.21805) |
| High-citation | 2025 | DiffMS: Diffusion Generation of Molecules Conditioned on Mass Spectra | [Link](https://proceedings.mlr.press/v267/bohde25a.html) |
| High-citation | 2025 | DiFFPO: Training Diffusion LLMs to Reason Fast and Furious via Reinforcement Learning | [Link](https://arxiv.org/abs/2510.02212) |
| High-citation | 2025 | DiffuCoder: Understanding and Improving Masked Diffusion Models for Code Generation | [Link](https://arxiv.org/abs/2506.20639) |
| High-citation | 2025 | DiffuGR: Generative Document Retrieval with Diffusion Language Models | [Link](https://arxiv.org/abs/2511.08150) |
| High-citation | 2025 | Diffuse Thinking: Exploring Diffusion Language Models as Efficient Thought Proposers for Reasoning | [Link](https://arxiv.org/abs/2510.27469) |
| High-citation | 2025 | Diffusion Beats Autoregressive in Data-Constrained Settings | [Link](https://arxiv.org/abs/2507.15857) |
| High-citation | 2025 | Diffusion Language Models are Super Data Learners | [Link](https://arxiv.org/abs/2511.03276) |
| High-citation | 2025 | Diffusion Language Models Know the Answer Before Decoding | [Link](https://arxiv.org/abs/2508.19982) |
| High-citation | 2025 | Diffusion Models for Molecules: A Survey of Methods and Tasks | [Link](https://arxiv.org/abs/2502.09511) |
| High-citation | 2025 | Diffusion vs Autoregression: An Empirical Study on Code Comment Translation | [Link](https://ieeexplore.ieee.org/abstract/document/11314568?casa_token=PCeruaLi_okAAAAA:QUxVv0F8kr2QwbbpOPN5WnsQob6dLjAbePKnSlH9JecON2bK9pB1UACIbiUF7RVoO2nm9pR0CCyvVmk) |
| High-citation | 2025 | Diffusion-based Large Language Models Survey | [Link](https://www.researchgate.net/profile/Junhao-Song-3/publication/394262235_Diffusion-based_Large_Language_Models_Survey/links/68a33b261bee4d42a24082d6/Diffusion-based-Large-Language-Models-Survey.pdf) |
| High-citation | 2025 | Diffusion-based symbolic music generation with structured state space models | [Link](https://openreview.net/forum?id=Qt5sBi0u7I) |
| High-citation | 2025 | Diffusion-Inspired Masked Language Modeling for Symbolic Harmony Generation on a Fixed Time Grid | [Link](https://www.mdpi.com/2076-3417/15/17/9513) |
| High-citation | 2025 | DiffuSpec: Unlocking Diffusion Language Models for Speculative Decoding | [Link](https://arxiv.org/abs/2510.02358) |
| High-citation | 2025 | DiffuTester: Accelerating Unit Test Generation for Diffusion LLMs via Mining Structural Pattern | [Link](https://arxiv.org/abs/2509.24975) |
| High-citation | 2025 | DINGO: Constrained Inference for Diffusion LLMs | [Link](https://openreview.net/forum?id=KaYMGsnZ4R) |
| High-citation | 2025 | DiRL: An Efficient Post-Training Framework for Diffusion Language Models | [Link](https://arxiv.org/abs/2512.22234) |
| High-citation | 2025 | Discovering Mathematical Equations with Diffusion Language Model | [Link](https://arxiv.org/abs/2509.13136) |
| High-citation | 2025 | Discrete diffusion for generative modeling of text-aligned speech tokens | [Link](https://openreview.net/forum?id=wHsFqmM1rp) |
| High-citation | 2025 | Discrete Diffusion for Reflective Vision-Language-Action Models in Autonomous Driving | [Link](https://arxiv.org/abs/2509.20109) |
| High-citation | 2025 | Discrete Diffusion in Large Language and Multimodal Models: A Survey | [Link](https://arxiv.org/abs/2506.13759) |
| High-citation | 2025 | Discrete Diffusion Models: Novel Analysis and New Sampler Guarantees | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/116858) |
| High-citation | 2025 | Discrete Diffusion Schrödinger Bridge Matching for Graph Transformation | [Link](https://openreview.net/forum?id=tQyh0gnfqW) |
| High-citation | 2025 | Discrete Diffusion VLA: Bringing Discrete Diffusion to Action Decoding in Vision-Language-Action Policies | [Link](https://arxiv.org/abs/2508.20072) |
| High-citation | 2025 | Discrete Flow Matching is a Surprisingly Effective Post-training Method to Address Compound Error in Autoregressive Models | [Link](https://dl.acm.org/doi/full/10.1145/3768292.3770442) |
| High-citation | 2025 | Discrete generative diffusion models without stochastic differential equations: A tensor network approach | [Link](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.111.025302#s3) |
| High-citation | 2025 | Discrete Markov Probabilistic Models: An Improved Discrete Score-Based Framework with sharp convergence bounds under minimal assumptions | [Link](https://openreview.net/forum?id=biJiSMLGOV) |
| High-citation | 2025 | Discrete Neural Flow Samplers with Locally Equivariant Transformer | [Link](https://arxiv.org/abs/2505.17741) |
| High-citation | 2025 | Discrete spatial diffusion: Intensity-preserving diffusion modeling | [Link](https://openreview.net/forum?id=VkqKOc0j9w) |
| High-citation | 2025 | Distillation of Discrete Diffusion through Dimensional Correlations | [Link](https://proceedings.mlr.press/v267/hayakawa25a.html) |
| High-citation | 2025 | dKV-Cache: The Cache for Diffusion Language Models | [Link](https://arxiv.org/abs/2505.15781) |
| High-citation | 2025 | dLLM-Cache: Accelerating Diffusion Large Language Models with Adaptive Caching | [Link](https://arxiv.org/abs/2506.06295) |
| High-citation | 2025 | DLLMQuant: Quantizing Diffusion-based Large Language Models | [Link](https://arxiv.org/abs/2508.14090) |
| High-citation | 2025 | DLM-One: Diffusion Language Models for One-Step Sequence Generation | [Link](https://arxiv.org/abs/2506.00290) |
| High-citation | 2025 | DMark: Order-Agnostic Watermarking for Diffusion Large Language Models | [Link](https://arxiv.org/abs/2510.02902) |
| High-citation | 2025 | dMLLM-TTS: Self-Verified and Efficient Test-Time Scaling for Diffusion Multi-Modal Large Language Models | [Link](https://arxiv.org/abs/2512.19433) |
| High-citation | 2025 | Don't Let It Fade: Preserving Edits in Diffusion Language Models via Token Timestep Allocation | [Link](https://arxiv.org/abs/2510.26200) |
| High-citation | 2025 | dParallel: Learnable Parallel Decoding for dLLMs | [Link](https://arxiv.org/abs/2509.26488) |
| High-citation | 2025 | DPCL-diff: temporal knowledge graph reasoning based on graph node diffusion model with dual-domain periodic contrastive learning | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/33623) |
| High-citation | 2025 | Draft with Diffusion, Verify with Autoregressive Models | [Link](https://czc726.github.io/DEER/static/files/paper.pdf) |
| High-citation | 2025 | Drax: Speech Recognition with Discrete Flow Matching | [Link](https://arxiv.org/abs/2510.04162) |
| High-citation | 2025 | Dream 7B: Diffusion Large Language Models | [Link](https://arxiv.org/abs/2508.15487) |
| High-citation | 2025 | Dream-Coder 7B: An Open Diffusion Language Model for Code | [Link](https://arxiv.org/abs/2509.01142) |
| High-citation | 2025 | Dream-VL & Dream-VLA: Open Vision-Language and Vision-Language-Action Models with Diffusion Language Model Backbone | [Link](https://arxiv.org/abs/2512.22615) |
| High-citation | 2025 | DToM: Decider-Guided Dynamic Token Merging for Accelerating Diffusion MLLMs | [Link](https://arxiv.org/abs/2511.12280) |
| High-citation | 2025 | dVLA: Diffusion Vision-Language-Action Model with Multimodal Chain-of-Thought | [Link](https://arxiv.org/abs/2509.25681) |
| High-citation | 2025 | dVLM-AD: Enhance Diffusion Vision-Language-Model for Driving via Controllable Reasoning | [Link](https://arxiv.org/abs/2512.04459) |
| High-citation | 2025 | Effective and Efficient Masked Image Generation Models | [Link](https://arxiv.org/abs/2503.07197) |
| High-citation | 2025 | Effective and Efficient Masked Image Generation Models | [Link](https://openreview.net/forum?id=pSnBPLYOBZ) |
| High-citation | 2025 | Effective Test-Time Scaling of Discrete Diffusion through Iterative Refinemen | [Link](https://arxiv.org/pdf/2511.05562) |
| High-citation | 2025 | Efficient Inference for Large Reasoning Models: A Survey | [Link](https://arxiv.org/abs/2503.23077) |
| High-citation | 2025 | Efficient perplexity bound and ratio matching in discrete diffusion language models | [Link](https://iclr.cc/virtual/2025/poster/29916) |
| High-citation | 2025 | Efficient-DLM: From Autoregressive to Diffusion Language Models, and Beyond in Speed | [Link](https://arxiv.org/abs/2512.14067) |
| High-citation | 2025 | Emotional Face-to-Speech | [Link](https://openreview.net/forum?id=EuDlvBqcSm) |
| High-citation | 2025 | Empirical Analysis of Decoding Biases in Masked Diffusion Models | [Link](https://arxiv.org/abs/2508.13021) |
| High-citation | 2025 | Enabling Approximate Joint Sampling in Diffusion LMs | [Link](https://arxiv.org/abs/2509.22738) |
| High-citation | 2025 | Encoder-Decoder Diffusion Language Models for Efficient Training and Inference | [Link](https://arxiv.org/abs/2510.22852) |
| High-citation | 2025 | Enhancing Reasoning for Diffusion LLMs via Distribution Matching Policy Optimization | [Link](https://arxiv.org/abs/2510.08233) |
| High-citation | 2025 | Error analysis of discrete flow with generator matching | [Link](https://arxiv.org/abs/2509.21906) |
| High-citation | 2025 | Fail Fast, Win Big: Rethinking the Drafting Strategy in Speculative Decoding via Diffusion LLMs | [Link](https://arxiv.org/abs/2512.20573) |
| High-citation | 2025 | Fast and Fluent Diffusion Language Models via Convolutional Decoding and Rejective Fine-tuning | [Link](https://arxiv.org/abs/2509.15188) |
| High-citation | 2025 | Fast and Fluent Diffusion Language Models via Convolutional Decoding and Rejective Fine-tuning | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/118860) |
| High-citation | 2025 | Fast-dLLM: Training-free Acceleration of Diffusion LLM by Enabling KV Cache and Parallel Decoding | [Link](https://arxiv.org/abs/2505.22618) |
| High-citation | 2025 | Fine-Tuning Discrete Diffusion Models via Reward Optimization with Applications to DNA and Protein Design | [Link](https://openreview.net/forum?id=G328D1xt4W) |
| High-citation | 2025 | Fine-Tuning Discrete Diffusion Models with Policy Gradient Methods | [Link](https://arxiv.org/abs/2502.01384) |
| High-citation | 2025 | Fine-Tuning Masked Diffusion for Provable Self-Correction | [Link](https://arxiv.org/abs/2510.01384) |
| High-citation | 2025 | Finish First, Perfect Later: Test-Time Token-Level Cross-Validation for Diffusion Large Language Models | [Link](https://openreview.net/forum?id=mcBAMstQmM) |
| High-citation | 2025 | Forget BIT, It is All about TOKEN: Towards Semantic Information Theory for LLMs | [Link](https://arxiv.org/abs/2511.01202) |
| High-citation | 2025 | FragFM: Efficient Fragment-Based Molecular Generation via Discrete Flow Matching | [Link](https://openreview.net/forum?id=2GO8WYNt0R) |
| High-citation | 2025 | Free Draft-and-Verification: Toward Lossless Parallel Decoding for Diffusion Large Language Models | [Link](https://arxiv.org/abs/2510.00294) |
| High-citation | 2025 | From Bits to Rounds: Parallel Decoding with Exploration for Diffusion Language Models | [Link](https://arxiv.org/abs/2511.21103) |
| High-citation | 2025 | From Denoising to Refining: A Corrective Framework for Vision-Language Diffusion Model | [Link](https://arxiv.org/abs/2510.19871) |
| High-citation | 2025 | From Next-Token to Next-Block: A Principled Adaptation Path for Diffusion LLMs | [Link](https://arxiv.org/abs/2512.06776) |
| High-citation | 2025 | FUDOKI: Discrete Flow-based Unified Understanding and Generation via Kinetic-Optimal Velocities | [Link](https://arxiv.org/abs/2505.20147) |
| High-citation | 2025 | Generative Deep Learning for de Novo Drug Design─A Chemical Space Odyssey | [Link](https://pubs.acs.org/doi/full/10.1021/acs.jcim.5c00641) |
| High-citation | 2025 | Generative molecule evolution using 3D pharmacophore for efficient Structure-Based Drug Design | [Link](https://arxiv.org/pdf/2507.20130) |
| High-citation | 2025 | Generative or Discriminative? Revisiting Text Classification in the Era of Transformers | [Link](https://aclanthology.org/2025.emnlp-main.486/) |
| High-citation | 2025 | GenMol: A Drug Discovery Generalist with Discrete Diffusion | [Link](https://proceedings.mlr.press/v267/lee25o.html) |
| High-citation | 2025 | Graph diffusion models: A comprehensive survey of methods and applications | [Link](https://www.sciencedirect.com/science/article/pii/S1574013725001303) |
| High-citation | 2025 | How Discrete and Continuous Diffusion Meet: Comprehensive Analysis of Discrete Diffusion Models via a Stochastic Integral Framework | [Link](https://openreview.net/forum?id=6awxwQEI82) |
| High-citation | 2025 | Implicit Search via Discrete Diffusion: A Study on Chess | [Link](https://openreview.net/forum?id=A9y3LFX4ds) |
| High-citation | 2025 | Improving Reasoning for Diffusion Language Models via Group Diffusion Policy Optimization | [Link](https://arxiv.org/abs/2510.08554) |
| High-citation | 2025 | In-Situ Tweedie Discrete Diffusion Models | [Link](https://arxiv.org/abs/2510.01047) |
| High-citation | 2025 | Inpainting-Guided Policy Optimization for Diffusion Large Language Models | [Link](https://arxiv.org/abs/2509.10396) |
| High-citation | 2025 | Insertion Language Models: Sequence Generation with Arbitrary-Position Insertions | [Link](https://arxiv.org/abs/2505.05755) |
| High-citation | 2025 | InstructLayout: Instruction-Driven 2D and 3D Layout Synthesis With Semantic Graph Prior | [Link](https://ieeexplore.ieee.org/abstract/document/11114812) |
| High-citation | 2025 | Integrating electronic structure into generative modeling of inorganic materials | [Link](https://arxiv.org/pdf/2511.14228) |
| High-citation | 2025 | ItDPDM: Information-Theoretic Discrete Poisson Diffusion Model | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/119780) |
| High-citation | 2025 | Jailbreaking Large Language Diffusion Models: Revealing Hidden Safety Flaws in Diffusion-Based Text Generation | [Link](https://arxiv.org/abs/2507.19227) |
| High-citation | 2025 | KLASS: KL-Guided Fast Inference in Masked Diffusion Models | [Link](https://openreview.net/forum?id=gOG9Zoyn4R) |
| High-citation | 2025 | LAD: LoRA-Adapted Diffusion | [Link](https://aclanthology.org/2025.emnlp-demos.8/) |
| High-citation | 2025 | Large Generative Graph Models | [Link](https://openreview.net/forum?id=c01YB8pF0s) |
| High-citation | 2025 | Large Language Diffusion Models | [Link](https://arxiv.org/abs/2502.09992) |
| High-citation | 2025 | Large Scene Generation with Cube-Absorb Discrete Diffusion | [Link](https://openaccess.thecvf.com/content/ICCV2025/html/Hu_Large_Scene_Generation_with_Cube-Absorb_Discrete_Diffusion_ICCV_2025_paper.html) |
| High-citation | 2025 | Lavida-O: Elastic Large Masked Diffusion Models for Unified Multimodal Understanding and Generation | [Link](https://arxiv.org/abs/2509.19244) |
| High-citation | 2025 | LayerDAG: A Layerwise Autoregressive Diffusion Model for Directed Acyclic Graph Generation | [Link](https://openreview.net/forum?id=kam84eEmub) |
| High-citation | 2025 | Learning to Parallel: Accelerating Diffusion Large Language Models via Learnable Parallel Decoding | [Link](https://openreview.net/forum?id=bFJ8Sdr224) |
| High-citation | 2025 | Learning Unmasking Policies for Diffusion Language Models | [Link](https://arxiv.org/abs/2512.09106) |
| High-citation | 2025 | Learning-Order Autoregressive Models with Application to Molecular Graph Generation | [Link](https://arxiv.org/abs/2503.05979) |
| High-citation | 2025 | LLaDA 1.5: Variance-Reduced Preference Optimization for Large Language Diffusion Models | [Link](https://arxiv.org/abs/2505.19223) |
| High-citation | 2025 | LLaDA-MedV: Exploring Large Language Diffusion Models for Biomedical Image Understanding | [Link](https://arxiv.org/abs/2508.01617) |
| High-citation | 2025 | LLaDA-MoE: A Sparse MoE Diffusion Language Model | [Link](https://arxiv.org/abs/2509.24389) |
| High-citation | 2025 | LLaDA-Rec: Discrete Diffusion for Parallel Semantic ID Generation in Generative Recommendation | [Link](https://arxiv.org/abs/2511.06254) |
| High-citation | 2025 | LLaDA-V: Large Language Diffusion Models with Visual Instruction Tuning | [Link](https://arxiv.org/abs/2505.16933) |
| High-citation | 2025 | LLaDA-VLA: Vision Language Diffusion Action Models | [Link](https://arxiv.org/abs/2509.06932) |
| High-citation | 2025 | LongLLaDA: Unlocking Long Context Capabilities in Diffusion LLMs | [Link](https://arxiv.org/abs/2506.14429) |
| High-citation | 2025 | Lookahead Unmasking Elicits Accurate Decoding in Diffusion Language Models | [Link](https://arxiv.org/abs/2511.05563) |
| High-citation | 2025 | Lumina-DiMOO: An Omni Diffusion Large Language Model for Multi-Modal Generation and Understanding | [Link](https://arxiv.org/abs/2510.06308) |
| High-citation | 2025 | Mask-prior-guided denoising diffusion improves inverse protein folding | [Link](https://www.nature.com/articles/s42256-025-01042-6) |
| High-citation | 2025 | Masked Diffusion Captioning for Visual Feature Learning | [Link](https://aclanthology.org/2025.findings-emnlp.1376/) |
| High-citation | 2025 | Masked Diffusion Models as Energy Minimization | [Link](https://arxiv.org/abs/2509.13866) |
| High-citation | 2025 | MDiff4STR: Mask Diffusion Model for Scene Text Recognition | [Link](https://arxiv.org/abs/2512.01422) |
| High-citation | 2025 | MDPO: Overcoming the Training-Inference Divide of Masked Diffusion Language Models | [Link](https://arxiv.org/abs/2508.13148) |
| High-citation | 2025 | MEGA: Masked Generative Autoencoder for Human Mesh Recovery | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Fiche_MEGA_Masked_Generative_Autoencoder_for_Human_Mesh_Recovery_CVPR_2025_paper.html) |
| High-citation | 2025 | Mercury: Ultra-Fast Language Models Based on Diffusion | [Link](https://ui.adsabs.harvard.edu/abs/2025arXiv250617298L/abstract) |
| High-citation | 2025 | MLLM-based Speech Recognition: When and How is Multimodality Beneficial? | [Link](https://arxiv.org/abs/2507.19037) |
| High-citation | 2025 | MMaDA-Parallel: Multimodal Large Diffusion Language Models for Thinking-Aware Editing and Generation | [Link](https://arxiv.org/abs/2511.09611) |
| High-citation | 2025 | MMaDA: Multimodal Large Diffusion Language Models | [Link](https://arxiv.org/abs/2505.15809) |
| High-citation | 2025 | MMaDA: Multimodal Large Diffusion Language Models | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/115311) |
| High-citation | 2025 | Muddit: Liberating Generation Beyond Text-to-Image with a Unified Discrete Diffusion Model | [Link](https://arxiv.org/abs/2505.23606) |
| High-citation | 2025 | Multiverse: Your Language Models Secretly Decide How to Parallelize and Merge Generation | [Link](https://arxiv.org/abs/2506.09991) |
| High-citation | 2025 | Neural approaches to SAT solving: Design choices and interpretability | [Link](https://www.sciencedirect.com/science/article/pii/S0888613X25002506) |
| High-citation | 2025 | Next Semantic Scale Prediction via Hierarchical Diffusion Language Models | [Link](https://arxiv.org/abs/2510.08632) |
| High-citation | 2025 | Nona: A unifying multimodal masking framework for functional genomics | [Link](https://www.biorxiv.org/content/10.1101/2025.11.06.687036v2.abstract) |
| High-citation | 2025 | Open Problems and a Hypothetical Path Forward in LLM Knowledge Paradigms | [Link](https://arxiv.org/abs/2504.06823) |
| High-citation | 2025 | Optimizing Decoding Paths in Masked Diffusion Models by Quantifying Uncertainty | [Link](https://arxiv.org/abs/2512.21336) |
| High-citation | 2025 | Orchestrating Dual-Boundaries: An Arithmetic Intensity Inspired Acceleration Framework for Diffusion Language Models | [Link](https://arxiv.org/abs/2511.21759) |
| High-citation | 2025 | Parallel Sampling from Masked Diffusion Models via Conditional Independence Testing | [Link](https://arxiv.org/abs/2510.21961) |
| High-citation | 2025 | Parallel Thinking, Sequential Answering: Bridging NAR and AR for Efficient Reasoning | [Link](https://arxiv.org/abs/2509.20744) |
| High-citation | 2025 | PartDiffuser: Part-wise 3D Mesh Generation via Discrete Diffusion | [Link](https://arxiv.org/abs/2511.18801) |
| High-citation | 2025 | Partition Generative Modeling: Masked Modeling Without Masks | [Link](https://icml.cc/virtual/2025/51231) |
| High-citation | 2025 | Path Planning for Masked Diffusion Models with Applications to Biological Sequence Generation | [Link](https://openreview.net/forum?id=VOW9YCgmMA) |
| High-citation | 2025 | Periodic Materials Generation using Text-Guided Joint Diffusion Model | [Link](https://openreview.net/forum?id=AkBrb7yQ0G) |
| High-citation | 2025 | Physics-inspired Generative AI models via real hardware-based noisy quantum diffusion | [Link](https://inspirehep.net/literature/2926297) |
| High-citation | 2025 | Plan for Speed: Dilated Scheduling for Masked Diffusion Language Models | [Link](https://arxiv.org/abs/2506.19037) |
| High-citation | 2025 | Planner and Executor: Collaboration between Discrete Diffusion And Autoregressive Models in Reasoning | [Link](https://arxiv.org/abs/2510.15244) |
| High-citation | 2025 | Plug-and-Play Context Feature Reuse for Efficient Masked Generation | [Link](https://arxiv.org/abs/2505.19089) |
| High-citation | 2025 | Preference-Based Alignment of Discrete Diffusion Models | [Link](https://arxiv.org/abs/2503.08295) |
| High-citation | 2025 | Principled and Tractable RL for Reasoning with Diffusion Language Models | [Link](https://arxiv.org/pdf/2510.04019) |
| High-citation | 2025 | Q-Fusion: Diffusing Quantum Circuits | [Link](https://ieeexplore.ieee.org/abstract/document/11130315) |
| High-citation | 2025 | Quant-dLLM: Post-Training Extreme Low-Bit Quantization for Diffusion Large Language Models | [Link](https://arxiv.org/abs/2510.03274) |
| High-citation | 2025 | Quantization Meets dLLMs: A Systematic Study of Post-training Quantization for Diffusion LLMs | [Link](https://arxiv.org/abs/2508.14896) |
| High-citation | 2025 | Rainbow Padding: Mitigating Early Termination in Instruction-Tuned Diffusion LLMs | [Link](https://arxiv.org/abs/2510.03680) |
| High-citation | 2025 | Reasoning in Diffusion Large Language Models is Concentrated in Dynamic Confusion Zones | [Link](https://arxiv.org/abs/2511.15208) |
| High-citation | 2025 | Redi: Rectified discrete flow | [Link](https://openreview.net/forum?id=49QC2D8exO) |
| High-citation | 2025 | ReDiSC: A Reparameterized Masked Diffusion Model for Scalable Node Classification with Structured Predictions | [Link](https://arxiv.org/abs/2507.14484) |
| High-citation | 2025 | Reinforcement Learning with Discrete Diffusion Policies for Combinatorial Action Spaces | [Link](https://arxiv.org/abs/2509.22963) |
| High-citation | 2025 | Reinforcing the Diffusion Chain of Lateral Thought with Diffusion Language Models | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/117288) |
| High-citation | 2025 | Remasking Discrete Diffusion Models with Inference-Time Scaling | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/118818) |
| High-citation | 2025 | Residual Vector Quantized Diffusion Model-Based Joint Source-Channel Coding for Task-Oriented Agent Communication | [Link](https://ieeexplore.ieee.org/abstract/document/10907795) |
| High-citation | 2025 | Reviving Any-Subset Autoregressive Models with Principled Parallel Sampling and Speculative Decoding | [Link](https://arxiv.org/abs/2504.20456) |
| High-citation | 2025 | Revolutionizing Reinforcement Learning Framework for Diffusion Large Language Models | [Link](https://arxiv.org/abs/2509.06949) |
| High-citation | 2025 | RFG: Test-Time Scaling for Diffusion Large Language Model Reasoning with Reward-Free Guidance | [Link](https://arxiv.org/abs/2509.25604) |
| High-citation | 2025 | Roll the dice & look before you leap: Going beyond the creative limits of next-token prediction | [Link](https://proceedings.mlr.press/v267/nagarajan25a.html) |
| High-citation | 2025 | Saber: An Efficient Sampling with Adaptive Acceleration and Backtracking Enhanced Remasking for Diffusion Language Model | [Link](https://arxiv.org/abs/2510.18165) |
| High-citation | 2025 | Sampling Binary Data by Denoising through Score Functions | [Link](https://icml.cc/virtual/2025/poster/46496) |
| High-citation | 2025 | Scale-wise var is secretly discrete diffusion | [Link](https://arxiv.org/abs/2509.22636) |
| High-citation | 2025 | Scaling Diffusion Language Models via Adaptation from Autoregressive Models | [Link](https://openreview.net/forum?id=j1tSLYKwg8) |
| High-citation | 2025 | SDAR-VL: Stable and Efficient Block-wise Diffusion for Vision-Language Understanding | [Link](https://arxiv.org/abs/2512.14068) |
| High-citation | 2025 | SDAR: A Synergistic Diffusion-AutoRegression Paradigm for Scalable Sequence Generation | [Link](https://arxiv.org/abs/2510.06303) |
| High-citation | 2025 | Self Speculative Decoding for Diffusion Large Language Models | [Link](https://arxiv.org/abs/2510.04147) |
| High-citation | 2025 | Self-Speculative Decoding in Any-Order and Any-Subset Autoregressive Models | [Link](https://openreview.net/forum?id=F1AUXqDLuh) |
| High-citation | 2025 | Self-Speculative Masked Diffusions | [Link](https://arxiv.org/abs/2510.03929) |
| High-citation | 2025 | ShortListing Model: A Streamlined SimplexDiffusion for Discrete Variable Generation | [Link](https://openreview.net/forum?id=eZh2UyeMrg) |
| High-citation | 2025 | Show-o: One Single Transformer to Unify Multimodal Understanding and Generation | [Link](https://openreview.net/forum?id=o6Ynz6OIQ6) |
| High-citation | 2025 | Sifting through the noise: A survey of diffusion probabilistic models and their applications to biomolecules | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0022283624004406) |
| High-citation | 2025 | Simple and critical iterative denoising: A recasting of discrete diffusion in graph generation | [Link](https://openreview.net/forum?id=kPTW6hGrJy) |
| High-citation | 2025 | Simple Denoising Diffusion Language Models | [Link](https://arxiv.org/abs/2510.22926) |
| High-citation | 2025 | Simple Guidance Mechanisms for Discrete Diffusion Models | [Link](https://openreview.net/forum?id=i5MrJ6g5G1) |
| High-citation | 2025 | SketchDNN: Joint Continuous-Discrete Diffusion for CAD Sketch Generation | [Link](https://openreview.net/forum?id=CxnKXLDCZM) |
| High-citation | 2025 | Sparse-LaViDa: Sparse Multimodal Discrete Diffusion Language Models | [Link](https://arxiv.org/abs/2512.14008) |
| High-citation | 2025 | SPG: Sandwiched Policy Gradient for Masked Diffusion Language Models | [Link](https://arxiv.org/abs/2510.09541) |
| High-citation | 2025 | Spiffy: Multiplying Diffusion LLM Acceleration via Lossless Speculative Decoding | [Link](https://arxiv.org/abs/2509.18085) |
| High-citation | 2025 | Spiking-Diffusion: Vector Quantized Discrete Diffusion Model with Spiking Neural Networks | [Link](https://ieeexplore.ieee.org/abstract/document/10933745) |
| High-citation | 2025 | STEAD: Robust Provably Secure Linguistic Steganography with Diffusion Language Model | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/117948) |
| High-citation | 2025 | Structure Language Models for Protein Conformation Generation | [Link](https://openreview.net/forum?id=OzUNDnpQyd) |
| High-citation | 2025 | Symbol Grounding in Neuro-Symbolic AI: A Gentle Introduction to Reasoning Shortcuts | [Link](https://arxiv.org/abs/2510.14538) |
| High-citation | 2025 | Syntax-Guided Diffusion Language Models with User-Integrated Personalization | [Link](https://arxiv.org/abs/2510.01028) |
| High-citation | 2025 | TabDiff: a Mixed-type Diffusion Model for Tabular Data Generation | [Link](https://openreview.net/forum?id=swvURjrt8z) |
| High-citation | 2025 | Taming Masked Diffusion Language Models via Consistency Trajectory Reinforcement Learning with Fewer Decoding Step | [Link](https://arxiv.org/abs/2509.23924) |
| High-citation | 2025 | Target Concrete Score Matching: A Holistic Framework for Discrete Diffusion | [Link](https://arxiv.org/abs/2504.16431) |
| High-citation | 2025 | Test-Time Anchoring for Discrete Diffusion Posterior Sampling | [Link](https://arxiv.org/abs/2510.02291) |
| High-citation | 2025 | Test-Time Scaling in Diffusion LLMs via Hidden Semi-Autoregressive Experts | [Link](https://arxiv.org/abs/2510.05040) |
| High-citation | 2025 | Test-Time Scaling in Diffusion LLMs via Hidden Semi-Autoregressive Experts | [Link](https://openreview.net/forum?id=L5y7in91vd) |
| High-citation | 2025 | TFG-Flow: Training-free Guidance in Multimodal Generative Flow | [Link](https://arxiv.org/abs/2501.14216) |
| High-citation | 2025 | The Cosine Schedule is Fisher-Rao-Optimal for Masked Discrete Diffusion Models | [Link](https://arxiv.org/abs/2508.04884) |
| High-citation | 2025 | The Devil behind the mask: An emergent safety vulnerability of Diffusion LLMs | [Link](https://arxiv.org/abs/2507.11097) |
| High-citation | 2025 | The Diffusion Duality | [Link](https://proceedings.mlr.press/v267/sahoo25a.html) |
| High-citation | 2025 | The Serial Scaling Hypothesis | [Link](https://arxiv.org/abs/2507.12549) |
| High-citation | 2025 | Theoretical Benefit and Limitation of Diffusion Language Model | [Link](https://arxiv.org/abs/2502.09622) |
| High-citation | 2025 | Think while You Generate: Discrete Diffusion with Planned Denoising | [Link](https://openreview.net/forum?id=MJNywBdSDy) |
| High-citation | 2025 | Thinking Inside the Mask: In-Place Prompting in Diffusion LLMs | [Link](https://arxiv.org/abs/2508.10736) |
| High-citation | 2025 | TiDAR: Think in Diffusion, Talk in Autoregression | [Link](https://arxiv.org/abs/2511.08923) |
| High-citation | 2025 | Time Is a Feature: Exploiting Temporal Dynamics in Diffusion Language Models | [Link](https://arxiv.org/abs/2508.09138) |
| High-citation | 2025 | TR2-D2: Tree Search Guided Trajectory-Aware Fine-Tuning for Discrete Diffusion | [Link](https://arxiv.org/abs/2509.25171) |
| High-citation | 2025 | Train for the Worst, Plan for the Best: Understanding Token Ordering in Masked Diffusions | [Link](https://arxiv.org/abs/2502.06768) |
| High-citation | 2025 | Training-Free Guidance Beyond Differentiability: Scalable Path Steering with Tree Search in Diffusion and Flow Models | [Link](https://arxiv.org/abs/2502.11420) |
| High-citation | 2025 | Ultra-fast language generation via discrete diffusion divergence instruct | [Link](https://openreview.net/forum?id=mtdyZsa47V) |
| High-citation | 2025 | UltraLLaDA: Scaling the Context Length to 128K for Diffusion Large Language Models | [Link](https://arxiv.org/abs/2510.10481) |
| High-citation | 2025 | Uncertainty-Masked Bernoulli Diffusion for Camouflaged Object Detection Refinement | [Link](https://arxiv.org/abs/2506.10712) |
| High-citation | 2025 | Unified Diffusion VLA: Vision-Language-Action Model via Joint Discrete Denoising Diffusion Process | [Link](https://arxiv.org/abs/2511.01718) |
| High-citation | 2025 | Unified Discrete Diffusion for Categorical Data | [Link](https://www.jmlr.org/papers/v26/25-0171.html) |
| High-citation | 2025 | Unified Multimodal Discrete Diffusion | [Link](https://arxiv.org/abs/2503.20853) |
| High-citation | 2025 | Unifying Autoregressive and Diffusion-Based Sequence Generation | [Link](https://openreview.net/forum?id=rgq9BFXSFl#discussion) |
| High-citation | 2025 | Unmasking Trees for Tabular Data | [Link](https://openreview.net/forum?id=0AxbTF3Ouq) |
| High-citation | 2025 | Unveiling the Potential of Diffusion Large Language Model in Controllable Generation | [Link](https://arxiv.org/abs/2507.04504) |
| High-citation | 2025 | Variational Masked Diffusion Models | [Link](https://arxiv.org/abs/2510.23606) |
| High-citation | 2025 | Vector Quantized Diffusion Model Based Speech Bandwidth Extension | [Link](https://ieeexplore.ieee.org/abstract/document/10889180) |
| High-citation | 2025 | ViLaD: A Large Vision Language Diffusion Framework for End-to-End Autonomous Driving | [Link](https://arxiv.org/abs/2508.12603) |
| High-citation | 2025 | WAM-Diff: A Masked Diffusion VLA Framework with MoE and Online Reinforcement Learning for Autonomous Driving | [Link](https://arxiv.org/abs/2512.11872) |
| High-citation | 2025 | WAM-Flow: Parallel Coarse-to-Fine Motion Planning via Discrete Flow Matching for Autonomous Driving | [Link](https://arxiv.org/abs/2512.06112) |
| High-citation | 2025 | wd1: Weighted Policy Optimization for Reasoning in Diffusion Language Models | [Link](https://arxiv.org/abs/2507.08838) |
| High-citation | 2025 | WeDLM: Reconciling Diffusion Language Models with Standard Causal Attention for Fast Inference | [Link](https://arxiv.org/abs/2512.22737) |
| High-citation | 2025 | What Exactly Does Guidance Do in Masked Discrete Diffusion Models | [Link](https://arxiv.org/abs/2506.10971) |
| High-citation | 2025 | Why mask diffusion does not work | [Link](https://arxiv.org/abs/2510.03289) |
| High-citation | 2025 | Why Masking Diffusion Works: Condition on the Jump Schedule for Improved Discrete Diffusion | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/115376) |
| High-citation | 2025 | Wide-In, Narrow-Out: Revokable Decoding for Efficient and Effective DLLMs | [Link](https://arxiv.org/abs/2507.18578) |
| High-citation | 2025 | WyckoffDiff – A Generative Diffusion Model for Crystal Symmetry | [Link](https://proceedings.mlr.press/v267/ekstrom-kelvinius25a.html) |
| High-citation | 2026 | -: Training-free Bidirectional Variable-Length Control for Masked Diffusion LLMs | [Link](https://arxiv.org/abs/2601.22527) |
| High-citation | 2026 | A Diffusion Model to Shrink Proteins While Maintaining their Function | [Link](https://openreview.net/forum?id=quxeCxJwKm) |
| High-citation | 2026 | Accelerating Diffusion Language Models Inference via Local Determinism Propagation | [Link](https://openreview.net/forum?id=XURWY9K3ZS) |
| High-citation | 2026 | All-atom protein sequence design using discrete diffusion models | [Link](https://link.springer.com/article/10.1186/s13321-025-01121-1) |
| High-citation | 2026 | BackPlay: Plug-in Look-Back Self-Correction for Diffusion Language Models | [Link](https://arxiv.org/abs/2601.06428) |
| High-citation | 2026 | Balancing Understanding and Generation in Discrete Diffusion Models | [Link](https://arxiv.org/abs/2602.01362) |
| High-citation | 2026 | Beyond GEMM-Centric NPUs: Enabling Efficient Diffusion LLM Sampling | [Link](https://arxiv.org/abs/2601.20706) |
| High-citation | 2026 | Beyond Next-Token Prediction: Diffusion vs. Autoregressive Reasoning in LLMs | [Link](https://openreview.net/forum?id=qVeNtSNeo5) |
| High-citation | 2026 | Causal Autoregressive Diffusion Language Model | [Link](https://arxiv.org/abs/2601.22031) |
| High-citation | 2026 | CD4LM: Consistency Distillation and aDaptive Decoding for Diffusion Language Models | [Link](https://arxiv.org/abs/2601.02236) |
| High-citation | 2026 | Context Tokens are Anchors: Understanding the Repetition Curse in dMLLMs from an Information Flow Perspective | [Link](https://arxiv.org/abs/2601.20520) |
| High-citation | 2026 | DART: Diffusion-Inspired Speculative Decoding for Fast LLM Inference | [Link](https://arxiv.org/abs/2601.19278) |
| High-citation | 2026 | Diffusion Language Model Inference with Monte Carlo Tree Search | [Link](https://openreview.net/forum?id=C7t0WRrxY4) |
| High-citation | 2026 | Diffusion LMs Can Approximate Optimal Infilling Lengths Implicitly | [Link](https://arxiv.org/abs/2602.00476) |
| High-citation | 2026 | DiMo: Discrete Diffusion Modeling for Motion Generation and Understanding | [Link](https://arxiv.org/abs/2602.04188) |
| High-citation | 2026 | Discrete diffusion trajectory alignment via stepwise decomposition | [Link](https://openreview.net/forum?id=h9b5h69v3p) |
| High-citation | 2026 | dLLM-ASR: A Faster Diffusion LLM-based Framework for Speech Recognition | [Link](https://arxiv.org/abs/2601.17902) |
| High-citation | 2026 | Efficient Diffusion Language Models: A Comprehensive Survey | [Link](https://www.authorea.com/doi/full/10.22541/au.176918713.36402137) |
| High-citation | 2026 | EntRGi: Entropy Aware Reward Guidance for Diffusion Language Models | [Link](https://arxiv.org/abs/2602.05000) |
| High-citation | 2026 | FOCUS: DLLMs Know How to Tame Their Compute Bound | [Link](https://arxiv.org/abs/2601.23278) |
| High-citation | 2026 | FourierSampler: Unlocking Non-Autoregressive Potential in Diffusion Language Models via Frequency-Guided Generation | [Link](https://arxiv.org/abs/2601.23182) |
| High-citation | 2026 | From Vulnerability to Defense: Understanding and Mitigating MASK-Based Attacks in dLLMs | [Link](https://openreview.net/forum?id=jKQQb8uClw) |
| High-citation | 2026 | FS-DFM: Fast and Accurate Long Text Generation with Few-Step Diffusion Language Models | [Link](https://openreview.net/forum?id=ue1zFeD275) |
| High-citation | 2026 | Generating Directed Graphs with Dual Attention and Asymmetric Encoding | [Link](https://neurips.cc/virtual/2025/loc/san-diego/127670) |
| High-citation | 2026 | Generation Order and Parallel Decoding in Masked Diffusion Models: An Information-Theoretic Perspective | [Link](https://arxiv.org/abs/2602.00286) |
| High-citation | 2026 | Hybrid Diffusion for Simultaneous Symbolic and Continuous Planning | [Link](https://ieeexplore.ieee.org/abstract/document/11395608) |
| High-citation | 2026 | Lookahead-then-Verify: Reliable Constrained Decoding for Diffusion LLMs under Context-Free Grammars | [Link](https://arxiv.org/abs/2602.00612) |
| High-citation | 2026 | LR-DWM: Efficient Watermarking for Diffusion Language Models | [Link](https://arxiv.org/abs/2601.12376) |
| High-citation | 2026 | MaDiS: Taming Masked Diffusion Language Models for Sign Language Generation | [Link](https://arxiv.org/abs/2601.19577) |
| High-citation | 2026 | ON POWERFUL WAYS TO GENERATE: AUTOREGRESSION, DIFFUSION, AND BEYOND | [Link](https://openreview.net/forum?id=PKidr9Ruli) |
| High-citation | 2026 | One Token Is Enough: Improving Diffusion Language Models with a Sink Token | [Link](https://arxiv.org/abs/2601.19657) |
| High-citation | 2026 | Overcoming Dimensional Factorization Limits in Discrete Diffusion Models through Quantum Joint Distribution Learning | [Link](https://www.nature.com/articles/s41534-026-01188-0) |
| High-citation | 2026 | Parallelism and Generation Order in Masked Diffusion Language Models: Limits Today, Potential Tomorrow | [Link](https://arxiv.org/abs/2601.15593) |
| High-citation | 2026 | Prism: Efficient Test-Time Scaling via Hierarchical Search and Self-Verification for Discrete Diffusion Language Models | [Link](https://arxiv.org/abs/2602.01842) |
| High-citation | 2026 | Reversible Diffusion Decoding for Diffusion Language Models | [Link](https://arxiv.org/abs/2602.00150) |
| High-citation | 2026 | ScDiVa: Masked Discrete Diffusion for Joint Modeling of Single-Cell Identity and Expression | [Link](https://arxiv.org/abs/2602.03477) |
| High-citation | 2026 | Self-Rewarding Sequential Monte Carlo for Masked Diffusion Language Models | [Link](https://arxiv.org/abs/2602.01849) |
| High-citation | 2026 | Sentence Curve Language Models | [Link](https://arxiv.org/abs/2602.01807) |
| High-citation | 2026 | SPA-Cache: Singular Proxies for Adaptive Caching in Diffusion Language Models | [Link](https://arxiv.org/abs/2602.02544) |
| High-citation | 2026 | Step-Wise Refusal Dynamics in Autoregressive and Diffusion Language Models | [Link](https://arxiv.org/abs/2602.02600) |
| High-citation | 2026 | Streaming-dLLM: Accelerating Diffusion LLMs via Suffix Pruning and Dynamic Decoding | [Link](https://arxiv.org/abs/2601.17917) |
| High-citation | 2026 | Swordsman: Entropy-Driven Adaptive Block Partition for Efficient Diffusion Language Models | [Link](https://arxiv.org/abs/2602.04399) |
| High-citation | 2026 | Test-time anchoring for discrete diffusion posterior sampling | [Link](https://openreview.net/forum?id=mO5sCWc3WX) |
| High-citation | 2026 | The Flexibility Trap: Rethinking the Value of Arbitrary Order in Diffusion Language Models | [Link](https://nzl-thu.github.io/the-flexibility-trap/static/paper.pdf) |
| High-citation | 2026 | The Flexibility Trap: Why Arbitrary Order Limits Reasoning Potential in Diffusion Language Models | [Link](https://arxiv.org/abs/2601.15165) |
| High-citation | 2026 | Thinking Out of Order: When Output Order Stops Reflecting Reasoning Order in Diffusion Language Models | [Link](https://arxiv.org/abs/2601.22035) |
| High-citation | 2026 | Top 10 Open Challenges Steering the Future of Diffusion Language Model and Its Variants | [Link](https://arxiv.org/abs/2601.14041) |
| High-citation | 2026 | Training-Free Self-Correction for Multimodal Masked Diffusion Models | [Link](https://arxiv.org/abs/2602.02927) |
| High-citation | 2026 | Training-Trajectory-Aware Token Selection | [Link](https://arxiv.org/abs/2601.10348) |
| High-citation | 2026 | Tuning the Implicit Regularizer of Masked Diffusion Language Models: Enhancing Generalization via Insights from -Parity | [Link](https://arxiv.org/abs/2601.22450) |
| High-citation | 2026 | Unifying Masked Diffusion Models with Various Generation Orders and Beyond | [Link](https://arxiv.org/abs/2602.02112) |
| High-citation | 2026 | VidLaDA: Bidirectional Diffusion Large Language Models for Efficient Video Understanding | [Link](https://arxiv.org/abs/2601.17868) |
| High-citation | 2026 | Where to Start Alignment? Diffusion Large Language Model May Demand a Distinct Position | [Link](https://arxiv.org/abs/2508.12398) |
| ICLR | 2022 | Autoregressive Diffusion Models | [Link](https://openreview.net/pdf?id=Lm8T39vLDTE) |
| ICLR | 2023 | Analog Bits: Generating Discrete Data using Diffusion Models with Self-Conditioning | [Link](https://iclr.cc/virtual/2023/poster/11907) |
| ICLR | 2023 | DiGress: Discrete Denoising diffusion for graph generation | [Link](https://iclr.cc/virtual/2023/poster/11556) |
| ICLR | 2023 | Discrete Contrastive Diffusion for Cross-Modal Music and Image Generation | [Link](https://iclr.cc/virtual/2023/poster/11915) |
| ICLR | 2023 | Discrete Predictor-Corrector Diffusion Models for Image Synthesis | [Link](https://iclr.cc/virtual/2023/poster/10854) |
| ICLR | 2023 | Score-based Continuous-time Discrete Diffusion Models | [Link](https://iclr.cc/virtual/2023/poster/10977) |
| ICLR | 2023 | Unified Discrete Diffusion for Simultaneous Vision-Language Generation | [Link](https://iclr.cc/virtual/2023/poster/11819) |
| ICLR | 2024 | Copilot4D: Learning Unsupervised World Models for Autonomous Driving via Discrete Diffusion | [Link](https://iclr.cc/virtual/2024/poster/18691) |
| ICLR | 2024 | Masked Completion via Structured Diffusion with White-Box Transformers | [Link](https://iclr.cc/virtual/2024/poster/18688) |
| ICLR | 2024 | VDT: General-purpose Video Diffusion Transformers via Mask Modeling | [Link](https://iclr.cc/virtual/2024/poster/18520) |
| ICLR | 2025 | Accelerating Diffusion Transformers with Token-wise Feature Caching | [Link](https://iclr.cc/virtual/2025/poster/27718) |
| ICLR | 2025 | Beyond Autoregression: Discrete Diffusion for Complex Reasoning and Planning | [Link](https://iclr.cc/virtual/2025/poster/29876) |
| ICLR | 2025 | Block Diffusion: Interpolating Between Autoregressive and Diffusion Language Models | [Link](https://iclr.cc/virtual/2025/poster/28004) |
| ICLR | 2025 | Convergence of Score-Based Discrete Diffusion Models: A Discrete-Time Analysis | [Link](https://iclr.cc/virtual/2025/poster/28280) |
| ICLR | 2025 | Discrete Copula Diffusion | [Link](https://iclr.cc/virtual/2025/poster/30336) |
| ICLR | 2025 | DPLM-2: A Multimodal Diffusion Protein Language Model | [Link](https://iclr.cc/virtual/2025/poster/30917) |
| ICLR | 2025 | Efficient Diversity-Preserving Diffusion Alignment via Gradient-Informed GFlowNets | [Link](https://iclr.cc/virtual/2025/poster/30600) |
| ICLR | 2025 | Energy-Based Diffusion Language Models for Text Generation | [Link](https://iclr.cc/virtual/2025/poster/28133) |
| ICLR | 2025 | Fine-Tuning Discrete Diffusion Models via Reward Optimization with Applications to DNA and Protein Design | [Link](https://iclr.cc/virtual/2025/poster/30308) |
| ICLR | 2025 | Glauber Generative Model: Discrete Diffusion Models via Binary Classification | [Link](https://iclr.cc/virtual/2025/poster/30199) |
| ICLR | 2025 | How Discrete and Continuous Diffusion Meet: Comprehensive Analysis of Discrete Diffusion Models via a Stochastic Integral Framework | [Link](https://iclr.cc/virtual/2025/poster/30876) |
| ICLR | 2025 | Implicit Search via Discrete Diffusion: A Study on Chess | [Link](https://iclr.cc/virtual/2025/poster/30648) |
| ICLR | 2025 | LayerDAG: A Layerwise Autoregressive Diffusion Model for Directed Acyclic Graph Generation | [Link](https://iclr.cc/virtual/2025/poster/31518) |
| ICLR | 2025 | Learning to Discretize Denoising Diffusion ODEs | [Link](https://iclr.cc/virtual/2025/poster/27797) |
| ICLR | 2025 | Masked Diffusion Models are Secretly Time-Agnostic Masked Models and Exploit Inaccurate Categorical Sampling | [Link](https://iclr.cc/virtual/2025/poster/30511) |
| ICLR | 2025 | MDSGen: Fast and Efficient Masked Diffusion Temporal-Aware Transformers for Open-Domain Sound Generation | [Link](https://iclr.cc/virtual/2025/poster/27741) |
| ICLR | 2025 | On the Inherent Privacy Properties of Discrete Denoising Diffusion Models | [Link](https://iclr.cc/virtual/2025/poster/31493) |
| ICLR | 2025 | Scalable Discrete Diffusion Samplers: Combinatorial Optimization and Statistical Physics | [Link](https://iclr.cc/virtual/2025/poster/28285) |
| ICLR | 2025 | Scaling Diffusion Language Models via Adaptation from Autoregressive Models | [Link](https://iclr.cc/virtual/2025/poster/28659) |
| ICLR | 2025 | Scaling up Masked Diffusion Models on Text | [Link](https://iclr.cc/virtual/2025/poster/29366) |
| ICLR | 2025 | Steering Masked Discrete Diffusion Models via Discrete Denoising Posterior Prediction | [Link](https://iclr.cc/virtual/2025/poster/29801) |
| ICLR | 2025 | SymmetricDiffusers: Learning Discrete Diffusion on Finite Symmetric Groups | [Link](https://iclr.cc/virtual/2025/poster/30408) |
| ICLR | 2025 | Unlocking Guidance for Discrete State-Space Diffusion and Flow Models | [Link](https://iclr.cc/virtual/2025/poster/29286) |
| ICLR | 2025 | Your Absorbing Discrete Diffusion Secretly Models the Conditional Distributions of Clean Data | [Link](https://iclr.cc/virtual/2025/poster/28131) |
| ICLR | 2026 | A Unification of Discrete, Gaussian, and Simplicial Diffusion | [Link](https://iclr.cc/virtual/2026/poster/10011795) |
| ICLR | 2026 | A2D: Any-Order, Any-Step Safety Alignment for Diffusion Language Models | [Link](https://iclr.cc/virtual/2026/poster/10009223) |
| ICLR | 2026 | Accelerating Diffusion Large Language Models with SlowFast Sampling: The Three Golden Principles | [Link](https://iclr.cc/virtual/2026/poster/10009203) |
| ICLR | 2026 | Aligning Visual Foundation Encoders to Tokenizers for Diffusion Models | [Link](https://iclr.cc/virtual/2026/poster/10008675) |
| ICLR | 2026 | Any-Order Flexible Length Masked Diffusion | [Link](https://iclr.cc/virtual/2026/poster/10006942) |
| ICLR | 2026 | Attention Is All You Need for KV Cache in Diffusion LLMs | [Link](https://iclr.cc/virtual/2026/poster/10006427) |
| ICLR | 2026 | Beyond Fixed: Training-Free Variable-Length Denoising for Diffusion Large Language Models | [Link](https://iclr.cc/virtual/2026/poster/10010283) |
| ICLR | 2026 | Beyond Masks: Efficient, Flexible Diffusion Language Models via Deletion-Insertion Processes | [Link](https://iclr.cc/virtual/2026/poster/10009122) |
| ICLR | 2026 | Beyond Text-to-Image: Liberating Generation with a Unified Discrete Diffusion Model | [Link](https://iclr.cc/virtual/2026/poster/10007345) |
| ICLR | 2026 | CheckMate! Watermarking Graph Diffusion Models in Polynomial Time | [Link](https://iclr.cc/virtual/2026/poster/10011153) |
| ICLR | 2026 | CineTrans: Learning to Generate Videos with Cinematic Transitions via Masked Diffusion Models | [Link](https://iclr.cc/virtual/2026/poster/10011151) |
| ICLR | 2026 | Consolidating Reinforcement Learning for Multimodal Discrete Diffusion Models | [Link](https://iclr.cc/virtual/2026/poster/10011081) |
| ICLR | 2026 | Constrained Decoding of Diffusion LLMs with Context-Free Grammars | [Link](https://iclr.cc/virtual/2026/poster/10011297) |
| ICLR | 2026 | Context Tokens are Anchors: Understanding the Repetition Curse in Diffusion MLLMs from an Information Flow Perspective | [Link](https://iclr.cc/virtual/2026/poster/10007580) |
| ICLR | 2026 | Continuously Augmented Discrete Diffusion model for Categorical Generative Modeling | [Link](https://iclr.cc/virtual/2026/poster/10010203) |
| ICLR | 2026 | D-AR: Diffusion via Autoregressive Models | [Link](https://iclr.cc/virtual/2026/poster/10010275) |
| ICLR | 2026 | dCache: Accelerating Diffusion-Based LLMs via Dual Adaptive Caching | [Link](https://iclr.cc/virtual/2026/poster/10009386) |
| ICLR | 2026 | DiCache: Let Diffusion Model Determine Its Own Cache | [Link](https://iclr.cc/virtual/2026/poster/10007759) |
| ICLR | 2026 | Dichotomous Diffusion Policy Optimization | [Link](https://iclr.cc/virtual/2026/poster/10009527) |
| ICLR | 2026 | DiffInk: Glyph- and Style-Aware Latent Diffusion Transformer for Text to Online Handwriting Generation | [Link](https://iclr.cc/virtual/2026/poster/10008981) |
| ICLR | 2026 | DiffuCoder: Understanding and Improving Masked Diffusion Models for Code Generation | [Link](https://iclr.cc/virtual/2026/poster/10011497) |
| ICLR | 2026 | DiffuGuard: How Intrinsic Safety is Lost and Found in Diffusion Large Language Models | [Link](https://iclr.cc/virtual/2026/poster/10006479) |
| ICLR | 2026 | Diffusion Language Models are Provably Optimal Parallel Samplers | [Link](https://iclr.cc/virtual/2026/poster/10011442) |
| ICLR | 2026 | Diffusion Language Models For Code Infilling Beyond Fixed-size Canvas | [Link](https://iclr.cc/virtual/2026/poster/10010681) |
| ICLR | 2026 | Diffusion LLMs Can Do Faster-Than-AR Inference via Discrete Diffusion Forcing | [Link](https://iclr.cc/virtual/2026/poster/10007008) |
| ICLR | 2026 | Discrete Diffusion for Bundle Construction | [Link](https://iclr.cc/virtual/2026/poster/10008417) |
| ICLR | 2026 | Discrete Diffusion for Reflective Vision-Language-Action Models in Autonomous Driving | [Link](https://iclr.cc/virtual/2026/poster/10008983) |
| ICLR | 2026 | Discrete Diffusion Trajectory Alignment via Stepwise Decomposition | [Link](https://iclr.cc/virtual/2026/poster/10008084) |
| ICLR | 2026 | Don't Settle Too Early: Self-Reflective Remasking for Diffusion Language Models | [Link](https://iclr.cc/virtual/2026/poster/10010900) |
| ICLR | 2026 | DPad: Efficient Diffusion Language Models with Suffix Dropout | [Link](https://iclr.cc/virtual/2026/poster/10011883) |
| ICLR | 2026 | Dynamic-dLLM: Dynamic Cache-Budget and Adaptive Parallel Decoding for Training-Free Acceleration of Diffusion LLM | [Link](https://iclr.cc/virtual/2026/poster/10009392) |
| ICLR | 2026 | Entering the Era of Discrete Diffusion Models: A Benchmark for Schrödinger Bridges and Entropic Optimal Transport | [Link](https://iclr.cc/virtual/2026/poster/10008954) |
| ICLR | 2026 | ES-dLLM: Efficient Inference for Diffusion Large Language Models by Early-Skipping | [Link](https://iclr.cc/virtual/2026/poster/10009817) |
| ICLR | 2026 | Fast Language Generation through Discrete Diffusion Divergence Instruct | [Link](https://iclr.cc/virtual/2026/poster/10007530) |
| ICLR | 2026 | Fast-dLLM v2: Efficient Block-Diffusion LLM | [Link](https://iclr.cc/virtual/2026/poster/10011837) |
| ICLR | 2026 | Fast-dLLM: Training-free Acceleration of Diffusion LLM by Enabling KV Cache and Parallel Decoding | [Link](https://iclr.cc/virtual/2026/poster/10011631) |
| ICLR | 2026 | FlashDLM: Accelerating Diffusion Language Model Inference via Efficient KV Caching and Guided Diffusion | [Link](https://iclr.cc/virtual/2026/poster/10010125) |
| ICLR | 2026 | Forward-Learned Discrete Diffusion: Learning how to noise to denoise faster | [Link](https://iclr.cc/virtual/2026/poster/10011583) |
| ICLR | 2026 | FS-DFM: Fast and Accurate Long Text Generation with Few-Step Diffusion Language Models | [Link](https://iclr.cc/virtual/2026/poster/10006880) |
| ICLR | 2026 | FSD-CAP: Fractional Subgraph Diffusion with Class-Aware Propagation for Graph Feature Imputation | [Link](https://iclr.cc/virtual/2026/poster/10010057) |
| ICLR | 2026 | FSOD-VFM: Few-Shot Object Detection with Vision Foundation Models and Graph Diffusion | [Link](https://iclr.cc/virtual/2026/poster/10007893) |
| ICLR | 2026 | Graph Diffusion Transformers are In-Context Molecular Designers | [Link](https://iclr.cc/virtual/2026/poster/10007697) |
| ICLR | 2026 | Hierarchy Decoding: A Training-free Parallel Decoding Strategy for Diffusion Large Language Models | [Link](https://iclr.cc/virtual/2026/poster/10008769) |
| ICLR | 2026 | HOG-Diff: Higher-Order Guided Diffusion for Graph Generation | [Link](https://iclr.cc/virtual/2026/poster/10010590) |
| ICLR | 2026 | Improving Classifier-Free Guidance in Masked Diffusion: Low-Dim Theoretical Insights with High-Dim Impact | [Link](https://iclr.cc/virtual/2026/poster/10007585) |
| ICLR | 2026 | Improving Discrete Diffusion Unmasking Policies Beyond Explicit Reference Policies | [Link](https://iclr.cc/virtual/2026/poster/10007374) |
| ICLR | 2026 | Improving Reasoning for Diffusion Language Models via Group Diffusion Policy Optimization | [Link](https://iclr.cc/virtual/2026/poster/10010188) |
| ICLR | 2026 | Inference-Time Scaling of Discrete Diffusion Models via Importance Weighting and Optimal Proposal Design | [Link](https://iclr.cc/virtual/2026/poster/10011250) |
| ICLR | 2026 | Information Estimation with Discrete Diffusion | [Link](https://iclr.cc/virtual/2026/poster/10007625) |
| ICLR | 2026 | Inpainting-Guided Policy Optimization for Diffusion Large Language Models | [Link](https://iclr.cc/virtual/2026/poster/10008042) |
| ICLR | 2026 | LaTo: Landmark-tokenized Diffusion Transformer for Fine-grained Human Face Editing | [Link](https://iclr.cc/virtual/2026/poster/10011283) |
| ICLR | 2026 | Lavida-O: Elastic Large Masked Diffusion Models for Unified Multimodal Understanding and Generation | [Link](https://iclr.cc/virtual/2026/poster/10006452) |
| ICLR | 2026 | Learning to Parallel: Accelerating Diffusion Large Language Models via Adaptive Parallel Decoding | [Link](https://iclr.cc/virtual/2026/poster/10008632) |
| ICLR | 2026 | Loopholing Discrete Diffusion: Deterministic Bypass of the Sampling Wall | [Link](https://iclr.cc/virtual/2026/poster/10006736) |
| ICLR | 2026 | Lumos-1: On Autoregressive Video Generation with Discrete Diffusion from a Unified Model Perspective | [Link](https://iclr.cc/virtual/2026/poster/10006725) |
| ICLR | 2026 | Membership Inference Attacks Against Fine-tuned Diffusion Language Models | [Link](https://iclr.cc/virtual/2026/poster/10007405) |
| ICLR | 2026 | MolEditRL: Structure-Preserving Molecular Editing via Discrete Diffusion and Reinforcement Learning | [Link](https://iclr.cc/virtual/2026/poster/10011588) |
| ICLR | 2026 | Multi-Resolution Score-Based Variational Graphical Diffusion for Causal Inference on Latent Systems | [Link](https://iclr.cc/virtual/2026/poster/10009976) |
| ICLR | 2026 | Multi-Subspace Multi-Modal Modeling for Diffusion Models: Estimation, Convergence and Mixture of Experts | [Link](https://iclr.cc/virtual/2026/poster/10009950) |
| ICLR | 2026 | NI Sampling: Accelerating Discrete Diffusion Sampling by Token Order Optimization | [Link](https://iclr.cc/virtual/2026/poster/10007114) |
| ICLR | 2026 | On the Reasoning Abilities of Masked Diffusion Language Models | [Link](https://iclr.cc/virtual/2026/poster/10010941) |
| ICLR | 2026 | Parallel Multimodal Diffusion Language Models for Thinking-Aware Editing and Generation | [Link](https://iclr.cc/virtual/2026/poster/10007546) |
| ICLR | 2026 | Parallel Sampling from Masked Diffusion Models via Conditional Independence Testing | [Link](https://iclr.cc/virtual/2026/poster/10008944) |
| ICLR | 2026 | ParallelBench: Understanding the Trade-offs of Parallel Decoding in Diffusion LLMs | [Link](https://iclr.cc/virtual/2026/poster/10009745) |
| ICLR | 2026 | Planned Diffusion | [Link](https://iclr.cc/virtual/2026/poster/10006720) |
| ICLR | 2026 | Planner Aware Path Learning in Diffusion Language Models Training | [Link](https://iclr.cc/virtual/2026/poster/10007707) |
| ICLR | 2026 | Principled RL for Diffusion LLMs Emerges from a Sequence-Level Perspective | [Link](https://iclr.cc/virtual/2026/poster/10009434) |
| ICLR | 2026 | Quant-dLLM: Post-Training Extreme Low-Bit Quantization for Diffusion Large Language Models | [Link](https://iclr.cc/virtual/2026/poster/10010415) |
| ICLR | 2026 | Query-Aware Flow Diffusion for Graph-Based RAG with Retrieval Guarantees | [Link](https://iclr.cc/virtual/2026/poster/10007513) |
| ICLR | 2026 | Rainbow Padding: Mitigating Early Termination in Instruction-Tuned Diffusion LLMs | [Link](https://iclr.cc/virtual/2026/poster/10008451) |
| ICLR | 2026 | ReFusion: A Diffusion Large Language Model with Parallel Autoregressive Decoding | [Link](https://iclr.cc/virtual/2026/poster/10010055) |
| ICLR | 2026 | Revolutionizing Reinforcement Learning Framework for Diffusion Large Language Models | [Link](https://iclr.cc/virtual/2026/poster/10010138) |
| ICLR | 2026 | Scaling Behavior of Discrete Diffusion Language Models | [Link](https://iclr.cc/virtual/2026/poster/10010520) |
| ICLR | 2026 | Scaling Speech Tokenizers with Diffusion Autoencoders | [Link](https://iclr.cc/virtual/2026/poster/10007650) |
| ICLR | 2026 | Self-Speculative Masked Diffusions | [Link](https://iclr.cc/virtual/2026/poster/10007386) |
| ICLR | 2026 | Soft-Masked Diffusion Language Models | [Link](https://iclr.cc/virtual/2026/poster/10010474) |
| ICLR | 2026 | SparseD: Sparse Attention for Diffusion Language Models | [Link](https://iclr.cc/virtual/2026/poster/10008368) |
| ICLR | 2026 | SPG: Sandwiched Policy Gradient for Masked Diffusion Language Models | [Link](https://iclr.cc/virtual/2026/poster/10011858) |
| ICLR | 2026 | Stopping Computation for Converged Tokens in Masked Diffusion-LM Decoding | [Link](https://iclr.cc/virtual/2026/poster/10009632) |
| ICLR | 2026 | TEST-TIME SCALING IN DIFFUSION LLMS VIA HIDDEN SEMI-AUTOREGRESSIVE EXPERTS | [Link](https://iclr.cc/virtual/2026/poster/10010063) |
| ICLR | 2026 | Time Is a Feature: Exploiting Temporal Dynamics in Diffusion Language Models | [Link](https://iclr.cc/virtual/2026/poster/10010359) |
| ICLR | 2026 | Token-based Audio Inpainting via Discrete Diffusion | [Link](https://iclr.cc/virtual/2026/poster/10011102) |
| ICLR | 2026 | Toward Safer Diffusion Language Models: Discovery and Mitigation of Priming Vulnerability | [Link](https://iclr.cc/virtual/2026/poster/10008814) |
| ICLR | 2026 | UltraLLaDA: Scaling the Context Length to 128K for Diffusion Large Language Models | [Link](https://iclr.cc/virtual/2026/poster/10011397) |
| ICLR | 2026 | UniCalli: A Unified Diffusion Framework for Column-Level Generation and Recognition of Chinese Calligraphy | [Link](https://iclr.cc/virtual/2026/poster/10009779) |
| ICLR | 2026 | Unified Diffusion VLA: Vision-Language-Action Model via Joint Discrete Diffusion Diffusion Process | [Link](https://iclr.cc/virtual/2026/poster/10009185) |
| ICLR | 2026 | Uniform Discrete Diffusion with Metric Path for Video Generation | [Link](https://iclr.cc/virtual/2026/poster/10010514) |
| ICLR | 2026 | Unifying Diffusion and Autoregression for Generalizable Vision-Language-Action Model | [Link](https://iclr.cc/virtual/2026/poster/10010439) |
| ICLR | 2026 | Universal Multi-Domain Translation via Diffusion Routers | [Link](https://iclr.cc/virtual/2026/poster/10010095) |
| ICLR | 2026 | Unveiling the Potential of Diffusion Large Language Model in Controllable Generation | [Link](https://iclr.cc/virtual/2026/poster/10007218) |
| ICLR | 2026 | Variational Autoencoding Discrete Diffusion with Enhanced Dimensional Correlations Modeling | [Link](https://iclr.cc/virtual/2026/poster/10006537) |
| ICLR | 2026 | VibeVoice: Expressive Podcast Generation with Next-Token Diffusion | [Link](https://iclr.cc/virtual/2026/poster/10010573) |
| ICLR | 2026 | Watermarking Diffusion Language Models | [Link](https://iclr.cc/virtual/2026/poster/10011629) |
| ICLR | 2026 | WavefrontDiffusion: Dynamic Decoding Schedule for Improved Reasoning | [Link](https://iclr.cc/virtual/2026/poster/10011520) |
| ICLR | 2026 | wd1: Weighted Policy Optimization for Reasoning in Diffusion Language Models | [Link](https://iclr.cc/virtual/2026/poster/10010070) |
| ICLR | 2026 | What Exactly Does Guidance Do in Masked Discrete Diffusion Models | [Link](https://iclr.cc/virtual/2026/poster/10008094) |
| ICML | 2023 | Autoregressive Diffusion Model for Graph Generation | [Link](https://icml.cc/virtual/2023/poster/23452) |
| ICML | 2023 | Blackout Diffusion: Generative Diffusion Models in Discrete-State Spaces | [Link](https://icml.cc/virtual/2023/poster/23799) |
| ICML | 2023 | Efficient and Degree-Guided Graph Generation via Discrete Diffusion Modeling | [Link](https://icml.cc/virtual/2023/poster/25116) |
| ICML | 2023 | MolDiff: Addressing the Atom-Bond Inconsistency Problem in 3D Molecule Diffusion Generation | [Link](https://icml.cc/virtual/2023/poster/24055) |
| ICML | 2023 | TabDDPM: Modelling Tabular Data with Diffusion Models | [Link](https://icml.cc/virtual/2023/poster/24703) |
| ICML | 2024 | A Diffusion Model Framework for Unsupervised Neural Combinatorial Optimization | [Link](https://icml.cc/virtual/2024/poster/34775) |
| ICML | 2024 | Antibody Design Using a Score-based Diffusion Model Guided by Evolutionary, Physical and Geometric Constraints | [Link](https://icml.cc/virtual/2024/poster/35143) |
| ICML | 2024 | Bridging discrete and continuous state spaces: Exploring the Ehrenfest process in time-continuous diffusion models | [Link](https://icml.cc/virtual/2024/poster/34853) |
| ICML | 2024 | Diffuse, Sample, Project: Plug-And-Play Controllable Graph Generation | [Link](https://icml.cc/virtual/2024/poster/33350) |
| ICML | 2024 | Diffusion Language Models Are Versatile Protein Learners | [Link](https://icml.cc/virtual/2024/poster/34203) |
| ICML | 2024 | Dirichlet Flow Matching with Applications to DNA Sequence Design | [Link](https://icml.cc/virtual/2024/poster/32887) |
| ICML | 2024 | Discrete Diffusion Modeling by Estimating the Ratios of the Data Distribution | [Link](https://icml.cc/virtual/2024/poster/34686) |
| ICML | 2024 | Generative Flows on Discrete State-Spaces: Enabling Multimodal Flows with Applications to Protein Co-Design | [Link](https://icml.cc/virtual/2024/poster/33257) |
| ICML | 2025 | CFP-Gen: Combinatorial Functional Protein Generation via Diffusion Language Models | [Link](https://icml.cc/virtual/2025/poster/45932) |
| ICML | 2025 | Discrete Markov Probabilistic Models: An Improved Discrete Score-Based Framework with sharp convergence bounds under minimal assumptions | [Link](https://icml.cc/virtual/2025/poster/44729) |
| ICML | 2025 | Distillation of Discrete Diffusion through Dimensional Correlations | [Link](https://icml.cc/virtual/2025/poster/44314) |
| ICML | 2025 | Generalized Interpolating Discrete Diffusion | [Link](https://icml.cc/virtual/2025/poster/43859) |
| ICML | 2025 | GenMol: A Drug Discovery Generalist with Discrete Diffusion | [Link](https://icml.cc/virtual/2025/poster/45647) |
| ICML | 2025 | Graph Diffusion for Robust Multi-Agent Coordination | [Link](https://icml.cc/virtual/2025/poster/45189) |
| ICML | 2025 | Outlier-Aware Post-Training Quantization for Discrete Graph Diffusion Models | [Link](https://icml.cc/virtual/2025/poster/43639) |
| ICML | 2025 | PepTune: De Novo Generation of Therapeutic Peptides with Multi-Objective-Guided Discrete Diffusion | [Link](https://icml.cc/virtual/2025/poster/45889) |
| ICML | 2025 | Simple and Critical Iterative Denoising: A Recasting of Discrete Diffusion in Graph Generatio | [Link](https://icml.cc/virtual/2025/poster/44256) |
| ICML | 2025 | SketchDNN: Joint Continuous-Discrete Diffusion for CAD Sketch Generation | [Link](https://icml.cc/virtual/2025/poster/46031) |
| ICML | 2025 | TabNAT: A Continuous-Discrete Joint Generative Framework for Tabular Data | [Link](https://icml.cc/virtual/2025/poster/45006) |
| ICML | 2025 | Target Concrete Score Matching: A Holistic Framework for Discrete Diffusion | [Link](https://icml.cc/virtual/2025/poster/44859) |
| ICML | 2025 | The Diffusion Duality | [Link](https://icml.cc/virtual/2025/poster/46226) |
| ICML | 2025 | Train for the Worst, Plan for the Best: Understanding Token Ordering in Masked Diffusions | [Link](https://icml.cc/virtual/2025/poster/45990) |
| ICML | 2026 | Advantage Weighted Matching: Aligning RL with Pretraining in Diffusion Models | [Link](https://icml.cc/virtual/2026/poster/61737) |
| ICML | 2026 | Adversarial Reinforcement Learning for Robust Diffusion Large Language Model Unlearning | [Link](https://icml.cc/virtual/2026/poster/65904) |
| ICML | 2026 | Any-Diffusion: Unified Multimodal Understanding and Generation with Masked Discrete Diffusion | [Link](https://icml.cc/virtual/2026/poster/65305) |
| ICML | 2026 | Any-Order GPT as Masked Diffusion Model: Decoupling Formulation and Architecture | [Link](https://icml.cc/virtual/2026/poster/61245) |
| ICML | 2026 | Balancing Understanding and Generation in Discrete Diffusion Models | [Link](https://icml.cc/virtual/2026/poster/61499) |
| ICML | 2026 | Beyond Confidence: Adaptive and Coherent Decoding for Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/63007) |
| ICML | 2026 | Breaking the Factorization Barrier in Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/62624) |
| ICML | 2026 | Can I Have Your Order? Monte-Carlo Tree Search for Slot Filling Ordering in Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/61868) |
| ICML | 2026 | CANDI: Hybrid Discrete-Continuous Diffusion Models | [Link](https://icml.cc/virtual/2026/poster/66818) |
| ICML | 2026 | Coevolutionary Continuous Discrete Diffusion: Make Your Diffusion Language Model a Latent Reasoner | [Link](https://icml.cc/virtual/2026/poster/66003) |
| ICML | 2026 | Consistent Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/66178) |
| ICML | 2026 | CoRe: Context-Robust Remasking for Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/62928) |
| ICML | 2026 | d2: Improved Techniques for Training Reasoning Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/61924) |
| ICML | 2026 | d3LLM: Ultra-Fast Diffusion LLM using Pseudo-Trajectory Distillation | [Link](https://icml.cc/virtual/2026/poster/61269) |
| ICML | 2026 | Dependency-Aware Parallel Decoding via Attention for Diffusion LLMs | [Link](https://icml.cc/virtual/2026/poster/64624) |
| ICML | 2026 | DFlash: Block Diffusion for Flash Speculative Decoding | [Link](https://icml.cc/virtual/2026/poster/64301) |
| ICML | 2026 | dgMARK: Decoding-Guided Watermarking for Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/61861) |
| ICML | 2026 | DiffuMamba: High-Throughput Diffusion LMs with Mamba Backbone | [Link](https://icml.cc/virtual/2026/poster/62355) |
| ICML | 2026 | DiffuReason: Enhancing Reasoning Ability for Diffusion Language Models via Monte Carlo Tree Search | [Link](https://icml.cc/virtual/2026/poster/64457) |
| ICML | 2026 | Diffusing to Coordinate: Efficient Online Multi-Agent Diffusion Policies | [Link](https://icml.cc/virtual/2026/poster/61146) |
| ICML | 2026 | Diffusion Language Model Parallel Decoding via Product-of-Experts Bridge | [Link](https://icml.cc/virtual/2026/poster/62267) |
| ICML | 2026 | Discrete Diffusion Samplers and Bridges: Off-Policy Algorithms and Applications in Latent Spaces | [Link](https://icml.cc/virtual/2026/poster/62949) |
| ICML | 2026 | Discrete Diffusion VLA: Bringing Discrete Diffusion to Action Decoding in Vision-Language-Action Policies | [Link](https://icml.cc/virtual/2026/poster/62902) |
| ICML | 2026 | Discrete Diffusion with Physical Mass Constraints for \emph{De Novo} Peptide Sequencing | [Link](https://icml.cc/virtual/2026/poster/61142) |
| ICML | 2026 | dLLM-Cache: Accelerating Diffusion Large Language Models with Adaptive Caching | [Link](https://icml.cc/virtual/2026/poster/62405) |
| ICML | 2026 | DSB: Dynamic Sliding Block Scheduling for Diffusion LLMs | [Link](https://icml.cc/virtual/2026/poster/63149) |
| ICML | 2026 | dTRPO : Trajectory Reduction in Policy Optimization of Diffusion Large Language Models | [Link](https://icml.cc/virtual/2026/poster/63947) |
| ICML | 2026 | DyLLM: Efficient Diffusion LLM inference via saliency-based token selection and partial attention | [Link](https://icml.cc/virtual/2026/poster/66757) |
| ICML | 2026 | Efficient Diffusion LLMs via Temporal-Spatial Parallel Decoding and Confidence Extrapolation | [Link](https://icml.cc/virtual/2026/poster/63560) |
| ICML | 2026 | Efficient Test-Time Scaling via Hierarchical Search and Self-Verification for Discrete Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/64102) |
| ICML | 2026 | Efficient-DLM: From Autoregressive to Diffusion Language Models, and Beyond in Speed | [Link](https://icml.cc/virtual/2026/poster/60580) |
| ICML | 2026 | Enhancing Reasoning for Diffusion LLMs via Distribution Matching Policy Optimization | [Link](https://icml.cc/virtual/2026/poster/66806) |
| ICML | 2026 | Exploring More to Solve More: Boosting Diversity in Text Diffusion Models via Entropy-Based Guidance | [Link](https://icml.cc/virtual/2026/poster/63343) |
| ICML | 2026 | FAIR-Calib: Frontier-Aware Instability-Reweighted Calibration for Post-Training Quantization of Diffusion Large Language Models | [Link](https://icml.cc/virtual/2026/poster/62977) |
| ICML | 2026 | Fine-Tuning Masked Diffusion for Provable Self-Correction | [Link](https://icml.cc/virtual/2026/poster/66597) |
| ICML | 2026 | FRIGID: Scaling Diffusion-Based Molecular Generation from Mass Spectra at Training and Inference Time | [Link](https://icml.cc/virtual/2026/poster/60806) |
| ICML | 2026 | From Bits to Rounds: Parallel Decoding with Exploration for Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/65555) |
| ICML | 2026 | Generalization Bounds for Discrete Diffusion: Statistical Advantage of Masking | [Link](https://icml.cc/virtual/2026/poster/64332) |
| ICML | 2026 | Generalized Discrete Diffusion with Self-Correction | [Link](https://icml.cc/virtual/2026/poster/60520) |
| ICML | 2026 | Generative Large Neighborhood Search: Scalable Set Cover Optimization via Discrete Diffusion | [Link](https://icml.cc/virtual/2026/poster/60514) |
| ICML | 2026 | Generative Representation Learning on Hyper-relational Knowledge Graphs via Masked Discrete Diffusion | [Link](https://icml.cc/virtual/2026/poster/61945) |
| ICML | 2026 | Guided Star-Shaped Masked Diffusion | [Link](https://icml.cc/virtual/2026/poster/61992) |
| ICML | 2026 | IDLM: Inverse-distilled Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/62959) |
| ICML | 2026 | Improving Sampling for Masked Diffusion Models via Information Gain | [Link](https://icml.cc/virtual/2026/poster/66694) |
| ICML | 2026 | Infinite Mask Diffusion for Few-Step Distillation | [Link](https://icml.cc/virtual/2026/poster/62932) |
| ICML | 2026 | InfoDLM: an Information-Adaptive Framework for Discrete Diffusion Language Model Pretraining | [Link](https://icml.cc/virtual/2026/poster/62899) |
| ICML | 2026 | Information-Geometric Adaptive Sampling for Graph Diffusion | [Link](https://icml.cc/virtual/2026/poster/63421) |
| ICML | 2026 | Is Your Diffusion Sampler Actually Correct? A Sampler-Centric Evaluation of Discrete Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/61598) |
| ICML | 2026 | Lavida-R1: Advancing Reasoning for Unified Multimodal Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/61503) |
| ICML | 2026 | Learnability-Informed Fine-Tuning of Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/64915) |
| ICML | 2026 | Learning Discrete Diffusion on Graphs via Free-Energy Gradient Flows | [Link](https://icml.cc/virtual/2026/poster/63600) |
| ICML | 2026 | Learning Unmasking Policies for Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/65277) |
| ICML | 2026 | Locally Coherent Parallel Decoding in Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/62309) |
| ICML | 2026 | Lookahead Path Likelihood Optimization for Diffusion LLMs | [Link](https://icml.cc/virtual/2026/poster/63448) |
| ICML | 2026 | Lookahead Sample Reward Guidance for Test-Time Scaling of Diffusion Models | [Link](https://icml.cc/virtual/2026/poster/64926) |
| ICML | 2026 | Lookahead Unmasking Elicits Reliable Decoding in Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/64337) |
| ICML | 2026 | LoSA: Locality Aware Sparse Attention in Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/63941) |
| ICML | 2026 | LUGS: Latent-aware Guidance for Efficient Unmasking in Diffusion Large Language Models | [Link](https://icml.cc/virtual/2026/poster/61065) |
| ICML | 2026 | Masks Can Be Distracting: On Context Comprehension in Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/62580) |
| ICML | 2026 | Mind-Omni: A Unified Multi-Task Framework for Brain-Vision-Language Modeling via Discrete Diffusion | [Link](https://icml.cc/virtual/2026/poster/66443) |
| ICML | 2026 | Mitigating Mask Prior Drift and Positional Attention Collapse in Large Diffusion Vision-Language Models | [Link](https://icml.cc/virtual/2026/poster/61233) |
| ICML | 2026 | Mosaic: Unlocking Over 30 Context Length for Diffusion LLMs Inference via Global Memory Planning and Dynamic Peak Taming | [Link](https://icml.cc/virtual/2026/poster/61986) |
| ICML | 2026 | NaRA: Noise-Aware LoRA for Parameter-Efficient Fine-Tuning of Diffusion LLMs | [Link](https://icml.cc/virtual/2026/poster/61250) |
| ICML | 2026 | Navigating the Energy Landscape of Collaboration: Multi-Agent Communication Graph Generation via Score-Based Diffusion | [Link](https://icml.cc/virtual/2026/poster/61913) |
| ICML | 2026 | Plan for Speed: Dilated Scheduling for Masked Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/65445) |
| ICML | 2026 | Plug-and-Play Guidance for Discrete Diffusion Models via Gradient-Informed Logit Correction | [Link](https://icml.cc/virtual/2026/poster/64933) |
| ICML | 2026 | Reasoning on the Manifold: Bidirectional Consistency for Self-Verification in Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/65552) |
| ICML | 2026 | Reinforcement Learning with Discrete Diffusion Policies for Combinatorial Action Spaces | [Link](https://icml.cc/virtual/2026/poster/61107) |
| ICML | 2026 | Residual Context Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/62575) |
| ICML | 2026 | Scaling Beyond Masked Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/60709) |
| ICML | 2026 | ScDiVa: Masked Discrete Diffusion for Joint Modeling of Single-Cell Identity and Expression | [Link](https://icml.cc/virtual/2026/poster/63890) |
| ICML | 2026 | Search or Accelerate: Confidence-Switched Position Beam Search for Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/65806) |
| ICML | 2026 | Self-Augmenting Retrieval for Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/60996) |
| ICML | 2026 | Simple Policy Gradients for Reasoning with Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/65988) |
| ICML | 2026 | Singular Proxies for Adaptive Caching in Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/66363) |
| ICML | 2026 | Smoothie: Smoothing Diffusion on Token Embeddings for Text Generation | [Link](https://icml.cc/virtual/2026/poster/64948) |
| ICML | 2026 | Stabilizing Reinforcement Learning for Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/63228) |
| ICML | 2026 | Stop Training for the Worst: Progressive Unmasking Accelerates Masked Diffusion Training | [Link](https://icml.cc/virtual/2026/poster/66284) |
| ICML | 2026 | Swordsman: Entropy-Driven Adaptive Block Partition for Efficient Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/65444) |
| ICML | 2026 | TD3B: Transition-Directed Discrete Diffusion for Allosteric Binder Generation | [Link](https://icml.cc/virtual/2026/poster/64049) |
| ICML | 2026 | TDM-R1: Reinforcing Few-Step Diffusion Models with Non-Differentiable Reward | [Link](https://icml.cc/virtual/2026/poster/66300) |
| ICML | 2026 | TEAM: Temporal–Spatial Consistency Guided Expert Activation for MoE Diffusion Language Model Acceleration | [Link](https://icml.cc/virtual/2026/poster/63641) |
| ICML | 2026 | Test-Time Anchoring for Discrete Diffusion Posterior Sampling | [Link](https://icml.cc/virtual/2026/poster/61295) |
| ICML | 2026 | Training Diffusion Language Models for Black-Box Optimization | [Link](https://icml.cc/virtual/2026/poster/63202) |
| ICML | 2026 | Trajectory-Level Speculative Decoding for Diffusion Language Models | [Link](https://icml.cc/virtual/2026/poster/61516) |
| ICML | 2026 | Tuning the Implicit Regularizer of Masked Diffusion Language Models: Enhancing Generalization via Insights from -Parity | [Link](https://icml.cc/virtual/2026/poster/63660) |
| ICML | 2026 | UDM-GRPO: Stable and Efficient Group Relative Policy Optimization for Uniform Discrete Diffusion Models | [Link](https://icml.cc/virtual/2026/poster/63538) |
| ICML | 2026 | Unifying Masked Diffusion Models with Various Generation Orders and Beyond | [Link](https://icml.cc/virtual/2026/poster/65757) |
| ICML | 2026 | UnMaskFork: Test-Time Scaling for Masked Diffusion via Deterministic Action Branching | [Link](https://icml.cc/virtual/2026/poster/66823) |
| ICML | 2026 | VidLaDA: Bidirectional Diffusion Large Language Models for Efficient Video Understanding | [Link](https://icml.cc/virtual/2026/poster/62653) |
| ICML | 2026 | WeDLM: Reconciling Diffusion Language Models with Standard Causal Attention for Fast Inference | [Link](https://icml.cc/virtual/2026/poster/64095) |
| ICML | 2026 | When Diffusion Language Models Hesitate: Detecting and Correcting Visual Hallucinations via Confidence Fluctuation | [Link](https://icml.cc/virtual/2026/poster/66650) |
| ICML | 2026 | “Do Diffusion Models Dream of Electric Planes?” Discrete and Continuous Simulation-Based Inference for Aircraft Design | [Link](https://icml.cc/virtual/2026/poster/66800) |
| IJCAI | 2023 | Diffusion Models for Non-autoregressive Text Generation: A Survey | [Link](https://www.ijcai.org/proceedings/2023/750) |
| IJCAI | 2023 | Discrete Diffusion Probabilistic Models for Symbolic Music Generation | [Link](https://www.ijcai.org/proceedings/2023/648) |
| IJCAI | 2023 | Generative Diffusion Models on Graphs: Methods and Applications | [Link](https://www.ijcai.org/proceedings/2023/751) |
| IJCAI | 2025 | A Prior-based Discrete Diffusion Model for Social Graph Generation | [Link](https://www.ijcai.org/proceedings/2025/397) |
| IJCAI | 2025 | Antibody Design and Optimization with Multi-scale Equivariant Graph Diffusion Models for Accurate Complex Antigen Binding | [Link](https://www.ijcai.org/proceedings/2025/303) |
| NAACL | 2024 | Aspect-based Sentiment Analysis with Context Denoising | [Link](https://aclanthology.org/2024.findings-naacl.194/) |
| NAACL | 2024 | Diffusion Glancing Transformer for Parallel Sequence-to-Sequence Learning | [Link](https://aclanthology.org/2024.naacl-long.271/) |
| NAACL | 2024 | Empowering Diffusion Models on the Embedding Space for Text Generation | [Link](https://aclanthology.org/2024.naacl-long.261/) |
| NAACL | 2024 | LaDiC: Are Diffusion Models Really Inferior to Autoregressive Counterparts for Image-to-Text Generation? | [Link](https://aclanthology.org/2024.naacl-long.373/) |
| NAACL | 2024 | P3Sum: Preserving Author’s Perspective in News Summarization with Diffusion Language Models | [Link](https://aclanthology.org/2024.naacl-long.119/) |
| NAACL | 2024 | Text Diffusion Model with Encoder-Decoder Transformers for Sequence-to-Sequence Generation | [Link](https://aclanthology.org/2024.naacl-long.2/) |
| NAACL | 2025 | Discrete Diffusion Language Model for Efficient Text Summarization | [Link](https://aclanthology.org/2025.findings-naacl.352/) |
| NAACL | 2025 | Private Synthetic Text Generation with Diffusion Models | [Link](https://aclanthology.org/2025.naacl-long.532/) |
| NAACL | 2025 | Speculative Diffusion Decoding: Accelerating Language Generation through Diffusion | [Link](https://aclanthology.org/2025.naacl-long.601/) |
| NAACL | 2025 | StyleTTS-ZS: Efficient High-Quality Zero-Shot Text-to-Speech Synthesis with Distilled Time-Varying Style Diffusion | [Link](https://aclanthology.org/2025.naacl-long.242/) |
| NeurIPS | 2021 | Structured Denoising Diffusion Models in Discrete State-Spaces | [Link](https://papers.neurips.cc/paper/2021/file/958c530554f78bcd8e97125b70e6973d-Paper.pdf) |
| NeurIPS | 2022 | Masked Generative Adversarial Networks are Data-Efficient Generation Learners | [Link](https://proceedings.neurips.cc/paper_files/paper/2022/hash/0efcb1885b8534109f95ca82a5319d25-Abstract-Conference.html) |
| NeurIPS | 2022 | MaskGIT: Masked Generative Image Transformer | [Link](https://openaccess.thecvf.com/content/CVPR2022/html/Chang_MaskGIT_Masked_Generative_Image_Transformer_CVPR_2022_paper.html) |
| NeurIPS | 2022 | Vector Quantized Diffusion Model for Text-to-Image Synthesis | [Link](https://openaccess.thecvf.com/content/CVPR2022/html/Gu_Vector_Quantized_Diffusion_Model_for_Text-to-Image_Synthesis_CVPR_2022_paper.html) |
| NeurIPS | 2023 | AR-Diffusion: Auto-Regressive Diffusion Model for Text Generation | [Link](https://neurips.cc/virtual/2023/poster/73068) |
| NeurIPS | 2023 | Characterizing and Measuring Linguistic Dataset Drift | [Link](https://aclanthology.org/2023.acl-long.498/) |
| NeurIPS | 2023 | Improving Discrete Diffusion Models via Structured Preferential Masking | [Link](https://neurips.cc/virtual/2023/74850) |
| NeurIPS | 2023 | Protein Design with Guided Discrete Diffusion | [Link](https://neurips.cc/virtual/2023/poster/71899) |
| NeurIPS | 2023 | TextDiffuser: Diffusion Models as Text Painters | [Link](https://neurips.cc/virtual/2023/poster/70636) |
| NeurIPS | 2024 | Aligning Target-Aware Molecule Diffusion Models with Exact Energy Optimization | [Link](https://neurips.cc/virtual/2024/poster/96029) |
| NeurIPS | 2024 | Breaking Determinism: Fuzzy Modeling of Sequential Recommendation Using Discrete State Space Diffusion Model | [Link](https://neurips.cc/virtual/2024/poster/94096) |
| NeurIPS | 2024 | Di2Pose: Discrete Diffusion Model for Occluded 3D Human Pose Estimation | [Link](https://neurips.cc/virtual/2024/poster/93586) |
| NeurIPS | 2024 | Discrete Flow Matching | [Link](https://neurips.cc/virtual/2024/poster/95902) |
| NeurIPS | 2024 | Discrete-state Continuous-time Diffusion for Graph Generation | [Link](https://neurips.cc/virtual/2024/poster/94674) |
| NeurIPS | 2024 | Fast Sampling via Discrete Non-Markov Diffusion Models with Predetermined Transition Time | [Link](https://neurips.cc/virtual/2024/poster/95646) |
| NeurIPS | 2024 | MC-DiT: Contextual Enhancement via Clean-to-Clean Reconstruction for Masked Diffusion Models | [Link](https://neurips.cc/virtual/2024/poster/93037) |
| NeurIPS | 2024 | Rethinking Task-Oriented Dialogue Systems: From Complex Modularity to Zero-Shot Autonomous Agent | [Link](https://aclanthology.org/2024.acl-long.152/) |
| NeurIPS | 2024 | Simple and Effective Masked Diffusion Language Models | [Link](https://neurips.cc/virtual/2024/poster/95622) |
| NeurIPS | 2024 | Simplified and Generalized Masked Diffusion for Discrete Data | [Link](https://neurips.cc/virtual/2024/poster/93071) |
| NeurIPS | 2024 | Unlocking the Capabilities of Masked Generative Models for Image Synthesis via Self-Guidance | [Link](https://neurips.cc/virtual/2024/poster/96852) |
| NeurIPS | 2025 | Absorb and Converge: Provable Convergence Guarantee for Absorbing Discrete Diffusion Models | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/117647) |
| NeurIPS | 2025 | Accelerated Sampling from Masked Diffusion Models via Entropy Bounded Unmasking | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/117618) |
| NeurIPS | 2025 | Any-Order Flexible Length Masked Diffusion | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/125446) |
| NeurIPS | 2025 | Beyond Masked and Unmasked: Discrete Diffusion Models via Partial Masking | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/116103) |
| NeurIPS | 2025 | Breaking AR’s Sampling Bottleneck: Provable Acceleration via Diffusion Language Models | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/115552) |
| NeurIPS | 2025 | Constrained Discrete Diffusion | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/119091) |
| NeurIPS | 2025 | Derivative-Free Guidance in Continuous and Discrete Diffusion Models with Soft Value-based Decoding | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/119789) |
| NeurIPS | 2025 | Discrete Spatial Diffusion: Intensity-Preserving Diffusion Modeling | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/116326) |
| NeurIPS | 2025 | Fast Solvers for Discrete Diffusion Models: Theory and Applications of High-Order Algorithms | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/118258) |
| NeurIPS | 2025 | Feedback Guidance of Diffusion Models | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/119581) |
| NeurIPS | 2025 | Improved Sampling from Masked Diffusion Models with Position Contrastive Guidance | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/125443) |
| NeurIPS | 2025 | Information-Theoretic Discrete Diffusion | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/119416) |
| NeurIPS | 2025 | Informed Correctors for Discrete Diffusion Models | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/118907) |
| NeurIPS | 2025 | KLASS: KL-Guided Fast Inference in Masked Diffusion Models | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/116747) |
| NeurIPS | 2025 | Large Language Diffusion Models | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/118608) |
| NeurIPS | 2025 | Learnable Sampler Distillation for Discrete Diffusion Models | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/116751) |
| NeurIPS | 2025 | Masked Diffusion Models as Energy Minimization | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/119627) |
| NeurIPS | 2025 | MDNS: Masked Diffusion Neural Sampler via Stochastic Optimal Control | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/115255) |
| NeurIPS | 2025 | Metis: A Foundation Speech Generation Model with Masked Generative Pre-training | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/118023) |
| NeurIPS | 2025 | Non-Markovian Discrete Diffusion with Causal Language Models | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/115857) |
| NeurIPS | 2025 | Plug-and-Play Context Feature Reuse for Efficient Masked Generation | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/116393) |
| NeurIPS | 2025 | Reinforcement Learning Meets Masked Generative Models: Mask-GRPO for Text-to-Image Generation | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/119326) |
| NeurIPS | 2025 | RETRO SYNFLOW: Discrete Flow-Matching for Accurate and Diverse Single-Step Retrosynthesis | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/117074) |
| NeurIPS | 2025 | ShortListing Model: A Streamlined Simplex Diffusion for Discrete Variable Generation | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/117372) |
| NeurIPS | 2025 | Split Gibbs Discrete Diffusion Posterior Sampling | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/117795) |
| NeurIPS | 2025 | State Size Independent Statistical Error Bound for Discrete Diffusion Models | [Link](https://neurips.cc/virtual/2025/loc/san-diego/poster/118983) |
| NeurIPS | 2025 | Think while You Generate: Discrete Diffusion with Planned Denoising | [Link](https://iclr.cc/virtual/2025/poster/29942) |
| NeurIPS | 2026 | The Devil behind the mask: An emergent safety vulnerability of Diffusion LLMs | [Link](https://iclr.cc/virtual/2026/poster/10007159) |
| NeurIPS |  | Argmax flows and multinomial diffusion: learning categorical distributions | [Link](https://dl.acm.org/doi/10.5555/3540261.3541214) |
| NeurIPS |  | Concrete Score Matching: Generalized Score Matching for Discrete Data | [Link](https://arxiv.org/abs/2211.00802) |
| NeurIPS |  | Concrete score matching: generalized score matching for discrete data | [Link](https://dl.acm.org/doi/10.5555/3600270.3602772) |
| NeurIPS |  | d3LLM: Ultra-Fast Diffusion LLM using Pseudo-Trajectory Distillation | [Link](https://arxiv.org/abs/2601.07568) |
| NeurIPS |  | DICE: Discrete Inversion Enabling Controllable Editing for Multinomial Diffusion and Masked Generative Models | [Link](https://arxiv.org/abs/2410.08207) |
| NeurIPS |  | Likelihood-Based Diffusion Language Models | [Link](https://openreview.net/forum?id=e2MCL6hObn&noteId=ueUWS1aqtE) |
| NeurIPS |  | Mask-Predict: Parallel Decoding of Conditional Masked Language Models | [Link](https://aclanthology.org/D19-1633/) |
| TMLR |  | Cometh: A continuous-time discrete-state graph diffusion model | [Link](https://openreview.net/forum?id=AY89HCxunl) |
| TMLR |  | Discrete Diffusion in Large Language and Multimodal Models: A Survey | [Link](https://openreview.net/forum?id=0DsqnkP8Cp) |
| TMLR |  | Discrete Graph Auto-Encoder | [Link](https://arxiv.org/abs/2306.07735) |
| TMLR |  | Discrete Interpolants: Unifying the Masked Generative and Discrete Diffusion Models | [Link](https://openreview.net/forum?id=CkAHiOUvOx) |
| TMLR |  | Efficient Object-Centric Representation Learning using Masked Generative Modeling | [Link](https://openreview.net/forum?id=t9KvOYPeL3) |
| TMLR |  | From discrete-time policies to continuous-time diffusion samplers: Asymptotic equivalences and faster training | [Link](https://arxiv.org/abs/2501.06148) |
| TMLR |  | G2D2: Gradient-Guided Discrete Diffusion for Inverse Problem Solving | [Link](https://openreview.net/forum?id=fj23qnVifX) |
| TMLR |  | GeNIe: Generative Hard Negative Images Through Diffusion | [Link](https://openreview.net/forum?id=VuLEOyTiPO) |
| TMLR |  | GraphMaker: Can Diffusion Models Generate Large Attributed Graphs? | [Link](https://openreview.net/forum?id=ledQ1BCrwc) |
| TMLR |  | Guided Discrete Diffusion for Electronic Health Record Generation | [Link](https://openreview.net/forum?id=N2rWhTgits) |
| TMLR |  | On the Inherent Privacy Properties of Discrete Denoising Diffusion Models | [Link](https://openreview.net/forum?id=UuU6C6CUoF) |
| TMLR |  | SparseDiff: Sparse Discrete Diffusion for Scalable Graph Generation | [Link](https://openreview.net/forum?id=kuJ3lpxnVC) |
