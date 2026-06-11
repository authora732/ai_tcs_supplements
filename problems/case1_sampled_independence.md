# Case 1: Sampled Independence and Exact Candidate Checking

## Supplement purpose

The short paper reports the main exact examples. This file records the additional workflow: how the students moved from a direct expectation question to a representation that made exact checking easier.

## Extended problem note

The problem asks about the expected independence number of a random sampled induced subgraph under a global independence constraint. For a graph $G$ on $n$ vertices with $
alpha(G)=an$, one studies the expectation of $
alpha(G[S])$ when $S$ is sampled from the vertex set. Obvious baseline constructions come from unions of cliques, but the goal of exploration was to test whether less obvious graphs can improve the expectation.

## Additional workflow detail

The productive prompt was not "prove the optimum." It was closer to: compare the baseline against explicit alternatives and give exact values. This shifted the task from theorem proving to exact enumeration.

The students then learned a standard theoretical move: pass to the complement. In the relevant cases, the complement $H=\overline{G}$ made the constraint easier to inspect. Instead of reasoning directly about independent sets in $G$, the students counted structures in $H$ and checked sampled induced subgraphs exactly.

## Checked artifacts

- Baseline for $a=1/5$: $2K_5$, exact value $31/16$.
- Candidate: $C_5[K_2]$, exact value $993/512$.
- Later candidates for $a=1/6$ and $a=1/7$ followed the same pattern: compute exactly first, compare to the correct clique-union baseline second, and only then discuss whether a structural pattern might exist.
- A screenshot-based candidate was rejected because visual plausibility was not enough; the graph had to be reconstructed and recomputed.

## What is not claimed

The supplement does not claim global optimality. It records exact examples, a useful representation, and a verification habit.

## Educational point

The students learned that a small exact improvement can be more valuable than a broad unsupported conjecture. They also learned that representation choice is part of theory work.
