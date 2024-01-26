---
title: "Tetanus Severity Classification in Low-Middle Income Countries through ECG Wearable Sensors and a 1D-Vision Transformer"
authors:
- admin 



date: "2024-01-19"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-26T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*BioMedInformatics*"
publication_short: ""

abstract: Tetanus, a life-threatening bacterial infection prevalent in low- and middle-income countries like Vietnam, impacts the nervous system, causing muscle stiffness and spasms. Severe tetanus often involves dysfunction of the autonomic nervous system (ANS). Timely detection and effective ANS dysfunction management require continuous vital sign monitoring, traditionally performed using bedside monitors. However, wearable electrocardiogram (ECG) sensors offer a more cost-effective and user-friendly alternative. While machine learning-based ECG analysis can aid in tetanus severity classification, existing methods are excessively time-consuming. Our previous studies have investigated the improvement of tetanus severity classification using ECG time series imaging. In this study, our aim is to explore an alternative method using ECG data without relying on time series imaging as an input, with the aim of achieving comparable or improved performance. To address this, we propose a novel approach using a 1D-Vision Transformer, a pioneering method for classifying tetanus severity by extracting crucial global information from 1D ECG signals. Compared to 1D-CNN, 2D-CNN, and 2D-CNN + Dual Attention, our model achieves better results, boasting an F1 score of 0.77 ± 0.06, precision of 0.70 ± 0. 09, recall of 0.89 ± 0.13, specificity of 0.78 ± 0.12, accuracy of 0.82 ± 0.06 and AUC of 0.84 ± 0.05.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.mdpi.com/2673-7426/4/1/16'
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
