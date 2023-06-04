# Algorithms and Data Structure 
Repository focused on the activities of the discipline of algorithms and data structures ll of the UFRN computer engineering course.

### Lessons
**Week 03** - Linkedlist, Queques, Stacks
- **Project description**: The object proposed here is to solve three common challenges of code interviews for programmers, these questions involve subjects such as: linkedlist, queues and stacks, which are extremely important to develop good logic.
We were encouraged to use the ChatGPT tool to help us solve the challenges and to support the learning journey.
To ensure that the functions were developed correctly, we use tests to validate the applied logic.
- The explanation in video: [![Open in Loom](https://img.shields.io/badge/-Video-83DA77?style=flat-square&logo=loom)](https://www.loom.com/share/03bd5b6f2d2541a4a3e73577fe531548) 

**Week 04** - Recursion, Binary tree and Search tree
- **Project description**: The object proposed here is to solve two common challenges of code interviews for programmers, like Fibonacci and now involving recursive problems.
We were encouraged to use the ChatGPT tool to help us solve the challenges and to support the learning journey.
To ensure that the functions were developed correctly, we use tests to validate the applied logic.
- The explanation in video: [![Open in Loom](https://img.shields.io/badge/-Video-83DA77?style=flat-square&logo=loom)](https://www.loom.com/share/f645b35a6a1b453f8f61c8b588e2182d)

**Week 10** - Small words(analysis about the fligthts in Brazil)
- **Project description**: Este trabalho tem por objetivo usar dos assuntos estudados como assortatividade, análise bivariada, componentes conectados e coeficiente de clusteriazação para fazer uma análise das conexões entre os voos no Brazil. Neste sentido, realizamos as 5 questões propostas da atividade, com a colaboração de [Vilson Rodrigues](https://github.com/Vilsonrodrigues) e dados de [Alvaro](https://github.com/alvarofpp/dataset-flights-brazil).

**Assortativity**

Network assortivity is a fundamental property that describes the tendency of network nodes to connect to other nodes with similar characteristics. This property influences the structure and dynamics of networks and is an active area of research in network science.

By calculating the assortativity coefficient using a specific node attribute, a value of approximately 0.37 was obtained. This positive value indicates the presence of assortativity in the network, implying that nodes with similar attributes tend to connect with each other.

**Análise Bivariada**

It was proposed to perform a bivariate analysis between the vertex degree and the average number of neighbors. This bivariate analysis can provide insights into the structure of the network, such as assortativity or the presence of hubs, as well as into connectivity patterns between vertices. It is important to point out that the results of this analysis may vary according to the type of network and its specific characteristics.

We got the following result:

Degree assortativity for Brazil = -0.1943

Degree assortativity for North = -0.2204

Degree assortativity for Northeast = -0.3271

Degree assortativity for South = -0.3555

Degree assortativity for Southeast = -0.3596

Degree assortativity for Central-West = -0.3436
It can be observed that airports in Brazil, at both national and regional levels, exhibit disassortative behavior, as indicated by their negative degree assortativity coefficients. This implies that airports with a high number of connections are not exclusively linked to other airports with similarly high connectivity.

**Connected components**

The components connected in a network are sets of nodes interconnected through direct or indirect connections. They represent distinct units of connectivity within the network and are important for understanding the structure and organization of the network. The analysis of connected components allows identifying groups of interconnected nodes and understanding the global connectivity of the network. For this task, we determined how many connected components there are in the Brazilian air network.

We obtained that the network is not connected and that it has 6 components connected.

**Shortest path**

| Region    | IATA Code | City            |
| --------- | --------- | --------------- |
| North     | SBAM      | Amapá           |
| Northeast | SBAR      | Aracajú         |
| South     | SBBG      | Bagé            |
| Southeast | SBCC      | Criciúma        |
| Midwest   | SBBH      | Belo Horizonte  |


Finally, we performed a clustering coefficient study considering the 5 regions of Brazil.

- The explanation in video: [![Open in Loom](https://img.shields.io/badge/-Video-83DA77?style=flat-square&logo=loom)](https://www.loom.com/share) 

