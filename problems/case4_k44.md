# Case 4: $K_{4,4}$, Finite-Field Constructions, and Empirical Status

## Supplement purpose

The short paper compresses the $K_{4,4}$ case. This file records the additional distinction between proved statements, empirical barriers, and bug-affected computation.

## Extended problem note

The students explored explicit graph constructions intended to avoid $K_{4,4}$ while having many edges. The search involved finite-field and algebraic constructions, where vertices may be represented by field elements and adjacency may be defined by equations.

## What AI helped with

AI helped generate candidate construction families, code fragments for finite-field experiments, and possible explanations for why certain constructions repeatedly failed. However, the case also showed why AI-generated code cannot be treated as neutral infrastructure.

## Field arithmetic audit

A key issue was whether the implementation actually constructed the intended finite field. If a polynomial used as a modulus is reducible, then computations take place in a quotient ring with zero divisors rather than a field. This matters mathematically: adjacency tests, solution counts, and common-neighbourhood behavior may change.

The students therefore marked affected tables as bug-affected and not usable as final evidence. This was a methodological result: code bugs in computational TCS can be mathematical bugs.

## BBK scope correction

Another lesson concerned theorem scope. The students initially considered a broad statement suggesting that a known algebraic obstruction ruled out a large class of finite-field constructions. After checking, the claim had to be narrowed. The supplement records only the narrower verified lesson: specific affine systems explain why a tested family fails, but this does not prove that every finite-field polynomial construction fails.

## Claim labels

- Proved: a narrow common-neighbourhood/affine-system lemma for the checked family.
- Empirical: repeated failures in tested finite-field families.
- Bug-affected: tables depending on invalid field representation.
- Not claimed: universal impossibility of finite-field constructions.

## Educational point

The students learned that experiments are useful only when their mathematical assumptions are correct. They also learned to separate empirical evidence from theorem-level evidence.
