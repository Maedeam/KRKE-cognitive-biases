---
description: Ontology page for "Prejudice Bias"
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

# ⚡ Prejudice Bias

## 1. Literature Review&#x20;

_<mark style="color:green;">Background, Context and Literature State of the Art</mark>_&#x20;

### Wikipedia&#x20;

Prejudice bias is a [Cognitive Bias](https://en.wikipedia.org/wiki/Cognitive\_bias) which can be an affective feeling towards a person based on their perceived group membership. The word is often used to refer to a preconceived (usually unfavourable) evaluation or classification of another person based on that person's perceived personal characteristics, such as political affiliation, sex, gender, gender identity, beliefs, values, social class, age, disability, religion, sexuality, race, ethnicity, language, nationality, culture, complexion, beauty, height, body weight, occupation, wealth, education, criminality, sport-team affiliation, music tastes or other perceived characteristics.

The word "prejudice" can also refer to unfounded or pigeonholed beliefs and it may apply to "any unreasonable attitude that is unusually resistant to rational influence".Gordon Allport defined prejudice as a "feeling, favorable or unfavorable, toward a person or thing, prior to, or not based on, actual experience".Auestad (2015) defines prejudice as characterized by "symbolic transfer", transfer of a value-laden meaning content onto a socially-formed category and then on to individuals who are taken to belong to that category, resistance to change, and overgeneralization.

[Wikipedia Link](https://en.wikipedia.org/wiki/Prejudice)

### Research Paper(s)

\[1] Tajfel, Henri (2001). Social stereotypes and social groups. In M. A. Hogg & D. Abrams (Eds.), _Key readings in social psychology. Intergroup relations: Essential readings_ (p. 132–145). Psychology Press.

\[2] Allport, Gordon (1954). _The nature of prejudice_. Addison-Wesley.

\[3] Fiske, Susan T., Amy J. Cuddy, Peter Glick & Jun Xu (2002). A model of (often mixed) stereotype content: competence and warmth respectively follow from perceived status and competition. _Journal of personality and social psychology, 82_(6), 878.

\[4] Fiske, Susan T. & Shelley E. Taylor (1984) _Social cognition_. Random House.

\[5] Spencer, Steven J., Christine Logel & Paul G. Davies (2016). Stereotype threat. _Annual Review of Psychology, 67_(1) : 415-437.

***

## 2. LLMs

_<mark style="color:green;">Large Language Models</mark>_

### 2.1. General Description

_<mark style="color:green;">A general description of the bias to get an overall idea of the domain</mark>_

Prejudice refers to a preconceived and unjust judgment or opinion formed about an individual or a group based on their perceived characteristics, such as race, ethnicity, gender, religion, or other distinguishing attributes. It involves making assumptions about others without considering individual differences or evaluating them on their own merits. Prejudice often stems from ingrained stereotypes, cultural biases, or ignorance, and can lead to discriminatory behavior and unfair treatment. Overcoming prejudice requires fostering understanding, promoting empathy, and challenging stereotypes to build a more inclusive and tolerant society.

### 2.2. Examples Scenarios

_<mark style="color:green;">Ten different examples of possible scenarios to understanding the context of the domain</mark>_

1. **Racial Profiling:** A person of a particular race being unfairly targeted by law enforcement solely based on their racial background, rather than any evidence of wrongdoing.
2. **Gender Discrimination in the Workplace:** Women facing prejudice in hiring, promotions, or pay solely due to their gender, disregarding their qualifications or capabilities.
3. **Religious Prejudice:** Discrimination against individuals or groups based on their religious beliefs, manifesting in exclusion, bias, or hostility.
4. **Stereotyping in Education:** Students being treated differently or underestimated by teachers based on stereotypes related to their cultural background, socioeconomic status, or gender.
5. **Ageism in Employment:** Older individuals encountering prejudice in the job market due to stereotypes about their age, leading to discriminatory hiring practices.
6. **Homophobia and Transphobia:** Individuals facing prejudice and discrimination based on their sexual orientation or gender identity, resulting in exclusion, harassment, or denial of rights.
7. **Class-Based Prejudice:** Discrimination against people from lower socioeconomic backgrounds, affecting their access to opportunities, education, and healthcare.
8. **Disability Discrimination:** Prejudice against individuals with disabilities, resulting in unequal treatment, exclusion, or the denial of accommodations.
9. **Nationality-Based Bias:** People experiencing prejudice based on their nationality, leading to stereotypes, discrimination, or xenophobia.
10. **Appearance-based Discrimination:** Prejudice directed at individuals due to their physical appearance, such as weight, height, or other superficial attributes, affecting how they are perceived and treated in various contexts.

### 2.3 Main Scenario

_<mark style="color:green;">Considering one scenario; here the</mark> <mark style="color:green;"></mark><mark style="color:green;">**Appearance-based Discrimination,**</mark> <mark style="color:green;"></mark><mark style="color:green;">as our main user story</mark>_

**User Story:** Sarah, a highly qualified professional, applied for a managerial position in a reputable company. Despite her impressive resume and relevant experience, she encountered appearance-based discrimination during the interview process. The hiring manager, influenced by biased perceptions, focused more on Sarah's physical appearance than her qualifications. Subtle comments about her clothing, hairstyle, and body shape were made, overshadowing her competence and expertise. Consequently, Sarah felt **marginalized** and unfairly judged, as the interview focused more on **superficial** aspects rather than her ability to contribute to the company. This experience highlighted the detrimental effects of appearance-based **discrimination** in professional settings, emphasizing the need for fair and objective evaluation based on skills and qualifications.

### 2.4. Possible CQs

_<mark style="color:green;">Generating some possible competency questions</mark>_

1. **AgentRole CQs:**

Question: Which agent does play the role of evaluating job candidates in the user story? And what is the role that is played by that agent?

Answer: The agent in this scenario is the hiring manager. The role played by the hiring manager is to assess and select suitable candidates for the managerial position within the company.

2. **Sequence CQs:**

Question: In the user story, what is before the appearance-based discrimination incident, and what immediately follows it during the interview process?

Answer: Before the appearance-based discrimination incident, the user, Sarah, applied for a managerial position. Immediately following the incident, the hiring manager continued to focus on superficial aspects, overshadowing Sarah's qualifications during the interview.

3. **Situation CQs:**

Question:  What is the context or situation surrounding the appearance-based discrimination in the user story, and what are the things present in this context or situation?

Answer: The context is a job interview for a managerial position in a reputable company. The situation involves the hiring manager making biased comments about Sarah's physical appearance, including her clothing, hairstyle, and body shape. The elements present in this context include Sarah's qualifications, the interview process, and the impact of appearance-based discrimination on fair evaluation.

### 2.5. Modelling Bias

_<mark style="color:green;">For making an Ontology and modelling the bias, we can create these classes and properties</mark>_

**Class: Prejudice**

Comment: The central class encompassing all forms of preconceived and unjust judgments or opinions.

**Class: Agent**

Comment: A class representing individuals or entities involved in the perpetuation or experience of prejudice.

**Class: Situation**

Comment: A class representing the context or circumstances in which prejudice manifests.

**Class: Marginalization**

Comment: A subclass under Prejudice, representing instances where individuals or groups are pushed to the sidelines or excluded unfairly.

Property: involvesAgent (Domain: Marginalization, Range: Agent)

Property: occursIn (Domain: Marginalization, Range: Situation)

**Class: Discrimination**

Comment: A subclass under Prejudice, focusing on biased treatment or unfair actions against individuals or groups.

**Property: involvesAgent (Domain: Discrimination, Range: Agent)**

**Property: occursIn (Domain: Discrimination, Range: Situation)**

**Class: Superficiality**

Comment: A subclass under Prejudice, highlighting instances where judgments are made based on surface-level attributes rather than meaningful qualities.

**Property: involvesAgent (Domain: Superficiality, Range: Agent)**

**Property: occursIn (Domain: Superficiality, Range: Situation)**

**Property: involvesAgent**

Domain: Prejudice

Range: Agent

Comment: Describes the agent or individual involved in perpetuating or experiencing prejudice.

**Property: occursIn**

Domain: Prejudice

Range: Situation

Comment: Describes the situations or contexts in which instances of prejudice occur.

### 2.6. Examples Ontology

_<mark style="color:green;">Three different examples of usage of the Ontology</mark>_

**Example 1: Marginalization in a Job Interview Situation**

Instance: MarginalizationX (an instance of Marginalization)

Instance: Interviewer1 (an instance of Agent)

Instance: JobInterviewX (an instance of JobInterviewSituation)

Property Usage: involvesAgent(MarginalizationX, Interviewer1)

Property Usage: occursIn(MarginalizationX, JobInterviewX)

Comment: In this example, MarginalizationX is an instance of the Marginalization class involving the agent Interviewer1 in a specific situation, JobInterviewX.

**Example 2: Discrimination in a Workplace Situation**

Instance: DiscriminationY (an instance of Discrimination)

Instance: ManagerA (an instance of Agent)

Instance: WorkplaceZ (an instance of WorkplaceSituation)

Property Usage: involvesAgent(DiscriminationY, ManagerA)

Property Usage: occursIn(DiscriminationY, WorkplaceZ

Comment: In this example, DiscriminationY is an instance of the Discrimination class involving the agent ManagerA in a specific situation, WorkplaceZ.

**Example 3: Superficiality in a Social Event Situation**

Instance: SuperficialityZ (an instance of Superficiality)

Instance: PeerB (an instance of Agent)

Instance: SocialEventY (an instance of SocialEventSituation)

Property Usage: involvesAgent(SuperficialityZ, PeerB)

Property Usage: occursIn(SuperficialityZ, SocialEventY)

Comment: In this example, SuperficialityZ is an instance of the Superficiality class involving the agent PeerB in a specific situation, SocialEventY.

***

## 3. Frame Semantic Triggers

_<mark style="color:green;">Words as Frame Semantic Triggers</mark>_

To better synchronize the biases with established semantic frames in Framester, we use knowledge extraction tools like [QUOKKA's Concepts Extractor Tool](http://etna.istc.cnr.it/quokka/concepts) and [FRED](http://wit.istc.cnr.it/stlab-tools/fred/demo/).

### 3.1. Starting Lexical Material (SLM),

_<mark style="color:green;">Choosing these Lexical Units, then extracted concepts in QUOKKA's and FRED</mark>_

* Marginalized
* Discrimination
* Superficial

### 3.2 Selected Framester F**rames**:

_<mark style="color:green;">Finally, these are the best Framester Frames can be chosen</mark>_



### 3.3 Creating the bias ontology file:

_<mark style="color:green;">In the last step, we create the bias ontology in the Protege and also a Graph of it</mark>_

{% hint style="success" %}
[Prejudice Bias OWL file](../../cognitive-biases/Cluster2-DiscardSpecificsFormGeneralities/PrejudiceBias.owl)
{% endhint %}

{% embed url="https://service.tib.eu/webvowl/#iri=https://raw.githubusercontent.com/Maedeam/KRKE-cognitive-biases/modeling-cognitive-biases/cognitive-biases/Cluster2-DiscardSpecificsFormGeneralities/PrejudiceBias.owl" %}
Visualisation the model of Prejudice Bias
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


