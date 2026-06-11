# Case 3: Borsuk, Rejected Proofs, and Counterexample Discipline

## Supplement purpose

The short paper mentions the Borsuk case as a verification-centered case. This file records the additional proof-audit lesson.

## Extended problem note

The relevant instance concerns Borsuk's partition problem in dimension four. In graph language, a finite set of points gives a diameter graph, and the desired partition corresponds to a colouring statement. The students used AI to learn the relationship between diameter graphs, chromatic number, regular simplex intuition, and known dimensions where the conjecture is proved or disproved.

## AI-generated proof sketch

AI produced a plausible proof strategy using neighbourhoods in critical graphs. The sketch suggested that a local colouring property of neighbourhoods would allow a global colouring argument.

## Verification episode

The students did not accept the proof. They asked for the exact theorem behind the neighbourhood step and then searched for the smallest counterexample. The graph $C_5$ already exposes the false step: it is $3$-critical, but every vertex neighbourhood is independent. Therefore, local neighbourhood simplicity does not yield the global colouring conclusion used in the sketch.

## Additional result not in the short paper

The case produced a precise rejected lemma: local neighbourhood colourability is insufficient for the intended global colouring. The failure was not vague; it had a one-line counterexample.

## Educational point

The students learned that rejecting a proof is not failure. A rejected proof can locate the exact gap and prevent a false theorem from entering the paper. This is one of the clearest examples of verification as learning.
