---
title: 'Alignahead: Online Cross-Layer Knowledge Extraction on Graph Neural Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - JiongyuGuo
  - DefangChen
  - CanWang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-09-30T00:00:00Z'
doi: '10.1109/IJCNN55064.2022.9892159'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-09-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['knowledge-distillation']

# Publication name and optional abbreviated publication name.
publication: In *International Joint Conference on Neural Networks*
publication_short: In *IJCNN 2022*

abstract: Existing knowledge distillation methods on graph neural networks (GNNs) are almost offline, where the student model extracts knowledge from a powerful teacher model to improve its performance. However, a pre-trained teacher model is not always accessible due to training cost, privacy, etc. In this paper, we propose a novel online knowledge distillation framework to resolve this problem. Specifically, each student GNN model learns the extracted local structure from another simultaneously trained counterpart in an alternating training procedure. We further develop a cross-layer distillation strategy by aligning ahead one student layer with the layer in different depth of another student model, which theoretically makes the structure information spread over all layers. Experimental results on five datasets including PPI, Coauthor-CS/Physics and Amazon-Computer/Photo demonstrate that the student performance is consistently boosted in our collaborative training framework without the supervision of a pre-trained teacher model. In addition, we also find that our alignahead technique can accelerate the model convergence speed and its effectiveness can be generally improved by increasing the student numbers in training. Code is available at https://github.com/GuoJY-eatsTG/Alignahead.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Knowledge Distillation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2205.02468'
url_code: 'https://github.com/GuoJY-eatsTG/Alignahead'
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
