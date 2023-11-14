---
description: 'Project documentation: our workflow in this project'
cover: .gitbook/assets/iStock-1172252198.webp
coverY: -270.0260586319218
---

# 🧗 Workflow

This extensive project documentation outlines the essential phases of developing an ontology focused on modelling two clusters of cognitive biases using the [_eXtreme Design pproach_](extreme-design-workflow.md). Our primary objective is to construct a task-specific Application Ontology tailored precisely to the domain at hand.

In this project, we use a mix of methods. First, we start with a top-down approach to understand and define our main subject. Then, we make it even better by using helpful tools like [_QUOKKA_](tools.md) and [_FRED_](tools.md) to enhance knowledge extraction from textual sources, enabling us to enrich and validate the ontology with valuable insights derived from the text. This way, we create a strong and complete ontology using both ideas and real information

Following enlightening discussions and guidance from [_Prof. Aldo Gangemi_](https://www.unibo.it/sitoweb/aldo.gangemi/en) and [_Stefano De Giorgis_](https://www.unibo.it/sitoweb/stefano.degiorgis2/en), we have identified the initial steps necessary for advancing from the planning phase to the practical implementation of our ontology project.

## 1. Literature Review

_<mark style="color:green;">Background, Context and Literature State of the Art</mark>_&#x20;

To understand how biases work, we start by referring to [_Wikipedia_](https://www.wikipedia.org/) to gain a foundational understanding and precise definition of the biases under investigation. We also read academic papers and articles from specialized journals. This helped us form our initial understanding of how biases behave and what makes them tick.

## 2. LLMs

_<mark style="color:green;">Large Language Models</mark>_

_LLM_s play a significant role in ontology development, providing suggestions, generating ontological elements, and aiding in the extraction of relevant information from textual sources. We use _AI_ like[ _ChatGPT_](https://chat.openai.com/) and [_Bard_](https://bard.google.com/chat) to create _Large Language Models_ to turn biases definitions into user stories.

We initially ask _AI_ a broad definition of biases and then request to generation ten different hypothetical scenarios to illuminate that particular bias. Among them, we selected one of the most tangible scenarios and crafted a user story. Subsequently, we extracted three different competency questions from this scenario, aiming to cover three main domains during the selection of these _CQ_s:

[AgentRole CPs](http://ontologydesignpatterns.org/wiki/Submissions:AgentRole)

Which agent does play this role? And What is the role that is played by that agent?

[Sequence CPs](http://ontologydesignpatterns.org/wiki/Submissions:Sequence)

What is before what? What's next? and What's immediately following this?

[Situation CPs](http://ontologydesignpatterns.org/wiki/Submissions:Situation)

What is the context or situation of something? and What are the things present in this context or situation?

Following this, with the assistance of _AI_, we created classes and properties for bias modeling. Finally, for better users comprehension of these classes and properties, we presented three diverse examples.

## 3. Frame Semantic Triggers

_<mark style="color:green;">Words as Frame Semantic Triggers</mark>_

We extract [_Lexical Units_](glossary.md#lexical-units) from the textual contents, which will be utilized to find [_Semantic Frames_](glossary.md#frame-semantics) in _Framester_. As part of the _XD_ procedure, we create _Competency Questions (CQs)_ from the scenarios. Analyzing these _CQs_ helps us identify classes and properties restrictions needed to answer them effectively. Whenever we run into problems while we're building the project, we can check _Ontology Design Patterns_ for ideas on how to solve them.



