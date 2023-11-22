---
description: Ontology page for "Implicit Associations Bias"
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

# ⚡ Implicit Associations Bias

## 1. Literature Review&#x20;

_<mark style="color:green;">Background, Context and Literature State of the Art</mark>_&#x20;

### Wikipedia&#x20;

The implicit-association test (IAT) is an assessment intended to detect subconscious associations between mental representations of objects (concepts) in memory. Its best-known application is the assessment of implicit stereotypes held by test subjects, such as associations between particular racial categories and stereotypes about those groups. The test has been applied to a variety of belief associations, such as those involving racial groups, gender, sexuality, age, and religion but also the self-esteem, political views, and predictions of the test taker. The implicit-association test is the subject of significant academic and popular debate regarding its validity, reliability, and usefulness in assessing implicit bias which is a [Cognitive Bias](https://en.wikipedia.org/wiki/Cognitive\_bias).

[Wikipedia Link](https://en.wikipedia.org/wiki/Implicit-association\_test)

### Research Paper(s)

\[1] [Project Implicit – take the test](https://implicit.harvard.edu/implicit/)

\[2] [IAT Review chapter in _Implicit measures of attitudes: Procedures and controversies_ (seven years after IAT creation)](http://faculty.washington.edu/agg/pdf/Lane%20et%20al.UUIAT4.2007.pdf)

\[3] [IAT Review chapter in _Zeitschrift für Experimentelle Psychologie_ (three years after IAT creation)](http://faculty.washington.edu/agg/pdf/Gwald\_Nosek\_ZEITSCHR\_2001.OCR.pdf)

\[4] [Discussion of IAT critiques in American Psychological Association article](http://www.apa.org/monitor/2008/07-08/psychometric.aspx)

\[5] [Further Readings on Unconscious Bias](http://tierneylab.blogs.nytimes.com/2008/11/17/further-reading-on-unconscious-bias/) from John Tierney New York Times column on [Bias of Bias test](https://www.nytimes.com/2008/11/18/science/18tier.html)

***

## 2. LLMs

_<mark style="color:green;">Large Language Models</mark>_

### 2.1. General Description

_<mark style="color:green;">A general description of the bias to get an overall idea of the domain</mark>_

Implicit Associations Bias refers to the subconscious attitudes and associations individuals hold towards certain groups or concepts, often formed through societal influences and personal experiences. These biases are implicit, meaning they operate at an unconscious level and can influence judgments and behavior unintentionally. Implicit Associations Bias can manifest in various forms, such as racial, gender, or age-related biases, and may affect decision-making processes despite an individual's conscious efforts to remain unbiased. Recognizing and addressing these implicit biases is crucial for promoting fairness, inclusivity, and equality in various social contexts.

### 2.2. Examples Scenarios

_<mark style="color:green;">Ten different examples of possible scenarios to understanding the context of the domain</mark>_

1. **Job Interview Bias:** An interviewer may unconsciously favor a candidate from the same ethnic background, even though they believe they are making an unbiased decision based on qualifications.
2. **Gendered Task Assignments:** In a workplace, a manager might subconsciously assign certain tasks based on traditional gender roles, even when skills and abilities are equal among team members.
3. **Student Achievement Expectations:** Teachers might unknowingly have different expectations for students of different races, impacting grading and feedback.
4. **Shopping Stereotypes:** Retail employees may unconsciously follow or monitor customers of a particular ethnicity, associating them with shoplifting.
5. **Healthcare Disparities:** Medical professionals might unintentionally provide different levels of care to patients based on their racial or socioeconomic background.
6. **Leadership Perception:** Individuals might perceive a person of a certain age as less capable of leadership, even if their experience and skills suggest otherwise.
7. **Media Portrayals Impact:** Unconscious biases can influence media portrayals, reinforcing stereotypes and shaping public perception of different social groups.
8. **Legal System Disparities:** Judges and jurors might unknowingly treat defendants differently based on factors like race or socioeconomic status, impacting legal outcomes.
9. **Networking Bias:** People may gravitate toward networking with individuals who share similar backgrounds, unintentionally excluding others and reinforcing existing biases.
10. **Teacher Expectations:** Educators might unconsciously expect less academic success from students with certain names or from specific neighborhoods, affecting their support and encouragement.

### 2.3 Main Scenario

_<mark style="color:green;">Considering one scenario; here the</mark> <mark style="color:green;"></mark><mark style="color:green;">**Networking Bias**</mark><mark style="color:green;">, as our main user story</mark>_

**User Story: Networking Bias**

As a professional attending a networking event, I want to connect with diverse individuals to broaden my professional network and gain different perspectives. However, due to implicit biases, I find myself naturally gravitating towards people who share similar backgrounds or interests. To address this, I wish for a feature in the networking event app that suggests connections based on a diverse range of criteria such as industry experience, skills, and interests, helping me break free from unconscious biases and fostering a more inclusive professional network.

### 2.4. Possible CQs

_<mark style="color:green;">Generating some possible competency questions</mark>_

**AgentRole Competency Questions:**

1. Who is the primary agent in the scenario described?
2. What role does the professional play in the networking event?
3. Are there any secondary agents involved, and what roles do they play in the networking event?

**Sequence Competency Questions:**

1. What happens first in the user story when attending the networking event?
2. What follows the initial action of connecting with diverse individuals?
3. What is the immediate next step after identifying the need to broaden the professional network?

**Situation Competency Questions:**

1. What is the context or setting of the user story?
2. Are there specific criteria considered in the scenario for suggesting connections?
3. What elements contribute to the unconscious biases in the networking scenario?

### 2.5. Modelling Bias

_<mark style="color:green;">For making an Ontology and modelling the bias, we can create these classes and properties</mark>_

**Classes:**

1. **ImplicitAssociationsBias:** The overarching class representing the concept of implicit associations bias.
   * _Subclass_: ImplicitAssociationsCategory (represents specific categories of associations).
2. **ImplicitAssociationsCategory:** Represents specific categories or domains for which implicit associations bias may occur.
   * _Subclasses_: GenderAssociation, RaceAssociation, AgeAssociation, etc. (representing different types of associations).
3. **Person:** Represents individuals affected by or exhibiting implicit associations bias.

**Object Properties:**

1. **exhibitsAssociationsBias:** Relates a person to the specific type of implicit associations bias exhibited.
   * _Domain_: Person
   * _Range_: ImplicitAssociationsCategory
2. **isAffectedBy:** Represents the influence of external factors on implicit associations bias.
   * _Domain_: ImplicitAssociationsBias
   * _Range_: SocialContext
3. **hasAssociationStrength:** Quantifies the strength of the implicit association.
   * _Domain_: ImplicitAssociationsCategory
   * _Range_: Data type property for numerical values.

**Data Properties:**

1. **hasBiasIntensity:** Represents the intensity or strength of the bias exhibited by a person.
   * _Domain_: Person
   * _Range_: Data type property for numerical values.

**Individuals:**

1. **GenderAssociation:** An instance representing implicit associations bias related to gender.
2. **RaceAssociation:** An instance representing implicit associations bias related to race.
3. **John:** An individual person affected by implicit associations bias.
4. **SocialContext:** An instance representing the broader societal or cultural context influencing implicit associations bias.

### 2.6. Examples Ontology

_<mark style="color:green;">Three different examples of usage of the Ontology</mark>_

1. **Example 1: Recording Implicit Associations Bias**
   * **Scenario:** John, a participant in a study, exhibits implicit associations bias related to gender.
   * **Usage:**
     * _Individual:_ John (Person)
     * _Association Type:_ GenderAssociation (ImplicitAssociationsCategory)
     * _Property:_ exhibitsAssociationsBias
     * _Assertion:_ John exhibits gender-related implicit associations bias.
2. **Example 2: Quantifying Bias Intensity**
   * **Scenario:** A research study aims to quantify the intensity of implicit associations bias in various participants.
   * **Usage:**
     * _Property:_ hasBiasIntensity
     * _Assertion:_ GenderAssociation hasBiasIntensity "0.75" (indicating a strong gender-related implicit associations bias).
3. **Example 3: Understanding Social Context Influence**
   * **Scenario:** Analyzing implicit associations bias in a cultural context.
   * **Usage:**
     * _Individual:_ SocialContext
     * _Property:_ isAffectedBy
     * _Assertion:_ GenderAssociation isAffectedBy SocialContext (indicating that the intensity of gender-related bias is influenced by the cultural context).

***

## 3. Frame Semantic Triggers

_<mark style="color:green;">Words as Frame Semantic Triggers</mark>_

To better synchronize the biases with established semantic frames in Framester, we use knowledge extraction tools like [QUOKKA's Concepts Extractor Tool](http://etna.istc.cnr.it/quokka/concepts) and [FRED](http://wit.istc.cnr.it/stlab-tools/fred/demo/).

### 3.1. Starting Lexical Material (SLM),

_<mark style="color:green;">Choosing these Lexical Units, then extracted concepts in QUOKKA's and FRED</mark>_

* **ImplicitAssociationsBias:** This term represents the overarching concept of implicit associations bias.
* **AssociationsCategory:** Refers to a category or type of associations, such as those related to gender or race.
* **BiasIntensity:** Represents the strength or intensity of implicit bias, often quantifiable on a scale.
* **SocialContext:** Describes the broader societal or cultural context that can influence implicit associations bias.
* **ExhibitsAssociationsBias:** Denotes an action or behavior of exhibiting implicit associations bias, often associated with individuals.

### 3.3 Creating the bias ontology file:

_<mark style="color:green;">In the last step, we create the bias ontology in the Protege and also a Graph of it</mark>_

{% hint style="success" %}
[Implicit Associations Bias OWL file](../../cognitive-biases/Cluster2-DiscardSpecificsFormGeneralities/ImplicitAssociations.owl)
{% endhint %}

{% embed url="https://service.tib.eu/webvowl/#iri=https://raw.githubusercontent.com/Maedeam/KRKE-cognitive-biases/modeling-cognitive-biases/cognitive-biases/Cluster2-DiscardSpecificsFormGeneralities/ImplicitAssociations.owl" %}
Visualisation the model of Implicit Associations Bias
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


