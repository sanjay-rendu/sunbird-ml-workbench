Introduction
============


ML-Workbench
------------

What is it?
~~~~~~~~~~~

ML-Workbench is a way to create, collaborate and consume Machine Learning (ML) tools and processes. It creates a level of abstraction that enables its users to express a ML application as a Directed Acyclic Graph. Each vertex of the graph represents an operation on the incoming data, while the edges represent the data flow.

It is natural for ML solutions to go through revisions during the design phase or even through their lifetime, as they are unfinished by design. Also, the desired implementation of components that make up a ML application may not always be available in a single library or a language. This has created a high entry and customization barrier, making it difficult to create and maintain ML solutions.

We have designed ML-Workbench as a solution to the above issues at Ekstep. ML-Workbench will host common ML operations and processes that are widely recognised in the ML community, to help you quickly get to a baseline solution. These operations and processes may have multiple implementations to suit the needs of different types or scales of data. It will also provide different levels of engagement for people working on the solution design, operational implementation and scalability of the solution, to enable better collaboration and experimentation.

Who should use it?
~~~~~~~~~~~~~~~~~~

If your solution has a long standing application, it is inevitable that the solution will require revisions and collaboration amongst multiple people. We recommend using ML-Workbench for individuals or organisation that are designing such long standing applications.

Guiding principles
~~~~~~~~~~~~~~~~~~

* **Easy to initiate**: ML workbench will provide a ready-made library and documentation, that can enable even novice users to readily write new applications from scratch.
* **Highly customizable**: The library will ensure that solutions are highly customizable, as the user can play and experiment with input parameters of APIs. It should enable addition, deletion or modification of intermediate steps.
* **Extensible**: ML Workbench library will allow users to add their own custom libraries that comply with the specified guidelines and conventions.
* **Automatically deployable**: The ML workbench will support creation of models and configuration files that can be directly used for deployment in production environment without further human intervention.
* **Scalable**: The ML workbench will enable creation of an end-to-end ML application that can work on large scale data, with high performance.
* **Repeatable**: The ML workbench will enable creation of applications which are robust and consistent, i.e. given identical datasets as input for different runs of an application, they would produce identical results without failure.

