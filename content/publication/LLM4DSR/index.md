---
title: 'LLM4DSR: Leveraging Large Language Model for Denoising Sequential Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - BohaoWang
  - FengLiu
  - ChangwangZhang
  - JiaweiChen
  - YudiWu
  - ShengZhou
  - XingyuLou
  - JunWang
  - YanFeng
  - ChunChen
  - CanWang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-10-14T00:00:00Z'
doi: '10.1145/3762182'


# Schedule page publish date (NOT publication's date).
publishDate: '2025-10-14T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['recommendation-systems']

# Publication name and optional abbreviated publication name.
publication: 'In *ACM Transactions on Information Systems*'
publication_short: 'In *TOIS 2025*'

abstract: 'Sequential recommenders generate recommendations based on users’ historical interaction sequences. However, in practice, these sequences are often contaminated by noisy interactions, which can arise from various factors such as clickbait, the influence of prominently positioned items, or accidental interactions. Such noise can significantly degrade recommendation performance. Accurately identifying such noisy interactions without additional information is particularly challenging due to the absence of explicit supervisory signals indicating noise. Large Language Models (LLMs), equipped with extensive open knowledge and semantic reasoning abilities, offer a promising avenue to bridge this information gap. However, employing LLMs for denoising in sequential recommendation presents notable challenges: (1) Direct application of pretrained LLMs may not be competent for the denoising task, frequently generating nonsensical responses; (2) Fine-tuning on the denoising task can partially mitigate the issue of generating nonsensical outputs. However, even after fine-tuning, the reliability of LLM outputs remains questionable, especially given the complexity of the denoising task and the inherent hallucination issue of LLMs. To tackle these challenges, we propose LLM4DSR, a tailored approach for denoising sequential recommendation using LLMs. We constructed a self-supervised fine-tuning task to activate LLMs’ capabilities to identify noisy items and suggest replacements. Furthermore, we developed an uncertainty estimation module that ensures only high-confidence responses are utilized for sequence corrections. Remarkably, LLM4DSR is model-agnostic, allowing corrected sequences to be flexibly applied across various recommendation models. To the best of our knowledge, this is the first work that employs LLMs for sequential recommendation denoising while addressing the unique challenges of adapting LLMs to this task. Extensive experiments conducted on three real-world datasets across two noise settings validate the effectiveness of LLM4DSR, demonstrating an average improvement of 12.9% in NDCG@20. The code is available at https://github.com/WANGBohaO-jpg/LLM4DSR.'


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Sequential Recommendation, Denoise, Large Language Model]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2408.08208'
url_code: 'https://github.com/WANGBohaO-jpg/LLM4DSR'
url_dataset: 'https://github.com/WANGBohaO-jpg/LLM4DSR'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
