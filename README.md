# Crew Tools reference packages

Public FAA-derived reference packages and the Crew Tools Data Center download catalog, maintained by Aukridge Inc.

This repository does not contain app source code, company manuals, user documents, or aircraft performance datasets.

## Downloads

- `catalog.json`: edition-specific download URLs, byte counts, validity windows, and source attribution.
- Release `nav-2609`: FAA-derived CDRs, preferred routes, airports, fixes, navaids and airways in an integrity-checked SQLite package.
- Regional IFR and VFR chart files download directly from FAA. This repository lists the original files rather than mirroring charts.

## Source and use boundaries

FAA sources: [CDR](https://www.fly.faa.gov/rmt/data_file/codedswap_db.csv), [preferred routes](https://www.fly.faa.gov/rmt/data_file/prefroutes_db.csv), [NASR](https://www.faa.gov/air_traffic/flight_info/aeronav/aero_data/NASR_Subscription/), [IFR charts](https://www.faa.gov/air_traffic/flight_info/aeronav/digital_products/ifr/), and [VFR charts](https://www.faa.gov/air_traffic/flight_info/aeronav/digital_products/vfr/).

The navigation package is a derived planning/reference dataset, not an FAA-certified navigation database. A published route is not evidence of activation, ATC acceptance, clearance or dispatch approval. Missing or ambiguous geometry remains unsupported; do not infer continuity across gaps. Use current official publications and notices.

Cycle 2609 navigation is effective 2026-09-03 09:01 UTC and expires 2026-10-01 09:01 UTC. Chart editions carry their own dates. A file checksum detects byte changes, not operational suitability. Chart PDFs are original reference documents; no georeferenced map-overlay claim is made.

Updates require fresh FAA source verification and package validation before publication. Old downloaded revisions can be retained for reference but must not be presented as current.
