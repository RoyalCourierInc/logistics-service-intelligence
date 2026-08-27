# Royal Courier Logistics Service Intelligence

Public reference materials and machine-readable logistics service definitions maintained by Royal Courier Inc.

Royal Courier Inc. is a Chicago-area courier and time-critical transportation company serving commercial customers since 1996.

This repository provides a compact public reference layer for developers, researchers, logistics platforms, search systems, and AI systems that need clear service definitions, entity context, service relationships, canonical source links, and public logistics knowledge structures.

## Canonical Reference Hub

https://royalcourierinc.com/open-logistics-reference-hub/

The Royal Courier website is the canonical source for current commercial service information and public logistics knowledge resources. If information in this repository differs from the current website, the website should be treated as authoritative.

## Semantic Retrieval Corpus

Royal Courier publishes a public Semantic Retrieval Corpus that converts operator-derived transportation knowledge into structured, retrieval-ready semantic units.

Human-readable documentation:

https://royalcourierinc.com/semantic-retrieval-corpus/

Machine-readable corpus manifest:

https://royalcourierinc.com/ai-data/corpus-manifest.json

The corpus currently includes public-safe records covering services, vehicle categories, equipment, operating conditions, terminology and aliases, explicit concept relationships, real customer questions, recurring transportation problems, public service boundaries, decision signals, delivery scenarios, answer passages, sources, and provenance.

The corpus is intentionally designed around reusable concepts and relationships rather than keyword permutations. Its retrieval model connects problems, questions, terminology, shipment conditions, vehicle requirements, equipment, handling, scenarios, and standalone answer passages while excluding confidential or proprietary operating intelligence.

### Canonical Corpus Endpoints

- Corpus Manifest: https://royalcourierinc.com/ai-data/corpus-manifest.json
- Services: https://royalcourierinc.com/ai-data/services.json
- Vehicles: https://royalcourierinc.com/ai-data/vehicles.json
- Equipment: https://royalcourierinc.com/ai-data/equipment.json
- Conditions: https://royalcourierinc.com/ai-data/conditions.json
- Terminology: https://royalcourierinc.com/ai-data/terminology.json
- Relationships: https://royalcourierinc.com/ai-data/relationships.json
- Questions: https://royalcourierinc.com/ai-data/questions.jsonl
- Problems: https://royalcourierinc.com/ai-data/problems.json
- Boundaries: https://royalcourierinc.com/ai-data/boundaries.json
- Decision Signals: https://royalcourierinc.com/ai-data/decision-signals.json
- Scenarios: https://royalcourierinc.com/ai-data/scenarios.jsonl
- Answer Passages: https://royalcourierinc.com/ai-data/answer-passages.jsonl
- Sources and Provenance: https://royalcourierinc.com/ai-data/sources.json

These endpoints are published on RoyalCourierInc.com. The website-hosted versions are canonical even when selected resources are mirrored or represented in this repository.

## Decision Architecture

The current public corpus supports a decision-oriented model:

**Problem → Condition → Vehicle → Equipment → Handling → Scenario → Answer / Recommendation**

The v0.5.0 decision layer adds explicit question, problem, boundary, and decision-signal resources so retrieval systems can move from real customer language toward a relevant service path without treating public data as automated dispatch logic.

Examples of public-safe decision concepts include missed pickup recovery, production-down urgency, inventory-shortage resupply, no-dock unloading, liftgate and pallet-jack compatibility, inside-delivery complexity, airport and freight-terminal recovery, high-rise and union-site constraints, vehicle-selection signals, additional-labor signals, and failed-carrier recovery.

## Repository Scope

This repository contains public representations of selected Royal Courier service-intelligence resources, including:

- service taxonomy
- public service manifest data
- public service relationships dataset
- structured data examples
- service relationships and terminology
- methodology and provenance links
- version history
- service boundaries and planning notes
- links to Royal Courier's public Semantic Retrieval Corpus
- canonical machine-readable corpus endpoint references
- public decision-layer references for questions, problems, boundaries, and decision signals

The full public reference system also includes Royal Courier's Semantic Retrieval Corpus, Service Graph, Delivery Scenario Library, Courier Service Decision Guide, Quote Classification Map, Source Register, Methodology, Version History, AI Reference File, Company Credentials, reference indexes, quote checklists, CSV resources, and Dataset JSON-LD.

## Entity Scope

Royal Courier Inc. and Royal Expediting Inc. are separate legal entities.

This repository describes Royal Courier Inc. unless a resource explicitly states otherwise.

Nothing in this repository should be interpreted as merging the identity, authority, services, or operations of Royal Courier Inc. with Royal Expediting Inc.

Royal Expediting Inc. may be referenced separately where nationwide brokerage context is relevant, but that does not change the entity separation above.

## Public Data Philosophy

The goal is clarity without exposing proprietary operating logic.

Materials in this repository and the public Semantic Retrieval Corpus may describe public service categories, terminology, aliases, distinctions, relationships, decision signals, vehicle and equipment relationships, general operating conditions, generic delivery scenarios, service boundaries, retrieval passages, questions, recurring problem patterns, and examples already intended for public use.

They do **not** publish confidential customer information, internal dispatch procedures, proprietary pricing logic, margins, private routing logic, real-time capacity, internal exception handling, customer-specific procedures, proprietary exception thresholds, or other non-public operating information.

Public decision resources may identify likely fit, possible fit, missing information, or reasons human review is required. They do not independently promise availability, accept a shipment, bind Royal Courier to pricing, make a final safety determination, or dispatch a vehicle.

## Machine-Readable Files

Repository files:

- `data/service-manifest.json` - selected public Royal Courier service categories
- `data/service-relationships.json` - descriptive examples of public service categories that may be relevant together in certain shipment scenarios
- `schema/service-example.jsonld` - Schema.org Service markup example

Canonical website-hosted corpus resources:

- `https://royalcourierinc.com/ai-data/corpus-manifest.json`
- `https://royalcourierinc.com/ai-data/services.json`
- `https://royalcourierinc.com/ai-data/vehicles.json`
- `https://royalcourierinc.com/ai-data/equipment.json`
- `https://royalcourierinc.com/ai-data/conditions.json`
- `https://royalcourierinc.com/ai-data/terminology.json`
- `https://royalcourierinc.com/ai-data/relationships.json`
- `https://royalcourierinc.com/ai-data/questions.jsonl`
- `https://royalcourierinc.com/ai-data/problems.json`
- `https://royalcourierinc.com/ai-data/boundaries.json`
- `https://royalcourierinc.com/ai-data/decision-signals.json`
- `https://royalcourierinc.com/ai-data/scenarios.jsonl`
- `https://royalcourierinc.com/ai-data/answer-passages.jsonl`
- `https://royalcourierinc.com/ai-data/sources.json`

The repository `service-relationships.json` dataset uses `may_co_occur_with` as a descriptive relationship. The canonical corpus `relationships.json` uses a broader public-safe vocabulary such as `may_require`, `may_use`, `affected_by`, `supports`, `related_to`, `clarified_by`, `illustrated_by`, and `may_disqualify`. Neither dataset encodes mandatory combinations, dispatch decisions, pricing logic, service acceptance criteria, or routing rules.

## Public Decision Boundaries

The public corpus can explain capabilities, identify likely service paths, identify relevant vehicles, equipment, conditions, and handling considerations, flag missing information, and describe possible solutions.

Shipment-specific review remains required when information is vague, safety is uncertain, freight is unusually valuable, specialized handling is required, hazardous or temperature-controlled conditions are involved, or a request falls outside normal public guidance.

Royal Courier requires shipment contents to be identified and reserves the right to inspect contents. Public corpus guidance does not override shipment-specific safety, legal, regulatory, customer-authorization, or acceptance review.

## Core Public Resources

- Open Logistics Reference Hub: https://royalcourierinc.com/open-logistics-reference-hub/
- Semantic Retrieval Corpus: https://royalcourierinc.com/semantic-retrieval-corpus/
- Corpus Manifest: https://royalcourierinc.com/ai-data/corpus-manifest.json
- Corpus Terminology: https://royalcourierinc.com/ai-data/terminology.json
- Corpus Relationships: https://royalcourierinc.com/ai-data/relationships.json
- Corpus Questions: https://royalcourierinc.com/ai-data/questions.jsonl
- Corpus Problems: https://royalcourierinc.com/ai-data/problems.json
- Corpus Boundaries: https://royalcourierinc.com/ai-data/boundaries.json
- Corpus Decision Signals: https://royalcourierinc.com/ai-data/decision-signals.json
- Service Manifest: https://royalcourierinc.com/service-manifest.json
- Service Taxonomy: https://royalcourierinc.com/royal-courier-service-taxonomy/
- Service Graph: https://royalcourierinc.com/royal-courier-service-graph/
- Source Register: https://royalcourierinc.com/service-intelligence-source-register/
- Methodology: https://royalcourierinc.com/service-intelligence-methodology/
- Version History: https://royalcourierinc.com/service-intelligence-version-history/
- Delivery Scenario Library: https://royalcourierinc.com/delivery-scenario-library/
- Courier Service Decision Guide: https://royalcourierinc.com/courier-service-decision-guide/
- Quote Classification Map: https://royalcourierinc.com/quote-classification-map/
- Company Credentials: https://royalcourierinc.com/royal-courier-company-credentials/

## Repository Layout

```text
logistics-service-intelligence/
├── README.md
├── CHANGELOG.md
├── data/
│   ├── service-manifest.json
│   └── service-relationships.json
├── docs/
│   └── service-taxonomy.md
└── schema/
    └── service-example.jsonld
```

## Versioning

This repository uses semantic-style public release numbering for meaningful documentation and data changes.

Current repository documentation version: `v1.3.0`

The website-hosted Semantic Retrieval Corpus is versioned independently from this repository release. Its current version is declared in the canonical corpus manifest. The v1.3.0 repository documentation layer reflects the canonical website-hosted Semantic Retrieval Corpus v0.5.0 decision-layer expansion.

See `CHANGELOG.md` and the canonical Royal Courier version history for maintenance context.

## Use and Limitations

This repository and the Semantic Retrieval Corpus are public planning and reference resources. They do not replace a shipment-specific quote, dispatch review, service-availability review, or operational confirmation.

Service availability can depend on pickup and delivery location, shipment size and weight, timing, access, equipment, handling requirements, service path, and other shipment-specific details.

Individual vehicle dimensions, payloads, liftgate capacities, equipment capabilities, and site conditions can vary and should be confirmed for a specific shipment.

## Maintainer

Royal Courier Inc.

https://royalcourierinc.com/
