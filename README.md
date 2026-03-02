# Awesome Physical AI

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Star History](https://img.shields.io/badge/Star%20History-⌛+gold?style=flat&logo=github)](https://star-history.com/#aichr/awesome-physical-ai)

Curated resources for Physical AI — where robotics, machine learning, and embodied intelligence converge to build intelligent physical systems.

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
- [Legend](#legend)
- [Star History](#star-history)
- [Contributing](#contributing)
- [License](#license)

---

## Foundation Models (VLA)

### Industry Models

- [Nvidia GR00T](https://research.nvidia.com/labs/gear/gr00t-n1_6/) - Foundation model for humanoid robots.
- [Physical Intelligence π0](https://arxiv.org/abs/2410.24164) - VLA flow model with 10k+ hours robot data. Code: [openpi](https://github.com/Physical-Intelligence/openpi)
- [Physical Intelligence π0.5](https://arxiv.org/abs/2504.16054) - VLA with open-world generalization.
- [Gemini Robotics](https://deepmind.google/models/gemini-robotics/) - Google's multimodal reasoning for robots.
- [Amazon DeepFleet](https://www.aboutamazon.com/news/operations/amazon-million-robots-ai-foundation-model) - Fleet coordination for 1M+ robots.

### Academic Papers

- **RT-2** - VLA model learning from web and robotics data. [Demo](https://robotics-transformer2.github.io/)
- **RT-1** - Robotics Transformer for real-world control. [Paper](https://arxiv.org/abs/2212.06817)
- **Open X-Embodiment** - RT-X: Generalist policies from 22 platforms. [Page](https://robotics-transformer-x.github.io/)
- **PaLM-E** - Embodied multimodal language model. [Page](https://palm-e.github.io)
- **Octo** - Open-source diffusion policy with 800k episodes. [Page](https://octo-models.github.io/) [Code](https://github.com/octo-models/octo)
- **LingBot-VLA** - Trained on 20k hours real robot data, 261 samples/sec. [Paper](https://arxiv.org/abs/2601.18692)
- **Recursive Belief VLA** - Belief-centric architecture for task tracking. [Paper](https://arxiv.org/abs/2602.20659)

---

## 3D Computer Vision

### Neural Radiance Fields & 3DGS

- **Awesome 3D Gaussian Splatting** - Curated paper list. [GitHub](https://github.com/MrNeRF/awesome-3D-gaussian-splatting)
- **2025 GS Paper List** - Updated daily. [GitHub](https://github.com/Lee-JaeWon/2025-Arxiv-Paper-List-Gaussian-Splatting)
- **NeRF + GS for Robotics** - ICCV 2025 paper. [Paper](https://openaccess.thecvf.com/content/ICCV2025/papers/Fang_NeRF_Is_a_Valuable_Assistant_for_3D_Gaussian_Splatting_ICCV_2025_paper.pdf)

### Point Cloud & Depth

- **Depth Anything** - Foundation model for depth estimation. [Code](https://github.com/LiheYoung/Depth-Anything)
- **MiDaS** - Monocular depth estimation. [Code](https://github.com/isl-org/MiDaS)

### Object Detection & Segmentation

- **SAM 3** - Segment Anything with concepts. [Paper](https://arxiv.org/abs/2511.16719) [Code](https://github.com/facebookresearch/segment-anything-3)
- **SAM 3D** - Segment Anything in 3D scenes. [Paper](https://arxiv.org/abs/2306.03908)
- **Grounded SAM 2** - For robotics. [Code](https://github.com/IDEA-Research/Grounded-SAM-2)

---

## Datasets

- **Open X-Embodiment** - 1M+ trajectories, 80+ embodiments. [GitHub](https://github.com/google-deepmind/open_x_embodiment)
- **BridgeData V2** - Large-scale manipulation from Berkeley. [GitHub](https://github.com/rail-berkeley/bridge_data_v2)
- **ManiSkill** - SAPIEN manipulation benchmark. [GitHub](https://github.com/haosulab/ManiSkill)
- **CALVIN** - Multi-task manipulation. [GitHub](https://github.com/Mees/calvin)
- **RT-1 Dataset** - Google's robot data. [Blog](https://blog.google/technology/ai/rt-1-robotics-transformer/)

---

## Benchmarks

- **VLABench** - Language-conditioned manipulation benchmark for VLAs. [Page](https://vlabench.github.io/)
- **LIBERO** - Benchmark for robot manipulation. [Page](https://libero-robot.github.io/)
- **RoboTwin** - Twin benchmark for VLA training. [Paper](https://arxiv.org/pdf/2509.09674)
- **ManiSkill** - Manipulation skill evaluation. [GitHub](https://github.com/haosulab/ManiSkill)
- **CALVIN** - Multi-task benchmark. [GitHub](https://github.com/Mees/calvin)

---

## Simulators

### General-Purpose

- **Isaac Lab** - NVIDIA GPU-accelerated robot learning. [GitHub](https://github.com/isaac-sim/IsaacLab) [Docs](https://developer.nvidia.com/isaac/lab)
- **Genesis** - Generative world for robotics. [GitHub](https://github.com/Genesis-Embodied-AI/Genesis)
- **MuJoCo** - Multi-Joint Dynamics with Contact. [GitHub](https://github.com/deepmind/mujoco)
- **PyBullet** - Physics simulation. [GitHub](https://github.com/bulletphysics/bullet3)
- **Gymnasium** - Standard RL API. [GitHub](https://github.com/Farama-Foundation/Gymnasium)

### Task-Specific

- **Habitat** - Embodied AI in 3D environments. [GitHub](https://github.com/facebookresearch/habitat)
- **iGibson** - Interactive Gibson benchmark. [GitHub](https://github.com/StanfordVL/iGibson)
- **SAPIEN** - Realistic physics and sensory simulation. [Site](https://sapien.ucsd.edu)
- **Webots** - Robot simulator. [GitHub](https://github.com/cyberbotics/webots)

---

## Edge AI & Inference

### Deployment Frameworks

- **TensorRT-LLM for Edge** - NVIDIA's edge inference optimization. [Blog](https://developer.nvidia.com/blog/accelerating-llm-and-vlm-inference-for-automotive-and-robotics-with-nvidia-tensorrt-edge-llm)
- **NVIDIA Jetson** - Edge AI deployment for robots. [Blog](https://developer.nvidia.com/blog/getting-started-with-edge-ai-on-nvidia-jetson-llms-vlms-and-foundation-models-for-robotics/)
- **vLLM** - High-performance LLM inference. [GitHub](https://github.com/vllm-project/vllm)

### Quantization & Optimization

- **llama.cpp** - Quantized LLM inference. [GitHub](https://github.com/ggerganov/llama.cpp)
- **AutoGPTQ** - GPTQ quantization. [GitHub](https://github.com/AutoGPTQ/AutoGPTQ)
- **TensorRT** - Optimized deep learning inference. [Site](https://developer.nvidia.com/tensorrt)

---

## Hardware & Actuation

### Tactile Sensing

- **GelSight** - Gel-based tactile sensors. [Site](https://www.gelsight.com/gelsightmini/)
- **Awesome-Touch** - Curated tactile sensing resources. [GitHub](https://github.com/linchangyi1/Awesome-Touch)
- **AnySkin** - Plug-and-play robotic skin. [Paper](https://arxiv.org/abs/2401.17695)
- **DexSkin** - Conformable robotic skin. [Paper](https://corl2025.org/)

### Motor Controllers & Actuation

- **EtherCAT** - Real-time industrial communication. [Site](https://www.ethercat.org/)
- **ROS 2 Control** - Hardware-agnostic robot control. [Docs](https://control.ros.org/)
- **Dynamixel** - Robot actuators. [Site](https://robotis.us/dynamixel/)

### Compute Platforms

- **NVIDIA Jetson** - Edge AI compute. [Site](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/)
- **Google Coral** - Edge TPU modules. [Site](https://coral.ai/)
- **Intel Neural Compute Stick** - NPU for edge. [Site](https://www.intel.com/content/www/us/en/developer/tools/neural-compute-stick.html)

---

## Frameworks & Libraries

### Agent & AI

- **RAI** - Vendor-agnostic agentic framework for ROS 2. [GitHub](https://github.com/RobotecAI/rai)
- **LangChain** - Building agents with tools. [GitHub](https://github.com/langchain-ai/langchain)
- **OpenHands** - AI-driven development. [GitHub](https://github.com/OpenHands/OpenHands)
- **OpenClaw** - Personal AI assistant. [GitHub](https://github.com/openclaw/openclaw)

### ROS & Robotics

- **copper-rs** - OS for robots in Rust with deterministic replay. [GitHub](https://github.com/copper-project/copper-rs)
- **ROS 2** - Robot Operating System 2. [Docs](https://docs.ros.org/en/humble/)
- **ROS 2 AI** - AI integration for ROS 2. [GitHub](https://github.com/ros2/ros2_ai)

### Training & Fine-Tuning

- **LlamaFactory** - Unified fine-tuning of 100+ LLMs. [GitHub](https://github.com/hiyouga/LlamaFactory)
- **LeRobot** - End-to-end robot learning. [GitHub](https://github.com/huggingface/lerobot)
- **Daydreamer** - World models for robot learning. [GitHub](https://github.com/danijar/daydreamer)

---

## Robot Platforms

### Humanoid & Quadruped

- **Unitree Robotics** - Go1, Go2, Ali quadrupeds. [GitHub](https://github.com/unitreerobotics)
- **Agility Robotics - Digit** - Humanoid for logistics. [GitHub](https://github.com/AgilityRobotics)
- **Apollo Robot** - Apollo humanoid. [Site](https://apollo.auto/developer)
- **ANYbotics** - ANYmal quadruped. [Site](https://www.anybotics.com/robotics/anymal/)

### Mobile Manipulation

- **Mobile ALOHA** - Stanford low-cost mobile manipulation. [Page](https://mobile-aloha.github.io)
- **Amazon Robotics** - 1M+ robots deployed. [Article](https://www.aboutamazon.com/news/operations/amazon-million-robots-ai-foundation-model)

---

## Research Labs

- **Nvidia GEAR Lab** - Generalist Embodied Agent Research. [Page](https://research.nvidia.com/labs/gear/)
- **Physical Intelligence** - Generalist robot foundation models. [Site](https://www.pi.website/)
- **Stanford RISELab** - Real-time intelligent systems. [GitHub](https://github.com/rise-lab-skku)
- **Stanford VL** - Vision and Learning Lab. [GitHub](https://github.com/StanfordVL)
- **MIT Robotics** - MIT's central robotics hub. [Site](https://robotics.mit.edu/)
- **MIT Distributed Robotics Lab** - CSAIL robotics group. [Page](https://www.csail.mit.edu/research/distributed-robotics-laboratory)
- **MIT Media Lab Personal Robots** - Socially intelligent robots. [Page](https://robots.media.mit.edu/)
- **Berkeley RAIL Lab** - Robot Autonomy and Interactive Learning. [Page](https://rail-berkeley.github.io/)
- **Google DeepMind** - Robotics research. [Site](https://deepmind.google/)

---

## Courses & Tutorials

### University

- **Stanford CS 224R** - Machine Learning for Robots. [Site](https://cs224r.stanford.edu)
- **MIT Foundation Models & AI** - OpenCourseWare. [Site](https://ocw.mit.edu/courses/6-s087-foundation-models-and-generative-ai-january-iap-2024/)

### Hands-On

- **Isaac Lab Documentation** - NVIDIA Isaac Lab tutorials. [Docs](https://developer.nvidia.com/isaac/lab)
- **LeRobot Tutorial** - Hugging Face course. [Site](https://huggingface.co/learn/lerobot)

### Online Resources

- **Physical AI for Science** - AI in scientific discovery. [GitHub](https://github.com/labclaw/awesome-physical-ai-for-science)

---

## Community

### Forums

- **ROS Discourse** - ROS community. [Site](https://discourse.ros.org)
- **r/robotics** - Reddit robotics. [Reddit](https://reddit.com/r/robotics)
- **r/ROS** - Robot Operating System community. [Reddit](https://reddit.com/r/ROS)
- **r/MachineLearning** - Machine learning discussions. [Reddit](https://reddit.com/r/MachineLearning)

### Conferences

- **CoRL** - Conference on Robot Learning. [Site](https://www.robot-learning.org)
- **ICRA** - Robotics and Automation. [Site](https://www.icra2025.org)
- **IROS** - Intelligent Robots and Systems. [Site](https://www.iros2025.org)
- **RSS** - Robotics: Science and Systems. [Site](https://www.robotics-science.org)

### News

- **The Robot Report** - Robotics industry news. [Site](https://www.therobotreport.com)
- **IEEE Spectrum Robotics** - Robotics coverage. [Site](https://spectrum.ieee.org/robotics)

---

## Legend

- 📄 Paper
- 🎬 Demo Video
- 💻 Open Source Code
- 🤖 Hardware-Verified

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=aichr/awesome-physical-ai&type=Date)](https://star-history.com/#aichr/awesome-physical-ai)

---

## Contributing

Contributions welcome. Please read the [contributing guidelines](CONTRIBUTING.md) before submitting PRs.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
