---
title: Advanced Medical Image Analysis of the Human Facial Nerve Based on Machine Learning Technologies
summary: Facial nerve segmentation for surgical planning of robotic cochlear implantation
tags:
  - Deep Learning
date: '2017-05-18T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'http://www.nanotera.ch/projects/362.php#desc'

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/PingLu02530767
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

It is a challenge for people, especially children, to speak, improve language, and communicate without hearing. In addition, if people cannot hear any sounds, they will feel isolated. At this point, cochlear implantation has become widely used as a treatment for people with a severe to profound sensorineural hearing loss and not benefiting from hearing aids. A cochlear implant is an electrical device, which uses the electrical signal to imitate the sound waves, as replacement of the damaged part of the inner ear. The implanted electrode stimulates the hearing nerve inside the cochlea in order to transfer the signal to the brain, which enables the person to hear.

Minimally invasive cochlear implantation is one representative case of microsurgical navigation technologies, that reduces the potential surgical trauma of the conventional cochlear implant surgery. The drill passes through the facial recess to the round window via a tiny trajectory, instead of milling a big hole. It is crucial that the drill does not hurt any critical structures, especially the facial nerve, which has the highest priority for protection. If the facial nerve is damaged, the patient will lose facial movement. Therefore, it is important to accurately segment the facial nerve in surgical planning for computing an optimal drill trajectory.

In addition, Computed Tomography (CT) or Cone-beam computed tomography (CBCT) used for surgical planning, features a low image resolution in relation to the small structure of interest, as well as patient motion artifacts. For these two main reasons, the CT or CBCT images are often blurred and visualizing the border of anatomical structures becomes difficult, which makes it extremely challenging to do the surgical planning in a precise way.

It is hypothesised in this thesis that an advanced CT-based image analysis of the ear can lead to a highly accurate facial nerve segmentation for micro-IGS cochlear implantation. This thesis presents two main works for personalized planning of cochlear implantation in robotic image-guided systems, which is developed at the University of Bern. The first task is related to motion detection. In order to estimate patient head movement, we developed an image-based pipeline. Experimental results demonstrate that the proposed approach to estimate head motion is feasible.

The second task is related to highly accurate facial segmentation from CT/CBCT images. A super-resolution strategy was developed and applied for image enhancement and sub-pixel classification.

For image enhancement, facial nerve image enhancement was developed using supervised learning based on multi-output Extra Tree regressor. The enhanced image is passed to a surgical planning software, OtoPlan, and facial nerve is segmented from OtoPlan. Segmentation from the enhanced CBCT and the original CBCT showed the enhanced CBCT with the proposed approach improves the segmentation.

For sub-pixel classification, an automatic random forest based super-resolution classification (SRC) framework is proposed for facial nerve segmentation refinement. In order to reduce computational time, a band-based region of interest selection (ROI) segmentation results from initial segmentation is selected. Then, SRC works on these ROI segmentation results for facial nerves segmentation.

Preliminary results on 3D CBCT and CT ex-vivo datasets achieved a segmentation accuracy with a Dice coefficient of 0.818±0.052, surface-to-surface distance of 0.121±0.030mm, and Hausdorff distance of 0.715±0.169mm. Compared with two other semi-automated segmentation software tools, ITK-SNAP and GeoS, the proposed method shows accurate segmentations at sub-voxel accuracy.
