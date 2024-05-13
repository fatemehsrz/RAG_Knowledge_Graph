# Enhancing RAG Accuracy with Knowledge Graphs

![plot](./Graph_RAG.png)

Graph retrieval augmented generation (Graph RAG) presents a powerful addition to traditional vector search retrieval methods. The idea is to leverage the structured nature of graph databases, which organize data as nodes and relationships, to enhance the depth and contextuality of retrieved information.

Constructing a knowledge graph is typically the most challenging step in leveraging the power of graph-based data representation. However, LLMs, with their profound understanding of language and context, can automate significant parts of the knowledge graph creation process. By analyzing text data, these models can identify entities, understand the relationships between them, and suggest how they might be best represented in a graph structure. This tutorial describes the process of knowledge graph construction and query answering module in two different ways: <br>
 1) [Llama-Index with Nebula Graph](https://github.com/fatemehsrz/RAG_Knowledge_Graph/blob/main/LlamaIndex_KG_Nebula.ipynb) <br>
 2) [LangChain with Neo4j Graph](https://github.com/fatemehsrz/RAG_Knowledge_Graph/blob/main/Langchian_KG_Neo4j.ipynb)
 
## Llama-Index and LangChain Comparison:

- [x] Context from Wikipedia on [Cybertruck](https://en.wikipedia.org/wiki/Tesla_Cybertruck)

<br />



|Model|Query| Answer|
|---|---|---|
|LlamaIndex| `What is Cybertruck?` | `Cybertruck is a vehicle developed by Tesla that uses a platform approach to powertrain components, including a single permanent magnet motor rotor/stator design, a single induction motor rotor/stator design, a single motor inverter design, and a single gear set design. It comes in three configurations: tri-motor AWD, dual-motor AWD, and single-motor RWD, with power ranging from 845 hp (630 kW) on the tri-motor down to 315 hp (235 kW) in the single-motor version. The windows use borosilicate glass, and the vehicle has raised safety concerns due to its angular design and stiff stainless-steel exterior. Cybertruck production began in Gigafactory Texas in Austin, Texas, with pre-production models in July 2023, and serial production had begun by November 2023. As of December 2023, Tesla confirmed that the Cybertruck will be available exclusively in the United States, Canada, and Mexico, with no plans for release in other global markets, including Europe and Australia.`|
|LangChain | `What is Cybertruck?` | `Cybertruck is a concept car manufactured by Tesla, Inc. It was introduced in November 2019 and is part of the Tesla Master Plan. It is an alternative to fossil-fuel-powered trucks and competes with the Ford F-150. The Cybertruck is equipped with armor glass and can carry the Tesla Cyberquad. It has been exhibited at the Petersen Automotive Museum and was awarded Concept Car Of The Year by Automobile Magazine.` |
|LlamaIndex| `Who is Elon Musk?`|`Elon Musk is mentioned multiple times in the provided context information as the CEO of Tesla and the person involved in the design process of the Cybertruck. He was inspired by Blade Runner and the Lotus Esprit driven by James Bond in The Spy Who Loved Me, which doubled as a submarine, for the design of the Cybertruck. Musk's son's quote "Why doesn't the future look like the future?" was used as an inspiration for the design as well. Musk wanted the Cybertruck to have all the utility of a pick-up truck but drive like a sports car. He also claimed that final specifications and pricing for the Cybertruck would be materially different from those unveiled on the concept vehicle in 2019.` |
|LangChain |`Who is Elon Musk?` | `Elon Musk is the CEO of Tesla, Inc. He is also a co-founder and shareholder of the company. He has been involved in envisioning products like the Tesla Cybertruck and Tesla Cyberquad. He has also invested in Tesla and was previously a shareholder in Paypal.`|
|LlamaIndex| `How powerful is the Cybertruck?`| `The Cybertruck comes in three configurations: tri-motor AWD, dual-motor AWD, and single-motor RWD. The tri-motor AWD version offers a maximum combined output of 845 hp (630 kW) in Beast Mode, split as 276 hp (206 kW) for the front motor and 284 hp (212 kW) for each rear motor. The dual-motor AWD version has a total power output of 600 hp (450 kW), with an induction motor on the front axle with a maximum output of 303 hp (226 kW) and a permanent magnet motor on the rear axle with a maximum output of 297 hp (221 kW). The single-motor RWD version has a power output of 315 hp (235 kW).` |
|LangChain | `How powerful is the Cybertruck?`| `The text does not provide information on how powerful the Cybertruck is.` |

 


