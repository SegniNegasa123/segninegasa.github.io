---
layout: page
title: Repositories
permalink: /repositories/
description: Open-source machine learning architectures, edge inference pipelines, and production civic SaaS repositories.
nav: true
nav_order: 5
---

<link rel="stylesheet" href="{{ '/assets/css/dossier.css' | relative_url }}">

<div class="dossier-wrapper" style="padding-top: 0;">

  <!-- System Header Ribbon -->
  <div class="dossier-status-bar" style="margin-bottom: 2rem;">
    <span class="status-live">
      <span class="status-pulse"></span>
      CODE ARTIFACTS // OPEN SCIENCE &amp; APPLIED AI
    </span>
    <span>USER: @SegniNegasa123 // GITHUB &amp; ZENODO</span>
  </div>

  <div class="dossier-bio-narrative" style="margin-bottom: 2.5rem;">
    <p>
      I adhere to open science principles: publishing reproducible machine learning models, quantified edge weights, and complete system architectures. Below are core production codebases spanning multimodal sign language translation, biomimetic computational fluid dynamics, urban traffic reinforcement learning, and enterprise EdTech SaaS engines.
    </p>
  </div>

  <!-- ==================== REPOSITORY 1: TEREGUWAMI ==================== -->
  <div class="dossier-info-card" style="margin-bottom: 2rem; padding: 1.75rem; border-left: 4px solid var(--sn-orange);">
    <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap; gap: 0.5rem; margin-bottom: 0.75rem;">
      <div>
        <h3 style="font-size: 1.35rem; font-weight: 700; color: var(--sn-navy); margin-bottom: 0.25rem;">
          <i class="fa-brands fa-github" style="color: var(--sn-orange); margin-right: 0.5rem;"></i>
          Tereguwami-
        </h3>
        <span style="font-size: 0.95rem; font-weight: 600; color: var(--sn-orange);">
          9-Layer Spatio-Temporal Graph Convolutional Architecture &amp; ONNX Edge Quantization
        </span>
      </div>
      <div style="display: flex; gap: 0.5rem; flex-wrap: wrap;">
        <a href="https://github.com/SegniNegasa123/Tereguwami-" target="_blank" rel="noopener noreferrer" class="dossier-btn-primary" style="padding: 0.35rem 0.85rem; font-size: 0.85rem;">
          <i class="fa-brands fa-github"></i> View Source
        </a>
        <a href="{{ '/assets/pdf/tereguwami_paper.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer" class="dossier-btn-secondary" style="padding: 0.35rem 0.85rem; font-size: 0.85rem;">
          <i class="fa-solid fa-file-pdf"></i> Read Paper
        </a>
      </div>
    </div>

    <p style="font-size: 0.95rem; line-height: 1.6; margin-bottom: 1rem;">
      Core open-source repository for <strong>Tereguwami</strong>, the Ministry of Innovation and Technology (MinT)-backed 9-layer multimodal framework for Ethiopian Sign Language (EthSL) translation. Features real-time landmark tracking, ST-GCN spatial skeletal topology modeling, sEMG signal disambiguation, and generative avatar speech-to-sign rendering.
    </p>

    <div style="background: var(--sn-surface); padding: 1rem 1.25rem; border-radius: 6px; margin-bottom: 1.25rem; border: 1px solid var(--sn-border);">
      <h4 style="font-size: 0.85rem; font-family: var(--sn-font-mono); text-transform: uppercase; letter-spacing: 0.05em; color: var(--sn-navy); margin-bottom: 0.5rem;">
        Key Architectural Modules:
      </h4>
      <ul style="margin: 0; padding-left: 1.25rem; font-size: 0.9rem; line-height: 1.6;">
        <li><code>models/st_gcn.py</code>: 9-layer Spatio-Temporal Graph Convolutional Network processing skeletal graph node sequences.</li>
        <li><code>inference/onnx_quantizer.py</code>: INT8 quantization pipeline reducing model footprint to 14.2MB for edge Android and ARM deployment.</li>
        <li><code>sensors/semg_stream.py</code>: DSP filtering pipeline (Butterworth bandpass, notch filter) for silent-speech muscular contraction disambiguation.</li>
        <li><code>api/fastapi_gateway.py</code>: Sub-50ms WebRTC &amp; WebSocket gateway streaming synchronized 3D avatar animation vectors.</li>
      </ul>
    </div>

    <div class="dossier-skill-tags" style="margin: 0;">
      <span class="dossier-skill-tag">PyTorch</span>
      <span class="dossier-skill-tag">ST-GCN</span>
      <span class="dossier-skill-tag">MediaPipe</span>
      <span class="dossier-skill-tag">ONNX Mobile</span>
      <span class="dossier-skill-tag">sEMG Signals</span>
      <span class="dossier-skill-tag">FastAPI</span>
      <span class="dossier-skill-tag">WebRTC</span>
    </div>
  </div>

  <!-- ==================== REPOSITORY 2: BIOMIMETIC COOLING ==================== -->
  <div class="dossier-info-card" style="margin-bottom: 2rem; padding: 1.75rem; border-left: 4px solid var(--sn-orange);">
    <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap; gap: 0.5rem; margin-bottom: 0.75rem;">
      <div>
        <h3 style="font-size: 1.35rem; font-weight: 700; color: var(--sn-navy); margin-bottom: 0.25rem;">
          <i class="fa-solid fa-wind" style="color: var(--sn-orange); margin-right: 0.5rem;"></i>
          BIOMIMETIC-COOLING-SIMULATION
        </h3>
        <span style="font-size: 0.95rem; font-weight: 600; color: var(--sn-orange);">
          Computational Fluid Dynamics (CFD) for Termite-Mound Passive Structural Cooling
        </span>
      </div>
      <div style="display: flex; gap: 0.5rem; flex-wrap: wrap;">
        <a href="https://github.com/SegniNegasa123/BIOMIMETIC-COOLING-SIMULATION" target="_blank" rel="noopener noreferrer" class="dossier-btn-primary" style="padding: 0.35rem 0.85rem; font-size: 0.85rem;">
          <i class="fa-brands fa-github"></i> View Source
        </a>
        <a href="https://doi.org/10.5281/zenodo.19902133" target="_blank" rel="noopener noreferrer" class="dossier-btn-secondary" style="padding: 0.35rem 0.85rem; font-size: 0.85rem;">
          <i class="fa-solid fa-database"></i> Zenodo Dataset
        </a>
      </div>
    </div>

    <p style="font-size: 0.95rem; line-height: 1.6; margin-bottom: 1rem;">
      Scientific research dataset and simulation software investigating natural convective airflow and thermal regulation mechanisms derived from biological termite mound geometries. Published openly to Zenodo with a registered DOI for architectural sustainability and green building research in sub-Saharan climates.
    </p>

    <div style="background: var(--sn-surface); padding: 1rem 1.25rem; border-radius: 6px; margin-bottom: 1.25rem; border: 1px solid var(--sn-border);">
      <h4 style="font-size: 0.85rem; font-family: var(--sn-font-mono); text-transform: uppercase; letter-spacing: 0.05em; color: var(--sn-navy); margin-bottom: 0.5rem;">
        Key Architectural Modules:
      </h4>
      <ul style="margin: 0; padding-left: 1.25rem; font-size: 0.9rem; line-height: 1.6;">
        <li><code>simulation/mesh_generator.py</code>: Parametric 3D internal chimney mesh generator modeling varying solar thermal chimney aspect ratios.</li>
        <li><code>cfd/navier_stokes_solver.py</code>: Incompressible Navier-Stokes numerical solver modeling buoyancy-driven natural ventilation.</li>
        <li><code>data/zenodo_bundle/</code>: Open dataset capturing temperature gradients, velocity vector fields, and passive thermal damping factors.</li>
      </ul>
    </div>

    <div class="dossier-skill-tags" style="margin: 0;">
      <span class="dossier-skill-tag">Computational Fluid Dynamics</span>
      <span class="dossier-skill-tag">Python</span>
      <span class="dossier-skill-tag">Numerical Analysis</span>
      <span class="dossier-skill-tag">Zenodo DOI: 10.5281/zenodo.19902133</span>
      <span class="dossier-skill-tag">Green Architecture</span>
    </div>
  </div>

  <!-- ==================== REPOSITORY 3: DURASCHOOLS-SAAS ==================== -->
  <div class="dossier-info-card" style="margin-bottom: 2rem; padding: 1.75rem; border-left: 4px solid var(--sn-orange);">
    <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap; gap: 0.5rem; margin-bottom: 0.75rem;">
      <div>
        <h3 style="font-size: 1.35rem; font-weight: 700; color: var(--sn-navy); margin-bottom: 0.25rem;">
          <i class="fa-solid fa-school" style="color: var(--sn-orange); margin-right: 0.5rem;"></i>
          dura-schools (DuraSchools-SaaS)
        </h3>
        <span style="font-size: 0.95rem; font-weight: 600; color: var(--sn-orange);">
          Production Multi-Tenant Cloud Architecture for African Primary &amp; Secondary Schools
        </span>
      </div>
      <div style="display: flex; gap: 0.5rem; flex-wrap: wrap;">
        <a href="https://github.com/SegniNegasa123/dura-schools" target="_blank" rel="noopener noreferrer" class="dossier-btn-primary" style="padding: 0.35rem 0.85rem; font-size: 0.85rem;">
          <i class="fa-brands fa-github"></i> View Source
        </a>
      </div>
    </div>

    <p style="font-size: 0.95rem; line-height: 1.6; margin-bottom: 1rem;">
      The production codebase powering <strong>DURA Tech's</strong> flagship EdTech SaaS product, DuraSchools. Deployed across 7 Ethiopian boarding schools, this platform automates school administration, continuous assessment grading, offline-resilient parent SMS notifications, and financial ledger reconciliation, generating over <strong>350,000+ ETB</strong> in commercial gap-year revenue.
    </p>

    <div style="background: var(--sn-surface); padding: 1rem 1.25rem; border-radius: 6px; margin-bottom: 1.25rem; border: 1px solid var(--sn-border);">
      <h4 style="font-size: 0.85rem; font-family: var(--sn-font-mono); text-transform: uppercase; letter-spacing: 0.05em; color: var(--sn-navy); margin-bottom: 0.5rem;">
        Key Architectural Modules:
      </h4>
      <ul style="margin: 0; padding-left: 1.25rem; font-size: 0.9rem; line-height: 1.6;">
        <li><code>backend/tenant_router.py</code>: Dynamic multi-tenant PostgreSQL schema isolation ensuring rigorous data privacy across separate institutions.</li>
        <li><code>services/sms_dispatcher.py</code>: Asynchronous Celery + Redis worker pool delivering automated academic progress SMS to parents via localized telecom gateways.</li>
        <li><code>frontend/src/dashboards/</code>: Responsive, lightweight React dashboards optimized for low-bandwidth 3G mobile connections.</li>
      </ul>
    </div>

    <div class="dossier-skill-tags" style="margin: 0;">
      <span class="dossier-skill-tag">FastAPI</span>
      <span class="dossier-skill-tag">React</span>
      <span class="dossier-skill-tag">PostgreSQL</span>
      <span class="dossier-skill-tag">Redis</span>
      <span class="dossier-skill-tag">Multi-Tenancy</span>
      <span class="dossier-skill-tag">350K+ ETB Revenue</span>
      <span class="dossier-skill-tag">DURA Tech</span>
    </div>
  </div>

  <!-- ==================== REPOSITORY 4: MESKELFLOW-AI ==================== -->
  <div class="dossier-info-card" style="margin-bottom: 2rem; padding: 1.75rem; border-left: 4px solid var(--sn-orange);">
    <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap; gap: 0.5rem; margin-bottom: 0.75rem;">
      <div>
        <h3 style="font-size: 1.35rem; font-weight: 700; color: var(--sn-navy); margin-bottom: 0.25rem;">
          <i class="fa-solid fa-traffic-light" style="color: var(--sn-orange); margin-right: 0.5rem;"></i>
          MeskelFlow-AI
        </h3>
        <span style="font-size: 0.95rem; font-weight: 600; color: var(--sn-orange);">
          Deep Q-Networks &amp; Edge Computer Vision for Traffic Signal Optimization
        </span>
      </div>
      <div style="display: flex; gap: 0.5rem; flex-wrap: wrap;">
        <a href="https://github.com/SegniNegasa123/MeskelFlow-AI-Intelligent-Adaptive-Traffic-Management-System-Meskel-Square-Addis-Ababa" target="_blank" rel="noopener noreferrer" class="dossier-btn-primary" style="padding: 0.35rem 0.85rem; font-size: 0.85rem;">
          <i class="fa-brands fa-github"></i> View Source
        </a>
        <a href="{{ '/assets/pdf/meskelflow_poster.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer" class="dossier-btn-secondary" style="padding: 0.35rem 0.85rem; font-size: 0.85rem;">
          <i class="fa-solid fa-file-pdf"></i> View Poster
        </a>
      </div>
    </div>

    <p style="font-size: 0.95rem; line-height: 1.6; margin-bottom: 1rem;">
      An intelligent adaptive traffic signal control framework engineered specifically for the dense, irregular traffic flows of Meskel Square and major Addis Ababa intersections. Uses real-time vehicle detection with YOLOv8 running on NVIDIA Jetson edge nodes to formulate state reward vectors for a Deep Q-Network (DQN) agent that dynamically tunes signal phase splits.
    </p>

    <div style="background: var(--sn-surface); padding: 1rem 1.25rem; border-radius: 6px; margin-bottom: 1.25rem; border: 1px solid var(--sn-border);">
      <h4 style="font-size: 0.85rem; font-family: var(--sn-font-mono); text-transform: uppercase; letter-spacing: 0.05em; color: var(--sn-navy); margin-bottom: 0.5rem;">
        Key Architectural Modules:
      </h4>
      <ul style="margin: 0; padding-left: 1.25rem; font-size: 0.9rem; line-height: 1.6;">
        <li><code>vision/yolov8_tracker.py</code>: Multi-class vehicle detection &amp; ByteTrack tracking pipeline extracting queue lengths and approach speeds.</li>
        <li><code>rl/dqn_agent.py</code>: Double Deep Q-Network with prioritized experience replay learning optimal green-light phase switching.</li>
        <li><code>simulation/sumo_env.py</code>: Microscopic traffic simulation wrapper (SUMO) calibrated against empirical Addis Ababa vehicle counts.</li>
      </ul>
    </div>

    <div class="dossier-skill-tags" style="margin: 0;">
      <span class="dossier-skill-tag">YOLOv8</span>
      <span class="dossier-skill-tag">Deep Q-Networks</span>
      <span class="dossier-skill-tag">Reinforcement Learning</span>
      <span class="dossier-skill-tag">SUMO Simulation</span>
      <span class="dossier-skill-tag">OpenCV</span>
      <span class="dossier-skill-tag">Jetson Nano</span>
    </div>
  </div>

  <!-- ==================== REPOSITORY 5: HIWOT EMERGENCY TRIAGE ==================== -->
  <div class="dossier-info-card" style="margin-bottom: 2rem; padding: 1.75rem; border-left: 4px solid var(--sn-orange);">
    <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap; gap: 0.5rem; margin-bottom: 0.75rem;">
      <div>
        <h3 style="font-size: 1.35rem; font-weight: 700; color: var(--sn-navy); margin-bottom: 0.25rem;">
          <i class="fa-solid fa-truck-medical" style="color: var(--sn-orange); margin-right: 0.5rem;"></i>
          Hiwot-Emergency-Triage
        </h3>
        <span style="font-size: 0.95rem; font-weight: 600; color: var(--sn-orange);">
          Decentralized Real-Time Emergency Medical Dispatch &amp; Priority Triage Network
        </span>
      </div>
      <div style="display: flex; gap: 0.5rem; flex-wrap: wrap;">
        <a href="https://github.com/SegniNegasa123" target="_blank" rel="noopener noreferrer" class="dossier-btn-primary" style="padding: 0.35rem 0.85rem; font-size: 0.85rem;">
          <i class="fa-brands fa-github"></i> Repository
        </a>
        <a href="{{ '/assets/pdf/hiwot_certificate.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer" class="dossier-btn-secondary" style="padding: 0.35rem 0.85rem; font-size: 0.85rem;">
          <i class="fa-solid fa-certificate"></i> Certification
        </a>
      </div>
    </div>

    <p style="font-size: 0.95rem; line-height: 1.6; margin-bottom: 1rem;">
      A robust real-time emergency medical dispatch codebase designed to solve communication fragmentation during acute trauma and hospital transfers in developing urban environments. Incorporates GIS nearest-facility routing, automatic ambulance dispatching, patient severity scoring (START algorithm), and automated fallback to encrypted SMS when data networks degrade.
    </p>

    <div style="background: var(--sn-surface); padding: 1rem 1.25rem; border-radius: 6px; margin-bottom: 1.25rem; border: 1px solid var(--sn-border);">
      <h4 style="font-size: 0.85rem; font-family: var(--sn-font-mono); text-transform: uppercase; letter-spacing: 0.05em; color: var(--sn-navy); margin-bottom: 0.5rem;">
        Key Architectural Modules:
      </h4>
      <ul style="margin: 0; padding-left: 1.25rem; font-size: 0.9rem; line-height: 1.6;">
        <li><code>triage/severity_calculator.py</code>: Algorithmic patient vital prioritization implementing emergency severity triage scores.</li>
        <li><code>geo/spatial_routing.py</code>: PostGIS and OpenStreetMap spatial routing minimizing transit times to verified trauma centers.</li>
        <li><code>telecom/sms_failover.py</code>: Automatic fallover engine that converts packet stream drops into compressed SMS payload bursts.</li>
      </ul>
    </div>

    <div class="dossier-skill-tags" style="margin: 0;">
      <span class="dossier-skill-tag">FastAPI</span>
      <span class="dossier-skill-tag">WebSockets</span>
      <span class="dossier-skill-tag">PostGIS</span>
      <span class="dossier-skill-tag">Emergency Triage</span>
      <span class="dossier-skill-tag">SMS Gateway</span>
      <span class="dossier-skill-tag">Civic Tech</span>
    </div>
  </div>

</div>
