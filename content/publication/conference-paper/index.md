---
title: "Combined Color Semantics and Deep Learning for the Automatic Detection of Dolphin Dorsal Fins"
authors:
- Vito Renò
- admin
- Flavio Forenza
- Tiziano Politi
- Ettore Stella
- Carmelo Fanizza
- Karin Hartman
- Roberto Carlucci
- Giovanni Dimauro
- Rosalia Maglietta
date: "2020-04-10T00:00:00Z"
doi: "https://doi.org/10.3390/electronics9050758"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Source Themes Conference*
publication_short: In *STC*

abstract: Photo-identification is a widely used non-invasive technique in biological studies for understanding if a specimen has been seen multiple times only relying on specific unique visual characteristics. This information is essential to infer knowledge about the spatial distribution, site fidelity, abundance or habitat use of a species. Today there is a large demand for algorithms that can help domain experts in the analysis of large image datasets. For this reason, it is straightforward that the problem of identify and crop the relevant portion of an image is not negligible in any photo-identification pipeline. This paper approaches the problem of automatically cropping cetaceans images with a hybrid technique based on domain analysis and deep learning. Domain knowledge is applied for proposing relevant regions with the aim of highlighting the dorsal fins, then a binary classification of fin vs. no-fin is performed by a convolutional neural network. Results obtained on real images demonstrate the feasibility of the proposed approach in the automated process of large datasets of Risso’s dolphins photos, enabling its use on more complex large scale studies. Moreover, the results of this study suggest to extend this methodology to biological investigations of different species.

# Summary. An optional shortened abstract.
summary: A novel algorithm for the detection of dorsal fins is presented in the context of a fully automated pipeline for the photo-identification of Risso’s dolphins. A lightweight convolutional neural network (CNN) architecture is proposed to recognize fins among cropped images, filtering the inputs for the photo-identification algorithm.

tags:
- Source Themes
featured: true

links:
url_pdf: https://doi.org/10.3390/electronics9050758
url_code: '#'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

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
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
