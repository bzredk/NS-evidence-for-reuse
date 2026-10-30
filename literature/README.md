# Literature

28 references on skill learning, evidence acquisition, and reuse. [BibTeX](../references.bib) / [Catalogue](catalog.json).

## Skill representations

| Reference | Note | Identifier |
|---|---|---|
| Human-level concept learning through probabilistic program induction<br>Lake et al., 2015. | Compositional programs and learned priors for concept learning. Experiments use handwritten characters. | DOI: [10.1126/science.aab3050](https://doi.org/10.1126/science.aab3050) |
| DreamCoder: bootstrapping inductive program synthesis with wake-sleep library learning<br>Ellis et al., 2021. | Learns reusable program libraries and a search guide. Library construction has a cost; compression does not replace missing evidence. | DOI: [10.1145/3453483.3454080](https://doi.org/10.1145/3453483.3454080) |
| PDSketch: Integrated Domain Programming, Learning, and Planning<br>Mao et al., 2022. | Uses supplied relational structure to connect model learning and planning. Separate learned grounding from given vocabulary and constraints. | [Official record](https://pdsketch.csail.mit.edu/) |

## Logged evidence and additional queries

| Reference | Note | Identifier |
|---|---|---|
| Active Learning with Logged Data<br>Yan et al., 2018. | Uses logged coverage to guide additional label queries. Assumes known logging propensities and visible unlabeled contexts. | [Official record](https://proceedings.mlr.press/v80/yan18a.html) |
| Optimal Best-Arm Identification in Bandits with Access to Offline Data<br>Agrawal et al., 2023. | Characterizes additional identification samples given offline arm counts. Guarantees are joint over historical and online randomness. | [arXiv:2306.09048v1](https://arxiv.org/abs/2306.09048v1) |
| Best Arm Identification with Possibly Biased Offline Data<br>Yang et al., 2025. | Combines offline and online observations with bias correction. Requires valid bias bounds. | [Official record](https://proceedings.mlr.press/v286/yang25b.html) |
| Active Offline Policy Selection<br>Konyushkova et al., 2021. | Shares return estimates across fixed policies through behavioral similarity. Its objective is return-based policy selection. | [Official record](https://proceedings.neurips.cc/paper_files/paper/2021/hash/cec2346566ba8ecd04bfd992fd193fb3-Abstract.html) |

## Decision targets and selective execution

| Reference | Note | Identifier |
|---|---|---|
| Near Optimal Bayesian Active Learning for Decision Making<br>Javdani et al., 2014. | Stops when remaining hypotheses share a valid decision. Approximation guarantees require the stated testing and structural assumptions. | [Official record](https://proceedings.mlr.press/v33/javdani14.html) |
| Learning When to Stop: Selective Imitation Learning Under Arbitrary Dynamics Shift<br>Goel et al., 2026. | Learns stopping rules under dynamics shift and permits expert handoff. Requires source action labels and target expert state trajectories. | [arXiv:2605.09183v2](https://arxiv.org/abs/2605.09183v2) |
| Self-Certification of Representation Adequacy: Sequential Certification at Minimum Task Loss<br>Huang, 2026. | Analyzes sequential certification costs in specified finite environment classes. Requires known feedback models and identifiability conditions. | [arXiv:2608.02267v2](https://arxiv.org/abs/2608.02267v2) |
| Testing Noise Assumptions of Learning Algorithms<br>Goel et al., 2026. | Tests learning assumptions before accepting a model. Guarantees depend on the hypothesis class and noise model. | [Official record](https://proceedings.mlr.press/v336/goel26a.html) |
| Tolerant Algorithms for Learning with Arbitrary Covariate Shift<br>Goel et al., 2024. | Studies selective learning under covariate shift. Changing environment dynamics requires a separate analysis. | [arXiv:2406.02742](https://arxiv.org/abs/2406.02742) |

## Relational action models and exploration

| Reference | Note | Identifier |
|---|---|---|
| Efficient, Safe, and Probably Approximately Complete Learning of Action Models<br>Stern and Juba, 2017. | Learns conservative action models from successful transitions. Approximate completeness concerns the sampling distribution. | DOI: [10.24963/ijcai.2017/615](https://doi.org/10.24963/ijcai.2017/615) |
| Safe Learning of Lifted Action Models<br>Juba et al., 2021. | Shares action rules across object bindings. SAM and E-SAM impose different binding conditions. | [Official record](https://proceedings.kr.org/2021/36/) |
| Stochastic Safe Action Model Learning<br>Deng and Juba, 2026. | Studies safe learning with stochastic action effects. Assumes finite effect support and specific structural conditions. | [Official record](https://proceedings.mlr.press/v336/deng26a.html) |
| Asking the Right Questions: Learning Interpretable Action Models Through Query Answering<br>Verma et al., 2021. | Uses distinguishing plans to identify interpretable action models. Query execution and feedback access must be specified. | DOI: [10.1609/aaai.v35i13.17428](https://doi.org/10.1609/aaai.v35i13.17428) |
| Active Learning of Abstract Plan Feasibility<br>Noseworthy et al., 2021. | Uses active robot experiments to learn abstract plan feasibility. Accounts for partial execution and test reachability. | DOI: [10.15607/RSS.2021.XVII.043](https://doi.org/10.15607/RSS.2021.XVII.043) |
| Embodied Active Learning of Relational State Abstractions for Bilevel Planning<br>Li and Silver, 2023. | Actively learns relational abstractions for bilevel planning. Assumes a vocabulary, simulator, and noiseless labels. | [Official record](https://proceedings.mlr.press/v232/li23a.html) |
| GLIB: Efficient Exploration for Relational Model-Based Reinforcement Learning via Goal-Literal Babbling<br>Chitnis et al., 2021. | Explores relational models by planning toward sampled goal literals. Convergence requires the stated exploration and environment conditions. | DOI: [10.1609/aaai.v35i13.17400](https://doi.org/10.1609/aaai.v35i13.17400) |

## Memory selection and compression

| Reference | Note | Identifier |
|---|---|---|
| The Trap of Trajectory: Towards Understanding and Mitigating Spurious Correlations in Agentic Memory<br>Tang et al., 2026. | Studies spurious correlations in agent memory, including outcome-filter bypass. Retrieval alone cannot supply unobserved causal evidence. | [arXiv:2605.09330v1](https://arxiv.org/abs/2605.09330v1) |
| Remember the Decision, Not the Description: A Rate-Distortion Framework for Agent Memory<br>Zou et al., 2026. | Allocates memory according to decision loss and includes certification exploration. Its objective is regret under a memory budget. | [arXiv:2605.10870v1](https://arxiv.org/abs/2605.10870v1) |

## Feedback and imitation baselines

| Reference | Note | Identifier |
|---|---|---|
| A Reduction of Imitation Learning and Structured Prediction to No-Regret Online Learning<br>Ross et al., 2011. | Learns from expert labels on states visited by the learner. Policy updates change execution ability. | [Official record](https://proceedings.mlr.press/v15/ross11a.html) |
| Active Imitation Learning: Formal and Practical Reductions to I.I.D. Learning<br>Judah et al., 2014. | Reduces expert queries through active state selection. The reductions rely on simulator and learning-oracle assumptions. | [Official record](https://www.jmlr.org/papers/v15/judah14a.html) |
| Query-Efficient Imitation Learning for End-to-End Simulated Driving<br>Zhang and Cho, 2017. | Uses a learned action-deviation classifier to select expert queries and control. Classifier accuracy alone does not certify reuse under arbitrary shift. | DOI: [10.1609/aaai.v31i1.10857](https://doi.org/10.1609/aaai.v31i1.10857) |

## Learning-theory background

| Reference | Note | Identifier |
|---|---|---|
| Efficient noise-tolerant learning from statistical queries<br>Kearns, 1998. | Separates sample, query, and computational requirements for learning. STAT results apply to statistical-query access. | DOI: [10.1145/293347.293351](https://doi.org/10.1145/293347.293351) |
| Queries and Concept Learning<br>Angluin, 1988. | Distinguishes membership, equivalence, and counterexample queries. These interfaces provide different feedback and are not interchangeable. | DOI: [10.1023/a:1022821128753](https://doi.org/10.1023/a:1022821128753) |
| An Introduction to Computational Learning Theory<br>Kearns and Vazirani, 1994. | Background on PAC learning, query access, and computational constraints. Bounds require the assumptions of the specific learning problem. | ISBN: 9780262111935. [Publisher](https://mitpress.mit.edu/9780262111935/an-introduction-to-computational-learning-theory/) |
| Language Generation in the Limit<br>Kleinberg and Mullainathan, 2024. | Separates language generation from complete identification in the limit. The result supplies no finite-sample bound for action learning. | [Official record](https://proceedings.neurips.cc/paper_files/paper/2024/hash/7988e9b3876ad689e921ce05d711442f-Abstract-Conference.html) |

Reading scopes and check dates are in the [catalogue](catalog.json). Prior reading covers selected sections of 22 papers and abstracts or metadata for six. [Identifier notes](identifier_updates.json) record publication updates, including one author-order discrepancy.
