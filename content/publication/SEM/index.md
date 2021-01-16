---
title: "Natural Language Adversarial Attacks and Defenses in Word Level"
authors:
- admin
- Hao Jin
- Kun He
date: "2019-09-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-09-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv preprint arXiv:1909.06723*
# publication_short: In *AAAI*

abstract: In recent years, inspired by a mass of researches on adversarial examples for computer vision, there has been a growing interest in designing adversarial attacks for Natural Language Processing (NLP) tasks, followed by very few works of adversarial defenses for NLP. To our knowledge, there exists no defense method against the successful synonym substitution based attacks that aim to satisfy all the lexical, grammatical, semantic constraints and thus are hard to be perceived by humans. We contribute to fill this gap and propose a novel adversarial defense method called **Synonym Encoding Method** (SEM), which inserts an encoder before the input layer of the model and then trains the model to eliminate adversarial perturbations. Extensive experiments demonstrate that SEM can efficiently defend current best synonym substitution based adversarial attacks with little decay on the accuracy for benign examples. To better evaluate SEM, we also design a strong attack method called Improved Genetic Algorithm (IGA) that adopts the genetic metaheuristic for synonym substitution based attacks. Compared with the first genetic based adversarial attack proposed in 2018, IGA can achieve higher attack success rate with lower word substitution rate, at the same time maintain the transferability of adversarial examples.
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
# url_poster: publication/ATFL/ATFL_poster.pdf
# url_project: ''
# url_slides: publication/ATFL/ATFL_slides.pdf
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
