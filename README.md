# Hi, I'm Chirag Goyal

Computer Science student at Mahindra University (B.Tech, 2023–2027). I build AI products end to end, including LLM agents, retrieval-augmented (RAG) systems and ML anomaly detection, and I measure them honestly: held-out tests, stated limits, no inflated numbers.

[LinkedIn](https://linkedin.com/in/chirag-goyal-b59b32257) · se23ucse050@mahindrauniversity.edu.in

## Experience

**AI Intern, Cybersecurity IRM · Jio Platforms** (Jun–Jul 2026)
Built a prototype AI-powered insider-risk platform. It scores 400 synthetic employees on 7 weighted risk indicators to flag higher-risk profiles. Working with the IRM team, I finalized 9 business units and their question set, then used an LLM (Groq Llama 3.1) to generate 5,970 awareness questions targeted at each employee's risk indicators. Admin and employee dashboards show risk and training coverage. *(Internship code is not public.)*

## Featured projects

### [CartGenii: AI Procurement Agent](https://github.com/tanishkasirohi/PayPal-Hackthon-Project) · [Live demo](https://cartgenii.onrender.com)
PayPal "Build What's Next with PayPal and AI" Hackathon (Devpost), Nov 2026. Team of 3; I was the lead architect.
- AI shopping agent built and deployed in under 8 hours: plain-English requests become ranked, explained picks from 27 products across 8 suppliers.
- Hallucination guardrails: the AI never sets prices or stock, every product it suggests is checked against real data, and checkout needs buyer approval.
- PayPal checkout with server-verified payments; deployed on Render.

`Python` `FastAPI` `Gemini API` `PayPal Orders v2` `Render`

### [IncidentLens](https://github.com/ChiRaG18042004/incidentlens)
Evidence-first assistant that investigates software outages from logs, metrics, traces and change records, and cites its evidence.
- Raised held-out root-cause accuracy from 45% to 76% on simulated incidents (52% under a stricter vocabulary-overlap control).
- A learned gate declines 83% of unanswerable questions; a citation verifier catches 83% of unsupported claims.
- 161 automated tests. All data is simulated; results on real outages are untested.

`Python` `FastAPI` `RAG` `Gemini API` `pytest`

### [Mystery Case Room](https://github.com/ChiRaG18042004/mystery-case-room)
Detective game built on the Model Context Protocol (MCP).
- MCP server with 9 tools, 3 resources and 2 prompts that holds the game state and reveals clues only once found.
- AI narrator with an allow-list: it can investigate but cannot make the final accusation. 14 tests (AI calls mocked).

`Python` `MCP` `Gemini API` `pytest`

### [Behavior Anomaly Detection (UEBA)](https://github.com/ChiRaG18042004/behavior-anomaly-ml)
ML for spotting unusual user behavior.
- Real-time dashboard over a simulated stream of 8,640 events; combining Isolation Forest and LOF raised precision to 80%.
- On the CERT r4.2 insider-threat benchmark, Random Forest beat Isolation Forest (48% vs 14% recall on the same test set).

`Python` `scikit-learn` `Pandas` `SQLite`

<details>
<summary>Earlier projects</summary>

- **[Resume Fit Ranker](https://github.com/ChiRaG18042004/resume-fit-ranker):** ranks resumes against job descriptions using TF-IDF similarity and skill-gap extraction.
</details>

## Skills

**Languages & backend:** Python, SQL, FastAPI, React, REST APIs, SQLite, pytest, Git
**AI & ML:** LLM APIs (Gemini, Groq), prompt engineering, AI agents, RAG, MCP, scikit-learn, Pandas, NumPy

## Beyond code

I co-founded **Prithvi Quest**, a drone-based facade-cleaning startup (Boeing collaboration, DPIIT recognition, signed LOI), and I'm **President of the Entrepreneurship Innovation Cell** at Mahindra University. I like problems where technology, users and messy real-world constraints meet.

## Learning next

- LangChain and LLM fine-tuning
- Fair LLM evaluation (pinned models, blind test sets, judges from a different model family)
- Production-style ML workflows
