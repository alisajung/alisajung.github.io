---
title: 'Wide Gamut Spectral Upsampling with Fluorescence'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Alexander Wilkie
  - Johannes Hanika
  - Wenzel Jakob
  - Carsten Dachsbacher

# Author notes (optional)
author_notes: ''

date: '2019-07-30T00:00:00Z'
doi: '10.1111/cgf.13773'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In *Computer Graphics Forum*
publication_short: In *CGF*

abstract: Physically based spectral rendering has become increasingly important in recent years. However, asset textures in such systems are usually still drawn or acquired as RGB tristimulus values. While a number of RGB to spectrum upsampling techniques are available, none of them support upsampling of all colours in the full spectral locus, as it is intrinsically bigger than the gamut of physically valid reflectance spectra. But with display technology moving to increasingly wider gamuts, the ability to achieve highly saturated colours becomes an increasingly important feature. Real materials usually exhibit smooth reflectance spectra, while computationally generated spectra become more blocky as they represent increasingly bright and saturated colours. In print media, plastic or textile design, fluorescent dyes are added to extend the boundaries of the gamut of reflectance spectra. We follow the same approach for rendering: we provide a method which, given an input RGB tristimulus value, automatically provides a mixture of a regular, smooth reflectance spectrum plus a fluorescent part. For highly saturated input colours, the combination yields an improved reconstruction compared to what would be possible relying on a reflectance spectrum alone. At the core of our technique is a simple parametric spectral model for reflectance, excitation, and emission that allows for compact storage and is compatible with texture mapping. The model can then be used as a fluorescent diffuse component in an existing more complex BRDF model. We also provide importance sampling routines for practical application in a path tracer.


# Summary. An optional shortened abstract.
summary: Given an input RGB tristimulus value, our method automatically provides a mixture of a regular, smooth reflectance spectrum plus a fluorescent part. For highly saturated input colours, the combination yields an improved reconstruction compared to what would be possible relying on a reflectance spectrum alone.

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://cg.ivd.kit.edu/publications/2019/uplifting/WideGamutSpectralUpsamplingWithFluorescence.pdf'
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
url_slides: 'https://cg.ivd.kit.edu/publications/2019/uplifting/fluouplift_egsr2019_public.pptx'
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

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

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
