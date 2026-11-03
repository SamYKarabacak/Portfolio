# Exact identifier extraction and source selection

A study of whether a language model can select the correct record and preserve its identifier exactly.

**Manuscript in preparation**

## The problem

A record can contain several plausible identifiers: some belong to older entries, some to ineligible sources, and some to the requested source. The study separates choosing the right source from copying its value accurately.

Outputs are scored for exact success, wrong-source selection, changed values, and invalid JSON.

## Reproducible evaluation

The study includes frozen synthetic datasets, paired cases, explicit prompts, archived local-model responses, deterministic parser baselines, and scoring and analysis code.

The planned extension reuses 96 paired cases, giving 192 main inputs per model, with separate development and repeat inputs. Content hashes and an offline verifier check the archived data, request construction, and replayed scores.

## Next experiments

I've prepared an extension using newer models, but I haven't run those experiments yet. The model choices and settings still need to be finalized before collecting responses.

The existing results cover the compact models and settings used in the original runs. They don't establish how newer models would perform. The manuscript is still in preparation and has not been submitted.

I'm keeping the working files private while the study is in preparation.

[Portfolio](../README.md)
