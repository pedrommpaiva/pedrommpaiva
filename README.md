# Pedro Paiva

I work on difficult text collections and public data: judicial transcription, Portuguese public-contracting records, historical corpora, open geospatial and event data.

## How these repositories are made

**The code here is built by AI systems under my direction. I do not write it.**

What I bring is the domain — I have transcribed judicial proceedings for over a decade — the formulation of the problem, and the verification of the output against the sources it claims to describe. That last part is most of the work. An AI will produce a pipeline that runs; whether it produced the right answer is a separate question, and answering it requires knowing the material.

I state this plainly because a GitHub profile is normally read as a claim to software engineering, and that would be a false claim. What these repositories document is a different competence: directing automated systems across domains I know well, and checking their output rigorously enough to publish the failures.

## Repositories

### [transcricao-automacao](https://github.com/pedrommpaiva/transcricao-automacao)
Transcription and revision tooling for judicial proceedings in European Portuguese. Automatic transcription with faster-whisper, LanguageTool-assisted revision, track-changes analysis to find recurring error types. Comes directly from the work I do.

### [base-contratacao-publica](https://github.com/pedrommpaiva/base-contratacao-publica)
The Portuguese public-contracting dataset — 246,809 rows for 2025 — turned into an auditable relational model with entity resolution. 9,625,551 cells verified against the source with zero differences. The published audit verdict is **FAILED**, naming three unresolved semantic errors.

### [gdelt-briefings](https://github.com/pedrommpaiva/gdelt-briefings)
A seven-step pipeline reducing a full day of GDELT 2.0 to a ranked set of news clusters, with the strategic-relevance weighting exposed in code rather than hidden in a model.

### [ruido-aeronautico-lisboa](https://github.com/pedrommpaiva/ruido-aeronautico-lisboa)
Aircraft movement extraction for Lisbon airport via OpenSky and Eurocontrol OPDI, underpinning work on urban noise exposure. The README states plainly that the counts are a lower bound of unquantified margin.

### [corpus-salazar-rag](https://github.com/pedrommpaiva/corpus-salazar-rag)
Semantic retrieval over the speeches and writings of António de Oliveira Salazar, built to retrieve and cite rather than to generate. The prohibition on impersonation is written into the system prompt itself.

## What I try to do consistently

- keep raw sources intact and separable from every transformation applied to them;
- make intermediate results inspectable instead of collapsing a pipeline into one opaque step;
- put subjective choices — thresholds, weights, classifications — in code where they can be argued with;
- publish limitations and failed audits alongside results, because a report that only says it went well is not a verification;
- keep confidential material out of public repositories entirely.

---

Based in Lisbon. Background in History (NOVA FCSH). Working in Portuguese and English.
