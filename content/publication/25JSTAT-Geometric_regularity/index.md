---
title: 'Geometric Regularity in Deterministic Sampling Dynamics of Diffusion-Based Generative Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - DefangChen
  - ZhenyuZhou
  - CanWang
  - SiweiLyu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-12-08T00:00:00Z'
doi: '10.1088/1742-5468/ae17ac'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-12-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['diffusion-models']

# Publication name and optional abbreviated publication name.
publication: 'In *Journal of Statistical Mechanics: Theory and Experiment*'
publication_short: In *JSTAT*

abstract: "Diffusion-based generative models employ stochastic differential equations and their equivalent probability flow ordinary differential equations to establish a smooth transformation between complex high-dimensional data distributions and tractable prior distributions. In this paper, we reveal a striking geometric regularity in the deterministic sampling dynamics of diffusion generative models: each simulated sampling trajectory along the gradient field lies within an extremely low-dimensional subspace, and all trajectories exhibit an almost identical ‘boomerang’ shape, regardless of the model architecture, applied conditions, or generated content. We characterize several intriguing properties of these trajectories, particularly under closed-form solutions based on kernel-estimated data modeling. We also demonstrate a practical application of the discovered trajectory regularity by proposing a dynamic programming-based scheme to better align the sampling time schedule with the underlying trajectory structure. This simple strategy requires minimal modification to existing deterministic numerical solvers, incurs negligible computational overhead, and achieves superior image generation performance, especially in regions with only 5–10 function evaluations."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Diffusion Models, Regularity]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://iopscience.iop.org/article/10.1088/1742-5468/ae17ac/meta'
url_code: 'https://github.com/zju-pi/diff-sampler'
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
