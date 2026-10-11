# The Daily AI Drop — Evening Edition, October 10, 2026

Three new videos landed this afternoon, and there's a real theme tonight: the gap between the biggest models in the world and the laptop on your desk keeps shrinking, while inside the biggest companies, the coding agent is quietly becoming everyone's coworker.

Listen: https://muse.ai/podcasts/media/1180242951829162/4c015424-5891-46ff-a366-0f9e546ae170/ep-20eeeb90-c97f-4ba1-bc78-1b539106c406.mp3

## Underdog Saluki 27B 1.0 Locally: Beyond Qwen and GSQ+RCO — Fahd Mirza

https://www.youtube.com/watch?v=96WTWX_inRY

Underdog (Conway Research) released Saluki 27B, a roughly 2-bit quantized version of Qwen3.8-27B that shrinks fifty-four gigabytes down to under eight — small enough to run on a laptop with sixteen gigabytes of RAM via stock llama.cpp, under the Apache 2.0 license. The quantization method (GSQ-RCO, from ISTA-DASLab in Austria) decides tensor by tensor what can survive at two bits, and Underdog tuned it specifically to protect tool calling — the skill that turns a chat model into an agent. On a standard tool-calling benchmark the little model actually beat the full-size original. The catch: competition math and complex reasoning dip. Fahd tests it locally, and it's the week's clearest data point that the frontier is moving to your desk.

## Everything has been solved — Matthew Berman

https://www.youtube.com/watch?v=cX2kD2yQf88

Berman's seventeen-minute AI news roundup with a deliberately provocative title. His thesis: this week's releases have closed the remaining gaps people kept pointing at — local models matching cloud models, agents doing real office work, creative apps getting rebuilt by AI. Best read as a mood check rather than a technical claim: not that everything is solved, but that the excuses are running out.

## How Oracle Uses Codex to Help Business Users Get Answers — OpenAI

https://www.youtube.com/watch?v=Ju-JyxDgV7g

OpenAI's case study on Oracle: one hundred thirty thousand active ChatGPT users and more than ninety-five thousand active Codex users inside the company. Oracle's Applications Lab built an internal map of their business objects and rules, which Codex uses to turn a plain-English question from a non-technical person into a real SQL query and report — no IT ticket, no two-week wait. Site reliability engineers use Codex to gather incident context and find the right playbook, and talent-acquisition research that took two to four days now takes fifteen to twenty minutes (a ninety-eight percent cut). Oracle's own caveat, included in the case study: humans stay responsible for architecture, security, and maintainable code — the agent drafts, people decide.
