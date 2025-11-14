#### Statistics
Compiled by [Boxuan Zhang](https://github.com/jucve)

A total of 70 GUI-related articles

highest average score: 6

lowest average score: 2.5

overall average score: 4.22

Highest-scoring articles: **1. ViMo: A Generative Visual GUI World Model for App Agents**
                   						 **2. OmniActor: A Generalist GUI and Embodied Agent for 2D&3D Worlds**
              							  **3. ScaleCUA: Scaling Open-Source Computer Use Agents with Cross-Platform Data**

Lowest-scoring articles: **1. Generalist Scanner Meets Specialist Locator: A Synergistic Coarse-to-Fine Framework for Robust GUI Grounding (2.5)**
                 						  **2. GUI-PRA: Process Reward Agent for GUI Tasks (2.8)**
                  					     **3. GUI-Shepherd: Reliable Process Reward and Verification for Long-Sequence GUI Tasks (2.7)**

[2,3): Three articles (4.3%)     [3,4): Twenty-two articles (31.4%)     [4,5): Twenty-seven articles (38.6%)     [5,6): Fifteen articles (21.4%)     [6,7): Three articles (4.3%)

#### Detailed Statistics

Title: Label-free GUI Grounding via Confidence-guided Negative Reinforcement Learning
TLDR: To address the bottleneck of high manual annotation costs in GUI agent scaling, based on insights that coordinate token confidence features and negative sample learning signals in sparse GUI coordinate spaces are more reliable, the proposed label-free training paradigms (CRL and CNRL) perform excellently on multiple benchmarks, confirming that coordinate token confidence can serve as an effective substitute for manual annotation.
Initial Scores: 6, 4, 6, 4
Confidence: 3, 4, 4, 5
Average Score: 5



Title: V2P: Visual Attention Calibration for GUI Grounding via Background Suppression and Center Peaking
TLDR: To address the bottleneck of high manual annotation costs in GUI agent scaling, based on insights that coordinate token confidence features and negative sample learning signals in sparse GUI coordinate spaces are more reliable, the proposed label-free training paradigms (CRL and CNRL) perform excellently on multiple benchmarks, confirming that coordinate token confidence can serve as an effective substitute for manual annotation.
Initial Scores: 4, 4, 4, 4
Confidence: 3, 4, 4, 4
Average Score: 4



Title: Learning GUI Grounding with Spatial Reasoning from Visual Feedback
TLDR: To address the Grounding problem for high-resolution, complex-layout GUIs, the GUI-Cursor 7B model reframes this task as an interactive search task. Trained via multi-step online reinforcement learning, it can output cursor movement actions to locate UI elements, achieving state-of-the-art accuracy on the ScreenSpot-v2 and ScreenSpot-Pro benchmarks. Furthermore, the number of movement steps during training decreases as accuracy improves, allowing it to adaptively handle samples of varying difficulty.
Initial Scores: 4, 6, 6, 4
Confidence: 4, 4, 4, 3
Average Score: 5



Title: UI-Ins: Enhancing GUI Grounding with Multi-Perspective Instruction as Reasoning
TLDR: To address the issue that existing GUI Grounding methods overlook the impact of instruction diversity, the proposed UI-Ins series of models, based on the "Instruction as Reasoning" paradigm and a two-stage training framework (supervised fine-tuning with diverse instructions + reinforcement learning for path selection and combination), achieves state-of-the-art results on multiple benchmarks. It also demonstrates emergent reasoning capabilities and excellent agent performance.
Initial Scores: 2, 6, 6, 6
Confidence: 4, 5, 4, 3
Average Score: 5



Title: UItron: Foundational GUI Agent with Advanced Perception and Planning
TLDR: Through innovative data pipelines and training frameworks, the proposed UItron has made significant advancements in both Chinese and English GUI agent interaction scenarios.
Initial Scores: 4, 6, 2, 2, 3
Confidence: 3, 3, 4, 4, 5
Average Score: 3.4



Title: GUI-ReWalk: Massive Data Generation for GUI Agent via Stochastic Exploration and Intent-Aware Reasoning
TLDR: To address the scarcity of high-quality trajectory data in GUI agent development, the reasoning-enhanced multi-stage framework GUI-ReWalk combines stochastic exploration with reasoning guidance to generate realistic, diverse GUI trajectory data supporting long-horizon workflows. Models trained with this data perform excellently on multiple benchmarks, confirming the framework's scalability and data efficiency, and promoting the development of real-world automation for GUI agents.
Initial Scores: 4, 4, 2
Confidence: 4, 4, 3
Average Score: 3.3



Title: GOLD: Global Overview to Local Detail in Efficient Visual Grounding for GUI Agents
TLDR: To address the high computational cost and difficulty in edge deployment of VLM-based GUI Grounding, the GOLD framework requires no fine-tuning and adapts to different interface densities. Through a three-stage process of global pruning, local refinement, and global-local context fusion, it reduces computational cost by 78% while improving accuracy by 0.7% on the ScreenSpot-V2 benchmark, confirming the efficiency of the global-to-local grounding approach.
Initial Scores: 4, 4, 6
Confidence: 3, 2, 3
Average Score: 4.7



Title: GUI-R1: A Generalist R1-Style Vision-Language Action Model For GUI Agents
TLDR: To solve the problems of large data requirements and weak generalization ability in existing LVLM-based SFT training paradigms for GUI agent development, GUI-R1 is the first reinforcement learning framework targeting advanced real-world task scenarios. By modeling a unified action space rule and utilizing a small amount of cross-platform high-quality data along with improved policy optimization algorithms, it surpasses previous SOTA methods on eight benchmarks across three major platforms using only 0.02% of the data (3K vs. 13M), confirming the great potential of this RL approach to enhance LVLM's practical GUI task execution capability.
Initial Scores: 2, 6, 4, 4
Confidence: 5, 2, 4, 4
Average Score: 3.5



Title: GUI‑AIMA: Aligning Intrinsic Multi-Modal Attention with a Context Anchor for GUI Grounding
TLDR: We proposed GUI-AIMA, a attention-based GUI visual grounding method supervised on anchored attention with query-adaptive multi-head weighting.
Initial Scores: 4, 4, 6, 2
Confidence: 4, 4, 4, 5
Average Score: 4



Title: Improving GUI Grounding with Explicit Position-to-Coordinate Mapping
TLDR: RULER tokens provide explicit position-to-pixel mapping and I-MRoPE balances spatial encoding, transforming GUI grounding from regression to referencing with strong high-resolution generalization.
Initial Scores: 2, 4, 4, 4
Confidence: 3, 3, 4, 5
Average Score: 3.5



Title: Beyond Clicking: A Step Towards Generalist GUI Grounding via Text Dragging
TLDR: We enhance and evaluate the text dragging capabilities of existing grounding models through an automated data collection pipeline and a comprehensive benchmark.
Initial Scores: 4, 4, 2, 6
Confidence: 4, 3, 4, 3
Average Score: 4



Title: Error as Signal: Stiffness-Aware Diffusion Sampling via Embedded Runge-Kutta Guidance
TLDR: Based on the key observation that the Local Truncation Error (LTE) of ODE trajectories in stiff regions of diffusion models is related to the dominant eigenvector, ERK-Guid requires no auxiliary network. By leveraging detected stiffness to reduce LTE and stabilize sampling, it consistently outperforms existing SOTA methods on synthetic datasets and the ImageNet benchmark.
Initial Scores: 4, 6, 4, 4
Confidence: 3, 3, 3, 3
Average Score: 4.5



Title: All in One: Unified Pretraining of GUI Agents via Masked Trajectory Prediction
TLDR: To address the issues of inconsistent objectives and data heterogeneity caused by directly unifying existing GUI agent pretraining strategies, the unified framework MTP integrates diverse pretraining strategies into a consistent objective through masking. Combined with a role-aware adapter learning module to handle data heterogeneity, it significantly outperforms previous methods and achieves SOTA on four major GUI navigation benchmarks, demonstrating excellent effectiveness and generalization capability.
Initial Scores: 4, 4, 2, 4
Confidence: 4, 4, 3, 5
Average Score: 3.5



Title: VistaGUI: Towards More Robust and Intelligent GUI Automation
TLDR: To address the fragility of existing GUI automation agents caused by low RAG retrieval accuracy, reliance on unimodal perception, and lack of failure recovery mechanisms, the multimodal GUI agent VistaGUI employs a unified framework comprising parallel instruction understanding modules, adaptive multimodal perception modules, and an environment-aware state management system. It significantly outperforms strong baseline models across various GUI automation tasks, excelling in task success rate, recovery speed, and overall robustness.
Initial Scores: 4, 4, 4, 4, 2
Confidence: 2, 2, 3, 4, 3
Average Score: 3.6



Title: ViMo: A Generative Visual GUI World Model for App Agents
TLDR: A visual world model that generates App GUI to help App agents envision outcomes of actions and make better decisions.
Initial Scores: 6, 4, 6, 8
Confidence: 3, 3, 4, 4
Average Score: 6



Title: GUI-Spotlight: Adaptive Iterative Focus Refinement for Enhanced GUI Visual Grounding
TLDR: A model trained for image-grounded reasoning that dynamically invokes multiple specialized tools to iteratively narrow its focus to the relevant region of the screen, thereby substantially improving visual grounding accuracy.
Initial Scores: 4, 6, 4, 2
Confidence: 5, 3, 3, 5
Average Score: 4



Title: Generalist Scanner Meets Specialist Locator: A Synergistic Coarse-to-Fine Framework for Robust GUI Grounding
TLDR: To improve GUI Grounding performance, the GMS framework, inspired by human interaction patterns, uses a generalist VLM as the "Scanner" to identify potential regions of interest and a fine-tuned grounding model as the "Locator" to output precise coordinates. Through a five-level architecture and hierarchical search with cross-modal communication, it achieves significant accuracy improvement on the ScreenSpot-Pro dataset and substantially outperforms various strong baseline models, demonstrating the robustness and potential of generalist GUI Grounding.
Initial Scores: 0, 4, 4, 2
Confidence: 5, 5, 4, 4
Average Score: 2.5



Title: SCREEN-SBERT: EMBEDDING FUNCTIONAL SEMANTICS OF GUI SCREENS TO SUPPORT GUI AGENTS
TLDR: To address the issues of low availability of structured metadata and insufficient functional matching of pure vision methods in GUI agent knowledge retrieval, Screen-SBERT is a pure vision method focusing on screenshot retrieval at the functional semantic level. It defines concepts of functional equivalence and functional page classes through a contrastive learning embedding framework. Its effectiveness in retrieving functionally equivalent screenshots in real mobile App scenarios surpasses several baseline models, providing effective support for the first stage of a two-stage retrieval framework.
Initial Scores: 4, 6, 4, 8
Confidence: 4, 3, 4, 4
Average Score: 5.5



Title: Grounding GUI Anything: Efficient and Semantically-Aware Parsing via Continuous Coordinate Decoding
TLDR: To address the limitations of existing GUI Grounding methods where discrete token generation restricts accuracy and efficiency, and predictions are confined to predefined elements, the end-to-end framework GGA combines MLLM with a regression decoder for continuous coordinate decoding, incorporates a rejection mechanism to reduce hallucinations, and introduces the ScreenParse benchmark. It consistently outperforms SOTA methods on multiple datasets, improving localization accuracy, inference speed, and generalization ability.
Initial Scores: 4, 8, 2, 2
Confidence: 4, 4, 4, 5
Average Score: 4



Title: Ferret-UI Lite: Lessons from Building Small On-Device GUI Agents
TLDR: To address the challenge of developing autonomous agents for cross-platform GUI interaction with small on-device models, FERRET-UI LITE is a compact end-to-end GUI agent with 3B parameters. By integrating real and synthetic GUI data, combining chain-of-thought reasoning with visual tool use, and employing on-device optimization techniques like reinforcement learning with reward mechanisms, it achieves competitiveness with other small GUI agents on GUI Grounding and navigation benchmarks. It also publicly shares methods and experiences for developing compact on-device GUI agents.
Initial Scores: 4, 4, 4, 6
Confidence: 4, 3, 5, 5
Average Score: 4.5



Title: D-Artemis: A Deliberative Cognitive Framework for Mobile GUI Multi-Agents
TLDR: To address the data bottleneck in end-to-end GUI agent training, high error detection costs, and the risk of conflicting guidance, the deliberative framework D-Artemis, inspired by the human "Think-Align-Reflect" cognitive loop, enhances MLLM's GUI task capabilities without relying on complex trajectory data training. It applies components such as exclusive prompt retrieval, pre-execution thought-action consistency checks and action correction, and post-execution state reflection. It achieves new SOTA on the AndroidWorld (75.8% success rate) and ScreenSpot-V2 (96.8%) benchmarks, with the contribution of each component validated through ablation studies.
Initial Scores: 4, 2, 2, 4
Confidence: 3, 4, 4, 4
Average Score: 3



Title: MobileGUI-RL: Advancing Mobile GUI Agent through Reinforcement Learning in Online Environment
TLDR: To solve the problems of poor scalability, overfitting to specific UI templates, and weak robustness to unknown environments caused by existing vision-based GUI agents relying on offline pre-collected trajectories for training, the online training framework MobileGUI-RL synthesizes learnable task curricula through self-exploration and filtering. It adapts GRPO for GUI navigation (combining trajectory awareness advantages with a composite reward balancing task success and execution efficiency), achieving continuous performance improvement on three online mobile agent benchmarks, validating its effectiveness.
Initial Scores: 4, 4, 2, 4, 4
Confidence: 4, 4, 4, 4, 5
Average Score: 3.6



Title: Difficulty-Aware Reasoning for Mobile GUI Automation via Reinforcement Fine-Tuning
TLDR: To address the issues of redundant computational overhead and performance degradation on simple steps caused by existing GUI agents using uniform Chain-of-Thought (CoT) reasoning, AdaGUI-R1 pioneers a difficulty-aware reasoning paradigm. It generates difficulty-aware reasoning trajectories through a self-supervised mechanism to provide the fundamental ability for dynamically adjusting reasoning depth, and enhances reasoning performance using the GAPO algorithm (including adaptive thinking reward and difficulty-aware Gaussian bandwidth exploration reward). It ultimately reduces redundant reasoning tokens by 40% while improving action accuracy by 5%, achieving new SOTA in GUI automation.
Initial Scores: 4, 4, 2, 4, 4
Confidence: 3, 4, 3, 4, 5
Average Score: 3.6



Title: GUI-360° : A Comprehensive Dataset and Benchmark for Computer-Using Agents
TLDR: To fill the gaps of scarce real-world Computer-Using Agents (CUAs) tasks, missing automated multimodal trajectory collection and annotation pipelines, and lack of unified benchmarks, the large-scale comprehensive dataset and benchmark suite GUI-360° is constructed through an automated process. It contains over 1.2 million Windows office application action steps and multimodal data, supporting three major tasks: GUI Grounding, screen parsing, action prediction, and a hybrid action space. Benchmark tests reveal native shortcomings in SOTA vision-language models, while supervised fine-tuning can bring significant performance improvements.
Initial Scores: 6, 4, 6, 2
Confidence: 3, 3, 3, 5
Average Score: 4.5



Title: UltraCUA: Scaling Computer Use Agent through GUI and Programmatic Control
TLDR: To solve the problems of cascading failures, performance bottlenecks due to reliance on primitive GUI actions, and lack of programming interface capabilities in Computer-Using Agents (CUAs), the foundational model UltraCUA seamlessly integrates GUI primitives with high-level programming tool calls through hybrid control. Relying on automated tool extension pipelines, a synthetic data engine, multi-agent trajectory generation, and a two-stage training pipeline, it achieves a 27% relative performance improvement on OSWorld with 11% faster steps, and reaches a 21.7% success rate in cross-domain testing on WindowsAgentArena. It reduces error propagation while ensuring execution efficiency, establishing a scalable paradigm connecting primitive GUI interaction with programmatic intelligence.
Initial Scores: 6, 4, 6, 4
Confidence: 3, 4, 4, 5
Average Score: 5



Title: Auto-scaling Continuous Memory for GUI Agent
TLDR: This research proposes a continuous memory mechanism (encoding GUI trajectories into fixed-length continuous embeddings using a VLM as the encoder) and an auto-scaling data flywheel. It reduces context costs and preserves visual details while achieving monotonically improving performance with increasing memory scale and retrieval depth. Fine-tuning only a small number of parameters enables Qwen-2.5-VL-7B to approach the performance of closed-source models like GPT-4o on real GUI tasks in long-horizon and distribution shift scenarios. Relevant data and code will be made public.
Initial Scores: 4, 6, 2, 4
Confidence: 4, 3, 4, 4
Average Score: 4



Title: Efficient Multi-turn RL for GUI Agents via Decoupled Training and Adaptive Data Curation
TLDR: This research proposes the Decoupled Agent Reinforcement Learning Training framework (DART), which improves system efficiency by asynchronously decoupling four modules: environment clusters, rollout services, data manager, and trainer. Combined with an adaptive data curation strategy (supplementing successful trajectories for high-difficulty tasks, etc.), it enables DART-GUI-7B to achieve a 42.13% task success rate on the OSWorld benchmark (a 14.61% improvement over the base model, exceeding the open-source SOTA by 7.34%). The relevant training framework, data, and model checkpoints will be open-sourced via a specified URL.
Initial Scores: 6, 4, 6
Confidence: 4, 4, 3
Average Score: 5.3



Title: GUI-PRA: Process Reward Agent for GUI Tasks
TLDR: We introduce GUI-PRA, a training-free judge agent that resolves key failure modes in GUI task supervision, through the lens of dynamic memory and adaptive UI perception.
Initial Scores: 4, 2, 2, 4, 2
Confidence: 2, 4, 3, 2, 3
Average Score: 2.8



Title: GUI-KV: Efficient GUI Agents via KV Cache with Spatio-Temporal Awareness
TLDR: This research addresses the low efficiency and slow inference in processing long sequences of high-resolution screenshots for VLM-driven GUI agents. Based on the insight that attention sparsity is high across all Transformer layers in GUI tasks, it proposes GUI-KV, a plug-and-play KV cache compression method requiring no retraining. By leveraging GUI-specific redundancy through spatial saliency guidance and temporal redundancy scoring, it outperforms similar cache compression baselines on multiple benchmarks. In the 5-screenshot scenario of AgentNetBench, it reduces decoding FLOPs by 38.9% and improves step accuracy by 4.1% compared to the full cache baseline.
Initial Scores: 2, 4, 6, 2
Confidence: 5, 3, 3, 4
Average Score: 3.5



Title: GUI-Shepherd: Reliable Process Reward and Verification for Long-Sequence GUI Tasks
TLDR: We propose a PRM and perform the first systematic study of process supervision in GUI agents from online long-horizon tasks to offline single-step prediction, from RL training to inference verification.
Initial Scores: 2, 2, 4
Confidence: 3, 4, 4
Average Score: 2.7



Title: InfiGUI-R1: Advancing Multimodal GUI Agents from Reactive Actors to Deliberative Reasoners
TLDR: This research addresses the capability level mismatch in the overall training paradigm of MLLM-driven GUI agents by proposing Actor2Reasoner, a two-stage hierarchical training paradigm of "Empower then Internalize". Through first-stage cognitive empowerment (goal supervised fine-tuning to inject key reasoning skills) and second-stage policy internalization (RL to internalize capabilities into robust decision-making policies), the instantiated InfiGUI-R1 achieves SOTA performance on benchmarks like AndroidControl, confirming that separating foundational capability empowerment from policy internalization is a superior path for building high-performance GUI agents.
Initial Scores: 8, 2, 4, 6
Confidence: 5, 3, 3, 3
Average Score: 5



Title: ProRe: A Proactive Reward System for GUI Agents via Reasoner–Actor Collaboration
TLDR: This research addresses the difficulties in generalizing existing reward methods to GUI agents and the limited accuracy of static LLM judging methods by proposing the proactive reward system ProRe. It schedules target state probing tasks through a general reasoner and collects additional observations via domain-specific evaluator agents actively interacting with the environment, enabling more accurate and verifiable reward assignment. On 3K+ trajectories, it improves reward accuracy and F1 score by up to 5.3% and 19.4% respectively. Integrated with SOTA policy agents, it boosts success rates by up to 22.4%.
Initial Scores: 4, 6, 6, 6
Confidence: 4, 3, 4, 4
Average Score: 5.5



Title: Agent-ScanKit: Unraveling Memory and Reasoning of Multimodal Agents via Sensitivity Perturbations
TLDR: We propose Agent-ScanKit to probe the memory and reasoning capabilities of MLLM-based agents via controlled perturbations. The results show that most agents rely on memorization rather than true reasoning, contravening safety over autonomy.
Initial Scores: 4, 4, 8, 4
Confidence: 4, 2, 3, 3
Average Score: 5



Title: GAIA: A Data Flywheel System for Training GUI Test-Time Scaling Critic Models
TLDR: This research addresses the irreversibility of operations in LVLM-driven GUI agents (where erroneous actions may lead to catastrophic deviation) by proposing the GAIA training framework. It iteratively enhances the Test-Time Scaling (TTS) performance of base GUI agents through critic capability: first training an Intuitive Critic Model (ICM) using positive and negative action samples from the base agent to assess action correctness, then using the critic model to guide the agent in collecting optimized samples, forming a self-improvement loop that trains a more discerning multi-round critic model. Experiments show that ICM improves test-time performance for various closed-source and open-source models, with performance gradually improving as data is recycled. Relevant code and datasets will be made public.
Initial Scores: 4, 6, 4, 4
Confidence: 3, 4, 3, 5
Average Score: 4.5



Title: GUI-Shift: Enhancing VLM-Based GUI Agents through Self-supervised Reinforcement Learning
TLDR: This research addresses the dependency of GUI agent training on large-scale annotated datasets (time-consuming and error-prone) by proposing the self-supervised inverse dynamics task K-step GUI Transition. This task enables the VLM to learn GUI dynamics by predicting the initial action causing the transition between two GUI states, without requiring natural language instructions, and can build scalable datasets from existing trajectories or automated exploration. Based on this, it proposes the GUI-Shift RL framework incorporating rule optimization and data filtering. On four benchmarks, GUI-Shift training shows good generalization for both GUI automation and grounding tasks, improving GUI automation accuracy by up to 11.2%, providing a scalable solution for training with unlabeled GUI trajectories.
Initial Scores: 6, 4, 6, 6
Confidence: 2, 4, 4, 3
Average Score: 5.5



Title: Computer-Use Agents as Judges for Automatic GUI Design
TLDR: The \bench benchmark covers 52 different domain applications and 1560 verifiable real-world simulation tasks. It proposes a "Coder (Designer)-CUA (Evaluator) Collaboration" framework, using the CUA dashboard to transform navigation history into interpretable guidance for optimizing design. The core metrics are task solvability and navigation success rate, promoting a shift towards agent-native, efficient, and reliable interface design, helping agents transition from passive use to active participation in digital environments.
Initial Scores: 2, 4, 4
Confidence: 4, 4, 4
Average Score: 3.3



Title: MobileA3gent: Training Mobile GUI Agents Using Decentralized Self-Sourced Data from Diverse Users
TLDR: MobileA3gent is a collaborative framework for training mobile GUI agents using globally distributed self-sourced data from diverse users. Through its Auto-Annotation component, it automatically collects high-quality datasets at low cost during users' daily phone use. Leveraging the FedVLM-A component, it combines episode-level and step-level variability for adaptive global aggregation, enhancing federated VLM training under non-IID conditions. It achieves superior performance at just 1% of the cost of traditional methods. Its code is open-source, providing a solution to the challenges of data collection and privacy protection in mobile GUI agent training.
Initial Scores: 2, 4, 6, 6
Confidence: 4, 3, 4, 3
Average Score: 4.5



Title: RISK: A Framework for GUI Agents in E-commerce Risk Management
TLDR: We introduce RISK, a framework that enables GUI agents to automate complex, multi-step web interactions for e-commerce risk management.
Initial Scores: 4, 4, 2
Confidence: 3, 4, 3
Average Score: 3.3



Title: $M^2$-Miner: Multi-Agent Enhanced MCTS for Mobile GUI Agent Data Mining
TLDR: We propose M-Miner, a Monte Carlo Tree Search-based collaborative multi-agent framework, which could efficiently mine GUI interaction trajectory data, thereby reducing the high cost of manual annotation.
Initial Scores: 4, 4, 6, 4
Confidence: 3, 3, 2, 4
Average Score: 4.5



Title: GUI Knowledge Bench: Revealing the Knowledge Gap Behind VLM Failures in GUI Tasks
TLDR: Although large Vision-Language Models (VLMs) have made progress in automating Graphical User Interface (GUI) tasks, they still fall short of humans. The research team posits that this gap stems from a lack of core GUI knowledge, distilled into three dimensions: interface perception, interaction prediction, and instruction understanding. They construct the GUI Knowledge Bench benchmark spanning 6 major platforms and 292 applications. Evaluation confirms that current VLMs have deficiencies in areas like system state perception and action prediction, and that GUI knowledge is closely related to task success rate. This research provides support for VLM selection and the construction of more efficient GUI agents.
Initial Scores: 2, 6, 4, 6
Confidence: 4, 3, 4, 4
Average Score: 4.5



Title: HyperClick: Advancing Reliable GUI Grounding via Uncertainty Calibration
TLDR: HyperClick improves the accuracy and confidence consistency of GUI agents in grounding tasks through uncertainty calibration and a dual-reward mechanism, mitigating overconfidence and enabling more reliable GUI automation.
Initial Scores: 2, 4, 2, 6, 4
Confidence: 4, 3, 2, 3, 4
Average Score: 3.6



Title: GAIR : GUI Automation via Information-Joint Reasoning and Group Reflection
TLDR: GAIR significantly enhances cross-task GUI automation performance and reliability by introducing a general MLLM to fuse information from multiple specialized GUI models and drive their "group reflection", integrating heterogeneous capabilities.
Initial Scores: 4, 4, 2, 2
Confidence: 3, 3, 4, 3
Average Score: 3



Title: LightAgent: Lightweight and Cost-Efficient Mobile Agents
TLDR: LightAgent achieves mobile GUI task performance close to that of large models while reducing invocation costs through a "small on-device model leads + large cloud model assists" approach and two-stage training.
Initial Scores: 4, 2, 4, 4
Confidence: 3, 4, 4, 4
Average Score: 3.5



Title: MobileWizard: A Data-Efficient GUI Agent with Structured Reasoning and Progressive Reinforcement Learning
TLDR: Leveraging structured chain-of-thought and progressive reinforcement learning, MobileWizard, a 7B model trained with only 24.8k trajectories, surpasses its 72B counterpart on AndroidWorld, realizing a data-efficient mobile GUI agent.
Initial Scores: 6, 6, 2, 2
Confidence: 4, 5, 3, 3
Average Score: 4



Title: OmniActor: A Generalist GUI and Embodied Agent for 2D&3D Worlds
TLDR: OmniActor resolves conflicts between GUI and embodied data through a "shallow-shared, deep-separated" Layer-heterogeneous MoE architecture, unifies the action space, and undergoes large-scale training, becoming a leading generalist multimodal agent excelling in both types of tasks.
Initial Scores: 10, 4, 4, 6
Confidence: 5, 3, 3, 4
Average Score: 6



Title: A3: Android Agent Arena For Mobile GUI Agents
TLDR: A3 addresses the shortcomings of existing static benchmarks by providing 100 online real App tasks and automatic "critical state" MLLM evaluation, offering a dynamic and efficient practical evaluation platform for mobile GUI agents.
Initial Scores: 4, 6, 4, 2, 2
Confidence: 4, 4, 3, 3, 4
Average Score: 3.6



Title: GuirlVG: Incentivize GUI Visual Grounding via Empirical Exploration on Reinforcement Learning
TLDR: Using only 5.2K samples and stable training with RL + adversarial KL factor, GuirlVG surpasses million-scale SFT methods in GUI visual grounding, providing a new paradigm for low-cost, high-performance GUI-VG.
Initial Scores: 6, 6, 4, 4
Confidence: 4, 3, 3, 5
Average Score: 5



Title: Towards Adaptive GUI Agents with Memory-Driven Knowledge Evolution
TLDR: We propose MAGNET, a memory-driven framework that adapts mobile app agents to UI and workflow changes for robust long-term reliability.
Initial Scores: 4, 2, 4, 2
Confidence: 4, 4, 4, 4
Average Score: 3



Title: WorldGUI: An Interactive Benchmark for Desktop GUI Automation from Any Starting Point
TLDR: We present a novel GUI benchmark called WorldGUI, which designs GUI tasks with various initial states to simulate authentic human-computer interactions.
Initial Scores: 2, 4, 2, 6
Confidence: 3, 4, 4, 3
Average Score: 3.5



Title: MobileRL: Online Agentic Reinforcement Learning for Mobile GUI Agents
TLDR: Using "Difficulty-Adaptive GRPO" online reinforcement learning, heavy-tailed distribution resampling, and shortest-path reward shaping, MOBILERL pushes a 9B model to a new SOTA of 80.2% on AndroidWorld, providing an efficient training framework for general-purpose mobile GUI agents.
Initial Scores: 4, 8, 4, 2
Confidence: 4, 5, 4, 3
Average Score: 4.5



Title: SWIRL: A Staged Workflow for Interleaved Reinforcement Learning in Mobile GUI Control
TLDR: We present SWIRL, a staged workflow for interleaved reinforcement learning designed for GUI multi-agent systems.
Initial Scores: 4, 4, 2, 6, 2
Confidence: 4, 2, 4, 3, 4
Average Score: 3.6



Title: MemGUI-Bench: Benchmarking Memory of Mobile GUI Agents in Dynamic Environments
TLDR: MemGUI-Bench is the first systematic evaluation of the cross-temporal memory capabilities of mobile GUI agents. Using 128 high-memory-dependency tasks and an 8-layer "progressive review" metric, it reveals a 4–10× performance drop in existing Agents in memory scenarios, establishing a benchmark for building human-like long-term GUI agents.
Initial Scores: 6, 6, 2
Confidence: 4, 3, 4
Average Score: 4.7



Title: VEM: Environment-Free Exploration for Training GUI Agent with Value Environment Model
TLDR: VEM decouples policy optimization from environment interaction using an offline pre-trained Value Environment Model. Relying solely on the semantic valuation of "whether an action advances the goal", it achieves SOTA on both Android and Web platforms, realizing a new paradigm for GUI reinforcement learning with zero interaction cost and robustness across layouts.
Initial Scores: 4, 4, 2, 4
Confidence: 3, 3, 3, 4
Average Score: 3



Title: Hijacking JARVIS: Benchmarking Mobile GUI Agents against Unprivileged Third Parties
TLDR: This study presents the first systematic investigation of mobile GUI agents' vulnerabilities to on-screen content manipulated by untrustworthy third parties.
Initial Scores: 4, 4, 2, 4
Confidence: 4, 2, 3, 3
Average Score: 3.5



Title: WebFactory: Automated Compression of Foundational Language Intelligence into Grounded Web Agents
TLDR: An open-source, fully controllable offline web environment whose built-in site knowledge drives a pipeline to generate executable tasks and high-quality RL data, significantly boosting web-agent performance.
Initial Scores: 6, 4, 6
Confidence: 4, 4, 4
Average Score: 5.3



Title: DKRF: Dynamic Knowledge Reasoning for Out-of-Distribution Generalization in Mobile GUI Agents
TLDR: Instead of just memorizing, our GUI agent learns how to reason with external knowledge to solve tasks in new environments.
Initial Scores: 4, 4, 4, 4
Confidence: 4, 4, 3, 2
Average Score: 4



Title: GUIrilla: A Scalable Framework for Automated Desktop UI Exploration
TLDR: We present GUIrilla, an automated framework for macOS GUI exploration, and GUIrilla-Task, the first large-scale macOS dataset (27,171 tasks, 1,108 apps) pairing GUI screenshots with detailed accessibility metadata.
Initial Scores: 4, 2, 2, 6
Confidence: 3, 4, 4, 4
Average Score: 3.5



Title: LPO: Towards Accurate GUI Agent Interaction via Location Preference Optimization
TLDR: We introduce Location Preference Optimization (LPO), a novel method that enhances GUI interactions by utilizing locational data and information entropy to improve spatial accuracy.
Initial Scores: 4, 4, 4, 6
Confidence: 2, 4, 2, 3
Average Score: 4.5



Title: Automotive-ENV: Benchmarking Multimodal Agents in Vehicle Interface Systems
TLDR: Leveraging GPS context, ASURADA completes 185 safety and intent tasks on the first in-vehicle infotainment (IVI) GUI benchmark, Automotive-ENV, validating the key enhancement of "geo-awareness" for in-vehicle agent decision-making.
Initial Scores: 4, 4, 4, 4
Confidence: 3, 1, 3, 4
Average Score: 4



Title: FingerTip 20K: A Benchmark for Proactive and Personalized Mobile LLM Agents
TLDR: Using 20,000 real long-term user trajectories, FingerTip 20K pioneers dual tracks of "Proactive Suggestion + Personalized Execution", exposing the huge gap between existing GUI agents and humans, and providing data and a benchmark for building user-centric mobile Agents.
Initial Scores: 8, 4, 6, 4
Confidence: 3, 3, 4, 4
Average Score: 5.5



Title: GAMBIT: A Graph-structured and Decision-Aware Benchmark for MoBile GUI Tasks
TLDR: We introduce GAMBIT, a graph-structured benchmark for decision-aware mobile GUI agents, which reveals severe performance drops in long-horizon and branching tasks, providing a challenging diagnostic testbed for future agent development.
Initial Scores: 4, 4, 4, 4
Confidence: 4, 4, 4, 3
Average Score: 4



Title: ReGUIDE: Data Efficient GUI Grounding via Spatial Reasoning and Search
TLDR: Using self-generated reasoning + spatially self-supervised online reinforcement learning, ReGUIDE refreshes the SOTA for web GUI element localization with only 0.2% of the data volume, and achieves low-cost, high-precision grounding through test-time spatial search aggregation.
Initial Scores: 4, 6, 4
Confidence: 4, 3, 5
Average Score: 4.7



Title: Training a Vision-Language Model for Diverse Exploration in Open GUI World
TLDR: ScreenExplorer enables a VLM to autonomously and continuously interact with entirely new applications without any annotations, using dual exploration rewards of "curiosity + state change" and streaming experience distillation. It breaks the dependency on static data, achieving lifelong generalized exploration for GUI agents.
Initial Scores: 6, 2, 4, 4
Confidence: 3, 4, 4, 4
Average Score: 4



Title: GTA1: GUI Test-time Scaling Agent
TLDR: GTA addresses large action space planning through "test-time parallel sampling - critic selection", then refines localization via reinforcement learning, achieving dual SOTA in planning and clicking for cross-platform GUI agents.
Initial Scores: 4, 4, 8, 6
Confidence: 4, 4, 3, 5
Average Score: 5.5



Title: LongHorizonUI: A Unified Framework for Robust long-horizon Task Automation of GUI Agent
TLDR: LongHorizonUI integrates element-indexed multimodal perception, hierarchical reflective decision-making, and rollback-based compensatory execution for long-horizon GUI control.
Initial Scores: 6, 6, 2, 4
Confidence: 5, 3, 4, 3
Average Score: 4.5



Title: ScaleCUA: Scaling Open-Source Computer Use Agents with Cross-Platform Data
TLDR: ScaleCUA open-sources the largest cross-6-system GUI dataset and trains a unified model, refreshing SOTA on three benchmarks with an average increase of +26.6 points, verifying the amplifying effect of "data as compute" for general computer use agents.
Initial Scores: 6, 6, 6, 6
Confidence: 4, 1, 5, 2
Average Score: 6



Title: Generalization in Online Reinforcement Learning for Mobile Agents
TLDR: AndroidWorld-Generalization formalizes the mobile GUI generalization challenge as a CMDP. The accompanying open-source GRPO-RL framework and three-tier benchmark show that a 7B model after RL training improves by 26.1% on unseen instances, but gains across templates/applications are limited, pointing the way for future few-shot online adaptation.
Initial Scores: 4, 2, 6
Confidence: 5, 3, 4
Average Score: 4



Title: PSBench: Editing Image via GUI Agents in Photoshop
TLDR: PSBench introduces the first benchmark of 600-layer non-destructive editing tasks for Photoshop. It reveals that while top MLLMs have low success rates, they can significantly accelerate novice practical operation, setting a new standard for evaluation and assisted design for professional graphics software agents.
Initial Scores: 4, 6, 4
Confidence: 3, 4, 2
Average Score: 4.7



Title: PrecogUI: Proactive GUI Agents via Pre-cognitive Simulation and Experience Retrieval
TLDR: PrecogUI recast GUI agents from reactive to foresight-driven decision-makers that anticipate disturbances and close the loop on errors, yielding state-of-the-art robustness and success on long-horizon, dynamic tasks.
Initial Scores: 6, 4, 2, 4, 4
Confidence: 2, 3, 4, 4, 4
Average Score: 4



Title: Let's Think in Two Steps: Mitigating Agreement Bias in MLLMs with Self-Grounded Verification
TLDR: SGV uses a two-step method of "self-setting standards then judging" to crack the "agreement bias" in MLLM evaluation. It improves performance by an average of 20% across three major tasks (Web, Robotics, GUI) and simultaneously open-sources a 10x accelerated (Visual)WebArena, providing real-time, reliable, and scalable reward signals for digital agents.
Initial Scores: 4, 8, 4, 6
Confidence: 3, 3, 3, 4

Average Score: 5.5
