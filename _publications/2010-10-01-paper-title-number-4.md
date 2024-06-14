---
title: "Dynamic Multi-FPGA Prototyping Platforms with Simultaneous Networking, Placement and Routing."
collection: publications
permalink: /publication/dynamicnet
date: 2024-06-12
venue: 'Great Lakes Symposium on VLSI 2024 (GLSVLSI ’24).'
---

Recommended citation: Xinshi Zang, Qin Luo, Zhongwei Shao, Jifeng Zhang, Evangeline F.Y. Young, and Martin D.F. Wong. Dynamic Multi-FPGA Prototyping Platforms with Simultaneous Networking, Placement and Routing. Great Lakes Symposium on VLSI 2024 (GLSVLSI ’24), June 12–14, 2024, Clearwater, FL, USA. ([Download paper here](https://dl.acm.org/doi/abs/10.1145/3649476.3658713))

Large-scale multi-FPGA prototyping platforms play an indispensable role in the functional verification of complex IC designs. The process of compiling circuit designs typically entails tasks such as partitioning, global placement and routing using a fixed multi-FPGA network. However, different circuit designs often exhibit varying inter-FPGA communication requirements after compilation. Neglecting this distinction, the use of fixed multi-FPGA networks may impede the performance enhancement of circuit verification. In this study, we investigate dynamic networking for multi-FPGA platforms and propose a comprehensive framework, which integrates
simultaneous networking and system-level placement and routing. Based on theoretical analysis, we formulate this dynamic networking problem as an Integer Linear Programming (ILP) problem. Additionally, we introduce two innovative techniques, namely two-level ILP optimization and edge grouping, to expedite the ILP-solving process. Compared to the baselines on Titan23 and ICEEC22 benchmarks, our method achieves remarkable 11% and 47% improvements in system frequency respectively.


