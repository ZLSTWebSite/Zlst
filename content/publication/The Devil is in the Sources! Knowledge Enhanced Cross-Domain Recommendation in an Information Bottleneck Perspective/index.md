---
title: 'The Devil is in the Sources! Knowledge Enhanced Cross-Domain Recommendation in an Information Bottleneck Perspective'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - BinbinHu
  - WeifanWang
  - ShuhanWang
  - ZiqiLiu
  - BinShen
  - YongHe
  - JiaweiChen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-01-23T00:00:00Z'
doi: '10.1145/3627673.3679595'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-21T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['recommendation-systems']

# Publication name and optional abbreviated publication name.

publication: 'In *Proceedings of the 33rd ACM International Conference on Information and Knowledge Management*'
publication_short: 'In *CIKM 2024*'

abstract: "Cross-domain Recommendation (CDR) aims to alleviate the data sparsity and the cold-start problems in traditional recommender systems by leveraging knowledge from an informative source domain. However, previously proposed CDR models pursue an imprudent assumption that the entire information from the source domain is equally contributed to the target domain, neglecting the evil part that is completely irrelevant to users' intrinsic interest. To address this concern, in this paper, we propose a novel knowledge enhanced cross-domain recommendation framework named CoTrans, which remolds the core procedures of CDR models with: Compression on the knowledge from the source domain and Transfer of the purity to the target domain. Specifically, following the theory of Graph Information Bottleneck, CoTrans first compresses the source behaviors with the perception of information from the target domain. Then to preserve all the important information for the CDR task, the feedback signals from both domains are utilized to promote the effectiveness of the transfer procedure. Additionally, a knowledge-enhanced encoder is employed to narrow gaps caused by the non-overlapped items across separate domains. Comprehensive experiments on three widely used cross-domain datasets demonstrate that CoTrans significantly outperforms both single-domain and state-of-the-art cross-domain recommendation approaches."


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Cross-domain recommendation, Information bottleneck, Graph neural network]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2409.19574'
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
