# RAG Accuracy Testing with Langsmith and RAGAS

This repository demonstrates the testing of the accuracy of a Retrieval-Augmented Generation (RAG) system using data sourced from Langsmith, and evaluated with RAGAS accuracy metrics.

## Tools Used
- **Langsmith**: A tool for sourcing production data to test the RAG system. It allows fetching and managing large-scale data for accuracy evaluation.
- **RAGAS**: A metric for evaluating the accuracy and performance of Retrieval-Augmented Generation systems. It provides precise evaluation of the response relevance and accuracy of RAG-based models.
- **Langchain**: A framework to build and manage RAG systems. Langchain allows integration with various data sources and simplifies the process of building pipelines for RAG systems.

## Workflow
1. **Data Retrieval**:
   - Production data is fetched using Langsmith.
   - This data is used as a test dataset for evaluating the RAG system's response accuracy.

2. **RAG System Setup**:
   - A RAG system is built using **Langchain**, which integrates the retrieval and generation processes.
   - The system retrieves relevant documents from a vector database and generates responses based on the retrieved information.

3. **Accuracy Testing**:
   - The system’s performance is evaluated using **RAGAS** accuracy metrics.
   - The metrics provide a comprehensive understanding of how well the RAG system performs on the test data, evaluating the relevance and precision of the responses.
