# Awesome-reasoning-safety
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/ybwang119/Awesome-reasoning-safety)
[![Last Commit](https://img.shields.io/github/last-commit/ybwang119/Awesome-reasoning-safety)](https://github.com/ybwang119/Awesome-reasoning-safety)

This repo is for the safety/robustness topic, including attacks, defenses and studies related to reasoning and RL. Data are mainly from arxiv.
## Attacks

[Don't Take Things Out of Context: Attention Intervention for Enhancing Chain-of-Thought Reasoning in Large Language Models](https://arxiv.org/abs/2503.11154) (03/14, 2025)

[A Frustratingly Simple Yet Highly Effective Attack Baseline: Over 90% Success Rate Against the Strong Black-box Models of GPT-4.5/4o/o1](https://arxiv.org/abs/2503.10635) (03/13, 2025) (adversarial attack/pixel manipulation 对于多模态大模型仍然有效)

[Stepwise Reasoning Error Disruption Attack of LLMs](https://arxiv.org/abs/2412.11934) (03/10, 2025)

[Cats Confuse Reasoning LLM: Query Agnostic Adversarial Triggers for Reasoning Models](https://arxiv.org/abs/2503.01781) (03/03, 2025) (添加有意义的多余句可以误导r1/distill模型产生错误结果)

[Output Length Effect on DeepSeek-R1's Safety in Forced Thinking](https://arxiv.org/abs/2503.01923) (03/02, 2025)

[A Mousetrap: Fooling Large Reasoning Models for Jailbreak with Chain of Iterative Chaos](https://arxiv.org/abs/2502.15806) (02/19, 2025) (添加更多的步骤让模型先思考真正的prompt再回答)

[H-CoT: Hijacking the Chain-of-Thought Safety Reasoning Mechanism to Jailbreak Large Reasoning Models, Including OpenAI o1/o3, DeepSeek-R1, and Gemini 2.0 Flash Thinking](https://arxiv.org/abs/2502.12893v1) (02/18, 2025)

[BoT: Breaking Long Thought Processes of o1-like Large Language Models through Backdoor Attack](https://arxiv.org/abs/2502.12202) (02/16, 2025)

[DeepSeek on a Trip: Inducing Targeted Visual Hallucinations via Representation Vulnerabilities](https://arxiv.org/abs/2502.07905) (02/11, 2025)

[OverThink: Slowdown Attacks on Reasoning LLMs](https://arxiv.org/abs/2502.02542) (02/05, 2025) (RAG背景下，向context中添加过多复杂问题来提高reasoning的长度，引发overthink)

[Adversarial Reasoning at Jailbreaking Time](https://arxiv.org/abs/2502.01633) (02/03, 2025) (不直接使用模型输出来优化prompt，而是根据prompt在目标模型上target answer计算的CEloss来对prompt进行优劣排序，把排序结果送给feedback模型输出可能的改进方向以及优劣原因，指导生成下一个reasoning内容。在这个基础上，每一次攻击模型是接受reasoning指令生成恶意prompt，再用prompt来越狱。这类似GIA里面优化latent vector而不是直接优化pixel。真正优化的内容是所谓reasoning的指令，然后通过attacker生成prompt里面最强的（CEloss最小）来判定这个reasoning内容的价值。)

[The dark deep side of DeepSeek: Fine-tuning attacks against the safety alignment of CoT-enabled models](https://arxiv.org/abs/2502.01225) (02/03, 2025)

[Enhancing Adversarial Attacks through Chain of Thought](https://arxiv.org/abs/2410.21791) (10/29, 2024)

[Preemptive Answer "Attacks" on Chain-of-Thought Reasoning](https://arxiv.org/abs/2405.20902) (05/31, 2024)

[BadChain: Backdoor Chain-of-Thought Prompting for Large Language Models](https://arxiv.org/abs/2401.12242) (01/20, 2024)
## Defenses
[ERPO: Advancing Safety Alignment via Ex-Ante Reasoning Preference Optimization](https://arxiv.org/abs/2504.02725) (04/06, 2025)

[STAR-1: Safer Alignment of Reasoning LLMs with 1K Data](https://arxiv.org/abs/2504.01903) (04/02, 2025)

[Collab: Controlled Decoding using Mixture of Agents for LLM Alignment](https://arxiv.org/abs/2503.21720) (03/27, 2025)

[Harnessing Chain-of-Thought Metadata for Task Routing and Adversarial Prompt Detection](https://arxiv.org/abs/2503.21464) (03/27, 2025)

[AgentSpec: Customizable Runtime Enforcement for Safe and Reliable LLM Agents](https://arxiv.org/abs/2503.18666) (03/24, 2025)

[SRMIR: Shadow Reward Models Based on Introspective Reasoning for LLM Alignment](https://arxiv.org/abs/2503.18991) (03/23, 2025)

[Safe RLHF-V: Safe Reinforcement Learning from Human Feedback in Multimodal Large Language Models](https://arxiv.org/abs/2503.17682) (03/22, 2025)

[Policy Frameworks for Transparent Chain-of-Thought Reasoning in Large Language Models](https://arxiv.org/abs/2503.14521) (03/14, 2025)

[Safety is Not Only About Refusal: Reasoning-Enhanced Fine-tuning for Interpretable LLM Safety](https://arxiv.org/abs/2503.05021) (03/06, 2025)

[GuardReasoner: Towards Reasoning-based LLM Safeguards](https://arxiv.org/abs/2501.18492) (01/30, 2025)

[Chain-of-Scrutiny: Detecting Backdoor Attacks for Large Language Models](https://arxiv.org/abs/2406.05948) (12/20, 2024)

[Towards Efficient and Explainable Hate Speech Detection via Model Distillation](https://arxiv.org/abs/2412.13698) (12/18, 2024)

[Causal Prompting: Debiasing Large Language Model Prompting based on Front-Door Adjustment](https://arxiv.org/abs/2403.02738) (12/17, 2024)
## Studies
[Reasoning Models Don’t Always Say What They Think](https://www.anthropic.com/research/reasoning-models-dont-say-think) (04/03, 2025)

[Effectively Controlling Reasoning Models through Thinking Intervention](https://arxiv.org/abs/2503.24370) (03/31, 2025)

[Landscape of Thoughts: Visualizing the Reasoning Process of Large Language Models](https://arxiv.org/abs/2503.22165) (03/31, 2025)

[Trade-offs in Large Reasoning Models: An Empirical Analysis of Deliberative and Adaptive Reasoning over Foundational Capabilities](https://arxiv.org/abs/2503.17979) (03/23, 2025)

[Do Chains-of-Thoughts of Large Language Models Suffer from Hallucinations, Cognitive Biases, or Phobias in Bayesian Reasoning?](https://arxiv.org/abs/2503.15268) (03/19, 2025)

[Safety Evaluation and Enhancement of DeepSeek Models in Chinese Contexts](https://arxiv.org/abs/2503.16529) (03/18, 2025)

[Monitoring Reasoning Models for Misbehavior and the Risks of Promoting Obfuscation](https://arxiv.org/abs/2503.11926) (03/14, 2025)

[Chain-of-Thought Reasoning In The Wild Is Not Always Faithful](https://arxiv.org/abs/2503.08679) (03/13, 2025)

[Safety Guardrails for LLM-Enabled Robots](https://arxiv.org/abs/2503.07885) (03/10, 2025)

[Answer, Refuse, or Guess? Investigating Risk-Aware Decision Making in Language Models](https://arxiv.org/abs/2503.01332) (03/03, 2025)

[Safety Tax: Safety Alignment Makes Your Large Reasoning Models Less Reasonable](https://arxiv.org/abs/2503.00555) (03/01, 2025)

[Can Large Language Models Detect Errors in Long Chain-of-Thought Reasoning?](https://arxiv.org/abs/2502.19361) (02/27, 2025)

[The Hidden Risks of Large Reasoning Models: A Safety Assessment of R1](https://arxiv.org/abs/2502.12659v3) (02/27, 2025) 
- R1比o3等模型安全性更弱
- 蒸馏模型比对齐的基础模型安全性差 （R1-7B比qwen弱，R1-8B比llama弱）
- 更强的推理能力会增加不安全回应的不安全程度
- 相比回答来说reasoning内容更值得关切，reasoning回答的恶意程度大于answer的恶意程度

[Are Smarter LLMs Safer? Exploring Safety-Reasoning Trade-offs in Prompting and Fine-Tuning](https://arxiv.org/abs/2502.09673) (02/21, 2025)

- few-shot cot证明safety跟performance有trade-off。prompt中含有safety内容会降低reasoning performance，过多performance相关的demonstration会影响safety
- 用cot数据finetune之后安全性会变差
- 数据越多越差，但没有很严重；相反，长cot数据会更严重地牺牲安全性
- 微调过程中可以添加安全数据与cot混合，比较详细地安全数据可以提升模型安全性，同时cot可以提升生模型准确度

[Safechain: Safety of language models with long chain-of-thought reasoning capabilities](https://arxiv.org/abs/2502.12025) (02/17, 2025) 
- 现有benchmark仍然暴露r1的安全问题，微调模型进行长思考并不一定能提升安全性，提出安全数据集实现finetune后安全增强

[A Closer Look at System Prompt Robustness](https://arxiv.org/abs/2502.12197) (02/15, 2025)
- 模型在使用的时候需要提前设置很多要求避免滥用，要求称为“guardrails”。现有的模型，尽管在没有攻击的情况下，依然不能很好的跟随指令。
- 收集数据集进行DPO或者SFT可以带来提升，但是实验结果发现仍有提升空间，同时deepseek系统指令的跟随效果很差

[The Danger of Overthinking: Examining the Reasoning-Action Dilemma in Agentic Tasks](https://arxiv.org/abs/2502.08235) (02/12, 2025) 

[Trading Inference-Time Compute for Adversarial Robustness](https://arxiv.org/abs/2501.18841) (01/31, 2025)

[Order Matters in Hallucination: Reasoning Order as Benchmark and Reflexive Prompting for Large-Language-Models](https://arxiv.org/abs/2408.05093) (12/30, 2024)

[Alignment faking in large language models](https://arxiv.org/abs/2412.14093) (12/19, 2024)

[Anchoring Bias in Large Language Models: An Experimental Study](https://arxiv.org/abs/2412.06593) (12/18, 2024)

[Building Trustworthy AI: Transparent AI Systems via Large Language Models, Ontologies, and Logical Reasoning (TranspNet)](https://arxiv.org/abs/2411.08469) (12/18, 2024)

[How Likely Do LLMs with CoT Mimic Human Reasoning?](https://arxiv.org/abs/2402.16048) (12/12, 2024)

[On the Impact of Fine-Tuning on Chain-of-Thought Reasoning](https://arxiv.org/abs/2411.15382) (11/22, 2024)

[Can Language Models Perform Robust Reasoning in Chain-of-thought Prompting with Noisy Rationales?](https://arxiv.org/abs/2410.23856) (31/10, 2024)

[Language Models Don’t Always Say What They Think: Unfaithful Explanations in Chain-of-Thought Prompting](https://arxiv.org/abs/2305.04388) (12/09, 2023)
## Surveys, Datasets, Evaluation and Benchmarks
[Recitation over Reasoning: How Cutting-Edge Language Models Can Fail on Elementary School-Level Reasoning Problems?](https://arxiv.org/abs/2504.00509) (04/01, 2025)

[Harnessing the Reasoning Economy: A Survey of Efficient Reasoning for Large Language Models](https://arxiv.org/abs/2503.24377) (03/31, 2025)

[Challenging the Boundaries of Reasoning: An Olympiad-Level Math Benchmark for Large Language Models](https://arxiv.org/abs/2503.21380) (03/28, 2025)

[Towards Understanding the Safety Boundaries of DeepSeek Models: Evaluation and Findings](https://arxiv.org/abs/2503.15092) (03/19, 2025)
- 模型对于不同语言的安全性不同（英文更不安全）
- 暴露的reasoning内容增加模型危险，相比v3，r1安全性大大降低 （结论说是因为reasoning暴露了，但是可能有问题：模型不一样，得到的结果也不同，多的危险性不一定来自reasoning文本，可能是因为本身训练的数据就不一样）
- 当面对jailbreak攻击，r1攻击成功率提升很多

[DNA Bench: When Silence is Smarter -- Benchmarking Over-Reasoning in Reasoning LLMs](https://arxiv.org/abs/2503.15793) (03/19, 2025)

[Safety Evaluation and Enhancement of DeepSeek Models in Chinese Contexts](https://arxiv.org/abs/2503.16529) (03/18, 2025)

[Red Teaming Contemporary AI Models: Insights from Spanish and Basque Perspectives](https://arxiv.org/abs/2503.10192) (03/13, 2025)

[Benchmarking Reasoning Robustness in Large Language Models](https://arxiv.org/abs/2503.04550) (03/06, 2025)

[Evaluating security risk in deepseek and other frontier reasoning models](https://blogs.cisco.com/security/evaluating-security-risk-in-deepseek-and-other-frontier-reasoning-models) (02/26, 2025)

[How Effective Is Constitutional AI in Small LLMs? A Study on DeepSeek-R1 and Its Peers](https://arxiv.org/abs/2503.17365) (02/01, 2025)

[Understanding the Dark Side of LLMs' Intrinsic Self-Correction](https://arxiv.org/abs/2412.14959) (12/19, 2024)
- 发现自我纠正更多会失败而非改正，添加自我纠正进行第二轮conversation会让模型表现下降
- 通过重要性分析，发现模型因为存在bias：倾向于回答更接近末尾的问题，而不是一开始的问题。提第二个self-correction的问题更接近prompt的末尾，吸引模型更多关注 (但是关注更多并不代表要回答错误的内容？只能说模型训练并不鲁棒，这样的问题本身更容易受到adversarial prompt，也就是self-correction prompt的影响从而实现翻转)
- 减轻方法
    - 1. 多问一句对应的问题，不仅仅让模型重新思考，而是让模型focus在最后的问题上
    - 2. SFT，收集经过self-correction之后依然正确的数据进行微调，少量数据就可以达到好的效果，说明这也是一个类似的bias

# type
## overthink
## faithfulness
## robustness versus reasoning
