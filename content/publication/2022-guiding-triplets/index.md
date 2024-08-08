---
title: 'Path Guiding with Vertex Triplet Distributions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Vincent Schüßler
  - Johannes Hanika
  - admin
  - Carsten Dachsbacher

# Author notes (optional)
author_notes: ''

date: '2022-07-30T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-07-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Computer Graphics Forum (Proceedings of Eurographics Symposium on Rendering 2022)*
publication_short: In *CGF (Proc. of EGSR)*

abstract: Good importance sampling strategies are decisive for the quality and robustness of photorealistic image synthesis with Monte Carlo integration. Path guiding approaches use transport paths sampled by an existing base sampler to build and refine a guiding distribution. This distribution then guides subsequent paths in regions that are otherwise hard to sample. We observe that all terms in the measurement contribution function sampled during path construction depend on at most three consecutive path vertices. We thus propose to build a 9D guiding distribution over vertex triplets that adapts to the full measurement contribution with a 9D Gaussian mixture model (GMM). For incremental path sampling, we query the model for the last two vertices of a path prefix, resulting in a 3D conditional distribution with which we sample the next vertex along the path. To make this approach scalable, we partition the scene with an octree and learn a local GMM for each leaf separately. In a learning phase, we sample paths using the current guiding distribution and collect triplets of path vertices. We resample these triplets online and keep only a fixed-size subset in reservoirs. After each progression, we obtain new GMMs from triplet samples by an initial hard clustering followed by expectation maximization. Since we model 3D vertex positions, our guiding distribution naturally extends to participating media. In addition, the symmetry in the GMM allows us to query it for paths constructed by a light tracer. Therefore our method can guide both a path tracer and light tracer from a jointly learned guiding distribution. 

# Summary. An optional shortened abstract.
summary: We guide the construction of light transport paths in difficult regions by reusing distributions of vertex triplets from previous paths.


tags:
  - Path Guiding
  
# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://cg.ivd.kit.edu/publications/2022/triplet-guiding/2022_guiding.pdf'
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
