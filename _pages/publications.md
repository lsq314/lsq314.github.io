---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

* **[TCAD'23]** Shiqing Li, Di Liu, and Weichen Liu, “Efficient FPGA-based Sparse Matrix-Vector Multiplication with Data Reuse-aware Compression”  in IEEE Transactions on Computer-Aided Design of Integrated
Circuits and Systems (TCAD) 2023.
* **[TCAD'23]** Shiqing Li, Shuo Huai, and Weichen Liu, “An Efficient Gustavson-based Sparse Matrix-matrix Multiplication Accelerator on Embedded FPGAs”  in IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD) 2023.
* **[TCAD’22]** “A comprehensive memory management framework for CPU-FPGA heterogenous SoCs”, Zelin Du, Qianling Zhang, Mao Lin, Shiqing Li, Xin Li, and Lei Ju. IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (2022).
* **[D&T'22]** Hao Kong, Shuo Huai, Di Liu, Lei Zhang, Hui Chen, Shien Zhu, Shiqing Li, Weichen Liu, Manu Rastogi, Ravi Subramaniam, Madhu Athreya, M. Anthony Lewis, ”EDLAB: A Benchmark for Edge Deep Learning Accelerators” in IEEE Design & Test 2022.
* **[TCAD'21]** Peng Chen, Weichen Liu, Hui Chen, Shiqing Li, Mengquan Li, Lei Yang, Nan Guan, ”Reduced Worst-Case Communication Latency Using Single-Cycle Multihop Traversal Network- on-Chip” in IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD) 2021.
* **[TECS'21]** Hui Chen, Zihao Zhang, Peng Chen, Xiangzhong Luo, Shiqing Li, Weichen Liu, ”MARCO: A High-performance Task Mapping and Routing Co-optimization Framework for Point-to-Point NoC-based Heterogeneous Computing Systems” in ACM Transactions on Embedded Computing Systems (TECS) 2021.
* **[ICCAD'23]** Shiqing Li, Di Liu, and Weichen Liu “Optimized Data Reuse via Reordering for Sparse Matrix-Vector Multiplication on FPGAs” in International Conference on Computer-Aided Design (ICCAD) 2021.
* **[DATE'23]** Shiqing Li and Weichen Liu, ”Accelerating Gustavson-based SpMM on Embedded FPGAs with Element-wise Parallelism and Access Pattern-aware Caches” in Design, Automation and Test in Europe (DATE), April 2023. (*Best Paper Candidate award*)
* **[FPL'23]** Shiqing Li, Shien Zhu, Xiangzhong Luo, Tao Luo and Weichen Liu, “An Efficient Sparse LSTM Accelerator on Embedded FPGAs with Bandwidth-oriented Pruning” in the 33rd edition of International Conference on Field-Programmable Logic and Applications (FPL 2023)
* **[DATE'19]** Shiqing Li, Yixun Wei and Lei Ju, "Automatic data placement for CPU-FPGA heterogeneous multiprocessor System-on-Chips," 2019 Design, Automation & Test in Europe Conference & Exhibition (DATE), Florence, Italy, 2019.
* **[ASPDAC'23]** Hui Chen, Di Liu, Shiqing Li, Shuo Huai, Xiangzhong Luo, Weichen Liu, ”MUGNoC: A Software-Configured Multicast-Unicast-Gather NoC for Accelerating CNN Dataflows.” in 28th Asia and South Pacific Design Automation Conference (ASPDAC 2023).
* **[GLVLSI'22]** Shien Zhu, Shiqing Li, and Weichen Liu, ”iMAD: An In-Memory Accelerator for AdderNet with Efficient 8-bit Addition and Subtraction Operations” in the 2022 Great Lakes Symposium on VLSI (GLSVLSI ’22), June 2022. (*Best Paper Candidate award*)
* **[SAC'21]** Peng Chen, Hui Chen, Jun Zhou, Di Liu, Shiqing Li, Weichen Liu, Wanli Chang, Nan Guan, ”Partial order based non-preemptive communication scheduling towards real-time networks-on-chip” in the 36th ACM/SIGAPP Symposium on Applied Computing (SAC), 2021.


