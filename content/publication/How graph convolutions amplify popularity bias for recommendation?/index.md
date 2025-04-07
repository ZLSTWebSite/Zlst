---
title: 'How graph convolutions amplify popularity bias for recommendation?'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - JiajiaChen
  - JiancanWu
  - JiaweiChen
  - XinXin
  - YongLi
  - XiangnanHe

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-01-23T00:00:00Z'
doi: '10.1007/s11704-023-2655-2'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-23T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['recommendation-systems']

# Publication name and optional abbreviated publication name.
publication: 'Frontiers of Computer Science'
publication_short: 'FCS'

abstract: 'Graph convolutional networks (GCNs) have become prevalent in recommender system (RS) due to their superiority in modeling collaborative patterns. Although improving the overall accuracy, GCNs unfortunately amplify popularity bias — tail items are less likely to be recommended. This effect prevents the GCN-based RS from making precise and fair recommendations, decreasing the effectiveness of recommender systems in the long run. In this paper, we investigate how graph convolutions amplify the popularity bias in RS. Through theoretical analyses, we identify two fundamental factors: (1) with graph convolution (i.e., neighborhood aggregation), popular items exert larger influence than tail items on neighbor users, making the users move towards popular items in the representation space; (2) after multiple times of graph convolution, popular items would affect more high-order neighbors and become more influential. The two points make popular items get closer to almost users and thus being recommended more frequently. To rectify this, we propose to estimate the amplified effect of popular nodes on each node’s representation, and intervene the effect after each graph convolution. Specifically, we adopt clustering to discover highly-influential nodes and estimate the amplification effect of each node, then remove the effect from the node embeddings at each graph convolution layer. Our method is simple and generic — it can be used in the inference stage to correct existing models rather than training a new model from scratch, and can be applied to various GCN models. We demonstrate our method on two representative GCN backbones LightGCN and UltraGCN, verifying its ability in improving the recommendations of tail items without sacrificing the performance of popular items. Codes are open-sourced.'


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [recommendation, graph convolution networks, popularity bias]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2305.14886'
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
