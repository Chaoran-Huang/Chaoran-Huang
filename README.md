# Chaoran Huang

Software engineer building **production AI and distributed systems** for correctness-sensitive workflows.

[Engineering notes](https://learn.chaoran-huang.com) · [LinkedIn](https://www.linkedin.com/in/chaoran-huang/) · [Email](mailto:chaoranhuang97@gmail.com)

I work on zero-to-one systems where correctness has to survive contact with production: measurable AI quality, bounded agent behavior, reliable asynchronous workflows, and auditable data boundaries.

## Current focus

- **Production AI evaluation** — expert-adjudicated golden tasks, repeated trials, provenance, confidence intervals, and product-readable results.
- **Agent orchestration** — explicit termination, citation and evidence gates, human-review routing, and cost/latency control.
- **Distributed systems** — event-driven workers, transactional outbox patterns, concurrency control, PostgreSQL row-level security, and external-system integration.
- **Primary tools** — TypeScript, Effect, Python, SQL, PostgreSQL, AWS, Kafka, BullMQ, and React.

## Open source

- [Effect-TS/effect PR #6395](https://github.com/Effect-TS/effect/pull/6395) — fixed multipart limit violations being silently swallowed; added a regression test and the change was merged upstream.
- Root-caused Amazon Bedrock provider issues in Effect: [#6185](https://github.com/Effect-TS/effect/issues/6185) and [#6186](https://github.com/Effect-TS/effect/issues/6186), with a related contribution in [PR #6278](https://github.com/Effect-TS/effect/pull/6278).

## Selected public work

- [Activation Checkpointing & Tensor Swapping](https://github.com/Chaoran-Huang/cs265-mlsys-2024) — automatic `torch.fx` graph transformations that reduced peak activation memory by roughly 70–85% in the tested models while checking gradient equivalence.
- [Chest X-ray Abnormality Detection](https://github.com/Chaoran-Huang/athlete-xray-abnormality-detection) — compared YOLOv5 and Faster R-CNN for medical-image localization, from DICOM preprocessing through evaluation.
- [Vehicle Listing NER](https://github.com/Chaoran-Huang/vehicle-listing-ner) — spaCy NER plus canonical-entity matching for normalizing noisy vehicle listings.

## Writing

I publish long-form explanations at [learn.chaoran-huang.com](https://learn.chaoran-huang.com):

- [From One-Hot to BERT](https://learn.chaoran-huang.com/docs/nlp)
- [From Representation to Behavior](https://learn.chaoran-huang.com/docs/llm)
- [Bits, Math, Hashes, Streams](https://learn.chaoran-huang.com/docs/systems-refresher)

## Background

M.S. Computer Science, [Brown University](https://www.brown.edu) · B.S. Computer Science, [UC Irvine](https://uci.edu) · Boston, Massachusetts
