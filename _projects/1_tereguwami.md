---
layout: page
title: "Tereguwami"
description: "9-layer multimodal AI system bridging communication for over 4 million Ethiopian Sign Language users with generative avatars and sEMG interfaces."
img: assets/img/projects/tereguwami_thumb.svg
importance: 1
category: research
related_publications: false
---

<link rel="stylesheet" href="{{ '/assets/css/dossier.css' | relative_url }}">

<div class="dossier-wrapper" style="padding-top: 0;">

  <!-- System Header Ribbon -->
  <div class="dossier-status-bar" style="margin-bottom: 1.5rem;">
    <span class="status-live">
      <span class="status-pulse"></span>
      RESEARCH CORE // PATENT & MINISTRY BACKED
    </span>
    <span>STATUS: ACTIVE RESEARCH & TRIAL DEPLOYMENT</span>
  </div>

  <div class="dossier-section-header">
    <h2 class="dossier-hero-h1" style="font-size: 2rem; margin-bottom: 0.25rem;">Tereguwami</h2>
    <span class="dossier-section-tag">[SEC 02 // DOSSIER PROJECT 01]</span>
  </div>

  <div class="dossier-skill-tags" style="margin: 1.25rem 0 2rem 0;">
  <span class="dossier-skill-tag">Multimodal AI</span>
  <span class="dossier-skill-tag">MediaPipe</span>
  <span class="dossier-skill-tag">PyTorch</span>
  <span class="dossier-skill-tag">sEMG</span>
  <span class="dossier-skill-tag">FastAPI</span>
  <span class="dossier-skill-tag">WebRTC</span>
</div>


  <div class="dossier-cta-row" style="margin: 2rem 0 1.5rem 0;">
  <a href="{{ '/assets/pdf/tereguwami_paper.pdf' | relative_url }}" class="dossier-btn-primary" target="_blank" rel="noopener noreferrer">
    <i class="fa-solid fa-file-pdf"></i>
    <span>Read Technical Paper</span>
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
      <p>Tereguwami is an end-to-end multimodal translation architecture engineered to eliminate systemic communication barriers for over 4 million Deaf and hard-of-hearing individuals across the Horn of Africa. Backed by the Ethiopian Ministry of Innovation and Technology (MInT), the platform bridges Ethiopian Sign Language (EthSL) and spoken Amharic/Afan Oromo in real-time.</p>
    </div>
  </section>

  <section class="dossier-section">
    <div class="dossier-section-header">
      <h3 class="dossier-section-title">Technical Architecture & Engineering</h3>
      <span class="dossier-section-tag">[ARCHITECTURE]</span>
    </div>
    <div class="dossier-bio-narrative">
- **Kinematic & Spatial Tracking**: Dual MediaPipe pipelines capturing 543 spatial landmark points spanning finger articulation, wrist trajectories, and facial micro-expressions.
- **Temporal Gesture Disambiguation**: Bidirectional LSTM and Transformer spatial-temporal encoders with dynamic time warping to handle dialectical velocity variations.
- **Neuromuscular Grounding**: Direct telemetry ingestion from custom 4-channel surface electromyography (sEMG) armbands capturing muscular action potentials during silent signing.
- **Bidirectional Avatar Synthesis**: Generative 3D avatar rendering engine driven via WebSockets/WebRTC delivering zero-latency reciprocal communication.

    </div>
  </section>

  <section class="dossier-section">
    <div class="dossier-section-header">
      <h3 class="dossier-section-title">Demonstrated Impact</h3>
      <span class="dossier-section-tag">[OUTCOMES]</span>
    </div>
    <div class="dossier-bio-narrative">
      <p style="font-weight: 600; color: var(--sn-orange);">Deployed in regional education pilot centers; reduced translation latency from 4.2 seconds to under 420ms on edge hardware.</p>
    </div>
  </section>

</div>
