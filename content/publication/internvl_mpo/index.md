---
title: "Enhancing the Reasoning Ability of Multimodal Large Language Models via Mixed Preference Optimization"
authors:
- 'Weiyun Wang'
- 'Zhe Chen'
- 'Wenhai Wang'
- admin
- 'Yangzhou Liu'
- 'Zhangwei Gao'
- 'Jinguo Zhu'
- 'Xizhou Zhu'
- 'Lewei Lu'
- 'Yu Qiao'
- 'Jifeng Dai'

date: "2024-11-15T18:59:27Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-11-15T18:59:27Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Existing open-source multimodal large language models (MLLMs) generally follow a training process involving pre-training and supervised fine-tuning. However, these models suffer from distribution shifts, which limit their multimodal reasoning, particularly in the Chain-of-Thought (CoT) performance. To address this, we introduce a preference optimization (PO) process to enhance the multimodal reasoning capabilities of MLLMs. Specifically, (1) on the data side, we design an automated preference data construction pipeline to create MMPR, a high-quality, large-scale multimodal reasoning preference dataset. and (2) on the model side, we explore integrating PO with MLLMs, developing a simple yet effective method, termed Mixed Preference Optimization (MPO), which boosts multimodal CoT performance. Our approach demonstrates improved performance across multiple benchmarks, particularly in multimodal reasoning tasks. Notably, our model, InternVL2-8B-MPO, achieves an accuracy of 67.0 on MathVista, outperforming InternVL2-8B by 8.7 points and achieving performance comparable to the 10x larger InternVL2-76B. We hope this study could inspire further advancements in MLLMs. Code, data, and model shall be publicly released.

# Summary. An optional shortened abstract.
summary: ''

tags:
  - Multimodal Large Language Models
  - Multimodal Reasoning

featured: true

url_pdf: ''
url_code: 'https://github.com/OpenGVLab/InternVL/tree/main/internvl_chat/tools/mmpr_pipeline'
url_dataset: 'https://huggingface.co/datasets/OpenGVLab/MMPR-v1.1'
url_project: 'https://internvl.github.io/blog/2024-12-20-InternVL-2.5-MPO/'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

### Citation

If you find this project useful in your research, please consider cite:

```BibTeX
@article{wang2024enhancing,
  title={Enhancing the reasoning ability of multimodal large language models via mixed preference optimization},
  author={Wang, Weiyun and Chen, Zhe and Wang, Wenhai and Cao, Yue and Liu, Yangzhou and Gao, Zhangwei and Zhu, Jinguo and Zhu, Xizhou and Lu, Lewei and Qiao, Yu and others},
  journal={arXiv preprint arXiv:2411.10442},
  year={2024}
}
```