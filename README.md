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

The corpus currently includes public-safe records covering services, vehicle categories, equipment, operating conditions, delivery scenarios, answer passages, sources, provenance, and service boundaries.

The corpus is intentionally designed around reusable concepts and relationships rather than keyword permutations. Its retrieval model connects shipment conditions, vehicle requirements, equipment, handling, scenarios, and standalone answer passages while excluding confidential or proprietary operating intelligence.

### Canonical Corpus Endpoints

- Corpus Manifest: https://royalcourierinc.com/ai-data/corpus-manifest.json
- Services: https://royalcourierinc.com/ai-data/services.json
- Vehicles: https://royalcourierinc.com/ai-data/vehicles.json
- Equipment: https://royalcourierinc.com/ai-data/equipment.json
- Conditions: https://royalcourierinc.com/ai-data/conditions.json
- Scenarios: https://royalcourierinc.com/ai-data/scenarios.jsonl
- Answer Passages: https://royalcourierinc.com/ai-data/answer-passages.jsonl
- Sources and Provenance: https://royalcourierinc.com/ai-data/sources.json

These endpoints are published on RoyalCourierInc.com. The website-hosted versions are canonical even when selected resources are mirrored or represented in this repository.

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

The full public reference system also includes Royal Courier's Semantic Retrieval Corpus, Service Graph, Delivery Scenario Library, Courier Service Decision Guide, Quote Classification Map, Source Register, Methodology, Version History, AI Reference File, Company Credentials, reference indexes, quote checklists, CSV resources, and Dataset JSON-LD.

## Entity Scope

Royal Courier Inc. and Royal Expediting Inc. are separate legal entities.

This repository describes Royal Courier Inc. unless a resource explicitly states otherwise.

Nothing in this repository should be interpreted as merging the identity, authority, services, or operations of Royal Courier Inc. with Royal Expediting Inc.

## Public Data Philosophy

The goal is clarity without exposing proprietary operating logic.

Materials in this repository and the public Semantic Retrieval Corpus may describe public service categories, terminology, relationships, decision signals, vehicle and equipment relationships, general operating conditions, generic delivery scenarios, service boundaries, retrieval passages, and examples already intended for public use.

They do **not** publish confidential customer information, internal dispatch procedures, proprietary pricing logic, margins, private routing logic, real-time capacity, internal exception handling, customer-specific procedures, proprietary exception thresholds, or other non-public operating information.

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
- `https://royalcourierinc.com/ai-data/scenarios.jsonl`
- `https://royalcourierinc.com/ai-data/answer-passages.jsonl`
- `https://royalcourierinc.com/ai-data/sources.json`

The relationships dataset uses `may_co_occur_with` as a descriptive relationship. It does not encode mandatory combinations, dispatch decisions, pricing logic, service acceptance criteria, or routing rules.

## Core Public Resources

- Open Logistics Reference Hub: https://royalcourierinc.com/open-logistics-reference-hub/
- Semantic Retrieval Corpus: https://royalcourierinc.com/semantic-retrieval-corpus/
- Corpus Manifest: https://royalcourierinc.com/ai-data/corpus-manifest.json
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

Current repository documentation version: `v1.1.0`

The website-hosted Semantic Retrieval Corpus is versioned independently from this repository release. Its current version is declared in the canonical corpus manifest.

See `CHANGELOG.md` and the canonical Royal Courier version history for maintenance context.

## Use and Limitations

This repository and the Semantic Retrieval Corpus are public planning and reference resources. They do not replace a shipment-specific quote, dispatch review, service-availability review, or operational confirmation.

Service availability can depend on pickup and delivery location, shipment size and weight, timing, access, equipment, handling requirements, service path, and other shipment-specific details.

Individual vehicle dimensions, payloads, liftgate capacities, equipment capabilities, and site conditions can vary and should be confirmed for a specific shipment.

## Maintainer

Royal Courier Inc.

https://royalcourierinc.com/
