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
links:
- name: Abstract EMEA 2024
  url: uploads/EMEA_Abstract.pdf

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

This work resulted from my Semester Project at the [Center for Project-Based Learning]{https://pbl.ee.ethz.ch/}. The goal was to develop a low-power object detection system that uses different sensor modalities to improve detection performance in challenging light conditions that could run on resource-constrained devices such as the GAP9 processor. The resulting network was 15x smaller and 7x faster than a conventional object detection network, making it suitable for real-time applications on edge devices.

My work was later accepted for demonstration at the [Edge AI Foundation EMEA 2024](https://www.edgeaifoundation.org/events/emea-2024), where the results were presented to an audience of industry professionals and researchers.


The project was graded **5.75 / 6.0**. 

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
