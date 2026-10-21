---
layout: page
title: "Hiwot sEMG Silent Speech Interface"
description: "Surface electromyography (sEMG) bio-signal processing hardware and micro-controller architecture decoding neuromuscular intention into speech synthesis."
img: assets/img/projects/hiwot_thumb.svg
importance: 5
category: engineering
related_publications: false
---

<link rel="stylesheet" href="{{ '/assets/css/dossier.css' | relative_url }}">

<div class="dossier-wrapper" style="padding-top: 0;">

  <!-- System Header Ribbon -->
  <div class="dossier-status-bar" style="margin-bottom: 1.5rem;">
    <span class="status-live">
      <span class="status-pulse"></span>
      BIOMEDICAL HARDWARE // NEURAL INTERFACE
    </span>
    <span>STATUS: PROTOTYPE VALIDATED // HARDWARE LAB</span>
  </div>

  <div class="dossier-section-header">
    <h2 class="dossier-hero-h1" style="font-size: 2rem; margin-bottom: 0.25rem;">Hiwot sEMG Silent Speech Interface</h2>
    <span class="dossier-section-tag">[SEC 02 // DOSSIER PROJECT 05]</span>
  </div>

  <div class="dossier-skill-tags" style="margin: 1.25rem 0 2rem 0;">
  <span class="dossier-skill-tag">Arduino</span>
  <span class="dossier-skill-tag">sEMG Biosensors</span>
  <span class="dossier-skill-tag">Signal Processing</span>
  <span class="dossier-skill-tag">C++</span>
  <span class="dossier-skill-tag">Hardware</span>
  <span class="dossier-skill-tag">Edge Computing</span>
</div>


  <div class="dossier-cta-row" style="margin: 2rem 0 1.5rem 0;">
  <a href="{{ '/assets/pdf/hiwot_certificate.pdf' | relative_url }}" class="dossier-btn-primary" target="_blank" rel="noopener noreferrer">
    <i class="fa-solid fa-file-pdf"></i>
    <span>View Engineering Certificate</span>
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
      <p>Hiwot is a wearable neural-interface hardware system designed to restore voice to individuals suffering from aphonia, vocal cord trauma, or laryngectomy. By capturing subtle neuromuscular electrical impulses on the throat and mandibular muscles, Hiwot decodes sub-vocal articulation without acoustic vibration.</p>
    </div>
  </section>

  <section class="dossier-section">
    <div class="dossier-section-header">
      <h3 class="dossier-section-title">Technical Architecture & Engineering</h3>
      <span class="dossier-section-tag">[ARCHITECTURE]</span>
    </div>
    <div class="dossier-bio-narrative">
- **Analog Front-End Design**: Custom 4-channel differential amplifier circuit with 60Hz notch filtering, 1000x gain, and active ground suppression.
- **Microcontroller Signal Filtering**: Arduino/ESP32 on-chip digital signal processing executing real-time Wavelet transforms and Root Mean Square (RMS) energy extraction.
- **Pattern Classification**: Lightweight k-NN and 1D-CNN classifier operating with low power consumption on embedded microcontrollers.
- **Real-Time Speech Synthesis**: Decoded phonetic tokens transmitted via Bluetooth Low Energy (BLE) to a companion mobile synthesizer.

    </div>
  </section>

  <section class="dossier-section">
    <div class="dossier-section-header">
      <h3 class="dossier-section-title">Demonstrated Impact</h3>
      <span class="dossier-section-tag">[OUTCOMES]</span>
    </div>
    <div class="dossier-bio-narrative">
      <p style="font-weight: 600; color: var(--sn-orange);">Recognized with national hardware innovation awards for frugal engineering and assistive technology accessibility.</p>
    </div>
  </section>

</div>
