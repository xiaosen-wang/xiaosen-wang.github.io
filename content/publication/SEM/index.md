---
title: "Natural Language Adversarial Defense through Synonym Encoding"
authors:
- admin
- Hao Jin
- Yichen Yang
- Kun He
date: "2021-05-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-05-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Conference on Uncertainty in Artificial Intelligence (UAI)
# publication_short: In *AAAI*

abstract: In the area of natural language processing, deep learning models are recently known to be vulnerable to various types of adversarial perturbations, however, relatively few works are done on the defense side. Especially, there exists little effective defense method against the successful synonym substitution based attacks that preserve the syntactic structure and semantic information of the original text while fooling the deep learning models. We contribute in this direction and propose a novel adversarial defense method called *Synonym Encoding Method* (SEM). Specifically, SEM inserts an encoder before the input layer of the target model to map each cluster of synonyms to a unique encoding and trains the model to eliminate possible adversarial perturbations without modifying the network architecture or adding extra data. Extensive experiments demonstrate that SEM can effectively defend the current synonym substitution based attacks and block the transferability of adversarial examples. SEM is also easy and efficient to be scaled to large models and big datasets.
# Summary. An optional shortened abstract.
summary: Adversarial Attacks and Defenses for Texts.

# tags:
# - Category: NLP
# - Source Themes
# featured: true
category: NLP
links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/1909.06723
url_code: https://github.com/xiaosen-wang/SEM
# url_dataset: '#'
url_poster: publication/sem/SEM_poster.pdf
# url_project: ''
url_slides: publication/sem/SEM_slides.pdf
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
