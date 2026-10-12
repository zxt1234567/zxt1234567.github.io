---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Xintong Zhang
=====

Hi, I’m Xintong Zhang, a senior undergraduate student majoring in Applied Mathematics and Computer Science at Duke Kunshan University.

I am currently conducting research on Vision-Language Navigation, collaborating with Dr. Kunhui Wang, Prof. Junyu Gao, [Prof. Changsheng Xu](https://nlpr-web.ia.ac.cn/mmc/homepage/csxu.html), and their team from the Institute of Automation, Chinese Academy of Sciences.

Previously, I worked on Multi-Agent Collaboration, under the supervision of [Dr. Junfeng Chen](https://junfengchen-robotics.github.io/), [Prof. Meng Guo](https://mengguo.github.io/personal_site/) from Peking University.

My research interests lie at the intersection of **Embodied AI**, **Multimodal Learning**, and **Robotics**. I am particularly interested in developing intelligent agents capable of perceiving complex environments, reasoning about future states, and making reliable decisions. My current research focuses on Vision-Language Navigation and Learning-based Planning, with previous experience in LLM based Multi-Agent Coordination and Collaboration.

Publication
=====

<div style="display: flex; align-items: flex-start; margin-bottom: 40px; gap: 20px;">
  <div style="flex-shrink: 0;">
    <img src="/paper_figure/ForeFly.png" alt="Article Image" style="width: 210px; border-radius: 4px;">
  </div>
  <div style="flex-grow: 1;">
    <strong style="font-size: 1.1em;">ForeFly: A Dual-Horizon World Action Model for Aerial Vision-Language Navigation</strong><br>
    Kunhui Wang*, <strong>Xintong Zhang*</strong>, Junyu Gao, Changsheng Xu<br>
    <em>Submitted to ICLR 2027</em><br>
    <a href="https://arxiv.org/pdf/2609.33581">Paper</a><br>
    <strong>Overview:</strong> We propose ForeFly, a dual-horizon latent world action model for aerial VLN. It predicts both a proximal future for local continuity and an adaptive route-critical future for long-range guidance. We design visual memories to provide history-aware context for future prediction, and we also introduce Foresight-Guided Action Refinement to exploit proximal foresight for local action enhancement and route-critical foresight for route-level guidance. The method is validated on the TravelUAV and UAV-ON benchmarks, showing that ForeFly consistently outperforms strong baselines across seen and unseen settings.
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px; gap: 20px;">
  <div style="flex-shrink: 0;">
    <img src="/paper_figure/MoARFly.png" alt="Article Image" style="width: 210px; border-radius: 4px;">
  </div>
  <div style="flex-grow: 1;">
    <strong style="font-size: 1.1em;">MoARFly: Learning Motion-Aware Action Refinement for Aerial Vision-Language Navigation</strong><br>
    Kunhui Wang, <strong>Xintong Zhang</strong>, Yufan Hu, Yang Yang, and Junyu Gao<br>
    <em>Submitted to TMM</em><br>
    <strong>Overview:</strong> We propose MoARFly, a motion-aware action refinement framework for aerial Vision-Language Navigation (VLN). By introducing a Dual-Query Transformer to capture inter-frame motion dynamics and progressively refine action representations, MoARFly bridges the gap between visual-language understanding and executable actions. Extensive experiments on OpenFly and TravelUAV demonstrate improved navigation accuracy, efficiency, and generalization to unseen environments.
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px; gap: 20px;">
  <div style="flex-shrink: 0;">
    <img src="/paper_figure/SR.png" alt="Article Image" style="width: 210px; border-radius: 4px;">
  </div>
  <div style="flex-grow: 1;">
    <strong style="font-size: 1.1em;">LLMs Meet Formal Methods for Robot Swarms: Reliable, Explainable and Efficient Human-in-the-loop Planning in Unknown Environments</strong><br>
    Junfeng Chen, Yuxiao Zhu, An Zhuo, <strong>Xintong Zhang</strong>, Shuo Zhang, Meng Guo, and Zhongkui Li<br>
    <em>Submitted to npj Robotics</em><br>
    <a href="https://arxiv.org/abs/2605.07877">Paper</a>
    <a href="https://www.youtube.com/watch?v=dwQUosh9Kds">Video</a>
    <a href="https://trio-pku.github.io/DEXTER-LLM-Plus/">Website</a><br>
    <strong>Overview:</strong> We propose a formal method and LLM framework for coordinating large fleets of heterogeneous robots in open and dynamic environments. Our approach integrates model-checking-based task planning with LLM-powered reasoning and interaction, ensuring adaptability, explainability, and optimal mission execution. Validated through simulations and real-world deployments, it proves effective for disaster response, infrastructure inspection, and dynamic surveillance.
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px; gap: 20px;">
  <div style="flex-shrink: 0;">
    <img src="/paper_figure/cocoplan.png" alt="Article Image" style="width: 210px; border-radius: 4px;">
  </div>
  <div style="flex-grow: 1;">
    <strong style="font-size: 1.1em;">CoCoPlan: Adaptive Coordination and Communication for Multi-robot Systems under Continual Temporal Tasks</strong><br>
    <!-- Jan 2025-August 2025<br> -->
    <strong>Xintong Zhang</strong>*, Junfeng Chen*, Yuxiao Zhu, Bing Luo, Meng Guo<br>
    <em>Robotics and Automation Letter (RA-L), 2026</em><br>
    <a href="https://arxiv.org/pdf/2601.10116">Paper</a>
    <a href="https://www.youtube.com/watch?v=45NcWNtqBwI">Video</a>
    <a href="https://zxt1234567.github.io/CoCoPlan-HomePage/">Website</a><br>
    <strong>Overview:</strong> We propose CoCoPlan, a collaborative framework addressing communication-aware task planning for multi-robot systems under intermittent connectivity constraints. The framework focuses on joint optimization of communication events and task allocation, ensuring robustness in unknown environments.
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px; gap: 20px;">
  <div style="flex-shrink: 0;">
    <img src="/paper_figure/iros.png" alt="Article Image" style="width: 210px; border-radius: 4px;">
  </div>
  <div style="flex-grow: 1;">
    <strong style="font-size: 1.1em;">DEXTER-LLM: Dynamic and Explainable Coordination of Multi-Robot Systems in Unknown Environments via Large Language Models</strong><br>
    <!-- Dec 2024-March 2025<br> -->
    Yuxiao Zhu*, Junfeng Chen*, <strong>Xintong Zhang</strong>, Meng Guo, Zhongkui Li<br>
    <em>IROS 2025</em><br>
    <a href="https://arxiv.org/pdf/2508.14387">Paper</a>
    <a href="https://www.youtube.com/watch?v=w2A-NG5LeAY">Video</a>
    <a href="https://tcxm.github.io/DEXTER-LLM/">Website</a><br>
    <strong>Overview:</strong> We propose DEXTER-LLM, a novel framework for dynamic task planning in unknown environments. Our approach integrates LLM-based multi-stage reasoning, optimization-based task assignment, and adaptive human-in-the-loop verification to tackle the challenges of online adaptability and explainability.
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px; gap: 20px;">
  <div style="flex-shrink: 0;">
    <img src="/paper_figure/slei3d.png" alt="Article Image" style="width: 210px; border-radius: 4px;">
  </div>
  <div style="flex-grow: 1;">
    <strong style="font-size: 1.1em;">SLEI3D: Simultaneous Large-scale 3D Exploration Inspection and Interaction via Heterogeneous Fleets under Limited Communication</strong><br>
    <!-- June-Dec 2024<br> -->
    Junfeng Chen, Yuxiao Zhu, <strong>Xintong Zhang</strong>, Bing Luo, Meng Guo<br>
    <em>Transactions on Automation Science and Engineering (TASE), 2025</em><br>
    <a href="https://arxiv.org/pdf/2601.00163">Paper</a>
    <a href="https://junfengchen-robotics.github.io/SLEI3D/">Website</a><br>
    <strong>Overview:</strong> We propose SLEI3D, a planning and coordination framework for heterogeneous multi-robot systems to perform simultaneous 3D exploration, inspection, and real-time reporting in unknown environments. Our approach integrates adaptive inspection and intermittent communication protocols with a multi-layer, multi-rate planning mechanism for robust coordination.
  </div>
</div>

Experiences
======
<div style="display: flex; align-items: flex-start; margin-bottom: 40px; gap: 40px;">
  <div style="flex-shrink: 0;">
    <img src="/paper_figure/CASIA_Logo.jpg" alt="Article Image" style="width: 110px; border-radius: 4px;">
  </div>
  <div style="flex-grow: 1;">
    <strong style="font-size: 1.1em;">Institute of Automation, Chinese Academy of Sciences</strong><br>
    Research Internship, 2024.04-Present<br>
    Supervisor: Dr. Kunhui Wang, Prof. Junyu Gao, 
    <a href="https://nlpr-web.ia.ac.cn/mmc/homepage/csxu.html">Prof. Changsheng Xu</a><br>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px; gap: 40px;">
  <div style="flex-shrink: 0;">
    <img src="/paper_figure/Duke_Logo.png" alt="Article Image" style="width: 110px; border-radius: 4px;">
  </div>
  <div style="flex-grow: 1;">
    <strong style="font-size: 1.1em;">Duke University</strong><br>
    Exchange, 2025.08-2025.12<br>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px; gap: 40px;">
  <div style="flex-shrink: 0;">
    <img src="/paper_figure/PKU_Logo.png" alt="Article Image" style="width: 110px; border-radius: 4px;">
  </div>
  <div style="flex-grow: 1;">
    <strong style="font-size: 1.1em;">Peking University, School of Advanced Manufacturing and Robotics</strong><br>
    Research Internship, 2024.05-2026.02<br>
    Supervisor: <a href="https://junfengchen-robotics.github.io/">Dr. Junfeng Chen</a>,
    <a href="https://mengguo.github.io/personal_site/">Prof. Meng Guo</a><br>
  </div>
</div>

Honors and Awards
======
**[2024.04]** National-Level College Student Innovation and Entrepreneurship Project - Organizing Committee of the Jiangsu Provincial College Student Innovation and Entrepreneurship Outstanding Achievement Exchange and Exhibition<br>
**[2025.04]** Student Experiential Learning Fellow (SELF) – Duke Kunshan University<br>
**[2025.04]** Signature Fund (SF) – Duke Kunshan University<br>
**[2025.12]** National Encouragement Scholarship - Jiangsu Provincial Department of Education<br>
**[2023-2026]** Dean's List – Duke Kunshan University

Services
======
**Reviewer**: RAL<br>
**Conference Participation**: IROS 2025, ICRA 2026<br>
**Teaching Assistant**: DKU COMPSCI101: Introduction into Computer Science (2024 Fall)

CV
======
See [here](https://zxt1234567.github.io/CV/CV-Xintong_Zhang_6.pdf)