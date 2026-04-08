---
layout: research_detail
permalink: /research/afm/
title: "Paper: Action Flow Matching for Continual Robot Learning" 

# --- Project Details ---
project_title: "Action Flow Matching for Continual Robot Learning"
authors_links:
  - name: "Alejandro Murillo-González"
    url: "https://alejandromllo.github.io/"
  - name: "Lantao Liu"
    url: "https://vail-robotics.net/pages/lantaoliu"
keywords:
  - "Dynamics Refinement"
  - "Online Learning"
  - "Generative Model"
  - "Model-Based RL (MBRL)"
  - "Lifelong Learning"
venue: "Robotics: Science and Systems (RSS), 2025"

# --- Links ---
links:

  -  label: "RSS"
     icon: "📄"
     url: "https://www.roboticsproceedings.org/rss21/p026.html"

  -  label: "PDF"
     icon: "📄"
     url: "https://arxiv.org/pdf/2504.18471"

  -  label: "Code"
     icon: "💻"
     url: "https://github.com/AlejandroMllo/action_flow_matching"

# main_video:
#   embed_url: "https://www.youtube.com/embed/QqK0IKINJEQ?start=14140"
#   title: "Oral Presentation at RSS 2025."
#   description: "Online and Non-Episodic Robot Dynamics Model Refinement."

# --- CITATION ---
# The layout file will format this into a nice-looking section.
bibtex: |
  @INPROCEEDINGS{murillo2025afm, 
      AUTHOR    = {Alejandro Murillo-González AND Lantao Liu}, 
      TITLE     = {{Action Flow Matching for Continual Robot Learning}}, 
      BOOKTITLE = {Proceedings of Robotics: Science and Systems}, 
      YEAR      = {2025}, 
      ADDRESS   = {LosAngeles, CA, USA}, 
      MONTH     = {June}, 
      DOI       = {10.15607/RSS.2025.XXI.026} 
  } 
---

## Abstract

Continual learning in robotics seeks systems that can constantly adapt to changing environments and tasks, mirroring human adaptability. A key challenge is refining dynamics models, essential for planning and control, while addressing issues such as safe adaptation, catastrophic forgetting, outlier management, data efficiency, and balancing exploration with exploitation —all within task and onboard resource constraints. Towards this goal, we introduce a generative framework leveraging flow matching for online robot dynamics model alignment. Rather than executing actions based on a misaligned model, our approach refines planned actions to better match with those the robot would take if its model was well aligned. We find that by transforming the actions themselves rather than exploring with a misaligned model —as is traditionally done— the robot collects informative data more efficiently, thereby accelerating learning. Moreover, we validate that the method can handle an evolving and possibly imperfect model while reducing, if desired, the dependency on replay buffers or legacy model snapshots. We validate our approach using two platforms: an unmanned ground vehicle and a quadrotor. The results highlight the method’s adaptability and efficiency, with a record 34.2% higher task success rate, demonstrating its potential towards enabling continual robot learning.

<!-- ## More Details

Here you can go into more depth about the project. You can add images, diagrams, or further explanations that wouldn't fit on the main resume page.

![Placeholder Diagram](https://placehold.co/600x300/f0f0f0/333?text=Project+Diagram)
*Fig. 1: A diagram explaining our novel approach.* -->
