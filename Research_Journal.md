# Research Journal

> "This journal is a retrospective reconstruction based on repository history, file changes, and documented research outputs. It is not a contemporaneous record of every research session."

**Author:** Liangyu Luo (River)  
**Reconstruction date:** July 28, 2026

## Method and Date Integrity

This journal uses only milestones that can be tied to the repository's Git history or to the current documented revision:

- **June 29, 2026:** initial repository, Module 1, and initial Module 2 work were created and revised in Git.
- **July 20, 2026:** Module 2 and the README were substantially revised in Git.
- **July 28, 2026:** this is the date of the current synthesis and credibility review. It is not presented as a prior Git milestone. Until this revision is committed, Git history will not independently verify it.

The repository contains no evidence for a day-by-day account between those milestones. No entries have been invented to fill the gaps.

## June 29, 2026

**Git basis:** Initial commit `1d00345`; creation and revisions of `research/01_power_constraint.md` from `396e7bc` through `c8e23e5`; creation and relocation of `research/02_regional_constraint_assessment.md` in `b5dd6b1` and `31cad3c`; multiple README revisions on the same date.

### Research Focus

The repository was established around a conditional question: whether power availability should be included as a constraint in AI infrastructure research. Module 1 collected demand forecasts, historical data, grid-operator materials, interconnection evidence, and counterarguments. Module 2 began as an in-progress regional comparison of PJM, ERCOT, and CAISO.

### Evidence Reviewed

The files and source categories visible in the June 29 history include:

- `research/01_power_constraint.md`
- the initial version of `research/02_regional_constraint_assessment.md`
- IEA demand scenarios
- DOE/LBNL U.S. data-center electricity use
- EPRI scenarios
- EIA, NERC, PJM, ERCOT, and CAISO materials
- DOE/LBNL interconnection-queue data
- Grid Strategies and Bipartisan Policy Center/Koomey counterarguments

### View at the Time

The documented working view was that power availability was a credible variable for further research and that a national aggregate would not be sufficient. Module 1 explicitly retained uncertainty around forecast realization, efficiency, and regional policy.

The initial Module 2 version was appropriately cautious. It described PJM, ERCOT, and CAISO conclusions as working hypotheses, marked evidence collection as incomplete, and stated that the evidence was insufficient for a definitive regional ranking.

### What Changed

The project moved from a broad macro question toward a regional framework. It began separating:

- aggregate electricity supply from local deliverability;
- requested load from expected load;
- national demand from ISO/RTO and utility conditions;
- thesis validation from company or security analysis.

### Remaining Questions

- Which utility territories and zones face actual service constraints?
- How much requested load should be treated as firm?
- Are constraints driven by generation, transmission, distribution, equipment, permitting, or some combination?
- Who pays for upgrades, and who is allowed to earn a return?
- How should efficiency gains change demand scenarios?
- How do power constraints compare with semiconductor and other project constraints?

## July 20, 2026

**Git basis:** Major Module 2 revisions in commits `17484ef` and `ec3c2b6`; README revision in `b67e0de`.

### Research Focus

The July 20 changes converted Module 2 from an active research notebook into a shorter regional narrative. The README was also expanded into a seven-module roadmap and marked Modules 1 and 2 as completed.

### Evidence Reviewed

The revised file continued to rely primarily on the source base assembled in Module 1:

- PJM load forecasts and Virginia/Dominion evidence;
- ERCOT's adjusted large-load methodology;
- CAISO large-load planning materials;
- national reliability, demand, and interconnection context.

No new repository dataset, notebook, utility filing set, project list, or valuation analysis was added.

### View at the Time

The July 20 narrative placed more emphasis on:

- PJM as the clearest case of concentrated demand and transmission relevance;
- ERCOT as a high-growth but uncertain request pipeline;
- CAISO as a planning comparison;
- local deliverability rather than regional generation totals.

### What Changed

The writing became more conclusive than the underlying work. Several statements moved beyond what the repository could trace:

- ERCOT was described as the "largest growth opportunity."
- CAISO was described as evidence of "planning sophistication" and a benchmark for "best practices."
- developer and infrastructure-owner implications were stated before ownership, project, regulatory, or valuation work existed.
- the module status changed to "Completed" even though utility- and project-level questions remained open.

Those statements have been narrowed in the July 28 revision. The module now distinguishes an **initial regional comparison** from completed subregional or investment analysis.

### Remaining Questions

- Can PJM constraints be documented below the RTO level?
- What proportion of ERCOT requests have deposits, signed service agreements, financing, or construction activity?
- Are CAISO constraints concentrated within specific utility territories?
- Do relevant infrastructure owners have durable economics after regulation, competition, and capital costs?
- Which conclusions can be monitored with reproducible data rather than narrative updates?

## July 28, 2026

**Basis:** Current repository-wide synthesis and skeptical editorial review. This entry records the present revision date; it should not be described as a historical commit until committed.

### Research Focus

The current review tests whether the repository can withstand three skeptical readers:

1. a private-investments recruiter looking for accurate representation of experience;
2. an investment director evaluating judgment, evidence, and writing discipline;
3. a fact-checker tracing claims to sources and Git history.

The review produced:

- `Executive_Summary.md`
- `Investment_Memorandum.md`
- `Research_Journal.md`
- an updated README with links to the core outputs
- targeted revisions to Module 2's strongest unsupported conclusions

### Evidence Reviewed

The review covered the complete repository, all Markdown files, the full Git log, file-specific history, and the source links already listed in Module 1. The repository contains no data files, notebooks, or charts, so none are represented as completed work.

### Current State of the Thesis

The strongest defensible statement is:

> Power availability should be treated as a material, region-specific variable in AI infrastructure research, while the magnitude, timing, and economic beneficiaries remain uncertain.

This is not a conclusion that electricity is the sole or primary constraint. It is also not a conclusion that electricity is definitively a longer bottleneck than semiconductors. The repository does not contain a common-duration comparison, a semiconductor supply analysis, or enough project-level evidence to support that claim.

### Strongest Supported Conclusions

- U.S. data-center electricity use has grown historically.
- Credible sources project additional growth, but the range is wide.
- Local deliverability and interconnection can affect timing.
- Requested load should be distinguished from realized demand.
- PJM, ERCOT, and CAISO require different analytical treatment.
- Current evidence supports further research, not security recommendations.

### Most Important Uncertainties

- Project realization and utilization.
- Utility- and zone-level service constraints.
- Cost allocation and regulatory recovery.
- The pace of generation and transmission response.
- Efficiency and rebound effects.
- Ownership and economic capture.
- Valuation and expected returns.
- Relative importance and duration of non-power constraints.

### What Changed From the Initial Framing

The project initially asked how long-term capital should be allocated if power becomes the primary constraint. The current framing is more careful: first determine whether and where power is a material constraint, then identify ownership and economics, and only later consider portfolio relevance.

The phrase "capital allocation" is retained in the project title and central question, but the documents avoid using it as a substitute for missing valuation or return analysis. "Investment implications" are presented as research directions. "Due diligence" appears only where its meaning and limitations are explicit.

### Next Research Priorities

1. Build a source-controlled dataset with source date, geography, definition, base/high/low cases, and update history.
2. Conduct utility- and zone-level work in PJM, beginning with the Dominion zone.
3. Track requested, adjusted, committed, under-construction, and operating large loads separately in ERCOT.
4. Review CAISO utility-territory applications and local transmission evidence.
5. Examine large-load tariffs, upgrade cost allocation, deposits, and termination protections.
6. Add project-level evidence before discussing powered-site or developer advantages.
7. Compare power, semiconductor, water, permitting, construction, and networking constraints on a common timeline.
8. Add company or asset analysis only after ownership, economics, and valuation can be supported.

### Remaining Questions

- Which constraint is actually binding for a specific project?
- How durable is the constraint?
- Who controls the relevant asset or right?
- Who bears the capital cost?
- What contractual or regulatory mechanism permits economic capture?
- What evidence would falsify the view?

The repository is now more explicit about what it knows, what it infers, and what it has not yet established. That distinction is the main result of the July 28 review.
