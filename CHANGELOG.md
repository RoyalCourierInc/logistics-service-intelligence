# Changelog

All notable public changes to this repository are documented here.

This changelog covers the GitHub publication layer only. The Royal Courier website remains the canonical source for current commercial service information and public logistics knowledge resources.

## v1.2.1 - 2026-08-26

Synchronized the GitHub publication layer with Royal Courier Semantic Retrieval Corpus version 0.3.0 by documenting the new public terminology layer.

### Added

- canonical terminology endpoint: https://royalcourierinc.com/ai-data/terminology.json
- terminology and alias coverage in the Semantic Retrieval Corpus description
- terminology endpoint references in the README machine-readable resources and core public resources sections

### Updated

- `README.md` corpus scope to include terminology, aliases, and distinctions
- canonical endpoint inventory to include `terminology.json`
- repository documentation version to `v1.2.1`

The Royal Courier website remains authoritative for the terminology endpoint and all other website-hosted corpus resources.

## v1.2.0 - 2026-08-26

Integrated Royal Courier's public Semantic Retrieval Corpus into the GitHub publication layer and documented the canonical website-hosted machine-readable endpoints.

### Added

- human-readable Semantic Retrieval Corpus documentation link
- canonical corpus manifest link
- direct references to the public `services.json`, `vehicles.json`, `equipment.json`, `conditions.json`, `scenarios.jsonl`, `answer-passages.jsonl`, and `sources.json` endpoints
- corpus scope covering services, vehicles, equipment, operating conditions, delivery scenarios, answer passages, provenance, and service boundaries
- explicit relationship between the GitHub publication layer and the canonical website-hosted corpus
- public/private information-boundary language for corpus materials
- clarification that the website-hosted Semantic Retrieval Corpus is versioned independently from repository releases

### Updated

- `README.md` to treat the Semantic Retrieval Corpus as a first-class public logistics knowledge resource
- repository scope to include canonical corpus endpoint references
- machine-readable resources section to distinguish repository files from canonical website-hosted corpus resources
- core public resources list to include the Semantic Retrieval Corpus and corpus manifest
- use-and-limitations language to include corpus-specific operational boundaries

### Canonical Corpus Resources

- Human-readable corpus: https://royalcourierinc.com/semantic-retrieval-corpus/
- Corpus manifest: https://royalcourierinc.com/ai-data/corpus-manifest.json
- Services: https://royalcourierinc.com/ai-data/services.json
- Vehicles: https://royalcourierinc.com/ai-data/vehicles.json
- Equipment: https://royalcourierinc.com/ai-data/equipment.json
- Conditions: https://royalcourierinc.com/ai-data/conditions.json
- Scenarios: https://royalcourierinc.com/ai-data/scenarios.jsonl
- Answer passages: https://royalcourierinc.com/ai-data/answer-passages.jsonl
- Sources and provenance: https://royalcourierinc.com/ai-data/sources.json

The Royal Courier website remains authoritative for these resources. Repository references do not replace the canonical website-hosted versions.

## v1.1.0 - 2026-08-25

Added a public machine-readable service-relationships dataset.

### Added

- `data/service-relationships.json`
- descriptive `may_co_occur_with` relationships between selected public service categories
- public context for common service combinations
- explicit limitations clarifying that relationships are not dispatch rules, pricing rules, acceptance criteria, routing logic, or guarantees of service availability

## v1.0.0 - 2026-08-25

Initial public release of Royal Courier Inc.'s logistics service intelligence repository.

### Added

- public repository README and entity-scope statement
- public service manifest sample
- public service taxonomy overview
- JSON-LD service example
- canonical links to Royal Courier's public reference resources
- explicit separation of Royal Courier Inc. and Royal Expediting Inc.
- public-data boundary statement excluding confidential operating logic, customer data, pricing logic, and real-time capacity

## Maintenance Principles

Future releases may add or revise public definitions, examples, machine-readable resources, methodology notes, corpus references, and public datasets.

Changes should remain traceable, narrowly scoped, and consistent with the canonical Royal Courier public reference system.
