Abdul Rafe Khalid
Full Stack AI Engineer · CS @ NUST (SEECS)
Current Focus

Building production RAG systems and chasing down the parts that quietly break — retrieval relevancy, chunking, hallucination
Full-stack work in Next.js + TypeScript
Learning AI/ML by shipping real, deployed projects — not just tutorials

Some things I've actually dealt with building real software:

Built a full-stack RAG assistant over the Quran (all 6,236 ayahs) and hadith. The hard part wasn't generating fluent answers — it was making retrieval pull the right verse. Off-the-shelf embeddings kept matching what was semantically close, not what the user meant. I fixed it with natural-boundary chunking (one verse / one narration per chunk), query expansion for transliterated terms (a user types "tawakkul", I expand it to "trust and complete reliance upon Allah" before embedding), and exact pgvector search. Then I measured it with RAGAS instead of trusting vibes: 0.922 average answer relevancy across 10 golden Q&A pairs.

Designed an 18-table relational schema for BuildLink, a construction marketplace, and wired it up end-to-end with Prisma, MySQL, NextAuth, and Cloudinary. Spent real time debugging seed scripts and connection pooling — the unglamorous database plumbing that decides whether an app actually works in production.

Built NUST Cafe Rater, a campus web app for rating on-campus cafes, with NUST email-based auth, one-review-per-user-per-cafe logic, and toast notifications — then went through the process of getting faculty permission to share it across the SEECS community.

Shipped a Java OOP trading-simulation engine (38 source files, 8 packages) demonstrating all four OOP pillars, generics, design patterns, and custom exceptions — a lesson in keeping a large codebase organized, not just working.


Stack: TypeScript · JavaScript · Next.js · React · Node.js · Express · Python · Java · PostgreSQL · MySQL · Prisma · Supabase (pgvector) · Anthropic Claude API · Tailwind CSS
Selected Projects

Quran & Hadith Assistant — full-stack RAG · Next.js · pgvector on Supabase · Claude API · live demo
BuildLink — construction marketplace · Next.js 14 · Prisma · MySQL · 18-table schema
NUST Cafe Rater — campus review app · Supabase · NUST email auth
AI News Summariser — JavaFX + Gemini API
CipherStack — visual encryption builder (hackathon project)

Connect with me
LinkedIn · GitHub
