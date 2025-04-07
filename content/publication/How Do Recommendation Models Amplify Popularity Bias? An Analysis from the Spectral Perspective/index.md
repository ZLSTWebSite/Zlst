---
title: 'How Do Recommendation Models Amplify Popularity Bias? An Analysis from the Spectral Perspective'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - SiyiLin
  - ChongmingGao
  - JiaweiChen
  - ShengZhou
  - BinbinHu
  - YanFeng
  - ChunChen
  - CanWang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-01-23T00:00:00Z'
doi: '10.1145/3701551.3703579'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-03-10T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['recommendation-systems']

# Publication name and optional abbreviated publication name.
publication: 'In *ACM Transactions on Information Systems*'
publication_short: 'In *TOIS 2024*'

abstract: 'Recommendation Systems (RS) are often plagued by popularity bias. When training a recommendation model on a typically long-tailed dataset, the model tends to not only inherit this bias but often exacerbate it, resulting in over-representation of popular items in the recommendation lists. This study conducts comprehensive empirical and theoretical analyses to expose the root causes of this phenomenon, yielding two core insights: 1) Item popularity is memorized in the principal spectrum of the score matrix predicted by the recommendation model; 2) The dimension reduction phenomenon amplifies the relative prominence of the principal spectrum, thereby intensifying the popularity bias. Building on these insights, we propose a novel debiasing strategy that leverages a spectral norm regularizer to penalize the magnitude of the principal singular value. We have developed an efficient algorithm to expedite the calculation of the spectral norm by exploiting the spectral property of the score matrix. Extensive experiments across seven real-world datasets and three testing paradigms have been conducted to validate the superiority of the proposed method.'


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Recommender System, Popularity Bias]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2404.12008'
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
