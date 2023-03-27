---
title: "Using Focal Loss to Fight Shallow Heuristics"
authors:
- Frano Rajič
- admin
- Axel Marmet
- Tim Poštuvan
date: "2022-11-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-11-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: arXiv, the free distribution service and open-access archive
publication_short: arXiv preprint

abstract: There is no such thing as a perfect dataset. In some datasets, deep neural networks discover underlying heuristics that allow them to take shortcuts in the learning process, resulting in poor generalization capability. Instead of using standard cross-entropy, we explore whether a modulated version of cross-entropy called focal loss can constrain the model so as not to use heuristics and improve generalization performance. Our experiments in natural language inference show that focal loss has a regularizing impact on the learning process, increasing accuracy on out-of-distribution data, but slightly decreasing performance on in-distribution data. Despite the improved out-of-distribution performance, we demonstrate the shortcomings of focal loss and its inferiority in comparison to the performance of methods such as unbiased focal loss and self-debiasing ensembles. 

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: false

url_pdf: https://arxiv.org/pdf/2211.13331
url_code: 'https://github.com/m43/focal-loss-against-heuristics'

---
