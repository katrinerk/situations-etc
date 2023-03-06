# Reading list: Situations, Scripts, Narrative Schemas, Scenes, Generalized Event Knowledge, 

## Scripts in Psychology and Artificial Intelligence

* Minsky: to be added

* [Schank & Abelson 1977, Scripts, Plans, Goals, and Understanding](https://www.taylorfrancis.com/books/mono/10.4324/9780203781036/scripts-plans-goals-understanding-roger-schank-robert-abelson): This seminal book develops the idea that humans know typical scripts, that is, typical sequences of events, and use them for making sense of the world. 

This idea has been further studied in many subsequent papers, among them: 

* [Bower/Black/Turner 1979, Scripts in Memory for Text](https://psycnet.apa.org/record/1979-27802-001) 
They test people's knowledge of scripts, including one experiment where participants put slashes in given stories to indicate "natural parts"

* [Liechtenstein/Brewer 1980, Memory for goal-directed events](https://psycnet.apa.org/record/1980-24752-001): Goals and subgoals as the main organizing force of scripts. 

* [Abbott/Black/Smith 1985, The representation of scripts in memory](https://psycnet.apa.org/record/1986-05481-001): They assume a 3-level hierarchy of scene actions (lowest), scene headers, script headers (highest). They find that people infer higher-level events from lower-level, but not vice versa.
They hypothesize that there's a "goldilocks level", like basic kinds in concept representation theory, and it's scene headers. 

* [Zwaan/Radavansky 1998, Situation models in language comprehension and memory](https://psycnet.apa.org/record/1998-00120-003): Humans build mental models. not model-theoretic but visual, spatial
imaginings of what is talked about

* [Austin/Vancouver 1996, Goal constructs in psychology: Structure, process, and content](https://psycnet.apa.org/record/1996-01405-002) They focus on defining the notion of goals in scripts


## Generalized Event Knowledge in psychology

While neither "scripts" nor "generalized event knowledge" are exactly defined in the literature (and probably they cannot be), Generalized Event Knowledge is about knowledge at a smaller scale than the scripts above: While scripts seem to be mainly long sequences of events structured into segments, Generalized Event Knowledge is about a single event and its participants. 

* Summary of this line of research in a single sentence (and an overview article): [McRae and Matsuki 2009, People use their knowledge of common events to understand language, and do so as quickly as possible](https://compass.onlinelibrary.wiley.com/doi/abs/10.1111/j.1749-818X.2009.00174.x)

In particular:

* [McRae/Ferretti/Amyote 1997, Thematic roles as verb-specific concepts](https://www.researchgate.net/profile/Todd-Ferretti/publication/236594987_Thematic_Roles_as_Verb-specific_Concepts/links/0c9605182b658b3a38000000/Thematic-Roles-as-Verb-specific-Concepts.pdf) Selectional preferences as concepts with typical features. For example, “young naive gambler” is a more likely Theme than Agent of “manipulate”

* Mention of an event along with one argument will make the listener expect specific other arguments, for example "mechanic checked... brakes" is more expected than "mechanic checked... spelling", and conversely for "journalist checked...":  [Bicknell et al 2008](http://grammar.ucsd.edu/labs/cpl/papers/bicknell_et_al_2008_cogsci.pdf), [Hare et al 2009](https://www.sciencedirect.com/science/article/abs/pii/S0010027709000389?dgcid=api_sd_search-api-endpoint)

* There is also an effect of loosely co-occurring objects and events: [Metusalem et al 2012](https://www.sciencedirect.com/science/article/abs/pii/S0749596X12000034)

* [Elman 2009](https://onlinelibrary.wiley.com/doi/10.1111/j.1551-6709.2009.01023.x) speculates that given that Generalized Event Knowledge does not easily fit into word-specific lexicon entries, and given that Generalized Event Knowledge influences human sentence processing, maybe we might not need to postulate a lexicon, and Generalized Event Knowledge might be enough.

* [Chersoni et al 2019](https://www.cambridge.org/core/journals/natural-language-engineering/article/abs/structured-distributional-model-of-sentence-meaning-and-processing/B263913EBBE16ECFED1F9439CFF78296) propose a computational model of Generalized Event Knowledge where (lexical) selectional preferences are re-ranked by event knowledge encoded in a graph. They also provide a challenge dataset.


## Situations, frames and scripts in linguistics

### Situation semantics

Situation semantics was introduced by Barwise and Perry, see [Barwise and Perry 1983](https://press.uchicago.edu/ucp/books/book/distributed/S/bo3625416.html).
For overviews, see [Kratzer 2021, Situations in Natural Language Semantics ](https://plato.stanford.edu/entries/situations-semantics/) and [Stojanovic 2012, Situation Semantics](https://hal.science/file/index/docid/629850/filename/situationsemantics.pdf). [Devlin 2006, Situation Theory and Situation Semantics](https://web.stanford.edu/~kdevlin/Papers/HHL_SituationTheory.pdf) gives an overview of the formalization.

Kratzer: "Situation semantics was developed as an alternative to possible worlds semantics. In situation semantics, linguistic expressions are evaluated with respect to partial, rather than complete, worlds. There is no consensus about what situations are, just as there is no consensus about what possible worlds or events are. According to some, situations are structured entities consisting of relations and individuals standing in those relations. According to others, situations are particular"

Stojanovic describes situation theory as "breaking off with the Fregean heritage"

* Primacy of situations. "reality consists primarily of situations, while other categories, such as individuals, properties, or locations, arise as uniformities across situations"
* Partiality: "information is [...] partial"
* Efficiency of language: "same words can be used in different contexts to mean different things"
* A relational theory of meaning: "the idea that meaning should be seen as a relation between situations, rather than some kind of independent entity"
* Uniformities and constraints: "agents get attuned to various kinds of uniformities, which allow them to classify the reality in ways that enhance their capacities for action". "constraints are then seen as uniformities that arise among the ways in which situations relate to one another
* The reference relation and its relata: "instead of taking reference to be a relation between a *sentence* and its *truth value*, it takes it to be a relation between *utterances* and (other) situations; secondly, instead of taking reference to be a relation between a *name* [...] and an *individual*, it takes it to be a relation again between utterances [...] and other situations"
* Truth as uniformity across situations: "truth is merely a device that helps us classify situations"
* Semantic innocence and attitude reports: "one of the main motivations is that the embedded clause [...] should have the same meaning as it does when it occurs on its own"



Barwise/Perry, Kratzer, Stojanovic

### Situations, frames, and scripts and sentence understanding

Fillmore: Frames are chunks of background information that are being evoked whenever you hear a word (or construction)
frames as comprising schemas, scripts, situations

Fillmore, Recanati point to importance of script knowledge in sentence understanding

### Situations in probabilistic semantics

Dobnik/Cooper/Lappin/Larsson: situations as atomic, with probabilistic propositions as types

Lassiter/Goodman: generative model of situations, size based on question under discussion

## Narrative schemas and scripts in computational linguistics
