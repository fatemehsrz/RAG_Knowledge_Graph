# Enhancing RAG Accuracy with Knowledge Graphs

![plot](./Graph_RAG.png)

Graph retrieval augmented generation (Graph RAG) presents a powerful addition to traditional vector search retrieval methods. The idea is to leverage the structured nature of graph databases, which organize data as nodes and relationships, to enhance the depth and contextuality of retrieved information.

Constructing a knowledge graph is typically the most challenging step in leveraging the power of graph-based data representation. However, LLMs, with their profound understanding of language and context, can automate significant parts of the knowledge graph creation process. By analyzing text data, these models can identify entities, understand the relationships between them, and suggest how they might be best represented in a graph structure. This tutorial describes the process of knowledge graph construction and query answering module in two different ways: <br>
 1) [Llama-Index with Nebula Graph](https://github.com/fatemehsrz/RAG_Knowledge_Graph/blob/main/LlamaIndex_KG_Nebula.ipynb) <br>
 2) [LangChain with Neo4j](https://github.com/fatemehsrz/RAG_Knowledge_Graph/blob/main/Langchian_KG_Neo4j.ipynb)
 
**Llama-Index and LangChain Comparison:**

| Model | Query | Answer!
| LlamaIndex | `What is Cybertruck?`| |
| Langchain | `What is Cybertruck?`| `Cybertruck is a concept car manufactured by Tesla, Inc. It was introduced in November 2019 and is part of the Tesla Master Plan. It is an alternative to fossil-fuel-powered trucks and competes with the Ford F-150. The Cybertruck is equipped with armor glass and can carry the Tesla Cyberquad. It has been exhibited at the Petersen Automotive Museum and was awarded Concept Car Of The Year by Automobile Magazine.
` |
| LlamaIndex | `Who is Elon Musk?`| |
| Langchain | `Who is Elon Musk?`|  |
| LlamaIndex | `How powerful is the CyberTruck?`| |
| Langchain |`How powerful is the CyberTruck?` |  |
 


