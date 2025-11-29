### Hi there, I'm Kush Kapoor! 👋

I am an **Undergraduate Researcher** passionate about bridging the gap between algorithmic demand and hardware constraints. My work focuses on **Computer Architecture**, **Hardware-Software Co-Design**, and **Domain-Specific Architectures (DSAs)** for ML and Serverless computing.

I specialize in building end-to-end systems—from architecting RTL in **SystemVerilog** to writing **C-based drivers** and developing rigorous **Python verification pipelines**.

---

### 🔬 Research Interests

* **Computer Architecture:** Manycore systems, Cache coherence, Custom memory hierarchies.
* **Domain-Specific Architectures:** Hardware acceleration for Transformers (LLMs), GCNs, and Sparse workloads.
* **Emerging Systems:** Hardware support for Serverless Computing and Processing-in-Memory (PIM).
* **Verification:** Trace-driven co-simulation, Cycle-accurate modeling, and FPGA prototyping.

---

### 🛠️ Featured Research Projects

#### ⚡ Hardware-Software Co-Design & Manycore Systems
| Project | Description | Stack |
| :--- | :--- | :--- |
| **[HB-TaskQueue-CoSim](https://github.com/KushKapoor2006/HB-TaskQueue-CoSim)** | **Hardware Task Queue for HammerBlade Manycore**<br>• Engineered a hardware FIFO task queue to eliminate leader-core dispatch bottlenecks, achieving **4.2× speedup**.<br>• Built a rigorous verification pipeline (C-driver + Python oracle) uncovering **3,164 functional mismatches** prior to synthesis. | `SystemVerilog` `C++` `Python` `Verilator` |
| **[serverless-shim-hdu](https://github.com/KushKapoor2006/serverless-shim-hdu)** | **Hardware Dispatch Unit for Serverless**<br>• Architected an HDU to offload authorization/scheduling, achieving **7.41× speedup** over SW with **0.02µs** latency.<br>• Synthesized to a minimal **425 cells** (Yosys) with a custom cycle-accurate simulation model. | `SystemVerilog` `Yosys` `Python` `Sim` |

#### 🧠 AI Accelerators & Memory Systems
| Project | Description | Stack |
| :--- | :--- | :--- |
| **[Flexagon-DSA](https://github.com/KushKapoor2006/Flexagon-DSA)** | **Memory-Prefetch Extension for NN Accelerators**<br>• Designed "FlexPipe," a synthesizable memory controller with pointer-walking prefetch DMA.<br>• Achieved **1.33× (VGG-16)** and **1.10× (DistilBERT)** speedup by boosting DRAM utilization to **95%**. | `SystemVerilog` `C` `Yosys` `DRAMSim` |
| **[SpAtten](https://github.com/KushKapoor2006/SpAtten)** | **Speculative Lookahead for Transformers**<br>• Implemented a cycle-aware simulator and RTL for speculative token pruning in Attention layers.<br>• Demonstrated **69.4% cycle reduction** with a **100% lookahead finish rate** for sparse Transformers. | `Verilog` `Python` `Monte-Carlo` |

#### 🌐 Graph Processing & PIM
| Project | Description | Stack |
| :--- | :--- | :--- |
| **[island_gcn_simulator](https://github.com/KushKapoor2006/island_gcn_simulator)** | **Island-Based GCN Accelerator**<br>• Prototyped adaptive PE merging to mitigate `c_max` granularity bottlenecks in Graph Convolutional Networks.<br>• Demonstrated **1.55× speedup** and **2× DRAM traffic reduction** via event-driven simulation. | `Python` `SystemVerilog` `GCNs` |
| **[PIM_NN](https://github.com/KushKapoor2006/PIM_NN)** | **Processing-in-Memory Neural Primitives**<br>• Developed a hardware sequencer to replace CPU oversight in PIM operations.<br>• Achieved **3.02× speedup** on control-heavy workloads, verified via cycle-approximate simulation. | `SystemVerilog` `Python` `PIM` |

---

### 💻 Technical Stack

* **HDL & Synthesis:** SystemVerilog, Verilog, Yosys, Vivado, Quartus.
* **Simulation & Verification:** Verilator, Gem5, ModelSim, GTKWave, Python (cocotb/custom harnesses).
* **Software & Systems:** C/C++, RISC-V Assembly, Python, Linux, Git.

---

### Contact
- Email: *kushkapoor.kk1234@gmail.com*
- Phone: +91 7042918473

> Open to internships, research collaborations, and project mentorship.

---

<div align="center">
  <p><i>"The goal is not just to build hardware, but to build systems that are verifiable, synthesizable, and mathematically rigorous."</i></p>
</div>
