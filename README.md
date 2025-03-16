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

## News
- 🔥🔥 **[2025-03-16]** A thorough review of code domain benchmarks for LLM research has been released.

## 🚀 Top Code Benchmark

### Code Completion & Code Generation

|<center>Benchmark</center>       | <center>Paper</center>              | <center>Source</center>        | <center>Github</center> | Dataset & Website & LeaderBoard | Comments |
|:---------------|:-----------------------------------------------------------------------|:------------------------------------------------------------|:--|:--|:--|
| HumanEval     | [Evaluating Large Language Models Trained on Code](https://arxiv.org/abs/2107.03374) [Arxiv 2021-07]                                                                                               | [Paper](https://arxiv.org/abs/2107.03374) Arxiv 2021-07                  | [Github](https://github.com/openai/human-eval)| [Huggingface](https://huggingface.co/datasets/openai/openai_humaneval) | code completion |
| MBPP          | Program Synthesis with Large Language Models                                                                                                    | [Paper](https://arxiv.org/abs/2108.07732) Arxiv 2021-08                  | | [Huggingface](https://huggingface.co/datasets/google-research-datasets/mbpp) | text -> code |
| EvalPlus      | Is Your Code Generated by Chat{GPT} Really Correct? <br> Rigorous Evaluation of Large Language Models for Code Generation                       | [Paper](https://arxiv.org/abs/2305.01210) NeruIPS 2023                  | [Github](https://github.com/evalplus/evalplus)| [Huggingface](https://huggingface.co/evalplus) | Extend of HumanEval and MBPP |
| MultiPL-E     | MultiPL-E: A Scalable and Polyglot Approach to Benchmarking Neural Code Generation. | [Paper](https://ieeexplore.ieee.org/abstract/document/10103177) TSE 2023 | [Github](https://github.com/nuprl/MultiPL-E) | [Huggingface](https://huggingface.co/datasets/nuprl/MultiPL-E) | Extends the HumanEval and MBPP benchmarks to 18 languages |
| BigCodeBench  | BigCodeBench: Benchmarking Code Generation with Diverse Function Calls and Complex Instructions                                                 | [Paper](https://arxiv.org/abs/2406.15877) ICLR 2025 | [Github](https://github.com/bigcode-project/bigcodebench) | [LeaderBoard](https://huggingface.co/spaces/bigcode/bigcodebench-leaderboard) | Complete Split & Instruct Split| 
| DevEval       | DevEval: A Manually-Annotated Code Generation Benchmark Aligned with Real-World Code Repositories                                               | [Paper](https://arxiv.org/abs/2405.19856) ACL 2024  | [Github](https://github.com/seketeam/DevEval)             | [Huggingface](https://huggingface.co/datasets/LJ0815/DevEval/blob/main/Source_Code.tar.gz)| Repo-level code generation


<!-- ### Code Generation (Text to Code)
|<center>Benchmark</center>       | <center>Paper</center>              | <center>Source</center>        | <center>Github</center> | HuggingFace |
|:---------------|:-----------------------------------------------------------------------|:------------------------------------------------------------|:--|:--|
| MBPP     | Program Synthesis with Large Language Models                        | [Paper](https://arxiv.org/abs/2108.07732) Arxiv 2021-08                  | | [Huggingface](https://huggingface.co/datasets/google-research-datasets/mbpp) | -->

### Code Efficiency
|<center>Benchmark</center>       | <center>Paper</center>              | <center>Source</center>        | <center>Github</center> | Dataset & Website & LeaderBoard |
|:---------------|:-----------------------------------------------------------------------|:------------------------------------------------------------|:--|:--|
| EvalPerf      | Evaluating Language Models for Efficient Code Generation                                        | [Paper](https://arxiv.org/abs/2408.06450)  COLM 2024                  | [Github](https://github.com/evalplus/evalplus)        | [Huggingface](https://huggingface.co/datasets/evalplus/evalperf) |
| EffiBench     | EffiBench: Benchmarking the Efficiency of Automatically Generated Code                          | [Paper](https://arxiv.org/abs/2402.02037)  NeurIPS 2024               | [Github](https://github.com/huangd1999/EffiBench)     |  |
| Mercury       | Mercury: A Code Efficiency Benchmark for Code Large Language Models                             | [Paper](https://arxiv.org/abs/2402.07844v4) NeurIPS 2024              | [Github](https://github.com/Elfsong/Mercury)          | [Huggingface](https://huggingface.co/datasets/Elfsong/Mercury) |
| ECCO          | ECCO: Can We Improve Model-Generated Code Efficiency Without Sacrificing Functional Correctness?| [Paper](https://arxiv.org/abs/2407.14044) EMNLP 2024                  | [Github](https://github.com/CodeEff/ECCO)             | [Huggingface](https://huggingface.co/datasets/CodeEff/ECCO)|
| PIE           | Learning Performance-Improving Code Edits                                                       | [Paper](https://arxiv.org/abs/2302.07867) ICLR 2024                   | [Github](https://github.com/LearningOpt/pie)          | [Website](https://pie4perf.com)|  
| ENAMEL        | How Efficient is LLM-Generated Code? A Rigorous & High-Standard Benchmark                       | [Paper](https://arxiv.org/abs/2406.06647) ICLR 2025                   | [Github](https://github.com/q-rz/enamel)              | [Huggingface](https://huggingface.co/datasets/q-rz/enamel) |

### CodeFix & Bug-Fix
|<center>Benchmark</center>       | <center>Paper</center>              | <center>Source</center>        | <center>Github</center> | Dataset & Website & LeaderBoard | Comments|
|:---------------|:-----------------------------------------------------------------------|:------------------------------------------------------------|:--|:--|:--|
| HumanEvalFix      | OctoPack: Instruction Tuning Code Large Language Models                                       | [Paper](https://arxiv.org/abs/2308.07124) Arxiv 2023-08                  | [Github](https://github.com/bigcode-project/octopack)        | [Huggingface](https://huggingface.co/datasets/bigcode/humanevalpack) |  code repair capabilitie |
| SWT-Bench         | SWT-Bench: Testing and Validating Real-World Bug-Fixes with Code Agents                       | [Paper](https://arxiv.org/abs/2406.12952) NeurIPS 2024                   | [Github](https://github.com/logic-star-ai/SWT-Bench)         | [Website](https://swtbench.com) | Evaluating LLMs on testing generation for real world software issues |
| SWE-bench         | SWE-bench: Can Language Models Resolve Real-World GitHub Issues?                              | [Paper](https://arxiv.org/abs/2310.06770) ICLR 2024                      | [Github](https://github.com/swe-bench/SWE-bench)             | [Website](https://www.swebench.com) | Evaluating LLMs Resolve Real-World GitHub Issues |
| SWE-bench Multimodal  | SWE-bench Multimodal: Do AI Systems Generalize to Visual Software Domains?                | [Paper](https://arxiv.org/abs/2410.03859) ICLR 2025                      | [Github](https://github.com/swe-bench/SWE-bench)             | [Website](https://www.swebench.com/multimodal) [Huggingface](https://www.swebench.com/multimodal) | Evaluate LLMs on their ability to fix bugs in visual, user-facing JavaScript software | 

### Code Reasoning & Understanding
|<center>Benchmark</center>       | <center>Paper</center>              | <center>Source</center>        | <center>Github</center> | Dataset & Website & LeaderBoard | Comments|
|:---------------|:-----------------------------------------------------------------------|:------------------------------------------------------------|:--|:--|:--|
| CRUXEval      | CRUXEval: A Benchmark for Code Reasoning, Understanding and Execution                                       | [Paper](https://arxiv.org/abs/2401.03065) Arxiv 2024-01                 | [Github](https://github.com/facebookresearch/cruxeval)        | [LeaderBoard](https://crux-eval.github.io/leaderboard.html) |  code reasoning, understanding, and execution capabilities |
| CodeMMLU      | CodeMMLU: A Multi-Task Benchmark for Assessing Code Understanding Capabilities of CodeLLMs                  | [Paper](https://arxiv.org/abs/2410.01999) ICLR 2025                     | [Github](https://github.com/FSoft-AI4Code/CodeMMLU/)          | [Huggingface](https://huggingface.co/datasets/Fsoft-AIC/CodeMMLU) [LeaderBoard](https://fsoft-ai4code.github.io/leaderboards/codemmlu/) [Website](https://fsoft-ai4code.github.io/codemmlu/) | code understanding and comprehension|

### Data science
|<center>Benchmark</center>       | <center>Paper</center>              | <center>Source</center>        | <center>Github</center> | Dataset & Website & LeaderBoard | Comments|
|:---------------|:-----------------------------------------------------------------------|:------------------------------------------------------------|:--|:--|:--|
| DS-1000      | DS-1000: A Natural and Reliable Benchmark for Data Science Code Generation                                      | [Paper](https://arxiv.org/abs/2211.11501) ICML 2023                 | [Github](https://github.com/xlang-ai/DS-1000)        | [HomePage](https://ds1000-code-gen.github.io) [Huggingface](https://huggingface.co/datasets/xlangai/DS-1000)  |  Data Science Code Generation|
| DA-Code      | DA-Code: Agent Data Science Code Generation Benchmark for Large Language Models                                 | [Paper](https://arxiv.org/abs/2410.07331) EMNLP 2024                | [Github](https://github.com/yiyihum/da-code)         | [Website](https://da-code-bench.github.io) [Huggingface](https://huggingface.co/datasets/Jianwen2003/DA-Code) | data science tasks; |


### Text2SQL 
|<center>Benchmark</center>       | <center>Paper</center>              | <center>Source</center>        | <center>Github</center> | Dataset & Website & LeaderBoard | Comments|
|:---------------|:-----------------------------------------------------------------------|:------------------------------------------------------------|:--|:--|:--|
| Spider      | Spider: A Large-Scale Human-Labeled Dataset for Complex and Cross-Domain Semantic Parsing and Text-to-SQL Task                                      | [Paper](https://arxiv.org/abs/1809.08887) EMNLP 2018                 | [Github](https://github.com/taoyds/spider)        | [Homepage](https://yale-lily.github.io/spider) | text-to-SQL |
| Spider 2.0  | Spider 2.0: Evaluating Language Models on Real-World Enterprise Text-to-SQL Workflows  | [Paper](https://arxiv.org/abs/2411.07763) ICLR 2025 | [Github](https://github.com/xlang-ai/Spider2) | [Website](https://spider2-sql.github.io) | text-to-SQL |


### MultiModal Code Generation
|<center>Benchmark</center>       | <center>Paper</center>              | <center>Source</center>        | <center>Github</center> | Dataset & Website & LeaderBoard | Comments|
|:---------------|:-----------------------------------------------------------------------|:------------------------------------------------------------|:--|:--|:--|
| ChartMimic      | ChartMimic: Evaluating LMM's Cross-Modal Reasoning Capability via Chart-to-Code Generation                                      | [Paper](https://arxiv.org/abs/2406.09961) ICLR 2025                | [Github](https://github.com/ChartMimic/ChartMimic)        | [Website](https://chartmimic.github.io) [Huggingface](https://huggingface.co/datasets/ChartMimic/ChartMimic) |  Chart-to-Code Generation|

### Security Code Generation
|<center>Benchmark</center>       | <center>Paper</center>              | <center>Source</center>        | <center>Github</center> | Dataset & Website & LearderBoard | Comments|
|:---------------|:-----------------------------------------------------------------------|:------------------------------------------------------------|:--|:--|:--|
| RedCode        | RedCode: Risky Code Execution and Generation Benchmark for Code Agents                                      | [Paper](https://arxiv.org/abs/2411.07781) NeurIPS 2024                | [Github](https://github.com/AI-secure/RedCode)        | [Website](https://redcode-agent.github.io) [LeaderBoard](https://redcode-agent.github.io/#leaderboard) |  comprehensive and practical evaluations on the safety of code agents |



### Code Version
Version-specific code generation (to be released soon)

### Industry Code Generation
PLC (Programmable logic controller) & Verilog (Hardware description language) & ... (to be released soon)

### Other
|<center>Benchmark</center>       | <center>Paper</center>              | <center>Source</center>        | <center>Github</center> | Dataset & Website & LeaderBoard | Comments|
|:---------------|:-----------------------------------------------------------------------|:------------------------------------------------------------|:--|:--|:-- |
| LiveCodeBench | LiveCodeBench: Holistic and Contamination Free Evaluation of Large Language Models for Code | [Paper](https://arxiv.org/abs/2403.07974) Arxiv 2024-03 | [Github](https://github.com/LiveCodeBench/LiveCodeBench) | [Huggingface](https://huggingface.co/livecodebench) | self-repair, code execution, test output prediction, code generation| 
| RACE          | Beyond Correctness: Benchmarking Multi-dimensional Code Generation for Large Language Models | [Paper](https://arxiv.org/abs/2407.11470) Arxiv 2024-07 | [Github](https://github.com/jszheng21/RACE) | [LeaderBoard](https://huggingface.co/spaces/jszheng/RACE_leaderboard) | Readability, Maintainability, Correctness, and Efficiency | 
<!-- | MultiPL-E     | MultiPL-E: A Scalable and Polyglot Approach to Benchmarking Neural Code Generation. | [Paper](https://ieeexplore.ieee.org/abstract/document/10103177) TSE 2023 | [Github](https://github.com/nuprl/MultiPL-E) | [Huggingface](https://huggingface.co/datasets/nuprl/MultiPL-E) | Extends the HumanEval and MBPP benchmarks to 18 languages | -->
<!-- | EvalPlus      | Is Your Code Generated by Chat{GPT} Really Correct? <br> Rigorous Evaluation of Large Language Models for Code Generation                       | [Paper](https://arxiv.org/abs/2305.01210) NeruIPS 2023                  | [Github](https://github.com/evalplus/evalplus)| [Huggingface](https://huggingface.co/evalplus) | Extend of HumanEval and MBPP | -->
<!-- | BigCodeBench  | BigCodeBench: Benchmarking Code Generation with Diverse Function Calls and Complex Instructions | [Paper](https://arxiv.org/abs/2406.15877) ICLR 2025 | [Github](https://github.com/bigcode-project/bigcodebench) | [LeaderBoard](https://huggingface.co/spaces/bigcode/bigcodebench-leaderboard) | Complete Split & Instruct Split|  -->