---
title: "Improving Classification of Tetanus Severity for Patients in Low-Middle Income Countries Wearing ECG Sensors by Using a CNN-Transformer Network"
authors:
- admin
- "et al."


date: "2022-10-21"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-26T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Biomedical Engineering*"
publication_short: ""

abstract: Tetanus is a life-threatening infectious disease, which is still common in low- and middle-income countries, including in Vietnam. This disease is characterized by muscle spasm and in severe cases is complicated by autonomic dysfunction. Ideally continuous vital sign monitoring using bedside monitors allows the prompt detection of the onset of autonomic nervous system dysfunction or avoiding rapid deterioration. Detection can be improved using heart rate variability analysis from ECG signals. Recently, characteristic ECG and heart rate variability features have been shown to be of value in classifying tetanus severity. However, conventional manual analysis of ECG is time-consuming. The traditional convolutional neural network (CNN) has limitations in extracting the global context information, due to its fixed-sized kernel filters. In this work, we propose a novel hybrid CNN-Transformer model to automatically classify tetanus severity using tetanus monitoring from low-cost wearable sensors. This model can capture the local features from the CNN and the global features from the Transformer. The time series imaging - spectrogram - is transformed from one-dimensional ECG signal and input to the proposed model. The CNN-Transformer model outperforms state-of-the-art methods in tetanus classification, achieves results with a F1 score of 0.82±0.03 , precision of 0.94±0.03 , recall of 0.73±0.07 , specificity of 0.97±0.02 , accuracy of 0.88±0.01 and AUC of 0.85±0.03 . In addition, we found that Random Forest with enough manually selected features can be comparable with the proposed CNN-Transformer model.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9926154' 
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
