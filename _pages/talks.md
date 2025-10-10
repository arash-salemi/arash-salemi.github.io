---
layout: single
title: "Talks and Presentations"
permalink: /talks/
author_profile: true
---

<!-- Pure CSS slideshow (no JS) -->
<style>
.slideshow {
  position: relative;
  width: 50%;              /* make it smaller (was 75%) */
  margin: 0 auto 32px;     /* center + spacing below */
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0,0,0,.15);
  background: #000;
}
.slideshow img {
  position: absolute;
  inset: 0;                /* top:0; right:0; bottom:0; left:0 */
  width: 100%;
  height: auto;
  opacity: 0;
  animation: slideCycle 20s infinite; /* 4 images × 5s each = 20s */
}

/* Stagger the start time for each image */
.slideshow img:nth-child(1) { animation-delay: 0s;  }
.slideshow img:nth-child(2) { animation-delay: 5s;  }
.slideshow img:nth-child(3) { animation-delay: 10s; }
.slideshow img:nth-child(4) { animation-delay: 15s; }

/* Fade in (0–1s), show (1–4s), fade out (4–5s), stay hidden otherwise */
@keyframes slideCycle {
  0%   { opacity: 0; }
  5%   { opacity: 1; }
  25%  { opacity: 1; }
  30%  { opacity: 0; }
  100% { opacity: 0; }
}
</style>

<div class="slideshow">
  <img src="/images/talks/talk1.jpg" alt="Presentation 1">
  <img src="/images/talks/talk2.jpg" alt="Presentation 2">
  <img src="/images/talks/talk3.jpg" alt="Presentation 3">
  <img src="/images/talks/talk4.jpg" alt="Presentation 4">
</div>


**Real-Time Modeling of Human Motor Learning in Robot-Aided Training**  
*May 9, 2025*  
Biomedical Engineering Research Day, University of Alberta, Edmonton, Canada  

**Accessible Precision Healthcare: AI-Enabled Technologies for Quantitative Assessment of Motor Function & Personalized Motor Training**  
*October 11, 2024*  
iSMART Talk, University of Alberta, Edmonton, Canada  

**Using Multi-Modal Emotion Recognition and Decision-Making Systems to Personalize Gaming Experience Based on Player Emotions**  
*November 12–13, 2024*  
Alberta Robotics & Intelligent Systems Expo (Alberta RISE 2024), Edmonton, Canada  

**Emotion-Driven Game Personalization: Integrating Vision Transformers and Recommender Systems to Personalize User Experience**  
*October 25–27, 2024*  
25th Annual Alberta Biomedical Engineering Conference (Alberta BME 2024), Banff, Canada  

**Enhancing Engagement Level Detection During Gameplay Using a Multi-Modal Vision Transformer Model**  
*September 6, 2024*  
Reverse EXPO 2024, University of Alberta, Edmonton, Canada  

**Integrating Webcam Image and User Log Data for Enhanced Affective State Analysis in Human-Computer Interaction During Gameplay**  
*August 13–15, 2024*  
Faculty of Engineering Graduate Research Symposium (FEGRS), Edmonton, Canada  
