---
title: "Operation-adversarial scenario generation"
authors:
- Zhirui Liang
- Robert Mieth
- Yury Dvorkin
date: 2022-06-01
doi: '10.1016/j.epsr.2022.108451'

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*2022 Power System Computation Conference*"
publication_short: ""

abstract: "This paper proposes a modified conditional generative adversarial network (cGAN) model to generate net load scenarios for power systems that are statistically credible, conditioned by given labels (e.g., seasons), and, at the same time, “stressful” to the system operations and dispatch decisions. The measure of stress used in this paper is based on the operating cost increases due to net load changes. The proposed operation-adversarial cGAN (OA-cGAN) internalizes a DC optimal power flow model and seeks to maximize the operating cost and achieve a worst-case data generation. The training and testing stages employed in the proposed OA-cGAN use historical day-ahead net load forecast errors and has been implemented for the realistic NYISO 11-zone system. Our numerical experiments demonstrate that the generated operation-adversarial forecast errors lead to more cost-effective and reliable dispatch decisions."

# Summary. An optional shortened abstract.
summary: ""

tags: ''
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/2110.02152.pdf'
url_code: 'https://github.com/ZhiruiLiang/OA-cGAN'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ''
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
slides: ''
---
