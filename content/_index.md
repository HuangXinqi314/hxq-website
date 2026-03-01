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
      title: Preprints
      text: ""
      filters:
        folders:
          - preprint
        exclude_featured: false
    design:
      view: citation
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
      text: "[Mingyuan Rong](https://www.mingyuanrong.com/)(3), [Zixiang Xu](https://www.ibs.re.kr/ecopro/zixiangxu/)(3), [Hong Liu](https://www.ibs.re.kr/ecopro/hongliu/)(1), [Xiande Zhang](http://staff.ustc.edu.cn/~drzhangx/)(2), [Chong Shangguan](https://faculty.sdu.edu.cn/sgc/zh_CN/index/1259037/list/index.htm)(1), Xinbu Cheng(1), Yuhao Zhao(1), Yuzhen Qi(1), Wenjie Zhong(1)  "
    design:
      columns: '1'
  
---
