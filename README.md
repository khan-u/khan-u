#### Hi, I'm Umais Khan.

I enjoy working at the intersection of computational neuroscience and neural engineering. I build data pipelines and analysis tools that turn messy, multi-channel neural and behavioral time-series into reproducible, queryable results. 

[ORCiD](https://orcid.org/0009-0005-5328-3977) · [LinkedIn](https://linkedin.com/in/umaisk)

#### Neural signal analysis & data engineering
- **[`eeg-feat-ext`](https://github.com/khan-u/eeg-feat-ext)**
  High-throughput pipeline for extracting cycle-level theta waveform features from human iEEG, built to support a waveform-shape control analysis which revealed HPC phase-amplitude coupling as a biomarker for memory.

- **[`theta-feat-warehouse`](https://github.com/khan-u/theta-feat-warehouse)**
  An Airflow pipeline that loads the `eeg-feat-ext` theta features into a DuckDB/SQL warehouse, gates them through 12 data-quality checks, runs paired permutation tests, and publishes the results to an offline dashboard and [Tableau](https://public.tableau.com/app/profile/umais.khan3104/viz/iEEGFeatureWarehouse/Dashboard1_1). Reads real iEEG through an NWB bridge ([DANDI 000673](https://dandiarchive.org/dandiset/000673)).

#### Open-source contributions
Contributing to **[`movement`](https://github.com/neuroinformatics-unit/movement)** (UCL Neuroinformatics Unit), a Python library for animal-tracking data:
- **Collective-behavior metrics:** proposed a metric suite ([#873](https://github.com/neuroinformatics-unit/movement/issues/873)), added `compute_polarization()` ([#875](https://github.com/neuroinformatics-unit/movement/pull/875)), and a skeleton-agnostic anterior/posterior body-axis inference pipeline ([#945](https://github.com/neuroinformatics-unit/movement/pull/945)).
- **3D vector utilities:** Cartesian/cylindrical/spherical coordinate transforms ([#948](https://github.com/neuroinformatics-unit/movement/pull/948)), being resubmitted as focused PRs per maintainer feedback ([#1036](https://github.com/neuroinformatics-unit/movement/issues/1036), [#1058](https://github.com/neuroinformatics-unit/movement/issues/1058)).

#### Focus
- Neuronal encoding ⇄ decoding
- Signal processing · Time-series analysis · Data engineering · Statistical inference
