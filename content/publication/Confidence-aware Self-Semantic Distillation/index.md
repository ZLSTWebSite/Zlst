---
title: 'Confidence-aware Self-Semantic Distillation on Knowledge Graph Embedding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 刘一辰
  - 陈佳伟
  - 冯雁
  - 王灿

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-10-21T00:00:00Z'
doi: '10.1145/3627673.3679683'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Conference on Information and Knowledge Management*
publication_short: In *CIKM*

abstract: Knowledge Graph Embedding (KGE), which projects entities and relations into continuous vector spaces, has garnered significant attention. Although high-dimensional KGE methods offer better performance, they come at the expense of significant computation and memory overheads. Decreasing embedding dimensions significantly deteriorates model performance. While several recent efforts utilize knowledge distillation or non-Euclidean representation learning to augment the effectiveness of low-dimensional KGE, they either necessitate a pre-trained high-dimensional teacher model or involve complex non-Euclidean operations, thereby incurring considerable additional computational costs. To address this, this work proposes Confidence-aware Self-Knowledge Distillation (CSD) that learns from the model itself to enhance KGE in a low-dimensional space. Specifically, CSD extracts knowledge from embeddings in previous iterations, which would be utilized to supervise the learning of the model in the next iterations. Moreover, a specific semantic module is developed to filter reliable knowledge by estimating the confidence of previously learned embeddings. This straightforward strategy bypasses the need for time-consuming pre-training of teacher models and can be integrated into various KGE methods to improve their performance. Our comprehensive experiments on six KGE backbones and four datasets underscore the effectiveness of the proposed CSD.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Knowledge Graph Embedding, Knowledge Distillation, Confidence, Self-distillation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2206.02963v2'
url_code: ''
url_dataset: ''
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
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
