# rag-agent-n8n
n8n RAG agent workflow. Ingests Google Drive docs into a Supabase vector store (Postgres + Google Gemini embeddings) and answers chat/webhook queries via an OpenAI-powered agent, with automated cleanup of stale/deleted files
