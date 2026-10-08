# Awesome CBOM (Cryptographic Bill of Materials) 🔐📋

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)
![Maintained](https://img.shields.io/badge/Maintained%3F-yes-green.svg)

The definitive curated index of Cryptographic Bill of Materials (CBOM) tools, cryptographic discovery scanners, post-quantum cryptography (PQC) migration resources, and crypto-agility frameworks.

## What Is a CBOM?

A **Cryptographic Bill of Materials (CBOM)** is a structured, machine-readable inventory of all the cryptographic assets used across a software environment. It is the cryptographic counterpart to the Software Bill of Materials (SBOM): an **extension of the CycloneDX SBOM standard**.

A CBOM is the foundational artifact for **post-quantum cryptography (PQC) migration**, **crypto-agility**, and **cryptographic compliance**.

## Table of Contents

- [What Is a CBOM?](#what-is-a-cbom)
- [CBOM Standards and Specifications](#cbom-standards-and-specifications)
- [Open Source CBOM and Cryptographic Discovery Tools](#open-source-cbom-and-cryptographic-discovery-tools)
- [Post-Quantum Cryptography (PQC) Migration Tools](#post-quantum-cryptography-pqc-migration-tools)
- [Crypto-Agility Frameworks and Resources](#crypto-agility-frameworks-and-resources)
- [Regulations, Mandates, and Compliance Guidance](#regulations-mandates-and-compliance-guidance)
- [Research and Publications](#research-and-publications)
- [Commercial CBOM and PQC Migration Platforms](#commercial-cbom-and-pqc-migration-platforms)
- [Community and Working Groups](#community-and-working-groups)
- [Support the Project](#support-the-project)
- [Contributing](#contributing)

## CBOM Standards and Specifications

The data formats and standards that define how a CBOM is structured and exchanged.

- [CycloneDX CBOM](https://cyclonedx.org/capabilities/cbom/) - The reference specification for representing cryptographic assets; CBOM is upstreamed into the CycloneDX standard (1.6+) and ratified as ECMA-424.
- [OWASP Authoritative Guide to CBOM (PDF)](https://cyclonedx.org/guides/) - The official OWASP/CycloneDX guide to authoring cryptographic bills of materials.
- [NIST Post-Quantum Cryptography Standards](https://csrc.nist.gov/projects/post-quantum-cryptography) - FIPS 203 (ML-KEM), FIPS 204 (ML-DSA), and FIPS 205 (SLH-DSA) — the standardized post-quantum algorithms a CBOM tracks migration toward.
- [NIST IR 8547: Transition to Post-Quantum Cryptography Standards](https://csrc.nist.gov/pubs/ir/8547/ipd) - NIST's roadmap for transitioning from quantum-vulnerable to post-quantum algorithms.

## Open Source CBOM and Cryptographic Discovery Tools

Open-source tools for discovering, generating, and visualizing cryptographic bills of materials.

- [cbom-tools](https://github.com/LennonHaha/fibemate-tools/tree/main/cbom-tools) - CBOM scanner and diff CLI for Node.js projects. Generates CycloneDX 1.6 CBOM; detects algorithm changes between releases.

## Post-Quantum Cryptography (PQC) Migration Tools

Tooling for discovering quantum-vulnerable cryptography and testing the migration to post-quantum algorithms.


## Crypto-Agility Frameworks and Resources

Crypto-agility is the architectural practice of building systems that can swap cryptographic algorithms via configuration rather than re-architecture.


## Regulations, Mandates, and Compliance Guidance

The regulatory forcing functions driving CBOM and PQC adoption.

## Research and Publications

## Commercial CBOM and PQC Migration Platforms

Vendor platforms offering cryptographic discovery, CBOM generation, and managed PQC migration.

*(Vendor entries are listed for completeness - inclusion is not an endorsement. Submit additions via PR.)*

## Community and Working Groups

## Support the Project

### ⭐ Featured in Awesome CBOM

If your tool or research is featured in this list, show your support and link back — it strengthens the cryptographic inventory ecosystem.

[![Featured in Awesome CBOM](https://img.shields.io/badge/Featured_in-Awesome_CBOM-blue?style=flat-square&logo=github)](https://github.com/riccardobiosas/awesome-cbom)

Copy the markdown below to embed the badge (replace `YOURUSERNAME` with your repo path):

```markdown
[![Featured in Awesome CBOM](https://img.shields.io/badge/Featured_in-Awesome_CBOM-blue?style=flat-square&logo=github)](https://github.com/YOURUSERNAME/awesome-cbom)
```

If this list helped you, please ⭐ star the repo & share it with your security team.
