# DP-800-SQL-AI-Developer-Associate-Preparation-Repository

## SQL AI Developer Associate (DP-800) — Exam Prep Notes

Personal study notes and practice questions for the Microsoft Certified: SQL AI Developer Associate (DP-800) exam — *Developing AI-Enabled Database Solutions*. Organized by exam domain, built while preparing for the exam.

`SQL SERVER` `AZURE SQL` `MICROSOFT FABRIC` `DP-800` `STATUS: CERTIFIED`

---

### About

This repo tracks my preparation for the **Microsoft Certified: SQL AI Developer Associate (DP-800)** exam. It's organized around the exam's official skills-measured domains, with summarized concepts, key distinctions I found easy to mix up, and practice question breakdowns.

> ✅ Passed the Microsoft Certified: SQL AI Developer Associate (DP-800) exam. Notes kept here as a reference and to build on toward deeper T-SQL + AI integration work.

> Note: DP-800 is a newer exam that spans SQL Server, Azure SQL, and SQL databases in Microsoft Fabric — unlike DP-600/DP-700, which are Fabric-only. It centers on bringing AI workloads (embeddings, vector search, RAG) directly into the database engine via T-SQL. If you're studying now, prioritize the official Microsoft Learn study guide, since it's updated more frequently than most third-party material.

---

### Exam Domains Covered

Based on the official Microsoft skills-measured outline for DP-800.

#### 1. Design and Develop Database Solutions (35–40%)
- Designing database schemas and data models for structured and semi-structured data
- Creating and managing database objects: tables, indexes, views, constraints
- Advanced T-SQL: programmability objects, stored procedures, functions, triggers
- Working with JSON and graph queries
- AI-assisted development with GitHub Copilot and MCP servers

#### 2. Secure, Optimize, and Deploy Database Solutions (35–40%)
- Security features: Row-Level Security, Dynamic Data Masking, Always Encrypted
- Query performance tuning and optimization
- CI/CD practices using GitHub workflows and SQL Database Projects
- Deployment across SQL Server, Azure SQL, and Microsoft Fabric

#### 3. Implement AI Capabilities in Database Solutions (25–30%)
- Native vector data types and embeddings generation (e.g. AI_GENERATE_EMBEDDINGS)
- Semantic, hybrid, and intelligent search in SQL databases
- Retrieval-Augmented Generation (RAG) pipelines built in T-SQL
- Integrating Azure OpenAI and outbound REST calls from the database engine

---

### Key Distinctions (things I kept mixing up)

| Concept | Quick distinction |
|---|---|
| DP-800 vs. DP-600/DP-700 | DP-600 and DP-700 are scoped entirely to Microsoft Fabric; DP-800 spans SQL Server, Azure SQL, *and* Fabric SQL databases — it's the only one of the three that isn't Fabric-exclusive |
| DP-800 vs. DP-300 | DP-300 is a traditional database administration exam; DP-800 layers AI capabilities (vectors, embeddings, RAG) on top of database development skills |
| Vector search vs. semantic search vs. hybrid search | Vector search matches embeddings directly; semantic search ranks by meaning using a reranker; hybrid search combines vector + keyword for better recall |
| Embeddings vs. fine-tuning | Embeddings represent data as vectors for retrieval/search; fine-tuning changes a model's weights — DP-800 focuses on embeddings + RAG, not model training |
| RLS vs. Dynamic Data Masking vs. Always Encrypted | RLS restricts *which rows* a user can see; Dynamic Data Masking obscures column values in query results; Always Encrypted protects data at rest and in transit from even the DB engine |

---

### Practice Question Log

Tracking topics I drilled, to identify weak spots before exam day.

- [ ] Database schema design and data modeling
- [ ] Advanced T-SQL and programmability objects
- [ ] JSON and graph queries
- [ ] Security: RLS, Dynamic Data Masking, Always Encrypted
- [ ] Query performance tuning
- [ ] CI/CD with GitHub and SQL Database Projects
- [ ] Vector embeddings and native vector types
- [ ] Semantic and hybrid search
- [ ] RAG pipeline design in T-SQL
- [ ] Full-length practice exam

---

### Resources Used

- Microsoft Learn: [DP-800 study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/dp-800)
- Microsoft Learn: [SQL AI Developer Associate certification page](https://learn.microsoft.com/en-us/credentials/certifications/developing-ai-enabled-database-solutions/)
- Microsoft Learn: Azure SQL and SQL Server documentation
- Microsoft Reactor: Get Certified — SQL AI Developer (DP-800) series

### Recommended YouTube Channels

DP-800 is a newer exam, so dedicated prep playlists are still growing. These channels cover the underlying T-SQL, Azure SQL, and AI integration concepts the exam draws from.

1. **John Savill** — Excellent for concise Azure and SQL explanations. Great for final review once you already understand the fundamentals.
2. **The AI Show** — Microsoft's official show; useful for how Azure OpenAI and AI capabilities plug into data platforms.
3. **Adam Marczak – Azure for Everyone** — Clear explanations with diagrams and practical, hands-on examples.
4. **Microsoft Reactor** — Official Microsoft sessions and exam prep livestreams, including the DP-800 kickoff series.

---

### Status

✅ Certified — passed the Microsoft Certified: SQL AI Developer Associate (DP-800) exam.
