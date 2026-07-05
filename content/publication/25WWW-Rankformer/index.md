---
title: 'Rankformer: A Graph Transformer for Recommendation based on Ranking Objective'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - SiruiChen
  - ShenHan
  - JiaweiChen
  - BinbinHu
  - ShengZhou
  - GangWang
  - YanFeng
  - ChunChen
  - CanWang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-04-28T00:00:00Z'
doi: '10.1145/3696410.3714547'


# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-28T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['recommendation-systems']

# Publication name and optional abbreviated publication name.
publication: 'In *Proceedings of the ACM Web Conference 2025*'
publication_short: 'In *WWW 2025*'

abstract: 'Recommender Systems (RS) aim to generate personalized ranked lists for each user and are evaluated using ranking metrics. Although personalized ranking is a fundamental aspect of RS, this critical property is often overlooked in the design of model architectures. To address this issue, we propose Rankformer, a ranking-inspired recommendation model. The architecture of Rankformer is inspired by the gradient of the ranking objective, embodying a unique (graph) transformer architecture -- it leverages global information from all users and items to produce more informative representations and employs specific attention weights to guide the evolution of embeddings towards improved ranking performance. We further develop an acceleration algorithm for Rankformer, reducing its complexity to a linear level with respect to the number of positive instances. Extensive experimental results demonstrate that Rankformer outperforms state-of-the-art methods. The code is available at https://github.com/StupidThree/Rankformer.'


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Sign-aware Recommendation, Graph, Transformer]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2503.16927'
url_code: 'https://github.com/StupidThree/Rankformer'
url_dataset: 'https://github.com/StupidThree/Rankformer'
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
