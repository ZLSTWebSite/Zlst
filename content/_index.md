---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero_neo
    id: my-hero-style
    content:
      title: The ZLST Lab
      text: |
        The ZLST Lab is affiliated with Computer Science, Zhejiang University. The lab is led by Professor Chun Chen, focusing on cutting-edge research in Big Data and Artificial Intelligence, particularly in Recommender Systems, Graph Mining, Diffusion Models, Knowledge Distillation, and Large Language Models, etc. Our team has been honored with five provincial/ministerial-level science and technology awards, and five best paper awards at top international academic conferences. We look forward to contributing to the field of artificial intelligence in the era of large models!
      image:
        filename: homepage_background.png
      design:
        flip: true
        column_size: 7
  - block: hero_neo
    id: my-hero-style
    content:
      title: Primary Research Interests
  - block: hero_neo
    id: my-hero-style
    content:
      subtitle: Recommendation systems
      text: |
        Recommender systems (RS) are technologies that utilize user behavior and content characteristics to predict user preferences and provide personalized recommendations, serving as core infrastructure for e-commerce and social media platforms. We are devoted to cutting-edge research topics including trustworthy recommendation, sequential recommendation, theoretical foundations of Recommender Systems, and LLM-enhanced recommendation paradigms. 
      image:
        filename: recommendation_systems.png
      design:
        flip: true
  - block: hero_neo
    id: my-hero-style
    content:
      subtitle: Graph mining
      text: |
        Graph data mining aims to extract the underlying relationships and patterns between entities from various graph-structured data, which has many real-world applications such as social network analysis, bioinformatics and financial fraud detection. We are committed to cutting-edge research topics including graph transformer, graph foundation models, graph structure learning, graph query and LLM-empowered graph models.
      image:
        filename: graph_mining.jpg
      design:
        flip: true
  - block: hero_neo
    id: my-hero-style
    content:
      subtitle: Diffusion Models
      text: |
        Diffusion Models are a class of generative models that have gained significant attention in recent years, particularly in the fields of computer vision and natural language processing. By establishing a mapping from noise distribution to data distribution, Diffusion Models can generate high-quality data such as images, videos, audios and text. We are devoted to provide a deeper understanding of the generaion dynamics of Diffusion Models and the acceleration of their sampling processes. 
      image:
        filename: logo-diffusion-models.png
      design:
        flip: true
  - block: hero_neo
    id: my-hero-style
    content:
      subtitle: Knowledge distillation
      text: |
        Knowledge distillation aims to achieve efficient transfer of knowledge from complex models to lightweight models. The goal is to balance the inference cost and performance of compact models, facilitating the deployment of intelligent models in resource-constrained scenarios such as edge computing and mobile devices.
      image:
        filename: logo-kd.jpg
      design:
        flip: true

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: background2.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
