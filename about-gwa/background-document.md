---
layout: default
---

# Background Document

**Description:**

The goal of GWA is to establish a Word-wide Association for maintaining,
standardising and interlinking wordnets for all languages in the world,
likewise preparing the ground for the development of a world-wide
multilingual database with wordnets. The main objectives of GWA are:

-   standardize the specification of lexical semantic relations, the
    notion of a synset and degrees of polysemy
-   standardize the Inter-Lingual-Index for interlinking the wordnets of
    different languages
-   extend the specification to include all Parts-of-Speech and
    multiword expressions
-   develop a common XML representation for wordnet data
-   prepare the development of sense-tagged corpora in all the linked
    languages.
-   sharing and transferring of data, software and specifications across
    wordnets for different languages
-   the development of guidelines and methodologies for building
    wordnets in new languages
-   the development of explicit criteria and definitions for verifying
    the relations in any language
-   the development of consistency checking, comparison and evaluation
    modules

**Lexical semantic relations, synset and polysemy**

The first objective involves the coordination and integration of the
current initiatives: the Princeton WordNet and EuroWordNet. Their
specifications will be compared and we will agree on a common
specification for future releases of wordnets. This will include, among
others, an extension of Princeton WordNet with references to the
Inter-Lingual-Index so that it can directly be compared and mapped to
the other wordnets in future.

**Inter-Lingual-Index**

A major issue of the project is the development of a standardized index
of sense-distinctions or so-called Inter-Lingual-Index (ILI) that can be
used as a universal and cross-lingual standard for sense
differentiation. The current ILI, developed in EuroWordNet, is based on
WordNet1.5 and is partially adapted to provide a better matching across
the languages. On the one hand, it should be the superset of all
concepts occurring in the different languages, on the other hand, it
should have a certain granularity or generality of
sense-differentiation. A similar adaptation of the sense-differentiation
has been applied to WordNet1.6, and is aimed at in Corelex developed at
Brandeis University. The granularity of WordNet1.5 is often discussed in
relation to comparing and evaluating word-sense-disambiguation
techniques. A major theme in the SENSEVAL/ROMANSEVAL competition has
been the need for such a standardised list of sense-distinctions.

Some fundamental issues still have to be resolved, before the ILI can be
agreed upon as index of word meanings. To what extent is regular
polysemy valid across languages, and can it be solved centrally in the
ILI, as it is currently done in EuroWordNet? In what sense should the
ILI be the universal superset of concepts and what is the status of the
concepts that are to be included? In GWA we will develop a fundamental
approach to standardised ILI. The status of concepts in the index will
be defined on the basis of criteria, such as:

-   Universality: in how many languages does the concept occur?
-   Usage: how frequently is the concept used across languages?
-   Productivity: how easily can similar or related concepts be derived
    as new concepts?
-   Morpho-syntactic markedness across languages: have words a
    morphological complex structure?
-   Relations between index-records: can index records be seen as
    (productive) specializations or regular extensions of other index
    records?
-   Ontological status of index-records: to which degree the concept is
    capable of distinguishing word senses in a minimally overlapping
    way.

These criteria will also clarify the different ways in which concepts
can be lexicalized in languages. This will shed light on the
cross-linguistic distribution of polysemy, derivation, compounding and
multi words or phrases as ways of expressing concepts in languages. The
resulting sense-structuring of ILI will be tested in
Word-Sense-Disambiguation and Automatic-Document-Classification tasks
for all the inter-linked languages. We will participate in international
competitions such as multilingual TREC and SENSEVAL/ROMANSEVAL.

Another important aspect of the ILI is that it should be made possible
to integrate other monolingual and ontological sources into the ILI
(senses from other dictionaries like Hector and ontologies such as
Mikrokosmos). This will create a platform for verification and
comparison. Techniques for semi-automatically linking these different
types of resources will have to be created and tested.

All this will amount to an extension of the present ILI architecture.
The ILI will have a layered structure in which different levels will be
distinguished. These levels may be the following:

1\) resource specific concepts.

The architecture should allow sense distinctions from different
resources to be incorporated as a contribution towards the
standardisation of the notion of

concept/word sense. For language specific wordnets this will mean
creating alternative linking systems involving different sets of ILIs.

2\) clusters

Composite ILIs need to be typed according to the resource that is
responsible for their clustering. Overlaps between the cluster types
need to be established.

3\) links between ILIs and ontologies (WN, Top Ontology, Mikrokosmos,
Cyc…)

In this way the status of concepts can be defined and standardised in a
bottom-up fashion, and GWA can be the multilingual platform for this
standardisation effort and the integration/merge of ontologies.

 

**All Parts-of-Speech and multiword expressions**

The third objective is closely related to the above lexicalization
phenomena. The current European wordnets are limited to nouns and verbs
and hardly include phrases and collocations. However, it is obvious that
meanings are not just expressed by nouns and verbs or single words.
Languages use a variety of ways to express content. When we include a
wider range of words and expressions we will also get a clear view on
the existence of concepts in language-cultures and the ways in which
these are expressed. We see for example that many lexicalized compounds
in Germanic languages are often expressed as adjective-noun
combinations, noun-preposition-noun combinations or derivations in
Romanic languages. The possibility to include phrases, derivations and
collocations in wordnet, either in a static way or dynamically, is
essential for high-quality applications in the areas of Information
Retrieval, Machine Translation, Language Generation and Language
Learning applications. The wordnets will make it possible to reduce
expressions to their conceptual content but also to generate all
possible conceptual combinations of words that are compatible with such
content (either within a language or across languages). Similar, it is
evident that a language-resource needs to be able to generate derived
forms when a direct equivalent for a concept is not present. Information
on typical collocation restrictions within this set can then be used to
select the typical and intuitive phrases out of all possible
combinations. In the future, sense-tagged corpora that are related to
the wordnets will become an essential component of the wordnets. GWA
will prepare the development of these corpora in a uniform way. This
involves the selection of comparable corpora and semantic tag sets.

**Sense-tagged corpora in all languages**

The Brown corpus with WordNet1.5 sense tags plays a crucial role in the
development of Word-Sense-Disambiguation techniques. To both test the
differentiation of senses across languages, and to evaluate the ILI as a
fund of universal sense-distinctions it is therefore crucially important
that similar corpora will be created for the other languages. These
corpora can be tagged with senses from the local wordnets, but we will
also tag them with ILI concepts, WordNet1.5 classes and the EuroWordNet
top-ontology classes. The latter taggings can be used to compare the
corpora, the sense codings and to test the Word-Sense-Disambiguation
techniques across languages.

**Software and Data Sharing across all languages**

A standardised specification of the relations and a standardised list of
sense-distinction in the form of the Inter-Lingual-Index will make it
possible to share and compare both data and software modules across
languages. Data sharing via the ILI will involve both language-neutral
and language-specific data:

-   definitions
-   examples
-   subject domains
-   ontologies
-   lexical relations

In the latter case, lexical relations are transferred from one wordnet
to another wordnet. This can either be done for special relations, such
as roles, meronymy or causal relations, but also for more fundamental
relations such as hyponymy and synonymy, when wordnets are being built
(see below).

Software that can be shared ranges from databases, editors, consistency
checking software, conversion software, and hierarchy comparison
software to conceptual distance and density measurements, corpus
verification, word-sense-disambiguation and automatic term-extraction
and classification. These modules, which are now available in different
environments, will be wrapped up and standardised in a shared toolkit
and evaluation module. This will make it possible to directly evaluate
and test new wordnets that are to be integrated in the database.

**Methodologies and guidelines for building wordnets**

Currently, a number of methods and principles have been developed to
build wordnets. A common approach is to start from an agreed set of
important concepts, the so-called Base Concepts, which have to be
represented in a local language and from which the core wordnets are
being built. The shared top-ontology plays an important role as a common
framework for guiding interpretation and formulating conceptual
constraints on the possible relations. Furthermore, there is now a list
of tests and definitions for semantic relations that can be extended and
improved, especially in combination with the top-ontology and being
supported by inheritance devices.

Extensions of the core wordnets can take place along different
strategies, e.g.: an expand or a merge approach. In the case of an
expand approach, a wordnet is translated and the lexical semantic
relations are taken over. In the case of the merge approach, independent
language specific structures are built first, which are translated to
the index afterwards. For both approaches, there exist techniques to
automatically map or translate wordnets to the ILI or to derive
relations from regular definition patterns or morphological structures.

In GWA we will collect these techniques and write guidelines and
methodologies that can be used by builders of wordnets for other
languages. The methodologies will not only make the construction process
more efficient but will also have a strong standardizing effect on the
encoding of the relations.

**Evaluation Module**

Finally, some of the software and the definitions can directly be used
to evaluate wordnets or fragments of wordnets. We will agree on a number
of evaluation criteria to test the validity and compatibility of
wordnets. In so far these criteria are implemented in software packages
we will provide automatic evaluation mechanisms. Currently the wordnets
are evaluated in terms of:

1\. size of synsets, meanings, words (per POS)

2\. density of Language Internal relations (per relation type, and per
POS)

3\. density of Equivalence relations (per relation type, per POS)

4\. overlap in Index items covered

5\. distribution over Ontology clusters

6\. length of the hyperonymy chains

7\. overlap of hyponym chains represented by the equivalent ILI-records

8\. overlap and coverage with respect to corpora

Further criteria will be developed and combined in a single evaluation
module.

 

GWA directly builds on the success of the Princeton WordNet and
EuroWordNet. It will fulfil a direct need for multilingual semantic
resources and will make it possible to share domain-ontologies across
languages or upgrade ontologies to multilingual dimensions.

On a longer term, GWA aims at the development of wordnets for all
languages in the world and to extend the wordnets to full coverage and
all parts-of-speech. We will investigate what regulations and
organisation are needed to support this. We will start co-operations
with institutes and national science foundations that are willing to
develop these wordnets or extend existing wordnets with the framework of
GWA.
