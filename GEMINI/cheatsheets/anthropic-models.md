# Cheatsheet: Anthropic (Claude)

Claude models are renowned for their large context windows, strong performance in coding and technical tasks, and a more "thoughtful" and less "sycophantic" conversational style.

| Model | Strength & Speciality | When to Use |
| --- | --- | --- |
| **Claude 3.5 Sonnet** | **Speed and Intelligence for the Price.** Anthropic's latest and most balanced model. It's faster than their previous top-tier model (Opus) and sets a new standard for intelligence in a "workhorse" model. It excels at coding, complex instructions, and content creation with a nuanced voice. | **Your new default for most tasks.** It's a strong competitor to GPT-4o and is excellent for coding, drafting documents, and as a general-purpose assistant. Its speed makes it ideal for interactive use. |
| **Claude 3 Opus** | **Maximum Intelligence and Analysis.** The most powerful model in the Claude 3 family, excelling at tasks requiring deep reasoning and analysis of large amounts of data. It has a massive 200K token context window. | **For your most demanding analytical tasks.** Analyzing lengthy legal documents, financial reports, or entire codebases. Use it when you need the highest level of comprehension and reasoning over a large body of information. |
| **Claude 3 Haiku** | **Speed and Cost-Effectiveness.** The fastest and most affordable model in the Claude 3 family. It's ideal for simple, repetitive tasks that need to be done quickly and at a low cost. | **For building lightweight, fast chatbots or automating simple summarization or data extraction tasks via the API.** |

## For Your Workflow

* **Claude CLI:** The Claude CLI is excellent for interacting with your codebase. Use Claude 3.5 Sonnet within the CLI for tasks like explaining code, suggesting refactors, and answering technical questions. For analyzing an entire repository, you might leverage the larger context window of Claude 3 Opus. The "Artifacts" feature in the web UI is also a powerful tool for iterative development.
