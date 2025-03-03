# Direct Preference Optimisation with Compiler Feedback: Your Language Model Is Secretly a Compiler

### Abstract
Programming serves as a potent and ubiquitous problem-solving tool. Enhancing its productivity and accessibility through systems capable of aiding programmers or even autonomously generating code stands as a significant goal. However, integrating AI innovations into this domain has presented challenges. While recent advancements in large language models (LLMs) showcase remarkable code generation capabilities for simpler tasks, they often falter when tasked with producing correct code in compiled languages like C++. In this paper, we propose a straightforward approach that leverages synthetic preference data obtained via compiler feedback to train existing language models in writing compilable code. Our method uses Direct Preference Optimisation (DPO) to improve the performance of a wide range of models. It also consistently surpasses traditional supervised fine-tuning techniques (SFT). Altogether, in terms of compilation success, we achieve improvements ranging 48\% to 234\% compared to base models, and 6\% to 154\% compared to SFT.

### Report
View the full report [here](https://github.com/jain-hl/dpo-llm-compiler-feedback/blob/main/DPO_with_compiler_feedback_your_language_model_is_secretly_a_compiler.pdf).

### Code
View the full code [here](https://github.com/Philippe-Guyard/COMP0087).
