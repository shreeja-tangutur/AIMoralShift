AIMoralShift

AIMoralShift explores how large language models (LLMs) change their stated positions during multi-turn conversations, especially under different persuasion strategies.

Overview

This project analyzes moral drift in AI systems, when models shift away from their original stance after interacting with users.

We evaluate how different prompting techniques (e.g., ethical reminders, self-consistency, persuasion strategies) influence model responses across multiple turns.

Goals
Measure when LLMs change their positions
Compare stability across models (e.g., GPT, Claude, Gemini, DeepSeek)
Evaluate effectiveness of persuasion strategies
Identify patterns of inconsistent reasoning or drift

Tech Stack
Python
Prompt engineering workflows
LLM APIs (OpenAI, Anthropic, etc.)

Project Structure
AIMoralShift/
- QUESTIONS/        # Base questions used for experiments
- SCRIPTS/          # Automation scripts for running tests
- RESULTS/          # Output data from model responses
- MILESTONES/       # Project planning + progress tracking
- AI prompting strategies.pdf  # Strategy definitions
- README.md
- LICENSE

How to Run
Clone the repo:
git clone https://github.com/shreeja-tangutur/AIMoralShift
Navigate into the project:
cd AIMoralShift
Run experiment scripts:
python scripts/run_experiments.py
