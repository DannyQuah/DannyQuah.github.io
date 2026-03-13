---
fileName: 2026-02-27-AI-inversion-LLM-introspect.md
Last-edited: 2026.03.13.1220.Fri -- Danny Quah ( dq @ mbam2-2023-04.local )
Type: Publication
Tags:
  - Obsidian
  - LLM
Created: 2026.02.27.1751.Fri -- Danny Quah (me @ DannyQuah.com)
title: "AI inversion.  I asked my local LLM to introspect and join up what I'd been thinking the last four years"
---
### "AI inversion.  I asked my local LLM to introspect and join up what I'd been thinking the last four years"  

by  
[Danny Quah](https://lkyspp.nus.edu.sg/our-people/faculty/danny-quah)  
Feb 2026  

This past weekend I looked at my LLMs and decided that for a while I wasn't going to be asking what the world says or knows.  Instead, I wanted to see the connections in and clusters of ideas, common turns of phrase, and formal parallels in statistical models and mathematical structures in and across the models of social mobility and of world order that I have been developing.  The source material had to be clearly circumscribed and controlled:  notes I keep of half-finished conjectures and ideas from what I've read; YouTube and podcast recordings of panels, roundtables, and fireside chats I've done; markdown and latex source of papers, blogs, and commentaries I've written.

<video width="480" controls>
  <source src="https://DannyQuah.github.io/Storage/2026.02.26.1120.Thu-original-DQ-second-brain-compressed.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

I wanted the ideational connections across these mathematical and conceptual models updated in real time, and I didn't want this source material uploaded to the cloud.  I wanted to query locally and dynamically my second brain, not just look at its connections graphically, which Obsidian had already long allowed me to do.  

So I rigged up on my MacBook Air an ollama runner, and downloaded onto it a Chat Model and a RAG Embedding Model, compact enough to run in 16Gb RAM. Then, because everything happens locally, there are no API or subscription charges, and I know any conclusion I draw comes only from thoughts I had myself.

It works.  I got connections, gaps, blindspots, suggestions.  

In the 1m02s animation, each of the nearly 6,000 nodes is a document, URL, or other link; and the size and links represent ideational footprint and connection strength.  

(If I'd known ahead of time the below was all I had to do, it would have taken only 5mins to get up and running:

```
curl -fsSL https://ollama.com/install.sh | sh  
ollama pull llama3:8b-insgtruct-q4_K_M  
ollama pull nomic-embed-text  
```
Obsidian Copilot plugin:
-  Self-hosted ollama API `http://localhost:11424`; ignore all other API key requests  
-  Chat model `llama3:8b-insgtruct-q4_K_M`; embedding model `nomic-embed-text`
-  For API key of both chat and embedding models, don't leave blank but put in any string  (like `x` or `ollama`).  
-  In tab QA, set embedding model to `nomic-embed-text (Ollama)`
-  Use `vault QA (free)`   



<!---
   Invisible section // 2026-02-27-AI-inversion-LLM-introspect.md
-->
