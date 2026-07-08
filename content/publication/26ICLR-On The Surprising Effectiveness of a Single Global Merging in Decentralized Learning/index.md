---
title: 'On The Surprising Effectiveness of a Single Global Merging in Decentralized Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tongtian Zhu
  - Tianyu Zhang
  - Mingze Wang
  - Zhanpeng Zhou
  - Can Wang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-04-23T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-04-23T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['decentralized-learning']

# Publication name and optional abbreviated publication name.
publication: 'In *Proceedings of The Fourteenth International Conference on Learning Representations*'
publication_short: 'In *ICLR 2026 (Oral Presentation, Top 1.2%)*'

abstract: 'Decentralized learning provides a scalable alternative to parameter-server-based training, yet its performance is often hindered by limited peer-to-peer communication. In this paper, we study how communication should be scheduled over time to improve global generalization, including determining when and how frequently devices synchronize. Counterintuitive empirical results show that concentrating communication budgets in the later stages of decentralized training remarkably improves global generalization. Surprisingly, we uncover that fully connected communication at the final step, implemented by a single global merging, can significant improve the generalization performance of decentralized learning under serve high data heterogeneity. Our theoretical contributions, which explains these phenomena, are first to establish that the globally merged model of decentralized SGD can match the convergence rate of parallel SGD. Technically, we reinterpret part of the discrepancy among local models, which were previously considered as detrimental noise, as constructive components essential for matching this rate. This work provides promising results that decentralized learning is able to generalize under high data heterogeneity and limited communication, while offering broad new avenues for model merging research.'


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Decentralized learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/forum?id=zrFnwRHuQo'
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
