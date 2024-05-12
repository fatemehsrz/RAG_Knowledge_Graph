#Enhancing RAG with Knowledge Graphs
![plot](./Graph_RAG.png)

Graph retrieval augmented generation (Graph RAG) presents a powerful addition to traditional vector search retrieval methods. The idea is to leverage the structured nature of graph databases, which organize data as nodes and relationships, to enhance the depth and contextuality of retrieved information.

Constructing a knowledge graph is typically the most challenging step in leveraging the power of graph-based data representation. However, LLMs, with their profound understanding of language and context, can automate significant parts of the knowledge graph creation process. By analyzing text data, these models can identify entities, understand the relationships between them, and suggest how they might be best represented in a graph structure. This tutorial describes the process of knowledge graph construction module in two diffrent ways 1) LangChain and Neo4j, 2) Llama-Index and Nebula Graph
