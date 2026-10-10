# The Daily AI Drop — Morning Edition, October 8, 2026

Alex and Jordan break down six overnight AI videos: LangChain on agent skills and OpenAI's hidden prompt-cache ceiling, Claude Haiku 5.5 going ten times cheaper and taking on GPT 6 Luna, Nate B. Jones asking whether Google can catch up, and Fahd Mirza testing a tiny local multimodal decision model.

Listen: https://muse.ai/podcasts/feed/1180242951829162/4c015424-5891-46ff-a366-0f9e546ae170

## What is an agent skill? How to protect your agent's context window
**Channel:** LangChain — https://www.youtube.com/watch?v=1BfAsoVz32Q

Most agents fail not because the model is dumb, but because the context window gets clogged with noise. Agent skills are the fix: little packaged bundles of knowledge an agent loads only when it needs them. This video draws the line between a long-running agent that executes complex tasks cleanly and one that constantly gets stuck — the difference is almost always context discipline.

## OpenAI's Prompt Cache Has a Secret 15 RPS Ceiling
**Channel:** LangChain — https://www.youtube.com/watch?v=sjKDovLb23Q

Prompt caching can make an OpenAI API call 90% cheaper — but only if you actually hit the cache. Unify CTO Connor Heggie explains the limit most builders miss: the cache key tops out around 15 requests per second. A real-world follow-up to the DevDay cost-cutting sessions — go check your request patterns, because there's a ceiling you didn't know about.

## NEW Anthropic Model 10X Cheaper Than Last
**Channel:** Mehul Mohan (mehulmpt) — https://www.youtube.com/watch?v=PC5y-jxQ0k0

Claude Haiku 5.5 is Anthropic's new cheapest and fastest small model — ten times cheaper than the last one. The big flagship models get the headlines, but the small models are where the bills get paid, and this price-to-performance story matters for anyone picking a default small model for their app.

## Claude Haiku 5.5 beats GPT 6 Luna?
**Channel:** Mehul Mohan (mehulmpt) — https://www.youtube.com/watch?v=oy1O_S9n-y8

The head-to-head version of the Haiku 5.5 story: can Anthropic's tiny cheap model trade punches with OpenAI's small model, GPT 6 Luna? A follow-up angle to Fahd Mirza's real-world Haiku 5.5 test from the evening edition — now the question is whether cheap also means good enough against OpenAI's offering.

## Can Google still catch up? Argon is entering the chat
**Channel:** Nate B. Jones — https://www.youtube.com/watch?v=EZAugIwI1Do

The name Argon comes from the Greek word for idle — a fun little dig — but the real question Nate raises is whether you can catch up in AI once you've fallen this far behind. The skeptical counterpoint to his longer video on Gemini 4 Argon topping the Vals Index leaderboard: at some point the leaderboard stops being the story and the products start being the story.

## d1-omni-600M Locally: A Decision Model for Audio, Vision, and Text
**Channel:** Fahd Mirza — https://www.youtube.com/watch?v=Sn03IZZUrbo

A 600-million-parameter decision model spanning audio, vision, and text, installed and tested locally. It fits the week's through-line: small, open models that do real work on your own hardware without an API. While the Haiku-vs-Luna price war rages in the cloud, a model you can run on your laptop is making multimodal decisions for free.
