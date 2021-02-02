---
title: "Admix: Enhancing the Transferability of Adversarial Attacks"
authors:
- admin
- Xuanran He
- Jingdong Wang
- Kun He
date: "2021-01-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-31T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv preprint arXiv:2102.00436*
# publication_short: In *AAAI*

abstract: Although adversarial attacks have achieved incredible attack success rates under the white-box setting, most existing adversaries often exhibit weak transferability under the black-box setting. To address this issue, various input transformations have been proposed to enhance the attack transferability. In this work, We observe that all the existing transformations are applied on a single image, which might limit the transferability of the crafted adversaries. Hence, we propose a new input transformation based attack called Admix Attack Method (AAM) that considers both the original image and an image randomly picked from other categories. Instead of directly calculating the gradient on the original input, AAM calculates the gradient on the admixed image interpolated by the two images in order to craft adversaries with higher transferablility. Empirical evaluations on the standard ImageNet dataset demonstrate that AAM could achieve much higher transferability than the existing input transformation methods. By incorporating with other input transformations, our method could further improve the transferability and outperform the state-of-the-art combination of input transformations by a clear margin of 3.4% on average when attacking nine advanced defense models.
# Summary. An optional shortened abstract.
summary: Adversarial Attacks and Defenses for Images.

# tags:
# - Category: NLP
# - Source Themes
# featured: true
category: NLP
links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/2102.00436
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
