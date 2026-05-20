# An Evolutionary Transportation Planning Model: Structure And Application

## Bibliographic Information

- Row ID: `paper-1995-02`
- Authors: David M. Levinson
- Year: 1995
- Venue: Transportation Research Record 1493:64-73 (1995)
- Citation: Levinson, David M. (1995). "An Evolutionary Transportation Planning Model: Structure and Application." Transportation Research Record 1493:64-73.

## Package Status

This package is ready for public upload review. A paper-first audit confirms that the paper describes an evolutionary Travel/2 / EMME/2 model application for Montgomery County, using land-use and demographic forecasts, coded network changes, trip generation and distribution components, route assignment, and annual model runs.

No raw human-subject microdata are staged here. The package should be described as a historical model/source archive rather than a modern turnkey reproduction. The historical workflow depends on HP-UX-era files and EMME/2/Travel/2 tooling; binary legacy archives are retained as archival originals.

## Contents

- `paper/`: local reference copy of the published paper.
- `model_archive/t2dyn_evolutionary_model/`: staged T2DYN evolutionary Travel/2 model tree from `/Users/dlev2617/Documents/~~Archives/MNCPPC/t2dyn`.
- `code/legacy/model_archive/SOURCE_TREE_MANIFEST.csv`: SHA-256 manifest and role labels for the staged model tree.
- `legacy_z_decoded_20260516/`: decode sidecars for legacy `.Z` files, with status manifests.
- `documentation/LEGACY_Z_DECODE_NOTES.md`: summary of complete and partial decode status.

## Boundary Correction

SLATE macro/context folders are intentionally not included in this package. They belong with `paper-1997-03`, A Windowed Transportation Planning Model. This package is the distinct T2DYN evolutionary model archive associated with `paper-1995-02`.

## Release Boundary

Public upload should preserve the model archive, original compressed files, and decode manifests, but should not claim that the archive is turnkey on modern systems. Public release should include provenance and dependency notes for the legacy agency model inputs, EMME/2/Travel/2 workflow, and decoded `.Z` sidecars.

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-20 14:46:37 AEST

- Pipeline: `READY-TO-UPLOAD/PUBLIC`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->
