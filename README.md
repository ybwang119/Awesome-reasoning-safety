# Awesome-reasoning-safety
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/ybwang119/Awesome-reasoning-safety)
[![Last Commit](https://img.shields.io/github/last-commit/ybwang119/Awesome-reasoning-safety)](https://github.com/ybwang119/Awesome-reasoning-safety)

This repo is for the trustworthy topics in reasoning-related technique, including but not limited to attacks, defenses, studies and benchmarks related to CoT, reasoning and RL. Data are mainly from arxiv. 

## Table of contents
- [Truthfulness](#Truthfulness:-Hallucination,-reasoning-faithfulness)
    - [Hallucination](#Hallucination)
    - [Reasoning faithfulness](#Reasoning-faithfulness)
- [Security](#Security:-Jailbreak,-prompt-injection,-backdoor)
    - [Jailbreak](#Jailbreak)
    - [Prompt injection](#Prompt-injection)
    - [Backdoor](#Backdoor)
- [Robustness](#Robustness:-input-perturbation,-overthinking/underthinking)
    - [Input perturbation](#Input-perturbation)
    - [Overthinking/underthinking](#overthinkingunderthinking)
- [Privacy](#Privacy)
- [Fairness](#fairness)
- [Related surveys and benchmarks](#Related-surveys-and-benchmarks)
- [Others](#Other-related-studies)
---
## Truthfulness: Hallucination, reasoning faithfulness
### Hallucination

<details>
<summary>Click to expand the paper list</summary>

|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[KnowRL: Exploring Knowledgeable Reinforcement Learning for Factuality](https://arxiv.org/abs/2506.19807)|arxiv|06/24, 2025|Hallucination mitigation|[Github](https://github.com/zjunlp/KnowRL)|
|[Mathematical Proof as a Litmus Test: Revealing Failure Modes of Advanced Large Reasoning Models](https://arxiv.org/abs/2506.17114)|arxiv|06/23, 2025|hallucination study|-|
|[Reasoning about Uncertainty: Do Reasoning Models Know When They Don't Know?](https://arxiv.org/abs/2506.18183)|arxiv|06/22, 2025|uncertainty and calibration|-|
|[Chain-of-Thought Prompting Obscures Hallucination Cues in Large Language Models: An Empirical Evaluation](https://arxiv.org/abs/2506.17088)|arxiv|06/20, 2025|evaluation|[Github](https://anonymous.4open.science/r/cot-hallu-detect)|
|[Uncertainty-o: One Model-agnostic Framework for Unveiling Uncertainty in Large Multimodal Models](https://arxiv.org/abs/2506.07527)|arxiv|06/09, 2025|hallucination estimation|-|
|[Joint Evaluation of Answer and Reasoning Consistency for Hallucination Detection in Large Reasoning Models](https://arxiv.org/abs/2506.04832)|arxiv|06/05, 2025|evaluation|-|
|[More Thinking, Less Seeing? Assessing Amplified Hallucination in Multimodal Reasoning Models](https://arxiv.org/abs/2505.21523)|arxiv|05/23, 2025|evaluation|[Project](https://mlrm-halu.github.io/)|
|[TreeCut: A Synthetic Unanswerable Math Word Problem Dataset for LLM Hallucination Evaluation](https://arxiv.org/abs/2502.13442)|arxiv|05/20, 2025|hallucination evaluation|[GitHub](https://github.com/j-bagel/treecut-math)|
|[The Hallucination Tax of Reinforcement Finetuning](https://arxiv.org/abs/2505.13988)|arxiv|05/20, 2025|hallucination|-|
|[Toward Reliable Biomedical Hypothesis Generation: Evaluating Truthfulness and Hallucination in Large Language Models](https://arxiv.org/abs/2505.14599)|arxiv|05/20, 2025|hallucination evaluation|[GitHub](https://github.com/Teddy-XiongGZ/TruthHypo)|
|[Auditing Meta-Cognitive Hallucinations in Reasoning Large Language Models](https://arxiv.org/abs/2505.13143)|arxiv|05/19, 2025|hallucination study|[anonymous_link](https://anonymous.4open.science/r/repo_for_meta_hallucination)|
|[Reasoning Large Language Model Errors Arise from Hallucinating Critical Problem Features](https://arxiv.org/abs/2505.12151)|arxiv|05/17, 2025|hallucination mitigation|-|
|[Enhancing Mathematical Reasoning in Large Language Models with Self-Consistency-Based Hallucination Detection](https://arxiv.org/abs/2504.09440)|arxiv|04/13, 2025|hallucination detection|-|
|[Do Chains-of-Thoughts of Large Language Models Suffer from Hallucinations, Cognitive Biases, or Phobias in Bayesian Reasoning?](https://arxiv.org/abs/2503.15268)|arxiv|03/19, 2025|hallucination|-|
|[Order Matters in Hallucination: Reasoning Order as Benchmark and Reflexive Prompting for Large-Language-Models](https://arxiv.org/abs/2408.05093)|arxiv|12/30, 2024|hallucination|-|
|[CLATTER: Comprehensive Entailment Reasoning for Hallucination Detection](https://arxiv.org/abs/2506.05243)|arxiv|06/05, 2025|evaluation|-|
|[The Hallucination Dilemma: Factuality-Aware Reinforcement Learning for Large Reasoning Models](https://arxiv.org/abs/2505.24630)|arxiv|05/30, 2025|evaluation|-|
|[MIRAGE: Assessing Hallucination in Multimodal Reasoning Chains of MLLM](https://arxiv.org/abs/2505.24238)|arxiv|05/30, 2025|evaluation|-|
|[Are Reasoning Models More Prone to Hallucination?](https://arxiv.org/abs/2505.23646)|arxiv|05/29, 2025|evaluation|-|
|[Analyzing Logical Fallacies in Large Language Models: A Study on Hallucination in Mathematical Reasoning](https://link.springer.com/chapter/10.1007/978-981-96-7071-0_12)|JSAI-isAI 2025|05/23, 2025|evaluation|[Project](https://mlrm-halu.github.io/)|
|[The Hallucination Tax of Reinforcement Finetuning](https://arxiv.org/abs/2505.13988)|arxiv|05/20, 2025|hallucination|-|
|[Detection and Mitigation of Hallucination in Large Reasoning Models: A Mechanistic Perspective](https://arxiv.org/abs/2505.12886)|arxiv|05/19, 2025|hallucination study|[anonymous_link](https://anonymous.4open.science/r/repo_for_meta_hallucination)|
|[Don't Let It Hallucinate: Premise Verification via Retrieval-Augmented Logical Reasoning](https://arxiv.org/abs/2504.06438)|arxiv|04/08, 2025|  hallucinationn detection|-|
|[Grounded Chain-of-Thought for Multimodal Large Language Models](https://arxiv.org/abs/2503.12799)|arxiv|03/17, 2025|hallucination|-|
|[Mitigating reasoning hallucination through Multi-agent Collaborative Filtering](https://www.sciencedirect.com/science/article/pii/S0957417424025909)|ESWA 2025|03/05, 2025|hallucination|-|
|[DeepSeek on a Trip: Inducing Targeted Visual Hallucinations via Representation Vulnerabilities](https://arxiv.org/abs/2502.07905)|arxiv|02/11, 2025|hallucination|-|
|[Think More, Hallucinate Less: Mitigating Hallucinations via Dual Process of Fast and Slow Thinking](https://arxiv.org/abs/2501.01306)|arxiv|01/02, 2025|hallucination|-|
|[Thinking Before Looking: Improving Multimodal LLM Reasoning via Mitigating Visual Hallucination]( https://arxiv.org/abs/2411.12591)|arxiv|11/15, 2024|hallucination|-|
|[HalluMeasure: Fine-grained Hallucination Measurement Using Chain-of-Thought Reasoning](https://aclanthology.org/2024.emnlp-main.837/)|EMNLP 2024|11/12, 2024|hallucination|-|
|[FG-PRM: Fine-grained Hallucination Detection and Mitigation in Language Model Mathematical Reasoning](https://arxiv.org/abs/2410.06304)|arxiv|10/08, 2024|hallucination|-|
|[CoMT: Chain-of-Medical-Thought Reduces Hallucination in Medical Report Generation](https://arxiv.org/abs/2406.11451)|arxiv|06/17, 2024|        hallucination|-|

</details>

### Reasoning faithfulness

<details>
<summary>Click to expand the paper list</summary>

|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Right Is Not Enough: The Pitfalls of Outcome Supervision in Training LLMs for Math Reasoning](https://arxiv.org/abs/2506.06877)|arxiv|06/24, 2025|faithfulness detector|-|
|[VFaith: Do Large Multimodal Models Really Reason on Seen Images Rather than Previous Memories?](https://arxiv.org/abs/2506.11571)|arxiv|06/13, 2025|MLLM faithfulness evaluation|[Github](https://github.com/LittleCoder12345/VFaith-Bench)|
|[Teaching Large Language Models to Maintain Contextual Faithfulness via Synthetic Tasks and Reinforcement Learning](https://arxiv.org/abs/2505.16483)|arxiv|05/22, 2025|faitufulness improvement|-|
|[Measuring the Faithfulness of Thinking Drafts in Large Reasoning Models](https://arxiv.org/abs/2505.13774)|arxiv|05/20, 2025|faithfulness assessment|-|
|[Walk the Talk? Measuring the Faithfulness of Large Language Model Explanations](https://arxiv.org/abs/2504.14150)|arxiv|05/20, 2025|faithfulness assessment|-|
|[Reasoning Models Don’t Always Say What They Think](https://www.anthropic.com/research/reasoning-models-dont-say-think)|arxiv|04/03, 2025|faithfulness|-|
|[Reasoning Inconsistencies and How to Mitigate Them in Deep Learning](https://arxiv.org/abs/2504.02577)|arxiv|04/03, 2025|faithfulness|-|
|[Landscape of Thoughts: Visualizing the Reasoning Process of Large Language Models](https://arxiv.org/abs/2503.22165)|arxiv|03/28, 2025|faithfulness|-|
|[Policy Frameworks for Transparent Chain-of-Thought Reasoning in Large Language Models](https://arxiv.org/abs/2503.14521)|arxiv|03/14, 2025|faithfulness|-|
|[Monitoring Reasoning Models for Misbehavior and the Risks of Promoting Obfuscation](https://arxiv.org/abs/2503.11926)|arxiv|03/14, 2025|faithfulness|-|
|[Chain-of-Thought Reasoning In The Wild Is Not Always Faithful](https://arxiv.org/abs/2503.08679)|arxiv|03/13, 2025|faithfulness|-|
|[A Causal Lens for Evaluating Faithfulness Metrics](https://arxiv.org/abs/2502.18848)|arxiv|02/26, 2025|faithfulness|-|
|[Measuring faithfulness of chains of thought by unlearning reasoning steps](https://arxiv.org/abs/2502.14829)|arxiv| 02/20, 2025 |faithfulness|-|
|[Are DeepSeek R1 And Other Reasoning Models More Faithful?](https://arxiv.org/abs/2501.08156)|ICLR 2025 Workshop|01/14, 2025|faithfulness|-|
|[Graph-Guided Textual Explanation Generation Framework](https://arxiv.org/abs/2412.12318)|arxiv|12/16, 2024|faithfulness|-|
|[New Faithfulness-Centric Interpretability Paradigms for Natural Language Processing](https://arxiv.org/abs/2411.17992)|arxiv|11/27, 2024|faithfulness|-|
|[On the Impact of Fine-Tuning on Chain-of-Thought Reasoning](https://arxiv.org/abs/2411.15382)|arxiv|11/22, 2024|faithfulness|-|
|[Causal-driven Large Language Models with Faithful Reasoning for Knowledge Question Answering](https://dl.acm.org/doi/abs/10.1145/3664647.3681263)|ACM MM 24|10/28, 2024|faithfulness|-|
|[Towards Faithful Natural Language Explanations: A Study Using Activation Patching in Large Language Models](https://arxiv.org/abs/2410.14155)|arxiv|10/18, 2024|faithfulness|-|
|[Enhancing Large Language Models' Situated Faithfulness to External Contexts](https://arxiv.org/abs/2410.14675v1)|arxiv|10/18, 2024|faithfulness|-|
|[FLARE: Faithful Logic-Aided Reasoning and Exploration](https://arxiv.org/abs/2410.11900)|arxiv|10/14, 2024|faithfulness|-|
|[CoMAT: Chain of Mathematically Annotated Thought Improves Mathematical Reasoning](https://arxiv.org/abs/2410.10336)|arxiv|10/14, 2024|faithfulness|-|
|[On the Difficulty of Faithful Chain-of-Thought Reasoning in Large Language Models](https://openreview.net/forum?id=3h0kZdPhAC)|ICML 2024 Workshop|06/19, 2024|faithfulness|-|
|[On the Hardness of Faithful Chain-of-Thought Reasoning in Large Language Models](https://arxiv.org/abs/2406.10625)|arxiv|06/15, 2024|faithfulness|-|
|[XPrompt:Explaining Large Language Model's Generation via Joint Prompt Attribution](https://arxiv.org/abs/2405.20404)|arxiv|05/30, 2024|faithfulness|-|
|[Faithful Logical Reasoning via Symbolic Chain-of-Thought](https://arxiv.org/abs/2405.18357)|ACL 2024|05/28, 2024|faithfulness|-|
|[Dissociation of Faithful and Unfaithful Reasoning in LLMs](https://arxiv.org/abs/2405.15092)|arxiv|05/23, 2024|faithfulness|-|
|[FiDeLiS: Faithful Reasoning in Large Language Model for Knowledge Graph Question Answering](https://arxiv.org/abs/2405.13873)|arxiv|05/22, 2024|faithfulness|-|
|[Faithful Reasoning over Scientific Claims](https://ojs.aaai.org/index.php/AAAI-SS/article/view/31209)|AAAI 2024|05/20, 2024|faithfulness|-|
|[Towards Faithful Chain-of-Thought: Large Language Models are Bridging ReasonersPreprint](https://ui.adsabs.harvard.edu/abs/2024arXiv240518915L/abstract)|arxiv|05/18, 2024|faithfulness|-|
|[Markovian Transformers for Informative Language Modeling](https://arxiv.org/abs/2404.18988)|arxiv|04/29, 2024|faithfulness|-|
|[Fact :Teaching MLLMs with Faithful, Concise and Transferable Rationales](https://arxiv.org/abs/2404.11129)|ACM MM 2024|04/17, 2024|faithfulness|-|
|[Argumentative Large Language Models for Explainable and Contestable Claim Verification](https://ojs.aaai.org/index.php/AAAI/article/view/33637)|AAAI 2025|04/11, 2024|faithfulness|-|
|[Recent Developments on Accountability and Explainability for Complex Reasoning Tasks](https://link.springer.com/chapter/10.1007/978-3-031-51518-7_9)|Springer|04/06, 2024|faithfulness|-|
|[The Probabilities Also Matter: A More Faithful Metric for Faithfulness of Free-Text Explanations in Large Language Models](https://arxiv.org/abs/2404.03189)|arxiv|04/04, 2024|faithfulness|-|
|[How Likely Do LLMs with CoT Mimic Human Reasoning?](https://arxiv.org/abs/2402.16048)|arxiv|02/25, 2024|faithfulness|-|
|[Chain-of-Thought Unfaithfulness as Disguised Accuracy](https://arxiv.org/abs/2402.14897)|TMLR|02/22, 2024|faithfulness|-|
|[Making Reasoning Matter: Measuring and Improving Faithfulness of Chain-of-Thought Reasoning](https://arxiv.org/abs/2402.13950)|EMNLP 2024 Findings|02/21, 2024|faithfulness|[Github](https://github.com/debjitpaul/Causal_CoT)|
|[How Interpretable are Reasoning Explanations from Prompting Large Language Models?](https://arxiv.org/abs/2402.11863)|NAACL 2024 Findings|02/19, 2024|faithfulness|[Github](https://github.com/SenticNet/CoT_interpretability)|
|[FaithLM: Towards Faithful Explanations for Large Language Models](https://arxiv.org/abs/2402.04678)|EMNLP 2024 Findings|02/07, 2024|faithfulness||
|[Faithfulness vs. Plausibility: On the (Un)Reliability of Explanations from Large Language Models](https://arxiv.org/abs/2402.04614)|arxiv|02/07, 2024|faithfulness||
|[Reasoning on Graphs: Faithful and Interpretable Large Language Model Reasoning](https://arxiv.org/abs/2310.01061)|ICLR 2024|10/02, 2023|faithfulness|[Github](https://github.com/RManLuo/reasoning-on-graphs)|
|[Measuring Faithfulness in Chain-of-Thought Reasoning](https://arxiv.org/abs/2307.13702)|arxiv|07/17, 2023|faithfulness|-|
|[Logic-LM: Empowering Large Language Models with Symbolic Solvers for Faithful Logical Reasoning](https://openreview.net/forum?id=nWXMv949ZH)|EMNLP 2023 Findings|05/20, 2023|faithfulness|-|
|[Language Models Don’t Always Say What They Think: Unfaithful Explanations in Chain-of-Thought Prompting](https://arxiv.org/abs/2305.04388)|arxiv|05/07, 2023|faithfulness|-|
|[Faithful Chain-of-Thought Reasoning](https://arxiv.org/abs/2301.13379)|IJCNLP-AACL 2023|01/31, 2023|faithfulness|[Github](https://github.com/veronica320/Faithful-COT)|

</details>

## Safety: Jailbreak, prompt injection, backdoor
### Jailbreak
<details>
<summary>Click to expand the paper list</summary>

|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:| 
|[MSR-Align: Policy-Grounded Multimodal Alignment for Safety-Aware Reasoning in Vision-Language Models](https://arxiv.org/abs/2506.19257)|arxiv|06/23, 2025|Multimodal Alignment|[Huggingface](https://huggingface.co/datasets/Leigest/MSR-Align)|
|[How Alignment Shrinks the Generative Horizon](https://arxiv.org/abs/2506.17871)|arxiv|06/21, 2025|alignment study|-|
|[Weakest Link in the Chain: Security Vulnerabilities in Advanced Reasoning Models](https://arxiv.org/abs/2506.13726)|LLMSEC 2025|06/16, 2025|red-teaming|-|
|[Thought Crime: Backdoors and Emergent Misalignment in Reasoning Models](https://arxiv.org/abs/2506.13206)|arxiv|06/16, 2025|finetuning attack|[Huggingface](https://huggingface.co/datasets/truthfulai/emergent_plus)|
|[Detecting Harmful Memes with Decoupled Understanding and Guided CoT Reasoning](https://arxiv.org/abs/2506.08477)|arxiv|06/10, 2025|harmful meme detection|[Link](https://anonymous.4open.science/r/HMC-AF2B)|
|[SafeCoT: Improving VLM Safety with Minimal Reasoning](https://arxiv.org/abs/2506.08399)|arxiv|06/09, 2025|VLM alignment|-|
|[RSafe: Incentivizing proactive reasoning to build robust and adaptive LLM safeguards](https://arxiv.org/abs/2506.07736)|arxiv|06/09, 2025|guardrail model|-|
|[Chasing Moving Targets with Online Self-Play Reinforcement Learning for Safer Language Models](https://arxiv.org/abs/2506.07468)|arxiv|06/09, 2025|alignment|-|
|[Safety-Polarized and Prioritized Reinforcement Learning](https://openreview.net/forum?id=x10ryC8F0C)|ICML 2025|not available|-|[Github](https://github.com/FrankSinatral/Safety-PP)|
|[HauntAttack: When Attack Follows Reasoning as a Shadow](https://arxiv.org/abs/2506.07031)|arxiv|06/08, 2025|jailbreak attack|-|
|[Saffron-1: Towards an Inference Scaling Paradigm for LLM Safety Assurance](https://arxiv.org/abs/2506.06444)|arxiv|06/06, 2025|alignment|[Github](https://github.com/q-rz/saffron)|
|[UDora: A Unified Red Teaming Framework against LLM Agents by Dynamically Hijacking Their Own Reasoning](https://arxiv.org/abs/2503.01908)|ICML 2025|06/06, 2025|red teaming agents|[Github](https://github.com/AI-secure/UDora)|
|[Mixture of insighTful Experts (MoTE): The Synergy of Thought Chains and Expert Mixtures in Self-Alignment](https://arxiv.org/abs/2405.00557)|arxiv|06/01, 2025|alignment|-|
|[Revealing the Intrinsic Ethical Vulnerability of Aligned Large Language Models](https://arxiv.org/abs/2504.05050)|arxiv|05/26, 2025|jailbreak attack|-|
|[VisCRA: A Visual Chain Reasoning Attack for Jailbreaking Multimodal Large Language Models](https://arxiv.org/abs/2505.19684)|arxiv|05/26, 2025|jailbreak MLRM|-|
|[Safety Through Reasoning: An Empirical Study of Reasoning Guardrail Models](https://arxiv.org/abs/2505.20087)|arxiv|05/26, 2025|guardrail model|-|
|[Does Chain-of-Thought Reasoning Really Reduce Harmfulness from Jailbreaking?](https://arxiv.org/abs/2505.17650)|arxiv|05/23, 2025|jailbreak analysis|-|
|[Chain-of-Lure: A Synthetic Narrative-Driven Approach to Compromise Large Language Models](https://arxiv.org/abs/2505.17519)|arxiv|05/23, 2025|jailbreak with CoT|-|
|[Three Minds, One Legend: Jailbreak Large Reasoning Model with Adaptive Stacked Ciphers](https://arxiv.org/abs/2505.16241)|arxiv|05/22, 2025|jailbreak attack|-|
|[ReasoningShield: Content Safety Detection over Reasoning Traces of Large Reasoning Models](https://arxiv.org/abs/2505.17244)|arxiv|05/22, 2025|Guardrail model|-|
|[From Evaluation to Defense: Advancing Safety in Video Large Language Models](https://arxiv.org/abs/2505.16643)|arxiv|05/22, 2025|multi-modal alignment|-|
|[RRTL: Red Teaming Reasoning Large Language Models in Tool Learning](https://arxiv.org/abs/2505.17106)|arxiv|05/21, 2025|red-teaming tool-learning evaluation|-|
|[Any Large Language Model Can Be a Reliable Judge: Debiasing with a Reasoning-based Bias Detector](https://arxiv.org/abs/2505.17100)|arxiv|05/21, 2025|LLM-as-a-judge|-|
|[How Should We Enhance the Safety of Large Reasoning Models: An Empirical Study](https://arxiv.org/abs/2505.15404)|arxiv|05/21, 2025|alignment|[GitHub](https://github.com/thu-coai/LRM-Safety-Study)|
|[J4R: Learning to Judge with Equivalent Initial State Group Relative Policy Optimization](https://arxiv.org/abs/2505.13346)|arxiv|05/20, 2025|LLM-as-a-judge|-|
|[Context Reasoner: Incentivizing Reasoning Capability for Contextualized Privacy and Safety Compliance via Reinforcement Learning](https://arxiv.org/abs/2505.14585)|arxiv|05/20, 2025|alignment|-|
|[SAFEPATH: Preventing Harmful Reasoning in Chain-of-Thought via Early Alignment](https://arxiv.org/abs/2505.14667)|arxiv|05/20, 2025|alignment|-|
|[ShieldVLM: Safeguarding the Multimodal Implicit Toxicity via Deliberative Reasoning with LVLMs](https://arxiv.org/abs/2505.14035)|arxiv|05/20, 2025|multi-modal jailbreak defense|-|
|[Linear Control of Test Awareness Reveals Differential Compliance in Reasoning Models](https://arxiv.org/pdf/2505.14617v1)|arxiv|05/20, 2025|alignment study|[GitHub](https://github.com/microsoft/Test_Awareness_Steering)|
|[Walking the Tightrope: Disentangling Beneficial and Detrimental Drifts in Non-Stationary Custom-Tuning](https://arxiv.org/abs/2505.13081)|arxiv|05/19, 2025|multi-modal alignment|-|
|[Think Twice Before You Act: Enhancing Agent Behavioral Safety with Thought Correction](https://arxiv.org/abs/2505.11063)|arxiv|05/19, 2025|agent alignment|-|
|[GuardReasoner-VL: Safeguarding VLMs via Reinforced Reasoning](https://arxiv.org/abs/2505.11049)|arxiv|05/16, 2025|guardrail model|-|[Github](https://github.com/yueliu1999/GuardReasoner-VL)|
|[FalseReject: A Resource for Improving Contextual Safety and Mitigating Over-Refusals in LLMs via Structured Reasoning](https://arxiv.org/abs/2505.08054)|arxiv|05/12, 2025|alignment (over reject mitigation)|-|
|[DeepSeek-R1 Thoughtology: Let's think about LLM Reasoning](https://arxiv.org/abs/2504.07128)|arxiv|05/12, 2025|safety assessment|-|
|[On the Robustness of Reward Models for Language Model Alignment](https://arxiv.org/abs/2505.07271)|arxiv|05/12, 2025|reward model|-|
|[Think in Safety: Unveiling and Mitigating Safety Alignment Collapse in Multimodal Large Reasoning Model](https://arxiv.org/abs/2505.06538)|arxiv|05/10, 2025|multi-modal alignment|-|
|[LlamaFirewall: An open source guardrail system for building secure AI agents](https://arxiv.org/abs/2505.03574)|arxiv|05/06, 2025|Guardrail model|-|
|[MR. Guard: Multilingual Reasoning Guardrail using Curriculum Learning](https://arxiv.org/abs/2504.15241)|arxiv|04/21, 2025|Guardrail model|-|
|[Energy-Based Reward Models for Robust Language Model Alignment](https://arxiv.org/abs/2504.13134)|arxiv|04/17, 2025|reward model|-|
|[VLMGuard-R1: Proactive Safety Alignment for VLMs via Reasoning-Driven Prompt Optimization](https://arxiv.org/abs/2504.12661)|arxiv|04/17, 2025|multi-modal alignment|-|
|[RealSafe-R1: Safety-Aligned DeepSeek-R1 without Compromising Reasoning Capability](https://arxiv.org/abs/2504.10081)|arxiv|04/14, 2025|alignment|-|
|[SaRO: Enhancing LLM Safety through Reasoning-based Alignment](https://arxiv.org/abs/2504.09420)|arxiv|04/13, 2025|alignment|-|
|[SafeMLRM: Demystifying Safety in Multi-modal Large Reasoning Models](https://arxiv.org/abs/2504.08813)|arxiv|04/09, 2025|multi-modal alignment|-|
|[ERPO: Advancing Safety Alignment via Ex-Ante Reasoning Preference Optimization](https://arxiv.org/abs/2504.02725)|arxiv|04/06, 2025|alignment|-|
|[STAR-1: Safer Alignment of Reasoning LLMs with 1K Data](https://arxiv.org/abs/2504.01903)|arxiv|04/02, 2025|alignment|-|
|[ShieldAgent: Shielding Agents via Verifiable Safety Policy Reasoning](https://arxiv.org/abs/2503.22738)|ICML 2025|03/26, 2025|guardrail model|[Github](https://shieldagent-aiguard.github.io/)|
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
|[Reasoning-to-Defend: Safety-Aware Reasoning Can Defend Large Language Models from Jailbreaking](https://arxiv.org/html/2502.12970v1)|arxiv|02/18, 2025|alignment|-|
|[H-CoT: Hijacking the Chain-of-Thought Safety Reasoning Mechanism to Jailbreak Large Reasoning Models, Including OpenAI o1/o3, DeepSeek-R1, and Gemini 2.0 Flash Thinking](https://arxiv.org/abs/2502.12893v1)|arxiv|02/18, 2025|jailbreak attack|-|
|[Safechain: Safety of language models with long chain-of-thought reasoning capabilities](https://arxiv.org/abs/2502.12025)|arxiv|02/17, 2025|alignment|-|
|[Safety Reasoning with Guidelines](https://arxiv.org/abs/2502.04040v2)|ICML 2025|02/06, 2025|alignment|
|[STAIR: Improving Safety Alignment with Introspective Reasoning](https://arxiv.org/abs/2502.02384)|arxiv|02/04, 2025|alignment|-|
|[Adversarial Reasoning at Jailbreaking Time](https://arxiv.org/abs/2502.01633)|arxiv|02/03, 2025|Jailbreak with CoT|-|
|[The dark deep side of DeepSeek: Fine-tuning attacks against the safety alignment of CoT-enabled models](https://arxiv.org/abs/2502.01225)|arxiv|02/03, 2025|finetuning attack|-|
|[o3-mini vs DeepSeek-R1: Which One is Safer?](https://arxiv.org/abs/2501.18438v1)|arxiv|01/30, 2025|jailbreak evaluation|-|
|[GuardReasoner: Towards Reasoning-based LLM Safeguards](https://arxiv.org/abs/2501.18492)|arxiv|01/30, 2025|defense|-|
|[Challenges in Ensuring AI Safety in DeepSeek-R1 Models: The Shortcomings of Reinforcement Learning Strategies](https://arxiv.org/pdf/2501.17030)|arxiv|01/28, 2025|safety evaluation|-|
|[Alignment faking in large language models](https://arxiv.org/abs/2412.14093)|arxiv|12/19, 2024|alignment|-|
|[Backtracking Improves Generation Safety](https://arxiv.org/abs/2409.14586)|ICLR 2025 Oral|09/22, 2024|defense|-|
|[GuardAgent: Safeguard LLM Agents by a Guard Agent via Knowledge-Enabled Reasoning](https://arxiv.org/abs/2406.09187)|ICML 2025|06/13, 2024|guardrail model|[Github](https://guardagent.github.io/)|
|[$R^2$-Guard: Robust Reasoning Enabled LLM Guardrail via Knowledge-Enhanced Logical Reasoning](https://arxiv.org/abs/2407.05557)|ICLR 2025 spotlight|06/08, 2024|Guardrail model|[Github](https://github.com/kangmintong/R-2-Guard)|

</details>

### Prompt injection
<details>
<summary>Click to expand the paper list</summary>

|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Practical Reasoning Interruption Attacks on Reasoning Large Language Models](https://arxiv.org/abs/2505.06643)|arxiv|05/10, 2025|prompt injection attack|-|
|[Token-Efficient Prompt Injection Attack: Provoking Cessation in LLM Reasoning via Adaptive Token Compression](https://arxiv.org/abs/2504.20493)|arxiv|04/29, 2025|prompt injection attack|-|
|[Harnessing Chain-of-Thought Metadata for Task Routing and Adversarial Prompt Detection](https://arxiv.org/abs/2503.21464)|arxiv|03/27, 2025|prompt injection defense|-|

</details>

### Poisoning

<details>
<summary>Click to expand the paper list</summary>

|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[GUARD:Dual-Agent based Backdoor Defense on Chain-of-Thought in Neural Code Generation](https://arxiv.org/abs/2505.21425)|arxiv|05/27, 2025|backdoor defense|-|
|[Chain-of-Thought Poisoning Attacks against R1-based Retrieval-Augmented Generation Systems](https://arxiv.org/abs/2505.16367)|arxiv|05/22, 2025|poisoning attacks|-|
|[System Prompt Poisoning: Persistent Attacks on Large Language Models Beyond User Injection](https://www.arxiv.org/abs/2505.06493)|arxiv|05/10, 2025|prompt poisoning|-|
|[To Think or Not to Think: Exploring the Unthinking Vulnerability in Large Reasoning Models](https://arxiv.org/abs/2502.12202)|arxiv|02/16, 2025|backdoor attack|[Github](https://github.com/zihao-ai/unthinking_vulnerability)|
|[Chain-of-Scrutiny: Detecting Backdoor Attacks for Large Language Models](https://arxiv.org/abs/2406.05948)|arxiv|12/20, 2024|backdoor defense|-|
|[BadChain: Backdoor Chain-of-Thought Prompting for Large Language Models](https://arxiv.org/abs/2401.12242)|arxiv|01/20, 2024|backdoor attack|-|
</details>

### Persuation
<details>
<summary>Click to expand the paper list</summary>

|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Persuasion and Safety in the Era of Generative AI](https://arxiv.org/abs/2505.12248)|arxiv|05/18, 2025|study|-|
</details>

## Robustness: input perturbation, overthinking/underthinking
### Input perturbation
<details>
<summary>Click to expand the paper list</summary>

|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[An Empirical Study of LLM-as-a-Judge: How Design Choices Impact Evaluation Reliability](https://arxiv.org/abs/2506.13639)|arxiv|06/16, 2025|LLM-as-a-judge|-|
|[Reasoning Models Are More Easily Gaslighted Than You Think](https://arxiv.org/abs/2506.09677)|arxiv|06/11, 2025|misleading inputs|-|
|[Chain-of-Code Collapse: Reasoning Failures in LLMs via Adversarial Prompting in Code Generation](https://arxiv.org/abs/2506.06971)|arxiv|06/07, 2025|adversarial prompting|[Github](https://github.com/jrohsc/Chain-of-Code-Collapse)|
|[CodeCrash: Stress Testing LLM Reasoning under Structural and Semantic Perturbations](https://arxiv.org/abs/2504.14119)|arxiv|05/23, 2025|adversarial attack|[GitHub](https://cuhk-arise.github.io/CodeCrash)|
|[Chain-of-Defensive-Thought: Structured Reasoning Elicits Robustness in Large Language Models against Reference Corruption](https://arxiv.org/abs/2504.20769)|arxiv|04/29, 2025|adversarial defense|-|
|[Assessing Judging Bias in Large Reasoning Models: An Empirical Study](https://arxiv.org/abs/2504.09946)|arxiv|04/18, 2025|bias|-|
|[Recitation over Reasoning: How Cutting-Edge Language Models Can Fail on Elementary School-Level Reasoning Problems?](https://arxiv.org/abs/2504.00509)|arxiv|04/01, 2025|recitation|[Huggingface](https://huggingface.co/datasets/kaiyan289/RoR-Bench)|
|[Process or Result? Manipulated Ending Tokens Can Mislead Reasoning LLMs to Ignore the Correct Reasoning Steps](https://arxiv.org/abs/2503.19326)|arxiv|03/25, 2025|token manipulation|-|
|[A Frustratingly Simple Yet Highly Effective Attack Baseline: Over 90% Success Rate Against the Strong Black-box Models of GPT-4.5/4o/o1](https://arxiv.org/abs/2503.10635)|arxiv|03/13, 2025|adversarial attack|[Github](https://github.com/VILA-Lab/M-Attack)|
|[Benchmarking Reasoning Robustness in Large Language Models](https://arxiv.org/abs/2503.04550)|arxiv|03/06, 2025|evaluation|-|
|[Cats Confuse Reasoning LLM: Query Agnostic Adversarial Triggers for Reasoning Models](https://arxiv.org/abs/2503.01781)|arxiv|03/03, 2025|adversarial attack|[Huggingface](https://huggingface.co/datasets/collinear-ai/cat-attack-adversarial-triggers)|
|[A Closer Look at System Prompt Robustness](https://arxiv.org/abs/2502.12197)|arxiv|02/15, 2025|system prompt robustness|-|
|[Trading Inference-Time Compute for Adversarial Robustness](https://arxiv.org/abs/2501.18841)|arxiv|01/31, 2025|input perturbation|-|
|[Understanding the Dark Side of LLMs' Intrinsic Self-Correction](https://arxiv.org/abs/2412.14959)|arxiv|12/19, 2024|self reflection|[Github](https://github.com/qingjiesjtu/USC)|
|[Stepwise Reasoning Disruption Attack of LLMs](https://arxiv.org/pdf/2412.11934)|arxiv|12/16, 2025|reasoning disruption|[Github](https://github.com/Applied-Machine-Learning-Lab/SEED-Attack)|
|[Can Language Models Perform Robust Reasoning in Chain-of-thought Prompting with Noisy Rationales?](https://arxiv.org/abs/2410.23856)|arxiv|10/31, 2024|input perturbation|[Github](https://github.com/tmlr-group/NoisyRationales)|
|[RUPBench: Benchmarking Reasoning Under Perturbations for Robustness Evaluation in Large Language Models](https://arxiv.org/abs/2406.11020)|arxiv|06/16, 2024|benchmark|[Github](https://github.com/EternityYW/RUPBench)|
|[Preemptive Answer "Attacks" on Chain-of-Thought Reasoning](https://arxiv.org/abs/2405.20902)|Findings of ACL 2024|05/31, 2024|preemptive attack|-|
</details>

### Overthinking/underthinking
<details>
<summary>Click to expand the paper list</summary>

|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Excessive Reasoning Attack on Reasoning LLMs](https://arxiv.org/abs/2506.14374)|arxiv|06/17, 2025|overthinking  attack|-|
|[ThinkEdit: Interpretable Weight Editing to Mitigate Overly Short Thinking in Reasoning Models](https://arxiv.org/abs/2503.22048)|arxiv|06/06, 2025|underthink|[Github](https://github.com/Trustworthy-ML-Lab/ThinkEdit)|
|[Large Language Models Struggle with Unreasonability in Math Problems](https://arxiv.org/abs/2403.19346)|arxiv|06/01, 2025|overthinking|-|
|[Mitigating Overthinking in Large Reasoning Models via Manifold Steering](https://arxiv.org/abs/2505.22411)|arxiv|05/28, 2025|overthinking|-|
|[Internal Bias in Reasoning Models leads to Overthinking](https://arxiv.org/abs/2505.16448)|arxiv|05/22, 2025|overthinking|-|
|[Between Underthinking and Overthinking: An Empirical Study of Reasoning Length and correctness in LLMs](https://arxiv.org/pdf/2505.00127)|arxiv|04/30, 2025|length and correctness|-|
|[TRACE Back from the Future: A Probabilistic Reasoning Approach to Controllable Language Generation](https://arxiv.org/abs/2504.18535)|arxiv|04/28, 2025|thought control|-|
|[Steering the CensorShip: Uncovering Representation Vectors for LLM "Thought" Control](https://arxiv.org/abs/2504.17130)|arxiv|04/23, 2025|thought control|-|
|[Missing Premise exacerbates Overthinking: Are Reasoning Models losing Critical](https://arxiv.org/abs/2504.06514)|arxiv|04/11, 2025|overthinking|-|
|[Trade-offs in Large Reasoning Models: An Empirical Analysis of Deliberative and Adaptive Reasoning over Foundational Capabilities](https://arxiv.org/abs/2503.17979)|arxiv|03/23, 2025|reasoning length analysis|-|
|[DNA Bench: When Silence is Smarter --Benchmarking Over-Reasoning in Reasoning LLMs](https://arxiv.org/abs/2503.15793)|arxiv|03/19, 2025|overthinking evaluation|-|
|[Output Length Effect on DeepSeek-R1's Safety in Forced Thinking](https://arxiv.org/abs/2503.01923)|arxiv|03/02, 2025|length analysis|-|
|[Can Large Language Models Detect Errors in Long Chain-of-Thought Reasoning?](https://arxiv.org/abs/2502.19361)|NeurIPS 2024|02/27, 2025|self reflection|[Github](https://github.com/OpenStellarTeam/DeltaBench)|
|[Thoughts Are All Over the Place: On the Underthinking of o1-Like LLMs](https://arxiv.org/pdf/2501.18585)|arxiv|05/18, 2025|underthinking analysis|-|
|[The Danger of Overthinking: Examining the Reasoning-Action Dilemma in Agentic Tasks](https://arxiv.org/abs/2502.08235)|arxiv|02/12, 2025|overthinking risk|[Github](https://github.com/AlexCuadron/Overthinking)|
|[OverThink: Slowdown Attacks on Reasoning LLMs](https://arxiv.org/abs/2502.02542v2)|arxiv|02/04, 2025|overthink attack|[Github](https://github.com/akumar2709/OVERTHINK_public)|
</details>

## Privacy and fingerprint

<details>
<summary>Click to expand the paper list</summary>

|Title|Venue|Date|topic|Code|
|:------:|:-----:|:-----:|:-----:|:----:|
|[Leaky Thoughts: Large Reasoning Models Are Not Private Thinkers](https://arxiv.org/abs/2506.15674)|arxiv|06/18, 2025|privacy leakage|[Github](https://github.com/parameterlab/leaky_thoughts)|-|
|[Reasoning Model Unlearning: Forgetting Traces, Not Just Answers, While Preserving Reasoning Skills](https://arxiv.org/abs/2506.12963)|arxiv|06/15, 2025|unlearning|[Github](https://github.com/OPTML-Group/Unlearn-R2MU)|
|[Step-by-Step Reasoning Attack: Revealing 'Erased' Knowledge in Large Language Models](https://www.arxiv.org/abs/2506.17279)|arxiv|06/14, 2025|unlearning attack|-|
|[Towards Copyright Protection for Knowledge Bases of Retrieval-augmented Language Models via Reasoning](https://arxiv.org/abs/2502.10440)|arxiv|05/23, 2025|copyright protection|-|
|[CoTSRF: Utilize Chain of Thought as Stealthy and Robust Fingerprint of Large Language Models](https://arxiv.org/abs/2505.16785)|arxiv|05/22, 2025|fingerprint|-|
|[R-TOFU: Unlearning in Large Reasoning Models](https://arxiv.org/abs/2505.15214)|arxiv|05/21, 2025|unlearning|-|
|[ImF: Implicit Fingerprint for Large Language Model](https://arxiv.org/abs/2503.21805)|arxiv|05/17, 2025|fingerprint|-|
|[Doxing via the Lens: Revealing Privacy Leakage in Image Geolocation for Agentic Multi-Modal Large Reasoning Model](https://arxiv.org/abs/2504.19373)|arxiv|04/29, 2025|privacy leakage|-|
|[Antidistillation Sampling](https://arxiv.org/abs/2504.13146)|arxiv|04/17, 2025|model distillation defense|-|
</details>

## Fairness
<details>
<summary>Click to expand the paper list</summary>

|Title|Venue|Date|topic|Code|
|:------:|:-----:|:-----:|:-----:|:----:|
|[Persona-Assigned Large Language Models Exhibit Human-Like Motivated Reasoning](https://arxiv.org/abs/2506.20020)|arxiv|06/24, 2025|persona bias|-|
|[Detection, Classification, and Mitigation of Gender Bias in Large Language Models](https://arxiv.org/abs/2506.12527)|arxiv|06/14, 2025|gender bias|-|
|[BiasGuard: A Reasoning-enhanced Bias Detection Tool For Large Language Models](https://arxiv.org/abs/2504.21299)|arxiv|06/10, 2025|bias detection|-|
|[Assessing Dialect Fairness and Robustness of Large Language Models in Reasoning Tasks](https://arxiv.org/abs/2410.11005)|arxiv|06/09, 2025|dialect fairness|[Github](https://github.com/fangru-lin/redial_dialect_robustness_fairness)|
|[Prompting techniques for reducing social bias in LLMs through system 1 and system 2 cognitive processes](https://arxiv.org/abs/2404.17218)|arxiv|04/26, 2024|social bias|[Github](https://github.com/kamruzzaman15/Reduce-Social-Bias-in-LLMs)|
|[Bias Runs Deep: Implicit Reasoning Biases in Persona-Assigned LLMs](https://arxiv.org/abs/2311.04892)|ICLR 2024|11/08, 2023|reasoning bias|[Project](https://allenai.github.io/persona-bias/)|
|[Human-like intuitive behavior and reasoning biases emerged in large language models but disappeared in chatgpt](https://www.nature.com/articles/s43588-023-00527-x)|Nature Computational Science|10/05, 2023|reasoning bias|-|
</details>

## Related surveys and benchmarks
<details>
<summary>Click to expand the paper list</summary>

|Title|Venue|Date|topic|Code|
|:-----:|:-----:|:-----:|:-----:|:----:|
|[FORTRESS: Frontier Risk Evaluation for National Security and Public Safety](https://arxiv.org/abs/2506.14922)|arxiv|06/24, 2025|safety evaluation|[Huggingface](https://huggingface.co/datasets/ScaleAI/fortress_public)|
|[IS-Bench: Evaluating Interactive Safety of VLM-Driven Embodied Agents in Daily Household Tasks](https://arxiv.org/abs/2506.16402)|arxiv|06/19, 2025|agent safety benchmark|-|
|[AbstentionBench: Reasoning LLMs Fail on Unanswerable Questions](https://arxiv.org/abs/2506.09038)|arxiv|06/10,2025|unanswerable benchmark|[Github](https://github.com/facebookresearch/AbstentionBench)|
|[PuzzleWorld: A Benchmark for Multimodal, Open-Ended Reasoning in Puzzlehunts](https://arxiv.org/abs/2506.06211)|arxiv|06/06, 2025|multi-modal open-ended reasoning benchmark|[Github](https://github.com/MIT-MI/PuzzleWorld)|
|[Beyond Safe Answers: A Benchmark for Evaluating True Risk Awareness in Large Reasoning Models](https://arxiv.org/abs/2505.19690)|arxiv|05/26, 2025|evaluation|[Github](https://github.com/OpenStellarTeam/BSA)|
|[Evaluation Faking: Unveiling Observer Effects in Safety Evaluation of Frontier AI Systems](https://arxiv.org/abs/2505.17815)|arxiv|05/23, 2025|evaluation benchmark|-|
|[A Survey of Slow Thinking-based Reasoning LLMs using Reinforced Learning and Inference-time Scaling Law](https://arxiv.org/abs/2505.02665)|arxiv|05/08, 2025|general survey|-|
|[100 Days After DeepSeek-R1: A Survey on Replication Studies and More Directions for Reasoning Language Models](https://arxiv.org/abs/2505.00551)|arxiv|05/02, 2025|r1 replication|-|
|[PolyMath: Evaluating Mathematical Reasoning in Multilingual Contexts](https://arxiv.org/abs/2504.18428)|arxiv|04/28, 2025|multilingual math performance|-|
|[Safety in Large Reasoning Models: A Survey](https://arxiv.org/abs/2504.17704)|arxiv|04/25, 2025|safety|-|
|[Harnessing the Reasoning Economy: A Survey of Efficient Reasoning for Large Language Models](https://arxiv.org/abs/2503.24377)|arxiv|03/31, 2025|efficient reasoning|-|
|[Challenging the Boundaries of Reasoning: An Olympiad-Level Math Benchmark for Large Language Models](https://arxiv.org/abs/2503.21380)|arxiv|03/28, 2025|math performance|-|

</details>

## Other related studies

<details>
<summary>Click to expand the paper list</summary>

[Understanding LLM Scientific Reasoning through Promptings and Model's Explanation on the Answers](https://arxiv.org/abs/2505.01482) (05/01, 2025)

[Moral Reasoning Across Languages: The Critical Role of Low-Resource Languages in LLMs](https://arxiv.org/abs/2504.19759) (04/28, 2025)

[How Effective Is Constitutional AI in Small LLMs? A Study on DeepSeek-R1 and Its Peers](https://arxiv.org/abs/2503.17365) (02/01, 2025)

[Building Trustworthy AI: Transparent AI Systems via Large Language Models, Ontologies, and Logical Reasoning (TranspNet)](https://arxiv.org/abs/2411.08469) (12/18, 2024)

[Anchoring Bias in Large Language Models: An Experimental Study](https://arxiv.org/abs/2412.06593) (12/18, 2024)

[Alignment faking in large language models](https://arxiv.org/abs/2412.14093) (12/19, 2024)

[Answer, Refuse, or Guess? Investigating Risk-Aware Decision-Making in Language Models](https://arxiv.org/abs/2503.01332) (03/03, 2025)

[Safety Guardrails for LLM-Enabled Robots](https://arxiv.org/abs/2503.07885) (03/10, 2025)

[Towards Efficient and Explainable Hate Speech Detection via Model Distillation](https://arxiv.org/abs/2412.13698) (12/18, 2024)

[Causal Prompting: Debiasing Large Language Model Prompting based on Front-Door Adjustment](https://arxiv.org/abs/2403.02738) (12/17, 2024)

[Collab: Controlled Decoding using Mixture of Agents for LLM Alignment](https://arxiv.org/abs/2503.21720) (03/27, 2025)

[AgentSpec: Customizable Runtime Enforcement for Safe and Reliable LLM Agents](https://arxiv.org/abs/2503.18666) (03/24, 2025)

[DeepSeek-R1 Thoughtology: Let's think about LLM Reasoning](https://arxiv.org/abs/2504.07128) (04/02, 2025)

[Modular Machine Learning: An Indispensable Path towards New-Generation Large Language Models](https://arxiv.org/abs/2504.20020) (04/29, 2025)

[AegisLLM: Scaling Agentic Systems for Self-Reflective Defense in LLM Security](https://arxiv.org/abs/2504.20965) (04/29, 2025)

[Don't Take Things Out of Context: Attention Intervention for Enhancing Chain-of-Thought Reasoning in Large Language Models](https://arxiv.org/abs/2503.11154) (03/14, 2025)


[The Steganographic Potentials of Language Models](https://arxiv.org/abs/2505.03439) (05/06, 2025)


[Towards Zero-Shot Differential Morphing Attack Detection with Multimodal Large Language Models](https://arxiv.org/abs/2505.15332) (05/21, 2025)

[Deliberation on Priors: Trustworthy Reasoning of Large Language Models on Knowledge Graphs](https://arxiv.org/abs/2505.15210) (05/21, 2025)

[The Staircase of Ethics: Probing LLM Value Priorities through Multi-Step Induction to Complex Moral Dilemmas](https://arxiv.org/abs/2505.18154) (05/23, 2025)

[If Pigs Could Fly... Can LLMs Logically Reason Through Counterfactuals?](https://arxiv.org/abs/2505.22318)

[What Makes a Good Reasoning Chain? Uncovering Structural Patterns in Long Chain-of-Thought Reasoning](https://arxiv.org/abs/2505.22148)

[Give Me FP32 or Give Me Death? Challenges and Solutions for Reproducible Reasoning](https://arxiv.org/abs/2506.09501)

</details>