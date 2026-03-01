# Awesome Physical AI

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

- **[Foundation Models for Decision Making](https://arxiv.org)** - Exploring how LLMs/VLMs enable reasoning in robotic tasks
- **[RT-2: Vision-Language-Action Models](https://robotics-transformer2.github.io)** - Baidu/Google DeepMind
- **[RT-3: Vision-Language-Action for General-Robot](https://deepmind.google/research/publications/)** 
- **[Open X-Embodiment](https://robotics-transformerX.github.io)** - RT-X: Generalist robot policies from multiple embodiments

### World Models & Simulation

- **[GAIA-1: Generative World Model](https://wayve.ai/thinking/gaia-1/)** - Wayve's generative world model for autonomous driving
- **[Daydreamer](https://dreamwalker.github.io)** - World Model for Real-World Robot Learning
- **[DreamerV2](https://dreamerv2.github.io)** - Model-based reinforcement learning with recurrent world models

### Manipulation & Grasping

- **[Foundation Manipulation](https://foundation-manipulation.github.io)** - Stanford's manipulation research
- **[UniGrasp](https://unigrasp.github.io)** - Learning universal grasping policies

### Navigation & Locomotion

- **[Learning to Walk in Minutes](https://anymal.mit.edu)** - MIT's quadruped robot learning
- **[RT-1: Robotics Transformer](https://robotics-transformer.github.io)**

### Multi-Modal Understanding

- **[MVP](https://multiviewpenguin.github.io)** - Multi-View Prompting for Robot Zero-Shot Execution
- **[VoxPoser](https://voxposer.github.io)** - Composable 3D Value Maps for Zero-Shot Robotic Manipulation

---

## Frameworks & Libraries

### Agent Frameworks

- [RAI](https://github.com/RobotecAI/rai) - Vendor-agnostic agentic framework for Physical AI using ROS 2
- [LangChain](https://github.com/langchain-ai/langchain) - Building agents with external tools
- [OpenHands](https://github.com/OpenHands/OpenHands) - AI-driven development agent

### ROS & Robotics

- [copper-rs](https://github.com/copper-project/copper-rs) - Operating system for robots in Rust (deterministic replay)
- [ROS 2](https://docs.ros.org/en/humble/) - Robot Operating System 2
- [ROS 2 AI](https://github.com/ros2/ros2_ai) - AI integration for ROS 2

### Training & Fine-Tuning

- [LlamaFactory](https://github.com/hiyouga/LlamaFactory) - Unified fine-tuning of 100+ LLMs & VLMs
- [LeRobot](https://github.com/huggingface/lerobot) - Making AI for robotics accessible with end-to-end learning
- [dmlj](https://github.com/DLR-RM/dm_lab_juicer) - DeepMind's JAX-based robot learning

### Perception

- [Grounded SAM 2](https://github.com/IDEA-Research/Grounded-SAM-2) - Segment Anything Model 2 for robotics
- [OVMM](https://openvocabmm.github.io) - Open Vocabulary Mobile Manipulation

---

## Datasets

- [Open X-Embodiment Dataset](https://robotics-datasets.github.io) - 1M+ robot trajectories across 80+ embodiments
- [RT-1 Dataset](https://rt1-dataset.github.io) - Large-scale robot manipulation dataset
- [Bridge Dataset](https://berkeleyautomation.github.io/bridge_dataset/) - Kuka robot data
- [CALVIN](https://calvin-dataset.github.io) - Multi-task manipulation benchmark
- [ManiSkill](https://maniskill2.github.io) - SAPIEN manipulation skill benchmark

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

### Cloud & Remote

- [Gola](https://github.com/) - Cloud robotics simulation (add if found)
- [RainbowDash](https:///) - (add if found)

---

## Projects

### Humanoid Robots

- [Unitree Go](https://github.com/unitreerobotics) - Quadruped robots
- [Apollo](https://github.com/Apollo) - Apollo Robot (add specific repo)
- [Digit](https://github.com/AgilityRobotics) - Agility Robotics humanoid

### Mobile Manipulation

- [Mobile ALOHA](https://mobile-aloha.github.io) - Mobile manipulation research from Stanford
- [PALM-E](https://palm-e.github.io) - Google's embodied multimodal language model

### Research Labs

- [Stanford RISELab](https://github.com/rise-lab-skku) - Real-time intelligent systems
- [MIT CSAIL](https://csail.mit.edu) - Computer Science and AI Lab
- [Google DeepMind Robotics](https://research.google/robotics/) - Robotics research

---

## Courses & Tutorials

### University Courses

- [MIT 6.5940: Foundation Models for Decision Making](https://foundation-model-decision-making.github.io)
- [Stanford CS 224R: Machine Learning for Robots](https://cs224r.stanford.edu)
- [UC Berkeley CS 287: Robot Manipulation](https://cs287.github.io)

### Online Resources

- [Physical AI for Science](https://github.com/labclaw/awesome-physical-ai-for-science) - Resources for AI in scientific discovery
- [Awesome 3D Gaussian Splatting](https://github.com/MrNeRF/awesome-3D-gaussian-splatting) - 3D GS for robotics
- [Awesome Robot Learning](https://github.com/arkulpa/awesome-robot-learning) - Robot learning resources
- [Awesome Embodied AI](https://github.com/P卷王/awesome-embodied-vision) - Embodied vision and AI

### Hands-On Tutorials

- [Isaac Lab Documentation](https://isaaclab.readthedocs.io)
- [LeRobot Tutorial](https://huggingface.co/learn/lerobot)

---

## Community

### Forums & Discussions

- [Physical AI Discord](https://discord.gg/physical-ai) - (verify link)
- [ROS Discourse](https://discourse.ros.org) - ROS community
- [r/robotics](https://reddit.com/r/robotics) - Reddit robotics
- [r/MLOS](https://reddit.com/r/MLOS) - Machine learning for robotics

### Conferences & Events

- [CoRL](https://www.robot-learning.org) - Conference on Robot Learning
- [ICRA](https://www.icra2025.org) - International Conference on Robotics and Automation
- [IROS](https://www.iros2025.org) - Intelligent Robots and Systems
- [RSS](https://www.robotics-science.org) - Robotics: Science and Systems
- [NeurIPS Embodied AI Workshop](https://neurips.cc/virtual) - (check annually)

### Newsletters

- [The Robot Report](https://www.therobotreport.com)
- [IEEE Spectrum Robotics](https://spectrum.ieee.org/robotics)
- [MIT Technology Review AI](https://www.technologyreview.com/ai)

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
