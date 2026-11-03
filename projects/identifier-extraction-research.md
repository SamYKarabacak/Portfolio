# Exact identifier extraction and source selection

Independent research into whether a language model selects the correct record and preserves its identifier exactly.

**Status:** Manuscript in preparation. A current-model extension is prepared but has not generated new model responses.

## Research question

When several plausible fields appear in a synthetic record, can a model follow the source-selection rule and return the exact required identifier? Evaluation distinguishes correct extraction from choosing the wrong source, changing the value, or returning invalid JSON.

## Reproducibility work

- Frozen synthetic development, main, and repeat datasets.
- Paired cases with controlled changes to the available record context.
- Archived local-model runs and deterministic parser baselines.
- Explicit prompts, response records, exact-match scoring, and analysis code.
- Content hashes and offline checks for the preserved data and prepared requests.

The extension preparation contains **192 main inputs from 96 paired cases**, plus separate development and repeat inputs. Its private source checkpoint passed the offline package verifier again on 3 November 2026, including replay of archived runs and request-integrity checks.

## Current limits

Historical runs describe their recorded compact-model configurations. They are not evidence about current public flagship models. The new provider-model roster and execution settings still require a freeze, actual access checks, and genuine response collection.

Independent semantic review, author approval, and manuscript submission remain outstanding. No peer-reviewed publication or current-model result is claimed.

The working dataset, scoring code, archived responses, and extension protocol are maintained privately while the study is in preparation.

[Back to portfolio](../README.md)
