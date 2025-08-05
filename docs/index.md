---
icon: octicons/space-24
hide:
  - toc
---

# OuSpark – Automated Results Analytics System

## Project Overview

OuSpark is a **Cross-Platform Mobile Application** and an **Automated Results Analytics System** designed to revolutionize how engineering students and faculty from Engineering Colleges affiliated with [Osmania University](https://www.osmania.ac.in/) analyze results.

<!-- Rive Animation 1 -->
<div class="canvas-container">
  <canvas id="riveCanvas1"></canvas>
</div>

## Quick Navigation

<div class="grid cards" markdown>

<!-- - [![OuSpark Logo](assets/favicon.svg)](https://ouspark.vercel.app/) -->


-  [:material-microsoft-windows:{ .lg .middle } :material-apple:{ .lg .middle } :fontawesome-brands-android:{ .lg .middle }  OuSpark Official Website](https://ouspark.vercel.app/)  

    ---

    Access official downloads for MacOS, Windows, Android, and get detailed terms and privacy policies.

-  [:material-android:{ .lg .middle } OuSpark on Google Play](https://play.google.com/store/apps/details?id=com.ou.spark&pli=1)

    ---

    Download Android App from Google Playstore. 

</div>

## Key Highlights

![key highlights](assets/images/bentodesign.png)


<!-- Rive Animation 2 -->
<div class="canvas-container">
  <canvas id="riveCanvas2"></canvas>
</div>


!!!tip "Use the App to explore how automation, analytics, and data engineering transform result transparency and insights for students and faculty"

<div align="center">
<img src='https://visitor-badge.laobi.icu/badge?page_id=mohammed-khubaib.github.io/OuSpark&left_color=%231B3041&right_color=%2323C062&left_text=OuSpark%20Docs%20Visitors&format=true'>
</div>

<!-- Rive Scripts and Styling -->
<script src="https://unpkg.com/@rive-app/canvas"></script>
<script>
  function initRive(id, src) {
    const canvas = document.getElementById(id);
    function resizeCanvas() {
      const rect = canvas.getBoundingClientRect();
      canvas.width = rect.width * devicePixelRatio;
      canvas.height = rect.height * devicePixelRatio;
    }
    resizeCanvas();
    window.addEventListener('resize', resizeCanvas);
    new rive.Rive({ src: src, canvas: canvas, autoplay: true });
  }

  initRive("riveCanvas1", "assets/features.riv");
  initRive("riveCanvas2", "assets/info_animation.riv");
</script>

<style>
  .canvas-container {
    width: 100%;
    max-width: 2160px;
    aspect-ratio: 2160 / 1350;
    margin: 2rem auto;
  }
  canvas {
    width: 100%;
    height: 100%;
    display: block;
  }
</style>
