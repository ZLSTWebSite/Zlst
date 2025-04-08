---
title: 'Homophily-enhanced Structure Learning for Graph Clustering'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ming Gu
  - Gaoming Yang
  - ShengZhou
  - Ning Ma
  - JiaweiChen
  - Qiaoyu Tan
  - Meihan Liu
  - Jiajun Bu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-01-23T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-05T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['recommendation-systems']

# Publication name and optional abbreviated publication name.
publication: 'In *Proceedings of the 32nd ACM International Conference on Information and Knowledge Management*'
publication_short: 'In *CIKM 23*'

abstract: "Graph clustering is a fundamental task in graph analysis, and recent advances in utilizing graph neural networks (GNNs) have shown impressive results. Despite the success of existing GNN-based graph clustering methods, they often overlook the quality of graph structure, which is inherent in real-world graphs due to their sparse and multifarious nature, leading to subpar performance. Graph structure learning allows refining the input graph by adding missing links and removing spurious connections. However, previous endeavors in graph structure learning have predominantly centered around supervised settings, and cannot be directly applied to our specific clustering tasks due to the absence of ground-truth labels. To bridge the gap, we propose a novel method called homophily-enhanced structure learning for graph clustering (HoLe). Our motivation stems from the observation that subtly enhancing the degree of homophily within the graph structure can significantly improve GNNs and clustering outcomes. To realize this objective, we develop two clustering-oriented structure learning modules, i.e., hierarchical correlation estimation and cluster-aware sparsification. The former module enables a more accurate estimation of pairwise node relationships by leveraging guidance from latent and clustering spaces, while the latter one generates a sparsified structure based on the similarity matrix and clustering assignments. Additionally, we devise a joint optimization approach alternating between training the homophily-enhanced structure learning and GNN-based clustering, thereby enforcing their reciprocal effects. Extensive experiments on seven benchmark datasets of various types and scales, across a range of clustering metrics, demonstrate the superiority of HoLe against state-of-the-art baselines."


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Graph Clustering, Graphs Structure Learning, Graph Neural Networks]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2308.05309'
url_code: 'https://github.com/galogm/HoLe'
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
