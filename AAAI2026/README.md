# **<center >AAAI 2026 Paper List</center>**

# **Benchmark**
1. **<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">D-GARA: A Dynamic Benchmarking Framework for GUI Agent Robustness in Real-World Anomalies</font>**

**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Abstract: </font>**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Developing intelligent agents capable of operating a wide range of Graphical User Interfaces (GUIs) with human-level proficiency is a key milestone on the path toward Artificial General Intelligence. While most existing datasets and benchmarks for training and evaluating GUI agents are static and idealized, failing to reflect the complexity and unpredictability of real-world environments, particularly the presence of anomalies. To bridge this research gap, we propose D-GARA, a dynamic benchmarking framework, to evaluate Android GUI agent robustness in real-world anomalies. D-GARA introduces a diverse set of real-world anomalies that GUI agents commonly face in practice, including interruptions such as permission dialogs, battery warnings, and update prompts. Based on D-GARA framework, we construct and annotate a benchmark featuring commonly used Android applications with embedded anomalies to support broader community research. Comprehensive experiments and results demonstrate substantial performance degradation in state-of-the-art GUI agents when exposed to anomaly-rich environments, highlighting the need for robustness-aware learning. D-GARA is modular and extensible, supporting the seamless integration of new tasks, anomaly types, and interaction scenarios to meet specific evaluation goals.


<div style="text-align: center;">
<img src="figures\Bench1.png"  width="60%" >
</div>

2. **<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">ProBench: Benchmarking GUI Agents with Accurate Process Information</font>**

**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Abstract: </font>**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">With the deep integration of artificial intelligence and interactive technology, Graphical User Interface (GUI) Agent, as the carrier connecting goal-oriented natural language and real-world devices, has received widespread attention from the community. Contemporary benchmarks aim to evaluate the comprehensive capabilities of GUI agents in GUI operation tasks, generally determining task completion solely by inspecting the final screen state. However, GUI operation tasks consist of multiple chained steps while not all critical information is presented in the final few pages. Although a few research has begun to incorporate intermediate steps into evaluation, accurately and automatically capturing this process information still remains an open challenge. To address this weakness, we introduce ProBench, a comprehensive mobile benchmark with over 200 challenging GUI tasks covering widely-used scenarios. Remaining the traditional State-related Task evaluation, we extend our dataset to include Process-related Task and design a specialized evaluation method. A newly introduced Process Provider automatically supplies accurate process information, enabling presice assessment of agent's performance. Our evaluation of advanced GUI agents reveals significant limitations for real-world GUI scenarios. These shortcomings are prevalent across diverse models, including both large-scale generalist models and smaller, GUI-specific models. A detailed error analysis further exposes several universal problems, outlining concrete directions for future improvements.


<div style="text-align: center;">
<img src="figures\Bench2.png"  width="60%" >
</div>

3. **<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Mind the Third Eye! Benchmarking Privacy Awareness in MLLM-powered Smartphone Agents</font>**

**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Abstract: </font>**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">With the deep integration of artificial intelligence and interactive technology, Graphical User Interface (GUI) Agent, as the carrier connecting goal-oriented natural language and real-world devices, has received widespread attention from the community. Contemporary benchmarks aim to evaluate the comprehensive capabilities of GUI agents in GUI operation tasks, generally determining task completion solely by inspecting the final screen state. However, GUI operation tasks consist of multiple chained steps while not all critical information is presented in the final few pages. Although a few research has begun to incorporate intermediate steps into evaluation, accurately and automatically capturing this process information still remains an open challenge. To address this weakness, we introduce ProBench, a comprehensive mobile benchmark with over 200 challenging GUI tasks covering widely-used scenarios. Remaining the traditional State-related Task evaluation, we extend our dataset to include Process-related Task and design a specialized evaluation method. A newly introduced Process Provider automatically supplies accurate process information, enabling presice assessment of agent's performance. Our evaluation of advanced GUI agents reveals significant limitations for real-world GUI scenarios. These shortcomings are prevalent across diverse models, including both large-scale generalist models and smaller, GUI-specific models. A detailed error analysis further exposes several universal problems, outlining concrete directions for future improvements.


<div style="text-align: center;">
<img src="figures\Bench3.png"  width="60%" >
</div>

# **Grounding & RL**
1. **UI-R1: Enhancing Efficient Action Prediction of GUI Agents by Reinforcement Learning**

**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Abstract: </font>**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);"> The recent DeepSeek-R1 has showcased the emergence of reasoning capabilities in LLMs through reinforcement learning (RL) with rule-based rewards. Despite its success in language models, its application in multi-modal domains, particularly in graphic user interface (GUI) agent tasks, remains under-explored. To address this issue, we propose UI-R1, the first framework to explore how rule-based RL can enhance the reasoning capabilities of multimodal large language models (MLLMs) for GUI action prediction tasks. Specifically, UI-R1 introduces a novel rule-based action reward, enabling model optimization via policy-based algorithms such as Group Relative Policy Optimization (GRPO). For efficient training, we curate a small yet high-quality dataset of 136 challenging tasks, encompassing five common action types on mobile devices. Experimental results demonstrate that our proposed UI-R1-3B achieves significant improvements over the base model (i.e. Qwen2.5-VL-3B) on both in-domain (ID) and out-of-domain (OOD) tasks, with average accuracy gains of 22.1% on ScreenSpot, 6.0% on ScreenSpot-Pro, and 12.7% on ANDROIDCONTROL. Furthermore, UI-R1-3B delivers competitive performance compared to larger models (e.g., OS-Atlas-7B) trained via supervised fine-tuning (SFT) on 76K samples. We additionally develop an optimized version, UI-R1-E-3B, which significantly improves both grounding efficiency and accuracy. These results underscore the potential of rule-based reinforcement learning to advance GUI understanding and control, paving the way for future research in this domain. 


<div style="text-align: center;">
<img src="figures\RL1.png"  width="60%" >
</div>

2. **History-Aware Reasoning for GUI Agents**

**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Abstract: </font>**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);"> Advances in Multimodal Large Language Models have significantly enhanced Graphical User Interface (GUI) automation. Equipping GUI agents with reliable episodic reasoning capabilities is essential for bridging the gap between users' concise task descriptions and the complexities of real-world execution. Current methods integrate Reinforcement Learning (RL) with System-2 Chain-of-Thought, yielding notable gains in reasoning enhancement. For long-horizon GUI tasks, historical interactions connect each screen to the goal-oriented episode chain, and effectively leveraging these clues is crucial for the current decision. However, existing native GUI agents exhibit weak short-term memory in their explicit reasoning, interpreting the chained interactions as discrete screen understanding, i.e., unawareness of the historical interactions within the episode. This history-agnostic reasoning challenges their performance in GUI automation. To alleviate this weakness, we propose a History-Aware Reasoning (HAR) framework, which encourages an agent to reflect on its own errors and acquire episodic reasoning knowledge from them via tailored strategies that enhance short-term memory in long-horizon interaction. The framework mainly comprises constructing a reflective learning scenario, synthesizing tailored correction guidelines, and designing a hybrid RL reward function. Using the HAR framework, we develop a native end-to-end model, HAR-GUI-3B, which alters the inherent reasoning mode from history-agnostic to history-aware, equipping the GUI agent with stable short-term memory and reliable perception of screen details. Comprehensive evaluations across a range of GUI-related benchmarks demonstrate the effectiveness and generalization of our method.


<div style="text-align: center;">
<img src="figures\RL2.png"  width="60%" >
</div>

3. **InfiGUI-G1: Advancing GUI Grounding with Adaptive Exploration Policy Optimization**

**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Abstract: </font>**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);"> The emergence of Multimodal Large Language Models (MLLMs) has propelled the development of autonomous agents that operate on Graphical User Interfaces (GUIs) using pure visual input. A fundamental challenge is robustly grounding natural language instructions. This requires a precise spatial alignment, which accurately locates the coordinates of each element, and, more critically, a correct semantic alignment, which matches the instructions to the functionally appropriate UI element. Although Reinforcement Learning with Verifiable Rewards (RLVR) has proven to be effective at improving spatial alignment for these MLLMs, we find that inefficient exploration bottlenecks semantic alignment, which prevent models from learning difficult semantic associations. To address this exploration problem, we present Adaptive Exploration Policy Optimization (AEPO), a new policy optimization framework. AEPO employs a multi-answer generation strategy to enforce broader exploration, which is then guided by a theoretically grounded Adaptive Exploration Reward (AER) function derived from first principles of efficiency eta=U/C. Our AEPO-trained models, InfiGUI-G1-3B and InfiGUI-G1-7B, establish new state-of-the-art results across multiple challenging GUI grounding benchmarks, achieving significant relative improvements of up to 9.0% against the naive RLVR baseline on benchmarks designed to test generalization and semantic understanding.


<div style="text-align: center;">
<img src="figures\RL3.png"  width="60%" >
</div>


4. **GUI-G2: Gaussian Reward Modeling for GUI Grounding**

**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Abstract: </font>**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);"> Graphical User Interface (GUI) grounding maps natural language instructions to precise interface locations for autonomous interaction. Current reinforcement learning approaches use binary rewards that treat elements as hit-or-miss targets, creating sparse signals that ignore the continuous nature of spatial interactions. Motivated by human clicking behavior that naturally forms Gaussian distributions centered on target elements, we introduce GUI Gaussian Grounding Rewards (GUI-G^2), a principled reward framework that models GUI elements as continuous Gaussian distributions across the interface plane. GUI-G^2 incorporates two synergistic mechanisms: Gaussian point rewards model precise localization through exponentially decaying distributions centered on element centroids, while coverage rewards assess spatial alignment by measuring the overlap between predicted Gaussian distributions and target regions. To handle diverse element scales, we develop an adaptive variance mechanism that calibrates reward distributions based on element dimensions. This framework transforms GUI grounding from sparse binary classification to dense continuous optimization, where Gaussian distributions generate rich gradient signals that guide models toward optimal interaction positions. Extensive experiments across ScreenSpot, ScreenSpot-v2, and ScreenSpot-Pro benchmarks demonstrate that GUI-G^2, substantially outperforms state-of-the-art method UI-TARS-72B, with the most significant improvement of 24.7% on ScreenSpot-Pro. Our analysis reveals that continuous modeling provides superior robustness to interface variations and enhanced generalization to unseen layouts, establishing a new paradigm for spatial reasoning in GUI interaction tasks.


<div style="text-align: center;">
<img src="figures\RL4.png"  width="60%" >
</div>

5. **GUI-Eyes: Tool-Augmented Perception for Visual Grounding in GUI Agents**




6. **FDC-Ground: Improving GRPO for GUI Grounding via Exponential Rewards and Fact-Aligned Pruning**






# **Test-time Scaling**
1. **<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Test-Time Reinforcement Learning for GUI Grounding via Region Consistency</font>**

**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Abstract: </font>**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Graphical User Interface (GUI) grounding, the task of mapping natural language instructions to precise screen coordinates, is fundamental to autonomous GUI agents. While existing methods achieve strong performance through extensive supervised training or reinforcement learning with labeled rewards, they remain constrained by the cost and availability of pixel-level annotations. We observe that when models generate multiple predictions for the same GUI element, the spatial overlap patterns reveal implicit confidence signals that can guide more accurate localization. Leveraging this insight, we propose GUI-RC (Region Consistency), a test-time scaling method that constructs spatial voting grids from multiple sampled predictions to identify consensus regions where models show highest agreement. Without any training, GUI-RC improves accuracy by 2-3% across various architectures on ScreenSpot benchmarks. We further introduce GUI-RCPO (Region Consistency Policy Optimization), transforming these consistency patterns into rewards for test-time reinforcement learning. By computing how well each prediction aligns with the collective consensus, GUI-RCPO enables models to iteratively refine their outputs on unlabeled data during inference. Extensive experiments demonstrate the generality of our approach: using only 1,272 unlabeled data, GUI-RCPO achieves 3-6% accuracy improvements across various architectures on ScreenSpot benchmarks. Our approach reveals the untapped potential of test-time scaling and test-time reinforcement learning for GUI grounding, offering a promising path toward more data-efficient GUI agents.


<div style="text-align: center;">
<img src="figures\Test-time.png"  width="60%" >
</div>

# **Training Framework**
1. **<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Co-EPG: A Framework for Co-Evolution of Planning and Grounding in Autonomous GUI Agents</font>**

**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Abstract: </font>**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Graphical User Interface (GUI) task automation constitutes a critical frontier in artificial intelligence research. While effective GUI agents synergistically integrate planning and grounding capabilities, current methodologies exhibit two fundamental limitations: (1) insufficient exploitation of cross-model synergies, and (2) over-reliance on synthetic data generation without sufficient utilization. To address these challenges, we propose Co-EPG, a self-iterative training framework for Co-Evolution of Planning and Grounding. Co-EPG establishes an iterative positive feedback loop: through this loop, the planning model explores superior strategies under grounding-based reward guidance via Group Relative Policy Optimization (GRPO), generating diverse data to optimize the grounding model. Concurrently, the optimized Grounding model provides more effective rewards for subsequent GRPO training of the planning model, fostering continuous improvement. Co-EPG thus enables iterative enhancement of agent capabilities through self-play optimization and training data distillation. On the Multimodal-Mind2Web and AndroidControl benchmarks, our framework outperforms existing state-of-the-art methods after just three iterations without requiring external data. The agent consistently improves with each iteration, demonstrating robust self-enhancement capabilities. This work establishes a novel training paradigm for GUI agents, shifting from isolated optimization to an integrated, self-driven co-evolution approach.</font>


<div style="text-align: center;">
<img src="figures\Framework1.png"  width="60%" >
</div>

# **Robustness**
1. **<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">GEM: Gaussian Embedding Modeling for Out-of Distribution Detection in GUI Agents</font>**

**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Abstract: </font>**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Graphical user interface (GUI) agents have recently emerged as an intriguing paradigm for human-computer interaction, capable of automatically executing user instructions to operate intelligent terminal devices. However, when encountering out-of-distribution (OOD) instructions that violate environmental constraints or exceed the current capabilities of agents, GUI agents may suffer task breakdowns or even pose security threats. Therefore, effective OOD detection for GUI agents is essential. Traditional OOD detection methods perform suboptimally in this domain due to the complex embedding space and evolving GUI environments. In this work, we observe that the in-distribution input semantic space of GUI agents exhibits a clustering pattern with respect to the distance from the centroid. Based on the finding, we propose GEM, a novel method based on fitting a Gaussian mixture model over input embedding distances extracted from the GUI agent that reflect its capability boundary. Evaluated on eight datasets spanning smartphones, computers, and web browsers, our method achieves an average accuracy improvement of 23.70\% over the best-performing baseline while only increasing training time by 4.9\% and testing time by 6.5\%. We also experimentally demonstrate that GEM can improve the step-wise success rate by 9.40\% by requesting assistance from the cloud model when encountering OOD samples. Analysis verifies the generalization ability of our method through experiments on nine different backbones. 


<div style="text-align: center;">
<img src="figures\Robustness1.png"  width="60%" >
</div>

# **Data Collection**
1. **<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">TongUI: Internet-Scale Trajectories from Multimodal Web Tutorials for Generalized GUI Agents</font>**

**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Abstract: </font>**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Building Graphical User Interface (GUI) agents is a promising research direction, which simulates human interaction with computers or mobile phones to perform diverse GUI tasks. However, a major challenge in developing generalized GUI agents is the lack of sufficient trajectory data across various operating systems and applications, mainly due to the high cost of manual annotations. In this paper, we propose the TongUI framework that builds generalized GUI agents by learning from rich multimodal web tutorials. Concretely, we crawl and process online GUI tutorials (such as videos and articles) into GUI agent trajectory data, through which we produce the GUI-Net dataset containing 143K trajectory data across five operating systems and more than 200 applications. We develop the TongUI agent by fine-tuning Qwen2.5-VL-3B/7B models on GUI-Net, which show remarkable performance improvements on commonly used grounding and navigation benchmarks, outperforming baseline agents about 10\% on multiple benchmarks, showing the effectiveness of the GUI-Net dataset and underscoring the significance of our TongUI framework. We will fully open-source the code, the GUI-Net dataset, and the trained models soon.


<div style="text-align: center;">
<img src="figures\Data1.png"  width="60%" >
</div>

# **Multi-Agent**
1. **<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Mobile-Agent-RAG: Driving Smart Multi-Agent Coordination with Contextual Knowledge Empowerment for Long-Horizon Mobile Automation</font>**

**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Abstract: </font>**<font style="color:rgb(44, 58, 74);background-color:rgb(255, 253, 250);">Mobile agents show immense potential, yet current state-of-the-art (SoTA) agents exhibit inadequate success rates on real-world, long-horizon, cross-application tasks. We attribute this bottleneck to the agents' excessive reliance on static, internal knowledge within MLLMs, which leads to two critical failure points: 1) strategic hallucinations in high-level planning and 2) operational errors during low-level execution on user interfaces (UI). The core insight of this paper is that high-level planning and low-level UI operations require fundamentally distinct types of knowledge. Planning demands high-level, strategy-oriented experiences, whereas operations necessitate low-level, precise instructions closely tied to specific app UIs. Motivated by these insights, we propose Mobile-Agent-RAG, a novel hierarchical multi-agent framework that innovatively integrates dual-level retrieval augmentation. At the planning stage, we introduce Manager-RAG to reduce strategic hallucinations by retrieving human-validated comprehensive task plans that provide high-level guidance. At the execution stage, we develop Operator-RAG to improve execution accuracy by retrieving the most precise low-level guidance for accurate atomic actions, aligned with the current app and subtask. To accurately deliver these knowledge types, we construct two specialized retrieval-oriented knowledge bases. Furthermore, we introduce Mobile-Eval-RAG, a challenging benchmark for evaluating such agents on realistic multi-app, long-horizon tasks. Extensive experiments demonstrate that Mobile-Agent-RAG significantly outperforms SoTA baselines, improving task completion rate by 11.0% and step efficiency by 10.2%, establishing a robust paradigm for context-aware, reliable multi-agent mobile automation.


<div style="text-align: center;">
<img src="figures\Multiagent1.png"  width="60%" >
</div>