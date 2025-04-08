---
title: 'Online Cross-Layer Knowledge Distillation on Graph Neural Networks with Deep Supervision'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - JiongyuGuo
  - DefangChen
  - CanWang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-08-08T00:00:00Z'
doi: 'https://doi.org/10.1007/s00521-023-08900-7'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['graph-mining']

# Publication name and optional abbreviated publication name.
publication: In *Neural Computing and Applications*
publication_short: In *NCA 2023*

abstract: Graph neural networks (GNNs) have become one of the most popular research topics in both academia and industry communities for their strong ability in handling irregular graph data. However, large-scale datasets are posing great challenges for deploying GNNs in edge devices with limited resources and model compression techniques have drawn considerable research attention. Existing model compression techniques such as knowledge distillation mainly focus on convolutional neural networks. Only limited attempts have been made recently for distilling knowledge from GNNs in an offline manner. As the performance of the teacher model does not necessarily improve as the number of layers increases in GNNs, selecting an appropriate teacher model will require substantial efforts. To address these challenges, we propose a novel online knowledge distillation framework called Alignahead++ in this paper. Alignahead++ transfers structure and feature information in a student layer to the previous layer of another simultaneously trained student model in an alternating training procedure. Meanwhile, to avoid over-smoothing problem in GNNs, deep supervision is employed in Alignahead++ by adding an auxiliary classifier in each intermediate layer to prevent the collapse of the node feature embeddings. Experimental results on four datasets including PPI, Cora, PubMed and CiteSeer demonstrate that the student performance is consistently boosted in our collaborative training framework without the supervision of a pre-trained teacher model and its effectiveness can generally be improved by increasing the number of students.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Graph Neural Networks]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2210.13743'
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
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
