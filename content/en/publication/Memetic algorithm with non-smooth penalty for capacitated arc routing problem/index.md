---
title: "Memetic algorithm with non-smooth penalty for capacitated arc routing problem"
authors:
- admin
date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "05/2021"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: The capacitated arc routing problem (CARP) has attracted much attention during last decades due to its wide applications. However, the existing research methods still have a little potential to make full use of the characteristics of CARP. This paper aims to mine the essential characteristics of arc routing problem that node routing problem does not have. Based on the observation on characteristics of arc routing instances, smooth condition is proposed and constructed as a rule to divide the link between two tasks into smooth link and non-smooth link. Then smooth degree is defined to measure the influence of non-smooth links on solution and a small smooth degree means the better quality for a solution. The effect of smooth degree is verified through simulation comparison on several instance sets, which indicates that there is a positive correlation between smooth degree and the total cost of a solution. Non-smooth penalty is used to drive the non-smooth solution to smooth and to improve its total cost. Then non-smooth penalty is inserted into path-scanning variants and new construction algorithms are obtained. A partial reconstruction method (PRM) is designed using these construction algorithms as an alternative kernel method. In order to further reduce the routes number, a reinsert method (RiM) is proposed. Combining these two methods with traditional local search algorithms, a memetic algorithm with non-smooth penalty (MANSP) is proposed which is originated from the initial observation on the essential characteristics of arc routing problem. Extensive experiments on smooth degree, penalty factor, and comparison with state-of-the-art algorithms show that the proposed strategies are effective and the proposed algorithm MANSP performs very competitive.

# Summary. An optional shortened abstract.
summary: Non-smooth penalty and a memetic algorithm with non-smooth penalty are proposed .

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf:  /files/MANSP.pdf
url_code: 'https://github.com/zmdsn/MANSP.git'
url_dataset: ''
url_poster: ''
url_project: 'project/siorea/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: ''
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- SIorEA
- CARP

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---
