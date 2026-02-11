# Clinisight AI

Clinisight AI is a medical intelligence assistant that combines large language models (LLMs) with verified biomedical literature to generate reliable, research-grounded diagnostic insights from free-text symptom descriptions.

The system extracts symptoms from user queries, generates preliminary diagnostic suggestions using an LLM, retrieves relevant research articles from PubMed (NCBI), and summarizes scientific abstracts into concise, human-readable insights. To minimize misinformation, LLM outputs are augmented and cross-validated using trusted medical sources rather than relying solely on generative responses.

The project is implemented as:

-> A FastAPI service for programmatic access

-> An MCP tool for seamless integration with AI clients (e.g., Cursor, Claude Desktop, custom MCP clients)

The architecture is modular and model-agnostic, enabling easy replacement of LLM providers and extension to additional medical data sources.
