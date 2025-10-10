---
layout: single
title: "Talks and Presentations"
permalink: /talks/
author_profile: true
---


<!-- Slideshow: put this above your talks list -->
<style>
.slideshow {
  position: relative;
  max-width: 1000px;
  margin: 0 auto 32px;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0,0,0,.12);
  background: #000;
}
.slideshow img {
  width: 100%;
  height: auto;
  display: none;
}
.slideshow img.active {
  display: block;
  animation: fade 1s ease-in-out;
}
@keyframes fade { from {opacity: 0} to {opacity: 1} }
</style>

<div class="slideshow" id="talks-slideshow">
  <img src="/images/talks/talk1.jpg" alt="Presentation 1" class="active">
  <img src="/images/talks/talk2.jpg" alt="Presentation 2">
  <img src="/images/talks/talk3.jpg" alt="Presentation 3">
  <img src="/images/talks/talk4.jpg" alt="Presentation 4">
</div>

<script>
(function(){
  const box = document.getElementById('talks-slideshow');
  const slides = box.querySelectorAll('img');
  let i = 0;
  setInterval(() => {
    slides[i].classList.remove('active');
    i = (i + 1) % slides.length;
    slides[i].classList.add('active');
  }, 4000); // change every 4 seconds
})();
</script>


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
