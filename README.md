<details open="open">
<summary>Topics covered</summary>

- [About](#about)
- [Overview](#overview)
- [Techniques](#techniques)
- [Reasoning Limitations](#reasoning-limitations)
- [Benchmarks](#benchmarks)
- [Miscellaneous](#miscellaneous)
- [Additional Resources](#additional-resources)
- [Acknowledgement](#acknowledgement)
- [Contributing](#contributing)
- [Authors \& contributors](#authors--contributors)
</details>

---

## About



Welcome to the **Awesome LLMs Planning Reasoning** repository! This collection is dedicated to exploring the rapidly evolving field of Large Language Models (LLMs) and their capabilities in planning and reasoning.



## Overview

As LLMs continue to demonstrate remarkable success in Natural Language Understanding (NLU) and Natural Language Generation (NLG), researchers are increasingly interested in assessing their abilities beyond traditional NLP tasks. One of the most promising and challenging areas of study is understanding how well LLMs can perform tasks that require planning and reasoning. These capabilities are essential for leveraging LLMs in more complex, real-world scenarios, such as autonomous decision-making, problem-solving, and strategic thinking. However, recent research suggests that LLMs often struggle with reasoning tasks that are relatively simple for most humans, highlighting the limitations of these models in this critical area.

This repository is a curated list of research papers, code repositories, and benchmarks that focus on the intersection of LLMs with planning and reasoning tasks. Here, you'll find:

- **Techniques**: Innovative methods that enable LLMs to reason and plan effectively, such as Chain-of-Thought prompting and Tree of Thoughts.
- **Reasoning Limitations**: Critical investigations that explore the limitations and challenges LLMs face in planning and reasoning tasks.
- **Benchmarks**: Standardized tests and evaluations designed to measure the performance of LLMs in these complex tasks.
- **Miscellaneous Papers**: Papers related to the field of LLMs and reasoning, but not directly focused on planning tasks.
- **Additional Resources**: Supplementary materials such as slides, dissertations, and other resources that provide further insights into LLM planning and reasoning.

Whether you're a researcher, developer, or enthusiast, this repository serves as a comprehensive resource for staying updated on the latest advancements and understanding the current challenges in the domain of LLMs' planning and reasoning abilities. Dive in and explore the fascinating world where language models meet high-level cognitive tasks!



</td></tr></table>


## Techniques

| Paper | Link | Code | Venue | Date | Other |
|-------|------|------|-------|------|-------|
| Chain-of-Thought Prompting Elicits Reasoning in Large Language Models  | [arXiv](https://arxiv.org/pdf/2201.11903) | -- | NeurIPS 22 | 28 Jan 2022  | [Video](https://www.youtube.com/watch?v=NBIRzSGHFro) |
| Self-Consistency Improves Chain of Thought Reasoning in Language Models | [arXiv](https://arxiv.org/pdf/2203.11171) | -- | ICLR 23 | 7 Mar 2023 | [Video](https://www.youtube.com/watch?v=XKY2ThptBWs) |
| REACT: Synergizing Reasoning and Acting in Language Models  | [arXiv](https://arxiv.org/pdf/2210.03629) | [GitHub](https://github.com/ysymyth/ReAct) | ICLR 23 | 10 Mar 2023 | [Project](https://react-lm.github.io/) [Video](https://www.youtube.com/watch?v=QX-p-vsDoiQ) |
| Least-To-Most Prompting Enables Complex Reasoning In Large Language Models  | [arXiv](https://arxiv.org/pdf/2205.10625) | -- | ICLR 23 | 16 Apr 2023 |  |
| Chain-of-Symbol Prompting Elicits Planning in Large Language Models  | [arXiv](https://arxiv.org/pdf/2305.10276) | [GitHub](https://github.com/hanxuhu/chain-of-symbol-planning) | ICLR 24 | 17 May 2023 |   |
| Better Zero-Shot Reasoning with Role-Play Prompting  | [arXiv](https://arxiv.org/pdf/2308.07702) | [GitHub](https://github.com/NKU-HLT/Role-Play-Prompting) | NAACL 24 | 15 Aug 2023 |  |
| LLM+P: Empowering Large Language Models with Optimal Planning Proficiency  | [arXiv](https://arxiv.org/pdf/2304.11477) |  [GitHub](https://github.com/Cranial-XIX/llm-pddl)  | arXiv | 27 Sep 2023 |  |
| Reasoning with Language Model is Planning with World Model | [arXiv](https://arxiv.org/pdf/2305.14992) | [GitHub](https://github.com/Ber666/RAP) | EMNLP 23 | 23 Oct 2023  | |
| Large Language Models as Commonsense Knowledge for Large-Scale Task Planning  | [arXiv](https://arxiv.org/abs/2305.14078) |  [GitHub](https://github.com/1989Ryan/llm-mcts)  | NeurIPS 23 | 30 Oct 2023 | [Project](https://llm-mcts.github.io) |
| Tree of Thoughts: Deliberate Problem Solving with Large Language Models | [arXiv](https://arxiv.org/pdf/2305.10601) | [GitHub](https://github.com/princeton-nlp/tree-of-thought-llm) | NeurIPS 23 | 3 Dec 2023 | [Video](https://www.youtube.com/watch?v=ut5kp56wW_4) |
| Learning adaptive planning representations with natural language guidance  | [arXiv](https://arxiv.org/pdf/2312.08566) | -- | arXiv |  13 Dec 2023  |  |
| The Truth is in There: Improving Reasoning in Language Models with Layer-Selective Rank Reduction  | [arXiv](https://arxiv.org/pdf/2312.13558) | [GitHub](https://github.com/pratyushasharma/laser) | ICLR 24 |  21 Dec 2023  |  |
| Large Language Models can Learn Rules  | [arXiv](https://arxiv.org/pdf/2310.07064) | -- | arXiv |  24 Apr 2024  |  |
| What’s the Plan? Evaluating and Developing Planning-Aware Techniques for Language Models | [arXiv](https://arxiv.org/pdf/2402.11489) | -- | arXiv | 22 May 2024 |  |
| Language Agent Tree Search Unifies Reasoning, Acting, and Planning in Language Models | [arXiv](https://arxiv.org/pdf/2310.04406) | [GitHub](https://github.com/lapisrocks/LanguageAgentTreeSearch) | arxiv | 6 Jun 2024 |  |
| Large Language Models Can Learn Temporal Reasoning  | [arXiv](https://arxiv.org/pdf/2401.06853) | [GitHub](https://github.com/xiongsiheng/TG-LLM) | ACL 24 |  11 Jun 2024   |  |
| Flow of Reasoning: Efficient Training of LLM Policy with Divergent Thinking | [arXiv](https://arxiv.org/pdf/2406.05673) | [GitHub](https://github.com/Yu-Fangxu/FoR) | arXiv | 24 Jun 2024  |  |
| Tree Search for Language Model Agents | [arXiv](https://arxiv.org/pdf/2407.01476) | [GitHub](https://github.com/kohjingyu/search-agents)  | arXiv | 1 Jul 2024 | [Project](https://jykoh.com/search-agents) |
| RELIEF: Reinforcement Learning Empowered Graph Feature Prompt Tuning  | [arXiv](https://arxiv.org/pdf/2408.03195v1) | -- | arXiv |  6 Aug 2024  |  |

## Reasoning Limitations

| Paper | Link | Code | Venue | Date | Other |
|-------|------|------|-------|------|-------|
| On the Planning Abilities of Large Language Models : A Critical Investigation | [arXiv](https://arxiv.org/pdf/2305.15771)| [GitHub](https://github.com/karthikv792/LLMs-Planning?utm_source=catalyzex.com) | NeurIPS 23 | 6 Nov 2023 | |
| Large Language Models Cannot Self-Correct Reasoning Yet | [arXiv](https://arxiv.org/pdf/2310.01798) | -- | ICLR 24 | 14 Mar 2024  |  |
| Dissociating language and thought in large language models | [arXiv](https://arxiv.org/pdf/2301.06627) | -- | Trends in Cognitive Sciences | 23 Mar 2024 |  |
| Reasoning or Reciting? Exploring the Capabilities and Limitations of Language Models Through Counterfactual Tasks | [arXiv](https://arxiv.org/pdf/2307.02477) | [GitHub](https://github.com/ZhaofengWu/counterfactual-evaluation) | NAACL 24 | 28 Mar 2024  | |
| Does Fine-Tuning LLMs on New Knowledge Encourage Hallucinations? | [arXiv](https://arxiv.org/pdf/2405.05904) | -- | arXiv | 13 May 2024  | [Video](https://www.youtube.com/watch?v=YhjdY2jbLpc) |
| On the Brittle Foundations of ReAct Prompting for Agentic Large Language Models | [arXiv](https://arxiv.org/pdf/2405.04776) | -- | arXiv | 22 May 2024 |  |
| Clever Hans or Neural Theory of Mind? Stress Testing Social Reasoning in Large Language Models | [arXiv](https://arxiv.org/pdf/2305.14763) | [GitHub](https://github.com/salavi/Clever_Hans_or_N-ToM) | EACL 24 | 24 May 2023 |  |
| Can Graph Learning Improve Task Planning? | [arXiv](https://arxiv.org/pdf/2405.19119v1) | [GitHub](https://github.com/WxxShirley/GNN4TaskPlan) | arXiv | 29 May 2024 |  |
| Graph-enhanced Large Language Models in Asynchronous Plan Reasoning | [arXiv](https://arxiv.org/pdf/2402.02805) | [GitHub](https://github.com/fangru-lin/graph-llm-asynchow-plan) | ICML 24 | 3 Jun 2024 |  |
| When is Tree Search Useful for LLM Planning? It Depends on the Discriminator | [arXiv](https://arxiv.org/pdf/2402.10890) | [GitHub](https://github.com/OSU-NLP-Group/llm-planning-eval) | ACL 24 | 6 Jun 2024 |  |
| Chain of Thoughtlessness? An Analysis of CoT in Planning | [arXiv](https://arxiv.org/pdf/2405.04776) | -- | arXiv | 6 Jun 2024 |  |
| Can LLMs Learn from Previous Mistakes? Investigating LLMs' Errors to Boost for Reasoning | [arXiv](https://arxiv.org/pdf/2403.20046) | [GitHub](https://github.com/YookiTong/Learn-from-Mistakes-CotErrorSet) | ACL 24 | 7 Jun 2024 |  |
| Can Language Models Serve as Text-Based World Simulators? | [arXiv](https://arxiv.org/pdf/2406.06485) | [GitHub](https://github.com/cognitiveailab/GPT-simulator)  | ACL 24 | 10 Jun 2024 | |
| LLMs Can’t Plan, But Can Help Planning in LLM-Modulo Frameworks | [arXiv](https://arxiv.org/pdf/2402.01817) | -- | ICML 24 | 12 Jun 2024 | [Video](https://www.youtube.com/watch?v=qPhbh9fQ7tI) |
| Alice in Wonderland: Simple Tasks Showing Complete Reasoning Breakdown in State-Of-the-Art Large Language Models | [arXiv](https://arxiv.org/pdf/2406.02061) | [GitHub](https://github.com/LAION-AI/AIW) | arXiv | 13 Jul 2024 |  |
| On the Self-Verification Limitations of Large Language Models on Reasoning and Planning Tasks  | [arXiv](https://arxiv.org/pdf/2402.08115)| -- | arXiv | 3 Aug 2024 | |
| Does Reasoning Emerge? Examining the Probabilities of Causation in Large Language Models | [arXiv](https://arxiv.org/pdf/2408.08210) | -- | arXiv | 15 Aug 2024 |  |


## Benchmarks
| Paper | Link | Code | Venue | Date | Other |
|-------|------|------|-------|------|-------|
| Benchmarks for Automated Commonsense Reasoning: A Survey  | [arXiv](https://arxiv.org/pdf/2302.04752)| -- | arXiv | 22 Feb 2023 | |
| PlanBench: An Extensible Benchmark for Evaluating Large Language Models on Planning and Reasoning about Change | [arXiv](https://arxiv.org/pdf/2206.10498) | [GitHub](https://github.com/karthikv792/LLMs-Planning?utm_source=catalyzex.com) | NeurIPS 23 Track on Datasets and Benchmarks | 23 Nov 2023 |  |
| Put Your Money Where Your Mouth Is: Evaluating Strategic Planning and Execution of LLM Agents in an Auction Arena  | [arXiv](https://arxiv.org/pdf/2310.05746)| [GitHub](https://github.com/jiangjiechen/auction-arena) | arXiv | 3 Apr 2024  | [Project](https://auction-arena.github.io/) |
| WebArena: A Realistic Web Environment for Building Autonomous Agents  | [arXiv](https://arxiv.org/pdf/2307.13854)| [GitHub](https://github.com/web-arena-x/webarena) | NeurIPS 23 Workshop | 16 Apr 2024 | [Project](https://webarena.dev/) |
| Test of Time: A Benchmark for Evaluating LLMs on Temporal Reasoning  | [arXiv](https://arxiv.org/pdf/2406.09170v1)| -- | arXiv | 3 Jun 2024 | [HuggingFace](https://huggingface.co/datasets/baharef/ToT) |
| Open Grounded Planning: Challenges and Benchmark Construction  | [arXiv](https://arxiv.org/pdf/2406.02903)| [GitHub](https://github.com/Shiguang-Guo/Open-Grounded-Planning) | ACL 24 | 5 Jun 2024 | |
| NATURAL PLAN: Benchmarking LLMs on Natural Language Planning   | [arXiv](https://arxiv.org/pdf/2406.04520)| -- | arXiv | 6 Jun 2024 | |
| OlympicArena: Benchmarking Multi-discipline Cognitive Reasoning for Superintelligent AI | [arXiv](https://arxiv.org/pdf/2406.12753)| [GitHub](https://github.com/GAIR-NLP/OlympicArena) | arXiv | 22 Jun 2024 | [Project](https://gair-nlp.github.io/OlympicArena/) |
| TravelPlanner: A Benchmark for Real-World Planning with Language Agents  | [arXiv](https://arxiv.org/pdf/2402.01622)| [GitHub](https://github.com/OSU-NLP-Group/TravelPlanner) | ICML 24 | 23 Jun 2024 | [Project](https://osu-nlp-group.github.io/TravelPlanner/) |
| GraCoRe: Benchmarking Graph Comprehension and Complex Reasoning in Large Language Models  | [arXiv](https://arxiv.org/pdf/2407.02936)| [GitHub](https://github.com/ZIKEYUAN/GraCoRe) | arXiv | 3 Jul 2024 | |


## Miscellaneous

| Paper | Link | Code | Venue | Date | Other |
|-------|------|------|-------|------|-------|
| Lost in the Middle: How Language Models Use Long Contexts | [arXiv](https://arxiv.org/pdf/2307.03172) | -- | TACL 23 | 20 Nov 2023 |  |
| The Impact of Large Language Models on Scientific Discovery: a Preliminary Study using GPT-4 | [arXiv](https://arxiv.org/pdf/2404.19737) | --  | arXiv | 8 Dec 2023  | [project page](https://github.com/microsoft/LLM4ScientificDiscovery) |
| Math-Shepherd: Verify and Reinforce LLMs Step-by-step without Human Annotations | [arXiv](https://arxiv.org/pdf/2312.08935) | -- | ACL 24 | 19 Feb 2024 | [project page](https://achieved-bellflower-4d6.notion.site/Math-Shepherd-Verify-and-Reinforce-LLMs-Step-by-step-without-Human-Annotations-41b6e73c860840e08697d347f8889bac?pvs=4) |
| Better & Faster Large Language Models via Multi-token Prediction | [arXiv](https://arxiv.org/pdf/2404.19737) | -- | arXiv | 30 Apr 2024 | [Video](https://www.youtube.com/watch?v=oJYA6mkMXwg) [HuggingFace](https://huggingface.co/facebook/multi-token-prediction)|
| Learning Iterative Reasoning through Energy Diffusion | [arXiv](https://arxiv.org/pdf/2406.11179) | [GitHub](https://github.com/yilundu/ired_code_release) | ICML 24 | 17 Jun 2024 | [Project](https://energy-based-model.github.io/ired/) |
| Connecting the Dots: LLMs can Infer and Verbalize Latent Structure from Disparate Training Data | [arXiv](https://arxiv.org/pdf/2406.14546) |  [GitHub](https://github.com/choidami/inductive-oocr) | arXiv | 20 Jun 2024 |  
| What's the Magic Word? A Control Theory of LLM Prompting | [arXiv](https://arxiv.org/pdf/2310.04444) | -- | arXiv | 3 Jul 2024 |  ||
| AGENTGEN: Enhancing Planning Abilities for Large Language Model based Agent via Environment and Task Generation| [arXiv](https://arxiv.org/pdf/2408.00764) | --  | arXiv | 1 Aug 2024 |  |


## Additional Resources

| Resource | Link |
|-------|------|
| Yochan Tutorials on Large Language Models and Planning | [link](https://yochan-lab.github.io/tutorial/LLMs-Planning/index.html) 
| On The Capabilities and Risks of Large Language Models | [link](https://jeffhj.github.io/files/dissertation.pdf) 
| Large Language Models for Reasoning | [link](https://sites.google.com/view/cs-159-2024/home?authuser=0)


## Acknowledgement


If you want to say **thank you** or/and support active development of Awesome LLMs for Planning and Reasoning, add a [GitHub Star](https://github.com/samkhur006/awesome-llm-planning-reasoning) to the project.


Together, we can make Awesome LLMs for Planning and Reasoning **better**!

## Contributing

First off, thanks for taking the time to contribute! Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make will benefit everybody else and are **greatly appreciated**.


## Authors & contributors

The original setup of this repository is by [Sambhav Khurana](https://github.com/samkhur006).

For a full list of all authors and contributors, see [the contributors page](https://github.com/samkhur006/awesome-llm-planning-reasoning/graphs/contributors).



