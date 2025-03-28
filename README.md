<div align="center">
  <h1>👨‍💻 Awesome Code Benchmark</h1>
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
  <a href="https://img.shields.io/badge/PRs-Welcome-red">
    <img src="https://img.shields.io/badge/PRs-Welcome-red" alt="PRs Welcome">
  </a>
</div>

A comprehensive code domain benchmark review of LLM researches.

<p align="center">
    <img src="https://i.imgur.com/waxVImv.png" alt="Oryx Video-ChatGPT">
</p>

## News 
- 🔥🔥 **[2025-03-17]** We add **Code Version** (Version-specific code generation) benchmarks.
- 🔥🔥 **[2025-03-16]** A thorough review of code domain benchmarks for LLM research has been released.

<!-- ## Table of Contents
1. [Code C](#1_Code Completion & Code Generation) -->

## 🚀 Top Code Benchmark

### Code Completion & Code Generation
* **HumanEval**: code completion 
* **MBPP**: text -> code; code generation 
* **APPS**: a benchmark for code generation from natural language specifications
* **EvalPlus**: extends the HumanEval and MBPP benchmarks
* **MultiPL-E**: extends the HumanEval and MBPP benchmarks to 18 languages
* **CodeClarQA**: containing pairs of natural language descriptions and code with created synthetic clarification questions and answers.
* **DevEval**: repo-level code generation
* **BigCodeBench**: complete Split & Instruct Split
* **DynaCode**: a dynamic complexity-aware code benchmark
* **Stack-Repo**: repo-level code completion of java
* **StudentEval**: a benchmark of student-written prompts for code generation evaluation
* **MCoNaLa**: code generation from multiple natural languages
* **LCC**: long code context code completion
* **RepoBench**: repo-level code auto-completion
* **ReCode**: a comprehensive robustness evaluation benchmark for code generation
* **LongBench**: a bilingual, multitask benchmark for long context understanding
* **CommitPack & HumanEvalPack**: multilingual code editing and understanding benchmarks based on Git commits and HumanEval extensions
* **COCO**: instruction-level robustness benchmark for code generation
* **ODEX**: open-domain, execution-based natural language to code generation
* **BioCoder**:  bioinformatics code generation
* **CrossCodeEval**: diverse and multilingual benchmark for cross-file code completion
* **Buggy-HumanEval & Buggy-FixEval**: buggy code completion
* **MT-Bench-101**: Multi-turn question answering
* **ML-Bench**: repo-level ML task solving benchmark using real-world code
* **PLPilot**: Benchmark automating programming language design tasks
* **CoderEval**: pragmatic code generation
* **MultiNL-H**: multilingual NL-to-code benchmark with keyword-guided generation
* **APPS+**: enhanced version of the APPS dataset, designed for reinforcement learning in code generation
* **OOP**: object-oriented programming evaluation benchmark of python programs
* **-**: static analysis-based evaluation framework for LLM code completions using ASTs
* **L2CEval**: multilingual, multi-task NL-to-code benchmark including semantic parsing, math reasoning and Python programming.
* **ICE-Score**: an evaluation metric for code quality without test cases or references
* **HumanExtension**：auxiliary-function-based code generation benchmark
* **R2E-Eval1**：repo-level programming agent benchmark from GitHub repos for evaluating static and interactive code generation systems
* **REval**: evaluates code LLMs’ reasoning and consistency with runtime behavior
* **InfiBench**: free-form question-answering benchmark comprising 234 high-quality Stack Overflow questions across 15 programming languages
* **RobustAPI**: Java API misuse benchmark from Stack Overflow for evaluating LLM code robustness
* **EvoCodeBench**: evolving Python code generation benchmark from real GitHub commits
* **CodeBenchGen**: scalable Python code generation benchmark built from GitHub functions and docstrings with execution-based evaluation
* **HALLUCODE**: evaluate LLMs' ability to recognize and mitigate hallucinations in code generation
* **LeetCodeEval**: Leetcode-based benchmark for comparing LLM vs. human code performance
* **X-HumanEval-X**: exploring Multi-Lingual Bias of Large Code Models in Code Generation
* **CodeHalu**: systematically evaluate code hallucinations in LLMs through execution-based verification
* **PYCOMMITS**: multi-round Python code editing benchmark from real commit histories
* **CodeContests**: complex programming task
* **EvoEval**: a comprehensive evaluation of LLMs' coding abilities across diverse domains
* **LLM4Decompile**: benchmark for evaluating binary-to-C decompilation on real-world open-source binaries
* **CatCoder**: a framework for repo-level code generation in statically typed languages using code and type context
* **AICoderEval**: AI task-specific code generation benchmark for LLMs in NLP, CV, and multimodal learning
* **CodeAgentBench**: repo-level code generation benchmark with tool-integrated agents for real-world tasks
* **AssertionBench**: assertion generation for hardware design verification
* **SAFIM**: syntax-aware code completion benchmark focusing on code blocks and conditional expressions​
* **GenCodeSearchNet**: benchmark for evaluating LLM generalization in programming language understanding across tasks and languages
* **ConCodeEval**: benchmark for assessing LLMs' understanding of code constraints in domain-specific languages like JSON and YAML

| Benchmark | Paper | Date | Github | Dataset & Website & LeaderBoard |
|:--|:--|:--|:--|:--|
| HumanEval     | [Evaluating Large Language Models Trained on Code](https://arxiv.org/abs/2107.03374)                                                                       | Arxiv 2021/07       | [Github](https://github.com/openai/human-eval)                                | [🤗Dataset](https://huggingface.co/datasets/openai/openai_humaneval) | 
| MBPP          | [Program Synthesis with Large Language Models](https://arxiv.org/abs/2108.07732)                                                                           | Arxiv 2021/08       | | [🤗Dataset](https://huggingface.co/datasets/google-research-datasets/mbpp) | 
| APPS          | [Measuring Coding Challenge Competence With APPS](https://arxiv.org/abs/2105.09938)                                                                        | NeurIPS 2021        | [Github](https://github.com/hendrycks/apps)                                   | [🤗Dataset](https://huggingface.co/datasets/codeparrot/apps) |
| EvalPlus      | [Is Your Code Generated by Chat{GPT} Really Correct? Rigorous Evaluation of Large Language Models for Code Generation](https://arxiv.org/abs/2305.01210)   | NeurIPS 2023        | [Github](https://github.com/evalplus/evalplus)                           | [🤗Dataset](https://huggingface.co/evalplus) | 
| MultiPL-E     | [MultiPL-E: A Scalable and Polyglot Approach to Benchmarking Neural Code Generation](https://ieeexplore.ieee.org/abstract/document/10103177)               | TSE 2023            | [Github](https://github.com/nuprl/MultiPL-E)                                 | [🤗Dataset](https://huggingface.co/datasets/nuprl/MultiPL-E) |
| CodeClarQA    | [Python Code Generation by Asking Clarification Questions](https://arxiv.org/abs/2212.09885v2)                                                             | ACL 2023            | [Github](https://github.com/UKPLab/codeclarqa)                                | [Dataset](https://drive.google.com/file/d/1bM-b-L10vNpk7Onyft9BXK8GlMIGl52q/view?usp=sharing) | 
| DevEval       | [DevEval: A Manually-Annotated Code Generation Benchmark Aligned with Real-World Code Repositories](https://arxiv.org/abs/2405.19856)                      | ACL 2024            | [Github](https://github.com/seketeam/DevEval)                                | [🤗Dataset](https://huggingface.co/datasets/LJ0815/DevEval/blob/main/Source_Code.tar.gz)|
| BigCodeBench  | [BigCodeBench: Benchmarking Code Generation with Diverse Function Calls and Complex Instructions](https://arxiv.org/abs/2406.15877)                        | ICLR 2025           | [Github](https://github.com/bigcode-project/bigcodebench)                  | [📊LeaderBoard](https://huggingface.co/spaces/bigcode/bigcodebench-leaderboard) |   
| DynaCode      | [DynaCode: A Dynamic Complexity-Aware Code Benchmark for Evaluating Large Language Models in Code Generation](https://arxiv.org/abs/2503.10452)            | Arxiv 2025/03       | | |
| Stack-Repo    | [RepoFusion: Training Code Models to Understand Your Repository](https://arxiv.org/abs/2306.10998)                  | Arxiv 2023/06       | [Github](https://github.com/seketeam/DevEval) | [🤗Dataset](https://huggingface.co/RepoFusion) |
| StudentEval   | [StudentEval: A Benchmark of Student-Written Prompts for Large Language Models of Code](https://arxiv.org/abs/2306.10998)            | ACL 2024 Findings       | [Github](https://github.com/Wellesley-EASEL-lab/StudentEval) | [🤗Dataset](https://huggingface.co/datasets/wellesley-easel/StudentEval) |
| MCoNaLa       | [MCoNaLa: A Benchmark for Code Generation from Multiple Natural Languages](https://arxiv.org/abs/2203.08388)        | EACL 2023 Findings      | [Github](https://github.com/zorazrw/multilingual-conala) | [🤗Dataset](https://huggingface.co/datasets/neulab/mconala) |
| LCC           | [LongCoder: A Long-Range Pre-trained Language Model for Code Completion](https://arxiv.org/abs/2306.14893)          | ICML 2023  | [Github](https://github.com/microsoft/CodeBERT/tree/master/LongCoder)    | |
| RepoBench     | [RepoBench: Benchmarking Repository-Level Code Auto-Completion Systems](https://arxiv.org/abs/2306.03091)           | ICLR 2024  | | |
| ReCode        | [ReCode: Robustness Evaluation of Code Generation Models](https://arxiv.org/abs/2212.10264)                         | ACL 2023  | [Github](https://github.com/amazon-science/recode)    | |
| LongBench     | [LongBench: A Bilingual, Multitask Benchmark for Long Context Understanding](https://arxiv.org/abs/2308.14508)      | ACL 2024  | [Github](https://github.com/THUDM/LongBench)    | [🤗Dataset](https://huggingface.co/datasets/THUDM/LongBench)|
| CommitPack & HumanEvalPack     | [OctoPack: Instruction Tuning Code Large Language Models](https://arxiv.org/abs/2308.07124)      | ICLR 2024  | [Github](https://github.com/bigcode-project/octopack)    | |
| COCO          | [COCO: Testing Code Generation Systems via Concretized Instructions](https://arxiv.org/abs/2308.13319)      | Arxiv 2023/08  | [Github](https://github.com/coco-2023/COCO)    | |
| ODEX          | [Execution-Based Evaluation for Open-Domain Code Generation](https://arxiv.org/abs/2212.10481)      | EMNLP 2023 Findings  | [Github](https://github.com/zorazrw/odex)    | |
| BioCoder      | [BioCoder: A Benchmark for Bioinformatics Code Generation with Large Language Models](https://arxiv.org/abs/2308.16458)      | Bioinformatics, July 2024  | [Github](https://github.com/gersteinlab/biocoder)    | [🤗Dataset](https://huggingface.co/datasets/lilbillbiscuit/biocoder_public) |
| CrossCodeEval | [CrossCodeEval: A Diverse and Multilingual Benchmark for Cross-File Code Completion](https://arxiv.org/abs/2310.11248)      | NeurIPS 2023  | [Github](https://github.com/amazon-science/cceval)    | |
| Buggy-HumanEval & Buggy-FixEval | [Large Language Models of Code Fail at Completing Code with Potential Bugs](https://arxiv.org/abs/2306.03438) | NeurIPS 2023  | [Github](https://github.com/amazon-science/buggy-code-completion) | |
| MT-Bench-101  | [MT-Bench: How Good are LLMs at Multi-turn Question Answering](https://arxiv.org/abs/2402.14762) | ACL 2024 | [Github](https://github.com/mtbench101/mt-bench-101)     | |
| ML-Bench      | [ML-Bench: Evaluating Large Language Models and Agents for Machine Learning Tasks on Repository-Level Code](https://arxiv.org/abs/2311.09835) | Arxiv 2023/11  | [Github](https://github.com/gersteinlab/ML-bench)   | [🤗Dataset](https://huggingface.co/datasets/super-dainiu/ml-bench)|
| PLPilot       | [PLPilot: Benchmark an Automated Programming Language Design Framework Enabled by LLMs](https://mlforsystems.org/assets/papers/neurips2023/paper13.pdf) | NeurIPS 2023  | [Github](https://github.com/changkaiyan/plpilot)   | |
| CoderEval     | [CoderEval: A Benchmark of Pragmatic Code Generation with Generative Pre-trained Models](https://arxiv.org/abs/2302.00288) | ICSE 2024  | [Github](https://github.com/CoderEval/CoderEval) | |
| MultiNL-H     | [Improving Natural Language Capability of Code Large Language Model](https://arxiv.org/abs/2401.14242) | Arxiv 2024/01  | [Github](https://github.com/NL2Code/AttentionCoder) | |
| APPS+         | [StepCoder: Improve Code Generation with Reinforcement Learning from Compiler Feedback](https://arxiv.org/abs/2402.01391) | ACL 2024 | [Github](https://github.com/Ablustrund/APPS_Plus) | |
| OOP           | [OOP: Object-Oriented Programming Evaluation Benchmark for Large Language Models](https://arxiv.org/abs/2401.06628) | ACL 2024 Findings | [Github](https://github.com/alphadl/OOP-eval)   | [🤗Dataset](https://huggingface.co/datasets/codeai-dteam/oop)         |
| - | [A Static Evaluation of Code Completion by Large Language Models](https://arxiv.org/abs/2306.03203) | ACL Industry Track 2023 | | |
| L2CEval       | [L2CEval: Evaluating Language-to-Code Generation Capabilities of Large Language Models](https://arxiv.org/abs/2309.17446) | TACL 2024 | | |
| ICE-Score     | [ICE-Score: Instructing Large Language Models to Evaluate Code](https://arxiv.org/abs/2304.14317) | EACL 2024 Findings | [Github](https://github.com/terryyz/ice-score) | |
| HumanExtension  | [Exploring Language Model's Code Generation Ability with Auxiliary Functions](https://arxiv.org/abs/2403.10575) | NAACL 2024 Findings | [Github](https://github.com/sh0416/humanextension) | |
| R2E-Eval1     | [R2E: Turning Any GitHub Repository into a Programming Agent Test Environment](https://dl.acm.org/doi/10.5555/3692070.3692922) | ICML 2024 | [Github](https://github.com/r2e-project/r2e) | |
| REval         | [Evaluating Large Language Models with Runtime Behavior of Program Execution](https://arxiv.org/abs/2403.16437) | ICSE 2025 | [Github](https://github.com/r-eval/r-eval.github.io) | [📊LeaderBoard](https://r-eval.github.io/) |
| InfiBench     | [InfiBench: Evaluating the Question-Answering Capabilities of Code Large Language Models](https://arxiv.org/abs/2404.07940) | NeurIPS 2024 | [Github](https://github.com/infi-coder/infibench-evaluation-harness/) | [🌐Website](https://infi-coder.github.io/infibench/) |
| RobustAPI     | [Can LLM Replace Stack Overflow? A Study on Robustness and Reliability of Large Language Model Code Generation](https://arxiv.org/abs/2308.10335) | AAAI 2024 | [Github](https://github.com/FloridSleeves/RobustAPI) | [🤗Dataset](https://huggingface.co/datasets/LilyZZZ/RobustAPI) |
| EvoCodeBench  | [EvoCodeBench: An Evolving Code Generation Benchmark Aligned with Real-World Code Repositories](https://arxiv.org/abs/2404.00599) | NeurIPS 2025  | [Github](https://github.com/seketeam/EvoCodeBench) | [🤗Dataset](https://huggingface.co/datasets/LJ0815/EvoCodeBench) |
| CodeBenchGen  | [CodeBenchGen: Creating Scalable Execution-based Code Generation Benchmarks](https://arxiv.org/abs/2404.00566) | Arxiv 2024/04  | [Github](https://github.com/yiqingxyq/CodeBenchGen) | |
| HALLUCODE | [Exploring and Evaluating Hallucinations in LLM-Powered Code Generation](https://arxiv.org/abs/2404.00971) | Arxiv 2024/04  | ||
| LeetCodeEval  | [A Performance Study of LLM-Generated Code on Leetcode](https://arxiv.org/abs/2407.21579) | EASE 2024 | | |
| X-HumanEval-X | [Exploring Multi-Lingual Bias of Large Code Models in Code Generation](https://arxiv.org/abs/2404.19368) | Arxiv 2024/04  | | |
| CodeHalu      | [CodeHalu: Investigating Code Hallucinations in LLMs via Execution-based Verification (Hallucination benchmark)](https://arxiv.org/abs/2405.00253) | AAAI 2025 | [Github](https://github.com/yuchen814/CodeHalu) | |
| PYCOMMITS     | [Coeditor: Leveraging Contextual Changes for Multi-round Code Auto-editing](https://arxiv.org/abs/2305.18584) | ICLR 2024 | [Github](https://github.com/MrVPlusOne/Coeditor) | |
| CodeContests  | [Competition-Level Code Generation with AlphaCode](https://arxiv.org/abs/2203.07814) | Science 2022 | [Github](https://github.com/google-deepmind/code_contests) | |
| EvoEval       | [Top Leaderboard Ranking = Top Coding Proficiency, Always? EvoEval: Evolving Coding Benchmarks via LLM](https://arxiv.org/abs/2403.19114) | COLM 2024 | [Github](https://github.com/evo-eval/evoeval) | |
| LLM4Decompile | [LLM4Decompile: Decompiling Binary Code with Large Language Models](https://arxiv.org/abs/2403.05286) | EMNLP 2024 | [Github](https://github.com/albertan017/LLM4Decompile) | |
| CatCoder      | [Enhancing Repository-Level Code Generation with Integrated Contextual Information](https://arxiv.org/abs/2406.03283) | Arxiv 2024/06  | | |
| AICoderEval   | [AICoderEval: Improving AI Domain Code Generation of Large Language Models](https://arxiv.org/abs/2406.04712) | Arxiv 2024/06  | | [🤗Dataset](https://huggingface.co/datasets/vixuowis/AICoderEval) |
| CodeAgentBench | [CodeAgent: Enhancing Code Generation with Tool-Integrated Agent Systems for Real-World Repo-level Coding Challenges](https://arxiv.org/abs/2401.07339) | ACL 2024 | | |
| AssertionBench| [AssertionBench: A Benchmark to Evaluate Large-Language Models for Assertion Generation](https://arxiv.org/abs/2406.18627) | NAACL 2025 | [Github](https://github.com/achieve-lab/assertion_data_for_LLM) | |
| SAFIM         | [Evaluation of LLMs on Syntax-Aware Code Fill-in-the-Middle Tasks](https://arxiv.org/abs/2403.04814) | ICLR 2024 | [Github](https://github.com/gonglinyuan/safim)   | [🤗Dataset](https://huggingface.co/datasets/gonglinyuan/safim) |
| GenCodeSearchNet | [GenCodeSearchNet: A Benchmark Test Suite for Evaluating Generalization in Programming Language Understanding](https://arxiv.org/abs/2311.09707) | GenBench Workshop 2023 | [Github](https://github.com/drndr/gencodesearchnet) | [🤗Dataset](https://huggingface.co/datasets/drndr/statcodesearch) |
| ConCodeEval   | [ConCodeEval: Evaluating Large Language Models for Code Constraints in Domain-Specific Languages](https://arxiv.org/abs/2407.03387) | Arxiv 2024/07  | | |

*　| HumanEval-X   | [CodeGeeX: A Pre-Trained Model for Code Generation with Multilingual Benchmarking on HumanEval-X](https://arxiv.org/abs/2303.17568) | SIGKDD 2023| [Github](https://github.com/THUDM/CodeGeeX) | |
* HumanEval-XL: A Multilingual Code Generation Benchmark for Cross-lingual Natural Language Generalization
* CodeScope: An Execution-based Multilingual Multitask Multidimensional Benchmark for Evaluating LLMs on Code Understanding and Generation
* XCodeEval: An Execution-based Large Scale Multilingual Multitask Benchmark for Code Understanding, Generation, Translation and Retrieval
* Fine-tuning Language Models for Joint Rewriting and Completion of Code with Potential Bugs | ACL 2024 Findings |
* PythonSaga: Redefining the Benchmark to Evaluate Code Generating LLMs https://aclanthology.org/2024.findings-emnlp.996.pdf
* ComplexCodeEval: A Benchmark for Evaluating Large Code Models on More Complex Code (It covers multiple aspects, including tasks such as code generation, code completion, API recommendation, and test case generation, and aims to comprehensively evaluate the performance of large language models in complex code scenarios.)
* JavaBench: A Benchmark of Object-Oriented Code Generation for Evaluating Large Language Models
* HumanEvalComm: Benchmarking the Communication Competence of Code Generation for LLMs and LLM Agent https://arxiv.org/abs/2406.00215
* CoderUJB: An Executable and Unified Java Benchmark for Practical Programming Scenarios https://arxiv.org/abs/2403.19287
* CodeScore: Evaluating Code Generation by Learning Code Execution (MBPP-ET)
* CrossCodeBench: Benchmarking Cross-Task Generalization of Source Code Models
* Teaching Code LLMs to Use Autocompletion Tools in Repository-Level Code Generation
* | RealWorld-Bench | [What's Wrong with Your Code Generated by Large Language Models? An Extensive Study](https://arxiv.org/abs/2407.06153)                             | Arxiv 2024/07               | | |

### Code Efficiency
| Benchmark | Paper | Date | Github | Dataset & Website & LeaderBoard |
|:--|:--|:--|:--|:--|
| EvalPerf      | [Evaluating Language Models for Efficient Code Generation](https://arxiv.org/abs/2408.06450)                                          | COLM 2024                   | [Github](https://github.com/evalplus/evalplus)        | [🤗Dataset](https://huggingface.co/datasets/evalplus/evalperf) |
| EffiBench     | [EffiBench: Benchmarking the Efficiency of Automatically Generated Code](https://arxiv.org/abs/2402.02037)                            | NeurIPS 2024                | [Github](https://github.com/huangd1999/EffiBench)     |  |
| Mercury       | [Mercury: A Code Efficiency Benchmark for Code Large Language Models](https://arxiv.org/abs/2402.07844v4)                             | NeurIPS 2024                | [Github](https://github.com/Elfsong/Mercury)          | [🤗Dataset](https://huggingface.co/datasets/Elfsong/Mercury) |
| ECCO          | [ECCO: Can We Improve Model-Generated Code Efficiency Without Sacrificing Functional Correctness?](https://arxiv.org/abs/2407.14044)  | EMNLP 2024                  | [Github](https://github.com/CodeEff/ECCO)             | [🤗Dataset](https://huggingface.co/datasets/CodeEff/ECCO)|
| PIE           | [Learning Performance-Improving Code Edits](https://arxiv.org/abs/2302.07867)                                                         | ICLR 2024                   | [Github](https://github.com/LearningOpt/pie)          | [🌐Website](https://pie4perf.com)|  
| ENAMEL        | [How Efficient is LLM-Generated Code? A Rigorous & High-Standard Benchmark](https://arxiv.org/abs/2406.06647)                         | ICLR 2025                   | [Github](https://github.com/q-rz/enamel)              | [🤗Dataset](https://huggingface.co/datasets/q-rz/enamel) |


### CodeFix & Bug-Fix
* **HumanEvalFix**: code repair capabilitie 
* **SWT-Bench**: Evaluating LLMs on testing generation for real world software issues 
* **SWE-bench**: Evaluating LLMs Resolve Real-World GitHub Issues 
* **SWE-bench Multimodal**: Evaluate LLMs on their ability to fix bugs in visual, user-facing JavaScript software 
* **GitBug-Java**: automatic program repair and fault localization of Java bugs
* **GitBug-Actions**: constructing reproducible bug-fix benchmarks using GitHub Actions
* **LiveCodeBench**: dynamic benchmark for contamination-free evaluation of LLMs from real-world platforms
* **RepoBugs**: repo-level bug-fix benchmark for evaluating LLM-based program repair with full context
* **RepoFixEval**: repository-level program repair benchmark for evaluating LLMs on issue discovery, fault localization, and code fixing
* **DebugBench**: evaluating LLMs' debugging capabilities across various bug categories and types
* **Multi-Bug**: a dataset for evaluating LLMs on multi-bug code debugging tasks
* **Socratic-Debugging**: evaluating LLMs on interactive, dialogue-based bug fixing
* **Coffee-Gym**: interactive benchmark environment for evaluating LLMs on NL-guided code repair
* **INTERVENOR**: interactive code repair benchmark with multi-turn learner–teacher dialogue
* **TFix & ManySStuBs4J & TSSB-3M**: evaluating automatic program repair in JavaScript, Java, and Python
* **StatType-SO**: benchmark for resolving imports and types in incomplete Stack Overflow code snippets

| Benchmark | Paper | Date | Github | Dataset & Website & LeaderBoard |
|:--|:--|:--|:--|:--|
| HumanEvalFix          | [OctoPack: Instruction Tuning Code Large Language Models](https://arxiv.org/abs/2308.07124)                                    | Arxiv 2023/08              | [Github](https://github.com/bigcode-project/octopack)        | [🤗Dataset](https://huggingface.co/datasets/bigcode/humanevalpack) |  
| SWT-Bench             | [SWT-Bench: Testing and Validating Real-World Bug-Fixes with Code Agents](https://arxiv.org/abs/2406.12952)                    | NeurIPS 2024               | [Github](https://github.com/logic-star-ai/SWT-Bench)         | [🌐Website](https://swtbench.com) |
| SWE-bench             | [SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://arxiv.org/abs/2310.06770)                           | ICLR 2024                  | [Github](https://github.com/swe-bench/SWE-bench)             | [🌐Website](https://www.swebench.com) | 
| SWE-bench Multimodal  | [SWE-bench Multimodal: Do AI Systems Generalize to Visual Software Domains?](https://arxiv.org/abs/2410.03859)                 | ICLR 2025                  | [Github](https://github.com/swe-bench/SWE-bench)             | [🌐Website](https://www.swebench.com/multimodal) [🤗Dataset](https://www.swebench.com/multimodal) | 
| GitBug-Java     | [GitBug-Java: A Reproducible Benchmark of Recent Java Bugs](https://arxiv.org/abs/2402.02961v2)                                      | MSR 2024                   | [Github](https://github.com/gitbugactions/gitbug-java) | [🌐Website](https://nuno.saavedra.pt/gitbug-java#!/) [🤗Dataset](https://huggingface.co/datasets/gitbugactions/gitbug-java) |
| GitBug-Actions | [GitBug-Actions: Building Reproducible Bug-Fix Benchmarks with GitHub Actions](https://arxiv.org/abs/2310.15642)                             | ICSE 2024 Demo              | [Github](https://github.com/gitbugactions/gitbugactions) | [▶️Video](https://www.youtube.com/watch?v=aBWwa1sJYBs) |
| LiveCodeBench  | [LiveCodeBench: Holistic and Contamination Free Evaluation of Large Language Models for Code](https://arxiv.org/abs/2403.07974)        | ICLR 2025           | [Github](https://github.com/LiveCodeBench/LiveCodeBench) | [🌐Website](https://livecodebench.github.io/) [🤗Dataset](https://huggingface.co/livecodebench) [📊LeaderBoard](https://livecodebench.github.io/leaderboard.html)|
| RepoBugs       | [When Large Language Models Confront Repository-Level Automatic Program Repair: How Well They Done?](https://arxiv.org/abs/2403.00448)    | ICSE 2024 Track | | |
| RepoFixEval    | [RepoFixEval: A Repository-Level Program Repair Benchmark From Issue Discovering to Bug Fixing](https://openreview.net/pdf?id=LaNCeNmoHR) | Openreview 2024 | | |
| DebugBench     | [DebugBench: Evaluating Debugging Capability of Large Language Models](https://arxiv.org/abs/2401.04621)                                     | ACL 2024            | [Github](https://github.com/thunlp/DebugBench) | [🤗Dataset](https://huggingface.co/datasets/Rtian/DebugBench) |
| Multi-Bug      | [Instruct, Not Assist: LLM-based Multi-Turn Planning and Hierarchical Questioning for Socratic Code Debugging](https://arxiv.org/abs/2406.11709)        | EMNLP 2024 Findings | [Github](https://github.com/agarwalishika/TreeInstruct) | | 
| Socratic-Debugging | [Socratic Questioning of Novice Debuggers: A Benchmark Dataset and Preliminary Evaluations](https://aclanthology.org/2023.bea-1.57.pdf)                     | BEA 2023            | [Github](https://github.com/taisazero/socratic-debugging-benchmark) | |
| Coffee-Gym     | [Coffee-Gym: An Environment for Evaluating and Improving Natural Language Feedback on Erroneous Code](https://arxiv.org/abs/2409.19715) | EMNLP 2024 | []() | [🤗Dataset](https://huggingface.co/spaces/Coffee-Gym/Project-Coffee-Gym) |
| INTERVENOR     | [INTERVENOR: Prompt the Coding Ability of Large Language Models with the Interactive Chain of Repairing](https://arxiv.org/abs/2311.09868) | ACL 2024 Findings | [Github](https://github.com/NEUIR/INTERVENOR) |
| TFix & ManySStuBs4J & TSSB-3M | [Towards Low-Resource Automatic Program Repair with Meta-Learning and Pretrained Language Models](https://aclanthology.org/2023.emnlp-main.430.pdf)  | EMNLP 2023        | [Github](https://github.com/wang-weishi/Meta-APR) | |
| StatType-SO    | [ZS4C: Zero-Shot Synthesis of Compilable Code for Incomplete Code Snippets using LLMs](https://arxiv.org/abs/2401.14279)                       | TOSEM 2024         | [Github]() | |

### Code Reasoning & Understanding
* **CRUXEval**: code reasoning, understanding, and execution capabilities
* **CodeMMLU**: code understanding and comprehension

|Benchmark | Paper | Date | Github | Dataset & Website & LeaderBoard |
|:--|:--|:--|:--|:--|
| CRUXEval      | [CRUXEval: A Benchmark for Code Reasoning, Understanding and Execution](https://arxiv.org/abs/2401.03065)                                      | Arxiv 2024/01         | [Github](https://github.com/facebookresearch/cruxeval)        | [📊LeaderBoard](https://crux-eval.github.io/leaderboard.html) |    
| CodeMMLU      | [CodeMMLU: A Multi-Task Benchmark for Assessing Code Understanding Capabilities of CodeLLMs](https://arxiv.org/abs/2410.01999)                 | ICLR 2025             | [Github](https://github.com/FSoft-AI4Code/CodeMMLU/)          | [🤗Dataset](https://huggingface.co/datasets/Fsoft-AIC/CodeMMLU) [📊LeaderBoard](https://fsoft-ai4code.github.io/leaderboards/codemmlu/) [🌐  Website](https://fsoft-ai4code.github.io/codemmlu/) | 

* | CodeJudge-Eval | [CodeJudge-Eval: Can Large Language Models be Good Judges in Code Understanding?](https://arxiv.org/abs/2408.10718)                                   | COLING 2025           | [Github](https://github.com/CodeLLM-Research/CodeJudge-Eval)
* | Poor-CodeSumEval | [How Effectively Do Code Language Models Understand Poor-Readability Code?](https://dl.acm.org/doi/10.1145/3691620.3695072)            | ASE 2024              | [Github](https://github.com/ythere-y/PoorCodeSumEval) | [🤗Dataset](https://huggingface.co/datasets/google/code_x_glue_ct_code_to_text) |
* | | [A Novel Refactoring and Semantic Aware Abstract Syntax Tree Differencing Tool and a Benchmark for Evaluating the Accuracy of Diff Tools](https://arxiv.org/abs/2403.05939) | TOSEM 2024 | [Github](https://github.com/pouryafard75/DiffBenchmark?utm_source=chatgpt.com) | |
* CodeQueries: A Dataset of Semantic Queries over Code
* A Benchmark for Testing the Capabilities of LLMs in Assessing the Quality of Multiple-choice Questions in Introductory Programming Education

### Data science
* **DS-1000**: Data Science Code Generation
* **DA-Code**: Data science tasks
* **GeoCodeBench** (inferred name): evaluation benchmark for testing LLMs on geospatial code generation tasks
* **SensorBench**: benchmark for evaluating LLMs on real-world sensor data processing tasks
* **MatPlotBench**: evaluating LLMs on scientific data visualization through code generation and visual feedback
* **ARCADE**: benchmark of multi-turn NL-to-code generation tasks in data science notebooks

| Benchmark | Paper | Date | Github | Dataset & Website & LeaderBoard |
|:--|:--|:--|:--|:--|
| DS-1000      | [DS-1000: A Natural and Reliable Benchmark for Data Science Code Generation](https://arxiv.org/abs/2211.11501)                                      | ICML 2023                 | [Github](https://github.com/xlang-ai/DS-1000)        | [🌐HomePage](https://ds1000-code-gen.github.io) [🤗Dataset](https://huggingface.co/datasets/xlangai/DS-1000)  | 
| DA-Code      | [DA-Code: Agent Data Science Code Generation Benchmark for Large Language Models](https://arxiv.org/abs/2410.07331)                                 | EMNLP 2024                | [Github](https://github.com/yiyihum/da-code)         | [🌐Website](https://da-code-bench.github.io) [🤗Dataset](https://huggingface.co/datasets/Jianwen2003/DA-Code) | 
| GeoCodeBench | [Evaluation of Code LLMs on Geospatial Code Generation](https://arxiv.org/abs/2410.04617)                                                                        | GeoAI 2024                | [Github](https://github.com/kraina-ai/geospatial-code-llms-dataset) | |
| SensorBench  | [SensorBench: Benchmarking LLMs in Coding-Based Sensor Processing](https://arxiv.org/abs/2410.10741) | HotMobile 2025 | [Github](https://github.com/nesl/LLM_sensor_processing) | |
| MatPlotBench | [MatPlotAgent: Method and Evaluation for LLM-Based Agentic Scientific Data Visualization](https://arxiv.org/abs/2402.11453)                         | ACL 2024 Findings         | [Github](https://github.com/thunlp/MatPlotAgent) | |
| ARCADE       | [Natural Language to Code Generation in Interactive Data Science Notebooks](https://arxiv.org/abs/2212.09248)                                       | ACL 2023                  | [Github](https://github.com/google-research/arcade-nl2code?utm_source=chatgpt.com) | [Dataset](https://www.kaggle.com/datasets/googleai/arcade-nl2code-dataset) |


### Text2SQL 
* **Spider**:  text-to-SQL  
* **Spider 2.0**: text-to-SQL
* **SNAILS**: benchmark for evaluating how schema identifier naturalness affects LLM-based NL-to-SQL performance
* **BIRD**: large-scale text-to-SQL benchmark focusing on value comprehension and SQL efficiency in realistic industrial settings
* **SecureSQL**: benchmark for evaluating sensitive data leakage risks in LLM-generated SQL
* **SQL2Text**: a dataset repurposed from Text-to-SQL resources for evaluating SQL-to-natural language generation  tasks
* **Spider-Syn**: derived from Spider for evaluating text-to-SQL model robustness to schema-related synonym substitution in NL questions
* **Spider-Realistic**: evaluating text-to-SQL models under more realistic text-table alignment conditions
* **Dr.Spider**: evaluating text-to-SQL model robustness across NL, SQL, and database variations
* **BookSQL**: large-scale text-to-SQL dataset for the accounting and finance domain
* **Archer**: bilingual text-to-SQL dataset focused on complex reasoning types across 20 domains
* **EHRSQL-2024**: text-to-SQL dataset for question answering over electronic health records focusing on reliability in clinical settings
* **Spider-DK**: evaluating text-to-SQL model robustness to rarely observed domain knowledge in NL questions
* **ScienceBenchmark**: NL-to-SQL benchmark for complex, domain-specific scientific databases
* **BULL**: practical text-to-SQL dataset for financial analysis, covering fund, stock, and macroeconomic databases
* **cwd-benchmark-data**: enterprise SQL QA benchmark in the insurance domain for evaluating LLM accuracy in real-world business scenarios

| Benchmark | Paper | Date | Github | Dataset & Website & LeaderBoard |
|:--|:--|:--|:--|:--|
| Spider      | [Spider: A Large-Scale Human-Labeled Dataset for Complex and Cross-Domain Semantic Parsing and Text-to-SQL Task](https://arxiv.org/abs/1809.08887)      | EMNLP 2018     | [Github](https://github.com/taoyds/spider)        | [🌐Homepage](https://yale-lily.github.io/spider) |
| Spider 2.0  | [Spider 2.0: Evaluating Language Models on Real-World Enterprise Text-to-SQL Workflows](https://arxiv.org/abs/2411.07763)                                   | ICLR 2025      | [Github](https://github.com/xlang-ai/Spider2)     | [🌐Website](https://spider2-sql.github.io) |
| SNAILS      | [SNAILS: Schema Naming Assessments for Improved LLM-Based SQL Inference](https://dl.acm.org/doi/10.1145/3709727) | PACMMOD 2025 | | |
| BIRD        | [Can LLM Already Serve as A Database Interface? A BIg Bench for Large-Scale Database Grounded Text-to-SQLs](https://arxiv.org/abs/2305.03111)      | NeurIPS 2023    | [Github](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/bird) | [🌐Website](https://bird-bench.github.io/) |
| SecureSQL   | [SecureSQL: Evaluating Data Leakage of Large Language Models as Natural Language Interfaces to Databases](https://aclanthology.org/2024.findings-emnlp.346.pdf)  | EMNLP 2024 Findings | [Github](https://github.com/JacobiSong/SecureSQL) | |
| SQL2Text    | [Semantic Captioning: Benchmark Dataset and Graph-Aware Few-Shot In-Context Learning for SQL2Text](https://arxiv.org/abs/2501.03166)                                    | COLING 2025   | [Github](https://github.com/aliwister/ast-icl) | |
| Spider-Syn  | [Towards robustness of text-to-SQL models against synonym substitution](https://arxiv.org/abs/2106.01065)                                                   | ACL 2021 | [Github](https://github.com/ygan/Spider-Syn) | |
| Spider-Realistic | [Structure-Grounded Pretraining for Text-to-SQL](https://arxiv.org/abs/2010.12773)                                                                      | NAACL 2021 | | [Dataset](https://zenodo.org/records/5205322) |
| Dr.Spider   | [Dr.Spider: A Diagnostic Evaluation Benchmark towards Text-to-SQL Robustness](https://arxiv.org/abs/2301.08881)                                             | ICLR 2023  | [Github](https://github.com/awslabs/diagnostic-robustness-text-to-sql) | |
| BookSQL     | [BookSQL: A Large Scale Text-to-SQL Dataset for Accounting Domain](https://arxiv.org/abs/2406.07860)                                                        | NAACL 2024 | [Github](https://github.com/Exploration-Lab/BookSQL) | |
| Archer      | [Archer: A Human-Labeled Text-to-SQL Dataset with Arithmetic, Commonsense and Hypothetical Reasoning](https://arxiv.org/abs/2402.12554)                    | EACL 2024 | | |
| EHRSQL-2024 | [Overview of the EHRSQL 2024 Shared Task on Reliable Text-to-SQL Modeling on Electronic Health Records](https://arxiv.org/abs/2405.06673)                | ClinicalNLP 2024 | [Github](https://github.com/glee4810/ehrsql-2024) | |
| Spider-DK  | [Exploring underexplored limitations of crossdomain text-to-sql generalization](https://arxiv.org/abs/2109.05157)                                            | EMNLP 2021 | [Github](https://github.com/ygan/Spider-DK) | |
| ScienceBenchmark | [ScienceBenchmark: A Complex Real-World Benchmark for Evaluating Natural Language to SQL Systems](https://arxiv.org/abs/2306.04743)                    | VLDB Endowment 2023 | | |
| BULL        | [FinSQL: Model-Agnostic LLMs-based Text-to-SQL Framework for Financial Analysis](https://arxiv.org/abs/2401.10506)                                          | SIGMOD/PODS 2024 | [Github]() | |
| cwd-benchmark-data | [A Benchmark to Understand the Role of Knowledge Graphs on Large Language Model's Accuracy for Question Answering on Enterprise SQL Databases](https://arxiv.org/abs/2311.07509) | GRADES-NDA 24 | [Github](https://github.com/datadotworld/cwd-benchmark-data)


### MultiModal Code Generation
* **ChartMimic** : Chart-to-Code Generation

| Benchmark | Paper | Date| Github | Dataset & Website & LeaderBoard |
|:--|:--|:--|:--|:--|
| ChartMimic      | [ChartMimic: Evaluating LMM's Cross-Modal Reasoning Capability via Chart-to-Code Generation](https://arxiv.org/abs/2406.09961)                       | ICLR 2025                | [Github](https://github.com/ChartMimic/ChartMimic)        | [🌐Website](https://chartmimic.github.io) [🤗Dataset](https://huggingface.co/datasets/ChartMimic/ChartMimic) |  

* MMCode: Evaluating Multi-Modal Code Large Language Models with Visually Rich Programming Problems
* Plot2Code: A Comprehensive Benchmark for Evaluating Multi-modal Large Language Models in Code Generation from Scientific Plots
* Web2Code: A Large-scale Webpage-to-Code Dataset and Evaluation Framework for Multimodal LLMs
* ToxVI: a Multimodal LLM-based Framework for Generating Intervention in Toxic Code-Mixed Videos

### Security Code Generation & Test Generation
* **RedCode**: comprehensive and practical evaluations on the safety of code agents 
* **CodeWMBench**: benchmark for evaluating code watermarking methods in detecting AI-generated code
* **RMCBench**: benchmark to assess LLMs' resistance to generating malicious code
* **Tests4Py**: benchmark for evaluating system and unit test generation on real-world Python applications
* **PyP4LLMSec**: Python benchmark for evaluating LLM-generated code security across real-world vulnerability types
* **LLMSecGuard**: framework integrating static code analyzers with LLMs to enhance code security and benchmark LLMs' security attributes
* **CyberSecEval 3**: benchmark suite assessing LLMs' cybersecurity risks and capabilities across eight risk areas

| Benchmark | Paper | Date| Github | Dataset & Website & LeaderBoard |
|:--|:--|:--|:--|:--|
| RedCode        | [RedCode: Risky Code Execution and Generation Benchmark for Code Agents](https://arxiv.org/abs/2411.07781)                                      | NeurIPS 2024                | [Github](https://github.com/AI-secure/RedCode)        | [🌐Website](https://redcode-agent.github.io) [📊LeaderBoard](https://redcode-agent.github.io/#leaderboard) |
| CodeWMBench    | [CodeWMBench: An Automated Benchmark for Code Watermarking Evaluation](https://dl.acm.org/doi/10.1145/3674399.3674447)                          | ACM-TURC 2024 | [Github](https://github.com/Dizzy-K/CodeWMBench) | 
| RMCBench       | [RMCBench: Benchmarking Large Language Models' Resistance to Malicious Code](https://arxiv.org/abs/2409.15154)                                  | ASE 2024      | [Github](https://github.com/qing-yuan233/RMCBench) | [🤗Dataset](https://huggingface.co/datasets/zhongqy/RMCBench) |
| Tests4Py       | [Tests4Py: A Benchmark for System Testing](https://arxiv.org/abs/2307.05147)                                                                    | FSE 2024      | [Github](https://github.com/smythi93/Tests4Py) | |
| PyP4LLMSec     | [Benchmarking the Security Aspect of Large Language Model-Based Code Generation](https://llm4code.github.io/2024/assets/pdf/papers/42.pdf)    | ICSE 2024     | [Github](https://github.com/Hahappyppy2024/PyP4LLMSec) | |
| LLMSecGuard   | [LLM Security Guard for Code](https://arxiv.org/abs/2405.01103) | EASE 2024 | [Github](https://github.com/aryakvnust/LLMSecGuard) | |
| CyberSecEval 3 | [CYBERSECEVAL 3: Advancing the Evaluation of Cybersecurity Risks and Capabilities in Large Language Models](https://arxiv.org/abs/2408.01605) | Arxiv 2024/08 | [Github](https://github.com/meta-llama/PurpleLlama/tree/main/CybersecurityBenchmarks) | |

### Code Translation
* **TransCoder**: code translation in C++, Java, Python


| Benchmark | Paper | Date| Github | Dataset & Website & LeaderBoard |
|:--|:--|:--|:--|:--|
| TransCoder        | [Unsupervised Translation of Programming Languages](https://arxiv.org/abs/2006.03511)                                      | NeurIPS 2020                | [Github](https://github.com/facebookresearch/TransCoder)(deprecated) [Github](https://github.com/facebookresearch/CodeGen)(new)        |  |
* CodeTransOcean: A Comprehensive Multilingual Benchmark for Code Translation
* Enhancing LLM-based Code Translation in Repository Context via Triple Knowledge-Augmented https://arxiv.org/abs/2503.18305

### Code Version
Version-specific code generation
* **CodeUpdateEval**: code migration with Time-wise dataset                        
* **JavaVersionGenBench**: Code Completion Across Evolving JAVA Versions                
* **VersiCode**: Version-controllable Code Generation                         
* **GitChameleon**: 116 version-aware Python code-completion problems with unit tests 
* **LLM-Deprecated-APl**:  Deprecated APl mapping and functions code completion        
* **CodeUpdateArena**: API Update Knowledge Editing Assessment                      
* **LibEvolutionEval**: Version-Specifc Code Generation                              

| Benchmark | Paper | Date| Github | Dataset & Website & LeaderBoard |
|:--|:--|:--|:--|:--|
| CodeUpdateEval             | [Automatically Recommend Code Updates: Are We There Yet?](https://arxiv.org/abs/2209.07048v3)                                                |  TOSEM 2024      | [Github](https://github.com/yueyueL/CodeLM-CodeUpdateEval)                       | [🤗Dataset](https://github.com/yueyueL/CodeLM-CodeUpdateEval/tree/main/dataset) | 
| JavaVersionGenBench        | [On the Generalizability of Deep Learning-based Code Completion Across Programming Language Versions](https://arxiv.org/pdf/2403.15149)      |  ICPC 2024       | [Github](https://github.com/java-generalization/java-generalization-replication) | [🤗Dataset](https://zenodo.org/records/10057237)               | 
| VersiCode                  | [VersiCode: Towards Version-controllable Code Generation](https://arxiv.org/abs/2406.07411)                                                  |  Arxiv 2024/10   | [Github](https://github.com/wutong8023/VersiCode)                                | [🌐Website](https://wutong8023.site/VersiCode/) [🤗Dataset](https://huggingface.co/datasets/AstoneNg/VersiCode) | 
| GitChameleon               | [GitChameleon: Unmasking the Version-Switching Capabilities of Code Generation Models](https://arxiv.org/abs/2411.05830)                     |  Arxiv 2024/11   | [Github](https://github.com/NizarIslah/GitChameleon)                             | [🤗Dataset](https://github.com/NizarIslah/GitChameleon/tree/main/dataset) | 
| LLM-Deprecated-APl         | [LLMs Meet Library Evolution: Evaluating Deprecated API Usage in LLM-based Code Completion](https://arxiv.org/abs/2406.09834)                |  ICSE 2025       | [Github](https://github.com/cs-wangchong/LLM-Deprecated-API)                     | [🤗Dataset](https://figshare.com/s/e8de860d8fc2ec0541d2)       |
| CodeUpdateArena            | [CodeUpdateArena: Benchmarking Knowledge Editing on API Updates](https://arxiv.org/abs/2407.06249)                                           |  Arxiv 2025/02   | [Github](https://github.com/leo-liuzy/CodeUpdateArena)                           | [🤗Dataset](https://github.com/leo-liuzy/CodeUpdateArena/tree/main/data) | 
| LibEvolutionEval           | [LibEvolutionEval: A Benchmark and Study for Version-Specific Code Generation](https://arxiv.org/abs/2412.04478)                             |  NAACL 2025      |                                                                                 |                                                              | 

### Industry Code Generation
PLC (Programmable logic controller) & Verilog (Hardware description language) & ... (to be released soon)

* VerilogEval Evaluating Large Language Models for Verilog Code Generation
* MetRex: A Benchmark for Verilog Code Metric Reasoning Using LLMs
* Exploring Code Language Models for Automated HLS-based Hardware Generation: Benchmark, Infrastructure and Analysis
* LLM-based and Retrieval-Augmented Control Code Generation
* VHDL-Eval: A Framework for Evaluating Large Language Models in VHDL Code Generation
* VHDL-Xform; Chain-of-Descriptions: Improving Code LLMs for VHDL Code Generation and Summarization

### Multi-Dimension
* **LiveCodeBench**: self-repair, code execution, test output prediction, code generation
* **RACE**: Readability, Maintainability, Correctness, and Efficiency 

| Benchmark | Paper | Date| Github | Dataset & Website & LeaderBoard |
|:--|:--|:--|:--|:--|
| LiveCodeBench | [LiveCodeBench: Holistic and Contamination Free Evaluation of Large Language Models for Code](https://arxiv.org/abs/2403.07974)  | Arxiv 2024/03 | [Github](https://github.com/LiveCodeBench/LiveCodeBench) | [🤗Dataset](https://huggingface.co/livecodebench) |  
| RACE          | [Beyond Correctness: Benchmarking Multi-dimensional Code Generation for Large Language Models](https://arxiv.org/abs/2407.11470) | Arxiv 2024/07 | [Github](https://github.com/jszheng21/RACE)              | [📊LeaderBoard](https://huggingface.co/spaces/jszheng/RACE_leaderboard) | 

* CODEEDITORBENCH: EVALUATING CODE EDITING CAPABILITY OF LARGE LANGUAGE MODELS
* AnalogCoder: Analog Circuit Design via Training-Free Code Generation
