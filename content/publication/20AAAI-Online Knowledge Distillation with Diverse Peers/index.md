---
title: 'Online Knowledge Distillation with Diverse Peers'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - DefangChen
  - JianpingMei
  - CanWang
  - YanFeng
  - ChunChen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2020-04-03T00:00:00Z'
doi: 'https://doi.org/10.1609/aaai.v34i04.5746'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-04-03T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the AAAI Conference on Artificial Intelligence*
publication_short: In *AAAI 2020*

abstract: Distillation is an effective knowledge-transfer technique that uses predicted distributions of a powerful teacher model as soft targets to train a less-parameterized student model. A pre-trained high capacity teacher, however, is not always available. Recently proposed online variants use the aggregated intermediate predictions of multiple student models as targets to train each student model. Although group-derived targets give a good recipe for teacher-free distillation, group members are homogenized quickly with simple aggregation functions, leading to early saturated solutions. In this work, we propose Online Knowledge Distillation with Diverse peers (OKDDip), which performs two-level distillation during training with multiple auxiliary peers and one group leader. In the first-level distillation, each auxiliary peer holds an individual set of aggregation weights generated with an attention-based mechanism to derive its own targets from predictions of other auxiliary peers. Learning from distinct target distributions helps to boost peer diversity for effectiveness of group-based distillation. The second-level distillation is performed to transfer the knowledge in the ensemble of auxiliary peers further to the group leader, i.e., the model used for inference. Experimental results show that the proposed framework consistently gives better performance than state-of-the-art approaches without sacrificing training or inference complexity, demonstrating the effectiveness of the proposed two-level distillation framework.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Knowledge Distillation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/1912.00350'
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
