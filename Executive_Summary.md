# AI Infrastructure Capital Allocation
## Executive Summary

> **Independent research disclaimer:** This document is independent research prepared for educational and analytical purposes. It is not investment advice, a security recommendation, or a forecast of investment performance.

**Author:** Liangyu Luo (River)  
**Evidence cut-off:** July 28, 2026  
**Research status:** Initial thesis review and three-region comparison completed; ownership, company exposure, valuation, and return analysis remain uncompleted.

### Research Question

How should an investor evaluate the AI infrastructure value chain if timely access to reliable electricity becomes a material constraint on deployment?

The wording is deliberately conditional. The repository tests whether power availability belongs in the research framework. It does not prove that electricity is the only, primary, or longest lasting bottleneck. It also does not compare the duration of electricity constraints with semiconductor supply constraints. The current work uses public evidence on data center electricity demand, grid planning, the process for connecting new supply and large users to the grid, and selected regional markets.

### Current Thesis

My current view is that power can be a material and local constraint for AI infrastructure. U.S. data center electricity use has grown, and most sources expect further growth. The forecasts still vary widely because many announced projects may not be built. For an investor, national electricity demand is only a starting point. The more useful question is whether a utility can deliver enough power to a specific site on the required schedule.

Confidence in that thesis is moderate, not high. Official and industry forecasts support the demand premise, but the work does not yet connect load growth to asset returns. The repository has not completed ownership mapping, company analysis, valuation, regulatory cost recovery, or project level review. [Module 1](research/01_power_constraint.md) supports further investigation. [Module 2](research/02_regional_constraint_assessment.md) provides an initial regional comparison, not a final ranking.

### Key Findings

#### 1. Data center electricity demand is rising, but the range of outcomes is wide

DOE/LBNL estimates that U.S. data centers used 176 TWh in 2023 and presents a range of 325 to 580 TWh for 2028. IEA, EPRI, EIA, and utility planning sources also point to higher demand, but their scenarios differ. Efficiency, AI adoption, project completion, and the treatment of announced loads explain part of the gap. The repository therefore supports a rising demand view, not a single forecast. See the [Module 1 evidence tracker](research/01_power_constraint.md#evidence-tracker).

**Why it matters:** Assets designed around one aggressive load forecast may be exposed to utilization and timing risk. Research should use scenarios and distinguish measured load, forecast load, requested load, and committed load.

#### 2. Local deliverability can matter even when regional generation appears sufficient

IEA notes that transmission construction in advanced economies can take years, while DOE/LBNL documents large interconnection queues and long completion timelines. PJM and Virginia evidence in Module 1 shows concentrated load growth and regional divergence. These sources support the proposition that access to power at a particular site and date can be more relevant than aggregate regional generation.

**Why it matters:** The next step is to study utility territories, transmission zones, substations, and individual projects instead of treating the United States as one market. This does not yet establish which owners earn attractive returns.

#### 3. Requested load is not equivalent to realized demand

ERCOT adjusts requested large load additions for the chance that projects are delayed or never completed. Grid Strategies also warns that utility forecasts may be overstated. These sources show why every announced data center should not be treated as firm demand. [Module 2](research/02_regional_constraint_assessment.md#ercot) treats ERCOT as a case where completion risk matters, not as a proven growth opportunity.

**Why it matters:** Project maturity, customer commitments, financing, power arrangements, and ramp schedules should be examined before forecast demand is incorporated into an investment view.

#### 4. The evidence is regional, not uniform

The regional review covers PJM Interconnection, the Electric Reliability Council of Texas, and the California Independent System Operator. These grid operators differ in existing load concentration, forecast methods, market structure, and near term data center growth in the cited sources. PJM has the clearest repository evidence of concentrated load growth and transmission needs. ERCOT reports a large requested load pipeline but reduces it to reflect projects that may not be completed. CAISO is a useful planning comparison, but the repository does not show that California is free of local constraints or that its process is better.

**Why it matters:** A national thesis can obscure local scarcity, regulatory differences, and project-specific execution risk. No regional return ranking is supported at this stage.

#### 5. The repository validates a research variable, not an investment recommendation

The completed work supports including power availability, interconnection, and deliverability in AI infrastructure analysis. It does not support buy, sell, or hold conclusions; claims about specific beneficiaries; or assertions that utilities, powered land, generation, transmission, or equipment suppliers will necessarily earn excess returns.

**Why it matters:** Scarcity does not automatically translate into attractive economics. Ownership, regulation, contract structure, capital intensity, competition, and valuation determine whether an observable constraint creates investable value.

### Investment Implications

The following points are research directions, not recommendations:

- **Generation:** Higher load may increase the value of dependable supply in constrained areas, but the repository has not evaluated fuel costs, dispatch, contract terms, permitting, or merchant-price exposure.
- **Transmission and substations:** Long lead times and local deliverability make these categories relevant. Returns may be shaped by regulation, cost allocation, and execution; those issues remain unstudied.
- **Regulated utilities:** Load growth may increase the amount of infrastructure on which a utility is allowed to earn a regulated return. That benefit can be offset by customer concentration, unused assets, affordability concerns, or limits on cost recovery. Utility level analysis is a planned step.
- **Data centers and powered sites:** Secured service and credible interconnection may improve schedule certainty. The repository does not contain project-level agreements or enough evidence to value that advantage.
- **Grid equipment:** Transformers and related equipment are mentioned as potential constraints, but the repository contains no supplier-level capacity, backlog, margin, or valuation work. This segment remains preliminary.
- **Semiconductors:** Compute efficiency is a key countervailing force. The repository does not establish whether electricity will remain constrained longer than semiconductor supply, nor does it compare the two constraints on a common timeline.

### Key Risks and Thesis Challenges

1. **Demand may be overstated.** Announced projects may be delayed, duplicated, downsized, or cancelled.
2. **Efficiency may improve faster than expected.** Better chips, models, cooling, and workload management could reduce electricity required per unit of compute, even if total demand still rises.
3. **Supply responses may arrive.** New generation, transmission, behind-the-meter supply, flexible-load arrangements, and interconnection reform could reduce scarcity.
4. **Regional evidence may not generalize.** PJM, ERCOT, and CAISO do not represent every U.S. market, and ISO-level data can conceal utility- and site-level differences.
5. **Constraint ownership is unresolved.** The party that controls a scarce resource may not be permitted or able to capture attractive economics.
6. **Timing may be mismatched.** Infrastructure investment can precede realized demand by years, creating utilization, financing, and regulatory risk.
7. **Source vintages differ.** The evidence tracker combines historical data, forecasts, scenarios, and reports published in different years. They should not be treated as directly comparable measurements.

The thesis would weaken materially if official forecasts decline across successive vintages, large-load realization rates remain low, interconnection times shorten without rising costs, or efficiency gains offset most incremental electricity use. It would strengthen if measured load continues to rise, firm service requests convert into operating demand, local delivery timelines remain extended, and utility or grid-operator plans show sustained investment tied to committed loads.

### Open Questions

- What share of forecast large-load growth is contracted, financed, under construction, or already operating?
- Which PJM zones and utility territories face the most binding delivery constraints?
- How should flexible or curtailable ERCOT loads be valued relative to firm service?
- Are CAISO constraints concentrated outside the aggregate forecast?
- Who bears transmission, substation, and generation-upgrade costs for new large loads?
- Which assets have contractual or regulatory mechanisms to earn adequate returns?
- How quickly could compute and cooling efficiency alter demand scenarios?
- How do power constraints compare with semiconductor, construction, water, permitting, and network constraints on a consistent timeline?

### Research Status

| Workstream | Status | What the repository currently supports |
|---|---|---|
| Demand and power-constraint evidence | Initial review completed | Power availability is a credible variable; forecast magnitude remains uncertain |
| PJM, ERCOT, and CAISO comparison | Initial comparison completed | Regional differences matter; no complete ranking is supported |
| Utility and subregional analysis | Preliminary / not completed | Questions identified, limited direct evidence |
| Constraint ownership | Planned | No owner-level conclusion |
| Value-chain economics | Planned | Research categories only |
| Company mapping and valuation | Not completed | No company recommendation or expected-return conclusion |
| Monitoring framework | Initial design included in the memorandum | Indicators identified; no historical tracking series built |

The next step is to narrow the work. I would focus on specific utilities and projects, then test whether a documented constraint leads to durable economics.
