---
title: Research
layout: research
excerpt: "Category index"
aside: false
---


### Fracture of Ice Floes in the Arctic
The rapid shrinking of the Arctic ice cap these last decades is seen as one of the most striking
manifestations of global warming. Our main goal in this study is to investigate what happens when two or more ice floes collide, both in 1D and in 2D. We start by modelling an ice floe as a mass-spring-damper lattice, then we derive convergence guarantees with respect to its dynamics (percussion, fracture, etc.). This work has several applications, from accurate climate modelling to the design of more resistant hull in boats that navigate the Arctic. 

{% include figure.html image="../assets/research-ice-floes.png" %}

<!-- Read more on [Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=80GLOSUAAAAJ&citation_for_view=80GLOSUAAAAJ:u-x6o8ySG0sC){:target="_blank"}, or get the [PDF](https://master-csmi.github.io/csmi-stages-2021/csmi-stages/m2/_attachments/NzoyemNgueguin-RousselDesmond.pdf){:target="_blank"}. -->

{% include nav-research-social.html scholar="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=80GLOSUAAAAJ&citation_for_view=80GLOSUAAAAJ:u-x6o8ySG0sC" github="https://github.com/desmond-rn/ice-floes" pdf="https://master-csmi.github.io/csmi-stages-2021/csmi-stages/m2/_attachments/NzoyemNgueguin-RousselDesmond.pdf"  twitter="https://twitter.com/rdesnzoyem" %}

### Simulation of soft tissues with Phi-FEM
In recent years, numerical models using the Finite Elements Method (FEM) to simulate the soft tissue mechanisms of the human body have attracted a great interest. In the context of computer-assisted surgery, the simulation method should be quick, precise, and patient-specific. This work develops a new method named $\Phi$-FEM that uses a Level Set function that cancels itself at the edges of the domain. We apply it to the Poisson and the linear elasticity equation.

{% include figure.html image="../assets/research-phi-fem.png" %}

<!-- Get the [PDF](https://github.com/desmond-rn/phifem/blob/main/report/main.pdf){:target="_blank"}. -->

{% include nav-research-social.html github="https://github.com/desmond-rn/phifem" pdf="https://github.com/desmond-rn/phifem/blob/main/report/main.pdf" %}


[Hey there, check out our welcome page :)]({% post_url 2022-01-24-welcome %})

### Cancer Screening Using Deep Neural Networks

With recent development in deep learning techniques, we implemented a VNet architecture are to solve a computerized tomography inverse problem: given the signal on the boundaries of an organ, we want to rebuild the density map of the organ, hence detecting abnormally high density zones which are potential indicators of early-onset cancer. Our main tasks were:
- Simulating the radiative transfer equation;
- Using neural networks CNN to solve the related inverse problem;
- Using a Vnet to improve accuracy and rebuild the complete density map.

{% include video.html id="64_a3EVG0xQ" title="Radiative Transfer 2D Simulation" %}

Read more on [Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=80GLOSUAAAAJ&citation_for_view=80GLOSUAAAAJ:u5HHmVD_uO8C){:target="_blank"}.

{% include nav-research-social.html scholar="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=80GLOSUAAAAJ&citation_for_view=80GLOSUAAAAJ:u5HHmVD_uO8C" github="https://github.com/desmond-rn/inverse-problem-vnet" pdf="https://irma.math.unistra.fr/~franck/cours/supervision/rapport/RapportDeStage_RousselDesmondNzoyem.pdf" %}
