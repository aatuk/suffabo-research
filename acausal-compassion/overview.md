- [The big picture: valence and consciousness realism informed by a dynamic systems / evolutionary perspective](#orgf96272a)
- [Valence realist and acausal decision theory](#org3230cb9)
- [ICK (ICBINAALM! Combinator Kernel)](#org282542c)

The term &ldquo;acausal compassion&rdquo; refers to a set of ideas, insights, approaches, design aesthetics, decision theoretic formalisms and conjectures, computational artefacts, and research directions and programs center around the following central conjecture:

-   valence realism, (likely Knightian) self-locating uncertainty, impredicative coherence, and the fact that acausal coordination/cooperation power is proportional to the impartial non-indexical discoverability, definability and preferability, imply that sentience based large-scale agency in reality corresponds to what can be described as the
    
    -   effectively open-individualist
    -   updateless, timeless and acausal
    -   impredicative
    -   valence-realist / increasingly suffering focused as the intensity of suffering increases
    -   super-cooperator
    
    cluster/attractor, a sort of self-designing and manifesting structure encoded in the unfolding of its decision theoretic structure (along &ldquo;decision theoretic&rdquo; or &ldquo;logical&rdquo; time)
-   this attractor is <span class="underline">over-determined</span> in that for instance effective open-individualism arises from many different forces, and is mutually reinforced by the interaction of the various constraints mentioned above, indeed a sort of &ldquo;impredicative fix-point&rdquo; with various manifestations that depend on the &ldquo;local conditions&rdquo;

In order to make this precise and explore it, we require sufficiently sophisticated **executable** mathematical machinery and formalism. Hence one of the &ldquo;computational artefatcs&rdquo; of this research program is **ICK** (ICBINAALM! Combinator Kernel), a meta-reflective combinator calculus with support for first-class impredicative and self-rerential data. (The larger ICBINAALM! project will also hopefully prove to be very helpful in alignment research, hardening the epistemic commons, and other less purely conceptual and theoretical pressing matters. This is related to &ldquo;Aumanning protocols&rdquo;.)

(&ldquo;Classical&rdquo; alignment research might be characterized as the quest to find the ultimate do anything machine, and also the correct input to feed to it. This is &#x2013; as many recognize! &#x2013; probably a) extremely dangerous and b) either impossible or extremely difficult. The approach suggested by the acausal compassion program is to instead start from the alignment goal &#x2013; the well-being of all sentient beings &#x2013; and figure out what the **partial application** \`(do-anything omnibenevolence)\` would look like, using the sort of &ldquo;impredicative&rdquo; tying-the-knot reasonign where you are allowed to just **assume you already have a solution** in certain places, as long as your reasoning has certain features, that is easy to explore and implement in ICK/ICBINAALM!.)

Part of the underlying generator aesthetic for this research program is the starting assumption point that while agency in some sense might be fundamental to reality &#x2013; arising essentially from certain sort of selection pressure at various &ldquo;levels&rdquo; &#x2013; factorization into distinct &ldquo;beings&rdquo; or &ldquo;agents&rdquo; is not, and indeed that the way we usually perceive/model reality and ourselves is an extremely specific special case of something vastly more general.

Indeed, the conjecture is not only that there is a specific decision theoretic attractor shared (at least at large enough scales) by all sentience / all sentient beings, but that it is also vastly more **efficient** to operate/think from an impartial &ldquo;effectively open-invididualist&rdquo; stance, and that this offers a way of thinking about ethics in a way that offers principled ways to resolve conflicts that does not reduce to simple might makes right (even in super-refined versions involving superrationality etc.)

One central tool here is the notion of active-inference and the free energy principle in particular. In order to understand our &ldquo;local conditions&rdquo;, it seems likely very useful to apply a whole system evolutionary &ldquo;cybernetics of cybernetics&rdquo; / &ldquo;agentless&rdquo; free-energy principle lens, in particular to understand the way self-locating uncertainty and (emergent) acausal &ldquo;coordination&rdquo; encoded in entanglement patterns in the self-modifying increasingly self-evidencing predictive machinery that is currently installing it into the local causal structure, with increasingly tightening causal feedback loops.

Here when we speak of &ldquo;computation&rdquo;, we do not necessarily mainly have in mind digital Turing-machine style computation, but rather the much more general &ldquo;qualia computation&rdquo; and the related &ldquo;material science of consciousness&rdquo;. It is helpful to see us as hovering around the QRI memeplex, and from which we draw theoretical and conceptual tools. As an illustrative (and useful in making contact with relatively concrete phenomena) case study, we do a side-quest into speed-running and Minecraft computers.

Since this, as well as many of the key ideas and concepts are somewhat unusual, little-known, or counter to the currently predominant ideas (such as computationalist-funcionalist account of consciousness and phenomenal binding), a key initial undertaking is simply to explain the central ideas and concepts, without necessarily trying to simultaneously **justify** them. Once this is done, it will then be possible to explore their justification, and how to handle uncertainty / disagreement about relatively fundamental matters in this space. It&rsquo;s my belief that simply providing a **coherent exposition** or a sophisticated version of valence-realist decision theory is in itself a valuable contribution to our understanding of our predicament.

---


<a id="orgf96272a"></a>

# The big picture: valence and consciousness realism informed by a dynamic systems / evolutionary perspective


<a id="org3230cb9"></a>

# Valence realist and acausal decision theory


<a id="org282542c"></a>

# ICK (ICBINAALM! Combinator Kernel)

-   a methodological approach: many aspects of our current practical access to the computational aspect of reality as well as the foundational conceptual framings are extremely path dependent and founded on contingent limitations that are no longer relevant (or as relevant)
-   it is possible to revisit certain &ldquo;bifurcation points&rdquo; in the historical unfolding and reattain some &ldquo;lost dreams&rdquo;, in particular
    -   full meta-reflectivity / meta-circularity without hard phase distinctions in the style of early LISP (before Scheme, macros and eschewal of f-exprs)
    -   non-stratified &ldquo;reflection&rdquo; or &ldquo;reification&rdquo; in the sense of 3-LISP
    -   simple capability based distributed computing
    -   live interactive higher-order &ldquo;systems&rdquo; programming
    -   full time-travelability (in a sense generalizing the use for debugging)
    -   direct implementation of &ldquo;self-referential&rdquo; or &ldquo;cyclica&rdquo; data
-   this is realized in ICK, which is
    -   a pure combinator calculus with no variables but names and explicit substitution combinators as first-class values
    -   a model of evaluation based on a generalization of the vau calculus / Kernel idea, so that all combinators in addition to their argument in the usual sense also receive the **evaluator** (which can be an arbitrary term, and need not be defined by a lexical environment)
    -   based on an ontology of &ldquo;rational trees with urelements&rdquo; thought of as a subuniverse of the set theoretic anti-foundation axiom (AFA) universe
    -   equality as bisimilarity, with O(1) equality check (by making physical/pointer equality conincide by bisimilarity by canonicalizing when entering terms as solutions to set of equations/evaluating)
    -   AFA data compatible evaluation using the standard &ldquo;allocate placholder + add to memo table + patch placeholder (with canonicalization) to point at the result&rdquo; knot tying pattern
    -   (nearly?) optimal reduction and maximal sharing thanks to hash consing and canonicalization
    -   I/O / mutation using continuation based async logged/replayble events conceived of as turns in an interaction game with the environment; everything immutable by default
    -   capable of easily expressing partial evaluation, Futamura projections, and allowing for aggressive super-compilation
    -   defined by a simple enough core evaluation mechanism plus a set of &ldquo;native combinators&rdquo;/&ldquo;primops&rdquo; to be fully understood by a single individual and implemented in any suitable host language, based on well-known algorithms (though maybe in a somewhat unusual combination)
-
