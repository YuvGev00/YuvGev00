### Hi, I'm Yuval

Final-semester Computer Science student at Reichman University (graduating February 2027), looking for **junior AI/ML and software engineering** roles in Israel. I like building systems I can measure: frozen test splits, CI on every change, and an honest list of what didn't work.

**Site:** [yuvgev.com](https://yuvgev.com) · **Email:** yuvgev1@gmail.com

#### Projects

- **[taintwall](https://github.com/YuvGev00/taintwall)**: a runtime firewall for tool-using LLM agents. A taint-tracking policy blocks side-effecting tool calls (send money, send email) whose arguments came only from untrusted tool output. On 461 held-out AgentDojo attacks against a live model that falls for them, it blocks as many as the ProtectAI detector (55.5% → 13.7%) while keeping 72% of benign tasks working versus 44%. *Python, FastAPI, Docker*
- **[Hebrew ToolBench](https://github.com/YuvGev00/hebrew-toolbench)**: a Hebrew tool-calling benchmark: 800 items over 52 Israeli-domain tools, scored by a deterministic AST scorer, with 9 models evaluated. The Hebrew calendar is the hardest part for every model, and the "wrong language for a canonical value" failure appears only in the smallest model. *Python*
- **[mini-engine](https://github.com/YuvGev00/mini-engine)**: an LLM inference engine written from scratch in PyTorch, with a paged KV cache, continuous batching, prefix caching and n-gram speculative decoding. Its greedy output is token-identical to Hugging Face, and it is benchmarked against vLLM on an L4: speculative decoding gives 4.5–4.7× on copy-heavy work. *Python, PyTorch*
- **[SubScan](https://subscan-eiu.pages.dev/)**: a Hebrew web app that finds forgotten subscriptions in the statements you export from Israeli card issuers and banks, and drafts the cancellation letters. In beta; the code is private. *TypeScript*
- **[penguin-forge](https://github.com/YuvGev00/penguin-forge)**: a real-time multiplayer world on an HTTP/WebSocket framework I hand-wrote on Node's raw `net` module, with zero dependencies. *JavaScript, Node.js*

#### Open source

- Opened [ethz-spylab/agentdojo#228](https://github.com/ethz-spylab/agentdojo/pull/228), which adds support for current Claude models to AgentDojo (under review).
