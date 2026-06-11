# Extended Literature Survey Notes Beyond the Six-Page Paper

The six-page paper compresses the literature review. These notes record the broader context used for the journal version.

## 1. AI as a guide for intuition, not a replacement for proof

A central theme in AI-for-mathematics work is that machine learning may help locate patterns, examples, and promising directions, while proof remains a human or formal-verification task. This is directly aligned with the study: the students did not use AI as a final authority. They used it to generate directions that could be checked.

## 2. Evaluator-guided discovery

FunSearch is important because it pairs a pretrained language model with a systematic evaluator. The model proposes programs; the evaluator scores them; improved candidates are fed back into the search process. The lesson for undergraduate TCS is that AI becomes much more reliable when its outputs are checkable. The students' workflow is an informal analogue: generate examples, compute exact values, compare baselines, and reject unsupported outputs.

AlphaEvolve extends this idea to broader code and combinatorial structures. Its relevance to the project is not that the students used AlphaEvolve, but that modern AI-math successes often depend on an external checking mechanism. This supports the paper's argument that students should learn verification-first workflows.

## 3. Theorem proving and autoformalization

Theorem-proving systems and autoformalization show both promise and limits. Lean-style verification can catch hallucinations, but students need mathematical background before they can formalize difficult results. The tutorial-to-project gap is important: using a proof assistant on examples is different from formalizing new research-level mathematics. For undergraduates, disciplined informal verification may be the realistic first layer before formal methods.

## 4. Aletheia/Gemini-style verification and semi-autonomous discovery

Recent semi-autonomous mathematical discovery work emphasizes candidate generation followed by heavy filtering. The most relevant lesson is that many outputs may be plausible, some may be technically correct but answer the wrong question, and some may rediscover existing literature. This maps closely to the Barber case and to the study's concern with semantic correctness.

## 5. Semantic correctness

A mathematical answer can be wrong even if it is fluent and locally plausible. It may silently change the problem, prove a stronger or weaker statement, cite an adjacent theorem, or satisfy a surface-level similarity rather than the intended meaning. This is why the students were trained to compare definitions and not just conclusions.

## 6. Subconscious plagiarism and rediscovery risk

AI systems trained on large corpora may reproduce or independently rediscover known ideas without clear attribution. Even when a model appears to generate a solution, students must ask whether the result already exists. The Boolean-cube case is a concrete educational example: the valuable answer was not a new proof, but identifying that the problem had an earlier solution.

## 7. Human depth and AI breadth

A useful framing from recent public discussions of AI and mathematics is that AI provides breadth while humans provide depth. AI can rapidly connect terms, suggest analogies, and generate many candidate directions. Human researchers must decide which direction is meaningful, which proof step is justified, and which claim is worth making. In this project, motivating prompts increased breadth, but verification supplied depth.

## 8. Serendipity and over-shortening of literature search

AI summaries can make literature search faster, but they can also remove productive wandering. Traditional literature search sometimes exposes researchers to unexpected adjacent ideas. Students using AI need to preserve some of that randomness by asking for alternative terminology, historical sources, failed approaches, and adjacent formulations rather than only asking for a short answer.

## 9. Why this matters for computing education

Most computing students will encounter AI before they have mature research habits. Therefore, education should not only warn that AI hallucinates. It should teach concrete practices: prompting for examples, checking definitions, asking for counterexamples, comparing to baselines, reading cited sources, and labeling claim status.
