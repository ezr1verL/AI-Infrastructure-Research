# AI Infrastructure Capital Allocation
## Independent Investment Research Memorandum

**Author:** Liangyu Luo (River)  
**Date:** July 28, 2026  
**Research status:** Initial thesis review and comparison of PJM, ERCOT, and CAISO completed. Utility, project, ownership, company, valuation, and return work remain incomplete.

> **Independent research disclaimer:** This memorandum is independent research prepared for educational and analytical purposes. It is not investment advice, a recommendation regarding any security or fund, or a forecast of investment performance. It does not represent institutional fund, general-partner, manager, or private-equity due diligence.

### 1. Executive Summary

This project asks whether timely access to reliable electricity should be an explicit variable in AI infrastructure research. The current evidence says yes, with important qualifications.

DOE/LBNL evidence cited in [Module 1](research/01_power_constraint.md) documents measured growth in U.S. data-center electricity use. Forecasts from government, grid-operator, and industry sources present a broad range of further growth scenarios. The same evidence also shows why headline forecasts must be handled cautiously. Large-load requests do not all become operating demand; efficiency may improve; projects can be delayed or cancelled; and grid conditions differ by region. The repository therefore does not adopt a single demand forecast.

My current thesis is narrower. A utility's ability to deliver power to a specific site may affect when and where AI infrastructure is built. The effect will differ by region, utility territory, and project. This is a view about deployment conditions, not asset returns.

The initial regional work compares PJM Interconnection, the Electric Reliability Council of Texas, and the California Independent System Operator. The rest of this memo uses the abbreviations PJM, ERCOT, and CAISO. PJM has the clearest repository evidence of concentrated data center load growth and transmission needs, particularly in the Dominion zone. ERCOT reports a large pipeline of requested load, but its forecast reduces that figure to reflect projects that may be delayed or never completed. CAISO provides a comparison case with a smaller quantified near term data center forecast in the sources cited by Module 1. The evidence is not sufficient to rank the regions as investments or to claim that one market has the best planning process.

The memo separates four categories that are often mixed together:

1. **Measured load** already visible in historical data.
2. **Forecast load** produced by agencies, grid operators, utilities, or researchers.
3. **Requested load** submitted by prospective projects.
4. **Committed or operating load** backed by firm utility service, construction, financing, and actual consumption.

The analysis is strongest when it keeps those categories separate. A shortage does not by itself prove that an investment will earn an attractive return. Moving from a national forecast to a company view requires work on ownership, regulation, contracts, spending needs, competition, and valuation.

The current evidence does **not** establish that electricity is definitively a longer-lasting bottleneck than semiconductors. It does not measure those constraints on a common timeline, and it does not analyze semiconductor supply in enough detail to support that comparison.

### 2. Research Question and Scope

#### Research question

How should an investor evaluate the AI infrastructure value chain if timely access to reliable electricity becomes a material constraint on deployment?

#### Why the question matters

AI infrastructure projects require more than computing equipment. They also require a site, electrical service, transmission and distribution capacity, substations, cooling, network connectivity, permitting, construction, and capital. If power cannot be delivered on the required schedule, a project may be delayed, relocated, redesigned, or paired with alternative supply arrangements.

That possibility affects research priorities. A semiconductor-centered view may be incomplete if deployment timing also depends on electricity infrastructure. The repository tests that proposition with public evidence rather than assuming it is true.

#### Included

- Historical and forecast data-center electricity demand.
- Grid-operator, government, and industry evidence on load growth.
- Interconnection and transmission timing.
- Initial comparison of PJM, ERCOT, and CAISO.
- Scenario uncertainty and disconfirming evidence.
- A preliminary monitoring framework based on existing sources.

#### Outside the current scope

- Security recommendations or expected returns.
- Company valuation, financial modeling, or management assessment.
- Fund, GP, manager, or institutional private-market diligence.
- Project-level contracts, power-purchase agreements, service agreements, or financing.
- A complete comparison of generation technologies.
- A full semiconductor supply-chain analysis.
- A conclusion that electricity constraints will outlast semiconductor constraints.
- A complete U.S. regional ranking.
- International market analysis beyond global context in cited sources.

#### Important limitations

The repository contains two research modules and no underlying dataset, notebook, or reproducible model. Most quantitative evidence is summarized in a Markdown tracker that links to external sources. Forecasts have different vintages, definitions, geographies, and scenarios. Some regional conclusions in the earlier draft of Module 2 were stronger than that evidence; those have been narrowed in the current revision.

### 3. Investment Thesis

#### Central thesis

Power availability should be treated as a material local variable in AI infrastructure research. The evidence supports more work on utility service and project completion. It does not yet support conclusions about assets, companies, or returns.

| Supporting proposition | Confidence | Current evidence | Evidence that would increase confidence | Evidence that would decrease confidence |
|---|---|---|---|---|
| U.S. data-center electricity use is likely to rise through the remainder of the decade | Moderate | DOE/LBNL historical use and forecast range; IEA, EPRI, EIA, and utility-planning forecasts summarized in Module 1 | Continued measured load growth; stable or rising forecasts across vintages; conversion of firm projects into operating load | Downward forecast revisions; low project realization; efficiency gains that materially offset adoption |
| Local deliverability can delay deployment even when regional supply appears adequate | Moderate | IEA transmission timelines; DOE/LBNL queue data; PJM and Virginia load evidence | Utility service timelines, substation constraints, signed upgrade plans, project-specific delays attributable to power | Faster service connections, shorter queues, or evidence that non-power factors dominate project timing |
| Regional conditions matter more than a single national shortage narrative | Moderate | Divergent PJM, ERCOT, and CAISO forecasts and methods | Utility- and zone-level comparisons using common indicators | Convergence of service timelines, costs, and load conditions across regions |
| Requested load must be probability-weighted | High | ERCOT's explicit methodology adjustments; Grid Strategies forecast caution | Public milestones linking requests to deposits, contracts, construction, and consumption | Evidence that most requests rapidly convert to firm operating demand |
| Observable scarcity may create research opportunities, but attractive returns are not established | Preliminary | Long infrastructure timelines and concentrated demand create plausible economic relevance | Ownership, rate treatment, contract quality, competitive position, capital cost, and valuation evidence | Regulatory disallowance, competition, poor cost recovery, overbuilding, or valuations that already price in benefits |

The confidence labels reflect the evidence in this repository, not the strength of the broader public debate.

### 4. Analytical Framework

The repository's framework can be expressed as a sequence of conditional relationships:

1. **Compute demand** influences demand for data-center capacity.
2. **Data-center deployment** creates incremental electricity requirements, but the magnitude depends on utilization, efficiency, and project realization.
3. **Generation** determines whether energy and dependable capacity are available at a regional level.
4. **Transmission, substations, and distribution** determine whether that power can reach a site.
5. **Grid connection and utility service processes** affect timing, upgrade costs, and certainty. Grid connection refers to the approvals and construction needed to connect new generation or a large customer.
6. **Regional market structure and regulation** determine planning, cost allocation, tariffs, and the ability of asset owners to recover investment.
7. **Capital deployment** responds only if expected economics are adequate after timing, execution, financing, and regulatory risks.

This framework avoids two common errors.

First, higher electricity demand does not automatically mean a regional shortage. Supply, transmission, flexible-load arrangements, and efficiency can respond. Second, a physical constraint does not automatically create an attractive investment. Economic capture depends on who owns the relevant asset, the rules governing returns, and the price paid.

#### Evidence classification

The research uses:

- **Historical evidence** for measured electricity use and load.
- **Forecasts and scenarios** for possible future demand.
- **Grid-operator evidence** for regional methods and planning.
- **Government and policy sources** for systemwide context.
- **Counterarguments** for uncertainty in realization and efficiency.

The [Module 1 evidence tracker](research/01_power_constraint.md#evidence-tracker) assigns reliability scores, but those scores are author judgments rather than externally validated ratings. A high score indicates source authority and transparency; it does not eliminate forecast error.

### 5. Supporting Evidence

#### 5.1 Historical growth and demand scenarios

##### Evidence

DOE/LBNL reports U.S. data-center electricity use of 176 TWh in 2023, up from 58 TWh in 2014, and presents a 325-580 TWh range for 2028. The IEA base case cited in Module 1 estimates global data-center electricity use of about 945 TWh by 2030 from 415 TWh in 2024. EPRI presents a 9%-17% range for the U.S. share of electricity by 2030. These figures are summarized and linked in [Module 1](research/01_power_constraint.md#evidence-tracker).

##### Interpretation

Measured U.S. use has increased, and multiple sources expect further growth. The forecast spread is itself important evidence: the rate of AI adoption, project realization, and efficiency is uncertain.

##### Investment relevance

Scenario analysis is more appropriate than a single demand case. Long-lived assets should be tested against slower load growth and delayed project ramps.

##### Limitations

The repository does not reconcile differences in definitions, embedded assumptions, or geographic coverage. It also does not build an independent forecast.

#### 5.2 Transmission and interconnection

##### Evidence

The IEA executive summary cited in Module 1 states that new transmission in advanced economies can take four to eight years and estimates that a portion of planned data-center projects could face delay if grid risks are not addressed. DOE/LBNL's *Queued Up* work documents a large interconnection backlog and median development times exceeding four years for projects built in 2018-2024.

##### Interpretation

New generation does not guarantee that power can reach a particular site. Transmission and the grid connection process can affect timing. The queue statistics mainly cover generation and storage projects. They show delays on the supply side, but they do not directly prove that data center utility service is delayed.

##### Investment relevance

Research should examine the actual path from generation to load: transmission upgrades, substation capacity, utility service, and cost allocation.

##### Limitations

The repository does not contain project-level data-center interconnection timelines or a dataset linking specific delays to specific grid causes.

#### 5.3 PJM and Virginia

##### Evidence

PJM's 2026 load forecast, as summarized in Module 1, projects 3.6% annual growth in summer peak over ten years and identifies substantial zone-level variation. EIA's Virginia analysis reports rapid commercial-sales growth and a 5.4% annual ten-year summer-peak growth forecast for the Dominion zone. NERC identifies rising resource-adequacy risk amid broader demand growth.

##### Interpretation

The repository evidence supports concentrated load growth and transmission relevance in PJM, especially the Dominion zone. It does not isolate AI workloads from all data-center activity and does not prove that electricity is the binding constraint for every project.

##### Investment relevance

PJM warrants utility- and zone-level follow-up. Relevant questions include service timelines, required upgrades, cost responsibility, rate design, and whether planned investment earns adequate returns.

##### Limitations

There is no utility filing review, substation map, congestion series, project list, or company valuation work in the repository.

#### 5.4 ERCOT

##### Evidence

ERCOT's 2025 long-term forecast update, cited in Module 1, shows large requested data-center growth but adjusts new demand to 49.8% of the requested amount and delays ramps by 180 days. The adjustment is based on observed realization and project timing.

##### Interpretation

Requested capacity is not expected consumption. ERCOT is useful because it makes the realization adjustment explicit.

##### Investment relevance

Project screening should consider development stage, financial commitments, customer identity, power arrangements, and service terms. Some ERCOT customers may agree to reduce electricity use when the grid is tight. That flexibility can help the grid, but it may also make service less certain for the customer.

##### Limitations

The repository does not identify individual projects, distinguish firm from flexible service in a dataset, or assess developers.

#### 5.5 CAISO

##### Evidence

CAISO's large-load materials, as summarized in Module 1, cite California Energy Commission forecasts of a 1.8 GW increase in data-center load by 2030 and 4.9 GW by 2040. The source describes how large loads enter planning.

##### Interpretation

The quantified near-term increase in the cited CAISO source is smaller than the headline requested-load growth cited for ERCOT and the concentrated growth cited for PJM. That does not establish an absence of local constraints.

##### Investment relevance

CAISO is a comparison case for planning treatment and regional differences. Utility-territory evidence is needed before making scarcity or beneficiary claims.

##### Limitations

The repository does not compare planning quality across operators and does not review California utility applications or local service queues.

#### 5.6 Counterarguments and uncertainty

##### Evidence

ERCOT's forecast haircuts, Grid Strategies' warning about possible overstatement, and Bipartisan Policy Center/Koomey analysis all challenge simple extrapolation. IEA scenarios also vary with uptake and efficiency.

##### Interpretation

The power thesis is conditional. Wider AI adoption can increase total demand even as energy efficiency improves, but the repository cannot determine the net effect.

##### Investment relevance

Forecast-vintage tracking, realized-load data, and project milestones are as important as announced capacity.

##### Limitations

No independent sensitivity model exists in the repository.

### 6. Regional or Market Comparison

The comparison below summarizes repository evidence. It is not a ranking of return potential.

| Region | Evidence in repository | Potential advantage to test | Material risks | Evidence quality |
|---|---|---|---|---|
| PJM / Dominion | Concentrated data-center load growth; higher peak forecasts; transmission relevance | Existing demand may support infrastructure investment | Transmission timing, cost allocation, permitting, customer concentration, forecast revision | Moderate: official forecasts, but limited subregional detail |
| ERCOT | Large requested-load pipeline; explicit realization haircut | Flexible market and project pipeline may create multiple development paths | Speculative requests, curtailment, weather, generation adequacy, price volatility | Moderate: official method is clear; project-level evidence absent |
| CAISO | Formal large-load planning materials; smaller cited near-term data-center increment | Planning process offers a useful comparison | Local constraints may be hidden by aggregate data; policy and cost risk | Preliminary to moderate: official source, limited local evidence |

The table deliberately avoids "best region," "largest opportunity," or "most sophisticated market" language. Those claims require common metrics and evidence not present in the repository.

### 7. Capital Allocation Implications

The current work supports a research agenda across selected parts of the value chain:

#### Generation

Dependable supply could become more valuable where committed load grows faster than available capacity. Further work must separate energy from dependable capacity, guaranteed service from intermittent output, market price exposure from contracted revenue, and permitted projects from early proposals.

#### Transmission, substations, and grid equipment

Long lead times make these categories relevant. However, revenue and returns depend on regulatory approval, cost recovery, manufacturing capacity, competition, and execution. The repository has not analyzed those economics.

#### Regulated utilities

Large load growth may increase utility investment. Regulators may allow the utility to earn a return on some of that spending. The same projects can create customer concentration, affordability disputes, or unused assets if demand does not arrive. Utility exposure should not be described as a beneficiary until these issues are assessed.

#### Data centers and powered sites

Existing service, credible upgrade schedules, and secured capacity may improve execution certainty. The repository lacks site-level evidence and cannot determine the value or durability of that advantage.

#### Semiconductors and compute efficiency

More efficient hardware and software can reduce energy intensity per unit of compute. Rebound effects may offset those gains if lower cost expands usage. The repository does not compare the duration or severity of power and semiconductor constraints and should not present electricity as definitively longer-lived.

No company-level recommendation is supported. Any company or asset exposure should be framed as a candidate for additional research.

### 8. Risks and Disconfirming Evidence

#### Technological risk

Efficiency improvements in accelerators, model architecture, inference, cooling, and workload management could reduce demand relative to current forecasts. Conversely, rebound effects could increase aggregate use. The direction and magnitude are unresolved.

#### Demand risk

Announced projects may be duplicates, placeholders, or contingent on customers and financing. Slower AI adoption or lower utilization would reduce load.

#### Power-market risk

New supply, storage, transmission, behind-the-meter generation, flexible demand, or interconnection reform could reduce bottlenecks. Extreme weather and fuel constraints could also worsen them.

#### Regulatory risk

Regulators may limit cost recovery, change tariff design, require customer protections, or reallocate upgrade costs. A physical need does not guarantee attractive owner economics.

#### Execution risk

Permitting, equipment, labor, construction, and financing can delay both grid assets and data centers. A project may fail for reasons unrelated to power.

#### Timing risk

Grid investment may be built before demand becomes firm. Long construction periods create mismatch between capital spending and utilization.

#### Incomplete-data risk

The repository summarizes source material but does not store underlying time series or a reproducible model. Source definitions and vintages differ. Several regional claims require utility- and project-level validation.

#### What would materially weaken or invalidate the thesis

- Sustained downward revisions in official data-center load forecasts.
- Low conversion of requested loads into operating consumption.
- Service and interconnection timelines that shorten materially without higher costs.
- Efficiency gains that offset most incremental load growth.
- Evidence that permitting, construction, water, networking, or semiconductor supply consistently dominates power in project delays.
- Regulatory frameworks that prevent relevant asset owners from earning adequate returns.

### 9. Future Diligence Questions

The term "future diligence" here means general research, not institutional fund or manager diligence.

#### Power supply

- How much incremental load is matched with firm generation or capacity?
- What portion relies on merchant exposure, on-site generation, or flexible service?

#### Transmission and interconnection

- Which upgrades are required, who pays, and what is the expected in-service date?
- Which constraints are local distribution issues versus bulk-transmission issues?

#### Utilities

- How are large-load requests screened?
- What deposits, minimum bills, or termination protections reduce stranded-cost risk?
- How do regulators allocate upgrade costs?

#### Data centers

- Which projects have land, permits, financing, customers, equipment, and power?
- What load ramp is contractually supported?

#### Technology efficiency

- How are power usage effectiveness, chip efficiency, utilization, and inference intensity changing?
- Are gains reducing total load or enabling more usage?

#### Regulation

- Are new large-load tariffs changing project economics?
- What reliability and affordability protections are being introduced?

#### Regional economics

- What are all-in power costs, congestion risks, and delivery timelines?
- How do taxes, water, labor, and network connectivity alter location decisions?

#### Capital intensity

- What spending is required per MW of new service?
- What is the timing between capital outlay and revenue recovery?

#### Competitive advantage

- Is access to power contractual, physical, regulatory, or merely announced?
- Can competitors replicate it, and on what timeline?

### 10. Monitoring Framework

| Indicator | Why it matters | Likely existing source | Strengthening signal | Weakening signal |
|---|---|---|---|---|
| U.S. data-center electricity use | Tests realized demand | DOE/LBNL | Measured growth near or above base scenarios | Growth materially below scenarios |
| IEA/EPRI forecast revisions | Tracks scenario direction | IEA; EPRI | Stable or rising forecasts with transparent assumptions | Repeated downward revisions |
| PJM zone load forecasts | Identifies concentration | PJM annual load forecast | Firm growth persists in data-center-heavy zones | Major downward revisions |
| Virginia commercial sales and Dominion peaks | Tests operating load | EIA; PJM | Continued measured growth | Plateau or decline |
| ERCOT requested versus adjusted load | Measures realization discount | ERCOT forecast updates | Narrowing gap as projects mature | Persistent or widening haircut |
| CAISO large-load forecast | Provides a comparison case | CAISO; CEC | Higher firm load with identified projects | Applications fail to convert |
| Interconnection queue size and completion time | Tests supply-side friction | DOE/LBNL *Queued Up* | Long timelines persist for projects needed to serve load | Faster completion and lower backlog |
| Transmission project schedules | Tests deliverability response | ISO/RTO planning documents | Delays or rising upgrade needs | On-time expansion ahead of load |
| Large-load tariff changes | Affects risk sharing | Utility and commission filings | Strong customer commitments and cost protections | Socialized costs or weak termination protection |

The repository has not built a quarterly database. This table is a design for future updates, not evidence that monitoring has already occurred.

### 11. Conclusion

#### What the evidence currently supports

- U.S. data-center electricity use has risen, and multiple credible sources expect further growth.
- Forecast magnitude is uncertain and should be scenario-weighted.
- Local deliverability, transmission, interconnection, and utility processes can affect deployment timing.
- PJM, ERCOT, and CAISO differ enough that a national conclusion is insufficient.
- Requested load should not be treated as realized demand.

#### What remains an inference

- Specific constrained locations may create valuable infrastructure positions.
- Certain asset owners may benefit if they can recover investment and preserve pricing power.
- Secured power may influence site competitiveness.

#### What remains unresolved

- Which constraints are binding at the utility, zone, and project level.
- Who owns or controls them.
- Whether scarcity produces attractive risk-adjusted returns.
- How power constraints compare in duration and severity with semiconductors and other deployment constraints.
- Which companies, if any, offer attractive exposure at current valuations.

My next step would be a narrower review of utilities and individual projects. Broadening the thesis before that work would create more narrative than analysis.

### Appendix A: Evidence Map

| Major conclusion | Repository support | Primary sources linked in repository |
|---|---|---|
| Data-center electricity demand has risen and may continue to rise | [Module 1 evidence tracker](research/01_power_constraint.md#evidence-tracker) | [DOE/LBNL release](https://www.energy.gov/articles/doe-releases-new-report-evaluating-increase-electricity-demand-data-centers), [IEA](https://www.iea.org/reports/energy-and-ai/energy-demand-from-ai), [EPRI](https://restservice.epri.com/publicattachment/97025) |
| Forecast range is wide | [Module 1](research/01_power_constraint.md#4-what-remains-uncertain) | [IEA key questions](https://iea.blob.core.windows.net/assets/3179f7f8-01f6-4dd6-bffa-c9f7b73f1dc9/KeyQuestionsonEnergyandAI.pdf), [BPC/Koomey](https://bipartisanpolicy.org/report/electricity-demand-growth-and-data-centers/) |
| Interconnection and transmission can create timing risk | [Module 1](research/01_power_constraint.md#3-what-the-evidence-supports) | [DOE/LBNL Queued Up](https://emp.lbl.gov/queues), [IEA executive summary](https://www.iea.org/reports/energy-and-ai/executive-summary) |
| PJM has concentrated load growth and transmission relevance | [Module 2 PJM section](research/02_regional_constraint_assessment.md#pjm) | [PJM 2026 forecast](https://www.pjm.com/-/media/DotCom/library/reports-notices/load-forecast/2026-load-report.pdf), [EIA Virginia analysis](https://www.eia.gov/todayinenergy/detail.php?id=67664) |
| ERCOT requests require realization adjustment | [Module 2 ERCOT section](research/02_regional_constraint_assessment.md#ercot) | [ERCOT forecast update](https://www.ercot.com/files/docs/2025/04/07/8.1-Long-Term-Load-Forecast-Update-2025-2031-and-Methodology-Changes.pdf) |
| CAISO is a regional comparison, not proof of no scarcity | [Module 2 CAISO section](research/02_regional_constraint_assessment.md#caiso) | [CAISO large loads](https://www.caiso.com/generation-transmission/load/large-loads) |
| No company or return conclusion is established | [README status](README.md#research-progress), [Executive Summary status](Executive_Summary.md#research-status) | Repository limitation |

### Appendix B: Research Limitations

1. Only two substantive research modules are present.
2. No underlying dataset, notebook, model, or chart is stored in the repository.
3. External sources use different definitions, geographies, vintages, and scenarios.
4. Reliability scores are author judgments.
5. Module 2 does not contain its own source table and depends partly on Module 1.
6. Utility-, zone-, substation-, and project-level evidence is limited.
7. The repository does not assess ownership, contracts, regulation, cost recovery, competitive position, valuation, or expected returns.
8. The repository does not support institutional fund, GP, manager, or private-market diligence claims.
9. The repository does not establish that electricity is the primary or longest-lived constraint relative to semiconductors or other inputs.
10. The monitoring framework is proposed, not implemented.
