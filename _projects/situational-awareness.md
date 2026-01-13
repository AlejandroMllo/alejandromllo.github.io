---
layout: project_detail
permalink: /projects/situational-awareness/
title: "Paper: Situationally-Aware Dynamics Learning" 

# --- Project Details ---
project_title: "Situationally-Aware Dynamics Learning"
# authors: "Alejandro Murillo-González & Lantao Liu"
authors_links:
  - name: "Alejandro Murillo-González"
    url: "https://alejandromllo.github.io/"
  - name: "Lantao Liu"
    url: "https://vail-robotics.net/pages/lantaoliu"
venue: "International Journal of Robotics Research (IJRR), 2026"

# --- Links ---
links:

  -  label: "Paper PDF"
     icon: "📄"
     url: "https://arxiv.org/pdf/2505.19574"

  -  label: "Code (TBD)"
     icon: "💻"
     url: "https://github.com/AlejandroMllo/" # TODO: Add GitHub Repo 1 URL

main_video:
  embed_url: "https://www.youtube.com/embed/7a-NzAackE4"
  title: "UGV Navigation in Diverse Environments."
  description: "We evaluate the learned situationally-aware dynamics model in a set of unstructured terrain navigation tasks."

videos:

    - embed_url: "https://www.youtube.com/embed/Eo68c5APuAo"
      title: "Situation Change Responsiveness"
      description: "This video shows how the situation symbol representing the latent factors experienced by the robot change as it traverses multiple scenarios."

    - embed_url: "https://www.youtube.com/embed/a9oVk-Qor9c" 
      title: "Quadrotor Flying under Changing Wind Conditions."
      description: "We investigate the performance of a situationally-aware dynamics model for a quadrotor tasked with crossing a series of gates suppend in the air while being disturbed by sudden changes in wind patterns."

    - embed_url: "https://www.youtube.com/embed/xGSFT9QvtJ0" # Example for a Vimeo video
      title: "Latent Factor Effect Characterization."
      description: "Data collection to present a real world example of the motivation for a latent factor representation learning method."

# --- CITATION ---
# The layout file will format this into a nice-looking section.
bibtex: | 
  @misc{murillogonzalez2025-sa,
        title={Situationally-Aware Dynamics Learning}, 
        author={Alejandro Murillo-González and Lantao Liu},
        year={2025},
        eprint={2505.19574},
        archivePrefix={arXiv},
        primaryClass={cs.RO},
        url={https://arxiv.org/abs/2505.19574}, 
  }
---

## Abstract

Autonomous robots operating in complex, unstructured environments face significant challenges due to latent, unobserved factors that obscure their understanding of both their internal state and the external world. Addressing this challenge would enable robots to develop a more profound grasp of their operational context. To tackle this, we propose a novel framework for online learning of hidden state representations, with which the robots can adapt in real-time to uncertain and dynamic conditions that would otherwise be ambiguous and result in suboptimal or erroneous behaviors. Our approach is formalized as a Generalized Hidden Parameter Markov Decision Process, which explicitly models the influence of unobserved parameters on both transition dynamics and reward structures. Our core innovation lies in learning online the joint distribution of state transitions, which serves as an expressive representation of latent ego- and environmental-factors. This probabilistic approach supports the identification and adaptation to different operational situations, improving robustness and safety. Through a multivariate extension of Bayesian Online Changepoint Detection, our method segments changes in the underlying data generating process governing the robot's dynamics. The robot's transition model is then informed with a symbolic representation of the current situation derived from the joint distribution of latest state transitions, enabling adaptive and context-aware decision-making. To demonstrate effectiveness, we validate our approach on an unmanned ground vehicle operating in diverse unstructured terrains, both in simulation and in real-world experiments. We also evaluate a quadrotor in simulation under randomly changing wind conditions. Both setups introduce unmodeled and unmeasured environmental factors that substantially affect robot motion. Extensive experiments in both simulation and real world reveal significant improvements in data efficiency, policy performance, and the emergence of safer, adaptive navigation strategies.

<!-- ## More Details

Here you can go into more depth about the project. You can add images, diagrams, or further explanations that wouldn't fit on the main resume page.

![Placeholder Diagram](https://placehold.co/600x300/f0f0f0/333?text=Project+Diagram)
*Fig. 1: A diagram explaining our novel approach.* -->
