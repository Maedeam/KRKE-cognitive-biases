---
description: Ontology page for "Positivity Effect"
cover: ../../.gitbook/assets/pb-iv-winter-wealth-wellbeing-banner.jpeg
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

# ⚡ Positivity Effect

## 1. Literature Review&#x20;

_<mark style="color:green;">Background, Context and Literature State of the Art</mark>_&#x20;

### Wikipedia&#x20;

The Positivity Effect, is a [Cognitive Bias](https://en.wikipedia.org/wiki/Cognitive\_bias) which is the&#x20;

[Wikipedia Link](https://en.wikipedia.org/wiki/Cross-race\_effect)

### Research Paper(s)

\[1] _B_

***

## 2. LLMs

_<mark style="color:green;">Large Language Models</mark>_

### 2.1. General Description

_<mark style="color:green;">A general description of the bias to get an overall idea of the domain</mark>_

The "Halo Effect" is a cognitive bias that influences individuals to form a favorable overall impression of a person, product, or entity based on a single positive trait, experience, or characteristic. This positive evaluation creates a metaphorical "halo" around the subject, leading to the assumption that other unrelated aspects or qualities must also be positive. In essence, the Halo Effect occurs when a positive perception in one area extends to influence judgments in unrelated areas, clouding objectivity. This bias can result in overly positive evaluations and skewed assessments, as individuals project their admiration or approval from one specific aspect onto the overall entity, sometimes leading to inaccurate or biased conclusions.

### 2.2. Examples Scenarios

_<mark style="color:green;">Ten different examples of possible scenarios to understanding the context of the domain</mark>_

1. **Interview Impressions:** A job candidate, known for a prestigious accomplishment, is automatically assumed to possess strong leadership skills and expertise in various areas, influencing interviewers to positively evaluate unrelated qualifications.
2. **Celebrity Influence:** Fans of a famous musician may extend their admiration for the artist's musical talent to presume expertise in other fields, like endorsing a product or expressing political opinions.
3. **Physical Attractiveness:** Individuals deemed physically attractive may be unconsciously perceived as possessing positive qualities in areas such as intelligence or kindness, solely based on their appearance.
4. **Company Reputation:** A company renowned for its innovative products might benefit from the Halo Effect, with consumers assuming excellence in customer service and ethical practices, even in the absence of direct evidence.
5. **Academic Achievements:** A student excelling in one subject is often perceived as competent in all subjects, showcasing the Halo Effect in educational settings.
6. **Political Figures:** Supporters of a political figure may attribute competence in various policy areas based on charisma or success in a specific domain, impacting overall political judgments.
7. **Athletic Endorsements:** An athlete's endorsement of a product might lead consumers to believe in the product's quality, even if the athlete's expertise lies solely in sports.
8. **Social Media Influence:** Influencers with a large following may experience the Halo Effect, where their audience assumes expertise in diverse fields beyond their primary content domain.
9. **Charitable Activities:** Individuals engaged in charitable work might be perceived as virtuous in all aspects of their lives, leading to a positive Halo Effect on their character.
10. **Product Packaging:** A well-designed and visually appealing product package may influence consumers to assume superior quality and functionality, creating a positive Halo Effect for the entire product.

### 2.3 Main Scenario

_<mark style="color:green;">Considering one scenario; here the</mark> <mark style="color:green;"></mark><mark style="color:green;">**Social Media Influence,**</mark> <mark style="color:green;"></mark><mark style="color:green;">as our main user story</mark>_

**User Story:** Navigating Social Media Influence and the Halo Effect

**User:** Emma, an avid follower of a popular social media influencer, Lily.

**Objective:** As Emma, I aim to critically assess the recommendations and opinions of Lily, the influencer, on various topics, recognizing and mitigating the potential Halo Effect that might influence my judgments.

**Scenario:** Lily, known for her engaging content on fashion and lifestyle, starts expressing opinions on environmental conservation. Emma, impressed by Lily's fashion sense, automatically assumes Lily's expertise in environmental matters, supporting Lily's initiatives without independently evaluating their environmental impact.

**Desired Outcome:** Emma, realizing the potential Halo Effect, decides to delve deeper into environmental issues. She seeks information from reliable sources, ensuring a more informed stance, separating Lily's influence in fashion from her credibility on environmental topics. Emma aims to avoid undue biases and make decisions based on a comprehensive understanding of each subject.

### 2.4. Possible CQs

_<mark style="color:green;">Generating some possible competency questions</mark>_

**1. AgentRole Competency Question:**

* **CQ1-1:** Who is the primary agent influencing Emma's opinions in the scenario?
* **CQ1-2:** What role does Lily, the social media influencer, play in shaping Emma's perspectives
* **CQ1-3:** Are there other agents aside from Lily that contribute to Emma's decision-making regarding environmental matters?

**2. Sequence Competency Question:**

* **CQ2-1:** What events or content precede Lily expressing opinions on environmental conservation in Emma's social media feed?
* **CQ2-2:** What follows Emma's initial support for Lily's initiatives in the context of environmental matters?
* **CQ2-3:** What is the sequence of events leading to Emma's realization of the potential Halo Effect?

**3. Situation Competency Question:**

* **CQ3-1:** What is the broader context or situation in which Emma encounters Lily's opinions on environmental issues?
* **CQ3-2:** What factors are present in the social media environment that contribute to Emma's automatic support for Lily's environmental initiatives?
* **CQ3-3:** How does Emma's understanding of the broader situation evolve as she navigates through Lily's content and environmental topics?

These competency questions aim to address the roles, sequences, and situations surrounding the user story, providing a comprehensive exploration of the factors influencing Emma's decision-making.

### 2.5. Modelling Bias

_<mark style="color:green;">For making an Ontology and modelling the bias, we can create these classes and properties</mark>_

**Classes:**

* **CognitiveBias**: Represents various types of cognitive biases, including the "Halo Effect." This class serves as a superclass for specific types of biases.
* **BiasType**: Represents different categories or types of biases. In this case, it would include the "Halo Effect" as a specific type of cognitive bias.
* **TargetDomain**: Represents the specific domain or area where the "Halo Effect" occurs. For example, in the scenario of celebrity admiration, the target domain could be the celebrity's expertise outside of their primary field.
* **InfluencingFactor**: Represents factors or traits that contribute to the formation of the "Halo Effect." This could include traits like talent, charisma, or public image.

**Properties:**

* **hasBiasType**: Connects a CognitiveBias instance to its corresponding BiasType instance, indicating that it is a specific type of bias, such as the "Halo Effect."
* **targetsDomain**: Specifies the TargetDomain instance that is the subject of the "Halo Effect" in a particular scenario.
* **isInfluencedBy**: Connects an instance of the "Halo Effect" to the factors or traits (InfluencingFactor) that contribute to its occurrence.
* **resultsInPerception**: Indicates the impact of the "Halo Effect" on perception or judgment. For example, it could represent the perception that excellence in one area implies excellence in unrelated areas.

These classes and properties provide a foundational structure for modeling the "Halo Effect" in different contexts and scenarios. The ontology can be extended or refined based on specific use cases and requirements.

### 2.6. Examples Ontology

_<mark style="color:green;">Three different examples of usage of the Ontology</mark>_

**Example 1: Celebrity Admiration Scenario**

Class Instances:

* Instance of CognitiveBias: "Halo Effect"
* Instance of BiasType: "Celebrity Bias"
* Instance of TargetDomain: "Environmental Advocacy"
* Instance of InfluencingFactor: "Public Statements"

Properties:

* hasBiasType: Connects "Halo Effect" to "Celebrity Bias."
* targetsDomain: Connects "Halo Effect" to "Environmental Advocacy."
* isInfluencedBy: Connects "Halo Effect" to "Public Statements."



**Example 2: Product Review Bias Scenario**

Class Instances:

* Instance of CognitiveBias: "Halo Effect"
* Instance of BiasType: "Product Review Bias"
* Instance of TargetDomain: "Product Expertise"
* Instance of InfluencingFactor: "Positive User Experience"

Properties:

* hasBiasType: Connects "Halo Effect" to "Product Review Bias."
* targetsDomain: Connects "Halo Effect" to "Product Expertise."
* isInfluencedBy: Connects "Halo Effect" to "Positive User Experience."



**Example 3: Academic Achievement Bias Scenario**

Class Instances:

* Instance of CognitiveBias: "Halo Effect"
* Instance of BiasType: "Academic Achievement Bias"
* Instance of TargetDomain: "General Intelligence"
* Instance of InfluencingFactor: "High Grades"

Properties:

* hasBiasType: Connects "Halo Effect" to "Academic Achievement Bias."
* targetsDomain: Connects "Halo Effect" to "General Intelligence."
* isInfluencedBy: Connects "Halo Effect" to "High Grades."



These examples demonstrate how the defined ontology can be instantiated in different scenarios, such as celebrity admiration, product reviews, or academic achievement, capturing the relationships between classes and properties.

***

## 3. Frame Semantic Triggers

_<mark style="color:green;">Words as Frame Semantic Triggers</mark>_

To better synchronize the biases with established semantic frames in Framester, we use knowledge extraction tools like [QUOKKA's Concepts Extractor Tool](http://etna.istc.cnr.it/quokka/concepts) and [FRED](http://wit.istc.cnr.it/stlab-tools/fred/demo/).

### 3.1. Starting Lexical Material (SLM),

_<mark style="color:green;">Choosing these Lexical Units, then extracted concepts in QUOKKA's and FRED</mark>_

* celebrity
* audience
* perspective
* judgement

### 3.2 Selected Framester F**rames**:

_<mark style="color:green;">Finally, these are the best Framester Frames can be chosen</mark>_

[Fame](http://etna.istc.cnr.it/framester2/data/framestercore/Fame)

stringAn Entity is well-known among a wide range of people (in general or in a particular domain) for a particular Reason, which may be a behavior, characteristic, or some other associated item. In the case of events, fame entails a large number of people being aware of the event's occurence; in the case of concrete entities, including humans, fame entails awareness of existence. In both cases, often fame is accompanied by awareness of the Entity's significance in historical, cultural, or social contexts. Shakespeare was famous during his life because he performed in front of Queen Elizabeth I more than anyone else.

[People](https://w3id.org/framester/data/framestercore/People)

This frame contains general words for Individuals, i.e. humans. The Person is conceived of as independent of other specific individuals with whom they have relationships and independent of their participation in any particular activity. They may have an Age, Descriptor, Origin, Persistent\_characteristic, or Ethnicity. A man from Phoenix was shot yesterday. She gave birth to a screaming babyyesterday. I study 16-year-old female adolescents. I am dating an African-American man. She comforted the terrified child. I always thought of him as a stupid man.

[Cogitation](https://w3id.org/framester/data/framestercore/Cogitation)

A person, the Cognizer, thinks about a Topic over a period of time. What is thought about may be a course of action that the person might take, or something more general. The men were silently mulling over the proposition of committing an assassination. Visualisation the model of Positivity Effect

### 3.3 Creating the bias ontology file:

_<mark style="color:green;">In the last step, we create the bias ontology in the Protege and also a Graph of it</mark>_

{% hint style="success" %}
[Positivity Effect OWL file](../../cognitive-biases/Cluster1-FamiliarsBetterThanUnfamiliars/PositivityEffect.owl)
{% endhint %}

{% embed url="https://service.tib.eu/webvowl/#iri=https://raw.githubusercontent.com/Maedeam/KRKE-cognitive-biases/modeling-cognitive-biases/cognitive-biases/Cluster1-FamiliarsBetterThanUnfamiliars/PositivityEffect.owl" %}
Visualisation the model of Positivity Effect
{% endembed %}

## 4. Selected Content Ontology Design Patterns

[**AgentRole**](http://ontologydesignpatterns.org/wiki/Submissions:AgentRole)

To represent agents and the roles they play.

**Reusable OWL Building Block:** [http://www.ontologydesignpatterns.org/cp/owl/agentrole.owl](http://www.ontologydesignpatterns.org/cp/owl/agentrole.owl)

[**Sequence**](http://ontologydesignpatterns.org/wiki/Submissions:Sequence)

To represent sequence schemas. It defines the notion of transitive and intransitive precedence and their inverses.

It can then be used between tasks, processes, time intervals, spatially locate objects, situations, etc.

**Reusable OWL Building Block:** [http://ontologydesignpatterns.org/cp/owl/sequence.ow](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler\&link=http://ontologydesignpatterns.org/cp/owl/sequence.owl\&message=OWL%20building%20block\&from\_page\_id=756\&update=)[l](http://ontologydesignpatterns.org/cp/owl/sequence.owl)

[**AffectedBy**](http://ontologydesignpatterns.org/wiki/Submissions:AffectedBy)

To represent properties/qualities that may affect the status of a feature of interest.

**Reusable OWL Building Block:** [https://w3id.org/affectedBy](https://w3id.org/affectedBy)\


