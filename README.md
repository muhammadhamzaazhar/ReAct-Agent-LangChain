# ReAct Agent from Scratch using LangChain

This project is a minimal, transparent implementation of a **ReAct (Reasoning and Acting) Agent** built manually using the [LangChain](https://github.com/langchain-ai/langchain) framework.

Instead of relying on high-level abstractions like `initialize_agent`, this repo walks through **how a ReAct agent works under the hood** — from formatting the prompt, invoking tools, to parsing LLM responses.

---

## Features

- Custom ReAct-style Prompt Template
- Tool execution (e.g., `get_text_length`)
- Manual ReAct-style reasoning/action loop
- Intermediate step tracking (scratchpad)
- Callback handler for logging LLM input/output

---

### **Note**:

> This project uses the **`mistralai/mistral-7b-instruct`** model hosted for **free via [OpenRouter](https://openrouter.ai)**.
> The model is accessed using the OpenAI-compatible API base
