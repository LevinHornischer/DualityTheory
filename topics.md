# Paper topics for Duality Theory

## Comments

Here I collect some possible topics for your final essay. (I might also still add more and update the present ones.) Just to be sure, the suggested topics are meant as first ideas. It is part of the task of writing an essay to turn an interesting aspect of the suggested topic into a precise research question and collect the relevant literature on it. Please take a look at the grading criteria mentioned in the file [`formalities.pdf`](formalities.pdf) to get a clear idea of what a good essay is expected to look like. 

Overall, the topics follow the pattern of applying the formal tools of duality theory to some philosophical topic. So they are an instance of the method of mathematical philosophy: 
1. Start with an interesting philosophical phenomenon.
2. Model it with an appropriate mathematical structure.
3. Study this structure with mathematical techniques.
4. Translate the mathematical results back to the philosophical setting.
5. Critically assess the formalization: Do the mathematical results yield genuinely new philosophical insights? Where is the mathematical formalization not precise enough? Where is it overly precise?  

Many of the suggested topics below are also found as exercises at the end of the introduction chapter. So they concern the philosophical phenomena that we used at the beginning of the course to motivate the formal duality, which we have subsequently studied. So also have a look again at this introduction chapter for more background.

## Topics

* _Adding negation_. When discussing the notion of a prime filter, we asked if it is lacking a principle concerning negation: that for every element $a$ of the lattice, either $a$ is in the filter or $\neg a$ is in the filter. This requires the lattice to be a Boolean algebra, i.e., have a (classical) notion of negation. Is this a plausible principle? What if the lattice contains vague properties, like being red? What about the formal results that a prime filter of a Boolean algebra already satisfies the just mentioned principle about negation (i.e., is an ultrafilter)?

* _Formal concept analysis_. To what extent can the 'objects vs. properties'-example of a duality be developed along the lines of [formal concept analysis](https://en.wikipedia.org/wiki/Formal_concept_analysis)?

* _Similarity on worlds_. From a classical point of view, the set $L$ of propositions (i.e., the meanings of declarative sentences) form a Boolean algebra and the set of possible worlds are (or can be identified with) maximally consistent sets of sentences, so they are prime filters on $L$. What duality theory adds is that that the set of possible worlds, i.e., the set $\mathsf{PrFilt}(L)$ of prime filters on $L$, carries a topology. We have motivated the topology as spelling out a notion of similarity between the prime filters, and hence between possible worlds. Philosophers have discussed in depth the notion of similarity between possible worlds, because it for example figures prominently in counterfactuals ('If A were true, then B would be true' is analyzed as: in the closest world where A is true, also B is true). Can the notion of similarity provided by duality theory help here?

* _Propositions as clopens_. The second addition that duality theory makes to the classical view on proposition is that propositions can indeed be identified with sets of worlds (namely the set of worlds where they are true), but not every set of worlds is a proposition (only the clopen sets are). This avoids the mismatch in cardinality plaguing the view that any set of worlds is a proposition. Because on that view there would be many more propositions (subsets of the set $W$ of worlds) than there are sentences (elements of the lattice $L$), while on the view that propositions must be clopen they align ($L$ is isomorphic to the set of clopen subsets of $W$). The requirement on propositions that they are clopen might be motivated by saying that they should, in a sense, be closed under similarity (which, in turn, is spelled out by the topology): does this motivation hold up under philosophical scrutiny?

* _Indiscernability_. For a logico-philosophical discussion of the principle of indiscernability, see [Ladyman et al. 2012](https://www.cambridge.org/core/journals/review-of-symbolic-logic/article/abs/identity-and-discernibility-in-philosophy-and-logic/C6A29A45353E6330A8FEF319BE438FC8). How does this inform the motivating philosophical discussion from the introduction chapter on 'worlds vs. propositions'? This paper is in the context of model theory, what does the above duality-theoretic perspective add?

* _Cognitive dualities_. Can you think of more examples where a duality is involved? In cognitive science: what about concepts vs. mental states (computable theory of mind vs. [connectionism](https://plato.stanford.edu/entries/connectionism/)). Or, related, in AI: or human-interpretable concepts (symbolic) vs. states of neural networks (subsymbolic)? Or are these better seen as relations of supervenience rather than duality? What about the infamous Cartesian duality between the physical and the mental world?

* _Abstraction principles_. The specialization order on a topological space describes a relation of abstraction between the points (thought of as objects or models) of the space: that one point is more special (more concrete, more informationally complete, more determined, etc.) than another point. Moving from the level of points to the level of (po)sets/spaces, the notion of an order adjunction (especially when the composition 'first lower adjoint then upper adjoin' is the identity function) also describes a sense in which the one poset is an abstraction of the other. Does this connect to the discussion of abstraction principles in philosophy? Specifically, in the context of Neo-logicism? For a short introduction to the latter, see [Linnebo 2007](https://www.jstor.org/stable/40271354).
