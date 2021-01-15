---
title: Adversarial Training in Textual Adversarial Attack and Defense

event: AI Drive Organized by Biendata and Paperweekly
# event_url: https://example.org

location: Online
address:
  street: 450 Serra Mall
  city: Stanford
  region: CA
  postcode: '94305'
  country: United States

summary: AI Drive Organized by Biendata and Paperweekly.
# abstract: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellusac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-01-12T19:00:00Z"
date_end: "2021-01-12T20:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2021-01-12T00:00:00Z"

authors: [Xiaosen Wang]
tags: []

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: publication/atfl/ATFL_slides.pdf
url_video: https://www.bilibili.com/video/BV1Pv41147bp?from=search&seid=2336547234866323090

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

Adversarial training is the most empirically successful approach in improving the robustness of deep neural networks for image classification.For text classification, however, existing synonym substitution based adversarial attacks are effective but not efficient to be incorporated into practical text adversarial training. Gradient-based attacks, which are very efficient for images, are hard to be implemented for synonym substitution based text attacks due to the lexical, grammatical and semantic constraints and the discrete text input space. Thereby, we propose a fast text adversarial attack method called Fast Gradient Projection Method (FGPM) based on synonym substitution, which is about 20 times faster than existing text attack methods and could achieve similar attack performance. We then incorporate FGPM with adversarial training and propose a text defense method called Adversarial Training with FGPM enhanced by Logit pairing (ATFL). Experiments show that ATFL could significantly improve the model robustness and block the transferability of adversarial examples.
