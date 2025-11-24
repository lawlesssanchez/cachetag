CacheTag™ Framework
A Lightweight, Hashtag-Triggered RAG Cache Using Natural-Language HashPacks™
Primary Author:
Dena Lawless — Zhooshh Venture Studio
Contributing Originator:
Abe Jarrett

Overview
CacheTag™ is a lightweight, hashtag-triggered RAG cache that returns curated Top-5 HashPacks™ instead of regenerating full LLM responses. This system dramatically reduces redundant computation, improves answer stability, and provides fast, predictable responses.
HashPacks automatically refresh every 30 days (TTL) or on user request, creating a sustainable, energy-efficient AI workflow that delivers many benefits of Retrieval-Augmented Generation (RAG) without embeddings or vector databases. This repository introduces CacheTag — a just-in-time memory and retrieval system built to work seamlessly with Model Context Protocol (MCP), enabling AI models to access only the precise, policy-approved information they need in real time.

How CacheTag Works
1. Hashtag Trigger
Typing a hashtag (e.g., #Fintech, #Leadership, #USC) retrieves the associated HashPack instantly.
2. HashPacks™
Each HashPack contains:
A topic name


Top 5 Q&A entries

Timestamp of last refresh

Optional personalization layer

3. 30-Day TTL Refresh
HashPacks refresh automatically every 30 days, or users can request updates with:
refresh #Topic


expand #Topic


narrow #Topic to X



Benefits
Ultra-fast response


Significantly lower compute cost


More consistent answers


Transparent and auditable


Easy for users to understand


Minimal infrastructure required


Ideal for enterprise AI systems



Documentation
Full whitepaper:
./CacheTag-Whitepaper.md

Credits
Primary Author:
Dena Lawless — Architecture, system design, HashPack model, TTL logic, and whitepaper.
Contributing Originator:
Abe Jarrett — Inspired the concept of caching repeated prompts.

License
MIT License
