---
layout: page
title: "MeskelFlow"
description: "Edge-native computer vision and urban traffic flow intelligence designed for high-density, heterogeneous intersection dynamics in Addis Ababa."
img: assets/img/projects/meskel_thumb.svg
importance: 2
category: software
related_publications: false
---

<link rel="stylesheet" href="{{ '/assets/css/dossier.css' | relative_url }}">

<div class="dossier-wrapper" style="padding-top: 0;">

  <!-- System Header Ribbon -->
  <div class="dossier-status-bar" style="margin-bottom: 1.5rem;">
    <span class="status-live">
      <span class="status-pulse"></span>
      PRODUCTION SYSTEM // URBAN AI
    </span>
    <span>STATUS: PILOT TESTED // MESKEL SQUARE CORRIDOR</span>
  </div>

  <div class="dossier-section-header">
    <h2 class="dossier-hero-h1" style="font-size: 2rem; margin-bottom: 0.25rem;">MeskelFlow</h2>
    <span class="dossier-section-tag">[SEC 02 // DOSSIER PROJECT 02]</span>
  </div>

  <div class="dossier-skill-tags" style="margin: 1.25rem 0 2rem 0;">
  <span class="dossier-skill-tag">Computer Vision</span>
  <span class="dossier-skill-tag">YOLOv8</span>
  <span class="dossier-skill-tag">DeepSORT</span>
  <span class="dossier-skill-tag">ONNX Runtime</span>
  <span class="dossier-skill-tag">Edge AI</span>
  <span class="dossier-skill-tag">OpenCV</span>
</div>


  <div class="dossier-cta-row" style="margin: 2rem 0 1.5rem 0;">
  <a href="{{ '/assets/pdf/meskelflow_poster.pdf' | relative_url }}" class="dossier-btn-primary" target="_blank" rel="noopener noreferrer">
    <i class="fa-solid fa-file-pdf"></i>
    <span>View Research Poster</span>
  </a>
  <a href="https://github.com/SegniNegasa123" class="dossier-btn-secondary" target="_blank" rel="noopener noreferrer">
    <i class="fa-brands fa-github"></i>
    <span>View Source Code</span>
  </a>
</div>


  <section class="dossier-section">
    <div class="dossier-section-header">
      <h3 class="dossier-section-title">System Overview</h3>
      <span class="dossier-section-tag">[OVERVIEW]</span>
    </div>
    <div class="dossier-bio-narrative">
      <p>MeskelFlow tackles the chaotic mobility bottlenecks of Addis Ababa's iconic Meskel Square and major arterial roundabouts. Traditional traffic models fail in environments where mini-buses, pedestrians, donkey carts, and emergency vehicles share unlaned asphalt. MeskelFlow implements localized edge-inference to quantify density vectors and predict gridlock 12 minutes in advance.</p>
    </div>
  </section>

  <section class="dossier-section">
    <div class="dossier-section-header">
      <h3 class="dossier-section-title">Technical Architecture & Engineering</h3>
      <span class="dossier-section-tag">[ARCHITECTURE]</span>
    </div>
    <div class="dossier-bio-narrative">
- **Custom Localized Weights**: Fine-tuned YOLOv8 model trained on 14,000 annoted frames of East African vehicular typologies (blue-and-white taxis, Isuzu trucks, Bajajs).
- **Occlusion-Resistant Tracking**: Modified DeepSORT tracking with Kalmar velocity filters resilient to severe visual occlusion in extreme density.
- **Edge Deployment Pipeline**: Quantized ONNX FP16 runtime executing on low-cost NVIDIA Jetson and Raspberry Pi micro-clusters at 34 FPS.
- **Signal Optimization Agent**: Reinforcement learning controller computing dynamic green-light duty cycles, reducing queue dwell time by 28% in simulation.

    </div>
  </section>

  <section class="dossier-section">
    <div class="dossier-section-header">
      <h3 class="dossier-section-title">Demonstrated Impact</h3>
      <span class="dossier-section-tag">[OUTCOMES]</span>
    </div>
    <div class="dossier-bio-narrative">
      <p style="font-weight: 600; color: var(--sn-orange);">Validated across 3 high-congestion corridors in Addis Ababa; presented to municipal traffic engineering authorities.</p>
    </div>
  </section>

</div>
