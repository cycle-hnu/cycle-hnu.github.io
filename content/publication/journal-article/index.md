---
title: 'Hierarchical search algorithm for error detection in floating-point arithmetic expressions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zuoyan Zhang
  - Jinchen Xu
  - Jiangwei Hao
  - Yang Qu
  - Haotian He
  - Bei Zhou
# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
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
publication: "*The Journal of Supercomputing"
publication_short: ""

abstract: Scientific and engineering applications rely on floating-point arithmetic to approximate real numbers. Due to the inherent rounding errors in floating-point numbers, error propagation during calculations can accumulate and lead to serious errors that may compromise the safety and reliability of the program. In theory, the most accurate method of error detection is to exhaustively search all possible floating-point inputs, but this is not feasible in practice due to the huge search space involved. Effectively and efficiently detecting maximum floating-point errors has been a challenge. To address this challenge, we design and implement an error detection tool for floating-point arithmetic expressions called HSED. It leverages modified mantissas under double precision floating-point types to simulate hierarchical searches from either half or single precision to double precision. Experimental results show that for 32 single-parameter arithmetic expressions in the FPBench benchmark test set, the error detection effects and performance of HSED are significantly better than the state-of-the-art error detection tools Herbie, S3FP and ATOMU. HSED outperforms Herbie, Herbie+, S3FP and ATOMU in 24, 19, 27 and 25 cases, respectively. The average time taken by Herbie, Herbie+, and S3FP is 1.82, 11.20, and 129.15 times longer than HSED, respectively.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

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
