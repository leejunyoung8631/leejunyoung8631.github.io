---
layout: about
title: About
permalink: /
subtitle: POSTECH

profile:
  align: right
  image: profile.jpg
  image_circular: false
  more_info: >
    <p>Research Associate<br>POSTECH CELL</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a Research Associate at POSTECH CELL. My research spans AI systems and language models. I develop learning-based methods for system optimization and study how to make language models more efficient while preserving the quality of their generation. I am particularly interested in how models use computation and how they learn to reason and generate reliably.

Previously, I received my B.S. from DGIST and my M.S. from the Department of Electrical Engineering and Computer Science at DGIST, advised by Prof. Yeseong Kim.

I am applying to PhD programs for Fall 2027.

You can reach me at [lolcy3205@postech.ac.kr](mailto:lolcy3205@postech.ac.kr) or [ljy32051@gmail.com](mailto:ljy32051@gmail.com), and find my code on [GitHub](https://github.com/leejunyoung8631).

<!-- intro-end -->

## Research Interests

- **Learning-based system optimization.** How can learning algorithms guide resource allocation and reduce the cost of finding effective system configurations?
- **Efficient model architectures and inference.** Which computations are essential for a given task, and how can model architectures and inference systems work together to allocate or reuse computation?
- **Language model learning and behavior.** How do training objectives shape the representations models use for reasoning and generation, and how can post-training help models use what they have learned more reliably?

## Selected Publications

- [**HVKV: Scalable Long-Context Inference through Hypervector KV Cache Retrieval**](https://doi.org/10.1145/3845814.3850042)  
  Hyunsei Lee, Sehyeon Park, Jaewoo Gwak, Shinhyoung Jang, **Junyoung Lee**, Yeseong Kim  
  ASPLOS 2027  
  HVKV uses hypervectors to retrieve the key–value cache entries most relevant to the next token during long-context generation.

- [**FOCUS & RePAIR: Mitigating Text Degeneration via Token-Level Guidance for Pruned Large Language Models**](https://proceedings.mlr.press/v306/lee26bb.html)  
  **Junyoung Lee**, Sehyeon Park, Shinhyoung Jang, Seonha Ryu, Hojeong Kim, Hyunsei Lee, Il Hong Suh, Yeseong Kim  
  ICML 2026, Spotlight  
  We trace why pruned language models get stuck in repetition loops and introduce two training methods that help them generate more varied text.

- [**Diffusion-Based Generative System Surrogates for Scalable Learning-Driven Optimization in Virtual Playgrounds**](https://doi.org/10.1145/3727112)  
  **Junyoung Lee**, Seohyun Kim, Shinhyoung Jang, Jongho Park, Yeseong Kim  
  SIGMETRICS 2025  
  DiffNEST generates realistic system traces with a diffusion model, so we can train policies for processor frequency and cache allocation without running each experiment on hardware.

- [**Late Breaking Results: Dynamically Scalable Pruning for Transformer-Based Large Language Models**](https://ieeexplore.ieee.org/abstract/document/10992978)  
  **Junyoung Lee**, Shinhyoung Jang, Seohyun Kim, Jongho Park, Il Hong Suh, Hoon Sung Chwa, Yeseong Kim  
  DATE 2025  
  Matryoshka lets a single language model run at several depths, so it can switch to a smaller, faster configuration when the compute budget changes.

[View all publications]({{ '/publications/' | relative_url }})

## News

- **Upcoming** · HVKV will appear at ASPLOS 2027.
- **October 2026** · [Forget-to-Focus](https://aclanthology.org/2026.findings-emnlp.952/) appeared in Findings of EMNLP 2026.
- **July 2026** · FOCUS & RePAIR was featured as a Spotlight at ICML 2026.
- **February 2026** · I joined POSTECH CELL as a Research Associate after receiving my M.S. from DGIST EECS.
- **June 2025** · I presented DiffNEST at SIGMETRICS 2025 in Stony Brook.
- **April 2025** · I presented Matryoshka at DATE 2025 in Lyon.
