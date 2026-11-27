# The Daily AI Drop — Morning Edition, November 27, 2026

A quiet overnight across the fifteen channels, but the two videos that did land are both worth your time: Tencent's DFly2 makes AI inference about 4.2× faster, and Google's AI agent rewrote its own harness, jumping from solving 5% of held-out tasks to 40% — without changing the model at all.

Listen: https://muse.ai/podcasts/media/1180242951829162/4c015424-5891-46ff-a366-0f9e546ae170/ep-6e4f7475-1a87-46c8-a364-55ba57667b4b.mp3

## Fahd Mirza — Tencent DFly2: 4.2× Faster AI Inference

https://www.youtube.com/watch?v=qAD0Pi9grSc

DFly2 speeds up AI inference by drafting predictions from the big model's own internal memory instead of relying on a separate small draft model, so far more of its guesses match what the big model would actually produce. That matters because inference — every answer you wait for — is the part of AI you actually feel, and a 4.2× speed-up makes everything from coding assistants to voice agents snappier and cheaper to run at scale. Fahd also puts the headline number in context, walking through the baseline, which workloads benefit most, and where the gains might shrink.

## Aish Reganti — Google's AI agent rewrote its own harness: 5% to 40%

https://www.youtube.com/shorts/5cqh54tKw6Y

Google researchers froze a Gemini model and let another AI rewrite the code around it — the harness that organizes planning, tool calls, and self-checking. With the model weights untouched, the coding agent went from solving 5% of held-out tasks to 40%, an eightfold improvement from better scaffolding alone. It is a vivid reminder that a huge share of real-world AI performance lives in the engineering around the model, not just in bigger training runs — and a small taste of recursive improvement, where AI tools get better at building the tools that make AI better.
