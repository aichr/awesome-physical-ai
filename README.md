# Awesome Physical AI

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated collection of resources for Physical AI — where robotics, machine learning, and embodied intelligence converge to build intelligent physical systems.

Physical AI refers to AI systems that can perceive, reason about, and interact with the physical world. This includes robot learning, manipulation, navigation, embodied AI, world models, simulation, and more.

## Contents

- [Papers](#papers)
- [Frameworks & Libraries](#frameworks--libraries)
- [Datasets](#datasets)
- [Simulators](#simulators)
- [Projects](#projects)
- [Courses & Tutorials](#courses--tutorials)
- [Community](#community)

---

## Papers

### Foundation Models for Robotics

- **[Physical Intelligence π0](https://arxiv.org/abs/2410.24164)** - Vision-Language-Action flow model for general robot control (10k+ hours robot data)
- **[Physical Intelligence π0.5](https://arxiv.org/abs/2504.16054)** - VLA model with open-world generalization for mobile manipulation
- **[OpenPi](https://github.com/Physical-Intelligence/openpi)** - Official implementation and checkpoints from Physical Intelligence
- **[RT-2: Vision-Language-Action Models](https://robotics-transformer2.github.io/)** - Google DeepMind's VLA model that learns from web and robotics data
- **[RT-1: Robotics Transformer](https://arxiv.org/abs/2211.09417)** - Model trained on multi-task robot demonstrations
- **[Open X-Embodiment](https://robotics-transformer-x.github.io/)** - RT-X: Generalist robot policies from 22 diverse robot platforms
- **[PaLM-E: An Embodied Multimodal Language Model](https://palm-e.github.io)** - Google's embodied multimodal language model
- **[Octo: Open-Source Generalist Robot Policy](https://octo-models.github.io/)** - Transformer-based diffusion policy pretrained on 800k robot episodes

### Industry & Research Labs

- **[Nvidia GEAR Lab](https://research.nvidia.com/labs/gear/)** - Generalist Embodied Agent Research building foundation models for embodied agents
- **[GR00T N1](https://research.nvidia.com/labs/gear/gr00t/)** - Nvidia's general-purpose foundation model for humanoid robots
- **[GR00T N1.5](https://research.nvidia.com/labs/gear/gr00t-n1_5/)** - Upgraded version with improved architecture and data
- **[GR00T N1.6](https://research.nvidia.com/labs/gear/gr00t-n1_6/)** - Latest version of GR00T foundation model
- **[Amazon DeepFleet](https://www.aboutamazon.com/news/operations/amazon-million-robots-ai-foundation-model)** - Amazon's foundation model for robotic fleet coordination (1M+ robots)
- **[Amazon Blue Jay](https://www.aboutamazon.com/news/operations/amazon-delivering-future-2025-online-shopping-speed-delivery)** - Amazon's latest robotics and AI technology
- **[Physical Intelligence](https://www.pi.website/)** - Company building generalist robot models (π0, π0.5)

### World Models & Simulation

- **[GAIA-1: Generative World Model](https://arxiv.org/abs/2309.17080)** - Wayve's generative world model for autonomous driving
- **[Scaling GAIA-1](https://wayve.ai/thinking/scaling-gaia-1/)** - 9-billion parameter version
- **[DayDreamer: World Models for Physical Robot Learning](https://arxiv.org/abs/2206.14176)** - World model for real-world robot learning
- **[DreamerV2](https://arxiv.org/abs/2110.09516)** - Model-based RL with recurrent world models

### Manipulation & Grasping

- **[Universal Manipulation Interface (UMI)](https://github.com/real-stanford/universal_manipulation_interface)** - Stanford's in-the-wild robot teaching
- **[UniGrasp](https://arxiv.org/abs/2208.11508)** - Learning universal grasping policies

### Navigation & Locomotion

- **[Learning to Walk in Minutes](https://arxiv.org/abs/2304.01189)** - MIT's quadruped robot learning with rapid motor adaptation
- **[ANYmal](https://anymal.mit.edu)** - MIT's ANYmal quadruped robot research

### Multi-Modal Understanding

- **[VoxPoser: Composable 3D Value Maps](https://voxposer.github.io)** - Zero-shot robotic manipulation with VLMs

---

## Frameworks & Libraries

### Agent Frameworks

- [RAI](https://github.com/RobotecAI/rai) - Vendor-agnostic agentic framework for Physical AI using ROS 2
- [LangChain](https://github.com/langchain-ai/langchain) - Building agents with external tools
- [OpenHands](https://github.com/OpenHands/OpenHands) - AI-driven development agent
- [OpenClaw](https://github.com/openclaw/openclaw) - Personal AI assistant for any OS

### ROS & Robotics

- [copper-rs](https://github.com/copper-project/copper-rs) - Operating system for robots in Rust (deterministic replay)
- [ROS 2](https://docs.ros.org/en/humble/) - Robot Operating System 2
- [ROS 2 AI](https://github.com/ros2/ros2_ai) - AI integration for ROS 2

### Training & Fine-Tuning

- [LlamaFactory](https://github.com/hiyouga/LlamaFactory) - Unified fine-tuning of 100+ LLMs & VLMs
- [LeRobot](https://github.com/huggingface/lerobot) - Making AI for robotics accessible with end-to-end learning
- [Daydreamer](https://github.com/danijar/daydreamer) - World Models for Physical Robot Learning

### Perception

- [Grounded SAM 2](https://github.com/IDEA-Research/Grounded-SAM-2) - Segment Anything Model 2 for robotics

---

## Datasets

- [Open X-Embodiment](https://github.com/google-deepmind/open_x_embodiment) - 1M+ robot trajectories across 80+ embodiments
- [BridgeData V2](https://github.com/rail-berkeley/bridge_data_v2) - Large-scale manipulation dataset from Berkeley RAIL
- [CALVIN](https://github.com/Mees/calvin) - Multi-task manipulation benchmark
- [ManiSkill](https://github.com/haosulab/ManiSkill) - SAPIEN-based manipulation skill benchmark
- [RT-1 Dataset](https://blog.google/technology/ai/rt-1-robotics-transformer/) - Google's large-scale robot manipulation dataset

---

## Simulators

### General-Purpose

- [Isaac Lab](https://github.com/NVIDIA-Isaac/IsaacLab) - NVIDIA's reference environment for robot learning
- [Genesis](https://github.com/Genesis-Embodied-AI/Genesis) - Generative world for general-purpose robotics
- [MuJoCo](https://github.com/deepmind/mujoco) - Multi-Joint Dynamics with Contact
- [PyBullet](https://github.com/bulletphysics/bullet3) - Physics simulation for robotics
- [Gymnasium](https://github.com/Farama-Foundation/Gymnasium) - Standard API for RL environments

### Task-Specific

- [Habitat](https://github.com/facebookresearch/habitat) - Embodied AI in simulated 3D environments
- [iGibson](https://github.com/StanfordVL/iGibson) - Interactive Gibson benchmark
- [SAPIEN](https://sapien.ucsd.edu) - Realistic physics and sensory simulation
- [Webots](https://github.com/cyberbotics/webots) - Robot simulator

---

## Projects

### Humanoid & Quadruped Robots

- [Unitree Robotics](https://github.com/unitreerobotics) - Quadruped robots (Go1, Go2, Ali)
- [Agility Robotics - Digit](https://github.com/AgilityRobotics) - Humanoid robot for logistics
- [Apollo Robot](https://apollo.auto/developer) - Apollo humanoid robot
- [Amazon Robotics](https://www.aboutamazon.com/news/operations/amazon-million-robots-ai-foundation-model) - 1M+ robots deployed, DeepFleet foundation model

### Mobile Manipulation

- [Mobile ALOHA](https://mobile-aloha.github.io) - Stanford's mobile manipulation research with low-cost hardware

### Research Labs

- [Stanford RISELab](https://github.com/rise-lab-skku) - Real-time intelligent systems
- [MIT CSAIL](https://csail.mit.edu) - Computer Science and AI Lab
- [Google DeepMind Robotics](https://research.google/robotics/) - Robotics research
- [Berkeley RAIL Lab](https://rail-berkeley.github.io/) - Robot Autonomy and Interactive Learning
- [Nvidia GEAR Lab](https://research.nvidia.com/labs/gear/) - Generalist Embodied Agent Research
- [Physical Intelligence](https://www.pi.website/) - Building generalist robot foundation models

---

## Courses & Tutorials

### University Courses

- [Stanford CS 224R: Machine Learning for Robots](https://cs224r.stanford.edu) - Deep dive into robot learning
- [MIT Foundation Models & Decision Making](https://ocw.mit.edu/courses/6-s087-foundation-models-and-generative-ai-january-iap-2024/) - MIT OpenCourseWare on foundation models

### Online Resources

- [Physical AI for Science](https://github.com/labclaw/awesome-physical-ai-for-science) - AI in scientific discovery
- [Awesome 3D Gaussian Splatting](https://github.com/MrNeRF/awesome-3D-gaussian-splatting) - 3D GS for robotics

### Hands-On Tutorials

- [Isaac Lab Documentation](https://developer.nvidia.com/isaac/lab) - NVIDIA Isaac Lab tutorials
- [Isaac Lab GitHub](https://github.com/isaac-sim/IsaacLab) - Source code and examples
- [LeRobot Tutorial](https://huggingface.co/learn/lerobot) - Hugging Face LeRobot course

---

## Community

### Forums & Discussions

- [ROS Discourse](https://discourse.ros.org) - ROS community
- [r/robotics](https://reddit.com/r/robotics) - Reddit robotics
- [r/ROS](https://reddit.com/r/ROS) - Robot Operating System community
- [r/MachineLearning](https://reddit.com/r/MachineLearning) - Machine learning discussions

### Conferences & Events

- [CoRL](https://www.robot-learning.org) - Conference on Robot Learning
- [ICRA](https://www.icra2025.org) - International Conference on Robotics and Automation
- [IROS](https://www.iros2025.org) - Intelligent Robots and Systems
- [RSS](https://www.robotics-science.org) - Robotics: Science and Systems

### Newsletters

- [The Robot Report](https://www.therobotreport.com)
- [IEEE Spectrum Robotics](https://spectrum.ieee.org/robotics)

---

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting PRs.

### Adding Resources

1. Fork the repository
2. Add your resource to the appropriate section
3. Ensure links are working and include brief descriptions
4. Submit a PR with a clear description

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related or neighboring rights to this work.

---

> *Physical AI is not just about making robots smarter — it's about bridging the gap between digital intelligence and physical reality.*
