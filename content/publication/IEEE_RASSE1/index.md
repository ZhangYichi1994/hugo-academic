---
title: "False Data Injection Attack Testbed of Industrial Cyber-Physical Systems of Process Industry and A Detection Application"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Wenfeng Deng
- Keke Huang
- Chunhua Yang

# Author notes (optional)
# author_notes:

date: "2020-12-12T00:00:00Z"
doi: "https://ieeexplore.ieee.org/abstract/document/9686839"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In 2021 IEEE International Conference on Recent Advances in Systems Science and Engineering (RASSE)
publication_short: In *IEEE RASSE 2021*

abstract: False data injection (FDI) attack is a common and destructive attack method in Industrial Cyber-Physical Systems (ICPSs), which is mounted in the cyber layer, compromises the measurement data and interferes the physical system at last, especially in the process industry and smart grid. In response, researchers developed many detection method rely on simulation, but the real situations are not ideal simulation environment. This leads to situation in which the high-level methods cannot applied to industrial sites directly. In this paper, we design a testbed of process industry, which is a hardware-in-the-loop platform, to simulate the real industrial production and applied a FDI attack on the platform. The physical process is simulated by a host, and the cyber items are real industrial controller or engineer station. Next, we design an efficient FDI attack detection method, DRIF. Based on our proposed framework, the optimal potential features of high-dimensional industrial process data can be fully extracted, which is conducive to the stage of accurate detection. In addition, it makes our proposed method practicable in real-world scenarios where data instances in normal condition can be used for model training only. The proposed method is applied on the designed platform, and the promising case studies show our framework can achieve satisfactory detection performance, which sheds light on the industrial security to some extent.

# Summary. An optional shortened abstract.
summary: 2021 IEEE International Conference on Recent Advances in Systems Science and Engineering (RASSE)

tags: [Cyber-Physical Systems, Attack Detection, Testbed, Hard-in-the-loop Platform]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/MrZhangCSU/DRIF'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Hard-in-the-loop Platform'
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

The source code can be found at [here](https://github.com/MrZhangCSU/DRIF).
