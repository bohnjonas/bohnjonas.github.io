---
title: "Monocular Pose Estimation for Human-Robot Co-Localization"
date: 2023-04-19
authors:
    - admin
    - Michel Zeller
    - Christopher Tibaldo
    - Mae Yamaguchi
author_notes:
    - "Equal contribution"
    - "Equal contribution"
    - "Equal contribution"
    - "Equal contribution"

summary: "This work was part of the 3D Vision course at ETH Zurich held by Prof. Dr. Marc Polleyfeys.
Grade: 5.75 / 6.0"

abstract: "In a human-robot interaction scenario, it is crucial for the different agents to be able to precisely localize each other in the shared environment, i.e. to visualize a planned trajectory. However, feature-based visual registration is an arduous task because feature matching between different camera streams is computationally expensive and challenging due to different points-of-view. In this work, we propose employing a monocular pose-estimation algorithm to obtain an initial guess of the spatial relationship, that can serve as a good prior for subsequent multi-agent posegraph optimisation."

url_pdf: uploads/3DV_finalreport.pdf
url_code: "https://github.com/mizeller/Monocluar-Pose-Estimation-Pipeline-for-Spot"
url_poster: uploads/3DV_poster.pdf

tags: 
    - Pose Estimation

image:
    caption: 'From NeRF model to real-world Pose Estimation'
    focal_point: Smart
    preview_only: false

reading_time: false
share: false
---

This project was part of the **3D Vision** course at ETH Zurich held by **Prof. Dr. Marc Polleyfeys** leading the [**Computer Vision and Geometry Lab**](https://cvg.ethz.ch/). The goal of the project was to develop a monocular pose-estimation algorithm to localize boston dynamics' Spot robot in a shared environment with a human. To achieve this, we created a pipeline that uses a NeRF model to generate synthetic images of the robot in the environment, which are then used to train a pose-estimation network, [**OnePose++**](https://arxiv.org/pdf/2301.07673). The network is then used to estimate the pose of the robot in real-world images. The project was graded **5.75 / 6.0**.

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