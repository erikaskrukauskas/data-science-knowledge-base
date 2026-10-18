---
title: Select an experimental design
tags: [practices, experiment, design, comparison]
status: verified
updated: 2026-10-17
---

# Select an experimental design

Choose the design from the decision the experiment supports and from how many factors you will change. A design that answers a different question does not become useful because it used the same measurements.

The NIST/SEMATECH e-Handbook states: "The choice of an experimental design depends on the objectives of the experiment and the number of factors to be investigated." ([How do you select an experimental design?](https://www.itl.nist.gov/div898/handbook/pri/section3/pri33.htm), checked 2026-10-17.)

## Match the design to the objective

Name the objective before picking a layout:

- **Comparative.** One factor matters in advance, and the question is whether the response changes across its levels.
- **Screening.** Many factors are candidates, and the question is which main effects are large enough to keep.
- **Response surface.** The question needs interactions or curvature, such as where the response improves.
- **Mixture.** The factors are proportions of a whole, and the question is which proportions improve the response.
- **Regression.** The question is a fitted relationship between continuous factors and the response, with estimates that are not systematically bent by the chosen runs.

Within a type, the handbook says the choice also depends on the runs you can afford and on how much control you want over a false conclusion. Leave spare runs for a center check and for repeating a run that failed in execution.

## What to state

State the response, the factors you will change, the factors you will hold still, and the unit that receives a run. That unit is part of the population in [Frame the decision](02-frame-the-decision.md). The comparison the design can support is the check that defines done.

Randomly assign units to the conditions the design names when the assignment itself could favor one condition. Record the assignment. A later analysis should be able to tell which units received which levels.

## After the runs

Analyze the design you ran. Do not treat an unused factor layout as if it had been executed. If the result will be compared with a model fit on other data, keep that comparison on data the fit did not see. See [Leakage and held-out data](04-leakage-and-held-out-data.md).

Report the estimate with uncertainty. See [Report uncertainty, then record](05-report-uncertainty-then-record.md).
