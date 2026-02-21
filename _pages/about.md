---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Senior Researcher</a>. Domain-Embedded AI Architect.

profile:
  align: left
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Korea Institute of Civil Engineering and Building Technology (KICT)</p>
    <p>Domain-Embedded AI Architect</p>
    <p>Email: seunghwanseo@kict.re.kr</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a Senior Researcher at the Korea Institute of Civil Engineering and Building Technology (KICT), working at the intersection of stochastic mechanics, machine learning, and intelligent infrastructure systems. My research centers on a fundamental question: how can we develop reliable and interpretable AI models for engineering systems where data are heterogeneous, noisy, and uncertain? I address this by integrating probabilistic theory, uncertainty-aware representation learning, and deployable AI architectures for safety-critical applications.

My academic foundation lies in stochastic process theory. In my Master’s thesis on sand-wave formation in movable beds, I examined how microscopic random sediment motions generate macroscopic structural patterns. By connecting deterministic governing equations with probabilistic formulations such as the Kramers–Moyal and Fokker–Planck equations, I established a research philosophy centered on the interplay between stochastic behavior and emergent structure across scales.

My doctoral research extended this perspective to data-driven uncertainty modeling in heterogeneous tabular domains. In my Ph.D. dissertation, “Uncertainty-Aware Representation and Label Refinement on Tabular Data: Methods and Engineering Applications,” I addressed the lack of structural priors and the prevalence of unreliable features and subjective labels in tabular data. I developed UA-Tab, an uncertainty-aware self-supervised learning framework that jointly models feature relevance and reliability through an attention–uncertainty mechanism with latent-space perturbation. In parallel, I proposed GF-KDA, a noise-resilient label refinement framework that performs confidence-based propagation in uncertainty-aware kernel space without explicit graph construction. Together, these methods establish a unified paradigm for robust representation learning and label refinement under feature corruption, noisy supervision, and domain shift.

At KICT, I apply these methodologies to intelligent geotechnical and infrastructure systems, including wall deformation prediction under domain shift, nationwide slope risk assessment, pile bearing capacity estimation, monitoring-data domain adaptation, and AI-integrated structural health evaluation. In these contexts, uncertainty arises from measurement noise, environmental variability, and expert judgment. Rather than suppressing it, I embed uncertainty directly into representation learning, supervision refinement, and knowledge distillation frameworks.
