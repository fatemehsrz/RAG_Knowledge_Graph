# Enhancing RAG Accuracy with Knowledge Graphs

![plot](./Graph_RAG.png)

Graph retrieval augmented generation (Graph RAG) presents a powerful addition to traditional vector search retrieval methods. The idea is to leverage the structured nature of graph databases, which organize data as nodes and relationships, to enhance the depth and contextuality of retrieved information.

Constructing a knowledge graph is typically the most challenging step in leveraging the power of graph-based data representation. However, LLMs, with their profound understanding of language and context, can automate significant parts of the knowledge graph creation process. By analyzing text data, these models can identify entities, understand the relationships between them, and suggest how they might be best represented in a graph structure. This tutorial describes the process of knowledge graph construction and query answering module in two different ways: <br>
 1) [LangChain with Neo4j](https://github.com/fatemehsrz/RAG_Knowledge_Graph/blob/main/LlamaIndex_KG_Nebula.ipynb) <br>
 2) [Llama-Index with Nebula Graph](https://github.com/fatemehsrz/RAG_Knowledge_Graph/blob/main/Langchian_KG_Neo4j.ipynb)
 
# Query example With Llama-Index and Neubula Graph:
 

Necessary library importing
```python
from tensorflow.keras.applications.densenet import VGG16
import tensorflow.keras as keras
from tensorflow.keras import models
from tensorflow.keras import layers
from tensorflow.keras import optimizers
import tensorflow as tf
from keras.models import load_model
import numpy as np
import matplotlib.pyplot as plt
import os


```

# Query example With Langchain and Neoj4 Graph:

Necessary library importing
```python
from tensorflow.keras.applications.densenet import VGG16
import tensorflow.keras as keras
from tensorflow.keras import models
from tensorflow.keras import layers
from tensorflow.keras import optimizers
import tensorflow as tf
from keras.models import load_model
import numpy as np
import matplotlib.pyplot as plt
import os


```
