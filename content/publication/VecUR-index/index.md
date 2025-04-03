---
title: 'Fast Query Answering by Labeling Index on Uncertain Graphs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - ZeyuWang
  - QihaoShi
  - JiaweiChen
  - CanWang
  - MingliSong
  - XinyuWang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-07-23T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-23T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['graph-mining']

# Publication name and optional abbreviated publication name.
publication: In *2024 IEEE 40th International Conference on Data Engineering (ICDE)*
publication_short: In *ICDE*

abstract: Given the ubiquity of Uncertain Graphs (UGs), the field of UG mining has garnered increasing attention. Among various mining tasks, query processing stands out as the most fundamental and crucial. Current methods for query answering on UGs primarily rely on Monte-Carlo sampling and heuristic approaches. However, these techniques either struggle with a significant efficiency-accuracy trade-off or lack generalization over different graphs and queries. To circumvent these limitations, this work proposes a novel index-based method for query answering on UGs. We construct a labeling index framework, which can answer queries by pre-computed and stored operators. To the best of our knowledge, this is the first index frame-work that can deal with reliability, expected reliable distance and distance-constrained reliability queries, providing lower or upper bounded query answer results. By transferring the time consuming sampling process into the offline index operator computation, the query answering only needs to traverse a limited number of operators, which accelerates the response time of query answering with several orders of magnitude. We further utilize the vertex cover and its h-hop extension to prune the index structure, thereby reducing the space complexity. Experimental results on five real-world datasets demonstrate that the proposed index framework is both effective and efficient.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Uncertain graph, Labeling index, Query answer- ing, Reliability]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10597788'
url_code: 'https://github.com/wangzeyu777/uncertainIndex'
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
