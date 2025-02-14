---
title: "Study on a Robotic Arm for Sampling Lunar Regolith"
date: 2020-07-01
authors:
    - admin
summary: "This project was part of the Studies on Mechatronics course in collaboration with Airbus Defence and Space. Grade 6.0 / 6.0"

abstract: "In-situ resource utilization is a key technology to reduce the cost of space exploration and increase the duration of manned missions. While the chemical concept
of resource utilization exists, the question of sampling and transporting regolith to
the reactor chamber remains unsolved.
As part of the Studies on Mechatronics, first an overview over space manipulators
and science tools is given. Building on this overview, the Studies on Mechatronics
aims at developing a concept for a robotic arm and operational concept, which is
placed on a commercial landing platform with tight space. The arm is aimed to
sample regolith from the lunar surface and performs various pick and place tasks
on the lander.
A 7-DOF robotic arm placed underneath the lander platform with a two-finger
gripper end-effector is the foundation to solve the problem. The robotic arm is
combined with a dedicated ”universal” interface that allows to pick up regolith
sampling tools and serves as an interface for manipulating. The manipulations that
are required to be done are very diverse including filtering, filling, and twisting, and
more."

url_pdf: uploads/SoM_finalreport.pdf
url_slides: uploads/SoM_finalpresentation.pdf

links:
- name: Reference Letter
  url: uploads/Reference_RSL.pdf


image:
    caption: 'Concept of the robotic arm for sampling lunar regolith'
    focal_point: Smart
    preview_only: false

reading_time: false
share: false
---

This project was part of the *Studies on Mechatronics* project which is part of the Bachelor's degree with Focus in Mechatronics at ETH Zurich. I chose this particular project to gain first experience in the field of robotics and to work on a real-world problem in collaboration with **Airbus Defence and Space**. During the project, I prepared weekly meetings with the project supervisor, conducted literature research, and developed a concept for a robotic arm and operational concept for sampling lunar regolith.

The project was conducted under the supervision of Dr. Hendrik Kolvenbach at the [**Robotic Systems Lab**](https://rsl.ethz.ch/), led by Prof. Dr. Marco Hutter, and was graded **6.0 / 6.0**.

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