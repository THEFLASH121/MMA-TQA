# MMA-TQA Prompt Templates

This repository contains prompt templates for the Metacognitive Multi-Agent Framework for Table Question Answering (MMA-TQA), as described in the paper (Section 3.1-3.6). Each JSON file corresponds to a specific agent or sub-module, including the prompt template, example input/output, and design rationale.

## Directory Structure
- `metacognitive_agent_prompt.json`: Strategy selection and coordination (Section 3.1).
- `metadata_extraction_agent_prompt.json`: Schema and data extraction (Section 3.2).
- `query_decomposing_agent_prompt.json`: Query decomposition (Section 3.3).
- `resolver_agent_prompts/`: Sub-module prompts for Resolver Agent (Section 3.4).
  - `direct_llm_prompt.json`: Direct LLM prompting.
  - `rag_prompt.json`: Retrieval-Augmented Generation.
  - `text_to_sql_prompt.json`: SQL generation.
  - `text_to_code_prompt.json`: Python code generation.
- `critic_agent_prompts/`: Sub-module prompts for Critic Agent (Section 3.5).
  - `symbolic_logic_prompt.json`: FOL/SMT validation.
  - `code_error_prompt.json`: Code error checking.
  - `answer_critic_prompt.json`: Answer evaluation.
- `memory_agent_prompt.json`: Memory encoding and reflection (Section 3.6).
