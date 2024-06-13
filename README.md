# SV-24SS
Notes for the lecture Software Verification

Gitlab Page: [click](https://gitlab2.cip.ifi.lmu.de/sosy-lab/sv-notebooks-ss24)

#### 1. Predicate analysis
##### 1.1 Predicate abstraction
reading [this paper](https://github.com/Lingyin-Luo/SV-SS24/blob/main/reading%20materials/predicate-analysis-01.pdf) section 2B



#### 2. CEGAR
##### [Explicite-state model checking based on CEGAR and Interpolation](https://link.springer.com/chapter/10.1007/978-3-642-37057-1_11)
counterexample guided  abstraction refinement
> a technique for automatic stepweise refinement for an abstract model

based on
   * a precision: the current abstraction level
   * a feasibility check: if there exits a concrete error path
   * a refinement procedure: 1. takes an infeasible error path  2. extracts a precision which suffices to instrcut the expolration algorithm not to expolre the same path again
