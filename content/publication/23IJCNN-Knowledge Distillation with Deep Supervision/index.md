---
title: 'Knowledge Distillation with Deep Supervision'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - ShiyaLuo
  - DefangChen
  - CanWang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-08-02T00:00:00Z'
doi: '10.1109/IJCNN54540.2023.10191309'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Joint Conference on Neural Networks*
publication_short: In *IJCNN 2023*

abstract: Knowledge distillation aims to enhance the performance of a lightweight student model by exploiting the knowledge from a pre-trained cumbersome teacher model. However, in the traditional knowledge distillation, teacher predictions are only used to provide the supervisory signal for the last layer of the student model, which may result in those shallow student layers lacking accurate training guidance in the layer-by-layer back propagation and thus hinders effective knowledge transfer. To address this issue, we propose Deeply-Supervised Knowledge Distillation (DSKD), which fully utilizes class predictions and feature maps of the teacher model to supervise the training of shallow student layers. A loss-based weight allocation strategy is developed in DSKD to adaptively balance the learning process of each shallow layer, so as to further improve the student performance. Extensive experiments on CIFAR-100 and TinyImageNet with various teacher-student models show significantly performance, confirming the effectiveness of our proposed method. Code is available at https://github.com/luoshiya/DSKD.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Knowledge Distillation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2202.07846'
url_code: 'https://github.com/luoshiya/DSKD'
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
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
