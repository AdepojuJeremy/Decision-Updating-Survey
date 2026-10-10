# Datasets and benchmarks

This is a qualitative catalogue of documented tasks. Evidence-type assignments and direct/component distinctions are the survey authors’ synthesis, not labels attributed to the original benchmark authors. No numerical results are added here.

| Resource | Evaluation structure | What it captures | Coverage limitation |
| --- | --- | --- | --- |
| [Belief-R](https://aclanthology.org/2024.emnlp-main.586/) | Direct: paired premise additions | Revision and preservation | Does not establish downstream action consistency. |
| [ClashEval](https://arxiv.org/abs/2404.10198) | Direct: prior answer versus retrieved context | Corrective use and resistance to incorrect evidence | Controlled perturbations do not cover all source-reliability judgments. |
| [WikiContradict](https://arxiv.org/abs/2406.13805) | Component: conflicting passages | Representation of disagreement | No prior model commitment is required in every setting. |
| [Flex-TravelPlanner](https://arxiv.org/abs/2506.04649) | Direct in sequential setting; component in priority setting | Adaptation and priority-sensitive constraint handling | Different settings must retain separate interpretations. |
| [TravelPlanner](https://arxiv.org/abs/2402.01622) | Component: static planning | Feasibility and multiple requirements | A feasible final plan does not establish appropriate revision. |
| [FollowBench](https://aclanthology.org/2024.acl-long.257/) | Component: constrained instructions | Individual and combined constraint satisfaction | Increasing constraints across variants need not be interactive updating. |
| [IFEval](https://arxiv.org/abs/2311.07911) | Component: verifiable instructions | Executable compliance checks | Does not by itself assess change from an earlier decision. |
| [Multi-IF](https://arxiv.org/abs/2410.15553) | Multi-turn component evaluation | Instruction retention across turns and languages | Multi-turn structure alone does not establish warranted revision. |
| [LongMemEval](https://arxiv.org/abs/2410.10813) | Mixed: memory histories and update questions | Retrieval, temporal reasoning, knowledge updates, abstention | Not every subset measures an explicit before/after commitment. |
| [MQuAKE](https://arxiv.org/abs/2305.14795) | Adjacent: factual knowledge editing | Propagation to multi-hop conclusions | Editing a fact differs from deciding whether evidence warrants accepting it. |
| [AmbigQA](https://aclanthology.org/2020.emnlp-main.466/) | Component: static ambiguous QA | Multiple interpretations and disambiguation | Not inherently an uncertainty-updating evaluation. |
| [CLAMBER](https://aclanthology.org/2024.acl-long.578/) | Component: ambiguity and clarification | Ambiguity recognition and question quality | Clarification quality does not establish calibrated confidence change. |
| [CLAM](https://arxiv.org/abs/2212.07769) | Interactive clarification | Clarify and answer using additional information | Answer gains do not establish calibration throughout the dialogue. |
| [MediQ](https://arxiv.org/abs/2406.00922) | Interactive clinical information seeking | Question asking before diagnostic commitment | Simulated interaction is not prospective clinical validation. |
| [Selective QA under domain shift](https://aclanthology.org/2020.acl-main.503/) | Component: selective answering | Accuracy-coverage trade-off | Does not directly measure evidence-triggered confidence changes. |
| [AbstentionBench](https://arxiv.org/abs/2506.09038) | Component: answerability and abstention | Withholding answers across different uncertainty conditions | Binary abstention does not capture every appropriate conditional response. |
| [XSTest](https://aclanthology.org/2024.naacl-long.301/) | Adjacent: safety refusal | Excessive refusal versus unsafe compliance | Safety refusal is distinct from epistemic abstention. |
| [KnowNo](https://proceedings.mlr.press/v229/ren23a.html) | Interactive embodied planning | Task completion and assistance seeking | Guarantees depend on the stated calibration assumptions and setup. |
| [τ-bench](https://arxiv.org/abs/2406.12045) | Interactive tool-agent-user tasks | Policy compliance and final-state task success | Final-state success does not establish that every intermediate revision was warranted. |

Use the cited study for models, prompts, dataset versions, ground truth, metric definitions, and numerical results. Compare reported scores only within their documented experimental conditions.

[Return to the survey README](../README.md)
