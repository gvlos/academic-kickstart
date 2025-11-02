---
title: "Power Grid Control with Graph-Based Distributed Reinforcement Learning}"
authors: ""
date: "2025-09-03T00:00:00Z"
doi: "10.48550/arXiv.2509.02861"

# Schedule page publish date (NOT publication's date).
# publishDate: "2020-04-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ECML-PKDD 2025, Machine Learning for Sustainable Power Systems workshop"
# publication_short: In *Electronics 2020, 9, 758*

abstract: "The necessary integration of renewable energy sources, combined with the expanding scale of power networks, presents significant challenges in controlling modern power grids. Traditional control systems, which are human and optimization-based, struggle to adapt and to scale in such an evolving context, motivating the exploration of more dynamic and distributed control strategies. This work advances a graph-based distributed reinforcement learning framework for real-time, scalable grid management. The proposed architecture consists of a network of distributed low-level agents acting on individual power lines and coordinated by a high-level manager agent. A Graph Neural Network (GNN) is employed to encode the network's topological information within the single low-level agent's observation. To accelerate convergence and enhance learning stability, the framework integrates imitation learning and potential-based reward shaping. In contrast to conventional decentralized approaches that decompose only the action space while relying on global observations, this method also decomposes the observation space. Each low-level agent acts based on a structured and informative local view of the environment constructed through the GNN. Experiments on the Grid2Op simulation environment show the effectiveness of the approach, which consistently outperforms the standard baseline commonly adopted in the field. Additionally, the proposed model proves to be much more computationally efficient than the simulation-based Expert method."

# Summary. An optional shortened abstract.
#summary: A novel algorithm for the detection of dorsal fins is presented in the context of a fully automated pipeline for the photo-identification of Risso’s dolphins. A lightweight convolutional neural network (CNN) architecture is proposed to recognize fins among cropped images, filtering the inputs for the photo-identification algorithm.

tags:
- Power grids
- Distributed Reinforcement Learning
- Graph neural networks
featured: false

links:
# - name: Custom Link
# url: 'https://arxiv.org/abs/2409.04467'
url_pdf: 'https://arxiv.org/abs/2509.02861'
# url_code: '#'
# url_dataset: '#'
# url_poster: 'https://gvlosapio.netlify.app/publication/fact_powgrids/ECML_poster.pdf'
# url_project: ''
# url_slides: 'https://gvlosapio.netlify.app/publication/fact_powgrids/ECML_presentation.pdf'
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