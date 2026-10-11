# Assignment 6 - Final Recommendation

## 1. Best-performing setup
DeepSeek Coder 1.3B with Ollama successfully loaded locally and generated a basic Python function. Its ability to implement the complete ELM module has not been verified.

## 2. Second-best option
Qwen2.5-Coder 7B with Ollama was attempted, but the OpenCode integration did not produce usable repository changes.

## 3. Setup to avoid
Avoid the tested Qwen/OpenCode configuration until its repository-editing and local-model integration issues are resolved.

## 4. Lessons learned
- A model generating code in a terminal does not guarantee that a coding agent can edit a real multi-file repository.
- Local model compatibility, repository access, specification handling, and build verification should all be tested separately.
