# Module 2: Regional Constraint Mapping

**Status:** Initial regional comparison completed; utility- and project-level validation remains outstanding
**Last Updated:** July 20, 2026

---

# Executive Summary

The United States does **not** operate as a single electric grid. Instead, electricity is managed by multiple regional grid operators, each with different market structures, planning methods, and infrastructure constraints.

This module compares three of the most important regional power systems for AI infrastructure:

- **PJM Interconnection (PJM)**, covering the Mid-Atlantic and parts of the Midwest
- **Electric Reliability Council of Texas (ERCOT)**, serving most of Texas
- **California Independent System Operator (CAISO)**, serving most of California

The evidence reviewed suggests that **local deliverability can constrain deployment even when regional generation is available**. The repository does not yet quantify how often deliverability, generation, equipment, permitting, or other factors are the decisive constraint for individual projects.

Among the three regions reviewed, **PJM has the clearest repository evidence of concentrated load growth and transmission relevance**. **ERCOT shows large requested-load growth but explicitly discounts requests for realization risk.** **CAISO provides a comparison case with a smaller quantified near-term data-center load forecast in the sources cited by Module 1.** These observations are not a complete ranking of investment attractiveness or grid severity.

---

# Why This Module Matters

Module 1 established that power availability is a credible variable for further research. It did not establish that electricity is the sole, primary, or longest-lasting bottleneck for AI infrastructure.

The next question is:

> **Where are those bottlenecks actually occurring?**

For investors, regional differences matter because companies exposed to one electricity market may face very different opportunities and risks than companies operating elsewhere.

Understanding **where power constraints may exist** is a prerequisite for identifying ownership, cost responsibility, and potential economic exposure, which is the focus of Module 3.

---

# Background

## Why the U.S. Grid Cannot Be Viewed as One System

Unlike many countries, the United States does not operate under one nationwide electricity operator.

Different regions have different:

- transmission networks
- wholesale electricity markets
- planning procedures
- interconnection rules
- utility structures
- resource mixes

As a result, an electricity shortage in one region does not necessarily imply a shortage elsewhere.

Likewise, surplus generation at the regional level does not guarantee that a new data center can obtain power at a specific location.

---

## Regional Power Systems Covered

### PJM Interconnection (PJM)

PJM coordinates the transmission grid and wholesale electricity market across the Mid-Atlantic and parts of the Midwest.

Its territory includes **Northern Virginia**, a major concentration of commercial data centers. Module 1 documents rapid commercial-load growth in Virginia but does not independently establish a global market ranking.

---

### Electric Reliability Council of Texas (ERCOT)

ERCOT operates the electric grid serving most of Texas.

Texas has experienced exceptionally rapid growth in proposed AI and data-center projects, making ERCOT one of the most important regions for future electricity demand.

---

### California Independent System Operator (CAISO)

CAISO operates most of California's high-voltage transmission system.

Although California currently shows less immediate AI-related power pressure than PJM, its planning framework provides a valuable comparison for understanding how large electricity users are incorporated into long-term grid planning.

---

# Research Questions

This module addresses four questions.

1. Which regions currently show the strongest AI-related electricity demand?

2. Where are transmission and utility infrastructure becoming deployment constraints?

3. Which regional planning methods produce the most reliable demand forecasts?

4. Which indicators are most useful for investors?

---

# Methodology

Rather than comparing regions using total electricity generation alone, this module evaluates:

- historical demand growth
- projected data-center demand
- transmission constraints
- utility readiness
- project credibility
- forecasting methodology

This approach focuses on **deliverability** rather than generation capacity.

In other words, the key question is not whether electricity exists somewhere in the region, but whether it can reach a specific project when needed.

---

# Regional Analysis

## PJM

### Background

PJM contains a large existing concentration of data-center electricity demand, particularly in Northern Virginia.

Repository sources show rapid commercial-load growth and higher peak-demand forecasts in the Dominion zone. The current evidence is regional and does not isolate AI workloads from all other data-center demand.

### Evidence

Previous research identified:

- rapid commercial electricity demand growth in Virginia
- sustained increases in peak electricity demand
- significant long-term load growth forecasts
- increasing transmission planning requirements

### Interpretation

The evidence suggests that **electricity delivery may be a material constraint** in parts of PJM; it does not establish that delivery is the primary constraint for every project.

Transmission upgrades, substations, and utility infrastructure warrant project-level review when assessing whether new facilities can receive service on schedule.

### Research Relevance

Powered sites, transmission assets, regulated utilities, and related infrastructure are areas for further research. The repository has not yet completed asset ownership, valuation, regulatory recovery, or company-level analysis.

---

## ERCOT

### Background

ERCOT reports a large volume of requested large-load additions. The repository does not contain a complete North American dataset for ranking request volumes.

### Evidence

ERCOT adjusts future demand forecasts to account for:

- project delays
- historical completion rates
- observed electricity usage
- probability that proposed projects become operational

### Interpretation

ERCOT's methodology materially reduces requested large-load additions, indicating that unadjusted requests should not be treated as expected consumption.

Project maturity, ramp timing, and observed utilization are relevant to interpreting the request pipeline.

### Research Relevance

The repository does not yet support a developer-level investment conclusion. A next step is to test which projects have credible schedules, power arrangements, financing, and customer commitments.

---

## CAISO

### Background

California continues to receive increasing large-load applications while developing formal planning processes for future electricity demand.

### Evidence

CAISO incorporates confidence levels, utilization assumptions, and utility applications into long-term forecasts.

### Interpretation

The cited CAISO materials document a formal large-load planning process. The repository does not compare planning quality across operators or establish a general absence of local scarcity.

### Research Relevance

CAISO serves as a comparison case for how large-load forecasts are incorporated into planning.

---

# Cross-Regional Comparison

| Region | Repository observation | Unresolved constraint question | Next research focus |
|---|---|---|---|
| PJM | Concentrated data-center load growth and transmission relevance | Which zones and utilities face binding deliverability limits? | Utility- and zone-level evidence |
| ERCOT | Large requested-load pipeline with explicit forecast haircuts | What share of requested load is likely to become operational? | Project maturity and flexible-load treatment |
| CAISO | Smaller quantified near-term data-center growth in cited sources | Are constraints concentrated within particular utility territories? | Local applications and transmission planning |

---

# Key Findings

1. The reviewed evidence varies materially by region; national aggregates are insufficient for site-level conclusions.

2. Transmission and local deliverability can matter even when aggregate generation appears sufficient.

3. Utility readiness may affect project schedules, but the repository lacks project-level service data.

4. Requested electricity demand should not be treated as operational demand.

5. Of the three regions reviewed, PJM has the clearest repository evidence of concentrated load growth and transmission relevance.

6. ERCOT's requested-load pipeline is large, but its own methodology demonstrates substantial realization uncertainty.

---

# Research Implications

The regional analysis suggests that aggregate electricity statistics are insufficient for investment research. Local deliverability, utility processes, and project maturity require additional work.

Regulated utilities, transmission owners, powered land, interconnection positions, and project developers are research categories, not recommendations. The repository has not yet assessed ownership, valuation, contract quality, regulatory treatment, or expected returns.

---

# Limitations

This module evaluates regional trends rather than individual projects.

Future research should incorporate:

- utility-level analysis
- substation availability
- interconnection queues
- project-level power agreements

---

# Next Module

Module 3 shifts from **where power constraints exist** to **who owns or controls the infrastructure needed to solve them**.

The next module is intended to map regulated utilities, transmission companies, generation owners, equipment suppliers, and data-center developers, then test ownership, cost recovery, competition, and valuation before drawing economic conclusions.
