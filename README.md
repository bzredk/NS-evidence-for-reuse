# Evidence for Policy Reuse

What additional evidence is needed to decide whether to reuse a fixed policy in new contexts?

The project began with a distinction between process validity and outcome correctness: an incorrect process can produce a correct answer. Policy reuse raises a further question. Even valid, successful executions can leave the underlying rule ambiguous.

Suppose every demonstrated key matches its lock in both color and shape. A color rule and a shape rule explain the same successes but disagree when the two attributes point to different keys. More demonstrations of the original kind do not resolve that ambiguity.

The collection policy determines what an agent encounters. Memory filtering determines what it retains. We study how these choices affect the evidence available for policy reuse:

- Which rules remain indistinguishable after selection and compression?
- What can retrieval, new labels, or interaction resolve, and at what cost?
- When do shared rules reduce the total cost, including identification and validation?

## Initial study

Use finite classes of task rules over objects and relations. Track rules consistent with the observations and ask whether they justify reusing the fixed policy. Certification depends on the stated rule class, feedback model, target distribution, and error requirement.

New labels update rule estimates and the evidence for reuse; the execution policy stays fixed. Compare methods with the same observations and query access. Count labels, retrieval, environment actions, and computation separately. Test exceptions and uninformative structure as well as shared rules.

## Literature

[Reading notes](literature/README.md) cover 28 references. [BibTeX](references.bib) and the [catalogue](literature/catalog.json) provide citation records, stable identifiers, and reading scope.
