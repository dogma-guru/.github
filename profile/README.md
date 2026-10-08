# Dogma Guru

Dogma Guru is the research label of Dogma LLC, New York. Its public work is open-source tooling for measuring what quantum processors actually do, with the rules fixed before each run and every result reproducible from the archived raw counts.

## Manacitra

[**Manacitra**](https://github.com/dogma-guru/manacitra) maps a quantum processor's qubit pairs by how much of a small, known signal each pair keeps, tests that map against the vendor's published figures under rules that can declare it redundant, and uses it to choose pairs for a job. The name is Sanskrit *māna* (measure) and *citra* (picture): a measured picture of a chip.

Results so far come from IBM and Rigetti processors, with the counts, the analyses and the compiled programs archived in the repository. Code is Apache 2.0; data and documentation are CC BY 4.0.

## How the results are made

Every result comes from a kickoff: a written brief fixed before the run, with the question, the circuits, the shot counts, the analysis and the verdict rule with every threshold. Predictions are sealed by hash before any data exist. Each hardware submission is approved once and never resubmitted. The hand-back is recomputed with separate code, and a scorecard marks every prediction. A rule changes only by a dated amendment, and the original rule is still reported beside the new one.

What would discredit a result is written down before the run, and a null outcome is published the same way as a positive one.

## Contact

Developed by Dogma Guru. Issues and discussions on the repositories are the best way to reach the project.
