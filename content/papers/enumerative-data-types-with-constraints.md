+++
title = "Enumerative Data Types with Constraints"
date = 2022-10-01
[extra]
venue = "FMCAD 2022"
authors = ["Andrew T. Walter", "David Greve", "Panagiotis Manolios"]
author-pos = 0
dblp_url = "https://dblp.org/rec/conf/fmcad/WalterGM22.html"
abstract = """
Many verification and validation activities involve
reasoning about constraints over complex, hierarchical data
types. For example, distributed protocols are often defined using
state machines that govern the behavior of processes communicating with messages which are hierarchical data types with statedependent constraints and dependencies between component
fields. Fuzzing, analyzing and evaluating implementations of such
protocols requires solving complex queries that pose challenges
to current SMT solvers. Generating fields that satisfy type
constraints is one of the challenges and this can be tackled using
enumerative data types: types that come with an enumerator, an
efficiently computable function from natural numbers to elements
of the type. Enumerative data types were introduced in ACL2s
as a key component of counterexample generation, but they do
not handle constraints such as dependencies between types. We
extend enumerative data types with constraints and show how
this extension enables applications such as hardware-in-the-loop
fuzzing of complex distributed protocols.
"""
file = "papers/enumerative-data-types-with-constraints.pdf"
+++