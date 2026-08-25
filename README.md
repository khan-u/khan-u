#### Hi, I'm Umais Khan.

I enjoy working at the intersection of computational neuroscience and neural engineering. I build data pipelines and analysis tools that turn messy, multi-channel neural and behavioral time-series into reproducible, queryable results. 

[ORCiD](https://orcid.org/0009-0005-5328-3977) · [LinkedIn](https://linkedin.com/in/umaisk)

#### Neural signal analysis & data engineering
- **[`eeg-feat-ext`](https://github.com/khan-u/eeg-feat-ext)**
  Human iEEG feature extraction (Python + MATLAB) — high-throughput, cycle-level theta waveform features; supported the waveform-shape control analysis that revealed hippocampal phase–amplitude coupling as a memory biomarker.

- **[`theta-feat-warehouse`](https://github.com/khan-u/theta-feat-warehouse)**
  Airflow + DuckDB/SQL warehouse (Python) over the `eeg-feat-ext` features — 12 data-quality gates, paired permutation tests, published to an offline dashboard and [Tableau](https://public.tableau.com/app/profile/umais.khan3104/viz/iEEGFeatureWarehouse/Dashboard1_1); reads real iEEG via a Neurodata Without Borders (NWB) bridge ([DANDI 000673](https://dandiarchive.org/dandiset/000673)).

#### Networked systems & measurement
- **[`prox-voice`](https://github.com/khan-u/prox-voice)**
  Peer-to-peer WebRTC voice mesh in the browser (TypeScript + C++) — audio links form by in-world proximity, no media server. Ground-truth mouth-to-ear latency measured with a custom acoustic rig (C = 66 ± 11 ms, five captures).

- **[`prox-voice-pipeline`](https://github.com/khan-u/prox-voice-pipeline)**
  Spark + dbt + Great Expectations + Airflow pipeline (Python) over the mesh telemetry — rebuilds the report figures from warehouse tables and checks every number against the originals.

#### Open-source contributions
Contributing to **[`movement`](https://github.com/neuroinformatics-unit/movement)** (UCL Neuroinformatics Unit), a Python library for animal-tracking data:
- **Collective-behavior metrics:** proposed a metric suite ([#873](https://github.com/neuroinformatics-unit/movement/issues/873)), added `compute_polarization()` ([#875](https://github.com/neuroinformatics-unit/movement/pull/875)), and a skeleton-agnostic anterior/posterior body-axis inference pipeline ([#945](https://github.com/neuroinformatics-unit/movement/pull/945)).
- **3D vector utilities:** Cartesian/cylindrical/spherical coordinate transforms ([#948](https://github.com/neuroinformatics-unit/movement/pull/948)), being resubmitted as focused PRs per maintainer feedback ([#1036](https://github.com/neuroinformatics-unit/movement/issues/1036), [#1058](https://github.com/neuroinformatics-unit/movement/issues/1058)).

#### Focus
- Neuronal encoding ⇄ decoding
- Signal processing · Time-series analysis · Data engineering · Statistical inference
