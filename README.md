# Awesome-reasoning-safety
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/ybwang119/Awesome-reasoning-safety)
[![Last Commit](https://img.shields.io/github/last-commit/ybwang119/Awesome-reasoning-safety)](https://github.com/ybwang119/Awesome-reasoning-safety)

This repo is for the trustworthy topics in reasoning-related technique, including but not limited to attacks, defenses, studies and benchmarks related to CoT, reasoning and RL. Data are mainly from arxiv. 

## Table of contents
- [Truthfulness](##Truthfulness)
    - [Hallucination](###Hallucination)
    - [Reasoning faithfulness](###Reasoning-faithfulness)
- [Security](##Security)
     - [Jailbreak](###Jailbreak)
     - [Prompt injection](###Prompt-injection)
     - [Backdoor](###Backdoor)
- [Robustness](##Robustness)
     - [Input perturbation](###Input-perturbation)
     - [Overthinking/underthinking](###Overthinking/underthinking)
- [Privacy](##Privacy)
- [Related surveys and benchmarks](##Related-surveys-and-benchmarks)
- [Others](##Other-related-studies)
---
## Truthfulness: Hallucination, reasoning faithfulness

### Hallucination
|  Title  |   Venue  |   Date   |  topic  |   Code   |
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Do Chains-of-Thoughts of Large Language Models Suffer from Hallucinations, Cognitive Biases, or Phobias in Bayesian Reasoning?](https://arxiv.org/abs/2503.15268)|arxiv|03/19, 2025|hallucination|-|
|[Order Matters in Hallucination: Reasoning Order as Benchmark and Reflexive Prompting for Large-Language-Models](https://arxiv.org/abs/2408.05093)|arxiv|12/30, 2024|hallucination|-|
### Reasoning faithfulness
|  Title  |   Venue  |   Date   |  topic  |   Code   |
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Reasoning Models Don’t Always Say What They Think](https://www.anthropic.com/research/reasoning-models-dont-say-think)|arxiv|04/03, 2025|faithfulness|-|
|[Landscape of Thoughts: Visualizing the Reasoning Process of Large Language Models](https://arxiv.org/abs/2503.22165)|arxiv|03/28, 2025|faithfulness|-|
|[Policy Frameworks for Transparent Chain-of-Thought Reasoning in Large Language Models](https://arxiv.org/abs/2503.14521)|arxiv|03/14, 2025|faithfulness|-|
|[Monitoring Reasoning Models for Misbehavior and the Risks of Promoting Obfuscation](https://arxiv.org/abs/2503.11926)|arxiv|03/14, 2025|faithfulness|-|
|[Chain-of-Thought Reasoning In The Wild Is Not Always Faithful](https://arxiv.org/abs/2503.08679)|arxiv|03/13, 2025|faithfulness|-|
|[Are DeepSeek R1 And Other Reasoning Models More Faithful?](https://arxiv.org/abs/2501.08156)|arxiv|02/20, 2025|faithfulness|-|
|[How Likely Do LLMs with CoT Mimic Human Reasoning?](https://arxiv.org/abs/2402.16048)|arxiv|12/12, 2024|faithfulness|-|
|[On the Impact of Fine-Tuning on Chain-of-Thought Reasoning](https://arxiv.org/abs/2411.15382)|arxiv|11/22, 2024|faithfulness|-|
|[Language Models Don’t Always Say What They Think: Unfaithful Explanations in Chain-of-Thought Prompting](https://arxiv.org/abs/2305.04388)|arxiv|12/09, 2023|faithfulness|-|
|[Measuring Faithfulness in Chain-of-Thought Reasoning](https://arxiv.org/abs/2307.13702)|arxiv|07/17, 2023|faithfulness|-|

## Security: Jailbreak, prompt injection, backdoor
### Jailbreak
|  Title  |   Venue  |   Date   |  topic  |   Code   |
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[LlamaFirewall: An open source guardrail system for building secure AI agents](https://arxiv.org/abs/2505.03574)|arxiv|05/06, 2025|jailbreak defense|-|
|[MR. Guard: Multilingual Reasoning Guardrail using Curriculum Learning](https://arxiv.org/abs/2504.15241)|arxiv|04/21, 2025|jailbreak defense|-|
|[Energy-Based Reward Models for Robust Language Model Alignment](https://arxiv.org/abs/2504.13134)|arxiv|04/17, 2025|reward model|-|
|[VLMGuard-R1: Proactive Safety Alignment for VLMs via Reasoning-Driven Prompt Optimization](https://arxiv.org/abs/2504.12661)|arxiv|04/17, 2025|multi-modal alignment|-|
|[RealSafe-R1: Safety-Aligned DeepSeek-R1 without Compromising Reasoning Capability](https://arxiv.org/abs/2504.10081)|arxiv|04/14, 2025|alignment|-|
|[SaRO: Enhancing LLM Safety through Reasoning-based Alignment](https://arxiv.org/abs/2504.09420)|arxiv|04/13, 2025|alignment|-|
|[SafeMLRM: Demystifying Safety in Multi-modal Large Reasoning Models](https://arxiv.org/abs/2504.08813)|arxiv|04/09, 2025|multi-modal alignment|-|
|[ERPO: Advancing Safety Alignment via Ex-Ante Reasoning Preference Optimization](https://arxiv.org/abs/2504.02725)|arxiv|04/06, 2025|alignment|-|
|[STAR-1: Safer Alignment of Reasoning LLMs with 1K Data](https://arxiv.org/abs/2504.01903)|arxiv|04/02, 2025|alignment|-|
|[SRMIR: Shadow Reward Models Based on Introspective Reasoning for LLM Alignment](https://arxiv.org/abs/2503.18991)|arxiv|03/23, 2025|reward model|-|
|[Safe RLHF-V: Safe Reinforcement Learning from Human Feedback in Multimodal Large Language Models](https://arxiv.org/abs/2503.17682)|arxiv|03/22, 2025|multi-modal alignment|-|
|[Towards Understanding the Safety Boundaries of DeepSeek Models: Evaluation and Findings](https://arxiv.org/abs/2503.15092)|arxiv|03/19, 2025|jailbreak evaluation|-|
|[Safety Evaluation and Enhancement of DeepSeek Models in Chinese Contexts](https://arxiv.org/abs/2503.16529)|arxiv|03/18, 2025|jailbreak evaluation|-|
|[Red Teaming Contemporary AI Models: Insights from Spanish and Basque Perspectives](https://arxiv.org/abs/2503.10192)|arxiv|03/13, 2025|jailbreak evaluation|-|
|[Reasoning-Augmented Conversation for Multi-Turn Jailbreak Attacks on Large Language Models](https://arxiv.org/abs/2502.11054)|arxiv|03/11, 2025|jailbreak with CoT|-|
|[Safety is Not Only About Refusal: Reasoning-Enhanced Fine-tuning for Interpretable LLM Safety](https://arxiv.org/abs/2503.05021)|arxiv|03/06, 2025|alignment|-|
|[Safety Tax: Safety Alignment Makes Your Large Reasoning Models Less Reasonable](https://arxiv.org/abs/2503.00555)|arxiv|03/01, 2025|alignment|-|
|[The Hidden Risks of Large Reasoning Models: A Safety Assessment of R1](https://arxiv.org/abs/2502.12659v3)|arxiv|02/27, 2025|jailbreak evaluation|-|
|[Evaluating security risk in deepseek and other frontier reasoning models](https://blogs.cisco.com/security/evaluating-security-risk-in-deepseek-and-other-frontier-reasoning-models)|website|02/26, 2025|jailbreak evaluation|-|
|[Are Smarter LLMs Safer? Exploring Safety-Reasoning Trade-offs in Prompting and Fine-Tuning](https://arxiv.org/abs/2502.09673)|arxiv|02/21, 2025|jailbreak evaluation|-|
|[A Mousetrap: Fooling Large Reasoning Models for Jailbreak with Chain of Iterative Chaos](https://arxiv.org/abs/2502.15806)|arxiv|02/19, 2025|jailbreak attack|-|
|[Reasoning-to-Defend: Safety-Aware Reasoning Can Defend Large Language Models from Jailbreaking](https://arxiv.org/html/2502.12970v1)|arxiv|02/18, 2025|jailbreak defense|-|
|[H-CoT: Hijacking the Chain-of-Thought Safety Reasoning Mechanism to Jailbreak Large Reasoning Models, Including OpenAI o1/o3, DeepSeek-R1, and Gemini 2.0 Flash Thinking](https://arxiv.org/abs/2502.12893v1)|arxiv|02/18, 2025|jailbreak attack|-|
|[Safechain: Safety of language models with long chain-of-thought reasoning capabilities](https://arxiv.org/abs/2502.12025)|arxiv|02/17, 2025|alignment|-|
|[STAIR: Improving Safety Alignment with Introspective Reasoning](https://arxiv.org/abs/2502.02384)|arxiv|02/04, 2025|alignment|-|
|[Adversarial Reasoning at Jailbreaking Time](https://arxiv.org/abs/2502.01633)|arxiv|02/03, 2025|Jailbreak with CoT|-|
|[The dark deep side of DeepSeek: Fine-tuning attacks against the safety alignment of CoT-enabled models](https://arxiv.org/abs/2502.01225)|arxiv|02/03, 2025|finetuning attack|-|
|[GuardReasoner: Towards Reasoning-based LLM Safeguards](https://arxiv.org/abs/2501.18492)|arxiv|01/30, 2025|defense|-|
|[Alignment faking in large language models](https://arxiv.org/abs/2412.14093)|arxiv|12/19, 2024|alignment|-|
|[Enhancing Adversarial Attacks through Chain of Thought](https://arxiv.org/abs/2410.21791)|arxiv|10/29, 2024|Jailbreak with CoT|-|
### Prompt injection
|  Title  |   Venue  |   Date   |  topic  |   Code   |
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Token-Efficient Prompt Injection Attack: Provoking Cessation in LLM Reasoning via Adaptive Token Compression](https://arxiv.org/abs/2504.20493)|arxiv|04/29, 2025|prompt injection attack|-|
|[Harnessing Chain-of-Thought Metadata for Task Routing and Adversarial Prompt Detection](https://arxiv.org/abs/2503.21464)|arxiv|03/27, 2025|prompt injection defense|-|
### Backdoor
|  Title  |   Venue  |   Date   |  topic  |   Code   |
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[BoT: Breaking Long Thought Processes of o1-like Large Language Models through Backdoor Attack](https://arxiv.org/abs/2502.12202)|arxiv|02/16, 2025|backdoor attack|-|
|[Chain-of-Scrutiny: Detecting Backdoor Attacks for Large Language Models](https://arxiv.org/abs/2406.05948)|arxiv|12/20, 2024|backdoor defense|-|
|[BadChain: Backdoor Chain-of-Thought Prompting for Large Language Models](https://arxiv.org/abs/2401.12242)|arxiv|01/20, 2024|backdoor attack|-| 
## Robustness: input perturbation, overthinking/underthinking
### Input perturbation
|  Title  |   Venue  |   Date   |  topic  |   Code   |
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Chain-of-Defensive-Thought: Structured Reasoning Elicits Robustness in Large Language Models against Reference Corruption](https://arxiv.org/abs/2504.20769)|04/29, 2025|arxiv|adversarial defense|-|
|[Assessing Judging Bias in Large Reasoning Models: An Empirical Study](https://arxiv.org/abs/2504.09946)|arxiv|04/18, 2025|bias|-|
|[Recitation over Reasoning: How Cutting-Edge Language Models Can Fail on Elementary School-Level Reasoning Problems?](https://arxiv.org/abs/2504.00509)|arxiv|04/01, 2025|recitation|-|
|[A Frustratingly Simple Yet Highly Effective Attack Baseline: Over 90% Success Rate Against the Strong Black-box Models of GPT-4.5/4o/o1](https://arxiv.org/abs/2503.10635)|arxiv|03/13, 2025|adversarial attack|-|
|[Benchmarking Reasoning Robustness in Large Language Models](https://arxiv.org/abs/2503.04550)|arxiv|03/06, 2025|evaluation|-|
|[Cats Confuse Reasoning LLM: Query Agnostic Adversarial Triggers for Reasoning Models](https://arxiv.org/abs/2503.01781)|arxiv|03/03, 2025|adversarial attack|-|
|[A Closer Look at System Prompt Robustness](https://arxiv.org/abs/2502.12197)|arxiv|02/15, 2025|system prompt robustness|-|
|[Trading Inference-Time Compute for Adversarial Robustness](https://arxiv.org/abs/2501.18841)|arxiv|01/31, 2025|input perturbation|-|
|[Can Language Models Perform Robust Reasoning in Chain-of-thought Prompting with Noisy Rationales?](https://arxiv.org/abs/2410.23856)|arxiv|10/31, 2024|input perturbation|-|
### Overthinking/underthinking
|  Title  |   Venue  |   Date   |  topic  |   Code   |
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[TRACE Back from the Future: A Probabilistic Reasoning Approach to Controllable Language Generation](https://arxiv.org/abs/2504.18535)|arxiv|04/28, 2025|thought control|-|
|[Steering the CensorShip: Uncovering Representation Vectors for LLM "Thought" Control](https://arxiv.org/abs/2504.17130)|arxiv|04/23, 2025|thought control|-|
|[Missing Premise exacerbates Overthinking: Are Reasoning Models losing Critical](https://arxiv.org/abs/2504.06514)|arxiv|04/11, 2025|overthing|-|
|[Trade-offs in Large Reasoning Models: An Empirical Analysis of Deliberative and Adaptive Reasoning over Foundational Capabilities](https://arxiv.org/abs/2503.17979)|arxiv|03/23, 2025|reasoning length analysis|-|
|[DNA Bench: When Silence is Smarter -- Benchmarking Over-Reasoning in Reasoning LLMs](https://arxiv.org/abs/2503.15793)|arxiv|03/19, 2025|overthinking evaluation|-|
|[Output Length Effect on DeepSeek-R1's Safety in Forced Thinking](https://arxiv.org/abs/2503.01923)|arxiv|03/02, 2025|length analysis|-|
|[Can Large Language Models Detect Errors in Long Chain-of-Thought Reasoning?](https://arxiv.org/abs/2502.19361)|arxiv|02/27, 2025|self reflection|-|
|[The Danger of Overthinking: Examining the Reasoning-Action Dilemma in Agentic Tasks](https://arxiv.org/abs/2502.08235)|arxiv|02/12, 2025|overthinking risk|-|
|[Understanding the Dark Side of LLMs' Intrinsic Self-Correction](https://arxiv.org/abs/2412.14959)|arxiv|12/19, 2024|self reflection|-|
## Privacy
|  Title  |   Venue  |   Date   |  topic  |   Code   |
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Doxing via the Lens: Revealing Privacy Leakage in Image Geolocation for Agentic Multi-Modal Large Reasoning Model](https://arxiv.org/abs/2504.19373)|arxiv|04/29, 2025|privacy leakage|-|
|[Antidistillation Sampling](https://arxiv.org/abs/2504.13146)|arxiv|04/17, 2025|model distillation defense|-|
## Related surveys and benchmarks
|  Title  |   Venue  |   Date   |  topic  |   Code   |
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[100 Days After DeepSeek-R1: A Survey on Replication Studies and More Directions for Reasoning Language Models](https://arxiv.org/abs/2505.00551)|arxiv|05/02, 2025|r1 replication|-|
|[PolyMath: Evaluating Mathematical Reasoning in Multilingual Contexts](https://arxiv.org/abs/2504.18428)|arxiv|04/28, 2025|multilingual math performance|-|
|[Safety in Large Reasoning Models: A Survey](https://arxiv.org/abs/2504.17704)|arxiv|04/25, 2025|safety|-|
|[Harnessing the Reasoning Economy: A Survey of Efficient Reasoning for Large Language Models](https://arxiv.org/abs/2503.24377)|arxiv|03/31, 2025|efficient reasoning|-|
|[Challenging the Boundaries of Reasoning: An Olympiad-Level Math Benchmark for Large Language Models](https://arxiv.org/abs/2503.21380)|arxiv|03/28, 2025|math performance|-|

## Other related studies
[Understanding LLM Scientific Reasoning through Promptings and Model's Explanation on the Answers](https://arxiv.org/abs/2505.01482) (05/01, 2025)

[Moral Reasoning Across Languages: The Critical Role of Low-Resource Languages in LLMs](https://arxiv.org/abs/2504.19759) (04/28, 2025)

[How Effective Is Constitutional AI in Small LLMs? A Study on DeepSeek-R1 and Its Peers](https://arxiv.org/abs/2503.17365) (02/01, 2025)

[Building Trustworthy AI: Transparent AI Systems via Large Language Models, Ontologies, and Logical Reasoning (TranspNet)](https://arxiv.org/abs/2411.08469) (12/18, 2024)

[Anchoring Bias in Large Language Models: An Experimental Study](https://arxiv.org/abs/2412.06593) (12/18, 2024)

[Alignment faking in large language models](https://arxiv.org/abs/2412.14093) (12/19, 2024)

[Answer, Refuse, or Guess? Investigating Risk-Aware Decision Making in Language Models](https://arxiv.org/abs/2503.01332) (03/03, 2025)

[Safety Guardrails for LLM-Enabled Robots](https://arxiv.org/abs/2503.07885) (03/10, 2025)

[Towards Efficient and Explainable Hate Speech Detection via Model Distillation](https://arxiv.org/abs/2412.13698) (12/18, 2024)

[Causal Prompting: Debiasing Large Language Model Prompting based on Front-Door Adjustment](https://arxiv.org/abs/2403.02738) (12/17, 2024)

[Collab: Controlled Decoding using Mixture of Agents for LLM Alignment](https://arxiv.org/abs/2503.21720) (03/27, 2025)

[AgentSpec: Customizable Runtime Enforcement for Safe and Reliable LLM Agents](https://arxiv.org/abs/2503.18666) (03/24, 2025)

[Modular Machine Learning: An Indispensable Path towards New-Generation Large Language Models](https://arxiv.org/abs/2504.20020) (04/29, 2025)

[AegisLLM: Scaling Agentic Systems for Self-Reflective Defense in LLM Security](https://arxiv.org/abs/2504.20965) (04/29, 2025)

[Don't Take Things Out of Context: Attention Intervention for Enhancing Chain-of-Thought Reasoning in Large Language Models](https://arxiv.org/abs/2503.11154) (03/14, 2025)

[Stepwise Reasoning Error Disruption Attack of LLMs](https://arxiv.org/abs/2412.11934) (03/10, 2025)

[Preemptive Answer "Attacks" on Chain-of-Thought Reasoning](https://arxiv.org/abs/2405.20902) (05/31, 2024)

[The Steganographic Potentials of Language Models](https://arxiv.org/abs/2505.03439) (05/06, 2025)
