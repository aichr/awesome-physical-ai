# Awesome Physical AI

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Star History](https://img.shields.io/badge/Star%20History-⌛+gold?style=flat&logo=github)](https://star-history.com/#aichr/awesome-physical-ai)

> A curated collection of resources for Physical AI — where robotics, machine learning, and embodied intelligence converge to build intelligent physical systems.

Physical AI refers to AI systems that can perceive, reason about, and interact with the physical world. This includes robot learning, manipulation, navigation, embodied AI, world models, simulation, and more.

## Contents

- [Foundation Models (VLA)](#foundation-models-vla)
- [3D Computer Vision](#3d-computer-vision)
- [Datasets](#datasets)
- [Benchmarks](#benchmarks)
- [Simulators](#simulators)
- [Edge AI & Inference](#edge-ai--inference)
- [Hardware & Actuation](#hardware--actuation)
- [Frameworks & Libraries](#frameworks--libraries)
- [Robot Platforms](#robot-platforms)
- [Research Labs](#research-labs)
- [Courses & Tutorials](#courses--tutorials)
- [Community](#community)

---

## Foundation Models (VLA)

### 🤖 Industry Models

| Model | Description | Links |
|-------|-------------|-------|
| **Nvidia GR00T** | Foundation model for humanoid robots | 🎬 [Demo](https://research.nvidia.com/labs/gear/gr00t-n1_6/) |
| **Physical Intelligence π0** | VLA flow model (10k+ hours robot data) | 📄 [Paper](https://arxiv.org/abs/2410.24164) · 💻 [Code](https://github.com/Physical-Intelligence/openpi) |
| **Physical Intelligence π0.5** | VLA with open-world generalization | 📄 [Paper](https://arxiv.org/abs/2504.16054) |
| **Gemini Robotics** | Google's multimodal reasoning for robots | 📄 [Paper](https://deepmind.google/models/gemini-robotics/) |
| **Amazon DeepFleet** | Fleet coordination (1M+ robots) | 📄 [Article](https://www.aboutamazon.com/news/operations/amazon-million-robots-ai-foundation-model) |

### 📄 Academic Papers

| Paper | Description | Tags |
|-------|-------------|------|
| **[RT-2](https://robotics-transformer2.github.io/)** | VLA model learning from web + robotics data | 🎬 |
| **[RT-1](https://arxiv.org/abs/2212.06817)** | Robotics Transformer for real-world control | 🎬 |
| **[Open X-Embodiment](https://robotics-transformer-x.github.io/)** | RT-X: Generalist policies from 22 platforms | 🤖 |
| **[PaLM-E](https://palm-e.github.io)** | Embodied multimodal language model | |
| **[Octo](https://octo-models.github.io/)** | Open-source diffusion policy (800k episodes) | 💻 🤖 |
| **[LingBot-VLA](https://arxiv.org/abs/2601.18692)** | 20k hours real robot data, 261 samples/sec | |
| **[Recursive Belief VLA](https://arxiv.org/abs/2602.20659)** | Belief-centric architecture | |

---

## 3D Computer Vision

### Neural Radiance Fields & 3DGS

- **[Awesome 3D Gaussian Splatting](https://github.com/MrNeRF/awesome-3D-gaussian-splatting)** 📚
- **[2025 GS Paper List](https://github.com/Lee-JaeWon/2025-Arxiv-Paper-List-Gaussian-Splatting)** 📚 Updated daily
- **[NeRF + GS for Robotics](https://openaccess.thecvf.com/content/ICCV2025/papers/Fang_NeRF_Is_a_Valuable_Assistant_for_3D_Gaussian_Splatting_ICCV_2025_paper.pdf)** 🎬

### Point Cloud & Depth

- **[Depth Anything](https://github.com/LiheYoung/Depth-Anything)** 💻 Foundation model for depth estimation
- **[MiDaS](https://github.com/isl-org/MiDaS)** Monocular depth estimation

### Object Detection & Segmentation

- **[SAM 3](https://arxiv.org/abs/2511.16719)** Segment Anything with concepts | 📄 💻
- **[SAM 3D](https://arxiv.org/abs/2306.03908)** Segment Anything in 3D scenes | 📄
- **[Grounded SAM 2](https://github.com/IDEA-Research/Grounded-SAM-2)** For robotics | 🤖 💻

---

## Datasets (Training Data)

- **[Open X-Embodiment](https://github.com/google-deepmind/open_x_embodiment)** 🤖 — 1M+ trajectories, 80+ embodiments
- **[BridgeData V2](https://github.com/rail-berkeley/bridge_data_v2)** — Large-scale manipulation (Berkeley)
- **[ManiSkill](https://github.com/haosulab/ManiSkill)** — SAPIEN manipulation benchmark
- **[CALVIN](https://github.com/Mees/calvin)** — Multi-task manipulation
- **[RT-1 Dataset](https://blog.google/technology/ai/rt-1-robotics-transformer/)** — Google's robot data

---

## Benchmarks (Evaluation)

- **[VLABench](https://vlabench.github.io/)** — Language-conditioned manipulation benchmark for VLAs 📄
- **[LIBERO](https://libero-robot.github.io/)** — Benchmark for robot manipulation
- **[RoboTwin](https://arxiv.org/pdf/2509.09674)** — Twin benchmark for VLA training
- **[ManiSkill](https://github.com/haosulab/ManiSkill)** — Manipulation skill evaluation
- **[CALVIN](https://github.com/Mees/calvin)** — Multi-task benchmark

---

## Simulators

### General-Purpose

- **[Isaac Lab](https://github.com/isaac-sim/IsaacLab)** 🤖 — NVIDIA GPU-accelerated robot learning
- **[Genesis](https://github.com/Genesis-Embodied-AI/Genesis)** — Generative world for robotics
- **[MuJoCo](https://github.com/deepmind/mujoco)** — Multi-Joint Dynamics with Contact
- **[PyBullet](https://github.com/bulletphysics/bullet3)** — Physics simulation
- **[Gymnasium](https://github.com/Farama-Foundation/Gymnasium)** — Standard RL API

### Task-Specific

- **[Habitat](https://github.com/facebookresearch/habitat)** — Embodied AI in 3D environments
- **[iGibson](https://github.com/StanfordVL/iGibson)** — Interactive Gibson benchmark
- **[SAPIEN](https://sapien.ucsd.edu)** — Realistic physics & sensory simulation
- **[Webots](https://github.com/cyberbotics/webots)** — Robot simulator

---

## Edge AI & Inference

### Deployment Frameworks

- **[TensorRT-LLM for Edge](https://developer.nvidia.com/blog/accelerating-llm-and-vlm-inference-for-automotive-and-robotics-with-nvidia-tensorrt-edge-llm)** — NVIDIA's edge inference optimization
- **[NVIDIA Jetson](https://developer.nvidia.com/blog/getting-started-with-edge-ai-on-nvidia-jetson-llms-vlms-and-foundation-models-for-robotics/)** — Edge AI deployment for robots
- **[vLLM](https://github.com/vllm-project/vllm)** — High-performance LLM inference

### Quantization & Optimization

- **[llama.cpp](https://github.com/ggerganov/llama.cpp)** — Quantized LLM inference
- **[AutoGPTQ](https://github.com/AutoGPTQ/AutoGPTQ)** — GPTQ quantization
- **[TensorRT](https://developer.nvidia.com/tensorrt)** — Optimized deep learning inference

---

## Hardware & Actuation

### Tactile Sensing

- **[GelSight](https://www.gelsight.com/gelsightmini/)** — Gel-based tactile sensors
- **[Awesome-Touch](https://github.com/linchangyi1/Awesome-Touch)** 📚 — Curated tactile sensing resources
- **[AnySkin](https://arxiv.org/abs/2401.17695)** — Plug-and-play robotic skin
- **[DexSkin](https://corl2025.org/)** — Conformable robotic skin (CoRL 2025)

### Motor Controllers & Actuation

- **[EtherCAT](https://www.ethercat.org/)** — Real-time industrial communication
- **[ROS 2 Control](https://control.ros.org/)** — Hardware-agnostic robot control
- **[Dynamixel](https://robotis.us/dynamixel/)** — Robot actuators

### Compute Platforms

- **[NVIDIA Jetson](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/)** — Edge AI compute
- **[Google Coral](https://coral.ai/)** — Edge TPU modules
- **[Intel Neural Compute Stick](https://www.intel.com/content/www/us/en/developer/tools/neural-compute-stick.html)** — NPU for edge

---

## Frameworks & Libraries

### Agent & AI

- [RAI](https://github.com/RobotecAI/rai) 🤖 — Vendor-agnostic agentic framework (ROS 2)
- [LangChain](https://github.com/langchain-ai/langchain) — Building agents with tools
- [OpenHands](https://github.com/OpenHands/OpenHands) — AI-driven development
- [OpenClaw](https://github.com/openclaw/openclaw) — Personal AI assistant

### ROS & Robotics

- [copper-rs](https://github.com/copper-project/copper-rs) 🤖 — OS for robots in Rust (deterministic replay)
- [ROS 2](https://docs.ros.org/en/humble/) — Robot Operating System 2
- [ROS 2 AI](https://github.com/ros2/ros2_ai) — AI integration for ROS 2

### Training & Fine-Tuning

- [LlamaFactory](https://github.com/hiyouga/LlamaFactory) — Unified fine-tuning of 100+ LLMs
- [LeRobot](https://github.com/huggingface/lerobot) 🤖 — End-to-end robot learning
- [Daydreamer](https://github.com/danijar/daydreamer) — World models for robot learning

---

## Robot Platforms

### Humanoid & Quadruped

- [Unitree Robotics](https://github.com/unitreerobotics) 🤖 — Go1, Go2, Ali (quadrupeds)
- [Agility Robotics - Digit](https://github.com/AgilityRobotics) 🤖 — Humanoid for logistics
- [Apollo Robot](https://apollo.auto/developer) 🤖 — Apollo humanoid
- [ANYbotics](https://www.anybotics.com/robotics/anymal/) 🤖 — ANYmal quadruped

### Mobile Manipulation

- [Mobile ALOHA](https://mobile-aloha.github.io) 🤖 — Stanford low-cost mobile manipulation
- [Amazon Robotics](https://www.aboutamazon.com/news/operations/amazon-million-robots-ai-foundation-model) 🤖 — 1M+ robots deployed

---

## Research Labs

- [Nvidia GEAR Lab](https://research.nvidia.com/labs/gear/) — Generalist Embodied Agent Research
- [Physical Intelligence](https://www.pi.website/) — Generalist robot foundation models
- [Stanford RISELab](https://github.com/rise-lab-skku) — Real-time intelligent systems
- [Stanford VL](https://github.com/StanfordVL) — Vision & Learning Lab
- [MIT Robotics](https://robotics.mit.edu/) — MIT's central robotics hub
- [MIT Distributed Robotics Lab](https://www.csail.mit.edu/research/distributed-robotics-laboratory) — CSAIL
- [MIT Media Lab Personal Robots](https://robots.media.mit.edu/) — Socially intelligent robots
- [Berkeley RAIL Lab](https://rail-berkeley.github.io/) — Robot Autonomy and Interactive Learning
- [Google DeepMind](https://deepmind.google/) — Robotics research

---

## Courses & Tutorials

### University

- [Stanford CS 224R: Machine Learning for Robots](https://cs224r.stanford.edu)
- [MIT Foundation Models & AI](https://ocw.mit.edu/courses/6-s087-foundation-models-and-generative-ai-january-iap-2024/)

### Hands-On

- [Isaac Lab Documentation](https://developer.nvidia.com/isaac/lab)
- [LeRobot Tutorial](https://huggingface.co/learn/lerobot)

### Online Resources

- [Physical AI for Science](https://github.com/labclaw/awesome-physical-ai-for-science)

---

## Community

### Forums

- [ROS Discourse](https://discourse.ros.org)
- [r/robotics](https://reddit.com/r/robotics)
- [r/ROS](https://reddit.com/r/ROS)
- [r/MachineLearning](https://reddit.com/r/MachineLearning)

### Conferences

- [CoRL](https://www.robot-learning.org) — Conference on Robot Learning
- [ICRA](https://www.icra2025.org) — Robotics and Automation
- [IROS](https://www.iros2025.org) — Intelligent Robots and Systems
- [RSS](https://www.robotics-science.org) — Robotics: Science and Systems

### News

- [The Robot Report](https://www.therobotreport.com)
- [IEEE Spectrum Robotics](https://spectrum.ieee.org/robotics)

---

## Legend

| Tag | Meaning |
|-----|---------|
| 📄 | Paper / Research Paper |
| 🎬 | Has Demo Video |
| 💻 | Open Source Code |
| 🤖 | Hardware-Verified (tested on real robots) |
| 📚 | Awesome List / Collection |

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=aichr/awesome-physical-ai&type=Date)](https://star-history.com/#aichr/awesome-physical-ai)

---

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting PRs.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

---

> *Physical AI is not just about making robots smarter — it's about bridging the gap between digital intelligence and physical reality.*
