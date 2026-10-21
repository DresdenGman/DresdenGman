<p align="center">
  <img src="assets/profile-banner.svg" alt="Dresden — building trustworthy computational tools through reliable machine learning, scientific open source, and probabilistic systems" width="100%">
</p>

<p align="center">
  <a href="https://github.com/DresdenGman/open-source-contributions">Open-source portfolio</a>
  ·
  <a href="https://gert-d.vercel.app">GERT</a>
  ·
  <a href="https://epsilon-livid.vercel.app/landing">EPSILON</a>
  ·
  <a href="https://dresdengman.github.io/the-backtest-that-lied">The Backtest That Lied</a>
  ·
  <a href="https://github.com/DresdenGman/pjm-polar-vortex-paper">PJM research</a>
</p>

I am a student developer working at the intersection of applied mathematics, machine learning, and scientific software. I build systems that make **uncertainty, provenance, assumptions, and failure conditions** visible—then test whether their conclusions still hold outside a clean demonstration.

My work has moved from training models and optimizing headline accuracy toward a harder question: **when should a computational result be trusted?** That question now connects my open-source engineering, energy-risk research, and quantitative decision tools.

## Open-source engineering

| Verified outcome | Snapshot |
| --- | ---: |
| Merged upstream engineering pull requests | **21** |
| Curated-resource listings | **1**, counted separately |
| Upstream repositories | **14** |
| Upstream owners | **13** (11 organizations, 2 individual owners) |
| Historical recipient-repository reach (October 9, 2026) | **253,097 stars** |

<sub>Contribution status verified October 21, 2026 (UTC): 21 upstream engineering merges and 1 separate directory listing. Own-project PRs and resource listings are excluded from the engineering total and its 14-repository / 13-owner metrics. The star total retains the October 9, 2026 (America/Los_Angeles) snapshot and was not remeasured; repository stars are context, not stars earned by my patches. See the <a href="https://github.com/DresdenGman/open-source-contributions/blob/main/METHODOLOGY.md">portfolio methodology and dated evidence</a>.</sub>

Selected work:

- **[StatsForecast #1241](https://github.com/Nixtla/statsforecast/pull/1241)**: exposed an optional fixed theta in AutoTheta, OptimizedTheta and DynamicOptimizedTheta, with optimizer-aligned validation and fit/forecast regression tests. Merged October 20; published-release availability and adoption are not claimed.

- **[SALib #693](https://github.com/SALib/SALib/pull/693)** — merged a Morris sampling reliability guard for unbounded distributions. The final version validates endpoints before sampling and includes maintainer refinements and regression tests. SALib now accounts for five merged upstream contributions.

- **[MAPIE #953](https://github.com/scikit-learn-contrib/MAPIE/pull/953)** — added AUROC and AUARC APIs for evaluating uncertainty estimates, including validation, tests, documentation, and review-driven iteration.
- **[Fairlearn #1674](https://github.com/fairlearn/fairlearn/pull/1674)** — integrated confidence-interval detection into the public `MetricFrame` plotting API with edge-case coverage.
- **[BeeWare Briefcase #2939](https://github.com/beeware/briefcase/pull/2939)** — hardened GitHub Actions through least-privilege permissions, pinned action references, credential-exposure reduction, and zizmor scanning.
- **[StatsForecast #1175](https://github.com/Nixtla/statsforecast/pull/1175)** — added conformal-error prediction intervals and supporting tests.
- **[NeuralForecast #1563](https://github.com/Nixtla/neuralforecast/pull/1563)** — implemented FreDF, a loss combining time- and frequency-domain error.

Every merged upstream engineering contribution has an evidence-backed writeup covering diagnosis, implementation, validation, review, and lessons learned: **[explore all merged work →](https://github.com/DresdenGman/open-source-contributions)**

**External resource inclusion:** EPSILON's 25-minute Assumption Clinic was [included in awesome-quant](https://github.com/wilsonfreitas/awesome-quant/pull/735) on October 19, 2026. This is a curated listing, not evidence of learner adoption or validation of trading performance.

## Featured work

| Project | What it investigates |
| --- | --- |
| **[GERT — Grid Extreme Risk Toolkit](https://github.com/DresdenGman/Grid-Extreme-Risk-Toolkit-GERT-)** · [Live](https://gert-d.vercel.app) | A probabilistic decision-support system for grid stress, tail risk, scenario intervention, and explicit data/model provenance. Its real-model path is gated by calibration rather than promoted when the evidence is insufficient. |
| **[EPSILON — Quantitative Decision Lab](https://github.com/DresdenGman/EPSILON-trading-simulator)** · [Live](https://epsilon-livid.vercel.app/landing) | A research environment for turning market ideas into falsifiable claims while keeping execution assumptions, provenance, negative evidence, and failure conditions visible. |
| **[The Backtest That Lied](https://github.com/DresdenGman/the-backtest-that-lied)** · [Live](https://dresdengman.github.io/the-backtest-that-lied) | A forensic ML study in which a near-perfect signal collapsed after leakage repair and failed again under costs and liquidity constraints—leading to a documented decision to terminate the strategy. |
| **[PJM Extreme-Winter Forecasting](https://github.com/DresdenGman/pjm-polar-vortex-paper)** | Ongoing research into how ordinary annual validation can conceal probabilistic forecast failure during rare cold events. The manuscript remains in development. |

## How I work

- **Negative results are results.** I preserve failed tests and stop hypotheses that do not survive their decision gates.
- **Reliability needs more than accuracy.** I examine uncertainty, calibration, subgroup behavior, leakage, distribution shift, and reproducibility.
- **Claims should remain inspectable.** I separate simulated from live data, document provenance, and link public statements to code, tests, or primary records.
- **Review is part of the engineering.** Maintainer feedback, scope reduction, edge cases, and regression tests are recorded—not hidden from the final story.

## Current direction

I am connecting two lines of work that began separately: **applied modeling** and **reviewed open-source engineering**. My next projects revisit real modeling problems with stronger validation, uncertainty quantification, and fairness analysis—using the same standards I learned while contributing to public scientific software.

<p align="center">
  <a href="https://github.com/DresdenGman/open-source-contributions"><strong>Contribution dashboard and merged writeups →</strong></a>
</p>
