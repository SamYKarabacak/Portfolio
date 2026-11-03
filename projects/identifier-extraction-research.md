# Exact identifier extraction and source selection

A study of whether a language model can select the correct record and preserve its identifier exactly.

**Manuscript in preparation**

## The problem

A record can contain several plausible identifiers: some belong to older entries, some to ineligible sources, and some to the requested source. The study separates choosing the right source from copying its value accurately.

Outputs are scored for exact success, wrong-source selection, changed values, and invalid JSON.

## Reproducible evaluation

The working project contains frozen synthetic datasets, paired cases, explicit prompts, archived local-model responses, deterministic parser baselines, and scoring and analysis code.

The planned extension reuses 96 paired cases, giving 192 main inputs per model, with separate development and repeat inputs. Content hashes and an offline verifier check the archived data, request construction, and replayed scores.

## Next experiments

The current-model extension is prepared, but new model responses have not been collected. Model access, execution settings, and the final protocol need to be checked and frozen before those runs.

Historical compact-model results describe their recorded configurations. They do not establish the performance of newer hosted models. Independent semantic review and author approval are still pending, and the manuscript has not been submitted.

The working files remain private while the study is being prepared.

[Portfolio](../README.md)
