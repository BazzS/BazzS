## Sergey Bazyliuk

Python engineer working on the backend/AI boundary — I build production APIs and
put LLM systems behind them. Based in Warsaw, Poland (EU work permit). Open to B2B contracts.

**Backend:** Python, Django, FastAPI, PostgreSQL, Celery, Redis, RabbitMQ, Docker, AWS
**AI:** LangChain, LangGraph, RAG pipelines, pgvector, OpenAI API, evaluation (RAGAS)

### What I've shipped

- **RAG document assistant** for a manufacturer — answers pricing questions from internal
  documents. LangGraph state machine with a verification node: the system checks whether the
  generated answer is grounded in retrieved context before returning it, retries if not, and
  refuses when it still fails. In a domain where the answer contains a price, a refusal is
  cheaper than a confident hallucination.
- **LLM support agent** — 500+ conversations/day, ~90% resolved without a human operator,
  with escalation to a live agent as the fallback path.
- **Booking platform** for a 50+ location network — scheduling, concurrent slot handling,
  Celery-based reminders.

### Certifications

AWS Certified Cloud Practitioner (2025) · AWS Certified AI Practitioner (2026)

[LinkedIn](https://linkedin.com/in/siarhei-bazyliuk) · siarheibazyliuk@gmail.com
