---
title: 'Holistic Weighted Distillation for Semantic Segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - WujieSun
  - DefangChen
  - CanWang
  - DeshiYe
  - YanFeng
  - ChunChen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-08-25T00:00:00Z'
doi: '10.1109/ICME55011.2023.00075'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['knowledge-distillation']

# Publication name and optional abbreviated publication name.
publication: 'In *International Conference on Multimedia and Expo 2023*'
publication_short: 'In *ICME 2023*'

abstract: 'Channel-wise distillation for semantic segmentation has proven to be a more effective method than spatial-based distillation. By removing the redundant information from the teacher model, the student can focus on specific channel-related pixels, which can be viewed as a weighting of the pixels. However, the standard channel-wise distillation ignores the fact that such importance difference also exists among channels. In this paper, we propose a novel method called Holistic Weighted Distillation (HWD) to address this issue. We calculate the channel divergences between the teacher and the student, and convert them into distillation weights, making the student focus more on learning channels that are not well mastered, thus improving the final model performance. Besides, our method does not introduce additional network structure or back-propagation process, which improves the training efficiency. Experiments on ADE20K, Cityscapes, and COCO-Stuff demonstrate the superiority of our method. The code is available at https://github.com/zju-SWJ/HWD.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Knowledge Distillation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10220035'
url_code: 'https://github.com/zju-SWJ/HWD'
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
