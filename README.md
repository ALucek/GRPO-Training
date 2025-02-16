# Unlocking Reasoning with Group Relative Policy Optimization (GRPO)

<img src="https://i0.wp.com/chatgptfrancais.org/wp-content/uploads/2025/02/open-ai-o3-mini.jpg?resize=900%2C506&ssl=1" width=600>

DeepSeek-R1 has disrupted the AI community by providing a competitive, comparable, and completely open sourced alternative to OpenAI's original reasoning models. Before the DeepSeek team released their report, the methods and techniques used to enable long reflective **reasoning** capabilities in language models have been largely speculative.

While it's still not clear exactly how the private labs like OpenAI have achieved their own reasoning, DeepSeek fully outlines their technique in the paper [*DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via
Reinforcement Learning*](https://arxiv.org/pdf/2501.12948).

Within the paper they outline the entire training pipeline for [DeepSeek-R1](https://huggingface.co/deepseek-ai/DeepSeek-R1) along with their breakthrough using a new reinforcement learning technique, Group Relative Policy Optimization (GRPO), originally outlined in [*DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models*](https://arxiv.org/pdf/2402.03300).

In this notebook we'll be show how GRPO is applied by covering:
1. How the Algorithm Works
2. The DeepSeek-R1 Training Pipeline
3. Applying GRPO Training Ourselves to Qwen-2.5-3B-Instruct
