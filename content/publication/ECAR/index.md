---
title: 'Ensemble clustering with attentional representation'

# 作者名单，使用拼音填写
authors:
  - ZhezhengHao
  - ZhouminLu
  - GuoxuLi
  - FeipingNie
  - RongWang
  - XuelongLi

  
# 填写发表日期
date: '2023-07-23T00:00:00Z'
doi: '10.1109/TKDE.2023.3292573'

# 填写同样的日期
publishDate: '2023-07-23T00:00:00Z'

# 填写论文研究方向，可选项："recommendation-systems, graph-mining, diffusion-models, knowledge-distillation"
publication_types: ['graph-mining']

# 发表的会议/期刊全称与简称
publication: 'IEEE Transactions on Knowledge and Data Engineering'
publication_short: 'TKDE 2023'

# 英文摘要
abstract: 'Ensemble clustering has emerged as a powerful framework for analyzing heterogeneous and complex data. Despite the abundance of existing schemes, co-association matrix-based methods remain the mainstream approach. However, focusing solely on pairwise correlations falls short of fully capturing the intricate cluster relationships. Moreover, despite its potential, ensemble clustering has yet to effectively leverage the powerful representation capabilities of neural networks. To address these limitations, we propose a deep ensemble clustering method called Ensemble Clustering with Attentional Representation (ECAR). Our method considers the results of base partitions as groups with related information to explore higher-order fusion information. ECAR captures the importance of each sample’s association with its related group by employing an attentional network, and encodes this information into a low-dimensional representation. The attentional network is trained by jointly optimizing the clustering loss from soft assignments learned from the embeddings and the reconstruction loss from the weighted graph generated from ensemble clustering. During training, the weights of base partitions are adaptively refined to promote diversity and consistency while reducing the impact of low-quality and redundant base partitions. Extensive experimental results on real-world datasets demonstrate the substantial improvement of our method over existing baseline ensemble clustering methods and deep clustering methods.'

# 标签（关键词）
tags: [Clustering methods, Clustering algorithms]

featured: true

# 填写相关 URL
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10173506'
url_code: 'https://github.com/zz-haooo/ECAR'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
