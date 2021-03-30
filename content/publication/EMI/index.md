---
title: "Boosting Adversarial Transferability through Enhanced Momentum"
authors:
- admin
- Jiadong Lin
- Han Hu
- Jingdong Wang
- Kun He
date: "2021-03-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv preprint arXiv:2103.10609*
# publication_short: In *AAAI*

abstract: Deep learning models are known to be vulnerable to adversarial examples crafted by adding human-imperceptible perturbations on benign images. Many existing adversarial attack methods have achieved great white-box attack performance, but exhibit low transferability when attacking other models. Various momentum iterative gradient-based methods are shown to be effective to improve the adversarial transferability. In what follows, we propose an enhanced momentum iterative gradient-based method to further enhance the adversarial transferability. Specifically, instead of only accumulating the gradient during the iterative process, we additionally accumulate the average gradient of the data points sampled in the gradient direction of the previous iteration so as to stabilize the update direction and escape from poor local maxima. Extensive experiments on the standard ImageNet dataset demonstrate that our method could improve the adversarial transferability of momentum-based methods by a large margin of 11.1% on average. Moreover, by incorporating with various input transformation methods, the adversarial transferability could be further improved significantly. We also attack several extra advanced defense models under the ensemble-model setting, and the enhancements are remarkable with at least 7.8% on average.

# Summary. An optional shortened abstract.
summary: Adversarial Attacks and Defenses for Images.

# tags:
# - Category: NLP
# - Source Themes
# featured: true
# category: NLP
links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/2103.10609
# url_code: https://github.com/xiaosen-wang/SEM
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
