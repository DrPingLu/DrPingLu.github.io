---
title: "Dynamic spatio-temporal graph convolutional networks for cardiac motion analysis"
authors:
- admin 



date: "2021 IEEE 18th International Symposium on Biomedical Imaging (ISBI)"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-25T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*2021 IEEE 18th International Symposium on Biomedical Imaging (ISBI)*"
publication_short: ""

abstract: We propose a dynamic spatio-temporal graph convolutional network (DST-GCN) approach to learn the left ventricular (LV) motion patterns from cardiac MR cine images. We represent the myocardial geometry using a graph that is constructed from sample nodes on endo- and epicardial contours. The DST-GCN follows an encoder-decoder framework. The encoder accepts a given cardiac motion represented by a sequence of ST-GCN. The decoder employs a graph-based gated recurrent unit (G-GRU) to predict future cardiac motion. We show that the DST-GCN can automatically quantify the spatio-temporal patterns in cardiac MR that characterise cardiac motion. Experiments are performed on the UK Biobank dataset. We compare four methods from two architecture variances. Experiments show that the proposed method inputting node velocities with residual connection in the decoder outperform others, and achieves a mean squared error of 0.135 pixel between the ground truth node locations and our prediction.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9433890?casa_token=eEipFeM73qwAAAAA:HKp7a8duoq4xcLM9Til_pAPHc1UFktJpYWMxQCQAwOZPQLm5swDwxCOYCRkEsz1lerQJLWY' 
# url_code: ''
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: **Ping Lu**' #(https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

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
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
