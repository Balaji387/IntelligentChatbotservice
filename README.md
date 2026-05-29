Built an ingestion pipeline using LangChain document loaders and text splitters to process the company's underwriting documents
and policy guidelines documents stored in the ImageZone repositories. Implemented document processing workflows include splitting documents into chunks,
calculating embeddings for these chunks, storing the chunks and their embeddings in a vector store. Develops scalable Retrieval-Augmented Generation (RAG) pipeline
using LangChain retrievers and chains, enabling accurate retrieval of insurance policy information for broker queries such as Workers’ Compensation eligibility and compliance rules.
For example, when a broker asks questions, "Do roofing employees qualify for Workers’ Compensation coverage?", "Is Workers’ Compensation mandatory in California?"
the RAG API will be invoked, and it will search the vector store for the relevant information. Engineered RESTful APIs using FastAPI and Uvicorn to expose LangChain-powered ingestion
and retrieval services for enterprise AI consumption. Leveraged LangChain prompt templates, memory modules, and retrieval chains to maintain context-aware,
multi-turn conversational capabilities. Implemented reranking and response optimization using Cohere rerank integrated within LangChain retrieval pipelines to improve answer relevance.
Added Redis-based caching integrated with LangChain memory and retrieval layers to optimize latency and reduce redundant LLM calls.
Developed containerized deployment architecture using Docker and Docker Compose for consistent execution of LangChain-based AI services.
Conducted evaluation of LangChain RAG pipelines using RAGAS metrics including Faithfulness, Answer Relevancy, Context Precision, and Context Recall.
