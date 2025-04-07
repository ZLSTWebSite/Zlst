---
title: 'Collaborative Knowledge Distillation for Heterogeneous Information Network Embedding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - CanWang
  - ShengZhou
  - KangYu
  - DefangChen
  - BolangLi
  - YanFeng
  - ChunChen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-04-25T00:00:00Z'
doi: 'https://doi.org/10.1145/3485447.3512209'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-04-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['knowledge-distillation']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the ACM Web Conference*
publication_short: In *WWW 2022*

abstract: Learning low-dimensional representations for Heterogeneous Information Networks (HINs) has drawn increasing attention recently for its effectiveness in real-world applications. Compared with homogeneous networks, HINs are characterized by meta-paths connecting different types of nodes with semantic meanings. Existing methods mainly follow the prototype of independently learning meta-path-based embeddings and integrating them into a unified embedding. However, meta-paths in a HIN are inherently correlated since they reflect different perspectives of the same object. If each meta-path is treated as an isolated semantic data resource and the correlations among them are disregarded, sub-optimality in the both the meta-path based embedding and final embedding will be resulted. To address this issue, we make the first attempt to explicitly model the correlation among meta-paths by proposing Collaborative Knowledge Distillation for Heterogeneous Information Network Embedding (CKD). More specifically, we model the knowledge in each meta-path with two different granularities, regional knowledge and global knowledge. We learn the meta-path-based embeddings by collaboratively distill the knowledge from intra-meta-path and inter-meta-path simultaneously. Experiments conducted on six real-world HIN datasets demonstrates the effectiveness of the CKD method.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Knowledge Distillation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3485447.3512209'
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
