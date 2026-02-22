---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Senior Researcher, KICT · Domain-Embedded AI Architect.</a>.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Email: seunghwanseo@kict.re.kr</p>


selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---
{% include social.liquid %}

Uncertainty and unreliable data remain major obstacles to deploying AI in safety-critical engineering systems. My research develops uncertainty-aware and interpretable AI frameworks that enable reliable decision-making under imperfect information.

I am a Senior Researcher at the <a href="https://www.kict.re.kr/" target="_blank" rel="noopener noreferrer">Korea Institute of Civil Engineering and Building Technology (KICT)</a>, working at the intersection of stochastic mechanics, machine learning, and intelligent infrastructure systems. My research centers on a fundamental question: how can we develop reliable and interpretable AI models for engineering systems where data are heterogeneous, noisy, and uncertain? I address this by **integrating probabilistic theory, uncertainty-aware representation learning, and deployable AI architectures for safety-critical applications**.

During my <a href="https://www.jstage.jst.go.jp/article/jscejhe/72/4/72_I_733/_pdf/-char/ja" target="_blank" rel="noopener noreferrer">Master’s research</a>, I studied sand-wave formation in movable beds through stochastic process theory, examining how microscopic random sediment motions generate organized macroscopic riverbed structures. By connecting deterministic governing equations with probabilistic formulations such as the **Kramers–Moyal and Fokker–Planck equations**, I established a research perspective centered on the interplay between stochastic behavior and emergent structural order across scales.

Building on this foundation, my Ph.D. research shifted toward uncertainty modeling in heterogeneous tabular data. I developed **UA-Tab**, an **uncertainty-aware self-supervised framework** that jointly models feature relevance and reliability, and proposed **GF-KDA**, a **noise-resilient label refinement method** operating in uncertainty-aware kernel space without explicit graph construction. Together, these contributions advance a unified paradigm for robust representation learning under feature corruption, noisy supervision, and domain shift.

At KICT, I apply these methodologies to intelligent geotechnical and infrastructure systems, including wall deformation prediction under domain shift, nationwide slope risk assessment, pile bearing capacity estimation, monitoring-data domain adaptation, and AI-integrated structural health evaluation.

### Research Interests
- **Uncertainty-aware representation learning for tabular data** and **robust label refinement** 
  (e.g., *Ua-Tab*; *Graph-Free Kernel Discriminant Analysis for noise-resilient label spreading*)
- **Deformation forecasting and monitoring** for excavation and earth-retaining structures  
  (time-series modeling, domain shift / domain adaptation, deployable prediction pipelines)
- **Data-driven geotechnics and sensing**: pile capacity estimation, seepage modeling, Raman-based carbonation assessment, DIC-based field measurement

A curated list is shown below. For the full list, please visit **/publications/**.
