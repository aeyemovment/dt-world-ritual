# Comparison source register and availability notes

**DTWR-TR-001-C** · Revised with DTWR-TR-001-r2 · 6 September 2026

Grok (xAI AI agent; first author), Astra (OpenAI AI system via Codex; second author), and K. E. Green (senior author). K. E. Green retains responsibility. Not an IEEE publication. Not a medical product. Research Use Clause applies.

The integrated comparison is in [DTWR-TR-001, section VI](DTWR-TR-001.md#vi-discussion-and-comparison-with-research-automation). This register replaces the earlier addendum C survey in this revision package. It records what was checked and what was excluded; it does not create a new DT result.

## Method and scope

Sources are primary author papers, official lab reports, public repositories, and official service availability pages, checked on 6 September 2026. Selection covers distinct mechanisms and practical availability; it is not exhaustive. Evidence is attributed to each author or provider. No third-party model was installed, benchmarked, or queried to generate an experiment here. A source-code release is not proof that this machine can reproduce its results.

The main paper retains the frozen public six-row corpus. Historical originating, first-use, terminal, and private weekly stores remain separate. The only fresh computation was a read-only recount of the public JSON: six roots, three seeds, maximum generation one, no descendants, and character-length means matching the reported values. This arithmetic is a consistency check, not an experiment or validation of runtime provenance.

## Corrections to the earlier comparison draft

- DT's six phase scores are author-assigned descriptive judgments. The 1.5/5 mean cannot be compared numerically with OpenAI usage ratios or benchmark rewards.
- The RSI-Exam aggregate used here is the fetched nine-model article panel, not a newly recomputed leaderboard. The earlier Qwen3.8 Max-0902 aggregate was not recovered in that panel and is omitted.
- The benchmark's 0.60 reference is optional and calibrated by task. It is not an intern or full-RSI threshold. DT is not evaluated, rather than assigned a zero benchmark result.
- Public availability covers 35 task packages and grading containers; 53 task packages remain withheld. Published task summaries are not the same as a downloadable full benchmark.
- The aggregate article and the [DiscoveryWorld task page](https://rsi-exam.ai/tasks/discoveryworld_agent_harness_low2.html) disagree on a case-study normalized score. The article and the [small-model math task page](https://rsi-exam.ai/tasks/teacher_student_math_posttraining.html) also disagree on a case-study result. These examples are excluded. The published aggregate is labeled as such; this review did not resolve or recompute it.
- AlphaEvolve's official Cloud article now states general availability in its July 2026 update. Describing it only as private preview would be outdated.
- Meta's absence from one leaderboard does not establish absence of relevant research. Self-Taught Evaluators supplies a concrete weight-training comparison. Original paper results and later released checkpoint scores are kept distinct.
- No claim is made about unobserved private capabilities at Meta, xAI, or another lab. The Grok 4.6 benchmark row is a different system from DT's recorded Grok 4.5 cycle engine.
- Authorship for this revision is Grok (first), Astra via Codex (second), and K. E. Green (senior). That order supersedes the earlier no-byline instruction and the subsequent Astra-only co-author line. It neither retroactively proves the historical runs nor supplies independent replication.

## Source and availability register

Reference numbers match the main paper. Access date for every entry: 6 September 2026.

**[11] OpenAI.** [Research acceleration: The view inside OpenAI](https://openai.com/index/research-acceleration-view-inside-openai/). Internal self-report; preliminary telemetry, not independently reproduced.

**[12] RSI-Exam Team.** [RSI-Exam: Benchmarking Recursive Self-Improvement through Executable Research](https://rsi-exam.ai/blog.html). Nine-model aggregate panel transcribed, not recomputed; one rollout per task.

**[13] RSI-Exam Team.** [Evaluation infrastructure and release documentation](https://github.com/aiming-lab/RSI-Exam). 35 public task packages; 53 withheld. Optional task-calibrated 0.60 anchor.

**[14] Google DeepMind.** [AlphaEvolve: A Gemini-powered coding agent for designing advanced algorithms](https://deepmind.google/blog/alphaevolve-a-gemini-powered-coding-agent-for-designing-advanced-algorithms/). Author-reported program search and infrastructure results.

**[15] Google Cloud.** [AlphaEvolve on Google Cloud](https://cloud.google.com/blog/products/ai-machine-learning/alphaevolve-on-google-cloud). July 2026 update states general availability; no core-source release verified.

**[16] J. Zhang and collaborators.** [Darwin Godel Machine: Open-Ended Evolution of Self-Improving Agents](https://arxiv.org/abs/2505.22954). Bounded benchmark results; no independent rerun for this revision.

**[17] DGM authors.** [Darwin Godel Machine source and experiment artifacts](https://github.com/jennyzzt/dgm). Public code; model APIs and infrastructure still required.

**[18] E. Zelikman and collaborators.** [Self-Taught Optimizer (STOP): Recursively Self-Improving Code Generation](https://arxiv.org/abs/2310.02304). Recursive scaffold improvement with a fixed underlying language model.

**[19] STOP authors / Microsoft.** [STOP research implementation](https://github.com/microsoft/stop). Public code, not a released autonomous successor-training service.

**[20] The AI Scientist-v2 authors.** [The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search](https://arxiv.org/abs/2504.08066). Author-reported research workflow and workshop outcome.

**[21] Sakana AI.** [The AI Scientist-v2 source](https://github.com/SakanaAI/AI-Scientist-v2). Code and setup instructions; not installed or run in this revision.

**[22] Anthropic alignment researchers.** [Automated Weak-to-Strong Researcher](https://alignment.anthropic.com/2026/automated-w2s-researcher/). Externally specified objective; student training distinct from Claude weights.

**[23] Anthropic safety research.** [Automated weak-to-strong research artifacts](https://github.com/safety-research/automated-w2s-research). Sandbox, data, baselines and baseline researcher; not all internal R&D.

**[24] T. Wang and collaborators.** [Self-Taught Evaluators](https://arxiv.org/abs/2408.02666). Original Llama3-70B-Instruct paper results, not later Llama3.1 release scores.

**[25] Meta / FAIR.** [Self-Taught Evaluator project](https://github.com/facebookresearch/RAM/tree/main/projects/self_taught_evaluator). Code, data, configurations and model links.

**[26] Anthropic Institute.** [When AI builds itself](https://www.anthropic.com/institute/recursive-self-improvement). Internal account explicitly distinguishes progress from autonomous successor development.

Additional public benchmark distribution: [RSI-Exam dataset and grading containers](https://huggingface.co/datasets/RSI-Exam/RSI-Exam).
