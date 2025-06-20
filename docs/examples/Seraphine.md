---
layout: default
title: Seraphine
carousel: true
---

<div class="swiper" style="width:100%;max-width:600px;margin:2rem auto;">
  <div class="swiper-wrapper">
    <div class="swiper-slide">
      <img src="../images/seraphine/02-prompt.png" alt="Prompt" style="width:100%">
    </div>
    <div class="swiper-slide">
      <img src="../images/seraphine/04-progress.png" alt="Progress" style="width:100%">
    </div>
    <div class="swiper-slide">
      <img src="../images/seraphine/05-complete.png" alt="Complete" style="width:100%">
    </div>
    <div class="swiper-slide">
      <img src="../images/seraphine/06-actor.png" alt="Actor" style="width:100%">
    </div>
    <div class="swiper-slide">
      <img src="../images/seraphine/07-notes.png" alt="Notes tab" style="width:100%">
    </div>
    <div class="swiper-slide">
      <img src="../images/seraphine/08-attacks.png" alt="Attacks panel" style="width:100%">
    </div>
    <div class="swiper-slide">
      <img src="../images/seraphine/09-actions.png" alt="Actions panel" style="width:100%">
    </div>
    <div class="swiper-slide">
      <img src="../images/seraphine/10-passives.png" alt="Passives panel" style="width:100%">
    </div>
    <div class="swiper-slide">
      <img src="../images/seraphine/11-portrait.png" alt="Portrait" style="width:100%">
    </div>
    <div class="swiper-slide">
      <img src="../images/seraphine/12-statistics.png" alt="Statistics panel" style="width:100%">
    </div>
    <div class="swiper-slide">
      <img src="../images/seraphine/13-statistics.png" alt="Statistics panel" style="width:100%">
    </div>
    <!-- add more .swiper-slide blocks as needed -->
  </div>

  <!-- Navigation buttons -->
  <div class="swiper-button-prev"></div>
  <div class="swiper-button-next"></div>

  <!-- Pagination dots -->
  <div class="swiper-pagination"></div>
</div>

<script>
  document.addEventListener("DOMContentLoaded", () => {
    /* eslint-disable no-undef */
    const mySwiper = new Swiper(".swiper", {
      loop: true,
      pagination: { el: ".swiper-pagination", clickable: true },
      navigation: {
        nextEl: ".swiper-button-next",
        prevEl: ".swiper-button-prev",
      },
    });
  });
</script>

<script src="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.js"></script>
