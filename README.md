# Enhancing RAG Accuracy with Knowledge Graphs

![plot](./Graph_RAG.png)

Graph retrieval augmented generation (Graph RAG) presents a powerful addition to traditional vector search retrieval methods. The idea is to leverage the structured nature of graph databases, which organize data as nodes and relationships, to enhance the depth and contextuality of retrieved information.

Constructing a knowledge graph is typically the most challenging step in leveraging the power of graph-based data representation. However, LLMs, with their profound understanding of language and context, can automate significant parts of the knowledge graph creation process. By analyzing text data, these models can identify entities, understand the relationships between them, and suggest how they might be best represented in a graph structure. This tutorial describes the process of knowledge graph construction and query answering module in two different ways: <br>
 1) [LangChain with Neo4j](https://github.com/fatemehsrz/RAG_Knowledge_Graph/blob/main/LlamaIndex_KG_Nebula.ipynb) <br>
 2) [Llama-Index with Nebula Graph](https://github.com/fatemehsrz/RAG_Knowledge_Graph/blob/main/Langchian_KG_Neo4j.ipynb)
 
**Query example With Llama-Index and Neubula Graph:**
 
```"What is Cybertruck?"
Cybertruck is a vehicle developed by Tesla that uses a platform approach to powertrain components, including a single permanent magnet motor rotor/stator design, a single induction motor rotor/stator design, a single motor inverter design, and a single gear set design. It comes in three configurations: tri-motor AWD, dual-motor AWD, and single-motor RWD, with power ranging from 845 hp (630 kW) on the tri-motor down to 315 hp (235 kW) in the single-motor version. The windows use borosilicate glass, and the vehicle has raised safety concerns due to its angular design and stiff stainless-steel exterior. Cybertruck production began in Gigafactory Texas in Austin, Texas, with pre-production models in July 2023, and serial production had begun by November 2023. As of December 2023, Tesla confirmed that the Cybertruck will be available exclusively in the United States, Canada, and Mexico, with no plans for release in other global markets, including Europe and Australia.
```

**Query example With Langchain and Neoj4 Graph:**

```"What is Cybertruck?"
Cybertruck is a concept car manufactured by Tesla, Inc. It was introduced in November 2019 and is part of the Tesla Master Plan. It is an alternative to fossil-fuel-powered trucks and competes with the Ford F-150. The Cybertruck is equipped with armor glass and can carry the Tesla Cyberquad. It has been exhibited at the Petersen Automotive Museum and was awarded Concept Car Of The Year by Automobile Magazine.
```
