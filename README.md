CS @ UofT St. George (Specialist Co-op). I build AI tools, mostly ones I actually wanted to use. 

Check out my portfolio: https://www.parthivpaul.me/

---

Right now I'm building **[Glowi](https://github.com/parthiv-2006/Glowi)**, an AI-powered skincare analysis app for React Native. Photograph a skin concern and a Skia-rendered scanning theater plays while Claude vision structures the result — an overall skin score and ranked concerns with severity, confidence, and affected areas. Each concern opens to three evidence-led tabs: Products (curated, ranked, with retailer links and AI rationale), Nutrition (PubMed-cited foods and nutrients), and Tips. Skin Weather pulls live environmental data (UV, humidity, AQI, pollen) and cross-references your scan history to deliver concrete add/swap/skip adjustments before you touch your face. The Shelf tracks your actual product inventory via AI label reading, routes Skin Weather advice through what you own, and flags expiry and low-stock nudges. An Ingredient Conflict Checker reasons over your whole shelf but only calls Claude when the shelf actually changes — results are cached per user. The Coach remembers you across sessions: skin type, goals, bad reactions, and where you left off, with access to today's forecast and your cabinet. Cross-session memory is written back by an extraction pass after every conversation. Full offline demo mode with a swappable `AIProvider` seam — the entire app runs at zero token cost before you wire up a key.  
`React Native` `Expo SDK 56` `TypeScript` `Supabase` `Anthropic Claude` `Skia` `Reanimated 4`

---

### What I've shipped

**[Reflecta](https://github.com/parthiv-2006/Reflecta-Ai-Agent)**  
Agentic test generation pipeline for Python. Point it at any repo and it maps coverage gaps via AST analysis, generates targeted pytest files through Gemini 2.5 Flash, and runs a Groq Llama repair loop on failures. Every kept test clears two hard gates: real AST-verified assertions and a strictly positive coverage delta. Multi-model routing across Gemini 2.5 Flash for generation, Groq Llama 8B/70B for repair, and Claude Sonnet for escalated cases.  
`Python` `Gemini 2.5 Flash` `Groq` `AST`

**[LeaseGuard](https://github.com/parthiv-2006/lease-guard)** · [leaseguard-sigma.vercel.app](https://leaseguard-sigma.vercel.app)  
AI lease analysis for Ontario renters. Upload your lease and get a full risk report cited to the Residential Tenancies Act in under 90 seconds. Hybrid BM25 + vector retrieval over a 2,372-chunk legal corpus, 161 passing tests, CI on every push.  
`TypeScript` `Next.js 15` `pgvector` `Playwright`

**[Gist](https://github.com/parthiv-2006/Gist) - Checkout my portfolio site for a Live Demo**  
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
**Open to:** Fall 2026 SWE / AI engineering internships, Toronto/GTA/Remote

Outside of this: basketball, lifting, eating my way through Toronto one neighbourhood at a time.
