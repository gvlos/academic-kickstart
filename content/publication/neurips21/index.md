---
title: "Efficient kernel methods for model-independent new physics searches"
authors: ""
date: "2021-12-01T00:00:00Z"
#doi: "10.3390/electronics9050758"

# Schedule page publish date (NOT publication's date).
# publishDate: "2020-04-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*NeurIPS 2021, Machine Learning and the Physical Sciences Workshop*"
# publication_short: In *Electronics 2020, 9, 758*

abstract: "We present a novel kernel-based anomaly detection algorithm for modelindependent new physics searches. The model is based on a re-weighted version of
kernel logistic regression and it aims at learning the likelihood ratio test statistics
from simulated anomaly-free background data and experimental data. Modelindependence is enforced by avoiding any prior assumption about the presence
or shape of new physics components in the data. This is made possible by kernel
methods being non-parametric models that, given enough data, can approximate
any continuous function and adapt to potentially any type of anomaly. This model
shows dramatic advantages compared to similar neural network implementations
in terms of training times and computational resources, while showing comparable
performances. We test the model on datasets of different dimensionalities showing
that modern implementations of kernel methods are competitive options for large
scale problems."

# Summary. An optional shortened abstract.
#summary: A novel algorithm for the detection of dorsal fins is presented in the context of a fully automated pipeline for the photo-identification of Risso’s dolphins. A lightweight convolutional neural network (CNN) architecture is proposed to recognize fins among cropped images, filtering the inputs for the photo-identification algorithm.

tags:
- Efficient Machine learning
- Kernel methods
- High energy physics
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://ml4physicalsciences.github.io/2021/files/NeurIPS_ML4PS_2021_146.pdf'
# url_code: '#'
# url_dataset: '#'
# url_poster: 'https://gvlosapio.netlify.app/publication/journal-article/poster.pdf'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: 'https://weconf.eu/imeko-metrosea-2020/presentation/lightweight-and-efficient-convolutional-neural-networks-for-recognition-of-dolphin-dorsal-fins'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image: 
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---