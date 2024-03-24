---
title: "Human motion segmentation via robust kernel sparse subspace clustering"
authors:
- admin
date: "2017-08-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-08-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Image Processing ( Volume: 27, Issue: 1, January 2018)"
publication_short: "IEEE TIP"

abstract: Studies on human motion have attracted a lot of attentions. Human motion capture data, which much more precisely records human motion than videos do, has been widely used in many areas. Motion segmentation is an indispensable step for many related applications, but current segmentation methods for motion capture data do not effectively model some important characteristics of motion capture data, such as Riemannian manifold structure and containing non-Gaussian noise. In this paper, we convert the segmentation of motion capture data into a temporal subspace clustering problem. Under the framework of sparse subspace clustering, we propose to use the geodesic exponential kernel to model the Riemannian manifold structure, use correntropy to measure the reconstruction error, use the triangle constraint to guarantee temporal continuity in each cluster and use multi-view reconstruction to extract the relations between different joints. Therefore, exploiting some special characteristics of motion capture data, we propose a new segmentation method, which is robust to non-Gaussian noise, since correntropy is a localized similarity measure. We also develop an efficient optimization algorithm based on block coordinate descent method to solve the proposed model. Our optimization algorithm has a linear complexity while sparse subspace clustering is originally a quadratic problem. Extensive experiment results both on simulated noisy data set and real noisy data set demonstrate the advantage of the proposed method.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://ieeexplore.ieee.org/abstract/document/8007249/
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

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

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
