---
title: "TRPlaceFPGA-MP: A Two-stage Reinforcement Learning Framework for Fast FPGA Macro Placer"
collection: publications
permalink: /publication/macroplacetrad
date: 2025-09-01
venue: 'The 35th International Conference on Field-Programmable Logic and Applications (FPL).'
---

Recommended citation: Qin Luo, Xinshi Zang, Evangeline F.Y. Young, Martin D.F. Wong. TRPlaceFPGA-MP: A Two-stage Reinforcement Learning Framework for Fast FPGA Macro Placer. The 35th International Conference on Field-Programmable Logic and Applications (FPL), 2025. ([Download paper here]([https://dl.acm.org/doi/abs/10.1145/3649476.3658713](https://github.com/tomqingo/tomqingo.github.io/blob/master/files/SE04-02_FPL_2025_paper.pdf)))

Reinforcement learning (RL)-based macro placement has garnered significant interest in both the fields of artificial intelligence and electronic design automation (EDA), due to its excellent potential for achieving better performance, power
and area optimization compared to analytical methods. However, existing techniques are restricted in the ASIC and ignore the
other hardware architectures like FPGA. Neglecting the intrinsic characters of FPGA structures, conventional RL-based methods for ASICs may result in a large exploration space and low sample efficiency. In this work, we propose TRPlaceFPGA-MP, a two-stage RL-based macro placement framework for Ultrascale FPGAs. Leveraging the columnar architecture, we first train a tiny RL model to determine the candidate columns for each macro in the first stage. With the pruned searching space, a more sophisticated RL model is then trained in the second stage to determine the ultimate positions of the macros. Experimental results on the MLCAD2023 contest benchmark demonstrate that TRPlaceFPGA-MP still maintains superior placement performance compared with Vivado and DreamplaceFPGA-MP. Furthermore, it improves the convergence rate by 2.28x and accelerates the exploration process by 1.61x compared to the one-stage RL approach.
