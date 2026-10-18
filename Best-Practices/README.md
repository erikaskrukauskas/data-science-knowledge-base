---
title: Best practices index
tags: [practices, index, data-science]
status: verified
updated: 2026-10-17
---

# Best practices

These pages are the stable data-science practices. Lessons in `Lessons-Learned/` capture findings from a particular analysis. When a lesson becomes a general rule, fold it into a page here and leave the lesson in place as the evidence.

These pages do not choose a library, language, or platform. Official documentation for a method or a library lives in [Official-Documentation/README.md](../Official-Documentation/README.md).

| Guide | Use it when |
| --- | --- |
| [Consult before an analysis](01-consult-before-analysis.md) | Starting a significant analysis or modeling choice |
| [Frame the decision](02-frame-the-decision.md) | Stating what the analysis is for |
| [Compare before choosing](03-compare-before-choosing.md) | Choosing a metric, a split, or a model class |
| [Leakage and held-out data](04-leakage-and-held-out-data.md) | Checking that a result can fail on unseen data |
| [Report uncertainty, then record](05-report-uncertainty-then-record.md) | Stating a result and saving a lesson |
| [Reusable and project knowledge](06-reusable-and-project-knowledge.md) | Deciding where a fact belongs |
| [Privacy and secrets](07-privacy-and-secrets.md) | Handling datasets, credentials, or customer data |
| [Write for search](08-write-for-search.md) | Adding a page others can find later |
| [Select an experimental design](09-select-an-experimental-design.md) | Choosing a design from the objective and the factors |
| [Characterize the measurement](10-characterize-the-measurement.md) | Stating bias and variation in the numbers you analyze |
| [Analyze residuals](11-analyze-residuals.md) | Checking that a fit summary hides structured error |
| [Name the confounding](12-name-the-confounding.md) | Refusing a one-factor claim when another effect shares the estimate |
| [State what reproducibility includes](13-state-what-reproducibility-includes.md) | Naming the conditions allowed to change in a repeat |
| [Block a known nuisance](14-block-a-known-nuisance.md) | Isolating a known change so it does not hide the comparison |
| [Randomize the assignment](15-randomize-the-assignment.md) | Assigning conditions so one run does not determine the next |
| [Replicate to separate error](16-replicate-to-separate-error.md) | Repeating a treatment so random error is not mixed with lack of fit |
| [Check for an interaction](17-check-for-an-interaction.md) | Asking whether one factor's effect depends on another |
| [Define the result you report](18-define-the-result-you-report.md) | Stating the number, the conditions it covers, and the claim it does not support |
| [Look before fitting](19-look-before-fitting.md) | Letting the data show its structure before a model family is chosen |
| [Separate exploration from confirmation](20-separate-exploration-from-confirmation.md) | Keeping a data-driven search from being reported as a pre-declared test |
| [Graph before you summarize](21-graphics-before-a-summary.md) | Reading a plot before trusting a single number |
| [Read a 4-plot](22-read-a-4-plot.md) | Checking location, spread, and distribution together |
| [Treat a non-random sequence as structure](23-non-random-sequence.md) | Refusing independent-error claims when the sequence has a pattern |
| [Do not assume a fixed location](24-drifting-location.md) | Checking that the center of the measurements stays put |
| [Do not assume fixed variation](25-changing-variation.md) | Checking that the spread stays constant |
| [Name the distributional assumption](26-distributional-assumption.md) | Saying which shape the probability statements require |
| [Check autocorrelation](27-check-autocorrelation.md) | Seeing whether neighboring measurements move together |
| [Read the histogram](28-read-the-histogram.md) | Using shape, not only the center, to describe measurements |
| [Read a lag plot](29-read-a-lag-plot.md) | Detecting dependence by plotting each point against the previous one |
| [Use a normal probability plot](30-normal-probability-plot.md) | Checking a normal shape without relying on a single test statistic |
| [Plot the run sequence](31-run-sequence-plot.md) | Looking at measurements in collection order |
| [Read a scatter plot](32-read-a-scatter-plot.md) | Judging form, direction, and unusual points before fitting a line |
| [Use a scatterplot matrix](33-scatterplot-matrix.md) | Seeing pairwise relationships before a many-variable model |
| [Require constant spread when the method assumes it](34-constant-spread.md) | Separating a relationship whose spread is stable from one whose spread changes |
| [Treat spread that depends on level as part of the model](35-changing-spread-with-level.md) | Modeling spread that grows or shrinks with the fitted level |
| [Compare groups with a box plot](36-compare-with-a-box-plot.md) | Comparing centers and spreads without letting a few points define the groups |
| [Prefer a resistant location when tails are long](37-resistant-location.md) | Choosing a center that a few extreme points do not own |
| [Report skewness instead of forcing symmetry](38-report-skewness.md) | Describing an asymmetric distribution on its own terms |
| [Use a runs test as a check on order](39-runs-test.md) | Checking whether highs and lows clump in time |
| [Screen outliers with a declared rule](40-screen-outliers-with-a-rule.md) | Deciding how an extreme point is handled before it is deleted |
| [Name the distribution you are using](41-name-the-distribution.md) | Treating a probability distribution as a model, not as a fact about the units |
| [Separate location from scale](42-separate-location-and-scale.md) | Reporting the center and the spread as different properties |
| [Say how the parameters were estimated](43-say-how-parameters-were-estimated.md) | Stating the estimation rule behind a fitted distribution |
| [State the least-squares assumptions](44-least-squares-needs-its-assumptions.md) | Using least squares only when its error assumptions are plausible |
| [Treat the normal model as an assumption](45-normal-model-is-an-assumption.md) | Using a normal model only where the measurements support it |
| [Use a lognormal model for multiplicative measures](46-lognormal-for-multiplicative-measures.md) | Modeling quantities that multiply rather than add |
| [Match a Weibull model to lifetime data](47-weibull-for-lifetimes.md) | Choosing a lifetime model that can speed up or slow down |
| [An exponential model means a constant hazard](48-exponential-means-constant-hazard.md) | Refusing an exponential lifetime model when the risk changes with age |
| [Use a binomial model for bounded counts](49-binomial-for-bounded-counts.md) | Modeling a count of events in a fixed number of trials |
| [Use a Poisson model for counts in an interval](50-poisson-for-unbounded-counts.md) | Modeling a count of events in time or space when the mean and variance match |
| [Pair a mean with an interval](51-interval-for-a-mean.md) | Reporting a range for a mean, not the mean alone |
| [Compare two means on the same footing](52-compare-two-means.md) | Comparing two groups only after the design of the comparison is stated |
| [Compare several groups as one question](53-one-factor-anova.md) | Testing several groups together instead of every pair in isolation |
| [Compare spreads with a resistant check](54-compare-spreads-with-levene.md) | Comparing variation across groups without trusting normality alone |
| [Use Anderson-Darling as a fit check](55-anderson-darling-fit.md) | Checking a named distribution with attention to the tails |
| [Bin a chi-square fit check on purpose](56-chi-square-goodness-of-fit.md) | Comparing observed counts with a named distribution in declared bins |
| [Use Kolmogorov-Smirnov for a continuous comparison](57-kolmogorov-smirnov-fit.md) | Comparing a sample distribution with a reference without arbitrary bins |
| [Bootstrap the sampling spread of a summary](58-bootstrap-the-sampling-spread.md) | Seeing how a summary moves when the sample is redrawn |
| [Transform with a stated reason](59-box-cox-with-a-reason.md) | Changing scale only to meet a stated assumption |
| [Compare distributions with a quantile plot](60-quantile-comparison.md) | Comparing two distributions across their range, not only at the mean |
| [Condition on a factor before pooling](61-condition-on-a-factor.md) | Checking that a relationship is the same inside the levels of another factor |
| [Compare methods with a Youden plot](62-youden-plot-for-labs.md) | Seeing whether two methods or labs agree, and whether one is shifted |
| [Name a mixture instead of averaging two peaks](63-name-a-mixture.md) | Refusing one summary when the histogram has two centers |
| [Keep a check standard](64-keep-a-check-standard.md) | Watching a measurement process with a stable artifact |
| [Name the reference base](65-name-the-reference-base.md) | Saying what a measurement is traced to |
| [Separate bias from accuracy](66-separate-bias-and-accuracy.md) | Distinguishing a systematic shift from the total error |
| [Chart the measurement process](67-chart-the-measurement-process.md) | Detecting a shift in a measurement process over time |
| [Chart short-term precision separately](68-chart-short-term-precision.md) | Watching repeatability on its own chart |
| [Calibrate before you interpret](69-calibrate-before-you-interpret.md) | Turning an instrument reading into a value on the reference scale |
| [Use reference standards in calibration](70-use-reference-standards.md) | Anchoring a calibration in known artifacts |
| [Watch instrument drift during calibration](71-watch-instrument-drift.md) | Keeping a slow instrument shift from looking like a unit difference |
| [Build uncertainty from repeated measurements](72-build-type-a-uncertainty.md) | Using scatter in the data as one component of uncertainty |
| [Do not correct a bias you cannot estimate](73-do-not-correct-a-sparse-bias.md) | Leaving a poorly estimated shift inside the uncertainty |
| [Include time-dependent error in the uncertainty](74-include-time-in-the-uncertainty.md) | Letting day-to-day movement into the reported range |
| [Match the sample to the process](75-match-the-sample-to-the-process.md) | Collecting measurements that represent the process the decision is about |
| [Establish stability before capability](76-establish-stability-first.md) | Refusing a capability number for a process that is still shifting |
| [State capability against named limits](77-capability-needs-limits-and-a-distribution.md) | Comparing a stable process with the limits the decision actually uses |
| [Use an attributes chart for counts of events](78-attributes-when-you-only-have-counts.md) | Charting defectives or defects when the measurement is a count |
| [Select the function deliberately](79-select-the-function-deliberately.md) | Choosing the form of a model before interpreting its coefficients |
| [Put subject knowledge in the function](80-put-scientific-knowledge-in-the-function.md) | Preferring a form the subject demands over a flexible curve |
| [Let the data challenge the function](81-let-the-data-challenge-the-function.md) | Rejecting a preferred form when the measurements contradict it |
| [Weight points when spread changes](82-weight-when-spread-changes.md) | Giving less influence to noisier observations |
| [Detect non-constant variation in the residuals](83-detect-non-constant-variation.md) | Finding a spread that changes across the fitted values |
| [Check that successive errors are independent](84-check-independent-errors.md) | Refusing an independent-error interval when residuals follow each other |
| [Drop terms that do no work](85-drop-terms-that-do-no-work.md) | Removing a term that the measurements do not support |
| [Improve a poor fit from the residuals](86-improve-a-poor-fit-from-the-residuals.md) | Changing the function because the residual plot shows a specific gap |
| [Give a prediction its own uncertainty](87-prediction-has-its-own-uncertainty.md) | Separating a fitted mean from a prediction of a new observation |
| [A calibration inverts the fitted function](88-calibration-inverts-the-fit.md) | Inferring an input from an output, with the uncertainty that reversal adds |
| [Optimize inside the observed region](89-optimize-inside-the-observed-region.md) | Keeping an optimum inside the conditions actually studied |
| [Prefer a prediction that uses the factors that matter](90-prefer-a-parsimonious-prediction.md) | Leaving out factors that do not change the prediction |
| [Read the design resolution before quoting effects](91-read-the-design-resolution.md) | Knowing which effects a fractional design can separate |
| [Add center points to see curvature](92-add-center-points-for-curvature.md) | Checking a straight-line factor model for a bend in the middle |
| [Keep the optimum inside the experimental region](93-keep-the-optimum-in-the-experimental-region.md) | Refusing an optimum the experiment never reached |
| [Stop when the process leaves control](94-stop-when-the-process-leaves-control.md) | Treating a control-chart signal as a reason to look for a cause |
| [An in-control process can still miss the need](95-in-control-can-still-miss-the-need.md) | Separating statistical control from meeting the decision's limits |
| [Treat acceptance sampling as a risk trade](96-acceptance-sampling-is-a-risk-trade.md) | Accepting a lot from a sample, with a stated chance of the wrong decision |
| [Choose the sampling plan from the risks](97-choose-the-sampling-plan-from-the-risks.md) | Picking a sample size and an accept number from the risks you will tolerate |
| [Read the operating characteristic of the plan](98-read-the-operating-characteristic.md) | Seeing the chance a plan accepts a lot at each quality level |
| [Stop a sequential sample on a pre-set rule](99-sequential-sampling-stops-on-a-rule.md) | Allowing sample size to vary only under a rule fixed in advance |
| [Chart a measured variable with limits from a stable period](100-chart-a-measured-variable.md) | Using a variables chart for a measured amount |
| [Model dependence in a time series](101-model-time-series-dependence.md) | Treating an ordered series as a series, not as a pile of independent points |
| [A moving average is a smoother, not a cause](102-a-moving-average-is-a-smoother.md) | Keeping a smoothed display from being treated as the measured series |
| [Treat exponential smoothing as a forecast](103-exponential-smoothing-is-a-forecast.md) | Using a smoother to forecast, and checking the forecast errors |
| [Scale variables before a principal-component summary](104-principal-components-need-a-scale.md) | Combining correlated measurements without letting units dominate |
| [A test answers a pre-declared question](105-a-test-answers-a-predeclared-question.md) | Using a statistical test only for the comparison named in advance |
| [Report the interval, not only whether a hurdle was cleared](106-report-the-interval-not-only-the-p.md) | Putting a difference and its uncertainty ahead of a yes-or-no label |
| [Say what the confidence interval covers](107-say-what-the-interval-covers.md) | Interpreting an interval as a range for a parameter under stated assumptions |
| [Read a test and an interval as the same comparison](108-a-test-and-an-interval-are-the-same-comparison.md) | Avoiding a significant test that contradicts the interval you would report |
| [Handle outliers before a group comparison](109-handle-outliers-in-a-comparison.md) | Keeping a few points from deciding a group comparison |
| [A trend can invalidate a pooled comparison](110-a-trend-can-invalidate-a-comparison.md) | Refusing to pool periods that are drifting |
| [Separate variance components](111-separate-variance-components.md) | Saying which layer of a nested process produces the spread |
| [Account for multiple comparisons](112-account-for-multiple-comparisons.md) | Paying for every comparison you were willing to highlight |
| [Put an interval on a difference of means](113-interval-for-a-difference.md) | Reporting how large a group difference is, not only that it exists |
| [Treat censored lifetimes as incomplete, not as failures](114-censored-lifetimes-are-incomplete.md) | Keeping a unit that has not failed yet in the lifetime analysis |
| [An accelerated test is an extrapolation](115-acceleration-is-an-extrapolation.md) | Carrying a high-stress result to use conditions only under a named model |
| [Choose a life distribution from the failure pattern](116-choose-a-life-distribution-from-the-failures.md) | Picking a lifetime model from how failures accumulate, not from convenience |
| [Treat reliability growth as a changing rate](117-reliability-growth-is-a-changing-rate.md) | Separating a system that is being fixed from a system with a fixed failure rate |
| [Estimate life from censored data with a method that uses the censoring](118-estimate-life-from-censored-data.md) | Fitting a lifetime model without dropping units that have not failed |
