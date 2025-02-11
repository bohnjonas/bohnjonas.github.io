---
title: "Automated Vessel Detection for Fetal Surgery"
date: 2021-02-18
authors:
    - admin
summary: "This work was done as part of my Bachelor Thesis at the Multi-Scale Robotics Lab at ETH Zurich, where I developed a deep learning model for automated vessel detection in fetoscopic videos."

abstract: "Twin-to-twin transfusion syndrome is a potentially severe condition in pregnancies, where twins share a single placenta. The most promising treatment is fetoscopic laser coagulation, where the clinician localises and ablates abnormal vessels to balance the blood flow between the twin fetuses again. The surgical procedure is particularly challenging due to poor visibility, challenging lighting conditions, a limited field of view of the fetoscopic camera and low overall image quality.
Automatically detecting blood vessels can help to identify all abnormalities, which facilitates the surgery. A solution using deep-learning models that creates binary segmentation is proposed. The binary segmentation can be recombined with the fetoscopic video frames to enhance the surgeons view on the placental blood vessels directly. As part of this thesis, a new dataset of 270 fetoscopic video frames is created of data acquired from a human placenta in an ex vivo setting. The video frames were annotated by an undergraduate student and used to evaluate 26 different state-of-the-art segmentation networks through cross-validation.
The best performing deep learning models resulting from the cross-validations are optimised and qualitatively evaluated on a test set. The obtained architectures can produce segmentations with a high similarity to the ground-truth annotations even outperforming the annotations of the undergraduate student in some cases.
The optimised neural networks are further used to create segmentations on video sequences, where different modalities to enhance the view on the placental blood vessel are implemented."

url_pdf: uploads/BachelorThesis.pdf
url_code: "https://github.com/bohnjonas/Fetopscopy_Python"
url_slides: "slides.com/someone/something"

supervisor: "Prof. Dr. Marco Hutter"

tags: 
    - Semantic Segmentation
    - Computer assisted surgery
    - Computer Vision
    - Deep Learning

image:
    focal_point: Smart
    preview_only: false
---

Testing some stuff.