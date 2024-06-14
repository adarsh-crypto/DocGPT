# DocGPT


Welcome to DocGPT, the cutting-edge AI project designed to revolutionize how you interact with your documents. By leveraging the power of Large Language Models (LLMs), DocGPT allows you to ask questions about your documents and receive accurate, context-aware answers—all while ensuring complete data privacy. 

## 🌟 Key Features

### High-level API
- **Document Ingestion**: Effortlessly parse, split, extract metadata, generate embeddings, and store your documents.
- **Chat & Completions**: Seamlessly retrieve context, engineer prompts, and generate responses based on your documents.

### Low-level API
- **Embeddings Generation**: Create embeddings from any text with ease.
- **Contextual Chunks Retrieval**: Fetch the most relevant text chunks based on your queries.

### User-Friendly Interface
Experience our intuitive [Gradio UI](https://www.gradio.app/) client, which simplifies testing and interaction with the API. It includes useful tools like bulk model download scripts, ingestion scripts, and document folder watchers.

## 🚀 Motivation

DocGPT is built with the belief that generative AI can transform industries but must prioritize privacy, especially in sensitive fields like healthcare, legal, and finance. With DocGPT, all data processing is done locally, ensuring that your data remains secure and private.

## 🛠️ Vision

Our vision for DocGPT is to be your go-to gateway for generative AI models and primitives, including document ingestion, RAG pipelines, and more. We aim to simplify AI application development and encourage community contributions to foster a collaborative and innovative environment.

## 📚 Comprehensive Documentation

For detailed information on installation, dependencies, configuration, server running, deployment options, local document ingestion, API details, and UI features, please visit our [documentation](https://docs.DocGPT.dev/).

## 🧩 Architecture

DocGPT is built using FastAPI and LlamaIndex, ensuring a robust and scalable framework. Key architectural features include:

- **Dependency Injection**: Decouples components and layers for easy customization.
- **LlamaIndex Abstractions**: Utilizes abstractions like `LLM`, `BaseEmbedding`, and `VectorStore` for flexible implementation.
- **Simplicity and Readiness**: Minimal additional layers and a fully implemented API and RAG pipeline for immediate use.

### Main Components
- **APIs**: Defined in `private_gpt:server:<api>`. Each package includes an API router and service implementation.
- **Components**: Located in `private_gpt:components:<component>`, providing implementations for the abstractions used in services.

## 💻 Software Used

DocGPT leverages several powerful software tools and frameworks to deliver its capabilities:
- **FastAPI**: For building the scalable and efficient API.
- **LlamaIndex**: Provides the base RAG framework and abstractions.
- **Gradio**: For the user-friendly UI client.
- **Qdrant**: For the default vector database.
- **Fern**: For documentation and SDKs.

