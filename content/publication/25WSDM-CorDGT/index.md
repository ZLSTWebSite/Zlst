---
title: 'Dynamic Graph Transformer with Correlated Spatial-Temporal Positional Encoding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - ZheWang
  - ShengZhou
  - JiaweiChen
  - ZhenZhang
  - BinbinHu
  - YanFeng
  - ChunChen
  - CanWang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-03-10T00:00:00Z'
doi: '10.1145/3701551.3703489'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-03-10T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['graph-mining']

# Publication name and optional abbreviated publication name.
publication: 'In *Proceedings of the Eighteenth ACM International Conference on Web Search and Data Mining*'
publication_short: 'In *WSDM 2025*'

abstract: 'Learning effective representations for Continuous-Time Dynamic Graphs (CTDGs) has garnered significant research interest, largely due to its powerful capabilities in modeling complex interactions between nodes. A fundamental and crucial requirement for representation learning in CTDGs is the appropriate estimation and preservation of proximity. However, due to the sparse and evolving characteristics of CTDGs, the spatial-temporal properties inherent in high-order proximity remain largely unexplored. Despite its importance, this property presents significant challenges due to the computationally intensive nature of personalized interaction intensity estimation and the dynamic attributes of CTDGs. To this end, we propose a novel Correlated Spatial-Temporal Positional encoding that incorporates a parameter-free personalized interaction intensity estimation under the weak assumption of the Poisson Point Process. Building on this, we introduce the Dynamic Graph Transformer with Correlated Spatial-Temporal Positional Encoding (CorDGT), which efficiently retains the evolving spatial-temporal high-order proximity for effective node representation learning in CTDGs. Extensive experiments on seven small and two large-scale datasets demonstrate the superior performance and scalability of the proposed CorDGT. The code is available at: https://github.com/wangz3066/CorDGT.'


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Continuous-Time Dynamic Graph, Graph Representation Learning, Transformer, Proximity]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3701551.3703489'
url_code: 'https://github.com/wangz3066/CorDGT'
url_dataset: 'https://github.com/wangz3066/CorDGT'
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
