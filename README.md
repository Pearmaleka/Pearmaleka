<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img alt="Le Nam Khanh. Statistics of evaluation, backtests, LLM agents. The best of 1,000 random strategies rises in sample; the same strategy goes nowhere out of sample." src="assets/header-light.svg" width="100%">
</picture>

Data Science and AI student at the Hong Kong Polytechnic University (Elite Class Scheme). I work
on the statistics of evaluation: when a benchmark score, a backtest or an AI agent's answer
can be trusted, and how to tell when it cannot.

**Evaluation and inference**

- [qlib-oos-audit](https://github.com/Pearmaleka/qlib-oos-audit): re-ran Microsoft Qlib's
  Alpha158 / CSI 300 benchmark on six more years of data. Rank IC fell 58% after mid-2020 and
  the model ranking reversed; the label normalisation explains much of it. 13-page paper.
- [overfit](https://github.com/Pearmaleka/overfit): deflated Sharpe ratio, PBO, White's Reality
  Check, Hansen's SPA, Romano–Wolf and purged CV. Of 2,902 technical trading rules, none beats
  buy-and-hold on US indices once the search is accounted for.
- [confidently-wrong](https://github.com/Pearmaleka/confidently-wrong): proof that agreement-based
  confidence scores (self-consistency, semantic entropy) cannot detect an LLM agent's systematic
  errors at any number of runs.
- [stat-traps](https://github.com/Pearmaleka/stat-traps): a benchmark of statistical traps
  (spurious regression, multiple testing, leakage) for LLM data-analysis agents.

**Quantitative finance**

- [pit-fundamentals](https://github.com/Pearmaleka/pit-fundamentals): point-in-time store of
  87M facts from 70 quarters of SEC filings. Measures filing lags, silent revisions and the
  look-ahead bias they cause in a cross-sectional signal.
- [conformal-var.](https://github.com/Pearmaleka/conformal-var.): online conformal calibration
  of Value-at-Risk, checked with the Kupiec, Christoffersen and Basel traffic-light backtests.

**Data infrastructure**

- [pitstore](https://github.com/Pearmaleka/pitstore): point-in-time feature store on DuckDB.
- [tinylake](https://github.com/Pearmaleka/tinylake): a lakehouse table format in ~1,200 lines
  of Python, with ACID commits, optimistic concurrency and data skipping.

Python · PyTorch · DuckDB · SQL · C++ · LaTeX

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Pearmaleka/Kian-Le/output/snake-dark.svg">
  <img alt="Contribution graph eaten by a snake" src="https://raw.githubusercontent.com/Pearmaleka/Kian-Le/output/snake.svg">
</picture>
