---
title: Open Source AI-enabled Smart Inhaler for Asthmatic Patients
date: 2025-01-31
authors:
    - Patrick Langer
    - admin
summary: "Development of a novel open source smart inhaler compatible with the three most common asthma inhaler types. Using passive sensors such as accelerometers to infer inhaler usage using machine learning. Grade: 6.0 / 6.0"
reading_time: false
share: false

---

This project was resulting as part of the Master's Thesis at the [**ADAMMA - Core for AI & Digital Biomarker Research**](https://adamma.ethz.ch/) at ETH Zurich in collaboration and supervision from Patrick Langer. The project aimed to develop a novel open-source smart inhaler compatible with the three most common asthma inhaler types (MDI, Turbohaler and Diskus). The smart inhaler uses passive sensors such as accelerometers to infer inhaler usage using machine learning. The project was done in collaboration with doctors and patients from the University Children's Hospital in Basel, where the smart inhaler was tested in a clinical study. The goal of the project was to develop a tool that can help patients with asthma to better manage their disease and to provide doctors with more accurate data on the patient's inhaler usage.

This work is currently **under review** for **publication**, more details, code and data will be available soon.

The Master Thesis was graded **6.0 / 6.0**.

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
