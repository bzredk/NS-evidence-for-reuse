# Evidence for Skill Reuse

When does an agent's experience justify reusing a learned skill?

The project began with a distinction between process validity and outcome correctness: an incorrect process can produce a correct answer. Skill learning raises a further question. Even valid, successful executions can leave the underlying rule ambiguous.

Suppose every demonstrated key matches its lock in both color and shape. A color rule and a shape rule explain the same successes but disagree when the two attributes point to different keys. More demonstrations of the original kind do not resolve that ambiguity.

An agent's policy determines what it encounters. Memory filtering determines what it retains. We study how these choices affect the evidence available for learning and reuse:

- Which rules remain indistinguishable after selection and compression?
- What can retrieval, new labels, or interaction resolve, and at what cost?
- When can shared mechanisms reduce that cost after learning and validation are counted?

## Initial study

Use finite rule classes and programs over objects and relations. Maintain the rules consistent with the observations and identify where they disagree on a reuse decision. Certification depends on the stated rule class, feedback model, target distribution, and error requirement.

Hold the execution policy fixed to measure the value of evidence. Compare methods with the same observations and query access. Count labels, retrieval, environment actions, and computation separately. Test exceptions and uninformative structure as well as shared rules.

## Literature

[Reading notes](literature/README.md) cover 28 references. [BibTeX](references.bib) and the [catalogue](literature/catalog.json) provide citation records, stable identifiers, and reading scope.
