---
title: 'Expanding Performance Boundaries of Open-Source Multimodal Models with Model, Data, and Test-Time Scaling'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 'Zhe Chen'
  - 'Weiyun Wang'
  - admin
  - 'Yangzhou Liu'
  - 'Zhangwei Gao'
  - 'Erfei Cui'
  - 'Jinguo Zhu'
  - 'Shenglong Ye'
  - 'Hao Tian'
  - 'Zhaoyang Liu'
  - 'Lixin Gu'
  - 'Xuehui Wang'
  - 'Qingyun Li'
  - 'Yimin Ren'
  - 'Zixuan Chen'
  - 'Jiapeng Luo'
  - 'Jiahao Wang'
  - 'Tan Jiang'
  - 'Bo Wang'
  - 'Conghui He'
  - 'Botian Shi'
  - 'Xingcheng Zhang'
  - 'Han Lv'
  - 'Yi Wang'
  - 'Wenqi Shao'
  - 'Pei Chu'
  - 'Zhongying Tu'
  - 'Tong He'
  - 'Zhiyong Wu'
  - 'Huipeng Deng'
  - 'Jiaye Ge'
  - 'Kai Chen'
  - 'Kaipeng Zhang'
  - 'Limin Wang'
  - 'Min Dou'
  - 'Lewei Lu'
  - 'Xizhou Zhu'
  - 'Tong Lu'
  - 'Dahua Lin'
  - 'Yu Qiao'
  - 'Jifeng Dai'
  - 'Wenhai Wang'

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-12-06T18:57:08Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-06T18:57:08Z'

# Publication type. paper-conference
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: '' # In *Hugo Blox Builder Conference*
publication_short: '' # In *ICW*

abstract: We introduce InternVL 2.5, an advanced multimodal large language model (MLLM) series that builds upon InternVL 2.0, maintaining its core model architecture while introducing significant enhancements in training and testing strategies as well as data quality. In this work, we delve into the relationship between model scaling and performance, systematically exploring the performance trends in vision encoders, language models, dataset sizes, and test-time configurations. Through extensive evaluations on a wide range of benchmarks, including multi-discipline reasoning, document understanding, multi-image / video understanding, real-world comprehension, multimodal hallucination detection, visual grounding, multilingual capabilities, and pure language processing, InternVL 2.5 exhibits competitive performance, rivaling leading commercial models such as GPT-4o and Claude-3.5-Sonnet. Notably, our model is the first open-source MLLMs to surpass 70% on the MMMU benchmark, achieving a 3.7-point improvement through Chain-of-Thought (CoT) reasoning and showcasing strong potential for test-time scaling. We hope this model contributes to the open-source community by setting new standards for developing and applying multimodal AI systems. HuggingFace demo see https://huggingface.co/spaces/OpenGVLab/InternVL.

# Summary. An optional shortened abstract.
summary: ''

tags:
  - Multimodal Large Language Models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/OpenGVLab/InternVL'
url_dataset: 'https://huggingface.co/collections/OpenGVLab/internvl-data-66ed4917fcc1c455f837b8e2'
url_project: 'https://internvl.github.io/'
url_slides: 'https://internvl.github.io/files/internvl_slides_chinese.pdf'
links:
- name: Demo
  url: https://internvl.opengvlab.com/
- name: HuggingFace
  url: https://huggingface.co/collections/OpenGVLab/internvl25-673e1019b66e2218f68d7c1c

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overall architecture.'
  focal_point: ''
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

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->




### Citation

If you find this project useful in your research, please consider cite:

```BibTeX
@article{chen2024expanding,
  title={Expanding performance boundaries of open-source multimodal models with model, data, and test-time scaling},
  author={Chen, Zhe and Wang, Weiyun and Cao, Yue and Liu, Yangzhou and Gao, Zhangwei and Cui, Erfei and Zhu, Jinguo and Ye, Shenglong and Tian, Hao and Liu, Zhaoyang and others},
  journal={arXiv preprint arXiv:2412.05271},
  year={2024}
}
```