# Graphs and Networks

Here's some links/material to theory and projects about Graphs and Networks

---
### Theory
- [ ] :thumbsup: [Introduction to Network science with NetworkX](https://medium.com/python-in-plain-english/introduction-to-network-science-with-networkx-part-1-c306fc3860e0)  
- [ ] [Top Trends of Graph Machine Learning in 2020](https://towardsdatascience.com/top-trends-of-graph-machine-learning-in-2020-1194175351a3)
- [ ] [node2vec: Embeddings for Graph Data](https://towardsdatascience.com/node2vec-embeddings-for-graph-data-32a866340fef)  
- [ ] [Random Walk in Node Embeddings (DeepWalk, node2vec, LINE, and GraphSAGE)](https://medium.com/towards-artificial-intelligence/random-walk-in-node-embeddings-deepwalk-node2vec-line-and-graphsage-ca23df60e493) - Graph Embeddings

---
### Notable Projects and Snippets
- [ ] [Analyzing Disease Co-occurrence Using NetworkX, Gephi, and Node2Vec](https://medium.com/analytics-vidhya/analyzing-disease-co-occurrence-using-networkx-gephi-and-node2vec-53941da35a0f)  
  - Explains how to run 100 points Node2Vec from adjacency matrix
- [ ] [Link Prediction with Neo4j Part 1: An Introduction](https://medium.com/neo4j/link-prediction-with-neo4j-part-1-an-introduction-713aa779fd9)
- [ ] [Python Interactive Network Visualization Using NetworkX, Plotly, and Dash](https://towardsdatascience.com/python-interactive-network-visualization-using-networkx-plotly-and-dash-e44749161ed7)
- [ ] [Graph Convolutional Networks (GCN)](https://medium.com/ai-in-plain-english/graph-convolutional-networks-gcn-baf337d5cb6b) - explains GCN
- [ ] :thumbsup: [Git to build Family Tree](https://github.com/sylhare/family-tree)
  - Includes refs to many other good projects and tools
- [Family Trees Projects](https://www.wired.com/story/researchers-used-this-genealogy-site-to-build-a-13-million-person-family-tree/) - Wired.com
  - [Quantitative analysis of population-scale family trees with millions of relatives](https://science.sciencemag.org/content/360/6385/171) - paper
  - [ ] :thumbsup: [FamiLinx](http://www.familinx.org/data.html) - **HOW TO DOWNLOAD GENI DATASET!**
    - [Downloads page **with Script**](http://www.familinx.org/download.html)  
  - [Geni Project](https://www.geni.com/platform/developer/help) - Origins of Geni
  - [pyGenealogicalTools](https://pypi.org/project/pyGenealogicalTools/) **TO CALL GENI API!**
    - <details>  
        From [this site](https://github.com/geni/geni-gedcom):
        Step 2 - Get an API key from Geni
        If you want to import gedcoms, chances are you have a Geni account. If not, you'll need one. Go get one.

        Now you need to register an application for the Geni API. This is a necessary step for getting an API key. Go to the platform apps page and click '+ Register New Application'. Now fill in the information. You must fill in at least 'Name', 'Site URL', and 'Site Domain', but the values of these are not really important.

        Next, go to the Geni API explorer. You can get a magic API key here. Just click "Get Access Token" and it should give you a fancy new key. This API key can be used with your account to upload a gedcom to it.</details>  (Expand for api token details)

  - [ ] [Gramps Project](https://github.com/gramps-project/gramps) - software (also in python) to help build family tree
- [ ] :thumbsup: :thumbsup: **[Working With Neo4j Date And Spatial Types In A React.js App](https://medium.com/neo4j/working-with-neo4j-date-and-spatial-types-in-a-react-js-app-5475b5042b50)** - showing neo4j, spatial mapping, js/react, and all tools to work with these seamlessly


---
### Techniques and Papers
- [Node2Vec]()
- [ ] [Building The LinkedIn Knowledge Graph]()
- [ ] :thumbsup: [An introduction to using Keras with Neo4j](https://medium.com/octavian-ai/an-introduction-to-machine-learning-on-graph-databases-24ee502fd12e) - **probabilistic models + keras to do ml**
- [ ] [LAI-Net: Local-Ancestry Inference with Neural Networks](https://arxiv.org/abs/2004.10377)


---
### Tools
- [A NetworkX-esque API for Neo4j Graph Algorithms](https://medium.com/neo4j/experimental-a-networkx-esque-api-for-neo4j-graph-algorithms-4002baac45be)
  - NetworkX-Neo4j Python Lib 
  - [networkx-neo4j](https://github.com/neo4j-graph-analytics/networkx-neo4j)
  - [Neo4j Graph Data Science Library](https://github.com/neo4j/graph-data-science/)  
- [ ] [Graph Database Superpowers](https://medium.com/swlh/graph-database-superpowers-d6ba435954a7) - summary of some graph dbs
- [py2neo](https://py2neo.org/v3/) - python lib
- [Family Tree Data Generator](https://github.com/phohenecker/family-tree-data-gen) - github

##### NetworkX
- [NetworkX Docs](https://networkx.github.io/documentation/stable/reference/introduction.html)  

##### Neo4j

###### Basic Concepts
- Nodes are often used to represent entities
- Labels are used to shape the domain by grouping nodes into sets where all nodes that have a certain label belongs to the same set
  - Labels can be added and removed during runtime
  - A node can have zero to many labels
- A relationship must have exactly one relationship type.
  - Relationships always have a direction.
- Properties are name-value pairs that are used to add qualities to nodes and relationships.
- A traversal is how you query a graph in order to find answers to questions, for example: "What music do my friends like that I don’t yet own?"
- A schema in Neo4j refers to indexes and constraints.
  - Neo4j is often described as schema optional, meaning that it is not necessary to create indexes and constraints. You can create data — nodes, relationships and properties — without defining a schema up front. Indexes and constraints can be introduced when desired, in order to gain performance or modeling benefits.
  - Constraints are used to make sure that the data adheres to the rules of the domain.
- Node labels, relationship types and properties are case sensitive

- Nodes and relationships can be considered as low-level building blocks. The real strength of the property graph lies in its ability to encode **PATTERNS** of connected nodes and relationships. 
- Cypher
  - Cypher uses a pair of parentheses to represent a node: (). 
  - Cypher uses a pair of dashes (--) to represent an undirected relationship. Directed relationships have an arrowhead at one end (<--, -->). Bracketed expressions ([…​]) can be used to add details. This may include variables, properties, and type information

###### Common Questions
- How to bulk import: 

###### Articles
- [Getting started with neo4j in 10 minutes](https://towardsdatascience.com/getting-started-with-neo4j-in-10-minutes-94788d99cc2b) - quick neo4j
- [ ] :thumbsup: [Hands-On With The Neo4j Graph Data Science Sandbox](https://medium.com/neo4j/hands-on-with-the-neo4j-graph-data-science-sandbox-7b780be5a44f) - with **Game of Thrones** examples
  - Neo4j Bloom
- [A New Neo4j Integration with Apache Kafka](https://medium.com/neo4j/a-new-neo4j-integration-with-apache-kafka-6099c14851d2)
- [Py2neo v4: The Next Generation](https://medium.com/neo4j/py2neo-v4-2bedc8afef2)
- [How to query Neo4j from Python](https://towardsdatascience.com/neo4j-cypher-python-7a919a372be7)  
- [Graph Visualization With Neo4j Using Neovis.js](https://medium.com/neo4j/graph-visualization-with-neo4j-using-neovis-js-a2ecaaa7c379)
- [Interacting with Neo4j in NodeJS using the Neode Object Mapper](https://medium.com/neo4j/interacting-with-neo4j-in-nodejs-using-the-neode-object-mapper-3d99cb324546)
- [ ] :thumbsup: [Life after 1 year of using Neo4J](https://medium.com/hackernoon/life-after-1-year-of-using-neo4j-4eca5ce95bf5) - some good considerations on Neo4j details.
- [ ] [Comparing Neo4j driver, py2neo and neo4jrestclient with some basic commands using the Panama Papers Data](https://medium.com/@hisanor714/comparing-py2neo-and-neo4jrestclient-with-some-basic-commands-using-the-panama-papers-data-223a67bbe533)
  - *Definitely **py2neo is not an option**. Although it is user-friendly in many respects, it is too slow for counting queries. Neo4jrestclient is not bad, but sometimes it returns nested list structure which we have to deal with using some trick (e.g. “sum(temp,[])” which I want to avoid. So I think I would go with the **Neo4j Python driver**. After all it is the only official release supported by Neo4j.*
- [Py2neo v4: The Next Generation](https://medium.com/neo4j/py2neo-v4-2bedc8afef2)


##### Viz
- [ ] :thumbsup: [Large Graph Visualization Tools and Approaches](https://towardsdatascience.com/large-graph-visualization-tools-and-approaches-2b8758a1cd59)


---
### Datasets
- [ ] [Github to Download Geni](https://github.com/erlichya/geni-download)
- [ ] [WikiTree](http://proj.ise.bgu.ac.il/sns/wikitree.html)
- [ ] [Kinship Classification by Modeling Facial Feature Heredity
People](http://chenlab.ece.cornell.edu/projects/KinshipClassification/index.html)