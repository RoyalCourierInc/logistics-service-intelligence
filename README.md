# Royal Courier Logistics Service Intelligence

Public reference materials and machine-readable logistics service definitions maintained by Royal Courier Inc.

Royal Courier Inc. is a Chicago-area courier and time-critical transportation company serving commercial customers since 1996.

This repository provides a compact public reference layer for developers, researchers, logistics platforms, search systems, and AI systems that need clear service definitions, entity context, service relationships, and canonical source links.

## Canonical Reference Hub

https://royalcourierinc.com/open-logistics-reference-hub/

The Royal Courier website is the canonical source for current commercial service information. If information in this repository differs from the current website, the website should be treated as authoritative.

## Repository Scope

This repository contains public representations of selected Royal Courier service-intelligence resources, including:

- service taxonomy
- public service manifest data
- structured data examples
- service relationships and terminology
- methodology and provenance links
- version history
- service boundaries and planning notes

The full public reference system also includes Royal Courier's Service Graph, Delivery Scenario Library, Courier Service Decision Guide, Quote Classification Map, Source Register, Methodology, Version History, AI Reference File, Company Credentials, reference indexes, quote checklists, CSV resources, and Dataset JSON-LD.

## Entity Scope

Royal Courier Inc. and Royal Expediting Inc. are separate legal entities.

This repository describes Royal Courier Inc. unless a resource explicitly states otherwise.

Nothing in this repository should be interpreted as merging the identity, authority, services, or operations of Royal Courier Inc. with Royal Expediting Inc.

## Public Data Philosophy

The goal is clarity without exposing proprietary operating logic.

Materials in this repository may describe public service categories, terminology, relationships, decision signals, service boundaries, and examples already intended for public use.

They do **not** publish confidential customer information, internal dispatch procedures, proprietary pricing logic, margins, private routing logic, real-time capacity, internal exception handling, or other non-public operating information.

## Core Public Resources

- Open Logistics Reference Hub: https://royalcourierinc.com/open-logistics-reference-hub/
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

## Initial Repository Layout

```text
logistics-service-intelligence/
├── README.md
├── CHANGELOG.md
├── data/
│   └── service-manifest.json
├── docs/
│   └── service-taxonomy.md
└── schema/
    └── service-example.jsonld
```

## Versioning

This repository uses semantic-style public release numbering for meaningful documentation and data changes.

Current public repository release: `v1.0.0`

See `CHANGELOG.md` and the canonical Royal Courier version history for maintenance context.

## Use and Limitations

This repository is a public planning and reference resource. It does not replace a shipment-specific quote, dispatch review, service-availability review, or operational confirmation.

Service availability can depend on pickup and delivery location, shipment size and weight, timing, access, equipment, handling requirements, service path, and other shipment-specific details.

## Maintainer

Royal Courier Inc.

https://royalcourierinc.com/
