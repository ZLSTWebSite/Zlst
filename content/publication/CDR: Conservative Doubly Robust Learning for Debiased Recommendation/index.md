---
title: 'CDR: Conservative Doubly Robust Learning for Debiased Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - ZijieSong
  - JiaweiChen
  - ShengZhou
  - QihaoShi
  - YanFeng
  - ChunChen
  - CanWang


# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-01-23T00:00:00Z'
doi: '10.1145/3583780.3614805'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-21T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['recommendation-systems']

# Publication name and optional abbreviated publication name.
publication: 'In *Proceedings of the 32nd ACM International Conference on Information and Knowledge Management*'
publication_short: 'In *CIKM 23*'

abstract: "In recommendation systems (RS), user behavior data is observational rather than experimental, resulting in widespread bias in the data. Consequently, tackling bias has emerged as a major challenge in the field of recommendation systems. Recently, Doubly Robust Learning (DR) has gained significant attention due to its remarkable performance and robust properties. However, our experimental findings indicate that existing DR methods are severely impacted by the presence of so-called Poisonous Imputation, where the imputation significantly deviates from the truth and becomes counterproductive. To address this issue, this work proposes Conservative Doubly Robust strategy (CDR) which filters imputations by scrutinizing their mean and variance. Theoretical analyses show that CDR offers reduced variance and improved tail bounds.In addition, our experimental investigations illustrate that CDR significantly enhances performance and can indeed reduce the frequency of poisonous imputation."


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Recommender Systems, Selection Bias, Doubly Robust]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2308.08461'
url_code: 'https://github.com/crazydumpling/CDR_CIKM2023'
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
