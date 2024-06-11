---
layout: homepage
---

## About Me

Dr. Harisankar (Hari) Sadasivan is a Staff Engineer in the AMD AI Group and a faculty member (part-time) at the University of Washington, Seattle. At AMD, Hari co-leads several research projects on optimizing irregular AI and genomics kernels on modern multi-chiplet GPUs. At UW, Hari designed and teaches a parallel programming course on GPUs. Hari received his PhD and Masters in CSE from the University of Michigan Ann Arbor where he was advised by [Prof. Satish Narayanasamy](https://eecs.engin.umich.edu/people/narayanasamy-satish/). [Hari's PhD research](https://deepblue.lib.umich.edu/handle/2027.42/178086) focussed on HW-SW co-design for accelerated and portable long-read DNA sequencing. Hari's PhD research has won the 2022 MICRO Top Picks with Honorable Mention (with multiple artifact badges). Hari is a Technical reviewer with several IEEE/ACM venues including CAL, TACO, CGO, MICRO, IPDPS-RAW, IISWC and an editorial board member on several AI and genomics journals. Hari has previously worked with NVIDIA and Samsung R&D.

## Research Interests

I envision a world where AI is advanced and performant enough to diagnose and find cures for all human diseases via techniques such as Precision Medicine. I realize that's a big jump. So, I have broken down my interests for now. 
- **High Performance Artificial Intelligence (AI):** Tall & Skinny GEMMs, Stream-K, Performance issues on multi-chiplet GPUs, LLM inference optimizations
- **High Performance -omics:** Long-read DNA alignment, Raw signal alignment, AI-based Basecalling, Metagenomics

Please shoot me an email if you are a potential collaborator/PI.

## Teaching

AI's demand for FLOPs has far outpaced what Moore's Law could offer. This gap can only be bridged with aggressive software innovation. In order to do this, it is necessary to understand the AI software stack and how it maps to the GPU hardware. I designed and teach a course on [AMD GPU Programming](https://sites.google.com/uw.edu/hipgpuprogramming) at the University of Washington Seattle. I am thankful to all content contributors (acknowledged on my slides). Students impressed me by porting several CUDA kernels to AMD's portable ROCm HIP framework. We ported Dynamic Time Warping, Tall and Skinny GEMMs, ML-based Minimap2 seedingand explored Stream-K optimizations.

## PhD co-advisees

I enjoy guiding motivated students:<br/>
-[M. Emin Ozturk](https://www.linkedin.com/in/m-emin-ozturk-11263944/), University of Utah<br/>
-[Juechu Dong](https://joydddd.github.io/) and [Xueshen Liu](https://www.linkedin.com/in/xueshen-liu-a75718205/), U Michigan Ann Arbor<br/>

## News

- **[May. 2024]** Our paper on GPU accelerated Minimap2 chaining is accepted at Biosys, ASPLOS 2024. Here's an [AMD blog post](https://rocm.blogs.amd.com/ecosystems-and-partners/university-of-michigan/README.html) detailing our collaboration.
- **[April. 2024]** Joined as a part-time course instructor in ECE, UW Seattle to teach GPU Programming. [Here's](https://www.linkedin.com/posts/uwece_applied-parallel-programming-on-gpusis-a-activity-7199847814019911680-kIcG?utm_source=share&utm_medium=member_desktop) what my students like about the most popular course at UW-ECE in 'SP24.
- **[Jan. 2024]** Our paper on GPU accelerated Dynamic Time Warping is published in the Journal of Biotechnology and Biomedicine.
- **[Dec. 2023]** Joined as a part-time course instructor at Paul G Allen School of CSE, UW Seattle to teach GPU Programming.

{% include_relative _includes/publications.md %}
