---
cover: .gitbook/assets/360_F_409077589_hmbAZgBuVFqfspRclw8ya2xG8IW9y4oV.jpeg
coverY: 0
---

# 🔤 Glossary

### Axiom

An axiom, postulate, or assumption is a statement that is taken to be true, to serve as a premise or starting point for further reasoning and arguments. The word comes from the Ancient Greek word ἀξίωμα (axíōma), meaning 'that which is thought worthy or fit' or 'that which commends itself as evident'.

The precise definition varies across fields of study. In classic philosophy, an axiom is a statement that is so evident or well-established, that it is accepted without controversy or question.In modern logic, an axiom is a premise or starting point for reasoning.

In mathematics, an axiom may be a "logical axiom" or a "non-logical axiom". Logical axioms are taken to be true within the system of logic they define and are often shown in symbolic form (e.g., (A and B) implies A), while non-logical axioms (e.g., a + b = b + a) are substantive assertions about the elements of the domain of a specific mathematical theory, such as arithmetic.

Non-logical axioms may also be called "postulates" or "assumptions". In most cases, a non-logical axiom is simply a formal logical expression used in deduction to build a mathematical theory, and might or might not be self-evident in nature (e.g., the parallel postulate in Euclidean geometry). To axiomatize a system of knowledge is to show that its claims can be derived from a small, well-understood set of sentences (the axioms), and there are typically many ways to axiomatize a given mathematical domain.

Any axiom is a statement that serves as a starting point from which other statements are logically derived. Whether it is meaningful (and, if so, what it means) for an axiom to be "true" is a subject of debate in the philosophy of mathematics.

In onotology design axioms are assertions (including rules) in a logical form that together comprise the overall theory that the ontology describes in its domain of application. This definition differs from that of "axioms" in generative grammar and formal logic. In these disciplines, axioms include only statements asserted as a priori knowledge. As used here, "axioms" also include the theory derived from axiomatic statements.

In an OWL 2 ontology a set of axioms — statements that say what is true in the domain - is the main component. OWL 2 provides an extensive set of axioms, all of which extend the Axiom class in the structural specification. Axioms in OWL 2 can be declarations, axioms about classes, axioms about object or data properties, datatype definitions, keys, assertions (sometimes also called facts), and axioms about annotations.

### Frame Semantics

Frame semantics is a theory of linguistic meaning developed by Charles J. Fillmore that extends his earlier case grammar. It relates linguistic semantics to encyclopedic knowledge. The basic idea is that one cannot understand the meaning of a single word without access to all the essential knowledge that relates to that word. For example, one would not be able to understand the word "sell" without knowing anything about the situation of commercial transfer, which also involves, among other things, a seller, a buyer, goods, money, the relation between the money and the goods, the relations between the seller and the goods and the money, the relation between the buyer and the goods and the money and so on. Thus, a word activates, or evokes, a frame of semantic knowledge relating to the specific concept to which it refers (or highlights, in frame semantic terminology).

### Frame

Frames are an artificial intelligence data structure used to divide knowledge into substructures by representing "stereotyped situations". They were proposed by Marvin Minsky in his 1974 article "A Framework for Representing Knowledge". Frames are the primary data structure used in artificial intelligence frame languages; they are stored as ontologies of sets.

Frames are also an extensive part of knowledge representation and reasoning schemes. They were originally derived from semantic networks and are therefore part of structure-based knowledge representations. According to Russell and Norvig's "Artificial Intelligence: A Modern Approach", structural representations assemble "\[...]facts about particular objects and event types and arrange the types into a large taxonomic hierarchy analogous to a biological taxonomy".

### Lexical unit

Lexical units (LU) are lemmas, with their part of speech, that evoke a specific frame. In other words, when an LU is identified in a sentence, that specific LU can be associated with its specific frame(s). For each frame, there may be many LUs associated to that frame, and also there may be many frames that share a specific LU, this is typically the case with LUs that have multiple word senses. Alongside the frame, each lexical unit is associated with specific frame elements by means of the annotated example sentences.

Example:

Lexical units that evoke the `Complaining` frame (or more specific perspectivized versions of it, to be precise), include the verbs "complain", "grouse", "lament", and others.

### Ontology Design Pattern (ODP)

An OP is a modeling solution to solve a recurrent ontology design problem. It is a template that represents a schema for specific design solutions. An ODP consists of a set of “prototypical” ontology entities that constitute the “abstract form” of a pattern, and of a set of metadata about its use cases, motivations, provenance, the pros and cons of its application, the links to other patterns, etc. Design solutions based on ODPs encode ontology entities that apply, specialize, or instantiate the prototypical entities defined by the schema.

### Content Ontology Design Pattern (CP)

CPs are distinguished networked ontologies and have their own namespace. They cover a speciﬁc set of competency questions (requirements), which represent the problem they provide a solution for. Furthermore, CPs show certain characteristics, i.e. they are: computational, small, autonomous, hierarchical, cognitively relevant, linguistically relevant, and best practices.

They show the following characteristics: CPs encode conceptual, rather than logical design patterns. In other words, while Logical OPs solve design problems independently of a particular conceptualization, CPs propose patterns for solving design problems for the domain classes and properties that populate an ontology, therefore addressing content problems. CPs are instantiations of Logical OPs (or of compositions of Logical OPs), featuring a non-empty signature. Hence, they have an explicit non-logical vocabulary for a specific domain of interest (i.e. they are content-dependent). CPs provide solutions to domain modeling problems and affect only the specific region of the ontology dealing with such domain modeling problems. They are typically reused by applying specialization, extension, and composition to them. In principle, CPs do not depend on any specific language, however in order to reuse them as building blocks, they have to be implemented in some way. In the portal _ontologydesignpatterns.org_ we mainly deal with CPs in a Semantic Web context, hence we currently support OWL as a reference formalism for representation.

\-- TO FIX -- Used CPs:

CQs: What is before that? What's Next? [http://ontologydesignpatterns.org/wiki/Submissions:Sequence](http://ontologydesignpatterns.org/wiki/Submissions:Sequence) Reusable OWL Building Block: [http://ontologydesignpatterns.org/cp/owl/sequence.owl](http://ontologydesignpatterns.org/cp/owl/sequence.owl)

CQs: What are the consequences of this action? [http://ontologydesignpatterns.org/wiki/Submissions:Action](http://ontologydesignpatterns.org/wiki/Submissions:Action) Reusable OWL Building Block: [http://www.ontology.se/odp/content/owl/Action.owl](http://www.ontology.se/odp/content/owl/Action.owl)
