# Five Additional Results and Verification Details Not Included in the Short Paper

This file lists five supplementary results/details. They are not presented as new theorems solving the original open problems. Their value is that they show how the students' AI-assisted workflow produced checkable artifacts, rejected false claims, or clarified the boundary between computation and proof.

## 1. Complement-counting representation in sampled independence

The short paper reports exact candidate values, but the supplement records the representational move behind the computation. Passing to the complement changed an independence-number constraint in a graph $G$ into a counting problem over a triangle-free graph $H$. This made the expected sampled independence number easier to enumerate because independent sets in $G[S]$ correspond to clique-free or edge-structured configurations in the complement. The important educational result is that students learned to change representation before computing.

Status: **verified method for the checked examples**, not a proof of global optimality.

## 2. Vocabulary mapping in the Barber case

The short paper states that the Boolean-cube problem was already solved. The supplement records the mechanism: the students compared the notation in the open-problem note with Barber's terminology. The key mapping involved balanced independent sets, the even/odd bipartition of the cube, and the extremal size formula. The students learned that novelty checking is not keyword matching; it requires comparing definitions across sources.

Status: **literature-status correction**, manually checked against the source.

## 3. Rejected Borsuk proof step via $C_5$

The Borsuk case produced an important negative result: a proof sketch relied on a false local-to-global statement about critical graph neighbourhoods. Testing $C_5$ showed the issue immediately. $C_5$ is $3$-critical, but each vertex neighbourhood is independent. Therefore, local neighbourhood colourability did not supply the global colouring conclusion needed by the proof sketch.

Status: **false claim rejected by counterexample**.

## 4. Finite-field audit in the $K_{4,4}$ case

The $K_{4,4}$ case showed that code is part of the mathematical object. A finite-field construction used a polynomial that did not actually define the intended field in one tested setting. When $t^4+1$ factors over $
umpy{F}_5$ or is otherwise not suitable as the assumed irreducible modulus, computations may occur in a ring with zero divisors rather than a field. This changes the meaning of the simulation. The affected tables were therefore marked for rerun.

Status: **bug-affected empirical evidence**, not final data.

## 5. Graphic TSP: exact compression preferred over approximation overclaim

The Graphic TSP case produced a precise structural artifact: degree-2 threads can be suppressed, a forced baseline $F$ separated, and the remaining parity/connectivity task represented as $
Gamma^*$. The useful statement is the exact decomposition idea, not a universal improvement over the $7/5$ barrier. The students also tested why a connectivity LP alone can miss parity constraints.

Status: **verified structural reformulation**, not a claimed new approximation ratio.

## Summary

These five details support the educational claim of the paper: AI was valuable when it produced objects that could be checked, compared, or rejected. It was dangerous when fluent proof prose was treated as evidence.
