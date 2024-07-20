# Paper List for Robotics & Embodied AI - [Tianxing Chen](https://tianxingchen.github.io)
## 0. Table of contents
1. Diffusion Model for Planning, Policy, and RL
2. 3D-based Manipulation
3. 2D-based Manipulation
4. LLM for robotics
5. LLM Agent (Planning)
6. Visual Feature: Correspondence, Affordance
7. Detection & Segmentation
8. Pose Estimation and Tracking
9. Humanoid
10. Dataset & Benchmark
11. Hardware
12. 2D to 3D Generation
13. Gaussion Splatting
14. Robotics for Medical
15. Companies

## 1. Diffusion Model for Planning, Policy, and RL
* **[arXiv]** Diffusion Models for Reinforcement Learning: A Survey, [arXiv](https://arxiv.org/abs/2311.01223)

* **[ICLR 2023 (Top 5% Notable)]** Is Conditional Generative Modeling all you need for Decision-Making?, [website](https://anuragajay.github.io/decision-diffuser/)

* **[RSS 2023]** Diffusion Policy: Visuomotor Policy Learning via Action Diffusion, [website](https://diffusion-policy.cs.columbia.edu/)

* **[ICML 2022 (Long Talk)]** Planning with Diffusion for Flexible Behavior Synthesis, [website](https://diffusion-planning.github.io/mobile.html)

* **[ICML 2023 Oral]** Adaptdiffuser: Diffusion models as adaptive self-evolving planners, [website](https://adaptdiffuser.github.io/)

* **[CVPR 2024]** SkillDiffuser: Interpretable Hierarchical Planning via Skill Abstractions in Diffusion-Based Task Execution, [website](https://skilldiffuser.github.io/)

* **[arXiv]** Learning a Diffusion Model Policy From Reward via Q-Score Matching, [arXiv](https://arxiv.org/abs/2312.11752)

* **[CoRL 2023]** ChainedDiffuser: Unifying Trajectory Diffusion and Keypose Prediction for Robotic Manipulation, [website](https://chained-diffuser.github.io/)

* **[CVPR 2023]** Affordance Diffusion: Synthesizing Hand-Object Interactions, [website](https://judyye.github.io/affordiffusion-www/)

* **[arXiv]** DiffuserLite: Towards Real-time Diffusion Planning, [arXiv](https://arxiv.org/abs/2401.15443)

* **[arXiv]** 3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations, [website](https://3d-diffusion-policy.github.io/)

* **[arXiv]** 3D Diffuser Actor: Policy Diffusion with 3D Scene Representations, [website](https://3d-diffuser-actor.github.io/)

* **[arXiv]** SafeDiffuser: Safe Planning with Diffusion Probabilistic Models, [arXiv](https://safediffuser.github.io/safediffuser/)

* **[CVPR 2024]** Hierarchical Diffusion Policy for Kinematics-Aware Multi-Task Robotic Manipulation, [arXiv](https://yusufma03.github.io/projects/hdp/)
  
* **[arXiv 2024]** Render and Diffuse: Aligning Image and Action Spaces for Diffusion-based Behaviour Cloning, [arXiv](https://arxiv.org/abs/2405.18196)

* **[arXiv 2024]** Surgical Robot Transformer: Imitation Learning for Surgical Tasks, [website](https://surgical-robot-transformer.github.io/)

## 2. 3D-based Manipulation

* **[RSS 2024]** RVT-2: Learning Precise Manipulation from Few Examples [website](https://robotic-view-transformer-2.github.io/)

* **[arXiv 2023]** D<sup>3</sup> Fields: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Robotic Manipulation, [website](https://robopil.github.io/d3fields/)

* **[arXiv 2024]** UniDoorManip: Learning Universal Door Manipulation Policy Over Large-scale and Diverse Door Manipulation Environments, [website](https://arxiv.org/pdf/2403.02604)

* **[CoRL 2023 (Oral)]** GNFactor: Multi-Task Real Robot Learning with Generalizable Neural Feature Fields, [website](https://yanjieze.com/GNFactor/)

### 2.2 Grasping
* GraspNet [website](https://graspnet.net/)：
  * **[TRO 2023]** AnyGrasp: Robust and Efficient Grasp Perception in Spatial and Temporal Domains, [arXiv](https://arxiv.org/abs/2212.08333)
* **[arXiv 2024]** ThinkGrasp: A Vision-Language System for Strategic Part Grasping in Clutter, [website](https://h-freax.github.io/thinkgrasp_page/)

## 3. 2D-based Manipulation
* **[NIPS 2023]** MoVie: Visual Model-Based Policy Adaptation for View Generalization, [website](https://yangsizhe.github.io/MoVie/)

## 4. LLM for robotics (LLM Agent)
* **[arXiv 2024]** OK-Robot: What Really Matters in Integrating Open-Knowledge Models for Robotics, [website](https://ok-robot.github.io)

* **[CoRL 2023]** VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models, [website](https://voxposer.github.io)

* **[arXiv 2023]** ChatGPT for Robotics: Design Principles and Model Abilities, [arXiv](https://arxiv.org/abs/2306.17582)

* **[arXiv 2024]** Language-Guided Object-Centric Diffusion Policy for Collision-Aware Robotic Manipulation, [arXiv](https://arxiv.org/pdf/2407.00451)

* **[PMLR 2023]** RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control, [website](https://robotics-transformer2.github.io/)

## 5. LLM Agnet (planning)
Coming Soon

## 6. Visual Feature
### 6.1 Correspondence
* **[arXiv 2023]** D<sup>3</sup> Fields: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Robotic Manipulation, [website](https://robopil.github.io/d3fields/)

* **[CoRL 2020]** Transporter Networks: Rearranging the Visual World for Robotic Manipulation, [website](https://transporternets.github.io)

* **[ICLR 2024]** SparseDFF: Sparse-View Feature Distillation for One-Shot Dexterous Manipulation, [website](https://arxiv.org/abs/2310.16838)

* **[ICRA 2024]** UniGarmentManip: A Unified Framework for Category-Level Garment Manipulation via Dense Visual Correspondence, [website](https://warshallrho.github.io/unigarmentmanip/)

* **[CoRL 2018]** Dense Object Nets: Learning Dense Visual Object Descriptors By and For Robotic Manipulation, [PDF](https://arxiv.org/pdf/1806.08756)

### 6.2 Affordance

* **[CoRL 2022]** Perceiver-Actor: A Multi-Task Transformer for Robotic Manipulation, [website](https://peract.github.io/)

* **[arXiv 2024]** Robo-ABC: Affordance Generalization Beyond Categories via Semantic Correspondence for Robot Manipulation, [arXiv](https://arxiv.org/abs/2401.07487)

* **[arXiv 2024]** PreAfford: Universal Affordance-Based Pre-Grasping for Diverse Objects and Environments, [arXiv](https://air-discover.github.io/PreAfford/)

* **[ICLR 2022]** VAT-Mart: Learning Visual Action Trajectory Proposals for Manipulating 3D ARTiculated Objects, [website](https://hyperplane-lab.github.io/vat-mart/)

* **[ICLR 2023]** DualAfford: Learning Collaborative Visual Affordance for Dual-gripper Object Manipulation, [arXiv](https://arxiv.org/abs/2207.01971)

* **[CVPR 2022]** Joint Hand Motion and Interaction Hotspots Prediction from Egocentric Videos, [website](https://stevenlsw.github.io/hoi-forecast/)

* **[ICCV 2023]** AffordPose: A Large-scale Dataset of Hand-Object Interactions with Affordance-driven Hand Pose, [website](https://affordpose.github.io/)

## 7. Detection & Segmentation

* **[ECCV 2024]** Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection, [Github repo](https://github.com/IDEA-Research/GroundingDINO?tab=readme-ov-file)

* **[arXiv 2024]** Grounded SAM: Marrying Grounding DINO with Segment Anything & Stable Diffusion & Recognize Anything - Automatically Detect, Segment and Generate Anything, [Github repo](https://github.com/IDEA-Research/Grounded-Segment-Anything)

* **[ICCV 2023]** DEVA: Tracking Anything with Decoupled Video Segmentation, [website](https://hkchengrex.com/Tracking-Anything-with-DEVA/)

* **[ECCV 2022]** Mem: Long-Term Video Object Segmentation with an Atkinson-Shiffrin Memory Model, [website](hkchengrex.com/XMem/)

## 8. Pose Estimation and Tracking
* **[CVPR 2024 (Highlight)]** FoundationPose: Unified 6D Pose Estimation and Tracking of Novel Objects, [website](https://nvlabs.github.io/FoundationPose/)

* **[CVPR 2023 (Highlight)]** GAPartNet: Cross-Category Domain-Generalizable Object Perception and Manipulation via Generalizable and Actionable Parts, [website](https://pku-epic.github.io/GAPartNet/)

* **[arXiv 2023]** GAMMA: Generalizable Articulation Modeling and Manipulation for Articulated Objects, [website](https://sites.google.com/view/gamma-articulation)

* **[arXiv 2024]** ManiPose: A Comprehensive Benchmark for Pose-aware Object Manipulation in Robotics, [website](https://sites.google.com/view/manipose)

* **[ICCV 2023]** AffordPose: A Large-scale Dataset of Hand-Object Interactions with Affordance-driven Hand Pose, [website](https://affordpose.github.io/)

* **[CVPR 2023]** BundleSDF: Neural 6-DoF Tracking and 3D Reconstruction of Unknown Objects, [website](https://bundlesdf.github.io/)

## 9. Humanoid
* **[arXiv 2024]** HumanPlus: Humanoid Shadowing and Imitation from Humans, [website](https://humanoid-ai.github.io/)


## 10. Dataset & Benchmark
* **[arXiv 2024]** Empowering Embodied Manipulation: A Bimanual-Mobile Robot Manipulation Dataset for Household Tasks, [website](https://embodiedrobot.github.io/), [zhihu](https://zhuanlan.zhihu.com/p/688624666?utm_medium=social&utm_psn=1756405102318243840&utm_source=wechat_sessiong)
* **[arXiv 2024]** GRUtopia: Dream General Robots in a City at Scale, [Github Repo](https://github.com/OpenRobotLab/GRUtopia)
* **[ICLR 2024]** AgentBoard: An Analytical Evaluation Board of Multi-Turn LLM Agents, [website](https://hkust-nlp.github.io/agentboard/)
* **[arXiv 2024]** RoboCAS: A Benchmark for Robotic Manipulation in Complex Object Arrangement Scenarios, [Github repo](https://github.com/notFoundThisPerson/RoboCAS-v0)

## 11. Hardware
* **[arXiv 2024]** DexCap: Scalable and Portable Mocap Data Collection System for Dexterous Manipulation, [website](https://dex-cap.github.io/)

## 12. 2D to 3D Generation

* **[arXiv 2024]** Unique3D: High-Quality and Efficient 3D Mesh Generation from a Single Image, [website](https://wukailu.github.io/Unique3D/)

## 13. Gaussian Splatting

* **[SIGGRAPH 2024]** 2DGS: 2D Gaussian Splatting for Geometrically Accurate Radiance Fields, [website](https://surfsplatting.github.io/)

## 14. Robotics for Medical
* **[arXiv 2024]** Surgical Robot Transformer: Imitation Learning for Surgical Tasks, [website](https://surgical-robot-transformer.github.io/)

## TO READ

* Where2Act: From Pixels to Actions for Articulated 3D Objects

* PreAfford: Universal Affordance-Based Pre-Grasping for Diverse Objects and Environments

* Decision Transformer: Reinforcement Learning via Sequence Modeling

* Toward General-Purpose Robots via Foundation Models: A Survey and Meta-Analysis

* AO-Grasp: Articulated Object Grasp Generation

* Human-to-Robot Imitation in the Wild

* RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots

* SAM-E: Leveraging Visual Foundation Model with Sequence Imitation for Embodied Manipulation https://sam-embodied.github.io/, ICML2024

* https://progprompt.github.io/

* PerAct, Act3D

* https://groups.csail.mit.edu/vision/datasets/ADE20K/

* Probing the 3D Awareness of Visual Foundation Model: https://arxiv.org/pdf/2404.08636

* ManipVQA: Injecting Robotic Affordance and Physically Grounded Information into Multi-Modal Large Language Models

* CLIP: Zero-shot Jack of All Trades, [website](https://blog.kzakka.com/posts/clip/), [CLIP GradCAM CLIP_GradCAM_Visualization](https://colab.research.google.com/github/kevinzakka/clip_playground/blob/main/CLIP_GradCAM_Visualization.ipynb)

* Articulated Object Manipulation with Coarse-to-fine Affordance for Mitigating the Effect of Point Cloud Noise: https://arxiv.org/pdf/2402.18699

* 3D-VLA: A 3D Vision-Language-Action Generative World Model
* PDDLGym: Gym Environments from PDDL Problems: https://arxiv.org/abs/2002.06432
* https://github.com/zjunlp/LLMAgentPapers?tab=readme-ov-file
* https://github.com/zjunlp/Prompt4ReasoningPapers
* TravelPlanner: A Benchmark for Real-World Planning with Language Agents
