---
title: "A New Anchor Word Selection Method for the Separable Topic Discovery"
authors:
- Kun He
- Wu Wang
- admin
- John E. Hopcroft
author_notes:
- 
- 
- Corresponding author

date: "2019-05-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-05-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *WIREs Data Mining and Knowledge Discovery*
# publication_short: In *AAAI*

abstract: Separable Non-negative Matrix Factorization (SNMF) is an important method for topic modeling, where "separable" assumes every topic contains at least one anchor word, defined as a word that has non-zero probability only on that topic. SNMF focuses on the word co-occurrence patterns to reveal topics by two steps&#58; anchor word selection and topic recovery. The quality of the anchor words strongly influences the quality of the extracted topics. Existing anchor word selection algorithm is to greedily find an approximate convex hull in a high-dimensional word co-occurrence space. In this work, we propose a new method for the anchor word selection by associating the word co-occurrence probability with the words similarity and assuming that the most different words on semantic are potential candidates for the anchor words. Therefore, if the similarity of a word-pair is very low, then the two words are very likely to be the anchor words. According to the statistical information of text corpora, we can get the similarity of all word-pairs. We build the word similarity graph where the nodes correspond to words and weights on edges stand for the word-pair similarity. Following this way, we design a greedy method to find a minimum edge-weight anchor clique of a given size in the graph for the anchor word selection. Extensive experiments on real-world corpus demonstrate the effectiveness of the proposed anchor word selection method that outperforms the common convex hull-based methods on the revealed topic quality. Meanwhile, our method is much faster than typical SNMF based method.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
# featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/1905.06109
# url_code: https://github.com/JHL-HUST/FGPM
# url_dataset: '#'
# url_poster: publication/ATFL/ATFL_poster.pdf
# url_project: ''
# url_slides: publication/ATFL/ATFL_slides.pdf
# url_source: '#'
# url_video: '#'

---
