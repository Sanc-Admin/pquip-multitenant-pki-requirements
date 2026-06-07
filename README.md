# draft-vicente-pquip-multitenant-pki-requirements

[![IETF Datatracker](https://img.shields.io/badge/IETF-Datatracker-blue)](https://datatracker.ietf.org/doc/draft-vicente-pquip-multitenant-pki-requirements/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)
[![Patent Pending](https://img.shields.io/badge/Patent-Pending-red.svg)](#ipr--patent-notice)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0006--6395--5308-A6CE39.svg)](https://orcid.org/0009-0006-6395-5308)

**Requirements and Gaps for Post-Quantum Certificate Rotation in Multi-Tenant Public Key Infrastructure Environments**

IETF Internet-Draft. Independent Submission. Working Group: Post-Quantum Use In Protocols (pquip).

## Status

| Revision | State | Date | Link |
|---|---|---|---|
| `-00` | Filed at IETF Datatracker | 2026-06-05 | [Datatracker](https://datatracker.ietf.org/doc/draft-vicente-pquip-multitenant-pki-requirements-00/) |
| `-01` | In preparation (this repo) | TBD | kramdown-rfc source: [`draft-vicente-pquip-multitenant-pki-requirements-01.md`](draft-vicente-pquip-multitenant-pki-requirements-01.md) |

## Abstract

Organizations operating Public Key Infrastructure (PKI) across multiple isolated tenant environments face a critical gap: existing PKI management protocols and standards do not address the coordination requirements for post-quantum cryptographic (PQC) algorithm migration in shared, multi-tenant certificate authority deployments. This document identifies the functional requirements and open protocol gaps that must be addressed to enable safe, consistent, and auditable PQC certificate rotation across multi-tenant PKI environments. No new protocol mechanisms are specified; this is an informational requirements document intended to motivate future standards work.

## Author

**Brian Vicente**
Sanctum SecOps LLC
Pine City, NY, United States of America
Email: `bvicente@sanctumsecops.com`
ORCID: [0009-0006-6395-5308](https://orcid.org/0009-0006-6395-5308)

## IPR / Patent Notice

The author may hold or apply for patents covering subject matter related to this document. Disclosure of any such patents will be made in accordance with the procedures defined in [BCP 79](https://www.rfc-editor.org/info/bcp79).

**Publication of this Internet-Draft does not constitute any patent license, express or implied, from the author or Sanctum SecOps LLC. License terms, if any, are not yet known.**

Patent disclosures filed with the IETF will appear at: <https://datatracker.ietf.org/ipr/>

No portion of this document is offered as a trade secret. All technical disclosures herein are intended as public prior art as of the publication date of the `-00` revision (2026-06-05).

## License

The text of this document is released under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE).

**This license grants copyright permissions only. It does NOT grant any patent license.**

## Citation

See [`CITATION.cff`](CITATION.cff). Once a release is tagged and Zenodo sync is enabled, a DOI will be minted; that DOI will be added here.

## Repository Contents

| File | Purpose |
|---|---|
| `draft-vicente-pquip-multitenant-pki-requirements-00.txt` | Canonical -00 text as filed at IETF (verbatim) |
| `draft-vicente-pquip-multitenant-pki-requirements-01.md` | kramdown-rfc source for -01 revision (in preparation) |
| `CITATION.cff` | Machine-readable citation metadata |
| `LICENSE` | CC BY 4.0 + explicit "no patent grant" notice |

## Build (-01)

```bash
gem install kramdown-rfc2629
kdrfc -3 draft-vicente-pquip-multitenant-pki-requirements-01.md
```

## Related Drafts

- [`draft-vicente-pquip-pqc-readiness-gaps`](https://datatracker.ietf.org/doc/draft-vicente-pquip-pqc-readiness-gaps/) — companion draft on PQC readiness observability gaps.
- [`draft-vicente-oauth-apm`](https://datatracker.ietf.org/doc/draft-vicente-oauth-apm/) — OAuth 2.0 Authorization Posture Mechanism.
- [`draft-vicente-lamps-pqchc`](https://datatracker.ietf.org/doc/draft-vicente-lamps-pqchc/) — PQC Hybrid Commitment X.509 extension.
