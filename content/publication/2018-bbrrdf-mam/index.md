---
title: 'A Simple Diffuse Fluorescent BBRRDF Model'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Johannes Hanika
  - Steve Marschner
  - Carsten Dachsbacher

# Author notes (optional)
author_notes: ''

date: '2018-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2018-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *MAM 2018: Eurographics Workshop on Material Appearance Modeling*
publication_short: In *MAM*

abstract: Todo
#Fluorescence — the effect of a photon being absorbed at one wavelength and re-emitted at another — is present in many common materials such as clothes and paper. Yet there has been little research in rendering or modeling fluorescent surfaces. We discuss the design decisions leading to a simple model for a diffuse fluorescent BBRRDF (bispectral bidirectional reflection and reradiation distribution function). In contrast to reradiation matrix based models our model is continuous in wavelength space. It can be parameterized by artificially designed spectra as well as by many publicly available physical measurements. It combines fluorescence and non-fluorescent reflectance, as most real- world materials are not purely fluorescent but also reflect some light without changing its wavelength. With its simple parameterization the BBRRDF is intended as a starting point for any physically based spectral rendering system aiming to simulate fluorescence. To that end we show how to continuously sample both incident and exitant wavelengths from our BBRRDF which makes it suitable for bidirectional transport, and we discuss energy and photon conservation in the context of fluorescence. 

# Summary. An optional shortened abstract.
summary: We present an analytical BBRRDF model that separates reflectance and fluorescence into spectra.


tags:
  - Fluorescence
  - Materials

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://cg.ivd.kit.edu/publications/2018/fluor_brdf/fluor_brdf.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://cg.ivd.kit.edu/publications/2018/fluor_brdf/fluor_brdf_slides.pdf'
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
