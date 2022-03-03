---
title: "Robust Structure Identification of Industrial Cyber-Physical System From Sparse Data: A Network Science Perspective"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Chunhua Yang
- Keke Huang
- Can Zhou
- Yonggang Li

# # Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-03-10T00:00:00Z"
doi: "10.1109/TASE.2021.3062356"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In IEEE Transactions on Automation Science and Engineering
publication_short: In *TASE*

abstract: Industrial cyber-physical systems (ICPSs) are deployed in many high-value facilities recently, and the monitoring of ICPS is more and more important. However, the prerequisite of ICPS monitoring is how to obtain an accurate network structure. In addition, the structure of ICPS may change over time and the observations data are limited and noisy. These situations make the ICPS network structure identification more difficult. In this article, we proposed the algorithm of temporal network identification from sparse data (ATNISD) to address these two issues simultaneously. First, we established the temporal network analysis model from the aspect of state equation and observation equation. Then, we analyze the characteristics of temporal networks in both time domain and space domain and propose a general framework of temporal networks structure identification, which is a combinatorial optimization problem. To improve the accuracy and alleviate the computational complexity, we decompose the combinatorial problem into small independent simple problems, which can be solved efficiently. The performance of the proposed algorithm is verified on synthetic evolutionary game dynamics on both homogeneous and heterogeneous temporal networks. The experimental results show that the proposed method can efficiently solve the problem of temporal networks structure identification from sparse data.

# Summary. An optional shortened abstract.
summary: IEEE Transactions on Automation Science and Engineering

tags: [Mathematical model, Games, Optimization, Evolution (biology), Data models, Complex networks, Task analysis]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9374759'
url_code: 'https://github.com/MrZhangCSU/ATNISD'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Dynamical Network modeling'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Source code can be found [here](https://github.com/MrZhangCSU/ATNISD).
