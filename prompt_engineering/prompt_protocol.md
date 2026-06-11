# Prompt Engineering Protocol Used in the Study

The students did not use AI mainly by asking one-shot questions such as "solve this open problem." The productive workflow was iterative and verification-oriented. The prompts below are generalized and anonymized; they are not raw transcripts.

## 1. Definition-first prompting

The first stage was to slow the model down and force it to explain the object before attempting a result.

Example pattern:

> Explain the problem from the beginning. Define every object, give the smallest nontrivial examples, and do not try to prove the open statement yet.

Purpose: this converted unfamiliar topics into workable objects. In the five cases, this helped with sampled induced subgraphs, balanced independent sets in the cube, diameter graphs, finite-field constructions, and Graphic TSP terminology.

## 2. Baseline-and-candidate prompting

Once a problem had known bounds or obvious constructions, the students asked the model to compare the baseline with explicit alternatives.

Example pattern:

> Do not search for a proof first. Compare this baseline construction with nearby non-clique constructions. Give exact values if possible, and separate computed values from conjectures.

Purpose: this was crucial in the sampled-independence case. The students moved from vague extremal intuition to exact comparison, for example baseline clique unions versus blow-up cycle candidates.

## 3. Adversarial prompting

When the model gave a proof sketch, the students often challenged the weakest step.

Example pattern:

> Identify the exact theorem used in this step. Is it actually true? Try to find the smallest counterexample.

Purpose: this exposed false proof steps in the Borsuk case. Instead of accepting fluent proof prose, the students tested a local critical-graph claim and found a simple counterexample.

## 4. Literature-status prompting

For problems stated as open in notes or reports, the students asked the model not to assume the status was still current.

Example pattern:

> Do not assume this is still open. Search for older terminology, equivalent formulations, and papers that might prove the same statement with different notation.

Purpose: this redirected the Boolean-cube case from proof invention to literature tracing and led to the Barber theorem match.

## 5. Motivation-style prompting

Some of the most useful prompts were not technical in the narrow sense. The students pushed the model to search more broadly.

Example pattern:

> I do not think this is your maximum. Try a different direction. Do not stay inside the first proof idea. Look for a construction, a counterexample, or a reformulation.

Purpose: such prompts did not verify anything. They functioned as search-control instructions. They increased breadth, after which the students still had to decide what was correct.

## 6. Claim-label prompting

Every nontrivial output was eventually forced into a label.

Example pattern:

> Put each claim in one of these categories: proved, computed exactly, empirical, plausible but unchecked, false, or future work. Do not mix them.

Purpose: this became the main protection against overclaiming. It also made professor feedback more efficient, because the expert did not have to guess which claims the students believed.

## 7. Student learning from prompting

The key learning outcome was not simply "better prompts." The students learned that prompting is a research practice: ask for examples before theorems, ask for refutations before confidence, ask for older terminology before novelty, and ask for exact computations before patterns.
