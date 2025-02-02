---
layout: default
---

# GWA Base Concepts

# Introduction

The notion of Base Concepts was introduced in the EuroWordNet project to
reach maximum overlap and compatibility across wordnets in different
languages, while at the same time, allow for the distributive
development of wordnets in the world, each wordnet being a language
specific structure and lexicalization pattern. The Base Concepts are
supposed to be the concepts that play the most important role in the
various wordnets of different languages. This role was measured in terms
of two main criteria:

1.  A high position in the semantic hierarchy;
2.  Having many relations to other concepts;

The Base Concepts are thus the fundamental building blocks for
establishing the relations in a wordnet and give information about the
dominant lexicalization patterns in languages. Base Concepts should not
be confused with Basic Level Concepts as defined by Rosch (1977). Basic
Level Concepts are the result of a compromise between two conflicting
principles of categorization:

1.  Apply to as many concepts as possible;
2.  Apply as many features as possible;

As a result of this, Basic Level Concepts typically occur in the middle
of hierarchies and less than the maximum number of relations. Base
Concepts mostly involve the first principle only. They are
generalizations of features or semantic components and thus apply to a
maximum number of concepts.

# Universality

The following types of Base Concepts have been distinguished:

1.  Common Base Concepts (CBC): concepts that act as Base Concepts in at
    least two languages;
2.  Local Base Concepts (LBC): concepts that act as Base Concepts in
    only a single language;
3.  Global Base Concepts (GBC): concepts that act as Base Concepts in
    all languages of the world;

The selection of the Base Concepts is an approximation based on:

-   Structural properties of the wordnets in different languages;
-   An equivalence mapping of the synset in a wordnet in Language X to a
    synset in the Princeton WordNet, initially to version 1.5 currently
    to version 2.0.

The structural properties of wordnets are partially arbitrary and thus
only weakly indicative. The idea has been so far that independent
selections from a large number of languages will still give a good
approximation. As properties have been used:

-   Position in the hierarchy and number or relations, if available;
-   Frequency in the definitions or glosses, if available;
-   Morphological complexity and dependency;

Sense frequencies are not available and word frequencies were shown to
be unreliable. Furthermore, it should be noted that many wordnets are
developed by expanding from Princeton WordNet and therefore do not
contribute to the definition of the Global Base Concepts. Roughly two
approaches have been followed for building wordnets:

1.  Expand approach: translate the synsets in the Princeton WordNet to
    your own language, take over the relations from Princeton and
    revise;
2.  Merge approach: define synsets and relations in your own language
    and then align your wordnet with the Princeton WordNet using
    equivalence relations;

Obviously, the merge aproach would give more independent suggestions for
BCs. However, the expand approach can still contribute if the resulting
local wordnet structure is revised and validated in a later phase and
afterwards makes a selection according to the same criteria.

In [EuroWordNet](http://www.illc.uva.nl/EuroWordNet/), an initial set of
1024 Common Base Concepts (CBCs) were selected and defined as Princeton
WordNet1.5 synsets. These CBCs play a BC role in at least two
independent wordnets. The languages in EuroWordNet are: English, Dutch,
German, French, Spanish, Italian, Czech and Estonian, but for the
initial selection only English, Dutch, Spanish and Italian were used.
For the 1012 CBCs, EuroWordNet defined a top-ontology that has been the
common semantic framework for defining the relations in each individual
wordnet separately. On the next page you can find a definition of the
EuroWordNet CBCs and the top-ontology classification: [EuroWordNet Base
Concepts and
Top-Ontology](http://www.globalwordnet.org/gwa/ewn_to_bc/topont.htm)

In the [BalkaNet](http://www.ceid.upatras.gr/Balkanet/) project, a
similar approach was applied to another set of languages: Greek,
Romanian, Serbian, Turkish, Bulgarian. BalkaNet extended the set to 4689
synsets and upgraded the mapping of the CBCs to Princeton WordNet 2.0.
The 5000 CBCs as WordNet2.0 synsets can be downloaded here:

[4689 Common Base Concepts from EuroWordNet and BalkaNet as Wordnet2.0
synsets](http://globalwordnet.org/wp-content/uploads/2013/07/5000_bc.zip)  

 

# The role of Base Concepts for Building wordnets

The Base Concepts have been defined so far in two European projects,
EuroWordNet and BalkaNet. They played a crucial role in building the
wordnets. More information can be found in this powerpoint
presentation: [Building Wordnets, by Piek
Vossen](http://www.globalwordnet.org/gwa/BuildingWordnets.ppt). Below is
a short description of the approach.

Each wordnet was developed in two phases according to a top-down
approach:

1.  Develop a core wordnet around the CBCs that is highly compatible in
    coverage and semantic interpretation;
2.  Extend the core wordnet semi-automatically top-down, given the
    semantic basis of the core wordnets;

Using this approach we guarantee that the cores of the wordnets are
highly compatible and comparable, but at the same time language-specific
structures and lexicalizations can be expressed. For developing the core
wordnets, we followed the next approach:

1.  Represent the 1024 CBCs by one or more synsets in the local language
    that are either equivalent or most closely approximate the CBCs in
    Princeton WordNet. These are the CBC-representatives in the local
    language;
2.  Add Base Concepts that are important to the local wordnet but not in
    the CBC set. These are Local Base Concepts (LBCs)
3.  Add hyperonyms of the BCs (=CBC-representatives+LBCs) to form a
    closed and consistent hyperonym hierarchy that is compatible with
    the EuroWordNet top-ontology
4.  Add further (horizontal) relations that are necessary to specify the
    semantics of the BCs.
5.  Extend the BCs with hyponyms one level down;

For developing the extended wordnets, various criteria were used, among
which:

-   Adding most frequent words from a corpus that are not included;
-   Add words and synsets that are easily included due to the specific
    properties of the language;
-   Add words and synsets that are easily linkable to the Princeton
    Wordnet with equivalence relations (automatically) derived from
    bilingual dictionaries;
-   Add synsets that increase the intersection with other wordnets;
-   Synsets that can be added because of specifically available
    resources, e.g. monolingual lexicons, ontologies, thesauri, etc.;

Core wordnets are typicaly between 5,000 and 10,000 synsets. Extended
wordnets go beyond 20,000 synsets.
