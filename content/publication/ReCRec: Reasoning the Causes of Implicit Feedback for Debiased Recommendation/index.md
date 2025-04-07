---
title: 'ReCRec: Reasoning the Causes of Implicit Feedback for Debiased Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - SiyiLin
  - ShengZhou
  - JiaweiChen
  - YanFeng
  - QihaoShi
  - ChunChen
  - YingLi
  - CanWang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-01-23T00:00:00Z'
doi: '10.1145/3672275'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-18T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['recommendation-systems']

# Publication name and optional abbreviated publication name.

publication: 'In *ACM Transactions on Information Systems*'
publication_short: 'In *TOIS 2024*'

abstract: "Implicit feedback (e.g., user clicks) is widely used in building recommender systems (RS). However, the inherent notorious exposure bias significantly affects recommendation performance. Exposure bias refers a phenomenon that implicit feedback is influenced by user exposure and does not precisely reflect user preference. Current methods for addressing exposure bias primarily reduce confidence in unclicked data, employ exposure models, or leverage propensity scores. Regrettably, these approaches often lead to biased estimations or elevated model variance, yielding sub-optimal results. To overcome these limitations, we propose a new method ReCRec that Reasons the Causes behind the implicit feedback for debiased Recommendation. ReCRec identifies three scenarios behind unclicked data—i.e., unexposed, dislike, or a combination of both. A reasoning module is employed to infer the category to which each instance pertains. Consequently, the model is capable of extracting reliable positive and negative signals from unclicked data, thereby facilitating more accurate learning of user preferences. We also conduct thorough theoretical analyses to demonstrate the debiased nature and low variance of ReCRec. Extensive experiments on both semi-synthetic and real-world datasets validate its superiority over state-of-the-art methods."


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Debias, recommendation, implicit feedback]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3672275'
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
