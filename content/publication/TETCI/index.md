---
title: "Reconstructing Heterogeneous Networks via Compressive Sensing and Clustering"
draft: true
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Chunhua Yang
- Keke Huang
- Marko Jusup
- Zhen Wang
- Xuelong Li

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-06-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In IEEE Transactions on Emerging Topics in Computational Intelligence
publication_short: In *TETCI*

abstract: Reconstructing complex networks from observed data is a fundamental problem in network science. Compressive sensing, widely used for recovery of sparse signals, has also been used for network reconstruction under the assumption that networks are sparse. However, heterogeneous networks are not exactly sparse. Moreover, when using compressive sensing to recover signals, the projection matrix is usually a random matrix that satisfies the restricted isometry property (RIP) condition. This condition is much harder to satisfy during network reconstruction because the projection matrix depends on time-series data of network dynamics. To overcome these shortcomings, we devised a novel approach by adapting the alternating direction method of multipliers to find a candidate adjacency matrix. Then we used clustering to identify high-degree nodes. Finally, we replaced the elements of the candidate adjacency vectors of high-degree nodes, which are likely to be incorrect, with the corresponding elements of small-degree nodes, which are likely to be correct. The proposed method thus overcomes the shortcomings of compressive sensing and is suitable for reconstructing heterogeneous networks. Experiments with both artificial scale-free and empirical networks showed that the proposed method is accurate and robust.

# Summary. An optional shortened abstract.
summary: IEEE Transactions on Emerging Topics in Computational Intelligence

tags: [Complex Networks, Network Identification, Cluster, Games, Compressive Sensing]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/MrZhangCSU/clustering-base-network-reconstruction'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'An example of the application of the proposed method for network structure reconstruction'
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

Source code can be found [here](https://github.com/MrZhangCSU/clustering-base-network-reconstruction).
