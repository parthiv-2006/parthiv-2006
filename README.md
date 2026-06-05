CS @ UofT St. George (Specialist Co-op). I build AI tools, mostly ones I actually wanted to use. 

Check out my portfolio: https://www.parthivpaul.me/

---

Right now I'm building **[Reflecta](https://github.com/parthiv-2006/Reflecta-Ai-Agent)**, an agentic test generation pipeline for Python. Point it at any repo and it maps your coverage gaps via AST analysis, generates targeted pytest files through Gemini 2.5 Flash, and runs a Groq Llama repair loop on any failures. Every kept test clears two hard gates: real AST-verified assertions and a strictly positive coverage delta. No test theater. Multi-model routing across Gemini 2.5 Flash for generation, Groq Llama 8B/70B for repair, and Claude Sonnet for escalated cases.

---

### What I've shipped

**[LeaseGuard](https://github.com/parthiv-2006/lease-guard)** · [leaseguard-sigma.vercel.app](https://leaseguard-sigma.vercel.app)  
AI lease analysis for Ontario renters. Upload your lease and get a full risk report cited to the Residential Tenancies Act in under 90 seconds. Hybrid BM25 + vector retrieval over a 2,372-chunk legal corpus, 161 passing tests, CI on every push.  
`TypeScript` `Next.js 15` `pgvector` `Playwright`

**[Gist](https://github.com/parthiv-2006/Gist)**  
Chrome extension that streams plain-English explanations of any highlighted text, then builds a searchable knowledge base from what you save. 3,072-dimensional embeddings, RAG over your saved concepts, PCA-projected graph of semantic clusters.  
`TypeScript` `FastAPI` `MongoDB Atlas` `Gemini`

**[Palate](https://github.com/parthiv-2006/palate)** · [palate-self.vercel.app](https://palate-self.vercel.app)  
Group restaurant decision app. Shared vibe check, AI-curated restaurant cards, parallel swiping, blind vote to surface a consensus winner. Built at UoftHacks 2026.  
`Next.js` `Node.js` `Gemini 2.5 Flash` `Foursquare`

**[MacroMatch](https://github.com/parthiv-2006/MacroMatch)** · [macro-match-cyan.vercel.app](https://macro-match-cyan.vercel.app)  
Computes exact ingredient quantities through linear programming to hit precise macro targets. Takes a pantry and macro goals, runs a constrained LP model, and returns up to three structurally distinct meal plans within a 5g tolerance band.  
`React` `Node.js` `Linear Programming`

**[Anima](https://github.com/parthiv-2006/Anima)** · [anima-client.vercel.app](https://anima-client.vercel.app)  
Habit tracker where your consistency grows a living creature. Three species, nine evolution paths across two stages, HP decay if you miss a day, and an XP economy with a coin shop and focus timer. Optimistic UI on every quest card, Lottie cinematics on evolution events, and a server-side productivity heatmap aggregated from `completionLog` subdocuments.  
`React 18` `Vite` `Express` `MongoDB` `Framer Motion`

---

**Stack:** TypeScript · Python · Next.js · FastAPI · React · Express · PostgreSQL · MongoDB · RAG / vector search  
**AI tools:** Claude Code · Cursor · Anthropic API · Gemini · Groq · Antigravity  
**Links:** [parthivpaul.me](https://www.parthivpaul.me) · [LinkedIn](https://linkedin.com/in/parthiv-paul)  
**Open to:** Fall 2026 SWE / AI engineering internships, Toronto or remote

Outside of this: basketball, lifting, eating my way through Toronto one neighbourhood at a time.
