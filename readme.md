Isabelle theory files for paper

_A Formal Foundation of the CMP Method for Parameterized Verification_

The main theorems proved are:
* ```CMP.thy```:
  - ```SymLemma'```: symmetry reduction.
  - ```symParamStrengthenRule2```: correctness of strengthening.
  - ```absRuleSim```: correctness of abstraction.
  - ```CMP```: connects all results to show that the parameterized protocol respects the invariant if the abstract protocol does.
* ```nMutual.thy``` and ```nGerman.thy```:
  - ```absProtSim```: correctness of parameterized protocol in the mutual exclusion and German examples. Assumption ```a4``` is to be verified by model checking.
