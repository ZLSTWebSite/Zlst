---
title: 'Distributionally Robust Graph-based Recommendation System'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 王博浩
  - 陈佳伟
  - 李昌栋
  - 周晟
  - 史麒豪
  - 冯雁
  - 陈纯
  - 王灿

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-1-23T00:00:00Z'
doi: '10.1145/3589334.3645598'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-5-13T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'In *Proceedings of the ACM Web Conference 2024*'
publication_short: 'In *WWW 2024*'

abstract: 'With the capacity to capture high-order collaborative signals, Graph Neural Networks (GNNs) have emerged as powerful methods in Recommender Systems (RS). However, their efficacy often hinges on the assumption that training and testing data share the same distribution (a.k.a. IID assumption), and exhibits significant declines under distribution shifts. Distribution shifts commonly arises in RS, often attributed to the dynamic nature of user preferences or ubiquitous biases during data collection in RS. Despite its significance, researches on GNN-based recommendation against distribution shift are still sparse. To bridge this gap, we propose Distributionally Robust GNN (DR-GNN) that incorporates Distributional Robust Optimization (DRO) into the GNN-based recommendation. DR-GNN addresses two core challenges: 1) To enable DRO to cater to graph data intertwined with GNN, we reinterpret GNN as a graph smoothing regularizer, thereby facilitating the nuanced application of DRO; 2) Given the typically sparse nature of recommendation data, which might impede robust optimization, we introduce slight perturbations in the training distribution to expand its support. Notably, while DR-GNN involves complex optimization, it can be implemented easily and efficiently. Our extensive experiments validate the effectiveness of DR-GNN against three typical distribution shifts. The code is available at https://github.com/WANGBohaO-jpg/DR-GNN.'


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Graph Recommendation, Out of Distribution, Robust]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2411.00163'
url_code: 'https://github.com/WANGBohaO-jpg/DR-GNN'
url_dataset: 'https://github.com/WANGBohaO-jpg/DR-GNN'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://dl.acm.org/doi/suppl/10.1145/3589334.3645598/suppl_file/rfp1717.mp4'

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
