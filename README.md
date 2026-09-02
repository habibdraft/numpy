I build tools for making structure in time-series data explicit and checkable.

### FeatureGraph

An open framework for deterministic, inspectable, and reproducible scientific
data analysis. A researcher declares what the data contains and what should be
grouped, measured, compared, and checked; FeatureGraph carries out those
declared steps and keeps the evidence behind each result.

- [featuregraph/featuregraph](https://github.com/featuregraph/featuregraph) — the framework (MIT)
- [featuregraph/featuregraph-research](https://github.com/featuregraph/featuregraph-research) — studies and reproducibility record
- [doi.org/10.5281/zenodo.21984186](https://doi.org/10.5281/zenodo.21984186) — archived beta `v0.1.0b1`
- [featuregraph.ai](https://featuregraph.ai)

### Where it came from

The repositories here go back to 2016. The thread running through them is state
representation: a reinforcement learning agent evaluates states, and what it can
learn is bounded by how well those states are described — but the description is
usually taken as given. Treating it as the problem itself is what led to
FeatureGraph, by way of signal interpretation (2022), a first feature graph
builder (2024), and a declarative language for signal transformations (2026).

Full arc in [Origins](https://github.com/featuregraph/featuregraph-research#origins).
