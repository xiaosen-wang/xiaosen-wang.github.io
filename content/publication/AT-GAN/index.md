---
title: "AT-GAN: A Generative Attack Model for Adversarial Transferring on Generative Adversarial Nets"
authors:
- admin
- Kun He
- Chuanbiao Song
- Liwei Wang
- John E. Hopcroft
date: "2019-04-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-04-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv preprint arXiv:1904.07793, 2019*
# publication_short: In *AAAI*

abstract: Despite the rapid development of adversarial machine learning, most adversarial attack and defense researches mainly focus on the perturbation-based adversarial examples, which is constrained by the input images. In comparison with existing works, we propose non-constrained adversarial examples, which are generated entirely from scratch without any constraint on the input. Unlike perturbation-based attacks, or the so-called unrestricted adversarial attack which is still constrained by the input noise, we aim to learn the distribution of adversarial examples to generate non-constrained but semantically meaningful adversarial examples. Following this spirit, we propose a novel attack framework called AT-GAN (Adversarial Transfer on Generative Adversarial Net). Specifically, we first develop a normal GAN model to learn the distribution of benign data, and then transfer the pre-trained GAN model to estimate the distribution of adversarial examples for the target model. In this way, AT-GAN can learn the distribution of adversarial examples that is very close to the distribution of real data. To our knowledge, this is the first work of building an adversarial generator model that could produce adversarial examples directly from any input noise. Extensive experiments and visualizations show that the proposed AT-GAN can very efficiently generate diverse adversarial examples that are more realistic to human perception. In addition, AT-GAN yields higher attack success rates against adversarially trained models under white-box attack setting and exhibits moderate transferability against black-box models.

# Summary. An optional shortened abstract.
summary: Adversarial Attacks and Defenses for Images.

# tags:
# - Source Themes
# featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/1904.07793
# url_code: https://github.com/JHL-HUST/FGPM
# url_dataset: '#'
# url_poster: publication/ATFL/ATFL_poster.pdf
# url_project: ''
# url_slides: publication/ATFL/ATFL_slides.pdf
# url_source: '#'
# url_video: '#'

---
