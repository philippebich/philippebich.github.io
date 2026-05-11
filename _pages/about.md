---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

<div class="about-card" markdown="1">

Hi! 👋 I am **Philippe Bich**, a **Research Scientist** at **Huawei Research** in Zürich, where I am part of the **AI Team** and focus on **model compression and quantization** for LLMs/VLMs.

Before joining Huawei, I completed my **Ph.D. at Politecnico di Torino** under the supervision of [Prof. Gianluca Setti](https://www.polito.it/en/staff?p=gianluca.setti), working on **AI model compression** and on making deep neural networks more efficient for resource-constrained platforms. During my Master's thesis at the **Boston University Robotics Lab** with [Prof. John Baillieul](https://www.bu.edu/eng/profile/john-baillieul/), I built a strong interest in **AI at the edge**, which later guided my doctoral research.

On this page, I try to keep track of my most recent works, talks, and publications. Feel free to reach out if any of it sparks your curiosity!

</div>


<h1 class="section-heading" id="-news">🔥 News</h1>
<ul class="news-list">
  <li>
    <span class="news-date upcoming">Jun 2026</span>
    <div class="news-body">
      🚀 <em>Coming soon:</em> <strong>“KVarN: Variance-Normalized KV-Cache Quantization Mitigates Error Accumulation in Reasoning Tasks”.</strong> Stay tuned!
    </div>
  </li>
  <li>
    <span class="news-date">May 2026</span>
    <div class="news-body">
      🎉 My paper <strong>“SINQ: Sinkhorn-Normalized Quantization for Calibration-Free Low-Precision LLM Weights”</strong> has been accepted at <strong>ICML 2026</strong>!
    </div>
  </li>
  <li>
    <span class="news-date">Feb 2026</span>
    <div class="news-body">
      🤗 <strong>SINQ</strong> is now integrated into <strong>Hugging Face Transformers</strong>! Check out the code and docs on <a href="https://github.com/huawei-csl/SINQ">GitHub</a>.
    </div>
  </li>
</ul>


<h1 class="section-heading" id="-selected-publications">📝 Selected Publications</h1>

<ul class="feat-list">
  <li>
    <div class="feat-thumb">
      <img src="images/kvarn.png" alt="KVarN preview">
      <span class="feat-badge upcoming">Coming soon</span>
    </div>
    <div class="feat-body">
      <span class="feat-title">KVarN: Variance-Normalized KV-Cache Quantization Mitigates Error Accumulation in Reasoning Tasks</span>
      <span class="feat-authors">Lorenz K. Mueller, <span class="me">Philippe Bich</span>, Chiara Boretti, Hyun Min Chang, Jiawei Zhuang, Lukas Cavigelli</span>
      <span class="feat-venue">Preprint, 2026.</span>
      <p class="feat-tldr"><strong>TL;DR:</strong> A novel state-of-the-art variance-normalized KV-cache quantization scheme that limits compounding error in long reasoning traces and beats TurboQuant by Google Research with better accuracy and lower bits.</p>
    </div>
  </li>

  <li>
    <div class="feat-thumb">
      <img src="images/sinq.png" alt="SINQ preview">
      <span class="feat-badge highlight">ICML 2026</span>
    </div>
    <div class="feat-body">
      <span class="feat-title">SINQ: Sinkhorn-Normalized Quantization for Calibration-Free Low-Precision LLM Weights</span>
      <span class="feat-authors">Lorenz K. Mueller, <span class="me">Philippe Bich</span>, Jiawei Zhuang, Ahmet Çalik, Luca Benfenati, Lukas Cavigelli</span>
      <span class="feat-venue">International Conference on Machine Learning (ICML), 2026.</span>
      <p class="feat-tldr"><strong>TL;DR:</strong> A calibration-free quantization method based on Sinkhorn normalization that delivers strong low-bit LLM weights out of the box. Integrated into 🤗 Hugging Face Transformers.</p>
    </div>
  </li>

  <li>
    <div class="feat-thumb">
      <img src="images/tpami.png" alt="TPAMI preview" style="object-position: center 75%;">
      <span class="feat-badge highlight">IEEE TPAMI 2025</span>
    </div>
    <div class="feat-body">
      <span class="feat-title">On the Universal Approximation Properties of Deep Neural Networks using MAM Neurons</span>
      <span class="feat-authors"><span class="me">Philippe Bich</span>, Andriy Enttsel, Luciano Prono, Alex Marchioni, Fabio Pareschi, Mauro Mangia, Gianluca Setti, Riccardo Rovatti</span>
      <span class="feat-venue">IEEE Transactions on Pattern Analysis and Machine Intelligence, 2025.</span>
      <p class="feat-tldr"><strong>TL;DR:</strong> Theoretical foundations showing that Multiply-And-Max/min (MAM) neurons preserve the universal approximation property while enabling aggressive structured pruning.</p>
    </div>
  </li>
</ul>

See the [full list at the bottom of the page ↓](#-all-publications).


<h1 class="section-heading" id="-education">📖 Education</h1>

<ul class="edu-list">
  <li class="edu-institution">
    <img class="edu-logo-large" src="images/polito_logo.png" alt="Politecnico di Torino">
    <div class="edu-body">
      <span class="edu-school-name">Politecnico di Torino</span>
      <ul class="edu-degree-list">
        <li>
          <span class="edu-degree">Ph.D. in Electrical, Electronics and Communications Engineering</span>
          <span class="edu-meta">Nov 2021 – 2025 · Advisor: Prof. Gianluca Setti · AI model compression and quantization</span>
        </li>
        <li>
          <span class="edu-degree">M.Sc. in Mechatronics Engineering — 110/110 <em>cum laude</em></span>
          <span class="edu-meta">2018 – 2021 · Master's thesis at the Boston University Robotics Lab with Prof. John Baillieul</span>
        </li>
        <li>
          <span class="edu-degree">B.Sc. in Computer Engineering — 109/110</span>
          <span class="edu-meta">2015 – 2018</span>
        </li>
      </ul>
    </div>
  </li>
</ul>


<h1 class="section-heading" id="-all-publications">📚 All Publications</h1>

<div class="pub-year-heading">2026</div>
<ul class="pub-list">
  <li class="highlight">
    <span class="pub-venue highlight">ICML</span>
    <div class="pub-body">
      <span class="pub-title">SINQ: Sinkhorn-Normalized Quantization for Calibration-Free Low-Precision LLM Weights</span>
      <span class="pub-meta">International Conference on Machine Learning (ICML), 2026.</span>
    </div>
  </li>
  <li>
    <span class="pub-venue">J-STARS</span>
    <div class="pub-body">
      <span class="pub-title">FOREST-GC: A conFOrmable Rendering Engine for Synthetic Tree Generation and Counting</span>
      <span class="pub-meta">IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 2026.</span>
    </div>
  </li>
</ul>

<div class="pub-year-heading">2025</div>
<ul class="pub-list">
  <li class="highlight">
    <span class="pub-venue highlight">TNNLS</span>
    <div class="pub-body">
      <span class="pub-title">A Multiply-And-Max/min Neuron Paradigm for Aggressively Prunable Deep Neural Networks</span>
      <span class="pub-meta">IEEE Transactions on Neural Networks and Learning Systems, vol. 36, no. 8, pp. 14414–14427, 2025.</span>
    </div>
  </li>
  <li class="highlight">
    <span class="pub-venue highlight">TPAMI</span>
    <div class="pub-body">
      <span class="pub-title">On the Universal Approximation Properties of Deep Neural Networks using MAM Neurons</span>
      <span class="pub-meta">IEEE Transactions on Pattern Analysis and Machine Intelligence, 2025.</span>
    </div>
  </li>
  <li>
    <span class="pub-venue">MLJ</span>
    <div class="pub-body">
      <span class="pub-title">Linearly-Interpretable Concept Embedding Models for Text Analysis</span>
      <span class="pub-meta">Machine Learning, vol. 114, no. 10, art. 224, 2025.</span>
    </div>
  </li>
  <li>
    <span class="pub-venue">xAI</span>
    <div class="pub-body">
      <span class="pub-title">V-CEM: Bridging Performance and Intervenability in Concept-based Models</span>
      <span class="pub-meta">World Conference on Explainable Artificial Intelligence (xAI), pp. 48–67, 2025.</span>
    </div>
  </li>
  <li>
    <span class="pub-venue">ECML PKDD</span>
    <div class="pub-body">
      <span class="pub-title">Towards Better Generalization and Interpretability in Unsupervised Concept-Based Models</span>
      <span class="pub-meta">Joint European Conference on Machine Learning and Knowledge Discovery in Databases (ECML PKDD), 2025.</span>
    </div>
  </li>
  <li>
    <span class="pub-venue">TCAS-II</span>
    <div class="pub-body">
      <span class="pub-title">MESA: A Dynamical Attention-based Pre-processing Pipeline for High-throughput Event-based Computer Vision Tasks</span>
      <span class="pub-meta">IEEE Transactions on Circuits and Systems II: Express Briefs, 2025.</span>
    </div>
  </li>
</ul>

<div class="pub-year-heading">2024</div>
<ul class="pub-list">
  <li>
    <span class="pub-venue workshop">CVPRW</span>
    <div class="pub-body">
      <span class="pub-title">Event-based Eye Tracking: AIS 2024 Challenge Survey</span>
      <span class="pub-meta">CVPR 2024 Workshops — AIS: Vision, Graphics and AI for Streaming.</span>
    </div>
  </li>
  <li>
    <span class="pub-venue">BioCAS</span>
    <div class="pub-body">
      <span class="pub-title">Memory in Motion: Exploring Leaky Integration of Time Surfaces for Event-Based Eye-Tracking</span>
      <span class="pub-meta">IEEE Biomedical Circuits and Systems Conference (BioCAS), pp. 1–5, 2024.</span>
    </div>
  </li>
  <li>
    <span class="pub-venue">AICAS</span>
    <div class="pub-body">
      <span class="pub-title">Optimizing Vision Transformers: Leveraging Max and Min Operations for Efficient Pruning</span>
      <span class="pub-meta">IEEE International Conference on Artificial Intelligence Circuits and Systems (AICAS), 2024.</span>
    </div>
  </li>
</ul>

<div class="pub-year-heading">2023</div>
<ul class="pub-list">
  <li>
    <span class="pub-venue workshop">CVPRW</span>
    <div class="pub-body">
      <span class="pub-title">Pedro: an Event-based Dataset for Person Detection in Robotics</span>
      <span class="pub-meta">CVPR 2023 Workshops — 4th International Workshop on Event-Based Vision.</span>
    </div>
  </li>
  <li>
    <span class="pub-venue">MWSCAS</span>
    <div class="pub-body">
      <span class="pub-title">Multiply-and-Max/min Neurons at the Edge: Pruned Autoencoder Implementation</span>
      <span class="pub-meta">IEEE International Midwest Symposium on Circuits and Systems (MWSCAS), 2023.</span>
    </div>
  </li>
</ul>

<div class="pub-year-heading">2022</div>
<ul class="pub-list">
  <li>
    <span class="pub-venue">ICRA</span>
    <div class="pub-body">
      <span class="pub-title">Visual Navigation Using Sparse Optical Flow and Time-to-Transit</span>
      <span class="pub-meta">IEEE International Conference on Robotics and Automation (ICRA), pp. 9397–9403, 2022.</span>
    </div>
  </li>
  <li>
    <span class="pub-venue">BioCAS</span>
    <div class="pub-body">
      <span class="pub-title">Aggressively Prunable MAM²-based Deep Neural Oracle for ECG Acquisition by Compressed Sensing</span>
      <span class="pub-meta">IEEE Biomedical Circuits and Systems Conference (BioCAS), pp. 163–167, 2022.</span>
    </div>
  </li>
</ul>
