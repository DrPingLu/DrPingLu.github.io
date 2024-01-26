---
title: '2D-WinSpatt-Net: A Dual Spatial Self-Attention Vision Transformer Boosts Classification of Tetanus Severity for Patients Wearing ECG Sensors in Low-and Middle-Income Countries'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Robert Ford

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-09-06'
doi: 'https://doi.org/10.3390/s23187705'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-26T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Sensors*
#publication_short: In *ICW*

abstract: Tetanus is a life-threatening bacterial infection that is often prevalent in low- and middle-income countries (LMIC), Vietnam included. Tetanus affects the nervous system, leading to muscle stiffness and spasms. Moreover, severe tetanus is associated with autonomic nervous system (ANS) dysfunction. To ensure early detection and effective management of ANS dysfunction, patients require continuous monitoring of vital signs using bedside monitors. Wearable electrocardiogram (ECG) sensors offer a more cost-effective and user-friendly alternative to bedside monitors. Machine learning-based ECG analysis can be a valuable resource for classifying tetanus severity; however, using existing ECG signal analysis is excessively time-consuming. Due to the fixed-sized kernel filters used in traditional convolutional neural networks (CNNs), they are limited in their ability to capture global context information. In this work, we propose a 2D-WinSpatt-Net, which is a novel Vision Transformer that contains both local spatial window self-attention and global spatial self-attention mechanisms. The 2D-WinSpatt-Net boosts the classification of tetanus severity in intensive-care settings for LMIC using wearable ECG sensors. The time series imaging—continuous wavelet transforms—is transformed from a one-dimensional ECG signal and input to the proposed 2D-WinSpatt-Net. In the classification of tetanus severity levels, 2D-WinSpatt-Net surpasses state-of-the-art methods in terms of performance and accuracy. It achieves remarkable results with an F1 score of 0.88 ± 0.00, precision of 0.92 ± 0.02, recall of 0.85 ± 0.01, specificity of 0.96 ± 0.01, accuracy of 0.93 ± 0.02 and AUC of 0.90 ± 0.00.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.mdpi.com/1424-8220/23/18/7705/pdf'
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
  caption: 'Image credit: [**Ping Lu**] #(https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
