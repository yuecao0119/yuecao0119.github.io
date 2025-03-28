---
title: "VisualPRM: An Effective Process Reward Model for Multimodal Reasoning"
authors:
- 'Weiyun Wang'
- 'Zhangwei Gao'
- 'Lianjie Chen'
- 'Zhe Chen'
- 'Jinguo Zhu'
- 'Xiangyu Zhao'
- 'Yangzhou Liu'
- admin
- 'Shenglong Ye'
- 'Xizhou Zhu'
- 'Lewei Lu'
- 'Haodong Duan'
- 'Yu Qiao'
- 'Jifeng Dai'
- 'Wenhai Wang'
date: "2025-03-13T12:03:37Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-03-13T12:03:37Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: We introduce VisualPRM, an advanced multimodal Process Reward Model (PRM) with 8B parameters, which improves the reasoning abilities of existing Multimodal Large Language Models (MLLMs) across different model scales and families with Best-of-N (BoN) evaluation strategies. Specifically, our model improves the reasoning performance of three types of MLLMs and four different model scales. Even when applied to the highly capable InternVL2.5-78B, it achieves a 5.9-point improvement across seven multimodal reasoning benchmarks. Experimental results show that our model exhibits superior performance compared to Outcome Reward Models and Self-Consistency during BoN evaluation. To facilitate the training of multimodal PRMs, we construct a multimodal process supervision dataset VisualPRM400K using an automated data pipeline. For the evaluation of multimodal PRMs, we propose VisualProcessBench, a benchmark with human-annotated step-wise correctness labels, to measure the abilities of PRMs to detect erroneous steps in multimodal reasoning tasks. We hope that our work can inspire more future research and contribute to the development of MLLMs. Our model, data, and benchmark are released in https://internvl.github.io/blog/2025-03-13-VisualPRM.

# Summary. An optional shortened abstract.
summary: ''

tags:
  - Multimodal Large Language Models
  - Multimodal Reasoning

featured: true

url_pdf: ''
url_code: 'https://github.com/OpenGVLab/InternVL'
url_dataset: 'https://huggingface.co/datasets/OpenGVLab/VisualPRM400K'
url_project: 'https://internvl.github.io/blog/2025-03-13-VisualPRM'
links:
- name: Model
  url: https://huggingface.co/OpenGVLab/VisualPRM-8B

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
@article{wang2025visualprm,
  title={VisualPRM: An Effective Process Reward Model for Multimodal Reasoning},
  author={Wang, Weiyun and Gao, Zhangwei and Chen, Lianjie and Chen, Zhe and Zhu, Jinguo and Zhao, Xiangyu and Liu, Yangzhou and Cao, Yue and Ye, Shenglong and Zhu, Xizhou and others},
  journal={arXiv preprint arXiv:2503.10291},
  year={2025}
}
```