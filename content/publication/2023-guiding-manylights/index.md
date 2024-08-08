---
title: 'Guiding Light Trees for Many-Light Direct Illumination'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Eric Hamann
  - admin
  - Carsten Dachsbacher

# Author notes (optional)
author_notes: ''

date: '2023-05-30T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Eurographics 2023 - Short Papers*
publication_short: In *EG Short Papers*

abstract: Path guiding techniques reduce the variance in path tracing by reusing knowledge from previous samples to build adaptive sampling distributions. The Practical Path Guiding (PPG) approach stores and iteratively refines an approximation of the incident radiance field in a spatio-directional data structure that allows sampling the incident radiance. However, due to the limited resolution in both spatial and directional dimensions, this discrete approximation is not able to accurately capture a large number of very small lights. We present an emitter sampling technique to guide next event estimation (NEE) with a global light tree and adaptive tree cuts that integrates into the PPG framework. In scenes with many lights our technique significantly reduces the RMSE compared to PPG with uniform NEE, while adding close to no overhead in scenes with few light sources. The results show that our technique can also aid the incident radiance learning of PPG in scenes with difficult visibility.

# Summary. An optional shortened abstract.
summary: ''


tags:
  - Path Guiding
  
# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://diglib.eg.org/bitstreams/01254950-f0d5-4152-9508-8fcf80058f79/download'
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
