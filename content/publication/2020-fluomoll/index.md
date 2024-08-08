---
title: 'Spectral Mollification for Bidirectional Fluorescence'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Johannes Hanika
  - Carsten Dachsbacher

# Author notes (optional)
author_notes: ''

date: '2020-07-13T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-07-13T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Computer Graphics Forum (Proceedings of Eurographics)*
publication_short: In *CGF (Proc. of EG)*

abstract: Fluorescent materials can shift energy between wavelengths, thereby creating bright and saturated colors both in natural and artificial materials. However, rendering fluorescence for continuous wavelengths or combined with wavelength dependent path configurations so far has only been feasible using spectral unidirectional methods. We present a regularization-based approach for supporting fluorescence in a spectral bidirectional path tracer. Our algorithm samples camera and light sub-paths with independent wavelengths, and when connecting them mollifies the BSDF at one of the connecting vertices such that it reradiates light across multiple wavelengths. We discuss arising issues such as color bias in early iterations, consistency of the method and MIS weights in the presence of spectral mollification. We demonstrate our method in scenes combining fluorescence and transport phenomena that are difficult to render with unidirectional or spectrally discrete methods. 

# Summary. An optional shortened abstract.
summary: In a fluorescent context, non-fluorescent surfaces are spectral singularities, just like mirrors are singularities in the geometric domain. We enable bidirectional connections between non-fluorescent surfaces in a fluorescent bidirectional path tracer with a spectral regularization approach.


tags:
  - Regularization
  - Fluorescence

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://cg.ivd.kit.edu/publications/2020/spectral_mollification/SpectralMollificationForBidirectionalFluorescence.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=AoAbvd540I4&feature=youtu.be&t=4844'

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
