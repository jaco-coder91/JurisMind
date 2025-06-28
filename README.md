# 📄 JurisMind – Legal AI Assistant for South African Lawyers

## 🔍 Project Summary

JurisMind is an AI-native legal assistant purpose-built for the South African legal context. It empowers legal professionals to research, draft, and strategize more efficiently. Unlike generic AI tools, JurisMind understands South African case law, statutory nuances, and multilingual considerations, delivering specialized legal insights with speed and precision.

**Key goals:**
- Streamline legal research through RAG-powered queries and summarization.
- Enable smart contract review with risk analysis and redlining.
- Support multilingual legal environments (English, isiZulu, Afrikaans, Sesotho).
- Provide strategy insights, case knowledge mapping, and POPIA/B-BBEE compliance advice.

## 🛠 Tech Stack Overview (Draft)

| Layer             | Technologies                                            |
|------------------|---------------------------------------------------------|
| **Frontend**     | React / Next.js                                         |
| **Backend**      | FastAPI (Python) or Node.js (Express)                  |
| **Auth**         | JWT, bcrypt, OAuth scaffold                             |
| **AI Layer**     | GPT-4 API + LangChain / LlamaIndex (for RAG)            |
| **Vector DB**    | Pinecone / Weaviate / FAISS                             |
| **Legal DB**     | PostgreSQL / MongoDB                                    |
| **Knowledge Graph** | Neo4j (optional), D3.js (frontend)                   |
| **File Parsing** | pdfplumber, docx, textract, tika                        |
| **Hosting**      | Vercel (frontend), DigitalOcean / AWS (backend)         |
| **DevOps**       | Docker, GitHub Actions, CI/CD pipeline                  |
| **Security**     | AES-256 encryption, POPIA-aware handling, audit logs    |

## 📆 Weekly Roadmap (Phase 1 – MVP Buildout)

| Week | Focus Area                      | Goals                                                          |
|------|----------------------------------|----------------------------------------------------------------|
| 1    | Project Kickoff & Setup          | Define scope, set up repo, CI/CD, and README                   |
| 2    | Core Web App Framework           | Bootstrap Next.js frontend & FastAPI backend                   |
| 3    | Auth & User Management           | Implement JWT auth, user roles, login/signup                   |
| 4    | Document Upload & Storage        | Secure file upload, tagging, and encrypted storage             |
| 5    | Legal Research Assistant         | RAG setup with SAFLII data, GPT-based Q&A module               |
| 6    | Case Summary Generator           | PDF parser and summary output                                  |
| 7    | Contract Review Assistant        | Clause analysis and GPT-powered redlining                      |
| 8    | Drafting Assistant & Export      | Document generation and export (Word/PDF)                      |
| 9    | Legal Strategy & Compliance Tool | Add strategy generator and POPIA/B-BBEE compliance scan        |
| 10   | Admin Dashboard & Audit Logging  | Usage stats, audit trails, incognito mode                      |
| 11   | QA & Testing                     | Unit tests, integration tests, CI pipeline optimization        |
| 12   | MVP Finalization & Feedback      | Deploy MVP, collect feedback from target users                 |
