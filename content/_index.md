---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        CYCLE Lab
      image:
        filename: poly.png
      text: |
        <br>
        <div style = "text-align: justify; font-size: 24px;">
        The CYCLE Lab focuses on advancing research in compilers, programming languages, and outcomes in computational systems. CYCLE is an abbreviation for <strong>C</strong>ompiler systems <strong>Y</strong>ielding for <strong>C</strong>omputational <strong>L</strong>anguages and <strong>E</strong>xecution acceleration. This name underscores our commitment to continuous optimization processes aimed at enhancing performance and efficiency across various applications, including deep learning, high-performance computing, and numerical computation, as well as multiple platforms such as CPU, GPU, and NPU. Additionally, CYCLE encompasses several interpretations, including but not limited to:
        <br>
        - a dynamic, iterative research approach, highlighting the significance of iterative improvement in both system optimization and compiler design;
        <br>
        - a synonym for loops, which are fundamental to polyhedral compilation techniques;
        <br>
        - a critical performance metric for computer systems.
        <br>
        Through these dimensions, the CYCLE Lab aims to innovate and lead in the fields of compiler technologies and computational systems.
        </div>

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 3
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
      title: Latest Publications
      text: ""
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'paper-conference'
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