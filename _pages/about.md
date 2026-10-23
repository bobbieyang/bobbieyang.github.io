---
permalink: /
title: "Xiaokun Yang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Dr. Xiaokun Yang is a Professor in the College of Science and Engineering at the University of Houston–Clear Lake and an Affiliate Faculty member in the Computer Architecture Group within the Computer Science Department at Lawrence Berkeley National Laboratory. He is a recipient of the 2025 President’s Distinguished Faculty Award, the 2025 Distinguished Professor Award, and the 2025 Semi-Finalist of the Minnie Piper Award. His research is currently supported by multiple federal grants (in total $700K), including awards from the U.S. Department of Energy (ASCR) and the National Science Foundation (CSSI, REU, and others). 

Before entering academia, Dr. Yang spent nearly a decade in industry as an ASIC Design and Verification Engineer at Advanced Micro Devices (AMD) and China Electronics Corporation (CEC). He earned his Ph.D. in Electrical and Computer Engineering from Florida International University (FIU) in 2016. Dr. Yang’s research focuses on (1) specialized chip design for high-performance computing (HPC) and AI; (2) quantum circuit verification and acceleration; and (3) AI-driven chip design flows, including field-programmable gate arrays (FPGAs), application-specific integrated circuits (ASICs), and systems-on-chip (SoCs). As first and/or corresponding author, he has published more than 50 scholarly works, including one textbook, three patents, over 15 peer-reviewed journal articles, and more than 40 papers in prestigious international conferences.

More details please see my <a href="{{ base_path }}/files/XYang_CV.pdf" target="_blank">📄 CV.

Should you have any questions, please feel free to contact
[yangxia@uhcl.edu](mailto:yangxia@uhcl.edu?subject=Research%20Inquiry) and/or
[xiaokunyang@lbl.gov](mailto:xiaokunyang@lbl.gov?subject=Research%20Inquiry)

Research Abstract
======
As traditional transistor scaling reaches its fundamental physical and economic limits, the semiconductor industry has entered the post-Moore’s Law era, where future computing performance relies entirely on specialized, workload-tailored hardware architectures. 
My research team explores how modular hardware generation can bridge the widening gap between surging computational demands and plateauing silicon efficiency. We present a unified, parameterized hardware generation framework designed to systematically optimize power, performance, and area (PPA) across both FPGAs and ASICs. By raising the level of hardware abstraction, our approach delivers reusable computational building blocks—spanning custom arithmetic units, dense linear algebra kernels (GEMM, TSQR), spectral transforms (FFT), and stencil solvers—supporting flexible numerical precisions and spatial-temporal parallelism. Building upon these foundations, we highlight two high-impact domains: 
1) Scientific Computing and AI: Accelerating demanding workloads such as density functional theory (DFT) and neural networks.
2) Quantum Circuit Simulation: Developing customized state representations and adaptive mixed-precision generators integrated with circuit-cutting techniques to overcome classical memory bottlenecks and scale quantum simulations.
Physical implementations in TSMC 7 nm demonstrate operating frequencies exceeding 1 GHz and a 50x improvement in energy and area efficiency over the NVIDIA H100 GPU on targeted workloads. This presentation will discuss the design principles behind this hardware specialization and their implications for the future of heterogeneous computing.

<img src="{{ base_path }}/images/research.png"
     style="display: block; width: 100%; height: auto; margin: 0 0 1em 0;"
     alt="Research area">


Student Recruiting
======
Presently, the Chip Design Lab is actively seeking talented and self-motivated students who possess a keen interest in hardware design for scientific computing, AI, and quantum computing. These selected students will receive robust support through federal grants, including the esteemed DOE ASCR, NSF CSSI, and NSF REU programs. 

The student qualifications are: 1) knowledgeable in ASIC/FPGA design and simulation; and 2) knowledgeable in Chisel/Scala programming. 

If you have taken either of my courses, **IC Design Flow** or **Advanced Digital Systems Design**, you are encouraged to apply directly. Otherwise, please complete the self-training materials before submitting your application.
- [Training tutorials](https://bobbieyang.github.io/lab/) for chip design flow
- [Recent projects](https://bobbieyang.github.io/portfolio/) for classical-quantum chip design

To apply, please send me your **CV and academic transcript**.


