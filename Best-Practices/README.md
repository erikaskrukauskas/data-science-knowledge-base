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
| [Use a Latin square when two nuisances both matter](119-use-a-latin-square-for-two-nuisances.md) | Removing two crossed nuisances when each has the same number of levels as the treatment |
| [Use a Plackett-Burman design only to screen](120-use-a-plackett-burman-screen.md) | Screening many factors for main effects while leaving interactions aliased |
| [Use a central composite design when the surface may curve](121-use-a-central-composite-for-curvature.md) | Adding axial points so a factorial can estimate a curved surface |
| [Use a Box-Behnken design to stay inside the region](122-use-a-box-behnken-inside-the-region.md) | Estimating curvature without running the corners of the factor space |
| [Block a response surface when the runs will not fit in one session](123-block-a-response-surface.md) | Keeping session-to-session shifts out of a curved-surface fit |
| [Fold a fraction over to clear an alias you now care about](124-fold-a-fraction-to-clear-aliases.md) | Adding the mirror fraction so a chosen alias can be separated |
| [Use three levels when curvature is the question](125-use-three-levels-when-curvature-is-expected.md) | Choosing three factor levels because a two-level design cannot see curvature |
| [Climb with steepest ascent only inside a local plane](126-climb-with-steepest-ascent.md) | Following a fitted slope as a search path rather than calling it the optimum |
| [Choose the step length on the ascent on purpose](127-choose-the-step-length-on-purpose.md) | Setting how far to move along a search path before the local fit stops holding |
| [Combine responses with a desirability you can state](128-combine-responses-with-a-named-desirability.md) | Turning several responses into one score only after the trade is written down |
| [Treat a mixture as a composition, not as independent factors](129-treat-a-mixture-as-a-composition.md) | Designing and interpreting factors that must sum to a fixed total |
| [Respect the constraints on a mixture](130-respect-mixture-constraints.md) | Keeping a mixture experiment inside the compositions you can actually make |
| [Separate mixture amounts from process settings](131-separate-mixture-amounts-from-process-settings.md) | Keeping recipe components distinct from the process settings used to run them |
| [Honor restricted randomization](132-honor-restricted-randomization.md) | Testing a hard-to-change factor against the error layer that matches how it was randomized |
| [Separate control factors from noise factors](133-separate-control-factors-from-noise-factors.md) | Studying how settings you can control change the effect of variation you cannot |
| [Use an optimal design when a classical design does not fit](134-use-an-optimal-design-when-the-region-is-irregular.md) | Computing a run list only when the region or the model defeats a standard design |
| [Confirm a designed result with new runs](135-confirm-a-designed-result-with-new-runs.md) | Checking a design conclusion with runs that were not used to fit it |
| [Read a half-normal plot of effects before keeping terms](136-read-a-half-normal-plot-of-effects.md) | Separating a few large effects from noise on an unreplicated factorial |
| [Separate engineering significance from a statistical test](137-separate-engineering-significance-from-a-test.md) | Judging an effect by whether it changes the decision, not only by a test |
| [Scale factors to the region you will run](138-scale-factors-to-the-region-you-will-run.md) | Choosing factor ranges and saying whether the fit is in coded or process units |
| [Randomize completely when there is no block](139-randomize-completely-when-there-is-no-block.md) | Using a fully randomized layout only when no known nuisance needs a block |
| [Screen before you model the surface](140-screen-before-you-model-the-surface.md) | Using an early design to drop factors, then building a new design for the ones that remain |
| [Check the measurement before the experiment](141-check-the-measurement-before-the-experiment.md) | Showing the measurement can resolve the effect before spending the experimental runs |
| [Show the process is stable before experimenting on it](142-show-the-process-is-stable-before-experimenting.md) | Refusing to attribute a change to the factors while the process is drifting |
| [Use a simplex lattice for an unconstrained mixture](143-use-a-simplex-lattice-for-an-unconstrained-mixture.md) | Placing mixture runs so a stated composition model can be estimated |
| [Prefer a smaller composite only when you can say what it gives up](144-prefer-a-smaller-composite-when-runs-are-scarce.md) | Saving runs on a curved surface only after naming the precision you give up |
| [Repair a design when planned runs are lost](145-repair-a-design-when-planned-runs-are-lost.md) | Replacing or narrowing a design after planned runs cannot be made |
| [State a Type B uncertainty as a judgment, not as a repeat](146-state-a-type-b-uncertainty.md) | Including an uncertainty component that comes from a stated bound rather than from repeats |
| [Build an uncertainty budget before you combine components](147-build-an-uncertainty-budget.md) | Listing each uncertainty component and how strongly the result depends on it |
| [Propagate uncertainty through the function you are using](148-propagate-uncertainty-through-the-function.md) | Carrying input uncertainties through the function that produces the reported result |
| [Check gauge linearity across the range you will use](149-check-gauge-linearity-across-the-range.md) | Seeing whether gauge bias stays constant across the range you will report |
| [Compare gauges before you pool their measurements](150-compare-gauges-before-you-pool-them.md) | Refusing to pool gauges until their differences have been compared |
| [Separate gauge variation from part variation](151-separate-gauge-variation-from-part-variation.md) | Splitting observed spread into the measurement and the parts being measured |
| [Estimate repeatability from repeats under the same conditions](152-estimate-repeatability-from-repeats.md) | Keeping same-condition repeat spread distinct from variation across conditions |
| [Match a nested gauge study to the way the measurement is nested](153-match-a-nested-gauge-study-to-the-measurement.md) | Estimating measurement components from a study whose factors were nested |
| [Compare a check standard with a propagation](154-compare-a-check-standard-with-a-propagation.md) | Using disagreement between a check standard and a propagation as a finding |
| [Widen a calibration uncertainty where the curve bends](155-widen-a-calibration-uncertainty-where-the-curve-bends.md) | Reporting calibration uncertainty at the level where the result is read |
| [Use nonlinear least squares when the function is nonlinear in the parameters](156-use-nonlinear-least-squares-for-a-nonlinear-function.md) | Fitting a function that is nonlinear in its parameters on the scale you will use |
| [Use a local smooth when you will not name a function](157-use-a-local-smooth-when-you-will-not-name-a-function.md) | Describing a trend with a local smooth while you still have no function to stand behind |
| [Say whether the predictors were measured with error](158-say-whether-the-predictors-were-measured-with-error.md) | Stating whether predictors were set exactly or measured with their own error |
| [Test for a missing term instead of trusting a significant fit](159-test-for-a-missing-term.md) | Checking a named alternative instead of stopping at a small residual |
| [Look for drift while the model data were collected](160-look-for-drift-while-the-model-was-fit.md) | Keeping a time trend during data collection from being absorbed into the fit |
| [Judge the function apart from the noise](161-judge-the-function-apart-from-the-noise.md) | Deciding the function is sufficient only when residuals no longer show a missing pattern |
| [Prefer a physical function when you have one](162-prefer-a-physical-function-when-you-have-one.md) | Fitting the mechanism's function when you intend to interpret the parameters |
| [An optimal design is optimal only for the model you named](163-an-optimal-design-is-optimal-for-a-named-model.md) | Refusing a computed design until the model and the criterion are named |
| [Analyze paired observations as pairs](164-analyze-paired-observations-as-pairs.md) | Comparing within pairs instead of treating matched observations as independent samples |
| [Compare a proportion with a requirement on the proportion scale](165-compare-a-proportion-with-a-requirement.md) | Judging a defective rate against a requirement stated on the proportion scale |
| [Compare a defect density with a count model](166-compare-a-defect-density-with-a-count-model.md) | Judging a count per unit of opportunity with a count model |
| [Use a tolerance interval when the question is a proportion of units](167-use-a-tolerance-interval-for-a-proportion-of-units.md) | Covering a stated share of future units rather than the mean alone |
| [Choose the sample size for the comparison you will report](168-choose-the-sample-size-for-the-comparison.md) | Sizing a sample from the difference, the uncertainty, and the variation you will stand behind |
| [Compare two proportions as proportions](169-compare-two-proportions-as-proportions.md) | Comparing two defective rates with a procedure made for proportions |
| [Compare failure rates on the rate scale](170-compare-failure-rates-on-the-rate-scale.md) | Comparing two lifetime processes on their rates after stating the life model |
| [Use a rank test when you will not assume a shape](171-use-a-rank-test-when-you-will-not-assume-a-shape.md) | Comparing several groups by ranks when a shared shape is not assumed |
| [Use a two-way layout when two factors are crossed](172-use-a-two-way-layout-when-two-factors-are-crossed.md) | Analyzing two crossed factors together so neither is dumped into the error |
| [Compare several proportions as a family](173-compare-several-proportions-as-a-family.md) | Reading every pair among several proportions as one family of comparisons |
| [Test a spread against a named standard](174-test-a-spread-against-a-named-standard.md) | Comparing an observed spread with a standard value under a stated shape |
| [Analyze several factors together when they were varied together](175-analyze-several-factors-together.md) | Keeping jointly varied factors in one analysis so their interactions stay visible |
| [Use a systematic effect order for a two-level factorial](176-use-yates-order-for-a-two-level-factorial.md) | Estimating two-level factorial effects in a declared order and reading the aliases |
| [Use an extreme-value model for a minimum or a maximum](177-use-an-extreme-value-model-for-a-minimum-or-a-maximum.md) | Modeling a minimum or a maximum with a distribution made for extremes |
| [Use a probability-plot correlation to compare candidate shapes](178-use-a-probability-plot-correlation-to-compare-shapes.md) | Comparing candidate distributions by how well they straighten a probability plot |
| [Report a percentile when the question is a percentile](179-report-a-percentile-when-the-question-is-a-percentile.md) | Reporting the value a stated share of units falls below, with an interval |
| [Compare a mean with a standard value you did not estimate](180-compare-a-mean-with-a-standard-value.md) | Comparing an estimate with a number that was stated rather than with a second sample |
| [Compare a spread with a standard value](181-compare-a-spread-with-a-standard-value.md) | Judging observed spread against a stated nominal value |
| [Use Tukey when every pair of means is in play](182-use-tukey-when-every-pair-of-means-is-in-play.md) | Adjusting every pair of means only when every pair was actually in play |
| [Compare two groups by rank when the shape is unknown](183-compare-two-groups-by-rank-when-the-shape-is-unknown.md) | Comparing two groups on ranks when a mean difference is not the claim |
| [Distinguish a repairable system from a life distribution](184-distinguish-a-repairable-system-from-a-life-distribution.md) | Choosing a recurrence model or a lifetime model according to whether the unit is repaired |
| [Define the hazard you are estimating](185-define-the-hazard-you-are-estimating.md) | Saying whether failure risk is constant or changes with age |
| [Read a bathtub curve as three regimes](186-read-a-bathtub-curve-as-three-regimes.md) | Separating early failure, a flat middle, and wear-out instead of quoting one life number |
| [Report a repair rate for a system that is fixed and returned](187-report-a-repair-rate-for-a-system-that-is-fixed.md) | Summarizing recurrent repairs of a system that stays in service |
| [Name an Arrhenius model when temperature is the stress](188-name-an-arrhenius-model-when-temperature-is-the-stress.md) | Using a temperature-acceleration equation only for a temperature stress |
| [Name the Eyring factors when the stress is not temperature alone](189-name-the-eyring-factors-when-stress-is-not-only-temperature.md) | Choosing an Eyring acceleration equation because the stress mechanism calls for it |
| [Use proportional hazards when a factor multiplies the hazard](190-use-proportional-hazards-when-a-factor-multiplies-the-hazard.md) | Modeling a factor as a multiplier on the hazard only while that assumption holds |
| [Use a homogeneous Poisson process for a constant repair rate](191-use-a-homogeneous-poisson-process-for-a-constant-repair-rate.md) | Adopting a constant repair rate only after the trend has been checked |
| [Use a power-law process when the repair rate changes smoothly](192-use-a-power-law-process-when-the-repair-rate-changes.md) | Letting a repair rate rise or fall as a power of time, and reporting that power |
| [Build system reliability from the failure modes](193-build-system-reliability-from-the-failure-modes.md) | Combining component failure modes through a stated system structure |
| [Plot reliability growth before you fit a growth model](194-plot-reliability-growth-before-you-fit-it.md) | Looking at the cumulative failure rate before fitting a growth slope |
| [Plan for a test that may produce no failures](195-plan-for-a-test-that-may-produce-no-failures.md) | Reporting a bound from a test with no failures instead of a rate of zero |
| [Use a nonparametric survival curve when you will not name a distribution](196-use-a-nonparametric-survival-curve-when-you-will-not-name-a-distribution.md) | Estimating survival without a life distribution, censoring included |
| [Plot the cumulative hazard before you pick a life model](197-plot-the-cumulative-hazard-before-you-pick-a-life-model.md) | Matching the life distribution to the way risk accumulates with age |
| [State the prior in a Bayesian reliability claim](198-state-the-prior-in-a-bayesian-reliability-claim.md) | Including the prior as part of a reliability claim, and showing how far the data moved it |
| [Model degradation when the failure is a threshold on a measured drift](199-model-degradation-when-failures-are-rare.md) | Inferring life from measured drift toward a failure threshold |
| [Project reliability to the use condition you named](200-project-reliability-to-the-use-condition.md) | Carrying an accelerated result to a named use condition through the acceleration model |
| [A gamma prior is a claim about the failure rate](201-a-gamma-prior-is-a-claim-about-the-rate.md) | Writing down the mean and the weight of a gamma prior on a failure rate |
| [Keep quality and reliability as different questions](202-keep-quality-and-reliability-as-different-questions.md) | Separating a result at manufacture from a result after time in use |
| [State a multiplicative degradation model when damage multiplies](203-state-a-multiplicative-degradation-model.md) | Fitting degradation on the multiplicative scale the mechanism claims |
| [Separate an exponential growth model from a power law](204-separate-an-exponential-growth-model-from-a-power-law.md) | Choosing between an exponential and a power-law model for a changing repair rate |
| [Require stationarity before a fixed time-series model](205-require-stationarity-before-a-fixed-time-series-model.md) | Refusing a fixed series model while the level or the dependence is still changing |
| [Model a season instead of calling it noise](206-model-a-season-instead-of-calling-it-noise.md) | Treating a repeating seasonal pattern as structure with a stated period |
| [Read a partial autocorrelation before you set an autoregressive order](207-read-a-partial-autocorrelation-before-an-autoregression.md) | Choosing an autoregressive order from the lags that remain after nearer lags |
| [Chart individuals when you cannot form a rational subgroup](208-chart-individuals-when-you-cannot-form-a-rational-subgroup.md) | Plotting one measurement at a time when no rational subgroup exists |
| [Use a cusum when a small persistent shift is the signal](209-use-a-cusum-when-a-small-shift-is-the-signal.md) | Accumulating small deviations so a persistent shift is visible |
| [Use an EWMA when recent points should count more than old ones](210-use-an-ewma-for-a-small-shift.md) | Weighting recent points more heavily so a small shift can show on a chart |
| [Use double sampling only under a plan written in advance](211-use-double-sampling-only-under-the-plan.md) | Allowing a second sample only inside a continue region fixed before inspection |
| [Skip lots only after a history you stated](212-skip-lots-only-after-a-history-you-stated.md) | Skipping lots only under a qualification rule, and returning when that rule fails |
| [Chart several measurements together when they move together](213-chart-several-measurements-together-when-they-move-together.md) | Watching correlated measurements as one vector so a joint shift is visible |
| [Check time-series residuals before you use the forecast](214-check-time-series-residuals-before-you-use-the-forecast.md) | Requiring forecast residuals to look like noise before the forecast interval is used |
| [Use multiple sampling only with the full plan in view](215-use-multiple-sampling-only-with-the-full-plan.md) | Staging inspection across several samples only under boundaries fixed in advance |
| [Chart a proportion with limits made for a proportion](216-chart-a-proportion-with-limits-made-for-a-proportion.md) | Setting chart limits for a rate of events rather than reusing limits from a measured variable |
| [Use double smoothing when the series has a trend](217-use-double-smoothing-when-the-series-has-a-trend.md) | Forecasting a local slope with double smoothing and checking it on later observations |
| [Identify a time-series model before you estimate it](218-identify-a-time-series-model-before-you-estimate-it.md) | Choosing the series model from the dependence plots before estimating its coefficients |
