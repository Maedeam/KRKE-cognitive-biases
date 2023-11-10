---
description: >-
  Here in "The XD iterative workflow" we will describe the workflow of XD with
  CPs, organised in 12 steps.
cover: .gitbook/assets/neuro-science.jpeg
coverY: 0
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 💡 eXtreme Design Methodology

## The eXtreme Design iterative workflow and 12 tasks

<figure><img src="https://github.com/KRKE-Delayed/KRKE-cognitive-biases/raw/main/documentation/img/XD-iterative-workflow.png" alt=""><figcaption><p>XD iterative workflow</p></figcaption></figure>

***

### **Task 1. Get into the project context**

The project aims to address bias in machine learning models and develop techniques to mitigate its impact. Bias in AI models can lead to unfair and discriminatory outcomes, affecting various aspects of society, such as hiring decisions, loan approvals, and criminal justice systems. The project focuses on identifying, understanding, and rectifying bias to build more equitable and ethical AI systems.

***

### Task 2. Collect requirement stories

We write two stories, possibly from real, documented scenarios, that samples the typical facts that should be stored in the resulting ontology. These stories include a description in natural language.

* #### Story 1

"Sarah, a politically active individual, had a strong confirmation bias towards a particular political party. She avidly followed news sources and social media accounts that shared views aligned with her party's ideology. One day, Sarah came across an article that presented a different perspective on a key issue. Despite the article being well-researched and providing evidence to support its claims, Sarah immediately dismissed it as biased and inaccurate, due to her confirmation bias. She shared the article with her friends, highlighting the parts that confirmed her pre-existing beliefs, reinforcing their shared biases.”

* #### Story 2

“John, a young professional, attends a networking event. As he enters the room, he notices a woman named Sarah standing by herself. Based on her elegant attire and confident posture, John immediately assumes that Sarah is unapproachable and disinterested in talking to him. He decides to focus his attention on other attendees who seem more approachable based on his preconceived notions. Little does John know that Sarah is actually a friendly and welcoming person who would have loved to engage in a conversation. Due to John's bias of discarding specifics to form generalities, he missed out on an opportunity to connect with someone who could have been a valuable professional contact or even a potential friend.”

***

### Task 3. Select a story that has not been treated yet

We choose our two previous stories that both of them are unique and based on true cases that they have not yet been treated and reviewed.

***

### Task 4. Transform the story into CQs

The pair process the story and from it derive a set of CQs. First the story is split into simple sentences, meaning that complex example sentences may be broken up into shorter sentences to increase clarity. The sentences are abstracted so that they describe a class of facts instead of a specific one.

<details>

<summary>An Example:</summary>

E.g. Rome is the capital of Italy, it is located in the Lazio region.

The sentences can be generalised in:

A city is the capital of a country. A city is located in a region.

In this case our CQs will be:

* What city is the capital of a certain country?
* In what region is a certain city located?
* In what country is a certain city located?

</details>

The CQs in our case will be:

1. Name of the observer is Story 1?
2. Which bias does Sarah exhibits?
3. Which information confirms her bias?
4. She holds belief about?
5. Which information she encountered?
6. Name of the characters in Story 2?
7. List all the generalities in Story 2?
8. Name of the bias does John exhibits in story 2?
9. What is the observation in story 2?
10. What are some specifics in Story 2?

***

### Task 5. Select a CQ that has not been treated yet

* CQ2: _"Which bias does Sarah exhibits?"_

***

### Task 6. Match the CQ to GUCs

This task has the aim of identifying candidate CPs based on the CQ, which express part of the LUC. The matching procedure can be done either with some tool support e.g., keyword based searching, or manually. In our case there was no match of CQ on [http://ontologydesignpatterns.org/](http://ontologydesignpatterns.org/)&#x20;

***

### Task 7. Select the CPs to reuse

The goal of this task is to select which of those patterns should be used for solving the modelling problem. We decided to go with Exhibiting of bias in story1.

***

### Task 8. Reuse and integrate selected CPs

The term _“reuse”_ here refers to the application of typical operation that can be applied to CPs i.e. import, specialisation, and composition. The result of this task is an UML diagram. This task can be divided in sub-tasks:

* **Task 8.1.** Select a CP that has not been integrated yet.
* **Task 8.2.** Specialisation: Identify CP's entities to be specialised and create subclass and sub-property axioms.

Iterate over the sub-tasks until all CPs have been integrated.

SO, in our case, the sub-tasks will be:

* **Task 8.1.** Which bias does Sarah exhibits?
* **Task 8.2.** Specialisation:

#### **Class**

We will first create a subclass of _**owl:Thing**_ which will be _**Bias1**_.

Then we will create two child classes of the _**Bias1**_ class which will be:

1. _**Observer**_ class
2. _**Bias**_ cclass

#### **Individual**

1. **Observer** Class has an Individual **Sarah**
2. **Bias** class has individual **Confirmation\_Bias**

#### Properties

_**exhibitsBias**_

1. Domain: _**Observer**_ class
2. Range: _**Bias**_ class

After all the above creating of class, properties and individual we will assert **Object Property Assertion** of Sarah that she **exhibitsBias Confirmation\_Bias**

<figure><img src=".gitbook/assets/image.png" alt=""><figcaption><p>Task 8</p></figcaption></figure>

***

### Task 9. Test and fix

The goal of this task is to validate the resulting module with respect to the CQ just modeled. To this aim, the task is executed through the following steps:

1. The CQ is elaborated in order to derive a unit test, e.g. SPARQL query;
2. The instance module is fed with sample facts based on the story;
3. The unit test is ran against the ontology module. If the result is not the expected one i.e. the test is not passed, the module is revised in order to fix it, and the unit test ran again until the test is passed;
4. Run all other unit tests associated with the story so far until they all pass. Notice that all unit tests are described in dedicated wiki pages that are properly linked to the associated story. If all CQs associated to the story have been addressed, the pair can pass to Task 10, otherwise they “go back” to Task 5.

**SPARQL Query**

<pre><code>PREFIX rdf: &#x3C;http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: &#x3C;http://www.w3.org/2002/07/owl#>
PREFIX rdfs: &#x3C;http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: &#x3C;http://www.w3.org/2001/XMLSchema#>
PREFIX bias: &#x3C;http://www.semanticweb.org/bias#>
SELECT ?subject
<strong>    WHERE { bias:Sarah  bias:exhibitsBias ?subject }
</strong></code></pre>

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption><p>Task 9</p></figcaption></figure>

***

### Task 10. Release module.

This task identifies the end of an iteration for a pair and its result is an ontology module. Once a whole story has been addressed, and the resulting module has been successfully tested, the new module can be released. The module is assigned with a URI and published in order to be shared by the whole team. If the module can be publicly shared, it can be published in open Web repositories such as ontologydesignpatterns.org. The module is then passed to the pair in charge of the integration. The pair of designer selects a new story if there are still some unaddressed.

***

### Task 11. Integrate, test and fix

Once a new module is released, it has to be integrated with all the others that constitute the current version of the ontology. At least one pair is in charge of performing integration and related tests: new unit tests are defined for the integration, and all existing ones are again executed as regression tests before moving to next task. In this task, all contextual statements are taken into account and all necessary alignment axioms are defined. The module is now under the complete control and editing of the pair in charge of the integration. The products of this tasks are new unit tests and alignment axioms, all properly documented in the wiki.

<figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption><p>Task 11</p></figcaption></figure>

***

### **Task 12. Release new version of the ontology**

Once all unit tests have been passed, a new version of the ontology can be released.





## Methodology

### Overview

Our final goal is modelling the biases presented above and create an ontology for semantic web technologies using a specific iterative method for pattern-based ontology design, called **eXtreme Design (XD).**

### **eXtreme Design (XD)**

As stated in the paper _"eXtreme Design with Content Ontology Design Patterns"_ by _Valentina Presutti, Enrico Daga, Aldo Gangemi and Eva Blomqvist_:

> "With the name eXtreme Design (XD), we identify an approach, a family of methods, and associated tools, based on the application, exploitation, and definition of **Ontology Design Patterns (ODPs)** for solving ontology development issues."

In few words, XD is an incremental, iterative method for pattern-based ontology design.

<figure><img src="https://github.com/KRKE-Delayed/KRKE-cognitive-biases/raw/main/documentation/img/XD-design-approach.png" alt=""><figcaption><p>eXtreme Design (XD)</p></figcaption></figure>

As you can see, XD adopts the notion of ontology project, a development project characterised by two main sets:

* _**The Problem Space:**_ which is composed of the actual modelling issues, here referred to as the _local problems_, that have to be addressed during the project.
* _**The Solution Space:**_ which is made up of reusable modelling solutions.

ODPs are associated with Generic Use Cases (GUC) and compose the ontology project’s solution space, which is used as the main knowledge source for addressing ontology design issues e.g. reengineering, evaluation, construction, etc., the ontology project’s problem space provides descriptions of the actual issues called “Local Use Cases” (LUC).

### Ontology Design Patterns

Before exploring the main principles and workflow of XD, it is worthy to spend some words on the methodology on which it is build upon [**Ontology Design Patterns** (Gangemi 2005)](bibliography.md#ontology-design-patterns-gangemi-2005).

Adapting a design idea originally from architecture, introduced by _Christopher Alexander_, ODPs is based on the idea of recurring modelling problems and providing a set of adaptable standard solutions. A _"pattern"_ is a solution to a problem in a given context. Originally described in _"A Pattern Language",_ Alexander states that:

> "The elements of this language are entities called patterns. Each pattern describes a problem that occurs over and over again in our environment, and then describes the core of the solution to that problem, in such a way that you can use this solution a million times over, without ever doing the same way twice."

Ontology Design Patterns provide small reusable (abstract) ontology templates with explicit documentation, stored in a searchable repository ordered by **competency questions** we distinguish:

* **Content Patterns:** Domain dependent, language independent.
* **Logical Patterns:** Domain independent, related to representation language.
* **Presentation Patterns:** Ontology from user perspective, as e.g. naming conventions.
* **Transformation Patterns:** How to transform an ontology in another representation language.

The two basic design principles building blocks are **Logical ODPs** and **Content ODPs (CPs).** The former solve design problems independently of a particular conceptualisation or domain, while the latter, are patterns for solving design problems for the domain classes and properties that populate an ontology; they address content problems. They are connected since Content ODPs are instantiations of Logical ODPs (or compositions of Logical ODPs).

In order to describe **CP**s, each one of them is associated with a _catalogue entry_ including the following set of information fields:&#x20;

* _**Name:**_ provides a name for the pattern.
* _**Intent:**_ describes the _Generic Use Case_ addressed by the pattern.
* _**Competency Questions:**_ contains examples of competency questions that the knowledge base associated with the CP needs to address.
* _**Also Known as:**_ provides other names (if any) with which the pattern is known
* _**Scenarios:**_ provides examples of requirements, expressed in natural language, that can be modeled by using the pattern.
* _**Diagram:**_ depicts a UML class diagram representing the pattern.
* _**Elements:**_ describes the elements (classes and relations) included in the pattern, and their role within the pattern.
* _**Consequences:**_ provides a description of the benefits and/or possible trade-offs when using the patterns.
* _**Known uses:**_ gives examples of realistic ontologies where the pattern is used.
* _**Extracted from/Reengineered from:**_ provides the reference ontology/conceptual schema (if any), from which the pattern has been extracted/reused.
* _**Related patterns:**_ indicates other patterns (if any) that are either a _specialization, generalization, composition,_ or _component_ of the pattern being described.

CPs are reusable solutions to recurrent modelling problems, these problems have two components: a domain and a use case (or task). A same domain can have many use cases, and a same use case can be found in different domains. Ontologies are usually considered models for a domain, but their use case is usually unknown. As reusable solutions, CPs must explicitly encode both a domain and a use case. Since use cases are extremely diversified, a catalogue of CPs requires the notion of a “Generic Use Case” (GUC), i.e. a generalization of use cases that can be provided as examples for an issue of domain modelling. A GUC is the expression of a recurrent scenario in different domain ontology projects. The intuition underlying GUC hierarchies is based on a methodological observation: ontologies must be built out of domain tasks that can be captured by means of _competency questions_. A competency question is a typical query that an expert might want to submit to a knowledge base of its target domain, for a certain task.

How we select the right pattern? Trying to summarise, usually if we try to model a problem, we have two components in our Content ODPs, we have first _**the domain**_ (where this application really will work) and, on the other hand, _**the requirements**_. The same domain can have many requirements and the same requirement can be found in different domains. So domain and requirements are things that are somehow to be represented for your content design pattern. A typical way of capturing requirements is by mean of **Competency Questions**, that are the key to your design patterns we are looking for. Content ODPs are collected and described in catalogues and comply to a common **presentation template**.

Here we provide an example: _Dr. Harald Sack_ in [_"Semantic Web Technologies"_ ](bibliography.md#semantic-web-technologies)model a fact like: _"Basil Rathbone played Sherlock Holmes in the 1939 movie 'The Hound of the Baskervilles'."_ So we want to model the fact that somebody is taking over a temporary role. We need to analyse the sentence that contains the knowledge that need to be represented. We have to match what's is in the sentence with some kind of competency question about a person that plays a character.

<figure><img src="https://github.com/KRKE-Delayed/KRKE-cognitive-biases/raw/main/documentation/img/ODPs-example.png" alt=""><figcaption><p>An example of <em>Sherlock Holmes role</em></p></figcaption></figure>

In the _"Problem Space"_ we have all the available competency questions, we need to map our basic sentence to a competency question that is about a person playing a character. If we find one in our _"Problem Space"_ usually we have mapping between the _competency questions_ and the _Ontology Design Patterns_ that are in the _"Solution Space"._ We select for example an ODPs that is described with _"represent objects and roles they play"_ and if it fits to our purpose we can take over this ontology template for our ontology and then represent this fact exactly with the according Ontology Design Pattern.

We need a large repository where we can look for ODPs, the one we will use in our project is [Ontology Design Patterns](http://ontologydesignpatterns.org/).

#### **eXtreme Design principles and tasks**

XD principles are inspired by those of the agile software methodology called eXtreme Programming (XP). The main idea of agile software development is to be able to incorporate changes easily, in any stage of the development. based on the idea of Gangemi A. in [_"eXtreme Design with Content Ontology Design Patterns"_](bibliography.md#extreme-design-with-content-ontology-design-patterns) The method make intensive use of _Content Ontology_ _Design Patterns_ (CPs) and its principles are based on modular design and collaboration. Main XD principles can be summarised as follow:

* **Costumer involvement and feedback.** A key point is to formulate complete and correct assumptions on the domain we want to model. Domain experts should be involved from the start in order to favouring the explicit expression of knowledge that is usually implicit in requirement documents, including competency questions.
* **Costumer stories, Competency Questions (CQs), and contextual statements.** The ontology requirements and its tasks are described in terms of small stories by the costumer representative. Designers work on those small stories and, together with the costumer, transform them in the form of CQs and contextual statements. Contestual statements are accompanyning assertions that explicit knowledge that is typically implicit in CQs. A CQ is a typical query that an expert might want to submit to a knowledge base of its target domain, for a certain task. It is a specific requirement on an ontology or a part of an ontology (e.g. an ontology design pattern). Given certain inputs, the ontology in conjunction with a reasoner can answer the competency question. CQs and contextual statements will be used through the whole development, and their definition is a key phase as the designers have the challenge to help the costumer in making explicit as much implicit knowledge as possible.
* **CP reuse and modular design.** If there is a CP's Generic Use Case (GUC) that matches our Local Use Case (LUC) it has to be reused. For our project we will use the design patterns collected in the [Ontology Design Patterns web site.](http://ontologydesignpatterns.org/wiki/Ontology\_Design\_Patterns\_.\_org\_\(ODP\))

Under the assumption that there exist classes of problems that can be solved by applying common solutions (as it has been experienced in software engineering), the aim is to support reusability on the design side specifically. CPs are a very beneficial kind of pattern for ontology design, because they provide solutions to domain-oriented problems, and are directly reusable.

CPs encode conceptual, rather than logical design patterns. They propose patterns for solving design problems for the domain classes and properties that populate an ontology, addressing content problems. They have an explicit non-logical vocabulary for a specific domain of interest (i.e. they are content-dependent). CPs provide solutions to domain modelling problems and affect only the specific region of the ontology dealing with such domain modelling problems. They are typically reused by applying specialisation, extension, and composition to them. In principle, CPs do not depend on any specific language, however in order to reuse them as building blocks, they have to be implemented in some way. (Gangemi A., Presutti V. Ontology Design Patterns, in Staab S. et al. (eds.): Handbook of Ontologies (2nd edition), Springer, 2009.)

* **Collaboration and Integration.** Since the ontology is developed in a modular way, integration is a key aspect of XD. Collaboration and constant sharing of knowledge is needed in a XD setting, in fact similar or even the same CQs and sentences can be defined for different stories. When this happens, it is important e.g. that the same CP is reused.
* **Task-oriented design.** The focus of the design is on that part of the domain of knowledge under investigation that is needed in order to address the user stories, and more generally, the tasks that the ontology is expected to address. This is opposed to the more philosophical approach of formal ontology design where the aim is to be comprehensive with respect to a certain domain.
* **Test-driven design.** Stories, CQs, and contextual statements are used in order to develop unit tests. A new story can be treated only when all unit tests associated with it have been passed. This aspect enforces the task-oriented approach of the method.
* **Pair design.** The team of designers is organized in pairs. At least one pair is in charge of integrating ontology modules.

***



A tutorial that puts together XD and Pattern-based Ontology Design is provided at the [_Training:EXtreme Design (XD): Pattern-based Ontology Design_](http://ontologydesignpatterns.org/wiki/Training:EXtreme\_Design\_\(XD\):\_Pattern-based\_Ontology\_Design)



