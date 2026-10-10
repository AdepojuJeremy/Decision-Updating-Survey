# Contributing

We welcome relevant papers, dataset suggestions, corrections, and improvements to the figures and documentation.

## Suggest literature

Provide the exact title, full author list, year and edition, and a primary source link (publisher, ACL Anthology, proceedings, or arXiv). Explain its connection to contradictory, complicating, or uncertainty-inducing evidence, or to a cross-cutting dimension. Identify whether the study evaluates a decision transition directly or a supporting capability.

Check `references/papers.json` for an existing record before adding a paper. Preserve differences between arXiv and proceedings versions; do not turn a preprint year into an unsupported conference claim. Add the record to the JSON catalogue and BibTeX file, then place a short, specific entry in the relevant README section.

## Report a correction

State the affected file and entry, the proposed correction, and the primary source supporting it. Numerical claims need an exact table, figure, page, or section and the applicable model, dataset, prompt, baseline, and metric definition. Distinguish percentage points from relative percentage improvements.

## Scope

Keep the three primary evidence categories distinct from orthogonal synthesis. Avoid inferring successful updating solely from static accuracy, instruction compliance, or confidence estimates. Do not add claims that the manuscript has been submitted, accepted, or published without confirmation from the maintainers.

## Figures

Edit the `.drawio` source and update its corresponding export when appropriate. Maintain readable labels and source attribution. Describe substantial changes in the pull request so they can be reviewed against the manuscript.
