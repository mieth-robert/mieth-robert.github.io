---
title: "Fast Security-Constrained Optimal Power Flow Through Low-Impact and Redundancy Screening"
authors:
- Richard Weinhold
- Robert Mieth
author_notes:
- "Equal contribution"
- "Equal contribution"
date: 2020-05-14
doi: "10.1109/TPWRS.2020.2994764"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Power Systems*"
publication_short: ""

abstract: "Determining contingency aware dispatch decisions by solving a security-constrained optimal power flow (SCOPF) is challenging for real-world power systems, as the high problem dimensionality often leads to impractical computational requirements. This problem becomes more severe when the SCOPF has to be solved not only for a single instance, but for multiple periods, e.g. in the context of electricity market analyses. This paper proposes an algorithm that identifies the minimal set of constraints that exactly define the space of feasible nodal injections for a given network and contingency scenarios. By internalizing the technical limits of the nodal injections and enforcing a minimal worst-case impact of contingencies to line flows, computational effort can be further improved. The case study applies and analyzes the methods on the IEEE 118 and A&M 2000 bus systems, as well as the German and European transmission systems. In all tested cases the proposed algorithm identifies at least 95% of the network and security constraints as redundant, leading to significant SCOPF solve time reductions. Scalability and practical implementation are explicitly discussed. The code and input data of the case study is published supplementary to the paper under an open-source license."

# Summary. An optional shortened abstract.
summary: ""

tags: ''
featured: yes

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/1910.09034.pdf
url_code: 'https://github.com/richard-weinhold/pomato'
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
