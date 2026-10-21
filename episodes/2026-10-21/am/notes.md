# The Daily AI Drop — Morning Edition, October 21, 2026

Alex and Jordan cover three overnight drops: NVIDIA's Nemotron 3.5 Super vision model
with native speculative decoding, Siraj Raval giving an AI agent one day to start a
product business, and Microsoft's SQL Modernization Day sessions on AI-ready databases.

## Fahd Mirza — "Nemotron 3.5 Super VL with Native Speculative Decoding"
Watch: https://www.youtube.com/watch?v=ELa0aj9ANOk

Fahd tests NVIDIA-Nemotron-3.5-Super-VL-120B, a 120B-parameter vision-language model
you can run locally. The headline feature is native speculative decoding: the speed
trick is baked into the model itself rather than bolted on as a serving hack, so
generation is faster without a separate draft model. Why it matters: a big open model
that doesn't feel sluggish when self-hosted is exactly what makes heavy local agents
practical — vision plus language on your own hardware with the speed bottleneck
reduced. Fahd runs it through his usual test gauntlet (coding, reasoning, vision)
and gives a verdict. He also flags a 50% discount link for A6000/A5000 GPU rentals
if you want to try it before buying hardware.

## Siraj Raval — "I Gave an AI Agent One Day to Start a Product Business"
Watch: https://www.youtube.com/watch?v=zectfFZJuMg

Siraj gives an AI agent a blank page and 24 hours: find a product people actually
want, find the factory that makes it, and get a real business started. The sourcing
runs through Alibaba (this video includes paid promotion). Why it matters: strip away
the sponsorship and this is the agentic-economy thesis in action — an agent doing
product research, demand validation, supplier discovery, and logistics research that
would take a human founder days of clicking. Watch it to calibrate what agents can
actually do right now as economic actors.

## Microsoft Developer — "SQL Modernization Day"
Watch: https://www.youtube.com/watch?v=MxwXGl-lpe0

Eight sessions from the Microsoft SQL team on moving SQL Server to Azure without a
rewrite, then building AI-ready apps once you land. Covers Azure SQL Database,
Hyperscale, Managed Instance, SQL Server on Azure VMs, SQL Server 2025, and SQL
database in Microsoft Fabric. Two new releases are in public preview: the SQL
modernization agent in GitHub Copilot (which helps with the migration work itself)
and features making the database natively capable of AI workloads — vectors,
embeddings, and RAG. Why it matters: the model is the easy part of AI apps; the hard
part is getting your data into a database that can serve vectors, do retrieval, and
stream changes without a six-month rewrite. For enterprise devs and data engineers,
this is the roadmap.
