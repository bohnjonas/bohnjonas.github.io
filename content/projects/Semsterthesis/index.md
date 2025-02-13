---
title: "Clear as Day: Low-Power Object Detection for Challenging Conditions"
date: 2024-02-01
authors:
    - admin
summary: "This work was done as part of my Semester Project at the Center for Project-Based Learning.
Grade: 5.75 / 6.0"


abstract: "This work explores sensor fusion for object detection in challenging light conditions using
the flexx2 3D camera. The focus is on integrating infrared and depth data to enhance
object detection performance on resource-constrained and low-power devices, particularly
in robotics and autonomous systems where efficiency and accuracy in object detection
are crucial under varied environmental conditions. As part of this work, a novel dataset
for object detection combining infrared and depth data is introduced, employing the
Faster Objects, More Objects (FOMO) model for sensor fusion. The thesis showcases
the feasibility of using sensor fusion and FOMO for fast and low-power object detection
on constrained devices."

url_pdf: "uploads/ST_finalreport.pdf"
url_code: "https://git.ee.ethz.ch/pbl/hs2023/jonas-bohn"
url_slides: uploads/ST_presentation.pdf

tags: 
    - Object Detection
    - Sensor Fusion
    - Low-Light
    - Deep Learning

image:
    caption: 'Example of sensor fusion for object detection using infrared and grayscale images'
    focal_point: Smart
    preview_only: false

reading_time: false
share: false

---

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
