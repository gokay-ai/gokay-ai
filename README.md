<picture>
  <source media="(max-width: 600px)" srcset="./assets/header-mobile.svg" />
  <img src="./assets/header.svg" width="100%" alt="Gökay Yılmaz — AI Engineer. Beyond the demo. Into the infrastructure." />
</picture>

**I don't stop at using the AI stack. I build on it—and fix what breaks underneath.**

I'm Gökay, an AI engineer working across **LLM infrastructure, autonomous agents, and developer tools**. From fine-tuning and RAG at Halkbank to upstream fixes in open-source AI, I work where model capability meets engineering reality.

**Build the tool. Trace the failure. Ship the fix.**

[My projects](#building) · [Open-source work](#selected-open-source-contributions) · [X](https://x.com/gokayai) · [LinkedIn](https://www.linkedin.com/in/gokay-ai/)

## Selected open-source contributions

### Merged upstream

**[Hermes Agent · Nous Research](https://github.com/NousResearch/hermes-agent/pull/95980)**  
**Agent infrastructure that recovers.** Fixed interrupted-update recovery so pending gateway restarts complete on the next run—even when Git already reports up to date. Original contribution incorporated upstream with co-author credit.  
[View merged work ↗](https://github.com/NousResearch/hermes-agent/pull/95980)

**[OpenClaw](https://github.com/openclaw/openclaw/pull/133888)**  
**Recovery instead of failed turns.** Fixed llama.cpp context-overflow detection to enable session compaction and retry. Also repaired plugin-catalog routing for direct navigation and refresh.  
[Agent recovery ↗](https://github.com/openclaw/openclaw/pull/133888) · [Catalog routing ↗](https://github.com/openclaw/openclaw/pull/144740)

**[Unsloth](https://github.com/unslothai/unsloth/pull/9358)**  
**Get past installation. Get to the model.** Fixed Studio's Linux installation fallback when distro `uv` policy blocks automatic Python downloads.  
[View merged work ↗](https://github.com/unslothai/unsloth/pull/9358)

**[Cherry Studio](https://github.com/CherryHQ/cherry-studio/pull/19874)**  
**Correctness at the data boundary.** Fixed schema validation that broke knowledge-base listing when a database contained zero documents.  
[View merged work ↗](https://github.com/CherryHQ/cherry-studio/pull/19874)

### Ongoing contributions

Open pull requests across inference, training, and agent systems—not yet merged.

- **[vLLM](https://github.com/vllm-project/vllm/pulls?q=is%3Apr+author%3Agokay-ai)** — KV-cache accounting for hidden-state extraction.
- **[SGLang](https://github.com/sgl-project/sglang/pulls?q=is%3Apr+author%3Agokay-ai)** — Disaggregated-serving staging, request retraction, and vision preprocessing.
- **[Hugging Face Accelerate](https://github.com/huggingface/accelerate/pulls?q=is%3Apr+author%3Agokay-ai)** — Avoiding double sharding of already-sharded data loaders.
- **[OpenHands](https://github.com/OpenHands/OpenHands/pulls?q=is%3Apr+author%3Agokay-ai)** — Claude Code ACP skill integration and agent-server reliability.
- **[LMDeploy](https://github.com/InternLM/lmdeploy/pulls?q=is%3Apr+author%3Agokay-ai)** — Safer HTTP weight updates and validation of untrusted serving inputs.
- **[LibreChat](https://github.com/danny-avila/LibreChat/pulls?q=is%3Apr+author%3Agokay-ai)** — MCP instructions, agent generation parameters, and proxy support.
- **[Jan](https://github.com/janhq/jan/pulls?q=is%3Apr+author%3Agokay-ai)** — Custom OpenAI-compatible providers and llama.cpp runtime configuration.
- **[Buzz](https://github.com/block/buzz/pulls?q=is%3Apr+author%3Agokay-ai)** — Bundled search-tool compatibility.

[Explore the work →](https://github.com/pulls?q=is%3Apr+author%3Agokay-ai+is%3Apublic)

## Building

### [Sheep](https://github.com/gokay-ai/sheep) · Undo for AI coding agents

**Agents move fast. Developers should keep control.**

Turn-level checkpoints and worktree-scoped restores, written in **Rust**. Inspect the plan, rewind an agent's changes, and notify it of the restored state. Explicit previews. Scoped restores. Git metadata untouched.

[Source](https://github.com/gokay-ai/sheep) · [Releases](https://github.com/gokay-ai/sheep/releases) · [Architecture](https://github.com/gokay-ai/sheep/blob/main/docs/architecture.md)

### [Claude Code Sound Notifications](https://github.com/gokay-ai/claude-code-sound-notifications)

**Your agent finished. You should know.**

Native completion notifications for macOS and Linux through Claude Code's `Stop` hook. Built for terminal-heavy workflows, including Ghostty, tmux, and Zellij.

## Engineering focus

**Python · Rust · TypeScript · PyTorch · Docker · Linux**

LLM fine-tuning and RAG experience at **Halkbank**. Studying **Artificial Intelligence at the University of Birmingham**, graduating in 2027. Building toward agents with better memory, measurable behavior, and recoverable workflows.

---

**Building serious AI infrastructure or developer tools? Let's talk.**  
[X / @gokayai](https://x.com/gokayai) · [LinkedIn](https://www.linkedin.com/in/gokay-ai/)
