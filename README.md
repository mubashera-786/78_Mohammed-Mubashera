Project Title
AI Customer Service Agent using Retrieval-Augmented Generation (RAG)

Project Description:
Built an AI-based customer support assistant for telecom-related queries.
Uses past agent–customer conversations and support tickets as a knowledge base.
Implemented Retrieval-Augmented Generation (RAG) to provide accurate answers.
User queries are sent through an /ask API endpoint.
The system retrieves relevant documents from a vector database before generating responses.
Returns both answer and source document IDs for transparency.
Uses ChromaDB / FAISS for fast similarity search.
Developed using Python and LangChain.
Added simple escalation rules to forward complex or unresolved issues to human agents.
Helps reduce manual workload and improves response time in customer support.

Problem Statement:
Many companies face a high volume of customer queries, causing delays in response.
Slow response times negatively impact customer satisfaction.
Support quality becomes inconsistent due to human limitations and workload.
Human agents cannot efficiently provide 24/7 customer support.
Manual handling of queries leads to higher operational costs.
There is a need for an AI-powered customer service agent.
The system should be able to automatically understand, respond to, and resolve customer queries in real time.

