# Interaction Nets

## Projects

- HVM/Bend [website](https://higherorderco.com/), [orga](https://github.com/HigherOrderCo/), [repo](https://github.com/HigherOrderCO/HVM), [discord](https://discord.higherorderco.com/)
    - interaction combinators as a backend of a Python/Haskell-like language
    - focus on efficient, parallel, and optimal reduction of the lambda calculus without oracle
- Vine [website](https://vine.dev/), [orga](https://github.com/VineLang/), [repo](https://github.com/VineLang/vine/), [discord](https://discord.gg/bgUPV8KjDv)
    - interaction nets as a backend of a Rust-like language
    - focus on concurrency and interoperation between functional and imperative patterns
- Inpla [repo](https://github.com/inpla/inpla)
    - focus on custom interaction rules and interaction calculus
- ∆-Nets [website](https://deltanets.org/), [repo](https://github.com/danaugrs/deltanets)
    - interactive translator from lambda calculus to ∆-Nets (variation of interaction nets)
- inet-forth [repo](https://github.com/cicada-lang/inet-forth)
    - focus on custom interaction rules and interaction calculus in forth
- optiscope [repo](https://github.com/etiams/optiscope)
    - efficient implementation of lambdascope
- GoI-Visualizer [website](https://koko-m.github.io/GoI-Visualiser/), [repo](https://github.com/koko-m/GoI-Visualizer)
    - interactive translator from lambda calculus to an interaction net-like token-passing encoding (GoI)
    - focus on enforcing reduction strategies by various applicator-token interactions

## Research

### General

- 1990: Lafont, "Interaction Nets." [url](http://portal.acm.org/citation.cfm?doid=96709.96718)
- 1991: Gay, "Interaction Nets." [url](https://www.dcs.gla.ac.uk/~simon/publications/diploma.pdf)
- 1994: Asperti and Laneve, "Interaction Systems I." [url](https://www.researchgate.net/publication/220173276_Interaction_Systems_I_The_Theory_of_Optimal_Reductions)
- 1996: Asperti and Laneve, "Interaction Systems II." [url](https://www.sciencedirect.com/science/article/pii/0304397595000623)
- 1997: Lafont, "Interaction Combinators." [url](https://linkinghub.elsevier.com/retrieve/pii/S0890540197926432)
- 2003: Fernández and Mackie, "Operational Equivalence for Interaction Nets." [url](https://www.sciencedirect.com/science/article/pii/S0304397502006370)
- 2006: Ehrhard and Regnier, "Differential Interaction Nets." [url](https://www.sciencedirect.com/science/article/pii/S0304397506005299)
- 2009: Fernández, Mackie, Sato, and Walker, "Recursive Functions with Pattern Matching in Interaction Nets." [url](https://www.sciencedirect.com/science/article/pii/S157106610900437X)
- 2016: Mackie and Sato, "In-place Graph Rewriting with Interaction Nets." [url](https://arxiv.org/pdf/1609.03641)
- 2016: Mackie and Sato, "Parallel Evaluation of Interaction Nets: Case Studies and Experiments." [url](https://eceasst.org/index.php/eceasst/article/download/2205/2376/2387)
- 2016: Gimenez and Moser, "The Complexity of Interaction." [url](https://dl.acm.org/doi/10.1145/2837614.2837646)

### Implementation

- 2000: Pinto, "Sequential and Concurrent Abstract Machines for Interaction Nets." [url](https://link.springer.com/chapter/10.1007/3-540-46432-8_18)
- 2003: Pinto, "Weak Reduction and Garbage Collection in Interaction Nets." [url](https://www.sciencedirect.com/science/article/pii/S1571066105826143)
- 2009: Hassan, Mackie, and Sato, "Compilation of Interaction Nets." [url](https://www.sciencedirect.com/science/article/pii/S1571066109004381)
- 2015: Kahl, "A Simple Parallel Implementation of Interaction Nets in Haskell." [url](http://arxiv.org/abs/1504.02603)
- 2015: Sato, "Design and Implementation of a Low-Level Language for Interaction Nets." [url](https://sussex.figshare.com/articles/thesis/Design_and_implementation_of_a_low-level_language_for_interaction_nets/23417312/1)
- 2020: Accattoli, Lago, and Vanoni, "The Abstract Machinery of Interaction." [url](http://arxiv.org/abs/2002.05649)
- 2024: Taelin, "HVM2: A Parallel Evaluator For Interaction Combinators." [url](https://raw.githubusercontent.com/HigherOrderCO/HVM/main/paper/HVM2.pdf)
- 2025: Huber and Yi, "An Encoding of Interaction Nets in Ocaml." [url](https://joerg.endrullis.de/downloads/gcm2024/STAF_2024_paper_72.pdf)

### Geometry

- 1989: Girard, "Geometry of Interaction 1." [url](https://www.sciencedirect.com/science/article/pii/S0049237X08702714)
- 1992: Gonthier, Abadi, and Lévy, "The Geometry of Optimal Lambda Reduction." [url](https://dl.acm.org/doi/10.1145/143165.143172)
- 1995: Mackie, "The Geometry of Interaction Machine." [url](https://dl.acm.org/doi/10.1145/199448.199483)
- 2002: Fernández and Mackie, "Call-by-Value λ-Graph Rewriting without Rewriting." [url](https://link.springer.com/chapter/10.1007/3-540-45832-8_8)

### Syntax

- 1990: Lafont, "Interaction Nets." [url](http://portal.acm.org/citation.cfm?doid=96709.96718)
- 1999: Fernández and Mackie, "A Calculus for Interaction Nets." [url](https://link.springer.com/chapter/10.1007/10704567_10)
- 2005: Mackie, "Towards a Programming Language for Interaction Nets." [url](https://www.sciencedirect.com/science/article/pii/S1571066105050176)

### Non-Determinism

- 1999: Alexiev, "Non-Deterministic Interaction Nets." [url](https://era.library.ualberta.ca/items/8af05152-4996-401c-8d53-9c180b717891)
- 2002: Fernández and Khalil, "Interaction Nets with McCarthy’s Amb." [url](https://www.sciencedirect.com/science/article/pii/S1571066105803639)
- 2006: Mazza, "Interaction Nets: Semantics and Concurrent Extensions." [url](https://lipn.univ-paris13.fr/~mazza/papers/Thesis-1.0.pdf)

### IO

- 2012: Jiresch, "Extending Interaction Nets towards the Real World." [url](https://repositum.tuwien.at/handle/20.500.12708/12949)
- 2024: Taelin, "HVM2: A Parallel Evaluator For Interaction Combinators." [url](https://raw.githubusercontent.com/HigherOrderCO/HVM/main/paper/HVM2.pdf)

### Lambda Calculus

#### Efficiency

- 1996: Lawall and Mairson, "Optimality and Inefficiency." [url](https://dl.acm.org/doi/10.1145/232629.232639)
- 1998: Mackie, "YALE: Yet Another Lambda Evaluator Based on Interaction Nets." [url](https://dl.acm.org/doi/pdf/10.1145/291251.289434)
- 2004: Mackie, "Efficient λ-Evaluation with Interaction Nets." [url](https://link.springer.com/chapter/10.1007/978-3-540-25979-4_11)
- 2017: Asperti, "About the Efficient Reduction of Lambda Terms." [url](http://arxiv.org/abs/1701.04240)

#### Optimality

- 1980: Lévy, "Optimal Reductions in the Lambda Calculus." [url](https://pauillac.inria.fr/~levy/pubs/80curry.pdf)
- 1990: Lamping, "An Algorithm for Optimal Lambda Calculus Reduction." [url](http://portal.acm.org/citation.cfm?doid=96709.96711)
- 1992: Gonthier, Abadi, and Lévy, "The Geometry of Optimal Lambda Reduction." [url](https://dl.acm.org/doi/10.1145/143165.143172)
- 1996: Asperti, Giovannetti, and Naletto, "The Bologna Optimal Higher-Order Machine." [url](https://www.cambridge.org/core/journals/journal-of-functional-programming/article/bologna-optimal-higherorder-machine/1F2763B0F931680F9B15BDC750BEB343)
- 1996: Danos and Regnier, "Reversible, Irreversible and Optimal λ-Machines." [url](https://www.sciencedirect.com/science/article/pii/S1571066105804025)
- 1997: Asperti and Chroboczek, "Safe Operators." [url](https://doi.org/10.1007/s002000050083)
- 1998: Asperti and Guerrini, "The Optimal Implementation of Functional Programming Languages." [url](https://www.researchgate.net/publication/235778993_The_optimal_implementation_of_functional_programming_languages)
- 2000: Asperti, Coppola, and Martini, "(Optimal) Duplication Is Not Elementary Recursive." [url](https://dl.acm.org/doi/10.1145/325694.325707)
- 2003: Coppola and Martini, "Optimizing Optimal Reduction." [url](http://arxiv.org/abs/cs/0305011)
- 2004: van Oostrom, van de Looij, and Zwitserlood, "Lambdascope: Another Optimal Implementation of the Lambda-Calculus." [url](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=61042374787bf6514706b49a5a4f0b74996979a0)
- 2005: Guerrini, "Sharing Implementations of Graph Rewriting Systems." [url](https://www.sciencedirect.com/science/article/pii/S1571066105050164)
- 2013: Balabonski, "Weak Optimality, and the Meaning of Sharing." [url](https://doi.org/10.1145/2544174.2500606)
- 2014: Pedicini, Pellitta, and Piazza, "Sequential and Parallel Abstract Machines for Optimal Reduction." [url](https://www.mat.uniroma3.it/users/pedicini/papers/subTFP2014.pdf)
- 2017: Lai, Pedicini, and Piazza, "Abstract Machines, Optimal Reduction, and Streams." [url](https://iris.uniroma1.it/bitstream/11573/1408275/6/Lai_preprint_abstract_2019.pdf)
- 2025: Salvadori, "Δ-Nets." [url](https://arxiv.org/abs/2505.20314)

#### Tokens

- 1995: Mackie, "The Geometry of Interaction Machine." [url](https://dl.acm.org/doi/10.1145/199448.199483)
- 2005: Sinot, "Call-by-Name and Call-by-Value as Token-Passing Interaction Nets." [url](https://link.springer.com/chapter/10.1007/11417170_28)
- 2006: Sinot, "Token-Passing Nets: Call-by-Need for Free" [url](https://www.sciencedirect.com/science/article/pii/S1571066106000934)
- 2008: Almeida, Pinto, and Vilaça, "Token-Passing Nets for Functional Languages." [url](https://www.sciencedirect.com/science/article/pii/S1571066108001667)
- 2016: Salikhmetov, "Token-Passing Optimal Reduction with Embedded Read-Back." [url](http://arxiv.org/abs/1609.03644)
- 2018: Muroya and Chica, "Efficient Implementation of Evaluation Strategies via Token-Guided Graph Rewriting" [url](https://arxiv.org/pdf/1802.06495)

#### Theory

- 1997: Asperti, "P = NP, up to Sharing." [url](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=d45b284c43f8a341bb60826b2819557e0d0fe94a)
- 1998: Asperti and Mairson, "Parallel Beta Reduction Is Not Elementary Recursive." [url](https://dl.acm.org/doi/10.1145/268946.268971)
- 2003: Beckmann, "Exact Bounds For Lengths of Reductions in Typed λ-Calculus" [url](https://www.beckmann.pro/PaperFiles/lambda.pdf)
- 2004: Baillot and Terui, "A Feasible Algorithm for Typing in Elementary Affine Logic." [url](http://arxiv.org/abs/cs/0412028)
- 2007: Terui, "Light Affine Lambda Calculus and Polynomial Time Strong Normalization." [url](https://doi.org/10.1007/s00153-007-0042-6)
- 2013: David, Grygiel, Kozic, Raffalli, Theyssier, and Zaionc, "Asymptotically Almost All λ-Terms Are Strongly Normalizing." [url](https://arxiv.org/pdf/0903.5505)
- 2014: Accattoli and Dal Lago, "Beta Reduction Is Invariant, Indeed." [url](https://doi.org/10.1145/2603088.2603105)
- 2022: Lago, "Implicit Computation Complexity in Higher-Order Programming Languages: A Survey in Memory of Martin Hofmann." [url](https://www.researchgate.net/publication/359247675_Implicit_computation_complexity_in_higher-order_programming_languages_A_Survey_in_Memory_of_Martin_Hofmann)

### Linear Logic

- 2000: Asperti, Coppola, and Martini, "(Optimal) Duplication Is Not Elementary Recursive." [url](https://dl.acm.org/doi/10.1145/325694.325707)
- 2000: Mackie, "Interaction Nets for Linear Logic." [url](https://www.sciencedirect.com/science/article/pii/S0304397500001985)
- 2002: Mackie and Pinto, "Encoding Linear Logic with Interaction Combinators." [url](https://www.sciencedirect.com/science/article/pii/S0890540102931639)
- 2019: Aschieri and Genco, "Par Means Parallel." [url](https://dl.acm.org/doi/10.1145/3371086)

### Term Rewriting System

- 1998: Fernández and Mackie, "Interaction Nets and Term-Rewriting Systems." [url](https://www.sciencedirect.com/science/article/pii/S0304397597000820)
