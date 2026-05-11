---
layout: research_detail
permalink: /research/pasta/
title: "RSS 2026: PASTA 🍝" 

# --- Project Details ---
# project_title: "🍝 PASTA: Policy-optimization via Adaptive Smooth Tchebycheff Attention"
project_title: "Adaptive Smooth Tchebycheff Attention for Multi-Objective Policy Optimization"
authors_links:
  - name: "Alejandro Murillo-González"
    url: "https://alejandromllo.github.io/"
  - name: "Mahmoud Ali"
    url: "https://sites.google.com/view/ali-mahmoudali/home"
  - name: "Lantao Liu"
    url: "https://vail-robotics.net/pages/lantaoliu"
keywords:
  - "Robot Learning"
  - "Reinforcement Learning (RL)"
  - "Multi-Objective RL (MORL)"
  - "Multi-Objective Optimization (MOO)"
  - "Visual Search"
  - "Unmanned Ground Vehicle (UGV)"
  - "Quadrotor"
venue: "Robotics: Science and Systems (RSS), 2026"

# --- Links ---
links:

  # -  label: "RSS"
  #    icon: "📄"
  #    url: # "https://doi.org/10.1177/02783649261431863"

  -  label: "PDF (TBA)"
     icon: "📄"
     url: # "https://arxiv.org/pdf/2505.19574"

  -  label: "Code (TBA)"
     icon: "💻"
     url: # "https://github.com/AlejandroMllo/situationally_aware_dynamics_learning"

main_video:
  embed_url: "https://www.youtube.com/embed/xLynYv05Bdc"
  title: "Stealth Visual Search."
  description: "Robot exploration task where its presence must be non-disruptive. For example, monitoring fragile ecosystems without disturbing wildlife."

videos:

    - embed_url: "https://www.youtube.com/embed/twh3YZ6eczo"
      title: "Drone Flying among Random Agents"
      description: "A drone must traverse a shared workspace while avoiding two other drones executing independent tasks within assigned lanes."

# --- CITATION ---
# The layout file will format this into a nice-looking section.
bibtex: |
  @INPROCEEDINGS{murillo2026pasta, 
      AUTHOR    = {Alejandro Murillo-González AND Mahmoud Ali AND Lantao Liu}, 
      TITLE     = {{Adaptive Smooth Tchebycheff Attention for Multi-Objective Policy Optimization}}, 
      BOOKTITLE = {Proceedings of Robotics: Science and Systems}, 
      YEAR      = {2026}, 
      ADDRESS   = {Sydney, Australia}, 
      MONTH     = {July}
  } 
---

## Abstract

Multi-objective reinforcement learning in robotic domains requires balancing complex, non-convex trade-offs between conflicting objectives. While linear scalarization methods provide stability, they are theoretically incapable of recovering solutions within non-convex regions of the Pareto front. Conversely, static non-linear scalarizations (e.g., Tchebycheff) can theoretically access these regions but often suffer from severe gradient variance and optimization instability in deep RL. In this work, we propose an Adaptive Smooth Tchebycheff framework that resolves this tension by dynamically modulating the curvature of the optimization landscape. We introduce a novel conflict-driven controller that regulates the optimization smoothness based on real-time gradient interference. This allows the agent to anneal toward precise, non-convex scalarization when objectives align, while elastically reverting to stable, smooth approximations when destructive gradient conflicts emerge. We validate our approach on a challenging robotic stealth visual search task---a proxy for monitoring of protected/fragile ecosystems---where an agent must balance search, exposure/interference minimization and exploration speed. Extensive ablations confirm that our conflict-aware adaptation enables the robust discovery of Pareto-optimal policies in non-convex regions inaccessible to linear baselines and unstable for static non-linear methods.

<!-- ## More Details

Here you can go into more depth about the project. You can add images, diagrams, or further explanations that wouldn't fit on the main resume page.

![Placeholder Diagram](https://placehold.co/600x300/f0f0f0/333?text=Project+Diagram)
*Fig. 1: A diagram explaining our novel approach.* -->
