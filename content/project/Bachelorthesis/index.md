---
title: "Automated Vessel Detection for Fetal Surgery"
date: 2021-02-18
authors:
    - admin
summary: "This work was done as part of my Bachelor Thesis at the Multi-Scale Robotics Lab at ETH Zurich, where I developed a deep learning model for automated vessel detection in fetoscopic videos.
Grade: 6.0 / 6.0"

abstract: "Twin-to-twin transfusion syndrome is a potentially severe condition in pregnancies, where twins share a single placenta. The most promising treatment is fetoscopic laser coagulation, where the clinician localises and ablates abnormal vessels to balance the blood flow between the twin fetuses again. The surgical procedure is particularly challenging due to poor visibility, challenging lighting conditions, a limited field of view of the fetoscopic camera and low overall image quality.
Automatically detecting blood vessels can help to identify all abnormalities, which facilitates the surgery. A solution using deep-learning models that creates binary segmentation is proposed. The binary segmentation can be recombined with the fetoscopic video frames to enhance the surgeons view on the placental blood vessels directly. As part of this thesis, a new dataset of 270 fetoscopic video frames is created of data acquired from a human placenta in an ex vivo setting. The video frames were annotated by an undergraduate student and used to evaluate 26 different state-of-the-art segmentation networks through cross-validation.
The best performing deep learning models resulting from the cross-validations are optimised and qualitatively evaluated on a test set. The obtained architectures can produce segmentations with a high similarity to the ground-truth annotations even outperforming the annotations of the undergraduate student in some cases.
The optimised neural networks are further used to create segmentations on video sequences, where different modalities to enhance the view on the placental blood vessel are implemented."

url_pdf: uploads/BachelorThesis.pdf
url_code: "https://github.com/bohnjonas/Fetopscopy_Python"
url_slides: uploads/BachelorThesis_finalpresentation.pdf

tags: 
    - Semantic Segmentation
    - Computer assisted surgery
    - Computer Vision
    - Deep Learning

image:
    focal_point: Smart
    preview_only: false

reading_time: false
share: false
---

To conclude my Bachelor's degree in Mechanical Engineering at ETH Zurich, I conducted a research project at the [**Multi-Scale Robotics Lab**](https://www.msrl.ethz.ch/) under the supervision of Dr. Jonas Lussi and Dr. Simone Gervasoni. The project aimed to develop a deep learning model for automated vessel detection in fetoscopic videos to support the treatment of twin-to-twin transfusion syndrome. During this project my goal was to deepen my theoretical and practical understanding of deep learning and computer vision, and to apply this knowledge to a real-world problem in the field of medical robotics. The project was graded **6.0 / 6.0**.

<button id="like-button">❤️ Like <span id="like-count">0</span></button>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const likeButton = document.getElementById("like-button");
    const likeCount = document.getElementById("like-count");

    // Use post-specific key to store likes per article
    const postID = window.location.pathname; 
    let count = localStorage.getItem(`likeCount_${postID}`) || 0;
    likeCount.textContent = count;

    likeButton.addEventListener("click", () => {
      count++;
      localStorage.setItem(`likeCount_${postID}`, count);
      likeCount.textContent = count;
    });
  });
</script>