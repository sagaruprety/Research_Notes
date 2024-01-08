# Research_Notes
AI research papers and notes

## [Reasoning with Language Model Prompting: A Survey](./Papers/LLM_Reasoning_by_Prompting_Survey_ACL_2023.pdf)
1. Reasoning abilities in pre-trained large language models can be unlocked by prompting strategies.
2. Two broad categories of methods for enhanching reasoning in LLMs via prompting:

    a. Strategy-enhanced prompting

    b. Knowledge-enchanced prompting

### Strategy-enhanced prompting:
As the name suggests, it is about devising an effective strategy for prompting, to enable LLMs to give desired responses via adequate reasoning. This method category has three specific sub-methods:
1. #### Prompt Engineering:
    Perhaps the most popular and well-known method of eliciting reasoning based responses in LLMs. This method is further divided into two:

   a. **Single-stage prompts**: Template based prompting. Including Chain-of-Thought (CoT) prompting. Leverages in-context learning ability of LLMs. In-context learning is greatly sensitive to the selection of exemplars, and even a tiny
change may cause a large drop in model performance.

   b. **Multi-stage prompts**: Decompose a complex problem into sim-
pler ones and to reason stage by stage. Similarly,
this series of works aims to transform one-stage
prompting (once input-output) into multi-stage
prompting (multi-times of input-output)

2. Process Optimisation:
    a. Iterative Optimisation
   
        1. **SELF-REFINE: Iterative Refinement with Self-Feedback**:
   
        2. **Reflexion: Language Agents with Verbal Reinforcement Learning**:
   
        3. **REFINER: Reasoning Feedback on Intermediate Representations**: 

4. 
