---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download the PDF version]({{ base_path }}/files/Meng_Wu_CV.pdf)

Education
======

- **University of Michigan**, Ann Arbor, MI  
  Ph.D. in Electrical and Computer Engineering, incoming Fall 2026  
  M.S. in Electrical and Computer Engineering, 2024-2026; GPA: 4.00/4.00  
  Advisor: Prof. Qing Qu
- **University of Electronic Science and Technology of China**, Chengdu, China  
  B.E. in Electronic Information Engineering, 2020-2024  
  GPA: 3.76/4.00; Major GPA: 3.98/4.00; Rank: 2/42

Research Experience
======

- **Graduate Research Assistant**, University of Michigan, Sep 2024-Present
  - Studied generalization degradation and model collapse in diffusion models.
  - Developed entropy-aware data selection methods and curriculum priors.
  - Proposed hierarchical diffusion alignment for UAV Sim2Real adaptation, improving VisDrone mAP by 7.1%.
- **AIGC Research Intern**, Shengshu AI, Apr-Jul 2024
  - Investigated fixed-identity image and video generation with diffusion models and temporal attention alignment.
  - Improved CLIP similarity by 6% and reduced FID by 8.4 on an internal benchmark.
- **Research Intern**, Baidu Research, Nov 2023-Apr 2024
  - Led a Diffusion Transformer video-editing project and fine-tuned U-ViT with multimodal conditioning.
  - Built a 120k-poster dataset and fine-tuned LLaVA with DPO, reducing hallucination by 12%.
- **Teaching Assistant**, UESTC, Aug 2023-Feb 2024
  - Led weekly AI and machine-learning labs and mentored 90 students.

Publications
======

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Selected Projects
======

- **Efficient Text-to-Image Fine-Tuning:** Integrated Textual Inversion, LoRA, and Custom Diffusion into UniDiffuser; reduced fine-tuning to approximately 30 minutes on one A6000.
- **Interactive Image Editing via LLM Guidance:** Built a conversational SDXL editing demo that received 4k+ GitHub stars.

Technical Skills
======

- **Languages:** Python, C/C++, MATLAB
- **Frameworks:** PyTorch, Diffusers, Hugging Face, OpenCV, scikit-learn
- **Tools:** Git, Docker, SLURM, Bash
