---
title: 'On the Effectiveness of Sampled Softmax Loss for Item Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - JiancanWu
  - XiangWang
  - XingyuGao
  - JiaweiChen
  - HongchengFu
  - TianyuQiu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-01-23T00:00:00Z'
doi: '10.1145/3637061'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-3-22T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['recommendation-systems']

# Publication name and optional abbreviated publication name.
publication: 'In *ACM Transactions on Information Systems*'
publication_short: 'In *TOIS*'

abstract: 'The learning objective plays a fundamental role to build a recommender system. Most methods routinely adopt either pointwise (e.g., binary cross-entropy) or pairwise (e.g., BPR) loss to train the model parameters, while rarely pay attention to softmax loss, which assumes the probabilities of all classes sum up to 1, due to its computational complexity when scaling up to large datasets or intractability for streaming data where the complete item space is not always available. The sampled softmax (SSM) loss emerges as an efficient substitute for softmax loss. Its special case, InfoNCE loss, has been widely used in self-supervised learning and exhibited remarkable performance for contrastive learning. Nonetheless, limited recommendation work uses the SSM loss as the learning objective. Worse still, none of them explores its properties thoroughly and answers “Does SSM loss suit for item recommendation?” and “What are the conceptual advantages of SSM loss, as compared with the prevalent losses?”, to the best of our knowledge. In this work, we aim at offering a better understanding of SSM for item recommendation. Specifically, we first theoretically reveal three model-agnostic advantages: (1) mitigating popularity bias, which is beneficial to long-tail recommendation; (2) mining hard negative samples, which offers informative gradients to optimize model parameters; and (3) maximizing the ranking metric, which facilitates top-K performance. However, based on our empirical studies, we recognize that the default choice of cosine similarity function in SSM limits its ability in learning the magnitudes of representation vectors. As such, the combinations of SSM with the models that also fall short in adjusting magnitudes (e.g., matrix factorization) may result in poor representations. One step further, we provide mathematical proof that message passing schemes in graph convolution networks can adjust representation magnitude according to node degree, which naturally compensates for the shortcoming of SSM. Extensive experiments on four benchmark datasets justify our analyses, demonstrating the superiority of SSM for item recommendation. Our implementations are available in both TensorFlow and PyTorch.'


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Sampled softmax loss, collaborative filtering, graph neural networks, long-tail recommendation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2201.02327'
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
