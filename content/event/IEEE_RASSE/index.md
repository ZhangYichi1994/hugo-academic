---
title: IEEE RASSE Talk

event: The IEEE International Conference on Recent Advances in Systems Science and Engineering 
event_url: https://2021.ieeerasse.org/

location: Shanghai
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: IEEE RASSE .
abstract: "False data injection (FDI) attack is a common and destructive attack method in Industrial Cyber-Physical Systems (ICPSs), which is mounted in the cyber layer, compromises the measurement data and interferes the physical system at last, especially in the process industry and smart grid. In response, researchers developed many detection method rely on simulation, but the real situations are not ideal simulation environment. This leads to situation in which the high-level methods cannot applied to industrial sites directly. In this paper, we design a testbed of process industry, which is a hardware-in-the-loop platform, to simulate the real industrial production and applied a FDI attack on the platform. The physical process is simulated by a host, and the cyber items are real industrial controller or engineer station. Next, we design an efficient FDI attack detection method, DRIF. Based on our proposed framework, the optimal potential features of high-dimensional industrial process data can be fully extracted, which is conducive to the stage of accurate detection. In addition, it makes our proposed method practicable in real-world scenarios where data instances in normal condition can be used for model training only. The proposed method is applied on the designed platform, and the promising case studies show our framework can achieve satisfactory detection performance, which sheds light on the industrial security to some extent."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2021-12-01T13:00:00Z'
date_end: '2021-12-30T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2022-01-25T00:00:00Z'

authors: [Yichi Zhang, Wenfeng Deng, Keke Huang, Chunhua Yang]
tags: [Cyber-Pysical Systems, FDIA, Testbed, Detection]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'IEEE RASSE 2021'
  focal_point: Right

links:
url_pdf: "https://ieeexplore.ieee.org/abstract/document/9686839"
url_code: "https://github.com/MrZhangCSU/DRIF"
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
# - example
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

<!-- Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/). -->

The source code can be found at [here](https://github.com/MrZhangCSU/DRIF)
<!-- Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->
