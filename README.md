# Prompt Engineering Project: The "Fictional Interviewer"

This project focuses on controlling Large Language Models (LLMs) through complex system instructions, role-playing, and enforced constraints to achieve specific, consistent output behavior.

## Goal

To create a "Master Prompt" that forces an LLM to adopt a consistent persona (a fictional character) and adhere to a strict set of rules while performing a structured task (a job interview). This demonstrates mastery over the LLM's style, format, and content generation.

## Artifacts

| Filepath | Description | Key Techniques Demonstrated |
|----------|----------|----------|
| holmes_interviewer.md | Master prompt for the Sherlock Holmes Persona (Hyper-skeptical, verbose, constraint setting). | System Prompting, Constraint Guardrails. |
| batman_interviewer.md | Master prompt for the Batman Persona (Strategic, minimalist dialogue, high-pressure, non-contracted speech). | Dialogue Constraint, Chain-of-Thought (CoT), Character Consistency. |

## Key Takeaways

How to use Chain-of-Thought (CoT) to force internal planning by the model.

The effectiveness of negative constraints (e.g., "Do not use contractions," "Ask exactly four questions").

The use of a clear, multi-part structure to prevent model drift (the LLM forgetting its role).