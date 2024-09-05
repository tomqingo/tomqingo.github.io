---
title: "A Routability-Driven Ultrascale FPGA Macro Placer with Complex Design Constraints."
collection: publications
permalink: /publication/macroplacetrad
date: 2024-05-04
venue: '2024 IEEE 32nd Annual International Symposium on Field-Programmable Custom Computing Machines (FCCM).'
---

Recommended citation: Qin Luo, Xinshi Zang, Qijing Wang, Fangzhou Wang, Evangeline F.Y. Young, Martin D.F. Wong. A Routability-Driven Ultrascale FPGA Macro Placer with Complex Design Constraints. 2024 IEEE 32nd Annual International Symposium on Field-Programmable Custom Computing Machines (FCCM). ([Download paper here](https://ieeexplore.ieee.org/document/10653672))

Macro placement significantly influences the performance of the FPGA placement. However, constraints in modern designs like relative placement constraint (RPC) and regional constraint (RC) are often overlooked in existing routability-driven FPGA placers during macro placement. These constraints introduce challenges in optimizing routability during global placement and macro legalization stages. In this paper, we propose a novel macro placer that specifically addresses these constraints while optimizing routability. Our macro placer integrates macro size-aware pseudo nets, RC guided spreading, and multi-stage look-ahead legalization techniques to enhance routability with specified design constraints. Experimental results show that compared with DreamplaceFPGA-MP and the macro placer in Vivado, our proposed approach achieves 6% and 8% total routing score reduction on the MLCAD2023 contest benchmark. Moreover, the place and route time is reduced by 3.5% on average and up to 43% after our macro placer is integrated into Vivado. These compelling results demonstrate the efficiency gains and superior routability optimization achieved through our approach.
