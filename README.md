### Step-Level Generative Flow Networks (GFlowNets) for Mathematical Reasoning in LLMs

Generative Flow Networks (GFlowNets) are a class of probabilistic models designed to sample diverse and structured outputs proportional to a given reward function. Unlike traditional generative models, GFlowNets operate as flow-based systems, where the probability of generating a specific output is modeled as a flow through a directed acyclic graph. This approach enables GFlowNets to promote diversity in generated solutions while maintaining alignment with the reward signal. For more details, refer to the foundational [GFlowNets paper](https://arxiv.org/abs/2106.04399).

In this work, we adapt GFlowNets to operate at the reasoning step level by leveraging a modified version of the Sub-TB Loss, originally introduced in [Amortizing intractable inference in large language models](https://arxiv.org/abs/2310.04363), which we further adjusted to function in a step-level context rather than a token-level context, aiming to enhance mathematical reasoning in Large Language Models (LLMs). Traditional reinforcement learning methods typically focus on maximizing a single reward signal, which can lead to limited exploration and solution diversity. In contrast, GFlowNets naturally encourage diverse solution strategies while preserving accuracy, making them particularly well-suited for complex reasoning tasks.

This work highlights the potential of GFlowNets as a powerful tool for developing more robust, diverse, and versatile mathematical reasoning capabilities in LLMs, paving the way for future advancements in AI-driven problem-solving.

