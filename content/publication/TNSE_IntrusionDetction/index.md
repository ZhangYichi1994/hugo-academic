---
title: "Intrusion Detection of Industrial Internet-of-Things Based on Reconstructed Graph Neural Networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Chunhua Yang
- Keke Huang
- Yonggang Li

# # Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-06-21T00:00:00Z"
doi: "10.1109/TNSE.2022.3184975"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Network Science and Engineering
publication_short: In *TNSE*

abstract: Industrial Internet-of-Things (IIoT) are highly vulnerable to cyber-attacks due to their open deployment in unattended environments. Intrusion detection is an efficient solution to improve security. However, because the labeled samples are difficult to obtain, and the sample categories are imbalanced in real applications, it is difficult to obtain a reliable model. In this paper, a general framework for intrusion detection is proposed based on graph neural network technologies. In detail, a network embedding feature representation is proposed to deal with the high dimensional, redundant but categories imbalanced and rare labeled data in IIoT. To avoid the influence caused by the inaccurate network structure, a network constructor with refinement regularization is designed to amend it. At last, the network embedding representation weights and network constructor are trained together. The high accuracy and robust properties of the proposed method were verified by conducting intrusion detection tasks based on public datasets. Compared with several state-of-art algorithms, the proposed framework outperforms these methods in many evaluation metrics. In addition, a hard-in-the-loop platform is designed to test the performance in real environments. The results show that the method can not only identify different attacks but also distinguish between cyber-attacks and physical failures.

# Summary. An optional shortened abstract.
summary: IEEE Transactions on Network Science and Engineering

tags: [Intrusion Detection, Graph Neural Network, Network Construction, Complex networks, Hard-in-the-Loop Platform]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9802721'
url_code: 'https://github.com/ZhangYichi1994/GID'
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

Source code can be found [here](https://github.com/MrZhangCSU/GID).
