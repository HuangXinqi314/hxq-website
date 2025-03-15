---
# Leave the homepage title empty to use the site title
title: "Huang's homepage"
date: 2025-01-07
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    content:
      title: 'Co-authors'
      subtitle: ''
      text: "Xinqi Huang(2), [Jie Ma](http://staff.ustc.edu.cn/~jiema/)(2), [Zixiang Xu](https://www.ibs.re.kr/ecopro/zixiangxu/)(2), Xinbu Cheng(1), Guorong Gao(1), Mingze Li(1), [Hong Liu](https://www.ibs.re.kr/ecopro/hongliu/)(1), [Tuan Tran](https://tuaentran.wixsite.com/homepage)(1)."
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'Useful websites'
      subtitle: 'some tools that I recommend for academic research'
      text: |
        - Here are three tools that significantly improved my research workflow: 
        - **[Deepseek](https://chat.deepseek.com/)**  
          When I need quick AI assistance for technical problems, **[Deepseek](https://chat.deepseek.com/)** has become my go-to tool. Its R1 version responds almost instantly, and what's really cool is you can actually see how the AI thinks through problems step by step - like watching someone's thought process in real time. This transparency helps me adjust my questions better when the initial response isn't quite right.
        - **[Inciteful](https://inciteful.xyz/)**  
          For literature discovery, I prefer **[Inciteful](https://inciteful.xyz/)** over Connected Papers because it lets me analyze multiple papers at once. Imagine being able to search for papers based on 5-10 papers simultaneously - it's like having a research map that shows hidden relationships between different papers. By identifying works that have multiple references to my input papers, it reveals connections that single-paper analysis would miss, creating more comprehensive research maps.
        - **[Undermind](https://www.undermind.ai/home/)**  
          When I'm not exactly sure what keywords to search, **[Undermind](https://www.undermind.ai/home/)** is my secret weapon. Unlike traditional keyword searches, its AI-powered system allows you to search without any keywords - you can progressively narrow or broaden the scope through dialogue, it understands the context like a research partner would. The downside is it is very slow, since it need to use LLM for vague searching.
    design:
      columns: '1'
---
