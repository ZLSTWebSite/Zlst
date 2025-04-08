---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title:
      subtitle: ''
      text: |
        <div style="display: flex; align-items: center; gap: 20px;">
          <div style="flex: 1;">
            <img src="https://www.zju.edu.cn/_upload/tpl/0b/bf/3007/template3007/static/media/logo.e85b920df15a055ad9bc.png" style="width: 100%; height: auto; border-radius: 8px;">
          </div>
          <div style="flex: 2; font-size: 1.1em;">
            The ZLST Lab is affiliated with Computer Science, Zhejiang University. The lab is led by Professor Chun Chen, focusing on cutting-edge research in Big Data and Artificial Intelligence, particularly in Recommender Systems, Graph Mining, Diffusion Models, Knowledge Distillation, and Large Language Models, etc. Our team has been honored with five provincial/ministerial-level science and technology awards, and five best paper awards at top international academic conferences. We look forward to contributing to the field of artificial intelligence in the era of large models!
          </div>
        </div>
  
  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  - block: markdown
    content:
      title:
      subtitle: ''
      text: |
        <div style="font-size: 0.8em;">

        #  Primary Research Interests

        <div style="display: flex; align-items: center; gap: 20px;">
        <div style="flex: 1;">
          <img src="https://www.zju.edu.cn/_upload/tpl/0b/bf/3007/template3007/static/media/logo.e85b920df15a055ad9bc.png" style="width: 100%; height: auto; border-radius: 8px;">
        </div>
        <div style="flex: 2; font-size: 1.1em;">

          ## Recommendation systems

          Recommender systems (RS) are technologies that utilize user behavior and content characteristics to predict user preferences and provide personalized recommendations, serving as core infrastructure for e-commerce and social media platforms.

          We are devoted to cutting-edge research topics including trustworthy recommendation, sequential recommendation, theoretical foundations of Recommender Systems, and LLM-enhanced recommendation paradigms. 
        </div>
        </div>

        <div style="display: flex; align-items: center; gap: 20px;">
        <div style="flex: 1;">
          <img src="https://www.zju.edu.cn/_upload/tpl/0b/bf/3007/template3007/static/media/logo.e85b920df15a055ad9bc.png" style="width: 100%; height: auto; border-radius: 8px;">
        </div>
        <div style="flex: 2; font-size: 1.1em;">

          ## Graph mining

          Graph data mining aims to extract the underlying relationships and patterns between entities from various graph-structured data, which has many real-world applications such as social network analysis, bioinformatics and financial fraud detection. 
          
          We are committed to cutting-edge research topics including graph transformer, graph foundation models, graph structure learning, graph query and LLM-empowered graph models.
        </div>
        </div>

        <div style="display: flex; align-items: center; gap: 20px;">
        <div style="flex: 1;">
          <img src="https://www.zju.edu.cn/_upload/tpl/0b/bf/3007/template3007/static/media/logo.e85b920df15a055ad9bc.png" style="width: 100%; height: auto; border-radius: 8px;">
        </div>
        <div style="flex: 2; font-size: 1.1em;">

          ## Diffusion Models

          Diffusion Models are a class of generative models that have gained significant attention in recent years, particularly in the fields of computer vision and natural language processing. By establishing a mapping from noise distribution to data distribution, Diffusion Models can generate high-quality data such as images, videos, audios and text. 
          
          We are devoted to provide a deeper understanding of the generaion dynamics of Diffusion Models and the acceleration of their sampling processes. 

        </div>
        </div>

        <div style="display: flex; align-items: center; gap: 20px;">
        <div style="flex: 1;">
          <img src="https://www.zju.edu.cn/_upload/tpl/0b/bf/3007/template3007/static/media/logo.e85b920df15a055ad9bc.png" style="width: 100%; height: auto; border-radius: 8px;">
        </div>
        <div style="flex: 2; font-size: 1.1em;">

          ## Knowledge Distillation

          Knowledge distillation aims to achieve efficient transfer of knowledge from complex models to lightweight models. The goal is to balance the inference cost and performance of compact models, facilitating the deployment of intelligent models in resource-constrained scenarios such as edge computing and mobile devices.

        </div>
        </div>

        </div>
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

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
