# The Daily AI Drop — Evening Edition, November 6, 2026

**Listen:** https://muse.ai/podcasts/media/1180242951829162/4c015424-5891-46ff-a366-0f9e546ae170/ep-f18046a0-c7f1-4a0c-8c22-e88c17be050e.mp3

Two new videos this afternoon, and they fit together: Siraj Raval tests whether giving an AI agent live internet access beats answering from memory, and OpenAI introduces LifeVal, a benchmark for the everyday tasks people actually want help with. Alex and Jordan find the thread connecting them — grounding AI in the real world instead of the demo.

## I Gave My AI Agent Live Internet Access (Here Is What Broke First) — Siraj Raval

https://www.youtube.com/watch?v=ibdmyMFd_z8

Siraj runs the same agent twice on the same prompts: once answering from training data alone, once searching the live internet through the Oxylabs Web API, scored across four rounds plus a two-hour mission to find something he could actually buy. The blind agent is confident and wrong — it quotes prices that moved, libraries that changed, and listings that are already gone — while the cited agent opens the actual page, reads it, and links every claim to its source. The practical detail that matters: the search tool returns clean markdown instead of raw HTML, so the model does not burn its context window before it gets to think. A sponsored video, but the experiment makes the training-cutoff problem concrete: a stale answer is not an abstract limitation, it is a wrong price or a dead link.

## LifeVal: Measuring AI progress on the tasks that matter in everyday life. — OpenAI

https://www.youtube.com/watch?v=hJOwOkLHRN0

OpenAI built a new benchmark, LifeVal, shaped by feedback from thousands of ChatGPT users about where they most want help from a personal assistant — finding childcare, accessing government services, managing personal finances. Instead of starting with what is easy to grade, it measures progress on the everyday tasks people actually care about, the ones where getting it wrong has consequences. OpenAI says it has used LifeVal over the past year to measure progress. If you are choosing what to build next, this is the strategic counterpoint to Siraj's video: the unglamorous tasks people ask for help with are exactly the ones worth measuring.
