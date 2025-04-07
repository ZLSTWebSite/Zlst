---
title: 'Online Adversarial Knowledge Distillation for Graph Neural Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - CanWang
  - ZheWang
  - DefangChen
  - ShengZhou
  - YanFeng
  - ChunChen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-03-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.eswa.2023.121671'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Expert Systems with Applications*
publication_short: In *ESA 2024*

abstract: Knowledge distillation, a technique recently gaining popularity for enhancing model generalization in Convolutional Neural Networks (CNNs), operates under the assumption that both teacher and student models are trained on identical data distributions. However, its effect on Graph Neural Networks (GNNs) is less than satisfactory since the graph topology and node attributes are prone to evolve, thereby leading to the issue of distribution shift. In this paper, we tackle this challenge by simultaneously training a group of graph neural networks in an online distillation fashion, where the group knowledge plays a role as a dynamic virtual teacher and the structure changes in graph neural networks are effectively captured. To improve the distillation performance, two types of knowledge are transferred among the students to enhance each other, local knowledge reflecting information in the graph topology and node attributes, and global knowledge reflecting the prediction over classes. We transfer the global knowledge with KL-divergence as the vanilla knowledge distillation does, while exploiting the complicated structure of the local knowledge with an efficient adversarial cyclic learning framework. Extensive experiments verified the effectiveness of our proposed online adversarial distillation approach. The code is published at https://github.com/wangz3066/OnlineDistillGCN.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Knowledge Distillation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S0957417423021735'
url_code: 'https://github.com/wangz3066/OnlineDistillGCN'
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
