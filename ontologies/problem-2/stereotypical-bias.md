---
description: Ontology page for "Stereotypical Bias"
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

# ⚡ Stereotypical Bias

## 1. Literature Review&#x20;

_<mark style="color:green;">Background, Context and Literature State of the Art</mark>_&#x20;

### Wikipedia&#x20;

Stereotypical bias is a [Cognitive Bias](https://en.wikipedia.org/wiki/Cognitive\_bias) which is shortly, memory distorted towards stereotypes (e.g., racial or gender). It's a part of Misattribution of memory bias.

[Wikipedia Link](https://en.wikipedia.org/wiki/Misattribution\_of\_memory)

### Research Paper(s)

\[1] Tajfel, Henri (2001). Social stereotypes and social groups. In M. A. Hogg & D. Abrams (Eds.), Key readings in social psychology. Intergroup relations: Essential readings (p. 132–145). Psychology Press.

\[2] Allport, Gordon (1954). The nature of prejudice. Addison-Wesley.

\[3] Fiske, Susan T., Amy J. Cuddy, Peter Glick & Jun Xu (2002). A model of (often mixed) stereotype content: competence and warmth respectively follow from perceived status and competition. Journal of personality and social psychology, 82(6), 878.

\[4] Fiske, Susan T. & Shelley E. Taylor (1984) Social cognition. Random House.

\[5] Spencer, Steven J., Christine Logel & Paul G. Davies (2016). Stereotype threat. Annual Review of Psychology, 67(1) : 415-437.

***

## 2. LLMs

_<mark style="color:green;">Large Language Models</mark>_

### 2.1. General Description

_<mark style="color:green;">A general description of the bias to get an overall idea of the domain</mark>_

Stereotypical bias, also known as stereotyping, refers to the cognitive inclination to generalize and apply predefined characteristics or traits to individuals based on their membership in a particular social group. This bias often stems from preconceived notions, cultural expectations, or widely held beliefs about specific groups, leading individuals to make assumptions about others without considering their unique qualities or individual differences. Stereotypical bias can influence perceptions, decisions, and interactions, contributing to the perpetuation of social stereotypes and potentially resulting in unfair judgments or discriminatory behaviors.

### 2.2. Examples Scenarios

_<mark style="color:green;">Ten different examples of possible scenarios to understanding the context of the domain</mark>_

1. **Job Interview:** Assuming a candidate's technical abilities are weak because of their gender, despite evidence to the contrary.
2. **Age Discrimination:** Believing that older individuals are not adept with technology simply due to their age.
3. **Ethnic Cuisine:** Assuming someone is an expert in a specific cuisine solely based on their ethnic background.
4. **Sports Proficiency:** Presuming that individuals from a certain country excel at a particular sport based on stereotypes.
5. **Fashion Choices:** Associating specific clothing styles with personality traits, disregarding individual preferences.
6. **Educational Background:** Assuming a person's intelligence based on the prestige of their alma mater.
7. **Language Proficiency:** Believing someone is not fluent in a language based on their accent or ethnic background.
8. **Parental Roles:** Expecting individuals to conform to traditional gender roles in parenting without considering their capabilities.
9. **Financial Status:** Assuming someone's financial situation based on their occupation or neighborhood.
10. **Disability Perceptions:** Stereotyping individuals with disabilities as being dependent or incapable in various aspects of life.

### 2.3 Main Scenario

_<mark style="color:green;">Considering one scenario; here the Fashion Choices, as our main user story</mark>_

**User Story: Unveiling Stereotypical Bias in Fashion**

_User:_ Emily, a fashion enthusiast with a unique and eclectic style.

_Objective:_ As Emily, I want to challenge the stereotype that associates specific personality traits with particular fashion choices, aiming to foster a more inclusive understanding of individual styles.

_Scenario:_ Emily, known for her diverse and unconventional fashion sense, attends a social gathering where she encounters curious glances and hears whispers suggesting that her eclectic wardrobe indicates a rebellious or non-conformist personality. Determined to address this stereotypical bias, Emily engages in conversations with attendees, sharing stories behind her fashion choices and emphasizing the importance of expressing oneself authentically. Through these interactions, Emily aims to dismantle preconceived notions about personality traits linked to fashion and inspire a more open-minded perspective among her peers.

_Desired Outcome:_ Emily hopes that, by challenging the stereotypical bias associated with her fashion choices, she can encourage others to embrace diverse styles without attaching predetermined judgments about individual personalities.

### 2.4. Possible CQs

_<mark style="color:green;">Generating some possible competency questions</mark>_

**AgentRole CQs:**

1. **Which agent is central to this scenario?**
   * Agent: Emily
2. **What role is Emily playing in the story?**
   * Role: Fashion Enthusiast and Advocate for Style Individuality

**Sequence CQs:**

1. **What happens before Emily attends the social gathering?**
   * Preceding Event: Emily's decision to attend the social gathering.
2. **What's next after Emily encounters curious glances and whispers?**
   * Subsequent Event: Emily engages in conversations with attendees to address stereotypical biases.
3. **What is immediately following Emily's interactions with her peers?**
   * Following Event: Emily hopes to inspire a more open-minded perspective among her peers.

**Situation CQs:**

1. **What is the context or situation where Emily challenges stereotypical biases?**
   * Context: Social gathering where Emily's fashion choices spark curiosity and whispers.
2. **What are the things present in this context or situation?**
   * Elements: Attendees, Emily's eclectic wardrobe, whispers, and social interactions.

### 2.5. Modelling Bias

_<mark style="color:green;">For making an Ontology and modelling the bias, we can create these classes and properties</mark>_

**Classes:**

1. **Person:**
   * Represents individuals in the context of stereotypical bias.
2. **Attribute:**
   * Represents characteristics or traits that are subject to stereotyping.
3. **StereotypicalBias:**
   * Represents the overarching concept of stereotypical bias.

**Object Properties:**

1. **hasAttribute:**
   * Relates a person to an attribute that is subject to stereotyping.
2. **exhibitsBiasTowards:**
   * Represents the bias exhibited by individuals toward others based on stereotypical attributes.
3. **challengesBias:**
   * Represents actions or behaviors that challenge or confront stereotypical biases.

**Individuals:**

1. **John:**
   * An individual person.
2. **FashionableAttribute:**
   * An attribute related to fashion choices.
3. **StereotypicalBiasExample:**
   * An instance representing a specific case of stereotypical bias.

**Domain and Range:**

1. **hasAttribute:**
   * _Domain:_ Person
   * _Range:_ Attribute
2. **exhibitsBiasTowards:**
   * _Domain:_ Person
   * _Range:_ StereotypicalBias
3. **challengesBias:**
   * _Domain:_ Person
   * _Range:_ StereotypicalBias

This ontology structure provides a foundation for representing individuals, stereotypical attributes, and the relationships between them. It allows for modeling instances where individuals exhibit biases based on stereotypical attributes and actions taken to challenge or confront such biases. Adjustments and additional details can be made based on specific use cases or requirements.

### 2.6. Examples Ontology

_<mark style="color:green;">Three different examples of usage of the Ontology</mark>_

1. **Example 1: Fashion Stereotype**
   * **Individuals:**
     * Person: John
     * Attribute: FashionableAttribute
   * **Object Properties:**
     * John hasAttribute FashionableAttribute
     * John exhibitsBiasTowards StereotypicalBiasExample
   * **Scenario:**
     * John, known for his fashionable choices, is stereotypically biased against for being perceived as less serious at work due to fashion stereotypes. The ontology captures this by linking John to the attribute "FashionableAttribute" and showing that he exhibits bias towards the stereotype.
2. **Example 2: Challenge to Bias**
   * **Individuals:**
     * Person: Sarah
   * **Object Properties:**
     * Sarah challengesBias StereotypicalBiasExample
   * **Scenario:**
     * Sarah actively challenges a stereotypical bias against women in leadership roles by participating in initiatives and advocating for equal opportunities. The ontology represents this by linking Sarah to the action of challenging the stereotype.
3. **Example 3: General Stereotypical Bias**
   * **Individuals:**
     * StereotypicalBiasExample
   * **Object Properties:**
     * StereotypicalBiasExample hasAttribute FashionableAttribute
   * **Scenario:**
     * This represents a generic instance of stereotypical bias, where a person is stereotyped based on being fashionable. The ontology captures this by associating the stereotypical bias example with the attribute "FashionableAttribute."

***

## 3. Frame Semantic Triggers

_<mark style="color:green;">Words as Frame Semantic Triggers</mark>_

To better synchronize the biases with established semantic frames in Framester, we use knowledge extraction tools like [QUOKKA's Concepts Extractor Tool](http://etna.istc.cnr.it/quokka/concepts) and [FRED](http://wit.istc.cnr.it/stlab-tools/fred/demo/).

### 3.1. Starting Lexical Material (SLM),

_<mark style="color:green;">Choosing these Lexical Units, then extracted concepts in QUOKKA's and FRED</mark>_

* **FashionableAttribute:** An attribute representing a person's inclination towards stylish and trendy clothing.
* **ChallengesBias:** An action or behavior that involves actively questioning or resisting stereotypical biases.
* **StereotypicalBiasExample:** A generic instance representing a scenario where a person is subjected to stereotyping based on certain characteristics or attributes.
* **EqualOpportunitiesAdvocate:** An individual who actively supports and promotes equal opportunities, especially in contexts where stereotypical biases may exist.
* **PerceivedAsLessSerious:** A state where a person is viewed or judged as lacking seriousness or professionalism based on certain stereotypes.

### 3.2 Selected Framester F**rames**:

_<mark style="color:green;">Finally, these are the best Framester Frames can be chosen</mark>_

[Differentiation](https://w3id.org/framester/data/framestercore/Differentiation)

Words in this frame have to do with a Cognizer being aware (or not being aware) of the difference between two Phenomena, which may be expressed jointly or disjointly. It is very difficult for people to visually distinguish between living and non-living things from such a great distance .

[Attribute](http://en.wiktionary.org/wiki/attribute)

An "attribute" is a characteristic or quality that describes a particular object, entity, or phenomenon. Attributes provide information about the properties, features, or traits associated with an element, helping to define and distinguish it within a given context. In data modeling and programming, attributes are often used to represent specific data elements or fields that contribute to the overall description of an entity, such as the color of an object, the age of a person, or the size of a file. Attributes play a crucial role in organizing and categorizing information, facilitating the understanding and analysis of the properties inherent to different entities.

[CauseChange](http://etna.istc.cnr.it/framester2/data/framestercore/CauseChange)

An Agent or Cause causes an Entity to change, either in its category membership or in terms of the value of an Attribute. In the former case, an Initial\_category and a Final\_category may be expressed, in the latter case an Initial\_value and a Final\_value can be specified. Our storylines follows the saga outlined by the Ultima Series, but we have modified it in order to make our writing more cohesive. I don't think you can turn that rabbit into a hat. How can a guy that changed his name from Bob Craft to Jack Ass declare anyone defamed his character? At this juncture, a new development changed the political situation on the island. She had at some time earlier completely changed her clothing and appearance and now stood in front of me dressed like a garden gnome. Hence, when (Hg 0 ) is converted to Hg 2+ , it can be rapidly taken up in rain water, snow, or adsorbed onto small particles Hence, when (Hg 0 ) is converted to Hg 2+ , it can be rapidly taken up in rain water, snow, or adsorbed onto small particles

### 3.3 Creating the bias ontology file:

_<mark style="color:green;">In the last step, we create the bias ontology in the Protege and also a Graph of it</mark>_

{% hint style="success" %}
[Stereotypical Bias OWL file](../../cognitive-biases/Cluster2-DiscardSpecificsFormGeneralities/StereotypicalBias.owl)
{% endhint %}

{% embed url="https://service.tib.eu/webvowl/#iri=https://raw.githubusercontent.com/Maedeam/KRKE-cognitive-biases/modeling-cognitive-biases/cognitive-biases/Cluster2-DiscardSpecificsFormGeneralities/StereotypicalBias.owl" %}
Visualisation the model of Stereotypical Bias
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


