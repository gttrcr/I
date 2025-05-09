---
title: Is there an "actual" library for agnostic transition systems?
date: 2024-01-05
permalink: /posts/2024/01/05/
tags:
   - Science
   - Computer science
   - Tools
---

## Graph libraries by programming languages

### Python

1. NetworkX:
   - NetworkX is one of the most popular libraries for creating, manipulating, and studying the structure, dynamics, and functions of complex networks.
   - Easy to use, extensive documentation, supports both directed and undirected graphs, many built-in algorithms (e.g., shortest path, clustering, etc.), visualization capabilities (when combined with Matplotlib or other visualization tools).
   - [NetworkX](https://networkx.github.io/documentation/stable/)

2. igraph:
   - igraph is another powerful library for network analysis, known for its efficiency and scalability.
   - Performance-oriented, supports large graphs, provides a wide range of graph algorithms, integrates well with other scientific computing libraries.
   - [igraph](https://igraph.org/python/)

3. PyVis:
   - PyVis is used for visualizing network graphs in Python, using the vis.js library.
   - Interactive visualizations, easy to use for creating web-based visualizations.
   - [PyVis](https://pyvis.readthedocs.io/)

### JavaScript

1. D3.js:
   - D3.js is a powerful library for creating dynamic and interactive data visualizations in web browsers.
   - Extensive capabilities for data visualization, integrates well with web technologies, highly customizable.
   - [D3.js](https://d3js.org/)

2. vis.js:
   - vis.js is specifically designed for visualizing data structures like networks.
   - Easy to use, interactive visualizations, supports large datasets, good documentation.
   - [vis.js](http://visjs.org/)

### Java

1. JGraphT:
   - JGraphT is a free Java graph library that provides mathematical graph-theory objects and algorithms.
   - Comprehensive set of algorithms, supports various types of graphs (directed, undirected, weighted, etc.), good performance.
   - [JGraphT](https://jgrapht.org/)

2. JUNG (Java Universal Network/Graph Framework):
   - JUNG is a library that provides a common and extendible language for the modeling, analysis, and visualization of data that can be represented as a graph or network.
   - Flexible, integrates well with other Java libraries, visualization capabilities.
   - [JUNG](https://github.com/jrtom/jung)

### R

1. igraph:
   - Similar to its Python counterpart, igraph for R is used for network analysis and visualization.
   - Efficient graph manipulation, comprehensive algorithms, visualization capabilities.
   - [igraph R](https://igraph.org/r/)

2. networkD3:
   - networkD3 provides tools to create D3 JavaScript network graphs from R.
   - Interactive network visualizations, integrates with D3.js.
   - [networkD3](https://christophergandrud.github.io/networkD3/)

### C++

1. Boost Graph Library (BGL):
   - BGL is a powerful, flexible, and efficient library for graph data structures and algorithms.
   - Extensive range of algorithms, highly efficient, part of the larger Boost C++ Libraries collection.
   - [Boost Graph Library](https://www.boost.org/doc/libs/release/libs/graph/doc/)
   - *Best for general-purpose graph algorithms and data structures, with extensive community support and integration with the Boost suite of libraries.*

2. LEMON (Library for Efficient Modeling and Optimization in Networks)
   - LEMON is a C++ library that focuses on combinatorial optimization tasks and provides a collection of easy-to-use templates and tools for working with graphs.
   - High performance, flexibility, and a comprehensive set of algorithms for graph theory and combinatorial optimization.
   - [LEMON](https://lemon.cs.elte.hu/trac/lemon)
   - *Ideal for optimization and combinatorial tasks, with a strong emphasis on performance and flexibility.*

3. CGAL (Computational Geometry Algorithms Library)
   - CGAL provides easy access to efficient and reliable geometric algorithms in the form of a C++ library.
   - While primarily focused on computational geometry, CGAL includes graph-related components, particularly for planar graphs and mesh generation.
   - [CGAL](https://www.cgal.org/documentation.html)
   - *Suited for applications needing computational geometry in addition to graph algorithms.*

4. Graph-tool
   - Graph-tool is an efficient Python library that uses C++ for its core data structures and algorithms, providing C++ bindings.
   - Highly efficient, supports large-scale graphs, extensive range of algorithms, strong focus on performance.
   - [Graph-tool](https://graph-tool.skewed.de/)
   - *Excellent if you need both a C++ and a Python interface, optimized for performance and large-scale graph analysis.*

5. STINGER (STructure INdependent Graph Representation)
   - STINGER is designed for handling dynamic graphs that change over time, such as those found in social networks or network security.
   - Optimized for high performance, dynamic graph updates, and parallel processing.
   - [STINGER](http://www.stingergraph.com/)
   - *Preferred for dynamic graph scenarios, especially where real-time updates and high throughput are critical.*

### Wolfram Language

1. Wolfram Language
   - Numeric and symbolic computation: The Wolfram Language excels at symbolic mathematics, enabling manipulation of algebraic expressions, solving equations symbolically, and performing calculus operations like differentiation and integration. It supports high-precision arithmetic, numerical solving of equations, optimization, and extensive support for linear algebra and other numerical methods.
   - Built-in Algorithms: the language provides comprehensive tools for creating both static and interactive visualizations, including 2D and 3D plots, charts, graphs, and custom graphics. Built-in functions for data import, cleaning, analysis, and visualization. Machine learning capabilities include supervised and unsupervised learning, neural networks, and natural language processing.
   - A vast collection of algorithms for various fields such as graph theory, number theory, combinatorics, geometry, and more are readily available.
   - Integration and Connectivity: Seamless integration with external systems, databases, and APIs. It also supports a wide range of file formats for import and export.

## Modeling tools

1. Z Notation:
    - A formal language for specifying computer systems. It uses a set of mathematical symbols to describe the states and transitions of a system.
    - Particularly used for the specification of critical systems where a high level of accuracy is essential.
    - Z Notation is a formal language based on set theory and predicative logic for specifying computer systems.
    - It is mainly used to specify high-level requirements and specifications of critical software.
    - Used in critical systems projects, such as aerospace and rail traffic control.
    - [Wikipedia - Z notation](https://en.wikipedia.org/wiki/Z_notation)
2. TLA+ (Temporal Logic of Actions):
    - A language for specifying, modeling, and verifying concurrent and distributed systems.
    - Used to describe the behavior of complex algorithms and distributed systems. TLA+ allows you to verify the properties of such systems through model checking.
    - The TLA+ toolbox provides tools for building and verifying models.
    - TLA+ (Temporal Logic of Actions) is a language for specifying, modeling and verifying concurrent and distributed algorithms and systems.
    - Uses a combination of mathematical logic and set theory to describe the behaviors of systems over time. The TLA+ Toolbox tool includes the TLC model checker to check model properties.
    - Used by companies like Amazon to test distributed protocols and critical systems.
    - [TLA+](https://lamport.azurewebsites.net/tla/tla.html)
3. VHDL (VHSIC Hardware Description Language):
    - A hardware description language used to model digital electronic systems.
    - Used for electronic circuit design and simulation.
4. SMV (Symbolic Model Verifier):
    - A specification language and model checking tool for checking logical properties in systems.
    - Mainly used for verifying hardware models and protocols.
5. B Method:
    - A formal method for specifying, designing, and coding reliable software.
    - Used in environments where formal correctness is crucial, such as aerospace and railway systems.
    - Atelier B, a suite of tools to support development based on the B method.
6. Promela (Process Meta Language):
    - A specification language used with the SPIN formal verification tool.
    - Used to describe and analyze concurrent and communication systems.
7. Coq:
    - A formal proof assistant that allows you to specify programs and verify their correctness.
    - Used in mathematics and computer science to verify complex theorems and programs.
    - The Coq IDE development environment provides an interface for interacting with the Coq language.
    - Coq is a formal programming language that allows you to define specifications and verify properties using mathematical proofs.
    - Uses a rich type system and supports extracting certified programs from formal specifications.
    - Used for verifying complex algorithms and mathematical theorems.
    - [Coq](https://coq.inria.fr/)
8. VDM (Vienna Development Method):
    - A formal specification method that includes a language for modeling software systems.
    - Applied to develop reliable and robust software, especially in industrial settings.
    - VDM is one of the oldest formal methods for software development, which uses formal specifications to model and analyze systems.
    - Includes support for specification and verification of concurrent and distributed systems.
    - Widely used in industrial settings for critical software development.
    - [Overture Tool](http://overturetool.org/)
9. SPIN and Promela:
    - SPIN is a model checker for concurrent systems, and Promela is the language used to describe the models to be verified.
    - Used for testing communication protocols, concurrent algorithms, and more.
10. Event-B:
     - A variant of method B, focused on formal modeling and verification of systems.
     - Used for modeling reactive, embedded and distributed systems.
     - Event-B is a method for formal system modeling that uses set theory and logic to describe and verify properties of complex systems.
     - Supports the use of progressive refinements to develop detailed specifications from abstract models.
     - Mainly used for embedded systems and critical software.
     - [Event-B](https://www.event-b.org/)
11. Petri Nets:
     - A mathematical model to describe concurrent event systems.
     - Used to model and analyze the behavior of distributed and concurrent systems, such as communications networks and manufacturing systems.
12. Vérif: A language for formal verification of network protocols and critical systems, used primarily in advanced research and development environments.
13. UML (Unified Modeling Language): It is one of the most widespread and standardized modeling languages for representing the structure and behavior of software systems. It offers a wide range of diagrams to describe different aspects of a system.
14. SysML (Systems Modeling Language): Derived from UML, it is designed to model complex systems that include both hardware and software components. It is mainly used in systems engineering.
15. ArchiMate: A modeling language specific to enterprise architecture, providing tools to describe, analyze, and visualize enterprise architectures across different levels of abstraction.
16. BPMN (Business Process Model and Notation): Used for business process modeling, BPMN offers a standard notation that is understandable by both technical and non-technical users, making it easy to analyze and optimize business workflows.
17. C4 Model: A modeling approach to software architecture that provides a series of diagrams to represent different levels of detail in a software system. It is appreciated for its simplicity and ease of understanding, making it accessible to different stakeholders.
18. Alloy: lightweight formal modeling notation and analysis tool used primarily in software engineering to specify and analyze software systems.

- Provides a formal modeling language for describing abstract software structures and behaviors. It allows to specify the structure of a system, its properties, and constraints in a concise and precise manner.
- Declarative syntax that emphasizes what needs to be modeled rather than how it should be implemented. This makes models more concise and easier to understand, promoting better communication among stakeholders.
- Include a model analyzer that can automatically check the consistency of models and verify properties specified in Alloy. This helps in detecting design flaws, inconsistencies, and potential errors early in the development process.
- Allows to specify the scope and bounds of the model, which helps in controlling the complexity of analysis.
- Can generate counterexamples that illustrate why the property does not hold. This helps developers understand the causes of design flaws and refine their models accordingly.
- Come with integrations for popular Integrated Development Environments (IDEs) such as Eclipse and IntelliJ IDEA.
- Widely used in academia as an educational tool for teaching formal methods and software engineering concepts. Its simple yet powerful syntax makes it suitable for introducing students to formal modeling and analysis techniques.
- Active community of users and researchers contributing to the development and improvement of Alloy. This community provides resources, tutorials, and case studies that help newcomers learn and apply Alloy effectively.

## UMLs and representation software

UML tools are software applications that aid in the creation, analysis, and management of UML diagrams and models, which are crucial for visualizing the design of software systems. These tools offer graphical interfaces for drawing various UML diagrams such as class diagrams, sequence diagrams, use case diagrams, and activity diagrams, among others. These diagrams are essential for representing both the static structure and dynamic behavior of a system. UML tools also support model management by providing features such as version control, model comparison, and merging, ensuring consistency and coherence across different parts of a model. In addition, many of these tools include code generation capabilities, enabling the automatic creation of source code from UML diagrams in various programming languages. This feature is particularly useful for bridging the gap between design and implementation. Moreover, some UML tools offer reverse engineering capabilities, allowing users to generate UML diagrams from existing source code. This is beneficial for understanding and documenting legacy systems. Modern UML tools often facilitate collaboration by allowing multiple users to work on the same model simultaneously. They also provide robust documentation generation features, making it easier to communicate design details to stakeholders. Advanced UML tools come equipped with validation features to check the correctness and consistency of models. Some also support simulation, which helps in testing the behavior of the system as depicted by the UML diagrams. These comprehensive functionalities make UML tools indispensable for system architects, designers, and developers, enhancing the clarity, consistency, and communication of system designs.

ls include IBM Rational Rose, Sparx Systems Enterprise Architect, Microsoft Visio, Lucidchart, Visual Paradigm, and ArgoUML. Each of these tools has its own set of features and strengths, tailored to different aspects of UML modeling and various stages of the software development lifecycle. Consider the following list about [Unified Modeling Language tools](https://en.wikipedia.org/wiki/List_of_Unified_Modeling_Language_tools) and the following table (sublist of the previous list filtered by tools whose last release occurred after 2020).

|              Name               |                    Creator                     |                            Platform / OS                            | First public release |     Latest stable release     | Open source |                              Software license                              |  Programming language used   |
| :-----------------------------: | :--------------------------------------------: | :-----------------------------------------------------------------: | :------------------: | :---------------------------: | :---------: | :------------------------------------------------------------------------: | :--------------------------: |
|              Cacoo              |                     Nulab                      |                        Windows 7+, Mac OS X                         |       2010-10        |  Website frequently updated   |     No      |                     Commercial, Free edition available                     |            HTML5             |
|            Creately             |                    Cinergix                    |                          Windows, Mac OS X                          |         2008         |  Website frequently updated   |     No      |                     Commercial, Free edition available                     |            HTML5             |
| Diagrams.net previously Draw.io |                  JGraph Ltd.                   |                    Windows, Linux, macOS, Chrome                    |      2016-09-06      |  Website frequently updated   |     Yes     |                              Free, Apache v2                               |       Javascript, Java       |
|             Gliffy              |               Gliffy by Perforce               |            Chrome, Safari, Firefox, Internet Explorer 9+            |      2006-08-01      |  Website frequently updated   |     No      |                           Commercial, Free trial                           |     HTML5 and JavaScript     |
|           Lucidchart            |                 Lucid Software                 |                   Windows, macOS, Linux, Solaris                    |       2008-12        |  Website frequently updated   |     No      |                      Commercial / Free (educational)                       |     HTML5 and JavaScript     |
|              Astah              |               ChangeVision, Inc.               |                        Cross-platform (Java)                        |      2009-10-19      |       2024-03-12 (v9.2)       |     No      |           Commercial. Free education edition, subscription model           |             Java             |
|              Umple              |              University of Ottawa              |                    Cross-platform; Java/Eclipse                     |         2008         |     2024-01-10 (v1.33.0)      |     Yes     |                                MIT License                                 |    Java, PHP, JavaScript     |
|     Software Ideas Modeler      |                  Dusan Rodina                  |                    Windows (.NET), Linux (Mono)                     |      2009-08-06      |          2023-11-27           |     No      |                Commercial, Freeware for non-commercial use                 |              C#              |
|            PlantUML             |                 Arnaud Roques                  |                        Cross-platform (Java)                        |      2009-04-17      |    2023-07-12 (v1.2023.10)    |     Yes     |                                    GPL                                     |             Java             |
|             Modelio             |          Modeliosoft (SOFTEAM Group)           |                        Windows, Linux, macOS                        |         2009         |      2023-03-31 (5.3.1)       |     Yes     |           Core tool: GPL, Extensions: Apache License, Commercial           |             Java             |
|             Papyrus             | Commissariat à l'Énergie Atomique, Atos Origin |                    Windows, Linux, macOS (Java)                     |      2013-06-27      |      2023-03-15 (v6.4.0)      |     Yes     |                                    EPL                                     |             Java             |
|      Enterprise Architect       |                 Sparx Systems                  |           Windows (supports Linux and macOS installation)           |         2000         | 2023-03-02 (v16.1 Build 1625) |     No      |                                 Commercial                                 |             C++              |
|             StarUML             |                     MKLab                      |                        Windows, macOS, Linux                        |      2005-11-01      |       2023-01-12 (v5.1)       |     No      |          Commercial, You can evaluate for free without time limit          |           V5 Java            |
|      Umbrello UML Modeller      |                 Umbrello Team                  |                         Unix-like; Windows                          |      2003-01-24      |      2022-10-22 (v2.34)       |     Yes     |                                    GPL                                     |           C++, KDE           |
|            NetBeans             |               Oracle Corporation               |                     Windows, macOS, Linux, Unix                     |         1996         |          2021-03-12           |     Yes     |                                CDDL or GPL2                                |             Java             |
|               yEd               |                  yWorks GmbH                   |                     Windows, macOS, Linux, Unix                     |       Un­known       |      2021-03-11 (v3.21)       |     No      |                                    Free                                    |             Java             |
|            MagicDraw            |     No Magic, a Dassault Systèmes company      | Windows Vista SP2 and later, OS X Mountain Lion and later, or Linux |         1998         |      2021-02-12 (2021x)       |     No      |                                 Commercial                                 |             Java             |
|              BOUML              |                  Bruno Pagès                   |                           Cross-platform                            |      2005-02-26      |          2021-01-14           |     No      | Free from v7.0, Commercial starting from v5.0 up to v6.12, GPL before v5.0 | C++/Qt and Java ("plug-out") |
|             JetUML              |              Martin P. Robillard               |                        Cross-platform (Java)                        |      2015-01-23      |       2020-12-04 (v3.1)       |     Yes     |                                    GPL                                     |             Java             |
|               ATL               |      Obeo, INRIA Free software community       |                        Cross-platform (Java)                        |       Un­known       |      2020-06-22 (4.2.1)       |     Yes     |                                    EPL                                     |             Java             |
|       Eclipse UML2 Tools        |               Eclipse Foundation               |                        Cross-platform (Java)                        |         2007         |      2020-03-02 (v5.5.1)      |     Yes     |                                    EPL                                     |             Java             |
|          CaseComplete           |                Serlio Software                 |                               Windows                               |         2004         |          2020 (v15)           |     No      |                                 Commercial                                 |              C#              |

## Source

- Consider the following [Overview of Standard Graph File Formats](https://intranet.icar.cnr.it/wp-content/uploads/2018/12/RT-ICAR-PA-2018-06.pdf) from Consiglio Nazionale delle Ricerche Istituto di Calcolo e Reti ad Alte Prestazioni
