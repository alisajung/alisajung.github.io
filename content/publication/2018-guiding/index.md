---
title: 'Selective guided sampling with complete light transport paths'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Florian Reibold
  - Johannes Hanika
  - admin
  - Carsten Dachsbacher

# Author notes (optional)
author_notes: ''

date: '2018-12-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2018-12-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Transactions on Graphics (Proceedings of SIGGRAPH Asia)*
publication_short: In *ToG (SIGGRAPH Asia)*

abstract: Finding good global importance sampling strategies for Monte Carlo light transport is challenging. While estimators using local methods (such as BSDF sampling or next event estimation) often work well in the majority of a scene, small regions in path space can be sampled insufficiently (e.g. a reflected caustic). We propose a novel data-driven guided sampling method which selectively adapts to such problematic regions and complements the unguided estimator. It is based on complete transport paths, i.e. is able to resolve the correlation due to BSDFs and free flight distances in participating media. It is conceptuall simple and places anisotropic truncated Gaussian distributions around guide paths to reconstruct a continuous probability density function (guided PDF). Guide paths are iteratively sampled from the guided as well as the unguided PDF and only recorded if they cause high variance in the current estimator. While plain Monte Carlo samples paths independently and Markov chain-based methods perturb a single current sample, we determine the reconstruction kernels by a set of neighbouring paths. This enables local exploration of the integrand without detailed balance constraints or the need for analytic derivatives. We show that our method can decompose the path space into a region that is well sampled by the unguided estimator and one that is handled by the new guided sampler. In realistic scenarios, we show 4x speedups over the unguided sampler. 

# Summary. An optional shortened abstract.
summary: We propose a guiding method that constructs new light transport paths based on previous paths from difficult regions.


tags:
  - Path Guiding
  
# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://cg.ivd.kit.edu/publications/2018/guiding/guiding.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
