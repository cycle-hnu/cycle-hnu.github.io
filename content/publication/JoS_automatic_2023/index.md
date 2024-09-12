---
title: 'Automatic Mixed Precision Optimization for Stencil Computation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Guanghui Song
  - Shaozhong Guo
  - Jie Zhao
  - Xiaohan Tao
  - Fei Li
  - Jinchen Xu
# Author notes (optional)
author_notes:
  - 'Information Engineering University'
  - 'Information Engineering University'
  - 'Information Engineering University'
  - 'Information Engineering University'
  - 'Information Engineering University'
  - 'Corresponding author'

date: '2023-11-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*The Journal of Software"
publication_short: ""

abstract: Mixed precision has made many advances in deep learning and precision tuning and optimization. Extensive research shows that mixed precision optimization for stencil computation is challenging. Moreover, the research achievements secured by the polyhedral model in the field of automatic parallelization indicate that the model provides a good mathematical abstraction for loop nesting, on the basis of which loop transformations can be performed. This study designs and implements an automatic mixed precision optimizer for Stencil computation on the basis of polyhedral compilation technology. By performing iterative domain partitioning, data flow analysis, and scheduling tree transformation on the intermediate representation layers, this study implements the source-to-source automatic generation of mixed precision codes for Stencil computation for the first time. The experiments demonstrate that the code after automatic mixed precision optimization can give full play to its parallelism potential and improve the performance of the program by reducing precision redundancy. With high-precision computing as the benchmark, the maximum speedup is 1.76, and the geometric average speedup is 1.15 on the x86 architecture; on the new-generation Sunway architecture, the maximum speedup is 1.64, and the geometric average speedup is 1.20.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://jos.org.cn/jos/article/abstract/6757'
url_code: 'https://github.com/sheenisme/lnlamp'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
