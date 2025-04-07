---
title: 'Confidence-Aware Multi-Teacher Knowledge Distillation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - HailinZhang
  - DefangChen
  - CanWang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-04-22T00:00:00Z'
doi: '10.1109/ICASSP43922.2022.9747534'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-04-22T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['knowledge-distillation']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Acoustics, Speech and Signal Processing*
publication_short: In *ICASSP 2022*

abstract: Knowledge distillation is initially introduced to utilize additional supervision from a single teacher model for the student model training. To boost the student performance, some recent variants attempt to exploit diverse knowledge sources from multiple teachers. However, existing studies mainly integrate knowledge from diverse sources by averaging over multiple teacher predictions or combining them using other various label-free strategies, which may mislead student in the presence of low-quality teacher predictions. To tackle this problem, we propose Confidence-Aware Multi-teacher Knowledge Distillation (CA-MKD), which adaptively assigns sample-wise reliability for each teacher prediction with the help of ground-truth labels, with those teacher predictions close to one-hot labels assigned large weights. Besides, CA-MKD incorporates intermediate layers to stable the knowledge transfer process. Extensive experiments show that our CA-MKD consistently outperforms all compared state-of-the-art methods across various teacher-student architectures.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Knowledge Distillation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2201.00007'
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
