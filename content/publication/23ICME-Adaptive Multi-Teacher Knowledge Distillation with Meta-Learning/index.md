---
title: 'Adaptive Multi-Teacher Knowledge Distillation with Meta-Learning'

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

date: '2023-08-25T00:00:00Z'
doi: '10.1109/ICME55011.2023.00333'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Multimedia and Expo*
publication_short: In *ICME 2023*

abstract: Multi-Teacher knowledge distillation provides students with additional supervision from multiple pre-trained teachers with diverse information sources. Most existing methods explore different weighting strategies to obtain a powerful ensemble teacher, while ignoring the student with poor learning ability may not benefit from such specialized integrated knowledge. To address this problem, we propose Adaptive Multi-teacher Knowledge Distillation with Meta-Learning (MMKD) to supervise student with appropriate knowledge from a tailored ensemble teacher. With the help of a meta-weight network, the diverse yet compatible teacher knowledge in the output layer and intermediate layers is jointly leveraged to enhance the student performance. Extensive experiments on multiple benchmark datasets validate the effectiveness and flexibility of our methods. Code is available at https://github.com/Rorozhl/MMKD.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Knowledge Distillation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2306.06634'
url_code: 'https://github.com/Rorozhl/MMKD'
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
