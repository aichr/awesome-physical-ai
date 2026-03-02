# Awesome Physical AI

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated collection of resources for Physical AI — where robotics, machine learning, and embodied intelligence converge to build intelligent physical systems.

Physical AI refers to AI systems that can perceive, reason about, and interact with the physical world. This includes robot learning, manipulation, navigation, embodied AI, world models, simulation, and more.

## Contents

- [Foundation Models (VLA)](#foundation-models-vla)
- [3D Computer Vision for Robotics](#3d-computer-vision-for-robotics)
- [World Models & Simulation](#world-models--simulation)
- [Datasets](#datasets)
- [Simulators](#simulators)
- [Frameworks & Libraries](#frameworks--libraries)
- [Robot Platforms](#robot-platforms)
- [Research Labs](#research-labs)
- [Courses & Tutorials](#courses--tutorials)
- [Community](#community)

---

## Foundation Models (VLA)

### Academic Papers

- **[RT-2: Vision-Language-Action Models](https://robotics-transformer2.github.io/)** - Google DeepMind's VLA model
- **[RT-1: Robotics Transformer](https://arxiv.org/abs/2212.06817)** - Robotics Transformer for real-world control at scale
- **[Open X-Embodiment](https://robotics-transformer-x.github.io/)** - RT-X: Generalist robot policies from 22 diverse platforms
- **[PaLM-E](https://palm-e.github.io)** - Google's embodied multimodal language model
- **[Octo](https://octo-models.github.io/)** - Open-source generalist robot policy (800k robot episodes)
- **[LingBot-VLA](https://arxiv.org/abs/2601.18692)** - VLA trained on 20k hours real robot data, 261 samples/sec
- **[Recursive Belief VLA](https://arxiv.org/abs/2602.20659)** - Belief-centric architecture tracking task progress

### Industry Models

- **[Physical Intelligence π0](https://arxiv.org/abs/2410.24164)** - Vision-Language-Action flow model for general robot control (10k+ hours robot data)
- **[Physical Intelligence π0.5](https://arxiv.org/abs/2504.16054)** - VLA model with open-world generalization for mobile manipulation
- **[OpenPi](https://github.com/Physical-Intelligence/openpi)** - Official implementation from Physical Intelligence
- **[Gemini Robotics](https://deepmind.google/models/gemini-robotics/)** - Google's Gemini for robotics
- **[Gemini Robotics-ER 1.5](https://deepmind.google/blog/gemini-robotics-15-brings-ai-agents-into-the-physical-world/)** - Embodied reasoning model for planning in physical environments
- **[Nvidia GR00T N1](https://research.nvidia.com/labs/gear/gr00t/)** - Foundation model for humanoid robots
- **[Nvidia GR00T N1.5](https://research.nvidia.com/labs/gear/gr00t-n1_5/)** - Improved architecture and data
- **[Nvidia GR00T N1.6](https://research.nvidia.com/labs/gear/gr00t-n1_6/)** - Latest version
- **[Amazon DeepFleet](https://www.aboutamazon.com/news/operations/amazon-million-robots-ai-foundation-model)** - Foundation model for robotic fleet (1M+ robots)

---

## 3D Computer Vision for Robotics

### Neural Radiance Fields & 3D Gaussian Splatting

- **[Awesome 3D Gaussian Splatting](https://github.com/MrNeRF/awesome-3D-gaussian-splatting)** - Curated paper list
- **[2025 GS Paper List](https://github.com/Lee-JaeWon/2025-Arxiv-Paper-List-Gaussian-Splatting)** - Updated daily
- **[NeRF + GS for Robotics](https://openaccess.thecvf.com/content/ICCV2025/papers/Fang_NeRF_Is_a_Valuable_Assistant_for_3D_Gaussian_Splatting_ICCV_2025_paper.pdf)** - ICCV 2025 paper

### Point Cloud & Depth Estimation

- **[Depth Anything](https://github.com/LiheYoung/Depth-Anything)** - Foundation model for monocular depth estimation
- **[MiDaS](https://github.com/isl-org/MiDaS)** - Monocular depth estimation
- **[3D Point Cloud Segmentation](https://www.mdpi.com/2227-7080/138/322)** - Survey on deep learning for 3D point clouds

### Object Detection & Reconstruction

- **[SAM 3](https://arxiv.org/abs/2511.16719)** - Segment Anything Model 3 with concept-based detection, segmentation, and tracking
- **[SAM 3D](https://arxiv.org/abs/2306.03908)** - Segment Anything in 3D scenes, extends 2D segmentation to point clouds
- **[Grounded SAM 2](https://github.com/IDEA-Research/Grounded-SAM-2)** - SAM 2 for robotics
- **[OpenScene](https://github.com/pengsongyou/OpenScene)** - Open-vocabulary 3D scene understanding

---

## World Models & Simulation

### Papers

- **[GAIA-1](https://arxiv.org/abs/2309.17080)** - Wayve's generative world model for autonomous driving
- **[Scaling GAIA-1](https://wayve.ai/thinking/scaling-gaia-1/)** - 9-billion parameter version
- **[DayDreamer](https://arxiv.org/abs/2206.14176)** - World models for real-world robot learning
- **[DreamerV2](https://arxiv.org/abs/2110.09516)** - Model-based RL with recurrent world models

### Projects

- **[Genesis](https://github.com/Genesis-Embodied-AI/Genesis)** - Generative world for general-purpose robotics

---

## Datasets

- **[Open X-Embodiment](https://github.com/google-deepmind/open_x_embodiment)** - 1M+ robot trajectories, 80+ embodiments
- **[BridgeData V2](https://github.com/rail-berkeley/bridge_data_v2)** - Large-scale manipulation (Berkeley RAIL)
- **[CALVIN](https://github.com/Mees/calvin)** - Multi-task manipulation benchmark
- **[ManiSkill](https://github.com/haosulab/ManiSkill)** - SAPIEN-based manipulation benchmark
- **[RT-1 Dataset](https://blog.google/technology/ai/rt-1-robotics-transformer/)** - Google's robot manipulation

---

## Simulators

### General-Purpose

- **[Isaac Lab](https://github.com/isaac-sim/IsaacLab)** - NVIDIA's GPU-accelerated robot learning
- **[Isaac Lab Docs](https://developer.nvidia.com/isaac/lab)** - Documentation & tutorials
- **[MuJoCo](https://github.com/deepmind/mujoco)** - Multi-Joint Dynamics with Contact
- **[PyBullet](https://github.com/bulletphysics/bullet3)** - Physics simulation
- **[Gymnasium](https://github.com/Farama-Foundation/Gymnasium)** - Standard RL API

### Task-Specific

- **[Habitat](https://github.com/facebookresearch/habitat)** - Embodied AI in 3D environments
- **[iGibson](https://github.com/StanfordVL/iGibson)** - Interactive Gibson benchmark
- **[SAPIEN](https://sapien.ucsd.edu)** - Realistic physics & sensory simulation
- **[Webots](https://github.com/cyberbotics/webots)** - Robot simulator

---

## Frameworks & Libraries

### Agent & AI Frameworks

- [RAI](https://github.com/RobotecAI/rai) - Vendor-agnostic agentic framework for Physical AI (ROS 2)
- [LangChain](https://github.com/langchain-ai/langchain) - Building agents with tools
- [OpenHands](https://github.com/OpenHands/OpenHands) - AI-driven development agent
- [OpenClaw](https://github.com/openclaw/openclaw) - Personal AI assistant

### ROS & Robotics

- [copper-rs](https://github.com/copper-project/copper-rs) - OS for robots in Rust (deterministic replay)
- [ROS 2](https://docs.ros.org/en/humble/) - Robot Operating System 2
- [ROS 2 AI](https://github.com/ros2/ros2_ai) - AI integration for ROS 2

### Training & Fine-Tuning

- [LlamaFactory](https://github.com/hiyouga/LlamaFactory) - Unified fine-tuning of 100+ LLMs & VLMs
- [LeRobot](https://github.com/huggingface/lerobot) - End-to-end robot learning
- [Daydreamer](https://github.com/danijar/daydreamer) - World models for robot learning
- [LeRobot Tutorial](https://huggingface.co/learn/lerobot) - Hugging Face course

---

## Robot Platforms

### Humanoid & Quadruped

- [Unitree Robotics](https://github.com/unitreerobotics) - Quadruped robots (Go1, Go2, Ali)
- [Agility Robotics - Digit](https://github.com/AgilityRobotics) - Humanoid for logistics
- [Apollo Robot](https://apollo.auto/developer) - Apollo humanoid
- [ANYbotics](https://www.anybotics.com/robotics/anymal/) - ANYmal quadruped

### Mobile Manipulation

- [Mobile ALOHA](https://mobile-aloha.github.io) - Stanford's low-cost mobile manipulation
- [Amazon Robotics](https://www.aboutamazon.com/news/operations/amazon-million-robots-ai-foundation-model) - 1M+ robots deployed

---

## Research Labs

- [Nvidia GEAR Lab](https://research.nvidia.com/labs/gear/) - Generalist Embodied Agent Research
- [Physical Intelligence](https://www.pi.website/) - Generalist robot foundation models
- [Stanford RISELab](https://github.com/rise-lab-skku) - Real-time intelligent systems
- [MIT Robotics](https://robotics.mit.edu/) - MIT's central robotics hub
- [MIT Distributed Robotics Lab](https://www.csail.mit.edu/research/distributed-robotics-laboratory) - CSAIL robotics group
- [MIT Media Lab Personal Robots](https://robots.media.mit.edu/) - Socially intelligent robots
- [Google DeepMind](https://deepmind.google/) - Main research site
- [Berkeley RAIL Lab](https://rail-berkeley.github.io/) - Robot Autonomy and Interactive Learning
- [Stanford VL](https://github.com/StanfordVL) - Vision & Learning Lab

---

## Courses & Tutorials

### University Courses

- [Stanford CS 224R: Machine Learning for Robots](https://cs224r.stanford.edu)
- [MIT Foundation Models & AI](https://ocw.mit.edu/courses/6-s087-foundation-models-and-generative-ai-january-iap-2024/)

### Online Resources

- [Physical AI for Science](https://github.com/labclaw/awesome-physical-ai-for-science)
- [Isaac Lab Documentation](https://developer.nvidia.com/isaac/lab)

---

## Community

### Forums

- [ROS Discourse](https://discourse.ros.org)
- [r/robotics](https://reddit.com/r/robotics)
- [r/ROS](https://reddit.com/r/ROS)
- [r/MachineLearning](https://reddit.com/r/MachineLearning)

### Conferences

- [CoRL](https://www.robot-learning.org) - Conference on Robot Learning
- [ICRA](https://www.icra2025.org) - Robotics and Automation
- [IROS](https://www.iros2025.org) - Intelligent Robots and Systems
- [RSS](https://www.robotics-science.org) - Robotics: Science and Systems

### News

- [The Robot Report](https://www.therobotreport.com)
- [IEEE Spectrum Robotics](https://spectrum.ieee.org/robotics)

---

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting PRs.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

---

> *Physical AI is not just about making robots smarter — it's about bridging the gap between digital intelligence and physical reality.*
