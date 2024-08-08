---
title: 'Improving Spectral Upsampling with Fluorescence'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Lars König
  - admin
  - Carsten Dachsbacher

# Author notes (optional)
author_notes: ''

date: '2020-06-29T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-06-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Workshop on Material Appearance Modeling*
publication_short: In *MAM*

abstract: Modern photorealistic rendering simulates spectral behaviour of light. Since many assets are still created in different RGB color spaces, spectral upsampling of the RGB colors to a spectral representation is required to use them in a spectral renderer. Limiting the upsampled spectra to physically valid and natural, i.e. smooth, spectra results in a more realistic image, but decreases the size of the gamut of colors that can be recreated. In order to upsample wide gamut color spaces with colors outside the gamut of physically valid reflectance spectra, a previous approach added fluorescence to create accurate and physically valid representations. We extend this approach to increase the realism and accuarcy while considering memory and computation time. 

# Summary. An optional shortened abstract.
summary: We improve upon our previous fluorescent spectral uplifting paper with different error metrics for faster convergence and alternative fluorescence parameterizations.

tags:
  - Fluorescence
  - Spectral Upsampling

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://cg.ivd.kit.edu/publications/2020/mam_uplifting/paper.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=QkP5u4yXTQA&feature=youtu.be&t=2132'

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
