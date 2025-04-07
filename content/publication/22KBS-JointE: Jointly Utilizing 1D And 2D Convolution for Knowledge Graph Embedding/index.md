---
title: 'JointE: Jointly Utilizing 1D And 2D Convolution for Knowledge Graph Embedding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - ZheHuiZhou
  - CanWang
  - YanFeng
  - DefangChen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-03-15T00:00:00Z'
doi: 'https://doi.org/10.1016/j.knosys.2021.108100'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-03-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Knowledge-Based Systems*
publication_short: In *KBS 2022*

abstract: Knowledge graph embedding is a popular method to predict missing links for knowledge graphs by projecting entities and relations into continuous low-dimension embeddings. Some recent embedding models employ translation-based operations to learn the representations of entities and relations with shallow and linear structures, and others leverage neural networks, especially convolution neural networks, to embed the entities and relations with deep and non-linear structures. However, shallow and linear models limit the extraction capacity of the latent knowledge while deep and non-linear models lead to the overabundance of parameters and the loss of surface and explicit knowledge. In this paper, we propose JointE, which utilizes 1D and 2D convolution operations jointly to alleviate these issues effectively. More specifically, we utilize 2D convolution operations to facilitate the interactions between entities and relations, thereby capturing the latent knowledge sufficiently. To reduce the number of parameters significantly, we innovatively construct 2D convolution filters from internal embeddings rather than using external filters which costs plenty of redundant parameters. Furthermore, we appropriately employ 1D convolution filters over input embeddings to extract the surface and explicit knowledge and preserve it by element-wise addition. Experimental evaluation on five benchmark datasets demonstrates that our model outperforms all other state-of-the-art convolution-based models and simultaneously enhances the parameter efficiency.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Knowledge Graph Embedding]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S0950705121011643'
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
