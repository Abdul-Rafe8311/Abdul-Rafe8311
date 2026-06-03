# Abdul Rafe Khalid

### Full-Stack & AI Engineer · CS @ NUST (SEECS)

---

## 🎯 Current Focus

- Building **production RAG systems** and chasing down the parts that quietly break — retrieval relevancy, chunking, hallucination
- Full-stack work in **Next.js + TypeScript**
- Learning AI/ML by shipping real, **deployed** projects — not just tutorials

---

## 🛠️ Some things I've actually dealt with building real software

- Built a full-stack **[RAG assistant over the Quran (all 6,236 ayahs) and hadith](https://quran-hadith-assistant.vercel.app)**. The hard part wasn't generating fluent answers — it was making retrieval pull the *right* verse. Off-the-shelf embeddings kept matching what was semantically close, not what the user meant. I fixed it with natural-boundary chunking (one verse / one narration per chunk), query expansion for transliterated terms (a user types "tawakkul", I expand it to "trust and complete reliance upon Allah" before embedding), and exact pgvector search. Then I measured it with **RAGAS** instead of trusting vibes: **0.922 average answer relevancy** across 10 golden Q&A pairs.

- Designed an **[18-table relational schema for BuildLink](https://buildlink-1.onrender.com/#builder-dashboard)**, a construction marketplace, and wired it end-to-end with Prisma, MySQL, NextAuth, and Cloudinary. Spent real time debugging seed scripts and connection pooling — the unglamorous database plumbing that decides whether an app actually works in production.

- Parsed hadith out of **messy OCR'd PDFs** — inconsistent numbering, garbage characters, broken line breaks. Wrote cleanup logic to detect numbered narration boundaries and strip junk before chunking, with a recursive-splitter fallback when no structure was found.

- Built **[NUST Cafe Rater](https://rate-nust-cafes.vercel.app)**, a campus web app for rating on-campus cafes, with NUST email auth, one-review-per-user-per-cafe logic, and toast notifications.

- Shipped a **Java OOP trading-simulation engine** (38 source files, 8 packages) demonstrating all four OOP pillars, generics, design patterns, and custom exceptions.

---

## 💻 Stack

`TypeScript` · `JavaScript` · `Next.js` · `React` · `Node.js` · `Express` · `Python` · `Java`
`PostgreSQL` · `MySQL` · `Prisma` · `Supabase (pgvector)` · `Anthropic Claude API` · `Tailwind CSS`

---

## 🚀 Selected Projects

| Project | What it is | Stack |
|---|---|---|
| **[Quran & Hadith Assistant](https://quran-hadith-assistant.vercel.app)** | Full-stack RAG over Quran + hadith | Next.js · pgvector · Claude API |
| **[BuildLink](https://buildlink-1.onrender.com/#builder-dashboard)** | Construction marketplace | Next.js 14 · Prisma · MySQL |
| **[NUST Cafe Rater](https://rate-nust-cafes.vercel.app)** | Campus review app | Supabase · NUST email auth |
| **[CipherStack](https://cipher-stack-amber.vercel.app)** | Visual encryption builder (hackathon) | React |
| **AI News Summariser** | News summariser | JavaFX · Gemini API |

---

## 🤝 Connect with me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdul-rafe-khalid-a5275a379)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Abdul-Rafe8311)


