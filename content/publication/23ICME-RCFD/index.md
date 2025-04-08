---
title: 'Accelerating Diffusion Sampling with Classifier-based Feature Distillation'

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
doi: '10.1109/ICME55011.2023.00144'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['knowledge-distillation']

# Publication name and optional abbreviated publication name.
publication: 'In *International Conference on Multimedia and Expo 2023*'
publication_short: 'In *ICME 2023*'

abstract: 'Although diffusion model has shown great potential for generating higher quality images than GANs, slow sampling speed hinders its wide application in practice. Progressive distillation is thus proposed for fast sampling by progressively aligning output images of N-step teacher sampler with N/2-step student sampler. In this paper, we argue that this distillation-based accelerating method can be further improved, especially for few-step samplers, with our proposed Classifier-based Feature Distillation (CFD). Instead of aligning output images, we distill teacher’s sharpened feature distribution into the student with a dataset-independent classifier, making the student focus on those important features to improve performance. We also introduce a dataset-oriented loss to further optimize the model. Experiments on CIFAR-10 show the superiority of our method in achieving high quality and fast sampling. Code is available at https://github.com/zju-SWJ/RCFD.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Knowledge Distillation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10219693'
url_code: 'https://github.com/zju-SWJ/RCFD'
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
