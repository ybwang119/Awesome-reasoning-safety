# Awesome-reasoning-safety
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/ybwang119/Awesome-reasoning-safety)
[![Last Commit](https://img.shields.io/github/last-commit/ybwang119/Awesome-reasoning-safety)](https://github.com/ybwang119/Awesome-reasoning-safety)
[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)

This repo is for the trustworthy topics in reasoning-related technique, including but not limited to attacks, defenses, studies and benchmarks related to CoT, reasoning and RL. Data are mainly from arxiv. 

<!-- ## 🚀 Our Survey

📢 **Check out our survey paper: [Title of Survey](link-to-survey)**  
We provide a comprehensive review of existing works, summarize key challenges, and point out future directions.   -->

<!-- ### 📖 Citation

If you find our survey useful, please cite it as:

```bibtex
@article{your_survey_2025,
  title   = {Your Survey Title},
  author  = {Author1 and Author2 and Author3},
  journal = {Journal/Conference Name},
  year    = {2025},
  url     = {link-to-survey}
}
```
--- -->

## 🤝 Contribute

We welcome contributions from the community! 🎉  

- Found a missing paper?  
- Have suggestions to improve this list?  

👉 Feel free to **open an [issue](../../issues)** or **submit a [pull request](../../pulls)**.  

If you like this project, don’t forget to **⭐️ star** it — it helps more people discover it! 💖  

---

## 📚Table of contents
- [Truthfulness](#truthfulness-hallucination-reasoning-faithfulness)
    - [Hallucination](#hallucination)
    - [Reasoning Faithfulness](#reasoning-faithfulness)
- [Safety](#safety-assessment-jailbreak-alignment-backdoor)
    - [Assessment](#vulnerability-assessment)
    - [Jailbreak](#jailbreak)
    - [Alignment](#alignment)
    - [Backdoor](#backdoor)
- [Robustness](#robustness-evaluation-and-attack-improvement-overthinking-underthinking)
    - [Robustness evalutaion and attack](#evaluation-and-attack)
    - [Overthinking/underthinking](#overthinking-and-underthinking)
- [Fairness](#fairness)
- [Privacy](#privacy)
- [Related surveys and benchmarks](#related-surveys-and-benchmarks)
- [Others](#other-related-studies)
---
## Truthfulness: Hallucination, reasoning faithfulness
### Hallucination

<details open>
<summary>Click to hide/show the paper list</summary>

|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Uncertainty Under the Curve: A Sequence-Level Entropy Area Metric for Reasoning LLM](https://arxiv.org/abs/2508.20384)|arxiv|08/27, 2025|hallucination study of LRM|-|
|[Quantized but Deceptive? A Multi-Dimensional Truthfulness Evaluation of Quantized LLMs](https://arxiv.org/abs/2508.19432)|arxiv|08/26, 2025|evaluation of quantized LLM|[Github](https://github.com/ClarkFu007/TruthfulnessEval/tree/main)|
|[Sycophancy under Pressure: Evaluating and Mitigating Sycophantic Bias via Adversarial Dialogues in Scientific QA](https://arxiv.org/abs/2508.13743)|arxiv|08/19, 2025|hallucination mitigation with reasoning|-|
|[Mitigating Hallucinations in Large Language Models via Causal Reasoning](https://arxiv.org/abs/2508.12495)|arxiv|08/17, 2025|hallucination mitigation with reasoning|[Github](https://github.com/MrLYG/CDCR-SFT)|
|[Hop, Skip, and Overthink: Diagnosing Why Reasoning Models Fumble during Multi-Hop Analysis](https://arxiv.org/abs/2508.04699)|arxiv|08/06, 2025|hallucination study of LRM|-|
|[ViFP: A Framework for Visual False Positive Detection to Enhance Reasoning Reliability in VLMs](https://arxiv.org/abs/2508.04201)|arxiv|08/06, 2025|hallucination mitigation with reasoning|-|
|[Trustworthy Reasoning: Evaluating and Enhancing Factual Accuracy in LLM Intermediate Thought Processes](https://arxiv.org/abs/2507.22940)|arxiv|08/02, 2025|hallucination mitigation with reasoning|-|
|[Deliberative Searcher: Improving LLM Reliability via Reinforcement Learning with constraints](https://arxiv.org/abs/2507.16727)|arxiv|07/22, 2025|calibration improvement with reasoning|-|
|[Beyond Binary Rewards: Training LMs to Reason About Their Uncertainty](https://arxiv.org/abs/2507.16806)|arxiv|07/22, 2025|calibration improvement with reasoning|-|
|[KnowRL: Exploring Knowledgeable Reinforcement Learning for Factuality](https://arxiv.org/abs/2506.19807)|arxiv|06/24, 2025|hallucination mitigation with reasoning|[Github](https://github.com/zjunlp/KnowRL)|
|[Mathematical Proof as a Litmus Test: Revealing Failure Modes of Advanced Large Reasoning Models](https://arxiv.org/abs/2506.17114)|arxiv|06/23, 2025|evaluation on math of LRM|[Github](https://github.com/guodadi/RFMDataset)|
|[Reasoning about Uncertainty: Do Reasoning Models Know When They Don't Know?](https://arxiv.org/abs/2506.18183)|arxiv|06/22, 2025|evaluation on uncertainty of LRM|-|
|[Chain-of-Thought Prompting Obscures Hallucination Cues in Large Language Models: An Empirical Evaluation](https://arxiv.org/abs/2506.17088)|arxiv|06/20, 2025|evaluation on hallucination detection|[Github](https://anonymous.4open.science/r/cot-hallu-detect)|
|[CLATTER: Comprehensive Entailment Reasoning for Hallucination Detection](https://arxiv.org/abs/2506.05243)|arxiv|06/05, 2025|evaluation on detection with reasoning|-|
|[Joint Evaluation of Answer and Reasoning Consistency for Hallucination Detection in Large Reasoning Models](https://arxiv.org/abs/2506.04832)|arxiv|06/05, 2025|evaluation on hallucination detection of LRM|[Github](https://github.com/bebr2/RACE)|
|[The Hallucination Dilemma: Factuality-Aware Reinforcement Learning for Large Reasoning Models](https://arxiv.org/abs/2505.24630)|arxiv|05/30, 2025|evaluation of LRM|-|
|[MIRAGE: Assessing Hallucination in Multimodal Reasoning Chains of MLLM](https://arxiv.org/abs/2505.24238)|arxiv|05/30, 2025|evaluation and mitigation with reaosning|-|
|[Are Reasoning Models More Prone to Hallucination?](https://arxiv.org/abs/2505.23646)|arxiv|05/29, 2025|evaluation of LRM|-|
|[More Thinking, Less Seeing? Assessing Amplified Hallucination in Multimodal Reasoning Models](https://arxiv.org/abs/2505.21523)|arxiv|05/23, 2025|evaluation of MLRM|[Project](https://mlrm-halu.github.io/)|
|[Analyzing Logical Fallacies in Large Language Models: A Study on Hallucination in Mathematical Reasoning](https://link.springer.com/chapter/10.1007/978-981-96-7071-0_12)|JSAI-isAI 2025|05/23, 2025|evaluation on math with reasoning|[Project](https://mlrm-halu.github.io/)|
|[TreeCut: A Synthetic Unanswerable Math Word Problem Dataset for LLM Hallucination Evaluation](https://arxiv.org/abs/2502.13442)|arxiv|05/20, 2025|unanswerable dataset|[GitHub](https://github.com/j-bagel/treecut-math)|
|[The Hallucination Tax of Reinforcement Finetuning](https://arxiv.org/abs/2505.13988)|arxiv|05/20, 2025|hallucination study with RL|[Huggingface](https://huggingface.co/datasets/lime-nlp/Synthetic_Unanswerable_Math)|
|[Toward Reliable Biomedical Hypothesis Generation: Evaluating Truthfulness and Hallucination in Large Language Models](https://arxiv.org/abs/2505.14599)|arxiv|05/20, 2025|hallucination detection with reasoning|[GitHub](https://github.com/Teddy-XiongGZ/TruthHypo)|
|[Detection and Mitigation of Hallucination in Large Reasoning Models: A Mechanistic Perspective](https://arxiv.org/abs/2505.12886)|arxiv|05/19, 2025|hallucination study of LRM|[Anonymous](https://anonymous.4open.science/r/repo_for_meta_hallucination)|
|[Auditing Meta-Cognitive Hallucinations in Reasoning Large Language Models](https://arxiv.org/abs/2505.13143)|arxiv|05/19, 2025|hallucination study of LRM|[Anonymous](https://anonymous.4open.science/r/repo_for_meta_hallucination)|
|[Reasoning Large Language Model Errors Arise from Hallucinating Critical Problem Features](https://arxiv.org/abs/2505.12151)|arxiv|05/17, 2025|hallucination study of LRM|-|
|[Enhancing Mathematical Reasoning in Large Language Models with Self-Consistency-Based Hallucination Detection](https://arxiv.org/abs/2504.09440)|arxiv|04/13, 2025|hallucination detection with reasoning|-|
|[Don't Let It Hallucinate: Premise Verification via Retrieval-Augmented Logical Reasoning](https://arxiv.org/abs/2504.06438)|arxiv|04/08, 2025|hallucinationn detection with reasoning|-|
|[Do Chains-of-Thoughts of Large Language Models Suffer from Hallucinations, Cognitive Biases, or Phobias in Bayesian Reasoning?](https://arxiv.org/abs/2503.15268)|arxiv|03/19, 2025|hallucination study with reasoning|-|
|[Grounded Chain-of-Thought for Multimodal Large Language Models](https://arxiv.org/abs/2503.12799)|arxiv|03/17, 2025|hallucination study with reasoning|[Github](https://github.com/DoubtedSteam/MM-GCoT)|
|[Mitigating reasoning hallucination through Multi-agent Collaborative Filtering](https://www.sciencedirect.com/science/article/pii/S0957417424025909)|ESWA 2025|03/05, 2025|hallucination mitigation with reasoning|-|
|[Think More, Hallucinate Less: Mitigating Hallucinations via Dual Process of Fast and Slow Thinking](https://arxiv.org/abs/2501.01306)|arxiv|01/02, 2025|hallucination mitigation with reasoning|-|
|[Thinking Before Looking: Improving Multimodal LLM Reasoning via Mitigating Visual Hallucination](https://arxiv.org/abs/2411.12591)|arxiv|11/15, 2024|hallucination mitigation with reasoning|[Github](https://github.com/Terry-Xu-666/visual_inference_chain)|
|[HalluMeasure: Fine-grained Hallucination Measurement Using Chain-of-Thought Reasoning](https://aclanthology.org/2024.emnlp-main.837/)|EMNLP 2024|11/12, 2024|hallucination measurement with reasoning|-|
|[FG-PRM: Fine-grained Hallucination Detection and Mitigation in Language Model Mathematical Reasoning](https://arxiv.org/abs/2410.06304)|arxiv|10/08, 2024|hallucination detection with reasoning|[Anonymous](https://anonymous.4open.science/r/FG-PRM-75BB/)|
|[CoMT: Chain-of-Medical-Thought Reduces Hallucination in Medical Report Generation](https://arxiv.org/abs/2406.11451)|arxiv|06/17, 2024|hallucination mitigation with reasoning|[Github](https://github.com/FRENKIE-CHIANG/CoMT)|

</details>

### Reasoning Faithfulness

<details open>
<summary>Click to hide/show the paper list</summary>

|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Truthful or Fabricated? Using Causal Attribution to Mitigate Reward Hacking in Explanations](https://arxiv.org/abs/2504.05294)|ICML 2025 Workshop on Actionable Interpretability|07/15, 2025|faithfulness improvement|[Github](https://github.com/PedroMLF/Reward-Hacking-in-Explanations)|
|[Teaching Models to Verbalize Reward Hacking in Chain-of-Thought Reasoning](https://arxiv.org/abs/2506.22777)|arxiv|07/13, 2025|faithfulness improvement|[Project](https://scale.com/research/verbalize_cot_reasoning)|
|[Teaching Models to Verbalize Reward Hacking in Chain-of-Thought Reasoning](https://arxiv.org/abs/2506.22777)|arxiv|06/28, 2025|faithfulness improvement|-|
|[Right Is Not Enough: The Pitfalls of Outcome Supervision in Training LLMs for Math Reasoning](https://arxiv.org/abs/2506.06877)|arxiv|06/24, 2025|faithfulness understanding|-|
|[VFaith: Do Large Multimodal Models Really Reason on Seen Images Rather than Previous Memories?](https://arxiv.org/abs/2506.11571)|arxiv|06/13, 2025|MLLM faithfulness evaluation|[Github](https://github.com/LittleCoder12345/VFaith-Bench)|
|[Teaching Large Language Models to Maintain Contextual Faithfulness via Synthetic Tasks and Reinforcement Learning](https://arxiv.org/abs/2505.16483)|arxiv|05/22, 2025|faitufulness improvement|-|
|[Measuring the Faithfulness of Thinking Drafts in Large Reasoning Models](https://arxiv.org/abs/2505.13774)|arxiv|05/20, 2025|faithfulness measurement|[Github](https://github.com/polaris-73/faithful-thinking-draft)|
|[Walk the Talk? Measuring the Faithfulness of Large Language Model Explanations](https://arxiv.org/abs/2504.14150)|arxiv|05/20, 2025|faithfulness measurement|-|
|[Reasoning Models Don’t Always Say What They Think](https://www.anthropic.com/research/reasoning-models-dont-say-think)|website|04/03, 2025|faithfulness understanding|-|
|[Reasoning Inconsistencies and How to Mitigate Them in Deep Learning](https://arxiv.org/abs/2504.02577)|arxiv|04/03, 2025|faithfulness improvement|-|
|[Landscape of Thoughts: Visualizing the Reasoning Process of Large Language Models](https://arxiv.org/abs/2503.22165)|arxiv|03/28, 2025|faithfulness understanding|[Github](https://github.com/tmlr-group/landscape-of-thoughts)|
|[Policy Frameworks for Transparent Chain-of-Thought Reasoning in Large Language Models](https://arxiv.org/abs/2503.14521)|arxiv|03/14, 2025|faithfulness improvement|-|
|[Chain-of-Thought Reasoning In The Wild Is Not Always Faithful](https://arxiv.org/abs/2503.08679)|arxiv|03/13, 2025|faithfulness understanding|-|
|[A Causal Lens for Evaluating Faithfulness Metrics](https://arxiv.org/abs/2502.18848)|arxiv|02/26, 2025|faithfulness measurement|-|
|[Measuring faithfulness of chains of thought by unlearning reasoning steps](https://arxiv.org/abs/2502.14829)|arxiv| 02/20, 2025 |faithfulness measurement|[Github](https://github.com/%20technion-cs-nlp/parametric-faithfulness)|
|[Are DeepSeek R1 And Other Reasoning Models More Faithful?](https://arxiv.org/abs/2501.08156)|ICLR 2025 Workshop|01/14, 2025|faithfulness understanding|-|
|[Graph-Guided Textual Explanation Generation Framework](https://arxiv.org/abs/2412.12318)|arxiv|12/16, 2024|faithfulness improvement|-|
|[New Faithfulness-Centric Interpretability Paradigms for Natural Language Processing](https://arxiv.org/abs/2411.17992)|arxiv|11/27, 2024|faithfulness understanding|-|
|[On the Impact of Fine-Tuning on Chain-of-Thought Reasoning](https://arxiv.org/abs/2411.15382)|arxiv|11/22, 2024|faithfulness understanding|-|
|[Causal-driven Large Language Models with Faithful Reasoning for Knowledge Question Answering](https://dl.acm.org/doi/abs/10.1145/3664647.3681263)|ACM MM 24|10/28, 2024|faithfulness improvement|-|
|[Towards Faithful Natural Language Explanations: A Study Using Activation Patching in Large Language Models](https://arxiv.org/abs/2410.14155)|arxiv|10/18, 2024|faithfulness improvement|-|
|[To Trust or Not to Trust? Enhancing Large Language Models' Situated Faithfulness to External Contexts](https://arxiv.org/abs/2410.14675)|ICLR 2024|10/18, 2024|faithfulness improvement|[Github](https://github.com/kkkevinkkkkk/situated_faithfulness)|
|[Enhancing Large Language Models' Situated Faithfulness to External Contexts](https://arxiv.org/abs/2410.14675)|arxiv|10/18, 2024|faithfulness improvement|-|
|[FLARE: Faithful Logic-Aided Reasoning and Exploration](https://arxiv.org/abs/2410.11900)|arxiv|10/14, 2024|faithfulness improvement|-|
|[CoMAT: Chain of Mathematically Annotated Thought Improves Mathematical Reasoning](https://arxiv.org/abs/2410.10336)|arxiv|10/14, 2024|faithfulness improvement|[Github](https://github.com/joshuaongg21/CoMAT)|
|[On the Hardness of Faithful Chain-of-Thought Reasoning in Large Language Models](https://arxiv.org/abs/2406.10625)|ICML 2024 Workshop|06/15, 2024|faithfulness understanding|-|
|[XPrompt:Explaining Large Language Model's Generation via Joint Prompt Attribution](https://arxiv.org/abs/2405.20404)|arxiv|05/30, 2024|faithfulness understanding|-|
|[Faithful Logical Reasoning via Symbolic Chain-of-Thought](https://arxiv.org/abs/2405.18357)|ACL 2024|05/28, 2024|faithfulness improvement|-|
|[Dissociation of Faithful and Unfaithful Reasoning in LLMs](https://arxiv.org/abs/2405.15092)|arxiv|05/23, 2024|faithfulness understanding|[Github](https://github.com/CoTErrorRecovery/CoTErrorRecovery)|
|[FiDeLiS: Faithful Reasoning in Large Language Model for Knowledge Graph Question Answering](https://arxiv.org/abs/2405.13873)|ACL 2025|05/22, 2024|faithfulness improvenment|[Github](https://github.com/Y-Sui/FiDeLiS)|
|[Faithful Reasoning over Scientific Claims](https://ojs.aaai.org/index.php/AAAI-SS/article/view/31209)|AAAI 2024|05/20, 2024|faithfulness improvement|-|
|[Towards Better Chain-of-Thought: A Reflection on Effectiveness and Faithfulness](https://arxiv.org/abs/2405.18915)|ACL 2025 Findings|05/29, 2024|faithfulness improvement|[Github](https://github.com/BugMakerzzz/better_cot)|
|[Markovian Transformers for Informative Language Modeling](https://arxiv.org/abs/2404.18988)|arxiv|04/29, 2024|faithfulness improvement|-|
|[Fact: Teaching MLLMs with Faithful, Concise and Transferable Rationales](https://arxiv.org/abs/2404.11129)|ACM MM 2024|04/17, 2024|faithfulness improvement|-|
|[Argumentative Large Language Models for Explainable and Contestable Claim Verification](https://arxiv.org/abs/2405.02079)|AAAI 2025|04/11, 2024|faithfulness improvement|[Github](https://github.com/CLArg-group/argumentative-llms)|
|[Recent Developments on Accountability and Explainability for Complex Reasoning Tasks](https://link.springer.com/chapter/10.1007/978-3-031-51518-7_9)|Springer|04/06, 2024|faithfulness improvement|-|
|[The Probabilities Also Matter: A More Faithful Metric for Faithfulness of Free-Text Explanations in Large Language Models](https://arxiv.org/abs/2404.03189)|ACL 2024|04/04, 2024|faithfulness measurement|-|
|[How Likely Do LLMs with CoT Mimic Human Reasoning?](https://arxiv.org/abs/2402.16048)|arxiv|02/25, 2024|faithfulness understanding|[Github](https://github.com/StevenZHB/CoT_Causal_Analysis)|
|[Chain-of-Thought Unfaithfulness as Disguised Accuracy](https://arxiv.org/abs/2402.14897)|TMLR|02/22, 2024|faithfulness understanding|-|
|[Making Reasoning Matter: Measuring and Improving Faithfulness of Chain-of-Thought Reasoning](https://arxiv.org/abs/2402.13950)|EMNLP 2024 Findings|02/21, 2024|faithfulness improvement|[Github](https://github.com/debjitpaul/Causal_CoT)|
|[How Interpretable are Reasoning Explanations from Prompting Large Language Models?](https://arxiv.org/abs/2402.11863)|NAACL 2024 Findings|02/19, 2024|faithfulness understanding|[Github](https://github.com/SenticNet/CoT_interpretability)|
|[FaithLM: Towards Faithful Explanations for Large Language Models](https://arxiv.org/abs/2402.04678)|EMNLP 2024 Findings|02/07, 2024|faithfulness improvement|-|
|[Faithfulness vs. Plausibility: On the (Un)Reliability of Explanations from Large Language Models](https://arxiv.org/abs/2402.04614)|arxiv|02/07, 2024|faithfulness understanding|-|
|[Reasoning on Graphs: Faithful and Interpretable Large Language Model Reasoning](https://arxiv.org/abs/2310.01061)|ICLR 2024|10/02, 2023|faithfulness improvement|[Github](https://github.com/RManLuo/reasoning-on-graphs)|
|[Measuring Faithfulness in Chain-of-Thought Reasoning](https://arxiv.org/abs/2307.13702)|arxiv|07/17, 2023|faithfulness measurement|-|
|[Question Decomposition Improves the Faithfulness of Model-Generated Reasoning](https://arxiv.org/abs/2307.11768)|arxiv|07/17, 2023|faithfulness improvement|[Github](https://github.com/anthropics/DecompositionFaithfulnessPaper)|
|[Logic-LM: Empowering Large Language Models with Symbolic Solvers for Faithful Logical Reasoning](https://arxiv.org/abs/2305.12295)|EMNLP 2023 Findings|05/20, 2023|faithfulness improvement|[Github](https://github.com/teacherpeterpan/Logic-LLM)|
|[Language Models Don’t Always Say What They Think: Unfaithful Explanations in Chain-of-Thought Prompting](https://arxiv.org/abs/2305.04388)|arxiv|05/07, 2023|faithfulness understanding|-|
|[Faithful Chain-of-Thought Reasoning](https://arxiv.org/abs/2301.13379)|IJCNLP-AACL 2023|01/31, 2023|faithfulness improvement|[Github](https://github.com/veronica320/Faithful-COT)|

</details>

## Safety: Assessment, Jailbreak, Alignment, Backdoor
### Vulnerability assessment
|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:| 
|[ORFuzz: Fuzzing the "Other Side" of LLM Safety -- Testing Over-Refusal](https://arxiv.org/abs/2508.11222)|arxiv|08/15, 2025|over-refusal evaluation|[Github](https://github.com/HotBento/ORFuzz)|
|[Safe Semantics, Unsafe Interpretations: Tackling Implicit Reasoning Safety in Large Vision-Language Models](https://arxiv.org/abs/2508.08926)|MM 2025|08/12, 2025|dataset|[Github](https://github.com/cwtpu/SSUI)|
|[Eliciting and Analyzing Emergent Misalignment in State-of-the-Art Large Language Models](https://arxiv.org/abs/2508.04196)|arxiv|08/06, 2025|content-safety evaluation|[Github](https://github.com/AIM-Intelligence/)|
|[Evaluating LLM Agent Adherence to Hierarchical Safety Principles: A Lightweight Benchmark for Probing Foundational Controllability Components](https://arxiv.org/abs/2506.02357)|ICML 2025 TAIG workshop|07/10, 2025|agenic safety evaluation|-|
|[FORTRESS: Frontier Risk Evaluation for National Security and Public Safety](https://arxiv.org/abs/2506.14922)|arxiv|06/24, 2025|safety evaluation|[Huggingface](https://huggingface.co/datasets/ScaleAI/fortress_public)|
|[Weakest Link in the Chain: Security Vulnerabilities in Advanced Reasoning Models](https://arxiv.org/abs/2506.13726)|LLMSEC 2025|06/16, 2025|content-safety evaluation|-|
|[UDora: A Unified Red Teaming Framework against LLM Agents by Dynamically Hijacking Their Own Reasoning](https://arxiv.org/abs/2503.01908)|ICML 2025|06/06, 2025|agenic safety evaluation|[Github](https://github.com/AI-secure/UDora)|
|[Beyond Safe Answers: A Benchmark for Evaluating True Risk Awareness in Large Reasoning Models](https://arxiv.org/abs/2505.19690)|arxiv|05/26, 2025|content-safety evaluation|[Github](https://github.com/OpenStellarTeam/BSA)|
|[RRTL: Red Teaming Reasoning Large Language Models in Tool Learning](https://arxiv.org/abs/2505.17106)|arxiv|05/21, 2025|tool-learning safety evaluation|-|
|[DeepSeek-R1 Thoughtology: Let's think about LLM Reasoning](https://arxiv.org/abs/2504.07128)|arxiv|04/02, 2025|content-safety evaluation|-|
|[Towards Understanding the Safety Boundaries of DeepSeek Models: Evaluation and Findings](https://arxiv.org/abs/2503.15092)|arxiv|03/19, 2025|content-safety evaluation|-|
|[Safety Evaluation and Enhancement of DeepSeek Models in Chinese Contexts](https://arxiv.org/abs/2503.16529)|arxiv|03/18, 2025|content-safety evaluation|-|
|[Red Teaming Contemporary AI Models: Insights from Spanish and Basque Perspectives](https://arxiv.org/abs/2503.10192)|arxiv|03/13, 2025|multi-lingual safety evaluation|-|
|[The Hidden Risks of Large Reasoning Models: A Safety Assessment of R1](https://arxiv.org/abs/2502.12659v3)|arxiv|02/27, 2025|content-safety evaluation|-|
|[Evaluating security risk in deepseek and other frontier reasoning models](https://blogs.cisco.com/security/evaluating-security-risk-in-deepseek-and-other-frontier-reasoning-models)|website|02/26, 2025|content-safety evaluation|-|
|[Are Smarter LLMs Safer? Exploring Safety-Reasoning Trade-offs in Prompting and Fine-Tuning](https://arxiv.org/abs/2502.09673)|arxiv|02/21, 2025|content-safety evaluation|-|
|[o3-mini vs DeepSeek-R1: Which One is Safer?](https://arxiv.org/abs/2501.18438v1)|arxiv|01/30, 2025|content-safety evaluation|-|
|[Challenges in Ensuring AI Safety in DeepSeek-R1 Models: The Shortcomings of Reinforcement Learning Strategies](https://arxiv.org/pdf/2501.17030)|arxiv|01/28, 2025|content-safety evaluation|-|
### Jailbreak
<details open>
<summary>Click to hide/show the paper list</summary>

#### Jailbreak attack

|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:| 
|[Jailbreaking Commercial Black-Box LLMs with Explicitly Harmful Prompts](https://arxiv.org/abs/2508.10390)|arxiv|08/14, 2025|jailbreak with CoT|[Github](https://github.com/AlienZhang1996/DH-CoT)|
|[The Emotional Baby Is Truly Deadly: Does your Multimodal Large Reasoning Model Have Emotional Flattery towards Humans?](https://arxiv.org/abs/2508.03986)|arxiv|08/05, 2025|multi-modal jailbreak attack|-|
|[Adversarial Manipulation of Reasoning Models using Internal Representations](https://arxiv.org/abs/2507.03167)|ICML 2025 R2-FM Workshop|07/01, 2025|White-box attack|[Github](https://github.com/ky295/reasoning-manipulation)|
|[HauntAttack: When Attack Follows Reasoning as a Shadow](https://arxiv.org/abs/2506.07031)|arxiv|06/08, 2025|jailbreak attack|-|
|[Revealing the Intrinsic Ethical Vulnerability of Aligned Large Language Models](https://arxiv.org/abs/2504.05050)|arxiv|05/26, 2025|jailbreak attack|-|
|[VisCRA: A Visual Chain Reasoning Attack for Jailbreaking Multimodal Large Language Models](https://arxiv.org/abs/2505.19684)|arxiv|05/26, 2025|jailbreak MLRM|-|
|[Does Chain-of-Thought Reasoning Really Reduce Harmfulness from Jailbreaking?](https://arxiv.org/abs/2505.17650)|arxiv|05/23, 2025|jailbreak analysis|-|
|[Chain-of-Lure: A Synthetic Narrative-Driven Approach to Compromise Large Language Models](https://arxiv.org/abs/2505.17519)|arxiv|05/23, 2025|jailbreak with CoT|-|
|[Three Minds, One Legend: Jailbreak Large Reasoning Model with Adaptive Stacked Ciphers](https://arxiv.org/abs/2505.16241)|arxiv|05/22, 2025|jailbreak attack|-|
|[AutoRAN: Weak-to-Strong Jailbreaking of Large Reasoning Models](https://arxiv.org/abs/2505.10846)|arxiv|05/16, 2025|jailbreak attack|[Github](https://github.com/JACKPURCELL/AutoRAN-public)|
|[When "Competency" in Reasoning Opens the Door to Vulnerability: Jailbreaking LLMs via Novel Complex Ciphers](https://arxiv.org/abs/2402.10601)|arxiv|03/16, 2025|jailbreak with CoT|[Github](https://github.com/DivijH/jailbreak_cryptography)|  
|[Reasoning-Augmented Conversation for Multi-Turn Jailbreak Attacks on Large Language Models](https://arxiv.org/abs/2502.11054)|arxiv|03/11, 2025|jailbreak with CoT|-|
|[A Mousetrap: Fooling Large Reasoning Models for Jailbreak with Chain of Iterative Chaos](https://arxiv.org/abs/2502.15806)|arxiv|02/19, 2025|jailbreak attack|-|
|[H-CoT: Hijacking the Chain-of-Thought Safety Reasoning Mechanism to Jailbreak Large Reasoning Models, Including OpenAI o1/o3, DeepSeek-R1, and Gemini 2.0 Flash Thinking](https://arxiv.org/abs/2502.12893v1)|arxiv|02/18, 2025|jailbreak attack|-|
|[Adversarial Reasoning at Jailbreaking Time](https://arxiv.org/abs/2502.01633)|arxiv|02/03, 2025|jailbreak with CoT|-|
|[The dark deep side of DeepSeek: Fine-tuning attacks against the safety alignment of CoT-enabled models](https://arxiv.org/abs/2502.01225)|arxiv|02/03, 2025|finetuning attack|-|

#### Jailbreak defense
|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[IntentionReasoner: Facilitating Adaptive LLM Safeguards through Intent Reasoning and Selective Query Refinement](https://arxiv.org/abs/2508.20151)|arxiv|08/27, 2025|guardrail model|-|
|[Pragmatic Inference Chain (PIC) Improving LLMs' Reasoning of Authentic Implicit Toxic Language](https://arxiv.org/abs/2503.01539)|arxiv|08/21, 2025|toxicity detection with CoT|-|
|[Turning Logic Against Itself : Probing Model Defenses Through Contrastive Questions](https://arxiv.org/abs/2501.01872)|arxiv|08/08, 2025|Jailbreak defense|[Github](https://github.com/UKPLab/arxiv2025-poate-attack)|
|[ReasoningGuard: Safeguarding Large Reasoning Models with Inference-time Safety Aha Moments](https://arxiv.org/abs/2508.04204)|arxiv|08/06, 2025|guardrail model|-|
|[SafeAgent: Safeguarding LLM Agents via an Automated Risk Simulator](https://arxiv.org/abs/2505.17735)|arxiv|07/18, 2025|agenic safety|[project](https://auto-safe.github.io/)|
|[Can We Predict Alignment Before Models Finish Thinking? Towards Monitoring Misaligned Reasoning Models](https://arxiv.org/abs/2507.12428)|arxiv|07/16, 2025|CoT Monitor|-|
|[Chain of Thought Monitorability: A New and Fragile Opportunity for AI Safety](https://arxiv.org/abs/2507.11473)|arxiv|07/15, 2025|CoT Monitor|-|
|[When Chain of Thought is Necessary, Language Models Struggle to Evade Monitors](https://arxiv.org/abs/2507.05246)|arxiv|07/07, 2025|CoT Monitor|-|
|[AgentBreeder: Mitigating the AI Safety Impact of Multi-Agent Scaffolds via Self-Improvement](https://arxiv.org/abs/2502.00757)|ICLR 2025|06/25, 2025|Agentic safety|[Github](https://github.com/J-Rosser-UK/AgentBreeder)|
|[Detecting Harmful Memes with Decoupled Understanding and Guided CoT Reasoning](https://arxiv.org/abs/2506.08477)|arxiv|06/10, 2025|harmful meme detection|[Link](https://anonymous.4open.science/r/HMC-AF2B)|
|[RSafe: Incentivizing proactive reasoning to build robust and adaptive LLM safeguards](https://arxiv.org/abs/2506.07736)|arxiv|06/09, 2025|guardrail model|[Github](https://github.com/SophieZheng998/RSafe)|
|[Safety Through Reasoning: An Empirical Study of Reasoning Guardrail Models](https://arxiv.org/abs/2505.20087)|arxiv|05/26, 2025|guardrail model|-|
|[ReasoningShield: Content Safety Detection over Reasoning Traces of Large Reasoning Models](https://arxiv.org/abs/2505.17244)|arxiv|05/22, 2025|Guardrail model|[Github](https://github.com/CosmosYi/ReasoningShield)|
|[J4R: Learning to Judge with Equivalent Initial State Group Relative Policy Optimization](https://arxiv.org/abs/2505.13346)|arxiv|05/20, 2025|LLM-as-a-judge|[Github](https://github.com/SalesforceAIResearch/ReasoningJudgeBench)|
|[ShieldVLM: Safeguarding the Multimodal Implicit Toxicity via Deliberative Reasoning with LVLMs](https://arxiv.org/abs/2505.14035)|arxiv|05/20, 2025|guardrail model|-|
|[GuardReasoner-VL: Safeguarding VLMs via Reinforced Reasoning](https://arxiv.org/abs/2505.11049)|arxiv|05/16, 2025|guardrail model|-|[Github](https://github.com/yueliu1999/GuardReasoner-VL)|
|[On the Robustness of Reward Models for Language Model Alignment](https://arxiv.org/abs/2505.07271)|arxiv|05/12, 2025|reward model|-|
|[LlamaFirewall: An open source guardrail system for building secure AI agents](https://arxiv.org/abs/2505.03574)|arxiv|05/06, 2025|Guardrail model|-|
|[MR. Guard: Multilingual Reasoning Guardrail using Curriculum Learning](https://arxiv.org/abs/2504.15241)|arxiv|04/21, 2025|Guardrail model|-|
|[VLMGuard-R1: Proactive Safety Alignment for VLMs via Reasoning-Driven Prompt Optimization](https://arxiv.org/abs/2504.12661)|arxiv|04/17, 2025|multi-modal guardrail model|-|
|[X-Guard: Multilingual guard agent for content moderation](https://arxiv.org/abs/2504.08848)|arxiv|04/11, 2025|multi-lingual guardrail model|[Github](https://github.com/UNHSAILLab/X-Guard)|
|[Steering the CensorShip: Uncovering Representation Vectors for LLM "Thought" Control](https://arxiv.org/abs/2504.17130)|arxiv|04/23, 2025|jailbreak defense study|[Github](https://github.com/hannahxchen/llm-censorship-steering)|
|[ShieldAgent: Shielding Agents via Verifiable Safety Policy Reasoning](https://arxiv.org/abs/2503.22738)|ICML 2025|03/26, 2025|guardrail model|[Github](https://shieldagent-aiguard.github.io/)|
|[GuardReasoner: Towards Reasoning-based LLM Safeguards](https://arxiv.org/abs/2501.18492)|arxiv|01/30, 2025|guardrail model|[Github](https://github.com/yueliu1999/GuardReasoner/)|
|[GuardAgent: Safeguard LLM Agents by a Guard Agent via Knowledge-Enabled Reasoning](https://arxiv.org/abs/2406.09187)|ICML 2025|06/13, 2024|guardrail model|[Project](https://guardagent.github.io/)|
|[$R^2$-Guard: Robust Reasoning Enabled LLM Guardrail via Knowledge-Enhanced Logical Reasoning](https://arxiv.org/abs/2407.05557)|ICLR 2025 spotlight|06/08, 2024|Guardrail model|[Github](https://github.com/kangmintong/R-2-Guard)|

</details>

### Alignment
|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[PRISM: Robust VLM Alignment with Principled Reasoning for Integrated Safety in Multimodality](https://arxiv.org/abs/2508.18649)|arxiv|08/25, 2025|VLM alignment with reasoning|[Github](https://github.com/SaFoLab-WISC/PRISM)|
|[Unveiling Trust in Multimodal Large Language Models: Evaluation, Analysis, and Mitigation](https://arxiv.org/abs/2508.15370)|arxiv|08/21, 2025|alignment with reasoning|-|
|[SDGO: Self-Discrimination-Guided Optimization for Consistent Safety in Large Language Models](https://arxiv.org/abs/2508.15648)|EMNLP 2025|08/21, 2025|alignment with reasoning|[Github](https://github.com/NJUNLP/SDGO)|
|[Reward-Shifted Speculative Sampling Is An Efficient Test-Time Weak-to-Strong Aligner](https://arxiv.org/abs/2508.15044)|arxiv|08/20, 2025|Inference-time alignment with TTS|-|
|[FuSaR: A Fuzzification-Based Method for LRM Safety-Reasoning Balance](https://arxiv.org/abs/2508.12897)|arxiv|08/18, 2025|alignment of LRM|[Github](https://arxiv.org/abs/2508.12897)|
|[AURA: Affordance-Understanding and Risk-aware Alignment Technique for Large Language Models](https://arxiv.org/abs/2508.06124)|arxiv|08/08, 2025|alignment with reasoning|[Github](https://github.com/sayantan11995/AURA)|
|[R1-ACT: Efficient Reasoning Model Safety Alignment by Activating Safety Knowledge](https://arxiv.org/abs/2508.00324)|arxiv|08/01, 2025|alignment of LRM|[Github](https://github.com/yeonjun-in/R1-Act)|
|[UnsafeChain: Enhancing Reasoning Model Safety via Hard Cases](https://arxiv.org/abs/2507.21652)|arxiv|07/29, 2025|alignment of LRM|[Github](https://github.com/mbzuai-nlp/UnsafeChain)|
|[SafeWork-R1: Coevolving Safety and Intelligence under the AI-45$^{\circ}$ Law](https://arxiv.org/abs/2507.18576)|arxiv|07/24, 2025|alignment of LRM|-|
|[AlphaAlign: Incentivizing Safety Alignment with Extremely Simplified Reinforcement Learning](https://arxiv.org/abs/2507.14987)|arxiv|07/20, 2025|alignment with reasoning|[Github](https://github.com/zy20031230/AlphaAlign)|
|[ARMOR: Aligning Secure and Safe Large Language Models via Meticulous Reasoning](https://arxiv.org/abs/2507.11500)|arxiv|07/14, 2025|alignment with reasoning|[Project](https://safolab-wisc.github.io/llm-armor/)|
|[Aligning Frozen LLMs by Reinforcement Learning: An Iterative Reweight-then-Optimize Approach](https://arxiv.org/abs/2506.17828)|arxiv|07/03, 2025|test-time alignment with RL|[Github](https://github.com/OptimAI-Lab/IRO)|
|[AdamMeme: Adaptively Probe the Reasoning Capacity of Multimodal Large Language Models on Harmfulness](https://arxiv.org/abs/2507.01702)|arxiv|07/02, 2025|VLM alignment with reasoning|[Github](https://github.com/Lbotirx/AdamMeme)|
|[Reasoning as an Adaptive Defense for Safety](https://arxiv.org/abs/2507.00971)|arxiv|07/01, 2025|alignment with reasoning|[Project](https://training-adaptive-reasoners-safety.github.io/)|
|[MSR-Align: Policy-Grounded Multimodal Alignment for Safety-Aware Reasoning in Vision-Language Models](https://arxiv.org/abs/2506.19257)|arxiv|06/23, 2025|multimodal alignment dataset|[Huggingface](https://huggingface.co/datasets/Leigest/MSR-Align)|
|[How Alignment Shrinks the Generative Horizon](https://arxiv.org/abs/2506.17871)|arxiv|06/21, 2025|alignment study of LRM|[Project](https://yangalan123.github.io/branching_factor/)|
|[SafeCoT: Improving VLM Safety with Minimal Reasoning](https://arxiv.org/abs/2506.08399)|arxiv|06/09, 2025|VLM alignment with reasoning|-|
|[Chasing Moving Targets with Online Self-Play Reinforcement Learning for Safer Language Models](https://arxiv.org/abs/2506.07468)|arxiv|06/09, 2025|alignment with reasoning|[Github](https://github.com/mickelliu/selfplay-redteaming)|
|[Saffron-1: Towards an Inference Scaling Paradigm for LLM Safety Assurance](https://arxiv.org/abs/2506.06444)|arxiv|06/06, 2025|alignment with reasoning|[Github](https://github.com/q-rz/saffron)|
|[Mixture of insighTful Experts (MoTE): The Synergy of Thought Chains and Expert Mixtures in Self-Alignment](https://arxiv.org/abs/2405.00557)|arxiv|06/01, 2025|alignment with reasoning|-|
|[Mitigating Deceptive Alignment via Self-Monitoring](https://arxiv.org/pdf/2505.18807)|arxiv|05/24, 2025|alignment of LRM|[Project](https://cot-monitor-plus.github.io/)|
|[SafeKey: Amplifying Aha-Moment Insights for Safety Reasoning](https://arxiv.org/pdf/2505.16186)|arxiv|05/22, 2025|alignment of LRM|[Project](https://safekeylrm.github.io/)|
|[From Evaluation to Defense: Advancing Safety in Video Large Language Models](https://arxiv.org/abs/2505.16643)|arxiv|05/22, 2025|multimodal alignment with reasoning|-|
|[How Should We Enhance the Safety of Large Reasoning Models: An Empirical Study](https://arxiv.org/abs/2505.15404)|arxiv|05/21, 2025|alignment study of LRM|[GitHub](https://github.com/thu-coai/LRM-Safety-Study)|
|[Context Reasoner: Incentivizing Reasoning Capability for Contextualized Privacy and Safety Compliance via Reinforcement Learning](https://arxiv.org/abs/2505.14585)|arxiv|05/20, 2025|alignment of LRM|-|
|[SAFEPATH: Preventing Harmful Reasoning in Chain-of-Thought via Early Alignment](https://arxiv.org/abs/2505.14667)|arxiv|05/20, 2025|alignment of LRM|[Project](https://ai-isl.github.io/safepath)|
|[Think Twice Before You Act: Enhancing Agent Behavioral Safety with Thought Correction](https://arxiv.org/abs/2505.11063)|arxiv|05/19, 2025|agent alignment with reasoning|[Huggingface](https://huggingface.co/fgdrg/Thought-Aligner-7B-v1.0)|
|[FalseReject: A Resource for Improving Contextual Safety and Mitigating Over-Refusals in LLMs via Structured Reasoning](https://arxiv.org/abs/2505.08054)|CoLM 2025|05/12, 2025|over reject mitigation with reasoning|[Project](https://false-reject.github.io/)|
|[Think in Safety: Unveiling and Mitigating Safety Alignment Collapse in Multimodal Large Reasoning Model](https://arxiv.org/abs/2505.06538)|arxiv|05/10, 2025|alignment of MLRM|[Github](https://github.com/xinyuelou/Think-in-Safety)|
|[Energy-Based Reward Models for Robust Language Model Alignment](https://arxiv.org/abs/2504.13134)|COLM 2025|04/17, 2025|reward model improvement|[Github](https://github.com/AnamikaLochab/EBRM)|
|[Monitoring Reasoning Models for Misbehavior and the Risks of Promoting Obfuscation](https://arxiv.org/abs/2503.11926)|arxiv|04/17, 2025|CoT monitor in alignment of LRM|-|
|[RealSafe-R1: Safety-Aligned DeepSeek-R1 without Compromising Reasoning Capability](https://arxiv.org/abs/2504.10081)|arxiv|04/14, 2025|alignment of LRM|[Huggingface](https://huggingface.co/RealSafe)|
|[SaRO: Enhancing LLM Safety through Reasoning-based Alignment](https://arxiv.org/abs/2504.09420)|arxiv|04/13, 2025|alignment with reasoning|[Github](https://github.com/MurrayTom/SaRO)|
|[SafeMLRM: Demystifying Safety in Multi-modal Large Reasoning Models](https://arxiv.org/abs/2504.08813)|arxiv|04/09, 2025|alignment of MLRM|[Github](https://github.com/fangjf1/OpenSafeMLRM)|
|[ERPO: Advancing Safety Alignment via Ex-Ante Reasoning Preference Optimization](https://arxiv.org/abs/2504.02725)|arxiv|04/06, 2025|alignment with reasoning|-|
|[STAR-1: Safer Alignment of Reasoning LLMs with 1K Data](https://arxiv.org/abs/2504.01903)|arxiv|04/02, 2025|alignment of LRM|[Project](https://ucsc-vlaa.github.io/STAR-1)|
|[Inverse Reinforcement Learning with Dynamic Reward Scaling for LLM Alignment](https://arxiv.org/abs/2503.18991)|arxiv|03/23, 2025|reward model improvement|-|
|[Think Before Refusal: Triggering Safety Reflection in LLMs to Mitigate False Refusal Behavior](https://arxiv.org/abs/2503.17882)|arxiv|03/22, 2025|over-reject mitigation with reasoning|-|
|[Safety is Not Only About Refusal: Reasoning-Enhanced Fine-tuning for Interpretable LLM Safety](https://arxiv.org/abs/2503.05021)|arxiv|03/06, 2025|alignment with reasoning|-|
|[Safety Tax: Safety Alignment Makes Your Large Reasoning Models Less Reasonable](https://arxiv.org/abs/2503.00555)|arxiv|03/01, 2025|alignment study of LRM|[Github](https://github.com/git-disl/Safety-Tax)|
|[Reasoning-to-Defend: Safety-Aware Reasoning Can Defend Large Language Models from Jailbreaking](https://arxiv.org/abs/2502.12970)|arxiv|02/18, 2025|alignment with reasoning|[Github](https://github.com/chuhac/Reasoning-to-Defend)|
|[Safechain: Safety of language models with long chain-of-thought reasoning capabilities](https://arxiv.org/abs/2502.12025)|arxiv|02/17, 2025|alignment of LRM|[Project](https://safe-chain.github.io/)|
|[Safety Reasoning with Guidelines](https://arxiv.org/abs/2502.04040v2)|ICML 2025|02/06, 2025|alignment with reasoning|-|
|[STAIR: Improving Safety Alignment with Introspective Reasoning](https://arxiv.org/abs/2502.02384)|arxiv|02/04, 2025|alignment with reasoning|[Github](https://github.com/thu-ml/STAIR)|
|[Enhancing Model Defense Against Jailbreaks with Proactive Safety Reasoning](https://arxiv.org/abs/2501.19180)|arxiv|01/31, 2025|alignment with reasoning|[anonymous](https://anonymous.4open.science/r/SCoT-D4D9)|
|[Backtracking Improves Generation Safety](https://arxiv.org/abs/2409.14586)|ICLR 2025 Oral|09/22, 2024|alignment with reasoning|-|

### Backdoor

<details open>
<summary>Click to hide/show the paper list</summary>

|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[SLIP: Soft Label Mechanism and Key-Extraction-Guided CoT-based Defense Against Instruction Backdoor in APIs](https://arxiv.org/abs/2508.06153)|arxiv|08/08, 2025|injection defense|[Github](https://github.com/CAU-ISS-Lab/Backdoor-Attack-Defense-LLMs/tree/main/SLIP)|
|[Defend LLMs Through Self-Consciousness](https://arxiv.org/abs/2508.02961)|KDD 2025 Workshop|08/04, 2025|injection defense|-|
|[BadReasoner: Planting Tunable Overthinking Backdoors into Large Reasoning Models for Fun or Profit](https://arxiv.org/abs/2507.18305)|arxiv|07/24, 2025|training-phase data poisoning|[Github](https://github.com/FZaKK/BadReasoner)|
|[Thought Purity: Defense Paradigm For Chain-of-Thought Attack](https://arxiv.org/abs/2507.12314)|arxiv|07/16, 2025|injection defense|-|
|[Thought Crime: Backdoors and Emergent Misalignment in Reasoning Models](https://arxiv.org/abs/2506.13206)|arxiv|06/16, 2025|Training-time
data poisoning|[Huggingface](https://huggingface.co/datasets/truthfulai/emergent_plus)|
|[GUARD:Dual-Agent based Backdoor Defense on Chain-of-Thought in Neural Code Generation](https://arxiv.org/abs/2505.21425)|arxiv|05/27, 2025|backdoor defense|[Github](https://github.com/WolfgangJin/GUARD)|
|[Chain-of-Thought Poisoning Attacks against R1-based Retrieval-Augmented Generation Systems](https://arxiv.org/abs/2505.16367)|arxiv|05/22, 2025|inference-time prompt manipulation|-|
|[System Prompt Poisoning: Persistent Attacks on Large Language Models Beyond User Injection](https://arxiv.org/abs/2505.06493)|arxiv|05/10, 2025|inference-time prompt manipulation|-|
|[Practical Reasoning Interruption Attacks on Reasoning Large Language Models](https://arxiv.org/abs/2505.06643)|arxiv|05/10, 2025|inference-time prompt manipulation|-|
|[Token-Efficient Prompt Injection Attack: Provoking Cessation in LLM Reasoning via Adaptive Token Compression](https://arxiv.org/abs/2504.20493)|arxiv|04/29, 2025|inference-time prompt manipulation|-|
|[ShadowCoT: Cognitive Hijacking for Stealthy Reasoning Backdoors in LLMs](https://arxiv.org/abs/2504.05605)|arxiv|04/08, 2025|training-phase data poisoning|-|
|[Harnessing Chain-of-Thought Metadata for Task Routing and Adversarial Prompt Detection](https://arxiv.org/abs/2503.21464)|arxiv|03/27, 2025|injection defense|-|
|[To Think or Not to Think: Exploring the Unthinking Vulnerability in Large Reasoning Models](https://arxiv.org/abs/2502.12202)|arxiv|02/16, 2025|training-phase data poisoning|[Github](https://github.com/zihao-ai/unthinking_vulnerability)|
|[DarkMind: Latent Chain-of-Thought Backdoor in Customized LLMs](https://arxiv.org/abs/2501.18617)|arxiv|01/24, 2025|inference-time prompt manipulation|-|
|[Chain-of-Scrutiny: Detecting Backdoor Attacks for Large Language Models](https://arxiv.org/abs/2406.05948)|ACL 2025 Findings|12/20, 2024|backdoor defense|-|
|[SABER: Model-agnostic Backdoor Attack on Chain-of-Thought in Neural Code Generation](https://arxiv.org/abs/2412.05829)|arxiv|12/08, 2025|training-phase data poisoning|-|
|[BadChain: Backdoor Chain-of-Thought Prompting for Large Language Models](https://arxiv.org/abs/2401.12242)|ICLR 2024|01/20, 2024|inference-time prompt manipulation|-|
</details>

## Robustness: evaluation and attack, improvement, overthinking, underthinking
### Evaluation and attack
<details open>
<summary>Click to hide/show the paper list</summary>

|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Measuring Sycophancy of Language Models in Multi-turn Dialogues](https://arxiv.org/abs/2505.23840)|arxiv|08/25, 2025|sycophancy evaluation|[Github](https://github.com/JiseungHong/SYCON-Bench)|
|[Refining Critical Thinking in LLM Code Generation: A Faulty Premise-based Evaluation Framework](https://arxiv.org/abs/2508.03622)|arxiv|08/05, 2025|evaluation on code|-|
|[MoHoBench: Assessing Honesty of Multimodal Large Language Models via Unanswerable Visual Questions](https://arxiv.org/abs/2507.21503)|arxiv|07/29, 2025|evaluation on unanswerable question|[Github](https://github.com/DSTTSD/MoHoBench)|
|[When LLMs Copy to Think: Uncovering Copy-Guided Attacks in Reasoning LLMs](https://arxiv.org/abs/2507.16773)|arxiv|07/22, 2025|adversarial attack|-|
|[Reasoning Models Are More Easily Gaslighted Than You Think](https://arxiv.org/abs/2506.09677)|arxiv|06/11, 2025|evaluation on misleading inputs|-|
|[AbstentionBench: Reasoning LLMs Fail on Unanswerable Questions](https://arxiv.org/abs/2506.09038)|arxiv|06/10,2025|evaluation on unanswerable question|[Github](https://github.com/facebookresearch/AbstentionBench)|
|[Chain-of-Code Collapse: Reasoning Failures in LLMs via Adversarial Prompting in Code Generation](https://arxiv.org/abs/2506.06971)|arxiv|06/07, 2025|evaluation on adversarial prompting|[Github](https://github.com/jrohsc/Chain-of-Code-Collapse)|
|[Hidden in Plain Sight: Reasoning in Underspecified and Misspecified Scenarios for Multimodal LLMs](https://arxiv.org/abs/2506.00258)|arxiv|05/30, 2025|Failure analysis|-|
|[CodeCrash: Stress Testing LLM Reasoning under Structural and Semantic Perturbations](https://arxiv.org/abs/2504.14119)|arxiv|05/23, 2025|evalution on code comprehension|[GitHub](https://cuhk-arise.github.io/CodeCrash)|
|[PolyMath: Evaluating Mathematical Reasoning in Multilingual Contexts](https://arxiv.org/abs/2504.18428)|arxiv|04/28, 2025|evaluation on math|[Github](https://github .com/QwenLM/PolyMath)|
|[Process or Result? Manipulated Ending Tokens Can Mislead Reasoning LLMs to Ignore the Correct Reasoning Steps](https://arxiv.org/abs/2503.19326)|arxiv|03/25, 2025|adversarial attack|-|
|[A Frustratingly Simple Yet Highly Effective Attack Baseline: Over 90% Success Rate Against the Strong Black-box Models of GPT-4.5/4o/o1](https://arxiv.org/abs/2503.10635)|arxiv|03/13, 2025|adversarial attack|[Github](https://github.com/VILA-Lab/M-Attack)|
|[Benchmarking Reasoning Robustness in Large Language Models](https://arxiv.org/abs/2503.04550)|arxiv|03/06, 2025|evaluation|-|
|[Cats Confuse Reasoning LLM: Query Agnostic Adversarial Triggers for Reasoning Models](https://arxiv.org/abs/2503.01781)|COLM 2025|03/03, 2025|adversarial attack|[Huggingface](https://huggingface.co/datasets/collinear-ai/cat-attack-adversarial-triggers)|
|[Can Large Language Models Detect Errors in Long Chain-of-Thought Reasoning?](https://arxiv.org/abs/2502.19361)|NeurIPS 2024|02/27, 2025|evaluation on self-reflection|[Github](https://github.com/OpenStellarTeam/DeltaBench)|
|[A Closer Look at System Prompt Robustness](https://arxiv.org/abs/2502.12197)|arxiv|02/15, 2025|evaluation on system prompt|[Github](https://github.com/normster/RealGuardrails)|
|[MATH-Perturb: Benchmarking LLMs' Math Reasoning Abilities against Hard Perturbations](https://arxiv.org/abs/2502.06453)|arxiv|02/10, 2025|evaluation on math|-|
|[Understanding the Dark Side of LLMs' Intrinsic Self-Correction](https://arxiv.org/abs/2412.14959)|arxiv|12/19, 2024|self reflection study|[Github](https://github.com/qingjiesjtu/USC)|
|[Stepwise Reasoning Disruption Attack of LLMs](https://arxiv.org/pdf/2412.11934)|ACL 2025|12/16, 2024|adversarial attack|[Github](https://github.com/Applied-Machine-Learning-Lab/SEED-Attack)|
|[Can Language Models Perform Robust Reasoning in Chain-of-thought Prompting with Noisy Rationales?](https://arxiv.org/abs/2410.23856)|arxiv|10/31, 2024|evaluation on noisy rationales|[Github](https://github.com/tmlr-group/NoisyRationales)|
|[RUPBench: Benchmarking Reasoning Under Perturbations for Robustness Evaluation in Large Language Models](https://arxiv.org/abs/2406.11020)|arxiv|06/16, 2024|evaluation|[Github](https://github.com/EternityYW/RUPBench)|
|[Preemptive Answer "Attacks" on Chain-of-Thought Reasoning](https://arxiv.org/abs/2405.20902)|Findings of ACL 2024|05/31, 2024|adversarial attack|-|
</details>

### Improvement
|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Error Reflection Prompting: Can Large Language Models Successfully Understand Errors?](https://arxiv.org/abs/2508.16729)|NAACL 2025|08/22, 2025|robustness improvement|-|
|[Any Large Language Model Can Be a Reliable Judge: Debiasing with a Reasoning-based Bias Detector](https://arxiv.org/abs/2505.17100)|arxiv|05/21, 2025|LLM-as-a-judge|-|
|[Chain-of-Defensive-Thought: Structured Reasoning Elicits Robustness in Large Language Models against Reference Corruption](https://arxiv.org/abs/2504.20769)|arxiv|04/29, 2025|adversarial defense|-|
|[Assessing Judging Bias in Large Reasoning Models: An Empirical Study](https://arxiv.org/abs/2504.09946)|arxiv|04/14, 2025|bias mitigation|-|
|[Recitation over Reasoning: How Cutting-Edge Language Models Can Fail on Elementary School-Level Reasoning Problems?](https://arxiv.org/abs/2504.00509)|arxiv|04/01, 2025|robustness imporvement|[Huggingface](https://huggingface.co/datasets/kaiyan289/RoR-Bench)|
|[Trading Inference-Time Compute for Adversarial Robustness](https://arxiv.org/abs/2501.18841)|arxiv|01/31, 2025|robustness improvement|-|
|[Self-Polish: Enhance Reasoning in Large Language Models via Problem Refinement](https://arxiv.org/abs/2305.14497)|EMNLP 2023 Findings|05/23, 2023|reasoning enhancement|[Github](https://github.com/WooooDyy/Self-Polish)|
### Overthinking and underthinking
<details open>
<summary>Click to hide/show the paper list</summary>

|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Don't Think Twice! Over-Reasoning Impairs Confidence Calibration](https://arxiv.org/abs/2508.15050)|ICML 2025 Workshop|08/20, 2025|overthinking study|-|
|[OptimalThinkingBench: Evaluating Over and Underthinking in LLMs](https://arxiv.org/abs/2508.13141)|arxiv|08/18, 2025|evaluation|[Github](https://github.com/facebookresearch/RAM/tree/main/projects/otb)|
|[Excessive Reasoning Attack on Reasoning LLMs](https://arxiv.org/abs/2506.14374)|arxiv|06/17, 2025|overthinking attack|-|
|[Mitigating Overthinking in Large Reasoning Models via Manifold Steering](https://arxiv.org/abs/2505.22411)|arxiv|05/28, 2025|overthinking mitigation|-|
|[ThinkEdit: Interpretable Weight Editing to Mitigate Overly Short Thinking in Reasoning Models](https://arxiv.org/abs/2503.22048)|arxiv|05/27, 2025|underthinking mitigation|[Github](https://github.com/Trustworthy-ML-Lab/ThinkEdit)|
|[Internal Bias in Reasoning Models leads to Overthinking](https://arxiv.org/abs/2505.16448)|arxiv|05/22, 2025|overthinking study|-|
|[Between Underthinking and Overthinking: An Empirical Study of Reasoning Length and correctness in LLMs](https://arxiv.org/pdf/2505.00127)|arxiv|04/30, 2025|reasoning length study|-|
|[Missing Premise exacerbates Overthinking: Are Reasoning Models losing Critical](https://arxiv.org/abs/2504.06514)|arxiv|04/11, 2025|overthinking study|-|
|[Trade-offs in Large Reasoning Models: An Empirical Analysis of Deliberative and Adaptive Reasoning over Foundational Capabilities](https://arxiv.org/abs/2503.17979)|arxiv|03/23, 2025|reasoning length study|[Guthub](https://github.com/SCIR-SC-Qiaoban-Team/FreeEvalLM)|
|[DNA Bench: When Silence is Smarter --Benchmarking Over-Reasoning in Reasoning LLMs](https://arxiv.org/abs/2503.15793)|arxiv|03/19, 2025|overthinking evaluation|-|
|[Output Length Effect on DeepSeek-R1's Safety in Forced Thinking](https://arxiv.org/abs/2503.01923)|arxiv|03/02, 2025|reasoning length study|-|
|[The Danger of Overthinking: Examining the Reasoning-Action Dilemma in Agentic Tasks](https://arxiv.org/abs/2502.08235)|arxiv|02/12, 2025|overthinking study|[Github](https://github.com/AlexCuadron/Overthinking)|
|[OverThink: Slowdown Attacks on Reasoning LLMs](https://arxiv.org/abs/2502.02542v2)|arxiv|02/04, 2025|overthinking attack|[Github](https://github.com/akumar2709/OVERTHINK_public)|
|[Thoughts Are All Over the Place: On the Underthinking of o1-Like LLMs](https://arxiv.org/abs/2501.18585)|arxiv|01/30, 2025|underthinking study|-|
|[Large Language Models Struggle with Unreasonability in Math Problems](https://arxiv.org/abs/2403.19346)|arxiv|03/28, 2024|overthinking study|-|
</details>

## Privacy

<details open>
<summary>Click to hide/show the paper list</summary>

|Title|Venue|Date|topic|Code|
|:------:|:-----:|:-----:|:-----:|:----:|
|[Evaluating Language Model Reasoning about Confidential Information](https://arxiv.org/abs/2508.19980)|arxiv|08/27, 2025|prompt-related privacy|[Github](https://github.com/locuslab/confidential_llms)|
|[1-2-3 Check: Enhancing Contextual Privacy in LLM via Multi-Agent Reasoning](https://arxiv.org/abs/2508.07667)|arxiv|08/11, 2025|privacy improvement|-|
|[Privacy-Preserving LLM Interaction with Socratic Chain-of-Thought Reasoning and Homomorphically Encrypted Vector Databases](https://arxiv.org/abs/2506.17336)|arxiv|07/01, 2025|privacy improvement|[Github](https://github.com/Yubeen-Bae/PPMI)|
|[Leaky Thoughts: Large Reasoning Models Are Not Private Thinkers](https://arxiv.org/abs/2506.15674)|arxiv|06/18, 2025|prompt-related privacy|[Github](https://github.com/parameterlab/leaky_thoughts)|[Github](https://github.com/parameterlab/leaky_thoughts)|
|[Reasoning Model Unlearning: Forgetting Traces, Not Just Answers, While Preserving Reasoning Skills](https://arxiv.org/abs/2506.12963)|arxiv|06/15, 2025|unlearning|[Github](https://github.com/OPTML-Group/Unlearn-R2MU)|
|[Step-by-Step Reasoning Attack: Revealing 'Erased' Knowledge in Large Language Models](https://www.arxiv.org/abs/2506.17279)|arxiv|06/14, 2025|unlearning attack|-|
|[Towards Copyright Protection for Knowledge Bases of Retrieval-augmented Language Models via Reasoning](https://arxiv.org/abs/2502.10440)|arxiv|05/23, 2025|copyright protection|-|
|[CoTSRF: Utilize Chain of Thought as Stealthy and Robust Fingerprint of Large Language Models](https://arxiv.org/abs/2505.16785)|arxiv|05/22, 2025|copyright protection|-|
|[R-TOFU: Unlearning in Large Reasoning Models](https://arxiv.org/abs/2505.15214)|arxiv|05/21, 2025|unlearning|[Project](https://ai-isl.github.io/r-tofu)|
|[ImF: Implicit Fingerprint for Large Language Model](https://arxiv.org/abs/2503.21805)|arxiv|05/17, 2025|copyright protection|-|
|[Doxing via the Lens: Revealing Privacy Leakage in Image Geolocation for Agentic Multi-Modal Large Reasoning Model](https://arxiv.org/abs/2504.19373)|arxiv|04/29, 2025|prompt-related privacy|[Project](https://doxbench.github.io/)|
|[Antidistillation Sampling](https://arxiv.org/abs/2504.13146)|arxiv|04/17, 2025|copyright protection|[Project](https://antidistillation.com/https://antidistillation.com/)|
</details>

## Fairness
<details open>
<summary>Click to hide/show the paper list</summary>

|Title|Venue|Date|topic|Code|
|:------:|:-----:|:-----:|:-----:|:----:|
|[Bridging the Culture Gap: A Framework for LLM-Driven Socio-Cultural Localization of Math Word Problems in Low-Resource Languages](https://arxiv.org/abs/2508.14913)|arxiv|08/22, 2025|multi-lingual bias|-|
|[Do Biased Models Have Biased Thoughts?](https://arxiv.org/abs/2508.06671)|COLM 2025|08/08, 2025|study|-|
|[FairReason: Balancing Reasoning and Social Bias in MLLMs](https://arxiv.org/abs/2507.23067)|arxiv|07/30, 2025|fairness improvement|[Github](https://github.com/Yutongzhang20080108/FairReason-Balancing-Reasoning-and-Social-Bias-in-MLLMs)|
|[The Emperor's New Chain-of-Thought: Probing Reasoning Theater Bias in Large Reasoning Models](https://arxiv.org/abs/2507.13758)|arxiv|07/18, 2025|fairness evaluation|-|
|[Guiding LLM Decision-Making with Fairness Reward Models](https://arxiv.org/abs/2507.11344)|arxiv|07/15, 2025|fairness improvement|[Github](https://github.com/zarahall/fairness-prms)|
|[Is Reasoning All You Need? Probing Bias in the Age of Reasoning Language Models](https://arxiv.org/abs/2507.02799)|arxiv|07/03, 2025|fairness evaluation|-|
|[Persona-Assigned Large Language Models Exhibit Human-Like Motivated Reasoning](https://arxiv.org/abs/2506.20020)|arxiv|06/24, 2025|persona bias|[Github](https://github.com/ameliereymond/motivated-reasoning/)|
|[Detection, Classification, and Mitigation of Gender Bias in Large Language Models](https://arxiv.org/abs/2506.12527)|arxiv|06/14, 2025|gender bias|-|
|[Assessing Dialect Fairness and Robustness of Large Language Models in Reasoning Tasks](https://arxiv.org/abs/2410.11005)|arxiv|06/09, 2025|dialect fairness|[Github](https://github.com/fangru-lin/redial_dialect_robustness_fairness)|
|[BiasGuard: A Reasoning-enhanced Bias Detection Tool For Large Language Models](https://arxiv.org/abs/2504.21299)|ACL 2025 Findings|04/30, 2025|bias detection|-|
|[Prompting techniques for reducing social bias in LLMs through system 1 and system 2 cognitive processes](https://arxiv.org/abs/2404.17218)|arxiv|04/26, 2024|social bias|[Github](https://github.com/kamruzzaman15/Reduce-Social-Bias-in-LLMs)|
|[Bias Runs Deep: Implicit Reasoning Biases in Persona-Assigned LLMs](https://arxiv.org/abs/2311.04892)|ICLR 2024|11/08, 2023|reasoning bias|[Project](https://allenai.github.io/persona-bias/)|
|[Human-like intuitive behavior and reasoning biases emerged in large language models but disappeared in chatgpt](https://www.nature.com/articles/s43588-023-00527-x)|Nature Computational Science|10/05, 2023|reasoning bias|-|

</details>

## Related surveys and benchmarks
<details>
<summary>Click to hide/show the paper list</summary>

|Title|Venue|Date|topic|Code|
|:-----:|:-----:|:-----:|:-----:|:----:|
|[Lost in Pronunciation: Detecting Chinese Offensive Language Disguised by Phonetic Cloaking Replacement](https://arxiv.org/abs/2507.07640)|arxiv|07/10, 2025|Offensive Language detection benchmark|[Huggingface](https://huggingface.co/datasets/UTSNLPGroup/PCR-ToxiCN)|
|[Towards Understanding the Cognitive Habits of Large Reasoning Models](https://arxiv.org/abs/2506.21571)|arxiv|07/05, 2025|cognitive habits|[Github](https://github.com/jianshuod/CogTest)|
|[IS-Bench: Evaluating Interactive Safety of VLM-Driven Embodied Agents in Daily Household Tasks](https://arxiv.org/abs/2506.16402)|arxiv|06/19, 2025|agent safety benchmark|-|
|[PuzzleWorld: A Benchmark for Multimodal, Open-Ended Reasoning in Puzzlehunts](https://arxiv.org/abs/2506.06211)|arxiv|06/06, 2025|multi-modal open-ended reasoning benchmark|[Github](https://github.com/MIT-MI/PuzzleWorld)|
|[Evaluation Faking: Unveiling Observer Effects in Safety Evaluation of Frontier AI Systems](https://arxiv.org/abs/2505.17815)|arxiv|05/23, 2025|evaluation benchmark|-|
|[A Survey of Slow Thinking-based Reasoning LLMs using Reinforced Learning and Inference-time Scaling Law](https://arxiv.org/abs/2505.02665)|arxiv|05/08, 2025|general survey|-|
|[100 Days After DeepSeek-R1: A Survey on Replication Studies and More Directions for Reasoning Language Models](https://arxiv.org/abs/2505.00551)|arxiv|05/02, 2025|r1 replication|-|
|[Safety in Large Reasoning Models: A Survey](https://arxiv.org/abs/2504.17704)|arxiv|04/25, 2025|safety|-|
|[Harnessing the Reasoning Economy: A Survey of Efficient Reasoning for Large Language Models](https://arxiv.org/abs/2503.24377)|arxiv|03/31, 2025|efficient reasoning|-|
|[Challenging the Boundaries of Reasoning: An Olympiad-Level Math Benchmark for Large Language Models](https://arxiv.org/abs/2503.21380)|arxiv|03/28, 2025|math performance|-|

</details>

<!-- ## Other related studies

<details>
<summary>Click to hide/show the paper list</summary>

|Title|Venue|Date|topic|Code|
|:-----:|:-----:|:-----:|:-----:|:----:|
|[Linear Control of Test Awareness Reveals Differential Compliance in Reasoning Models](https://arxiv.org/pdf/2505.14617)|arxiv|05/20, 2025|alignment study|[GitHub](https://github.com/microsoft/Test_Awareness_Steering)|
|[Order Matters in Hallucination: Reasoning Order as Benchmark and Reflexive Prompting for Large-Language-Models](https://arxiv.org/abs/2408.05093)|arxiv|12/30, 2024|hallucination study|-|
|[Slow Tuning and Low-Entropy Masking for Safe Chain-of-Thought Distillation](https://arxiv.org/abs/2508.09666)|arxiv|08/15, 2025|safe data distillation|-|

[Corrupted by Reasoning: Reasoning Language Models Become Free-Riders in Public Goods Games](https://arxiv.org/abs/2506.23276) (06/29, 2025)

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

[Effectively Controlling Reasoning Models through Thinking Intervention](https://arxiv.org/pdf/2503.24370)

[Truth Neurons](https://arxiv.org/abs/2505.12182) (07/08, 2025)

[Defending Against Prompt Injection With a Few Defensive Tokens](https://arxiv.org/abs/2507.07974) (07/10, 2025)

[Representation Bending for Large Language Model Safety](https://arxiv.org/abs/2504.01550) (07/14, 2025)

[The Scales of Justitia: A Comprehensive Survey on Safety Evaluation of LLMs](https://arxiv.org/abs/2506.11094) (06/06, 2025)

</details>
### Persuation
<details open>
<summary>Click to hide/show the paper list</summary>

|Title|Venue|Date|topic|Code|
|:--------:|:--------:|:--------:|:--------:|:--------:|
|[It's the Thought that Counts: Evaluating the Attempts of Frontier LLMs to Persuade on Harmful Topics](https://arxiv.org/abs/2506.02873)|arxiv|08/18, 2025|evaluation|[Github](github.com/AlignmentResearch/AttemptPersuadeEval)|
|[Persuasion and Safety in the Era of Generative AI](https://arxiv.org/abs/2505.12248)|arxiv|05/18, 2025|study|-|
</details> -->
