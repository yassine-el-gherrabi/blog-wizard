# Blog Wizard 🧙‍♂️
Automated blog generation using RAG (Retriever-Augmented Generation). Combines web scraping, LLM-powered content creation, and dynamic image generation with Rust.

## Features
- 🌐 Scraping web data and storing in MongoDB.
- 🧠 Enhancing prompts with embeddings for accurate LLM responses.
- 🖼️ Automatic image generation for blog articles.
- 🚀 Built with Rust for speed and efficiency.

## Tech Stack
- **Language:** Rust
- **Database:** MongoDB + Pinecone for embeddings
- **LLM:** OpenAI API
- **Image Generation:** DALL-E API
- **Orchestration:** API Gateway + Microservices

## Getting Started
1. Clone the repository.
2. Install dependencies: `cargo build`.
3. Run the project: `cargo run`.

## Roadmap
- [ ] Scraping + RAG POC
- [ ] Image generation POC
- [ ] API Gateway and Auth
- [ ] Event triggers with CRON
