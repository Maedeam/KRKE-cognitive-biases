---
description: Ontology page for "Implicit Stereotypes Bias"
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

# ⚡ Implicit Stereotypes Bias

## 1. Literature Review&#x20;

_<mark style="color:green;">Background, Context and Literature State of the Art</mark>_&#x20;

### Wikipedia&#x20;

An implicit bias or implicit stereotype is a [Cognitive Bias](https://en.wikipedia.org/wiki/Cognitive\_bias) which is the pre-reflective attribution of particular qualities by an individual to a member of some social out group. Implicit stereotypes are thought to be shaped by experience and based on learned associations between particular qualities and social categories, including race and/or gender. Individuals' perceptions and behaviors can be influenced by the implicit stereotypes they hold, even if they are sometimes unaware they hold such stereotypes. Implicit bias is an aspect of implicit social cognition: the phenomenon that perceptions, attitudes, and stereotypes can operate prior to conscious intention or endorsement. The existence of implicit bias is supported by a variety of scientific articles in psychological literature. Implicit biases, however, are thought to be the product of associations learned through past experiences. Implicit biases can be activated by the environment and operate prior to a person's intentional, conscious endorsement. Implicit bias can persist even when an individual rejects the bias explicitly.

[Wikipedia Link](https://en.wikipedia.org/wiki/Implicit\_stereotype)

### Research Paper(s)

\[1] [Project implicit](https://implicit.harvard.edu/) Take Implicit Association Tests to reveal your own implicit attitudes and stereotypes, as well as contribute to the research as a participant.

\[2] [Are We All Unconscious Racists? No: there’s scant evidence to support the trendy implicit-bias theory](https://www.city-journal.org/html/are-we-all-unconscious-racists-15487.html). [Heather Mac Donald](https://en.wikipedia.org/wiki/Heather\_Mac\_Donald) in [_City Journal_](https://en.wikipedia.org/wiki/City\_Journal\_\(New\_York\_City\)).

\[3] Li Chen, Shuyu Zeng, Rui He; [Negative Emotions Can Interfere with the Inhibitory Effect of Proactive Control on Implicit Stereotypes](https://doi.org/10.5281/zenodo.4675801) North American Academic Research, 4(4)53-69, April 2021

***

## 2. LLMs

_<mark style="color:green;">Large Language Models</mark>_

### 2.1. General Description

_<mark style="color:green;">A general description of the bias to get an overall idea of the domain</mark>_

Implicit Stereotype Bias refers to the unconscious and automatic associations or attitudes individuals hold toward certain groups or categories, influencing their judgments and behavior without conscious awareness. These biases are often deeply ingrained in societal norms and cultural contexts, shaping perceptions based on characteristics such as gender, race, or ethnicity. Implicit stereotypes can affect decision-making processes, interactions, and evaluations, even when individuals consciously reject or oppose such biases. Recognizing and addressing implicit stereotype bias is crucial for promoting fairness, inclusivity, and equitable treatment in various social settings.

### 2.2. Examples Scenarios

_<mark style="color:green;">Ten different examples of possible scenarios to understanding the context of the domain</mark>_

1. **Hiring Decisions:** An employer unconsciously favors a candidate from their own cultural background, despite qualifications being equal, due to implicit stereotypes about work habits associated with that culture.
2. **Classroom Dynamics:** A teacher may inadvertently provide more attention and opportunities for participation to students of a certain gender, influenced by implicit stereotypes about academic abilities.
3. **Medical Treatment:** A healthcare provider might make assumptions about a patient's pain tolerance based on their ethnicity, leading to disparities in pain management.
4. **Leadership Perceptions:** Individuals may unconsciously associate leadership qualities with specific gender traits, impacting promotion decisions and perpetuating gender-based stereotypes.
5. **Consumer Preferences:** A marketing team might unintentionally create ads that align with racial or cultural stereotypes, influencing product appeal in a way that reinforces biases.
6. **Criminal Justice:** Law enforcement officers might subconsciously associate certain demographics with criminal behavior, affecting their approach during stops or investigations.
7. **Performance Evaluations:** Managers might rate employees differently based on implicit assumptions about age, leading to biased performance assessments.
8. **Educational Opportunities:** Implicit stereotypes can influence recommendations for advanced courses, limiting opportunities for students from underrepresented backgrounds.
9. **Media Portrayals:** Stereotypical representations in media can reinforce implicit biases, affecting how individuals perceive and interact with people from different backgrounds.
10. **Networking Events:** Individuals may unconsciously gravitate towards those who share similar backgrounds at networking events, limiting the diversity of their professional connections due to implicit biases.

### 2.3 Main Scenario

_<mark style="color:green;">Considering one scenario; here the Hiring Decisions, as our main user story</mark>_

**User Story: Hiring Decisions**

As a hiring manager for a tech company, I want to ensure fair and unbiased recruitment processes to build a diverse and talented team. During the screening of resumes, I notice that I have a preference for candidates with names that sound familiar or culturally similar to mine. Recognizing the potential for implicit stereotypes to influence my decisions, I decide to implement blind recruitment practices. By removing personally identifiable information from resumes, such as names and photos, I aim to focus solely on the skills and qualifications of each candidate. This user story reflects the commitment to addressing implicit biases in hiring decisions and promoting a more inclusive workplace.

### 2.4. Possible CQs

_<mark style="color:green;">Generating some possible competency questions</mark>_

**AgentRole Competency Questions:**

1. Which agent is responsible for the hiring decisions in this scenario?
2. What role does the hiring manager play in the recruitment process?
3. Are there any other agents involved in the decision-making process, and what roles do they play?

**Sequence Competency Questions:**

1. What precedes the decision to implement blind recruitment practices in the hiring process?
2. What steps are taken immediately after the hiring manager recognizes a potential preference for culturally familiar names?
3. What follows the implementation of blind recruitment practices to ensure fair and unbiased hiring?

**Situation Competency Questions:**

1. What is the context or situation that triggers the hiring manager's decision to address implicit biases?
2. Are there external factors influencing the need for diverse hiring practices in the tech company?
3. What elements are present in the recruitment process context that contribute to the recognition of potential biases?

### 2.5. Modelling Bias

_<mark style="color:green;">For making an Ontology and modelling the bias, we can create these classes and properties</mark>_

**Classes:**

1. **ImplicitStereotypeBias:**
   * Represents the overarching concept of implicit stereotypes bias.
2. **Person:**
   * Represents individuals affected by implicit stereotypes bias.
3. **Attribute:**
   * Represents characteristics or traits that are subject to stereotyping.
4. **SocialContext:**
   * Represents the broader societal or cultural context influencing implicit stereotypes bias.

#### Properties:

1. **exhibitsBiasTowards:**
   * Domain: Person
   * Range: ImplicitStereotypeBias
   * Represents the bias exhibited by individuals toward others based on implicit stereotypes.
2. **hasAttribute:**
   * Domain: Person
   * Range: Attribute
   * Relates a person to an attribute that is subject to stereotyping.
3. **isAffectedBy:**
   * Domain: ImplicitStereotypeBias
   * Range: SocialContext
   * Represents the influence of social context on implicit stereotypes bias.

#### Individuals:

1. **StereotypeChallengeEvent:**
   * Type: ImplicitStereotypeBias
   * Represents an event challenging or confronting implicit stereotypes bias.
2. **John:**
   * Type: Person
   * Individuals affected by implicit stereotypes bias.
3. **GenderAttribute:**
   * Type: Attribute
   * Represents an attribute related to gender that may be subject to stereotyping.

### 2.6. Examples Ontology

_<mark style="color:green;">Three different examples of usage of the Ontology</mark>_

1. **Example 1: Stereotype Challenge Workshop**
   * **Context:**
     * A workshop is organized to challenge and address implicit stereotypes in a workplace.
   * **Usage:**
     * Individuals attending the workshop (e.g., employees) are instances of the class "Person."
     * The workshop event itself is an instance of the class "ImplicitStereotypeBias."
     * The property "exhibitsBiasTowards" is used to link individuals (e.g., John) to specific attributes (e.g., GenderAttribute) that are subject to stereotyping.
     * The property "isAffectedBy" links the workshop event to the broader societal or cultural context (e.g., SocialContext).
2. **Example 2: Implicit Gender Bias Study**
   * **Context:**
     * A research study is conducted to investigate implicit gender biases in decision-making.
   * **Usage:**
     * Participants in the study are instances of the class "Person."
     * The study itself is an instance of the class "ImplicitStereotypeBias."
     * The property "exhibitsBiasTowards" is used to link participants to attributes (e.g., GenderAttribute) under investigation.
     * The property "isAffectedBy" connects the study to the broader social context influencing implicit stereotypes.
3. **Example 3: Online Diversity Training Program**
   * **Context:**
     * An online diversity training program aims to address and reduce implicit stereotypes in a virtual learning environment.
   * **Usage:**
     * Participants enrolled in the training program are instances of the class "Person."
     * The training program event is an instance of the class "ImplicitStereotypeBias."
     * The property "exhibitsBiasTowards" is used to link participants to specific attributes targeted in the training (e.g., RaceAttribute).
     * The property "isAffectedBy" establishes the link between the training program and the broader social context.

***

## 3. Frame Semantic Triggers

_<mark style="color:green;">Words as Frame Semantic Triggers</mark>_

To better synchronize the biases with established semantic frames in Framester, we use knowledge extraction tools like [QUOKKA's Concepts Extractor Tool](http://etna.istc.cnr.it/quokka/concepts) and [FRED](http://wit.istc.cnr.it/stlab-tools/fred/demo/).

### 3.1. Starting Lexical Material (SLM),

_<mark style="color:green;">Choosing these Lexical Units, then extracted concepts in QUOKKA's and FRED</mark>_

* ImplicitStereotypesBias
* StereotypeChallenge
* WorkplaceDiversity
* DecisionMakingBias
* AwarenessTraining

### 3.3 Creating the bias ontology file:

_<mark style="color:green;">In the last step, we create the bias ontology in the Protege and also a Graph of it</mark>_

{% hint style="success" %}
[Implicit Stereotypes Bias OWL file](../../cognitive-biases/Cluster2-DiscardSpecificsFormGeneralities/ImplicitStereotypes.owl)
{% endhint %}

{% embed url="https://service.tib.eu/webvowl/#iri=https://raw.githubusercontent.com/Maedeam/KRKE-cognitive-biases/modeling-cognitive-biases/cognitive-biases/Cluster2-DiscardSpecificsFormGeneralities/ImplicitStereotypes.owl" %}
Visualisation the model of Implicit Stereotypes Bias
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


