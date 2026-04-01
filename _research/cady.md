---
layout: research_detail
permalink: /research/cady/
title: "Paper: Learning Causal Structure Distributions for Robust Planning" 

# --- Project Details ---
project_title: "Learning Causal Structure Distributions for Robust Planning"
authors_links:
  - name: "Alejandro Murillo-González"
    url: "https://alejandromllo.github.io/"
  - name: "Junhong Xu"
    url: "https://junhongxu.github.io/"
  - name: "Lantao Liu"
    url: "https://vail-robotics.net/pages/lantaoliu"
venue: "Robotics and Automation Letters (RA-L), 2025"

# --- Links ---
links:

  -  label: "RA-L"
     icon: "📄"
     url: "https://ieeexplore.ieee.org/abstract/document/11123776"

  -  label: "Paper PDF"
     icon: "📄"
     url: "https://arxiv.org/pdf/2508.06742"

main_video:
  embed_url: "https://www.youtube.com/embed/X6k5t7OOnNc"
  title: "UGV Unstructured Terrain Navigation."
  description: "We evaluate the CAusally-informed DYnamics (CADY) model in a set of unstructured terrain navigation tasks."

videos:

    - embed_url: "https://www.youtube.com/embed/v-WnfQF0hyI"

    - embed_url: "https://www.youtube.com/embed/Du3ASfPx6-I"

# --- CITATION ---
# The layout file will format this into a nice-looking section.
bibtex: | 
  @ARTICLE{murillo2025cady,
    author={Murillo-González, Alejandro and Xu, Junhong and Liu, Lantao},
    journal={IEEE Robotics and Automation Letters}, 
    title={Learning Causal Structure Distributions for Robust Planning}, 
    year={2025},
    volume={10},
    number={10},
    pages={9916-9923},
    keywords={Robots;Planning;Mathematical models;Robustness;Periodic structures;Computational modeling;Uncertainty;Vectors;Probabilistic logic;Training;Model learning for control;integrated planning and control;reinforcement learning;planning under uncertainty;unstructured environment},
    doi={10.1109/LRA.2025.3598663}
  }

---

## Abstract

Structural causal models describe how the components of a robotic system interact. They provide both structural and functional information about the relationships that are present in the system. The structural information outlines the variables among which there is interaction. The functional information describes how such interactions work, via equations or learned models. In this letter we find that learning the functional relationships while accounting for the uncertainty about the structural information leads to more robust dynamics models which improves downstream planning, while using significantly lower computational resources. This in contrast with common model-learning methods that ignore the causal structure and fail to leverage the sparsity of interactions in robotic systems. We achieve this by estimating a causal structure distribution that is used to sample causal graphs that inform the latent-space representations in an encoder-multidecoder probabilistic model. We show that our model can be used to learn the dynamics of a robot, which together with a sampling-based planner can be used to perform new tasks in novel environments, provided an objective function for the new requirement is available. We validate our method using manipulators and mobile robots in both simulation and the real-world. Additionally, we validate the learned dynamics' adaptability and increased robustness to corrupted inputs and changes in the environment, which is highly desirable in challenging real-world robotics scenarios.

<!-- ## More Details

Here you can go into more depth about the project. You can add images, diagrams, or further explanations that wouldn't fit on the main resume page.

![Placeholder Diagram](https://placehold.co/600x300/f0f0f0/333?text=Project+Diagram)
*Fig. 1: A diagram explaining our novel approach.* -->
