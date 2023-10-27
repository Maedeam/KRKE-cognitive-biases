---
description: Ontology page for "Halo effect"
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

# ⚡ Halo effect

Halo effect OWL file

Diagram for the ontology of Halo effect

## 1. Literature Review&#x20;

_<mark style="color:green;">Background, Context and Literature State of the Art</mark>_&#x20;

### Wikipedia:&#x20;

The Halo effect (sometimes called the halo error) is the tendency for positive impressions of a person, company, country, brand, or product in one area to positively or negatively influence one's opinion or feelings in other areas.

The Halo effect is "the name given to the phenomenon whereby evaluators tend to be influenced by their previous judgments of performance or personality."

The halo effect is a cognitive bias which can possibly prevent someone from accepting a person, a product or a brand based on the idea of an unfounded belief on what is good or bad.

The term was coined by Edward Thorndike. A simplified example of the halo effect is a person, after noticing that an individual in a photograph is attractive, well groomed, and properly attired, then assuming, using a mental heuristic, that the person in the photograph is a good person based upon the rules of their own social concept.

This constant error in judgement is reflective of the individual's preferences, prejudices, ideology, aspirations, and social perception.

[Wikipedia Link](https://en.wikipedia.org/wiki/Halo\_effect)

### Research Paper(s):

xxx

***

## 2. LLMs

_<mark style="color:green;">Large Language Models</mark>_

### 2.1. General Description

_<mark style="color:green;">A general description of the bias to get an overall idea of the domain</mark>_

The "Halo Effect" is a cognitive bias where individuals tend to form a favorable overall impression of a person, product, or entity based on a single positive trait, experience, or characteristic, which then radiates, or creates a "halo," leading to the presumption that other unrelated aspects or qualities must also be positive. This bias can cloud judgment and decision-making, as it assumes that excellence in one area equates to excellence in others, often resulting in overly positive evaluations and potentially biased assessments.

### 2.2. Examples Scenarios

_<mark style="color:green;">Ten different examples of possible scenarios to understanding the context of the domain</mark>_

1. Job Interview: An applicant for a job position is an excellent athlete, leading the interviewer to assume they are equally competent in their professional skills.
2. Celebrity Admiration: Fans assume that a beloved actor's expertise in film extends to topics like politics and nutrition, demonstrating the "Halo Effect" where excellence in one area leads to broader credibility.
3. Expert Opinion: A well-respected scientist expresses their views on climate change, and the public automatically trusts their advice on unrelated scientific matters, such as medical research.
4. Attractive Politician: A politician is considered physically attractive, and voters assume they are more capable and honest in their political decisions.
5. Popular Teacher: A teacher who is liked by many students for their sense of humor is believed to be an excellent educator in all subjects, even those outside their expertise.
6. Company Reputation: A tech company is known for creating innovative software, leading consumers to believe that their hardware products must also be of high quality.
7. Nobel Laureate: A Nobel Prize winner in physics is asked for their opinion on a complex political issue, and many assume their expertise extends to political matters.
8. Philanthropic Act: A wealthy philanthropist donates a substantial amount to a charitable cause, and people assume they must be morally superior in all aspects of life.
9. Celebrity Chef: A famous chef prepares a delightful dish on a cooking show, and viewers assume they are equally skilled in other culinary styles or unrelated fields.
10. Sports Star: A renowned athlete endorses a brand of energy drinks, and consumers believe that drinking the product will make them as physically fit and skilled as the athlete.

### 2.3 - Main Scenario

_<mark style="color:green;">Considering one scenario, here the</mark> <mark style="color:green;"></mark><mark style="color:green;">**Celebrity Admiration,**</mark> <mark style="color:green;"></mark><mark style="color:green;">as our main user story and generate competency questions from that</mark>_

User Story: Understanding Celebrity Admiration and the Halo Effect

User: Sarah, an avid fan of a well-known actor, Alex.

Objective: As Sarah, I want to recognize and overcome the "Halo Effect" related to my admiration for Alex, the actor, to make more informed judgments about the actor's expertise in areas outside of acting.

Scenario: Sarah has always been a fan of Alex for their outstanding acting skills. She has followed Alex's career closely and admires their performances in various movies and television series. Recently, Alex made public statements about environmental conservation, advocating for sustainable practices. Sarah found herself wholeheartedly supporting Alex's stance on the environment, assuming that someone so talented in acting must also be highly knowledgeable about ecological matters.

Desired Outcome: Sarah recognizes that her admiration for Alex in the realm of acting may have led to a cognitive bias, the "Halo Effect," influencing her perception of Alex's expertise in unrelated fields. She aims to evaluate environmental matters and other subjects independently from her admiration for the actor, ensuring a more balanced and informed approach to the causes and topics she supports.

### 2.4. Possible CQs

_<mark style="color:green;">Generating some possible competency questions</mark>_

Now we derive Three different possible CQs from the user story:

* CQ1: What factors contribute to the "Halo Effect" in celebrity admiration?
* CQ2: How can individuals recognize and mitigate the "Halo Effect" in their judgments?
* CQ3: What are the implications of the "Halo Effect" on public support for various causes and topics?

### 2.5. Modelling Bias

_<mark style="color:green;">For making an Ontology and modelling the bias, we can create these classes and properties</mark>_

**Classes:**

1. **CognitiveBias:** Represents various types of cognitive biases, including the "Halo Effect." This class serves as a superclass for specific types of biases.
2. **BiasType:** Represents different categories of cognitive biases that generalize traits or attributes to specific individuals, like the "Halo Effect."
3. **HaloEffectBias:** Instances of biases related to the "Halo Effect" where individuals tend to form a favorable overall impression of a person based on a single positive trait.
4. **Individual:** Represents individuals, such as Sarah and Alex, who are subject to the "Halo Effect."
5. **Trait:** Represents specific traits or characteristics, for example, Alex's acting skills and environmental advocacy.
6. **AreaOfExpertise:** Represents different fields of expertise, for example, acting and environmental conservation.

**Properties:**

1. **hasBiasType:** Connects an Individual to its corresponding BiasType instance, indicating the type of cognitive bias involved (e.g., "HaloEffectBias").
2. **hasTrait:** Connects an Individual to their specific traits or characteristics. For example, it connects Sarah to her admiration for Alex's acting skills and his environmental advocacy.
3. **isKnownFor:** Connects an Individual to their areas of expertise or fields they are known for. For example, it connects Alex to his expertise in acting and environmental conservation.
4. **hasOpinion:** Connects an Individual to their opinions and beliefs. In this case, it would connect Sarah to her support for Alex's environmental stance.
5. **isInfluencedBy:** Connects an Individual to entities, such as celebrities or influencers, that influence their opinions and beliefs. This could connect Sarah to her influence by Alex's performances.

These classes and properties should provide a foundation for representing the "Halo Effect" and how it relates to individuals and their areas of expertise. You can further expand or customize this ontology based on your specific requirements and use cases.

### 2.6. Examples Ontology

_<mark style="color:green;">Three different examples of usage of the Ontology</mark>_

**Example 1: Identifying Cognitive Bias**

* **Instance:** Sarah
* **Scenario:** Sarah, as a fan of Alex, supports his stance on environmental conservation due to her admiration for his acting skills.
* **Usage:** We can create an instance of the `EssentialismBias` class representing the "Halo Effect" cognitive bias. This instance links to `Sarah` as the observer and `Alex` as the target actor. The `hasBiasType` property connects it to the specific `BiasType` representing the "Halo Effect."

**Example 2: Analyzing Influence**

* **Instance:** Alex
* **Scenario:** Alex's celebrity status and acting skills influence Sarah's perception of his expertise in environmental matters.
* **Usage:** We can create an instance of the `Influence` class to represent the influence that Alex has on Sarah. The `hasName` property can be used to assign a name or label to this influence, such as "Celebrity Influence." This can help analyze how social or cultural influences affect cognitive biases.

**Example 3: Recognizing Cognitive Bias Impact**

* **Instance:** Sarah
* **Scenario:** Sarah recognizes that her admiration for Alex may have led to the "Halo Effect" bias influencing her perception.
* **Usage:** We can create an instance of the `CognitiveBias` class with the `EssentialismBias` subclass that represents the "Halo Effect." This instance links to `Sarah` as the individual experiencing the bias. Additionally, the `isAttributedToGroup` property can be used to associate traits or attributes with specific groups to better understand the impact of biases on group interactions.

These examples demonstrate how the ontology's classes and properties can be applied to capture and analyze instances related to the "Halo Effect" and its influence on individuals like Sarah.

***

## 3. Frame Semantic Triggers

_<mark style="color:green;">Words as Frame Semantic Triggers</mark>_

To further align the biases with existing semantic frames in Framester, we leverage powerful knowledge extraction tools like QUOKKA's "Concepts Extractor" and FRED.

In QUOKKA, we extracted concepts from the following lexical units:

* 1
* 2
* 3

We cross our results with the ones obtained in FRED by putting the following scenario:

**Celebrity Admiration:** Fans assume that a beloved actor's expertise in film extends to topics like politics and nutrition, demonstrating the "Halo Effect" where excellence in one area leads to broader credibility.



