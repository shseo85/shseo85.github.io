---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Korea Institute of Civil Engineering and Building Technology (KICT)</p>
    <p>Department of Geotechnical Engineering Research </p>
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

I am a Senior Researcher at the Korea Institute of Civil Engineering and Building Technology (KICT), working at the intersection of stochastic mechanics, machine learning, and intelligent infrastructure systems. My research is driven by a central question: how can we build reliable and interpretable AI models for engineering systems where data are inherently heterogeneous, noisy, and uncertain? I approach this challenge by integrating probabilistic theory, uncertainty-aware representation learning, and deployable AI architectures for safety-critical infrastructure applications.

My academic foundation began with stochastic process theory. In my Master’s thesis, “A Study on Formation of Sand Waves in Movable Bed Based on Stochastic Processes”, I investigated how random sediment particle motions at the microscopic scale give rise to organized sand-wave patterns at the macroscopic riverbed scale. By connecting deterministic governing equations with probabilistic formulations such as the Kramers–Moyal and Fokker–Planck equations, I explored how randomness and structural order coexist across scales. This work established my long-term research philosophy: engineering phenomena must be understood through the interplay of stochastic behavior and emergent structure.

Building on this foundation, my doctoral research transitioned from physical stochastic systems to data-driven uncertainty modeling in heterogeneous tabular domains. My Ph.D. dissertation, “Uncertainty-Aware Representation and Label Refinement on Tabular Data: Methods and Engineering Applications,” addresses the fundamental challenge that tabular data—prevalent in infrastructure management, healthcare, and finance—lack structural priors and often contain unreliable features and subjective labels. I developed UA-Tab, an Uncertainty-Aware Self-Supervised Learning framework that jointly models feature relevance and feature reliability through an attention–uncertainty mechanism, generating semantically consistent representations via latent-space perturbation. Complementing this, I proposed GF-KDA (Graph-Free Kernel Discriminant Analysis), a noise-resilient label refinement framework that performs confidence-based propagation directly in uncertainty-aware kernel space, eliminating the instability of explicit graph construction. Together, these methods establish a unified paradigm for uncertainty-aware representation learning and label refinement in tabular data, demonstrating robust performance under feature corruption, noisy supervision, and domain shift.

At KICT, I extend these methodological contributions to intelligent geotechnical and infrastructure systems. My current research includes excavation-induced wall deformation prediction under domain shift, nationwide slope risk assessment using large-scale management databases, pile bearing capacity estimation through data-driven modeling, domain adaptation for monitoring data, and AI-integrated structural health evaluation. In these real-world settings, uncertainty arises not only from measurement noise but also from environmental variability and human expert judgment. Rather than suppressing uncertainty, I treat it as a first-class modeling principle, embedding it directly into representation learning, supervision refinement, and knowledge distillation pipelines.

My research aims to bridge stochastic mechanics and modern machine learning, advancing uncertainty-aware AI methodologies that are interpretable, stable, and deployable for safety-critical infrastructure systems operating under imperfect information.
