# pdf-rag-assistant
 Offline, AI-powered Question Answering from CSV &amp; PDF files using fine-tuned retrieval models + RAG pipeline.


CSV-QA-Engine is an AI-powered question-answering system that enables fast and accurate querying of structured CSV datasets and PDF documents. This project combines custom fine-tuned retrieval models with a lightweight RAG (Retrieval-Augmented Generation) pipeline to extract precise answers from uploaded files—fully offline and lightning-fast.

The system automatically converts CSV rows and PDF text into semantically meaningful embeddings, allowing users to ask natural language questions about their data without manual analysis or code.

It is specifically designed for:

✅ Instant, offline data exploration

✅ Enterprise CSV & document Q&A

✅ Fast & accurate responses from local data sources

The pipeline uses:

Custom fine-tuned SentenceTransformer models for semantic retrieval.

PDF & CSV data preprocessing for universal access.

RAG-based architecture for optimized retrieval & answer generation.

Optional integration with Mistral or other GGUF models for advanced reasoning.

⚡ Key Features:

Fast, offline, local Q&A on CSV and PDF files.

No need for external APIs or cloud services.

Handles both numeric & text-based questions from datasets.

Easy to extend to other file formats.

🎯 Example Queries Supported:

“Which department handled transaction T0002?”

“What product was sold on 2024-07-16?”

“Who is the employee responsible for transaction T0003?”

🛠️ Technologies Used:

SentenceTransformers (fine-tuned MiniLM)

Pandas & PDF parsers

FAISS / ChromaDB for vector retrieval

LlamaCpp or Mistral for optional answer generation

This project is ideal for developers, researchers, and organizations that need high-speed, local document & data querying capabilities without relying on cloud-based solutions.
