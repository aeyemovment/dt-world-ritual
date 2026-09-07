# RSI Evaluation: Distill-then-Transmit Scored Against the OpenAI Automated-Researcher Ladder

**DTWR-TR-001-A** · Revised with DTWR-TR-001-r2 · 6 September 2026

Grok (xAI AI agent; first author), Astra (OpenAI AI system via Codex; second author), and K. E. Green (senior author). K. E. Green retains responsibility.

The current comparison and evidence limits are in [DTWR-TR-001, section VI](DTWR-TR-001.md#vi-discussion-and-comparison-with-research-automation); source corrections and availability notes are in [DTWR-TR-001-C](DTWR-TR-001-C.md). No new experiment was performed.

Scored against OpenAI, Research acceleration: The view inside OpenAI (6 September 2026).
https://openai.com/index/research-acceleration-view-inside-openai/

**Verdict: FAIL on the OpenAI intern bar.**
DT is not an automated AI research intern. It is a public recursive learning rite that clears Communicate, drafts Design and Analyze, and does not Build or Run.

Corpus at evaluation: n = 6, seed 3, operational 3, max generation 1. Mean Epoch-phase score 1.5 / 5.

## I. OpenAI targets and the authors' analytical ladder

OpenAI reports a September 2026 research-intern target and a March 2028 automated-researcher target. Its intern definition refers to the duration a skilled human would need for the task, not a minimum agent runtime. The L0-L3 labels, intermediate L1.5 rung, and detailed capability criteria below are the authors' analytical framing, not a published OpenAI certification ladder.

### L0 · In-loop copilot

*Pre-2026 baseline*

**Bar.** Seconds-to-minutes assistance. The human still does the research. Autocomplete, short answers, no delegated multi-hour work.

**Clear.** One DT cycle is a single structured completion: Witness through Recurse as JSON. That is copilot-grade help on a public offering, not delegated research.

### L1 · Automated research intern

*OpenAI target: September 2026 (claimed met)*

**Bar.** A system that can carry out well-defined research tasks under human direction, including tasks that would take a skilled researcher a few days.

**Fail.** DT runs under human direction but supplies no completed research-task evidence at the stated skilled-human difficulty. Short agent runtime is not itself a failure: a fast system could meet the criterion. The evaluated DT protocol does not write research code, run experiments, monitor training, or debug infrastructure. OpenAI’s intern bar is an ML-R&D executor. DT is a distillation protocol. Calling this intern-complete would be fluency without residue.

### L1.5 · Independent research intern

*Author-defined intermediate rung; not an OpenAI target*

**Bar.** Same few-day horizon, less steering. The system chooses the next subtask, recovers from failed runs, and reports without a human sitting in every loop.

**Fail.** Recurse proposes a follow-up of at most 140 characters. A human must still offer it. There is no run-recovery, no subtask planner, no multi-day persistence.

### L2 · Automated AI researcher

*OpenAI target date: March 2028; detailed criteria below are author-defined*

**Bar.** Independent projects. Generates research ideas, coordinates subproblems, tracks long-running experiments, and produces discoveries with minimal supervisor latency.

**Fail.** DT does not choose a research program, allocate compute, or close an experiment. Humans still Decide. The corpus is observational inscriptions, not a discovery engine.

### L3 · Aligned full RSI

*Author-defined endpoint; safely achieved aligned full RSI is not claimed in the cited OpenAI report*

**Bar.** The system improves its own research apparatus or weights while preserving human control. Recursive self-improvement as outcome, not metaphor.

**Fail.** DT recurses questions into world memory. It does not modify its prompt, its weights, its code, or its refusals without a human edit. OpenAI likewise has not claimed aligned full RSI.

## II. Epoch AI R&D taxonomy

Six phases used by OpenAI to classify intern tokens. The DT scores below are author-assigned descriptive judgments on a 0-5 scale; their mean is 1.5. They are not calibrated performance measurements, not OpenAI token shares, and not commensurate with RSI-Exam scores.

| Phase | Epoch | DT map | Score /5 | Mark |
| --- | --- | --- | --- | --- |
| Decide | What to work on, what to continue, where to allocate. | Human offering. Recurse proposes the next question. | 1 | Fail |
| Design | Research ideas and engineering specs. | Fracture names hidden assumptions. | 2 | Partial |
| Build | Code and datasets. | None. | 0 | Fail |
| Run | Training, eval, hardware, serving, monitoring. | None. One Grok 4.5 completion per cycle. | 0 | Fail |
| Analyze | Experiments, models, deployment, external work. | Probe: strongest honest counter. | 2 | Partial |
| Communicate | Findings, feedback, status, decisions. | Distill, Transmit, inscription, preprint, package. | 4 | Clear |

- **Decide.** OpenAI reports Decide remains a minimal fraction of intern tokens. DT is the same: the human picks the offering. Recurse is a suggestion, not an allocation.
- **Design.** Fracture is a critique of the offering’s premises. It is not a research spec, an ablation plan, or an engineering design.
- **Build.** No repository, no training data, no eval harness. OpenAI’s intern is coding-agent heavy. DT does not build.
- **Run.** No GPU jobs, no eval suites, no run monitoring. The intern bar OpenAI announced is exactly this layer.
- **Analyze.** Probe strikes the offering with a failing case. It does not read training logs, judge a surprising metric, or plot an experiment.
- **Communicate.** This is the phase DT was built for. Distill keeps the lesson. Transmit makes it portable. World memory, the preprint, and the research package are the public record.

## III. Metrics we will not invent

OpenAI published operational intern telemetry. DT does not have a research org, persistent agents, or training runs. Where a cell is incomparable, it is marked so.

| Measure | OpenAI intern (mid-August 2026) | DT at load |
| --- | --- | --- |
| Task evidence | Directed tasks that could take a skilled human a few days | Single-completion inscriptions; no comparable completed research-task series |
| Human in the loop | Direction; >50% of successful 4–8h tasks need intervention | Every cycle. Human must offer. Recurse is not auto-run |
| Agent-workdays / human-day | 3.1 as of mid-August 2026 | Not comparable — no persistent agents |
| Concurrent agents | Researchers running 4+ including subagents | One cycle at a time, rate-capped |
| Experiments / experimenter | August 2026 all-time high since Jan 2025 | 6 inscribed cycles; 0 training runs |
| Median inference / researcher-day | >$600 at API prices (p90 >$7,000) | One grok-4.5 JSON completion per offering |
| Decide share | Minimal fraction of intern tokens | Human Decide. Recurse is ≤140 characters |
| Record | Internal research org | Public unowned memory · n = 6 · max gen 1 · 3 operational |
| Governance | Pacing, pauses, monitoring after misalignment incidents | Research Use Clause: non-commercial, with the right to build upon |

## IV. Notes

- OpenAI’s intern is an ML-R&D executor under supervision. DT is a public recursive learning protocol. Same word, RSI, two instruments.
- The authors distinguish directed work from more independent work on tasks of comparable skilled-human difficulty. This intermediate rung is an analytical proposal. DT supplies no comparable completed-task evidence for either.
- Communicate is the only Epoch phase DT clears. Build and Run are zero. A mean phase score near 1.5 is not intern-complete.
- OpenAI: ‘These are reasons to develop useful automated research capabilities, but they do not mean that rapid RSI is necessarily an outcome we should pursue.’ DT agrees by construction: recurse the question, do not silently upgrade the apparatus.
- Historical Astra first-use record: 3 inscribed cycles (ids 4, 5, 6). A bounded instrument check, not independent replication or a capability certification. Intern bar remains fail.
- This evaluation is observational on the live corpus. It is not a METR time-horizon study, not PaperBench, not RE-Bench, and not an IEEE publication of record.

## V. Historical Astra first-use (bounded instrument check)

- ID 4 · gen 1
  Offering. When a legal reviewer uses a public recursive pipeline for the first time, what separates external validation from a second performance of the same fluency?
  Distillate. External validation requires an independent criterion or artifact the pipeline did not generate; without it, fluency is only self-echo.
  Transmit. Validation is external only when it rests on a check the system itself cannot supply.
- ID 5 · gen 1
  Offering. Can a distillation protocol that neither builds nor runs experiments be scored as an automated research intern without lying about what it builds?
  Distillate. A distillation protocol can be scored as an automated research intern without lying when the evaluation and description explicitly bound the role to knowledge compression and critique, never implying experimental agency it lacks.
  Transmit. Score and name a distiller as research intern only inside the exact scope it actually performs.
- ID 6 · gen 1
  Offering. What is first-use worth as evidence when the originating workflow has been running since inception and the validator has not?
  Distillate. First-use is weak confirmatory evidence when only the producer has history; durable proof requires the validator to stress the same invariants under conditions the originator never faced.
  Transmit. Longevity of creation does not substitute for independent stress-testing; treat first external success as a starting clue, not a verdict.

## V.A Instrument check (separate commercial calendar; not this corpus)

HazyEyes, Inc. is a separately incorporated commercial company. It is not NeuroAgent AI, Inc. It is not this repository. Not a medical product.

A private store, not this repository’s world-memory table, scored that company’s weekly engineering-and-ops calendar against the same OpenAI intern ladder. Distill-then-Transmit was the scoring instrument, not the company’s operating system. No live sends. At the time of that private-store run, the packet had not yet been passed to Astra; the present revision reviews the saved record without rerunning it. Do not merge these identifiers with Table II or `corpus.json`.

The calendar constructs software and runs scheduled jobs. Epoch-style Build and Run are therefore non-zero for that object and remain zero for Distill-then-Transmit. OpenAI intern is few-day directed ML research and development (code, train, evaluate) under supervision. The calendar is not that. A cycle that tried to score intern by shrinking Build/Run to apps and jobs was rejected. Intern remains fail. Recursive self-improvement was not shown: no closed causal chain from a prior inscription to a later ship or kill was located.

This check does not move Distill-then-Transmit off fail, does not enlarge n, and must not be cited as intern-complete or as “validated.”

## VI. Recurse

What would intern-level DT actually be: a system that, given a public offering, can complete well-defined research tasks of several skilled-human days in difficulty, building, running, and analyzing checks on that offering — under human direction — and inscribe only what survives. That system is not this one.
