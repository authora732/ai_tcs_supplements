# Case 5: Graphic TSP, Thread Compression, and Resisting Overclaiming

## Supplement purpose

The short paper reports the final structural artifact. This file records the additional restraint: several attractive approximation claims were rejected.

## Extended problem note

Graphic TSP asks for a shortest closed walk visiting all vertices of an unweighted connected graph. It can be studied through connected Eulerian multigraphs and approximation ratios. The students were interested in whether AI-assisted reasoning could help around known barriers such as the $7/5$-type context.

## What AI helped with

AI helped compare different formulations: spanning-tree views, parity correction, LP relaxations, and structural simplifications. The most useful direction was not a new approximation ratio, but an exact compression for degree-2 threads.

## Additional structural artifact

The students isolated forced contributions from degree-2 threads into a baseline $F$ and represented the remaining parity/connectivity task as a smaller core problem, denoted here by $\Gamma^*$. The useful identity is an exact decomposition idea:

$$\mathrm{OPT}_{\mathrm{GTSP}}(G)=F+\Gamma^*.$$

The point of the supplement is not that this beats known approximation ratios. The point is that the structural statement is checkable.

## Rejected directions

Several hybrid approximation claims sounded promising but were not retained. In particular, connectivity-only LP reasoning was not enough because parity constraints can remain hidden until a counterexample is tested. The students learned that a precise partial theorem is stronger than a dramatic unsupported claim.

## Claim labels

- Verified: exact thread-state compression under the stated setup.
- Rejected: broad claims of a universal improvement over the known barrier.
- Future work: whether the compressed formulation can support a new rounding or approximation argument.

## Educational point

This case best illustrates research maturity. The students wanted a stronger result, but the verified result was narrower. The paper keeps the narrower result because it is inspectable by another researcher.
