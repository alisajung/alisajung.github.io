---
title: 'Detecting Bias in Monte Carlo Renderers using Welch’s t-test'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Johannes Hanika
  - Carsten Dachsbacher

# Author notes (optional)
author_notes: ''

date: '2020-06-13T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-06-13T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Journal of Computer Graphics Techniques, Invited at I3D 2021*
publication_short: In *JCGT 2020, I3D 2021*

abstract:  When checking the implementation of a new renderer, one usually compares the output to that of a reference implementation. However, such tests require a large number of samples to be reliable, and sometimes they are unable to reveal very subtle differences that are caused by bias, but overshadowed by random noise. We propose using Welch’s t-test, a statistical test that reliably finds small bias even at low sample counts. Welch’s t-test is an established method in statistics to determine if two sample sets have the same underlying mean, based on sample statistics. We adapt it to test whether two renderers converge to the same image, i.e., the same mean per pixel or pixel region. We also present two strategies for visualizing and analyzing the test’s results, assisting us in localizing especially problematic image regions and detecting biased implementations with high confidence at low sample counts both for the reference and tested implementation.

# Summary. An optional shortened abstract.
summary: We use a statistical test, Welch's t test, to detect bias renderers. The text requires little memory and computational overhead and can detect even small bias at low sample counts.

tags: ''

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://jcgt.org/published/0009/02/01/paper.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/dwi5qJ6oPjE?t=8837'

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
