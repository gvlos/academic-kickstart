---
title: "State and Action Factorization in Power Grids"
authors: ""
date: "2024-09-03T00:00:00Z"
doi: "10.48550/arXiv.2409.04467"

# Schedule page publish date (NOT publication's date).
# publishDate: "2020-04-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ECML-PKDD 2024, Machine Learning for Sustainable Power Systems workshop"
# publication_short: In *Electronics 2020, 9, 758*

abstract: "The increase of renewable energy generation towards the zero-emission target is making the problem of controlling power grids more and more challenging. The recent series of competitions Learning To Run a Power Network (L2RPN) have encouraged the use of Reinforcement Learning (RL) for the assistance of human dispatchers in operating power grids. All the solutions proposed so far severely restrict the action space and are based on a single agent acting on the entire grid or multiple independent agents acting at the substations level. In this work, we propose a domain-agnostic algorithm that estimates correlations between state and action components entirely based on data. Highly correlated state-action pairs are grouped together to create simpler, possibly independent subproblems that can lead to distinct learning processes with less computational and data requirements. The algorithm is validated on a power grid benchmark obtained with the Grid2Op simulator that has been used throughout the aforementioned competitions, showing that our algorithm is in line with domain-expert analysis. Based on these results, we lay a theoretically-grounded foundation for using distributed reinforcement learning in order to improve the existing solutions."

# Summary. An optional shortened abstract.
#summary: A novel algorithm for the detection of dorsal fins is presented in the context of a fully automated pipeline for the photo-identification of Risso’s dolphins. A lightweight convolutional neural network (CNN) architecture is proposed to recognize fins among cropped images, filtering the inputs for the photo-identification algorithm.

tags:
- Power grids
- Distributed Reinforcement Learning
featured: false

links:
# - name: Custom Link
# url: 'https://arxiv.org/abs/2409.04467'
url_pdf: 'https://arxiv.org/abs/2409.04467'
# url_code: '#'
# url_dataset: '#'
url_poster: 'https://gvlosapio.netlify.app/publication/fact_powgrids/ECML_poster.pdf'
# url_project: ''
url_slides: 'https://gvlosapio.netlify.app/publication/fact_powgrids/ECML_presentation.pdf'
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