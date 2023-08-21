---
cover: .gitbook/assets/360_F_409077589_hmbAZgBuVFqfspRclw8ya2xG8IW9y4oV.jpeg
coverY: 0
---

# 🔤 Glossary

### Frame Semantics

Frame semantics is a theory of linguistic meaning developed by Charles J. Fillmore that extends his earlier case grammar. It relates linguistic semantics to encyclopedic knowledge. The basic idea is that one cannot understand the meaning of a single word without access to all the essential knowledge that relates to that word. For example, one would not be able to understand the word "sell" without knowing anything about the situation of commercial transfer, which also involves, among other things, a seller, a buyer, goods, money, the relation between the money and the goods, the relations between the seller and the goods and the money, the relation between the buyer and the goods and the money and so on. Thus, a word activates, or evokes, a frame of semantic knowledge relating to the specific concept to which it refers (or highlights, in frame semantic terminology).

### Frame

Frames are an artificial intelligence data structure used to divide knowledge into substructures by representing "stereotyped situations". They were proposed by Marvin Minsky in his 1974 article "A Framework for Representing Knowledge". Frames are the primary data structure used in artificial intelligence frame languages; they are stored as ontologies of sets.

Frames are also an extensive part of knowledge representation and reasoning schemes. They were originally derived from semantic networks and are therefore part of structure-based knowledge representations. According to Russell and Norvig's "Artificial Intelligence: A Modern Approach", structural representations assemble "\[...]facts about particular objects and event types and arrange the types into a large taxonomic hierarchy analogous to a biological taxonomy".

### Lexical unit

Lexical units (LU) are lemmas, with their part of speech, that evoke a specific frame. In other words, when an LU is identified in a sentence, that specific LU can be associated with its specific frame(s). For each frame, there may be many LUs associated to that frame, and also there may be many frames that share a specific LU, this is typically the case with LUs that have multiple word senses. Alongside the frame, each lexical unit is associated with specific frame elements by means of the annotated example sentences.

_Example:_

_Lexical units that evoke the `Complaining` frame (or more specific perspectivized versions of it, to be precise), include the verbs "complain", "grouse", "lament", and others._

### Ontology Design Pattern (ODP)

An OP is a modelling solution to solve a recurrent ontology design problem. It is a template that represents a schema for specific design solutions. An ODP consists of a set of “prototypical” ontology entities that constitute the “abstract form” of a pattern, and of a set of metadata about its use cases, motivations, provenance, the pros and cons of its application, the links to other patterns, etc. Design solutions based on ODPs encode ontology entities that apply, specialize, or instantiate the prototypical entities defined by the schema.

### Content Ontology Design Pattern (CP)

CPs are distinguished networked ontologies and have their own namespace. They cover a speciﬁc set of competency questions (requirements), which represent the problem they provide a solution for. Furthermore, CPs show certain characteristics, i.e. they are: computational, small, autonomous, hierarchical, cognitively relevant, linguistically relevant, and best practices.

They show the following characteristics: CPs encode conceptual, rather than logical design patterns. In other words, while Logical OPs solve design problems independently of a particular conceptualization, CPs propose patterns for solving design problems for the domain classes and properties that populate an ontology, therefore addressing content problems. CPs are instantiations of Logical OPs (or of compositions of Logical OPs), featuring a non-empty signature. Hence, they have an explicit non-logical vocabulary for a specific domain of interest (i.e. they are content-dependent). CPs provide solutions to domain modeling problems and affect only the specific region of the ontology dealing with such domain modeling problems. They are typically reused by applying specialization, extension, and composition to them. In principle, CPs do not depend on any specific language, however in order to reuse them as building blocks, they have to be implemented in some way. In the portal _ontologydesignpatterns.org_ we mainly deal with CPs in a Semantic Web context, hence we currently support OWL as a reference formalism for representation.

### Web Ontology Language (OWL)

Old OWL is based on description logic, a semantic fragment of first order logic, called SHOIN(D). OWL 2 is based on SROIQ(D) (extention of the old description logic). From now on we will refer to OWL 2

An OWL Ontology consists of: classes / properties / individual (instances of classes). Is based on an Open World Assumption - the absence of information must not be valued as negative information - and No Unique Name Assumption - difference must be expressed explicitly.

### OWL Syntax Variants

OWL2 can be represented in different Syntax variants:

* Functional Syntax: substitutes abstract syntax of OWL1
* RDF/XML-Syntax: extension of existing OWL/RDF (for legacy reasons)
* OWL/XML-Syntax: indipendent XML serialisation
* Manchester-Syntax: machine readable syntax, especially used for ontology editors
* Turtle: concise and easy readable

### Open World Reasoning

In Open World Assumption the existence of further individuals is possible, if they are not explicitly excluded. The biggest single hurdle to understanding OWL and Description Logics is the use of Open World Reasoning. Almost certainly, all systems that newcomers to OWL will have encountered previously use closed world reasoning with “negation as failure” – i.e. if something cannot be found, it is assumed to be absent, e.g. databases, logic programming, constraint languages in frame systems, etc. By contrast, OWL uses open world reasoning with negation as unsatisfiability - i.e. something is false only if it can be proved to contradict other information in the ontology.
