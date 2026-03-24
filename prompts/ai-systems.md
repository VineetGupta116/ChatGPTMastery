# AI Systems & Prompt Engineering Prompts

> Domain: Prompt Design, Agent Orchestration, System Prompts, Evaluation

---

## System Prompt Design
```
Design a system prompt for an AI agent with this role: [describe role].
Requirements:
- Tone and persona
- Scope boundaries (what it should/shouldn't do)
- Output format defaults
- Error handling behavior
- Memory/context utilization instructions

Output as a ready-to-deploy system prompt block.
```

## Prompt Evaluation Framework
```
Evaluate this prompt across 5 dimensions:
1. Clarity of intent
2. Constraint completeness
3. Output format specificity
4. Ambiguity risk
5. Token efficiency

Score each 1-10. Rewrite the prompt with improvements.

[paste prompt]
```

## Reverse Prompt Engineering
```
Based on this AI response, reverse-engineer the most likely prompt
that produced it. Then suggest a better prompt that would yield
a more precise or useful output.

[paste AI response]
```

## Multi-Agent Orchestration Design
```
Design a multi-agent workflow for [task].
Specify:
- Agent roles and responsibilities
- Handoff triggers between agents
- Shared memory/context requirements
- Error recovery logic
- Output aggregation method

Format as a workflow diagram description + agent spec table.
```

## Chain-of-Thought Activation
```
Before answering, think step by step:
1. What is actually being asked?
2. What hidden assumptions exist in this question?
3. What are 3 different valid approaches?
4. What are the trade-offs of each?
5. Now give your recommended answer with reasoning.

Question: [your question]
```

## Prompt Library Taxonomy
```
Organize this set of prompts into a logical taxonomy.
Group by: use case, complexity level, model tier required.
Output as a structured table with columns:
Prompt Name | Category | Complexity | Best Model | Key Variables

[paste prompts]
```
