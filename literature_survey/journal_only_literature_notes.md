# Literature Survey Material Suitable for the Journal Version

These notes are too detailed for the short paper but useful for a journal extension.

## FunSearch

- Uses a pretrained LLM plus an evaluator.
- Searches for programs that generate good mathematical objects.
- Maintains a database/population of candidate programs.
- Shows why fast evaluation can make AI useful even when solving is hard.
- Educational connection: students can imitate this at small scale by generating candidate examples and computing exact scores.

## AlphaEvolve / AI as research partner

- Uses LLM-guided search over code or combinatorial structures.
- Emphasizes computationally checkable improvement.
- Relevant to approximation and complexity-theory settings where exact solution is impossible but better constructions or bounds may be found.
- Educational connection: students should learn to distinguish "candidate found" from "theorem proved."

## AI4Math survey themes

- Problem-specific modeling versus general-purpose modeling.
- Construction of examples/counterexamples.
- Retrieval of relevant theorems and lemmas.
- Autoformalization and automated theorem proving.
- Semantic correctness: answering the intended problem, not merely a nearby one.

## Lean and formalization

- Formalization can catch hallucinations.
- Students must already understand the mathematics to formalize it well.
- Learning proof assistants takes substantial time.
- Educational connection: informal verification and professor feedback are realistic first steps for novice TCS researchers.

## Tao-style breadth/depth framing

- AI is strong at breadth: many directions, analogies, summaries, and candidate attempts.
- Human mathematical work requires depth: slow checking, taste, proof boundaries, and knowing when an idea is meaningful.
- Educational connection: students should not use AI to avoid thinking; they should use it to create more things worth thinking about.
