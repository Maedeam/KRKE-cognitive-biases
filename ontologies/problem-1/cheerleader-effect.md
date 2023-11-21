---
description: Ontology page for "Cheerleader Effect"
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

# ⚡ Cheerleader Effect

## 1. Literature Review&#x20;

_<mark style="color:green;">Background, Context and Literature State of the Art</mark>_&#x20;

### Wikipedia&#x20;

The cheerleader effect, is a [Cognitive Bias](https://en.wikipedia.org/wiki/Cognitive\_bias) which is also known as the group attractiveness effect or the friend effect, is a proposed cognitive bias which causes people to perceive individuals as 1.5–2.0% more attractive in a group than when seen alone.The first paper to report this effect was written by Drew Walker and Edward Vul, in 2014.

[Wikipedia Link](https://en.wikipedia.org/wiki/Cheerleader\_effect)

### Research Paper(s)

\[1] _May, Cindi (December 3, 2013)._ [_"The Cheerleader Effect"_](http://www.scientificamerican.com/article/the-cheerleader-effect/)_._ [_Scientific American_](https://en.wikipedia.org/wiki/Scientific\_American)_. Retrieved December 5, 2015._ Article on Walker and Vul's 2013 study.

***

## 2. LLMs

_<mark style="color:green;">Large Language Models</mark>_

### 2.1. General Description

_<mark style="color:green;">A general description of the bias to get an overall idea of the domain</mark>_

The "Cheerleader Effect" also known as the "Group Attractiveness Effect," refers to a cognitive bias in social perception where individuals tend to appear more attractive when seen as part of a group rather than in isolation. Coined by the character Barney Stinson on the television show "How I Met Your Mother," the concept suggests that people tend to be perceived as more appealing when viewed within the context of a group, such as a team or a social gathering. This phenomenon may be attributed to the averaging of facial features within a group, resulting in a more favorable and harmonious overall impression. Essentially, the Cheerleader Effect highlights the influence of social context on our perception of attractiveness, revealing the intriguing ways in which our minds interpret and evaluate individuals based on their surroundings.

From a psychological standpoint, the Cheerleader Effect can be linked to various cognitive mechanisms, including the Gestalt principles of perception, which emphasize how our brains tend to organize visual elements into a cohesive whole. When people are viewed collectively, the brain may process and blend their features, smoothing out individual idiosyncrasies and creating a more aesthetically pleasing composite image. This bias can impact social dynamics and decision-making, as individuals may be more positively evaluated and considered more attractive when surrounded by others. Understanding the Cheerleader Effect provides insights into the complex interplay between social context and our perceptions of attractiveness, shedding light on the ways our minds navigate the intricacies of human interaction and visual processing.

### 2.2. Examples Scenarios

_<mark style="color:green;">Ten different examples of possible scenarios to understanding the context of the domain</mark>_

1. **Group Photos at Parties:** Individuals in group photos taken at social events may appear more attractive collectively than when viewed individually, contributing to the Cheerleader Effect.
2. **Team Sports:** Athletes on a sports team might be perceived as more appealing when seen together on the field, with the shared uniform and coordinated movements enhancing their attractiveness.
3. **Professional Networking Events:** Attendees at business conferences or networking events might benefit from the Cheerleader Effect, as the collective environment enhances the perceived attractiveness of individuals in professional settings.
4. **Wedding Parties:** Bridesmaids and groomsmen, dressed uniformly and standing together, may benefit from the Cheerleader Effect, creating an impression of heightened attractiveness.
5. **Musical Performances:** Band members on stage may be individually less attractive, but the synergy of their performance and shared presence could enhance their overall appeal.
6. **Dance Ensembles:** Dancers in a group may experience the Cheerleader Effect, with synchronized movements and costumes contributing to a more favorable perception of their attractiveness.
7. **Workplace Teams:** Colleagues working closely on a project or within a team may collectively benefit from the Cheerleader Effect, appearing more attractive when collaborating in a professional context.
8. **Family Gatherings:** Family members in a group photo during holidays or special occasions may experience the Cheerleader Effect, where the shared genetic features contribute to an overall perception of attractiveness.
9. **Fashion Shows:** Models walking the runway as part of a collection may individually have distinct features, but when presented together, they can collectively benefit from the Cheerleader Effect.
10. **Social Media Group Shots:** Individuals posting group photos on social media platforms may receive more positive responses and be perceived as more attractive due to the Cheerleader Effect, as the context of friendship and camaraderie enhances their appeal.

### 2.3 Main Scenario

_<mark style="color:green;">Considering one scenario; here the</mark> <mark style="color:green;"></mark><mark style="color:green;">**Social Media Influence,**</mark> <mark style="color:green;"></mark><mark style="color:green;">as our main user story</mark>_

As a dedicated _**soccer player**_, Emily felt a surge of _**excitement**_ as she and her _**teammates**_ gathered on the field for their _**championship game**_. Eagerly donning their team uniforms, they exuded a sense of _**unity**_ and camaraderie that had been cultivated through weeks of rigorous training. As they positioned themselves for the group photo before the match, Emily couldn't help but marvel at how everyone looked more attractive together.

Later, when Emily's friend posted the team photo on social media, the _**comments**_ poured in, praising the team's collective charisma and spirit. Emily's individual features seemed to blend seamlessly with her teammates', creating a _**visual synergy**_ that made each player more _**appealing**_ than they might have appeared in solo snapshots. The shared victory on the field and the captured moment in the group photo not only celebrated the team's success but also highlighted the Cheerleader Effect, leaving Emily with a sense of _**pride**_ in both her individual contributions and the collective _**magnetism**_ of her soccer team.

### 2.4. Possible CQs

_<mark style="color:green;">Generating some possible competency questions</mark>_

1. **AgentRole CQs:**

_**Question:**_ Who played the role of the dedicated soccer player in the championship game?

_**Answer:**_ Emily played the role of the dedicated soccer player in the championship game.

2. **Sequence CQs:**

_**Question:**_ What happened immediately after the team gathered on the field for the championship game?

_**Answer:**_ Immediately after gathering on the field, the team positioned themselves for a group photo before the championship game.

3. **Situation CQs:**

_**Question:**_ What was the context or situation in which positive comments poured in on social media?

_**Answer:**_ The positive comments poured in on social media when Emily's friend posted the team photo, celebrating the collective charisma and spirit of the soccer team.

### 2.5. Modelling Bias

_<mark style="color:green;">For making an Ontology and modelling the bias, we can create these classes and properties</mark>_

**Classes:**

\- Phenomenon

&#x20; \- Comment: Represents the phenomenon of collective attractiveness of individuals in a group.

\- Person

&#x20; \- Subclass Of: Phenomenon

&#x20; \- Comment: Represents an individual.

\- Team

&#x20; \- Subclass Of: Phenomenon

&#x20; \- Comment: Represents a team.

\- Event

&#x20; \- Subclass Of: Phenomenon

&#x20; \- Comment: Represents an event.

\- SocialMediaPost

&#x20; \- Subclass Of: Phenomenon

&#x20; \- Comment: Represents a social media post.

**Object Properties:**

\- belongsToTeam

&#x20; \- Domain: Person

&#x20; \- Range: Team

&#x20; \- Comment: Relates a person to a team.

\- participatedInEvent

&#x20; \- Domain: Person

&#x20; \- Range: Event

&#x20; \- Comment: Relates a person to an event.

\- hasTeammates

&#x20; \- Domain: Team

&#x20; \- Range: Person

&#x20; \- Comment: Relates a team to its members (Persons).

\- participatedInEvent

&#x20; \- Domain: Team

&#x20; \- Range: Event

&#x20; \- Comment: Relates a team to an event.

\- capturedInPhoto

&#x20; \- Domain: Person

&#x20; \- Range: SocialMediaPost

&#x20; \- Comment: Relates a person or a team to a social media post.

**Datatype Properties:**

\- hasExcitementLevel

&#x20; \- Domain: Person

&#x20; \- Range: String

&#x20; \- Comment: Represents the excitement level of an individual.

\- hasPrideLevel

&#x20; \- Domain: Person

&#x20; \- Range: String

&#x20; \- Comment: Represents the pride level of an individual.

\- hasUnity

&#x20; \- Domain: Team

&#x20; \- Range: String

&#x20; \- Comment: Represents the sense of unity within a team.

\- hasVisualSynergy

&#x20; \- Domain: Event

&#x20; \- Range: String

&#x20; \- Comment: Represents the visual synergy associated with an event.

\- hasComments

&#x20; \- Domain: SocialMediaPost

&#x20; \- Range: String

&#x20; \- Comment: Represents the comments on a social media post.

\- hasMagnetism

&#x20; \- Domain: SocialMediaPost

&#x20; \- Range: String

&#x20; \- Comment: Represents the perceived magnetism of a social media post.

**Individuals:**

\- SoccerPlayer

&#x20; \- Type: Person

&#x20; \- belongsToTeam: SoccerTeam

&#x20; \- participatedInEvent: ChampionshipGame

\- Teammate1

&#x20; \- Type: Person

&#x20; \- belongsToTeam: SoccerTeam

&#x20; \- participatedInEvent: ChampionshipGame

\- SoccerTeam

&#x20; \- Type: Team

&#x20; \- hasTeammates: SoccerPlayer

&#x20; \- participatedInEvent: ChampionshipGame

\- ChampionshipGame

&#x20; \- Type: Event

\- TeamPhotoPost

&#x20; \- Type: SocialMediaPost

&#x20; \- capturedInPhoto: Soccerteam

### 2.6. Examples Ontology

_<mark style="color:green;">Three different examples of usage of the Ontology</mark>_

**Example 1: Emily's Participation in a Championship Game**

Individuals Involved:

Emily (Person)

SoccerTeam (Team)

ChampionshipGame (Event)

Properties Utilized:

Emily participatesInEvent ChampionshipGame

Emily belongsToTeam SoccerTeam

SoccerTeam hasTeammates \[List of individual Persons]

ChampionshipGame hasVisualSynergy High

This example demonstrates how Emily, as an individual, is associated with both the SoccerTeam and the ChampionshipGame. The visual synergy of the championship game is captured through the "hasVisualSynergy" property, emphasizing the collective appeal of the event.

**Example 2 : Social Media Post Capturing Team's Magnetism**

Individuals Involved:

TeamPhoto (SocialMediaPost)

SoccerTeam (Team)

Properties Utilized:

TeamPhoto capturedInPhoto SoccerTeam

TeamPhoto hasMagnetism High

TeamPhoto hasComments \[List of comments]

In this example, the social media post (TeamPhoto) captures the collective magnetism of the SoccerTeam. The "hasMagnetism" property is used to indicate the perceived attractiveness of the post, and the "hasComments" property includes a list of comments associated with the post.

**Example 3 : Analyzing Team Unity and Player Excitement**

Individuals Involved:

SoccerTeam (Team)

Emily (Person)

Properties Utilized:

SoccerTeam hasUnity Strong

Emily hasExcitementLevel High

Emily belongsToTeam SoccerTeam

This example focuses on analyzing the unity of the SoccerTeam, represented by the "hasUnity" property with a value of "Strong." Additionally, Emily's excitement level is captured through the "hasExcitementLevel" property, emphasizing the individual emotional aspect within the team context.

***

## 3. Frame Semantic Triggers

_<mark style="color:green;">Words as Frame Semantic Triggers</mark>_

To better synchronize the biases with established semantic frames in Framester, we use knowledge extraction tools like [QUOKKA's Concepts Extractor Tool](http://etna.istc.cnr.it/quokka/concepts) and [FRED](http://wit.istc.cnr.it/stlab-tools/fred/demo/).

### 3.1. Starting Lexical Material (SLM),

_<mark style="color:green;">Choosing these Lexical Units, then extracted concepts in QUOKKA's and FRED</mark>_

* Team Sports: Soccer player,Championship game,Teammates,Unity
* Collective Charisma: Visual synergy,Appealing
* Positive Feedback on Social Media: Comments , Magnetism
* Personal Experience: Excitement , Pride

### 3.2 Selected Framester F**rames**:

_<mark style="color:green;">Finally, these are the best Framester Frames can be chosen</mark>_

[Fame](http://etna.istc.cnr.it/framester2/data/framestercore/Fame)

stringAn Entity is well-known among a wide range of people (in general or in a particular domain) for a particular Reason, which may be a behavior, characteristic, or some other associated item. In the case of events, fame entails a large number of people being aware of the event's occurence; in the case of concrete entities, including humans, fame entails awareness of existence. In both cases, often fame is accompanied by awareness of the Entity's significance in historical, cultural, or social contexts. Shakespeare was famous during his life because he performed in front of Queen Elizabeth I more than anyone else.

[People](https://w3id.org/framester/data/framestercore/People)

This frame contains general words for Individuals, i.e. humans. The Person is conceived of as independent of other specific individuals with whom they have relationships and independent of their participation in any particular activity. They may have an Age, Descriptor, Origin, Persistent\_characteristic, or Ethnicity. A man from Phoenix was shot yesterday. She gave birth to a screaming babyyesterday. I study 16-year-old female adolescents. I am dating an African-American man. She comforted the terrified child. I always thought of him as a stupid man.

[Cogitation](https://w3id.org/framester/data/framestercore/Cogitation)

A person, the Cognizer, thinks about a Topic over a period of time. What is thought about may be a course of action that the person might take, or something more general. The men were silently mulling over the proposition of committing an assassination.

### 3.3 Creating the bias ontology file:

_<mark style="color:green;">In the last step, we create the bias ontology in the Protege and also a Graph of it</mark>_

{% hint style="success" %}
[Cheerleader Effect OWL file](../../cognitive-biases/Cluster1-FamiliarsBetterThanUnfamiliars/CheerleaderEffect.owl)
{% endhint %}

{% embed url="https://service.tib.eu/webvowl/#iri=https://raw.githubusercontent.com/Maedeam/KRKE-cognitive-biases/modeling-cognitive-biases/cognitive-biases/Cluster1-FamiliarsBetterThanUnfamiliars/CheerleaderEffect.owl" %}
Visualisation the model of Cheerleader Effect
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


