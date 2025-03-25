# Awesome-reasoning-safety
This repo is for the safety topic, including attacks, defenses and studies related to reasoning and RL. Data are mainly from arxiv.
## Attacks

[Don't Take Things Out of Context: Attention Intervention for Enhancing Chain-of-Thought Reasoning in Large Language Models](https://arxiv.org/abs/2503.11154) (03/14, 2025)

[A Frustratingly Simple Yet Highly Effective Attack Baseline: Over 90% Success Rate Against the Strong Black-box Models of GPT-4.5/4o/o1](https://arxiv.org/abs/2503.10635) (03/13, 2025) (adversarial attack/pixel manipulation 对于多模态大模型仍然有效)

[Cats Confuse Reasoning LLM: Query Agnostic Adversarial Triggers for Reasoning Models](https://arxiv.org/abs/2503.01781) (03/03, 2025) (添加有意义的多余句可以误导r1/distill模型产生错误结果)

[Output Length Effect on DeepSeek-R1's Safety in Forced Thinking](https://arxiv.org/abs/2503.01923) (03/02, 2025)

[The Hidden Risks of Large Reasoning Models: A Safety Assessment of R1](https://arxiv.org/abs/2502.12659v3) (02/27, 2025)

[A Mousetrap: Fooling Large Reasoning Models for Jailbreak with Chain of Iterative Chaos](https://www.arxiv.org/abs/2502.15806) (02/19, 2025) (添加更多的步骤让模型先思考真正的prompt再回答)

[H-CoT: Hijacking the Chain-of-Thought Safety Reasoning Mechanism to Jailbreak Large Reasoning Models, Including OpenAI o1/o3, DeepSeek-R1, and Gemini 2.0 Flash Thinking](https://arxiv.org/abs/2502.12893v1) (02/18, 2025)

[BoT: Breaking Long Thought Processes of o1-like Large Language Models through Backdoor Attack](https://arxiv.org/abs/2502.12202) (02/16, 2025)

[DeepSeek on a Trip: Inducing Targeted Visual Hallucinations via Representation Vulnerabilities](https://arxiv.org/abs/2502.07905) (02/11, 2025)


[OverThink: Slowdown Attacks on Reasoning LLMs](https://arxiv.org/abs/2502.02542) (02/05, 2025) (RAG背景下，向context中添加过多复杂问题来提高reasoning的长度，引发overthink)

[Adversarial Reasoning at Jailbreaking Time](https://arxiv.org/abs/2502.01633) (02/03, 2025) (用reasoning model来做red teaming)

[The dark deep side of DeepSeek: Fine-tuning attacks against the safety alignment of CoT-enabled models](https://arxiv.org/abs/2502.01225) (02/03, 2025)

## Defenses
[Safe RLHF-V: Safe Reinforcement Learning from Human Feedback in Multimodal Large Language Models](https://arxiv.org/abs/2503.17682) (03/22, 2025)

[Policy Frameworks for Transparent Chain-of-Thought Reasoning in Large Language Models](https://arxiv.org/abs/2503.14521) (03/14, 2025)

[Safety is Not Only About Refusal: Reasoning-Enhanced Fine-tuning for Interpretable LLM Safety](https://arxiv.org/abs/2503.05021) (03/06, 2025)

[GuardReasoner: Towards Reasoning-based LLM Safeguards](https://arxiv.org/abs/2501.18492) (01/30, 2025)
## Studies
[Trade-offs in Large Reasoning Models: An Empirical Analysis of Deliberative and Adaptive Reasoning over Foundational Capabilities](https://arxiv.org/abs/2503.17979) (03/23, 2025)

[Towards Understanding the Safety Boundaries of DeepSeek Models: Evaluation and Findings](https://arxiv.org/abs/2503.15092) (03/19, 2025)

[Do Chains-of-Thoughts of Large Language Models Suffer from Hallucinations, Cognitive Biases, or Phobias in Bayesian Reasoning?](https://arxiv.org/abs/2503.15268) (03/19, 2025)

[Safety Evaluation and Enhancement of DeepSeek Models in Chinese Contexts](https://arxiv.org/abs/2503.16529) (03/18, 2025)

[Monitoring Reasoning Models for Misbehavior and the Risks of Promoting Obfuscation](https://arxiv.org/abs/2503.11926) (03/14, 2025)

[Chain-of-Thought Reasoning In The Wild Is Not Always Faithful](https://arxiv.org/abs/2503.08679) (03/13, 2025)

[Safety Guardrails for LLM-Enabled Robots](https://arxiv.org/abs/2503.07885) (03/10, 2025)

[Answer, Refuse, or Guess? Investigating Risk-Aware Decision Making in Language Models](https://arxiv.org/abs/2503.01332) (03/03, 2025)

[Safety Tax: Safety Alignment Makes Your Large Reasoning Models Less Reasonable](https://arxiv.org/abs/2503.00555) (03/01, 2025)

[Safechain: Safety of language models with long chain-of-thought reasoning capabilities](https://arxiv.org/abs/2502.12025) (02/17, 2025) (现有benchmark仍然暴露r1的安全问题，微调模型进行长思考并不一定能提升安全性，提出安全数据集实现finetune后安全增强)

[A Closer Look at System Prompt Robustness](https://arxiv.org/abs/2502.12197) (02/15, 2025)

[The Danger of Overthinking: Examining the Reasoning-Action Dilemma in Agentic Tasks](https://arxiv.org/abs/2502.08235) (02/12, 2025) 

[TRADING INFERENCE-TIME COMPUTE FOR ADVERSARIAL ROBUSTNESS](https://arxiv.org/abs/2501.18841) (01/31, 2025)
## Surveys, Datasets, Evaluation and Benchmarks
[Towards Understanding the Safety Boundaries of DeepSeek Models: Evaluation and Findings](https://arxiv.org/abs/2503.15092) (03/19, 2025)

[DNA Bench: When Silence is Smarter -- Benchmarking Over-Reasoning in Reasoning LLMs](https://arxiv.org/abs/2503.15793) (03/19, 2025)

[Safety Evaluation and Enhancement of DeepSeek Models in Chinese Contexts](https://arxiv.org/abs/2503.16529) (03/18, 2025)

[Red Teaming Contemporary AI Models: Insights from Spanish and Basque Perspectives](https://arxiv.org/abs/2503.10192) (03/13, 2025)

[Benchmarking Reasoning Robustness in Large Language Models](https://arxiv.org/abs/2503.04550) (03/06, 2025)

[Can Large Language Models Detect Errors in Long Chain-of-Thought Reasoning?](https://arxiv.org/abs/2502.19361) (02/27, 2025)

[Evaluating security risk in deepseek and other frontier reasoning models](https://blogs.cisco.com/security/evaluating-security-risk-in-deepseek-and-other-frontier-reasoning-models) (02/26, 2025)

[How Effective Is Constitutional AI in Small LLMs? A Study on DeepSeek-R1 and Its Peers](https://arxiv.org/abs/2503.17365) (02/01, 2025)


# Other interesting papers
[Long Is More Important Than Difficult for Training Reasoning Models](https://arxiv.org/abs/2503.18069) (03/23, 2025)

[SafeMERGE: Preserving Safety Alignment in Fine-Tuned Large Language Models via Selective Layer-Wise Model Merging](https://arxiv.org/abs/2503.17239) (03/21, 2025)


[Adapting Language-Specific LLMs to a Reasoning Model in One Day via Model Merging](https://arxiv.org/abs/2502.09056) (02/17, 2025)

[A Survey of Safety on Large Vision-Language Models: Attacks, Defenses and Evaluations](https://arxiv.org/abs/2502.14881) (02/14, 2025)