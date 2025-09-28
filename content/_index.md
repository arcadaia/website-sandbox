---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content: 
      title: |
        Tantra Lab
      image:
        filename: lab_Vishal.jpg
      text: |
        <br>
        The **Founded by Vishal Jain, a translational neuroscientist, TANTRA Lab is an incubator space dedicated to building the next generation of neurotechnologies that bridge discovery and practice. Established within the Chamanzar Lab under the mentorship of Prof. Maysam Chamanzar and Prof. Pulkit Grover, TANTRA Lab integrates engineering, neuroscience, and clinical insight to design tools that advance how we sense, stimulate, and interface with the brain and body.
        Our mission is to translate cutting-edge research into real-world solutions—from novel brain stimulation and neural recording platforms to innovative imaging and sensing technologies. By combining rigorous scientific exploration with a translational mindset, TANTRA Lab aims to create impactful systems that address pressing challenges in neuroscience, medicine, and human health.**

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
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
        publication_type: 'article'
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
