<!-- Rights Reserved, Unlicensed -->

# Future Systems Lab

**SOVEREIGN by Design**

Decentralized infrastructure for sovereign data governance, with behavioral health as the proving ground.

**[evidence.futuresystemslab.io](https://evidence.futuresystemslab.io)** — public evidence portfolio documenting deployed contracts, system architecture, and independent verification.

---

## What FSL Is

A multi-platform Web3 ecosystem built on wallet-signed consent (Phase 1 deployed; Phases 2–4 scaffolded and specified):

- **EncryptHealth** — sovereign guide portal with EIP-191 authentication
- **HypnoNeuro** — wellness-engagement platform organized around neurotransmitter systems
- **SovereignLedger** — session attestation on the Ethereum Sepolia testnet
- **AlchemistForge** — permissionless behavioral health engagement recording
- **NeuroBalance** — biosensor integration layer (scaffolded)

Four platform surfaces on a unified backend (EncryptHealth); HypnoNeuro, SovereignLedger, and AlchemistForge are delivered through encrypthealth.io. One scaffolded (NeuroBalance). Ten current smart contracts on the Ethereum Sepolia testnet (13 deployed: 10 current, 2 superseded — SovereignLedger v2 and BenevolenceFund v2 — and SovereignLedger v4, awaiting its production switch).

### Why most repositories here are private
FSL's platform repositories contain deployment configuration and work covered by two pending U.S. provisional patent applications (64/063,037 and 64/106,748). The evidence portfolio is the public window: every deployed contract address is listed and independently verifiable on Sepolia Blockscout.

## Architecture

EIP-191 wallet-signed consent unifies authentication, informed consent, session authorization, and data attribution into a single cryptographic signature event. No protected health information is written on chain, and the platform runs on simulated data. The zero-PHI boundary is an architectural design choice, not a regulatory determination. Hybrid on-chain/off-chain data model. Client-side AES-256-GCM encryption is deployed on the AlchemistForge path; bilateral session-key derivation (Phase 5) is the focus of ongoing research.

## Research

*EIP-191 Consent Architecture for Sovereign Behavioral Health Data Governance: A Hybrid On-Chain/Off-Chain Implementation* — manuscript prepared for Blockchain in Healthcare Today (BHTY).

Proposed Doctor of Engineering applied project at Arizona State University.

## Intellectual Property

- **U.S. Provisional Patent No. 64/063,037** — filed May 2026 — single-signer EIP-191 wallet-signed consent architecture, zero-PHI constraint, Sovereign Guide attestation model. Assigned to Future Systems Lab LLC.
- **U.S. Provisional Patent No. 64/106,748** — filed July 2026 — bilateral dual-signature consent protocol (EIP-191 + EIP-712), HKDF session-key derivation. Assigned to Future Systems Lab LLC.
- **USPTO Trademark Serial No. 99533250** — "Future Systems Lab," Class 42, filed December 2025
- **USPTO Trademark Serial No. 99821948** — "Future Systems Lab," Class 35, filed May 2026, not being pursued

## Open-Source Contributions

| Repository | PR | Description | Status |
|---|---|---|---|
| [bcgov/aries-vcr](https://github.com/bcgov/aries-vcr/pull/811) | #811 | Healthcare verifiable-credential schema examples + validation | Merged |
| [openmrs/openmrs-module-fhir2](https://github.com/openmrs/openmrs-module-fhir2/pull/577) | #577 | FHIR CodeableConcept normalization utility + tests (Java) | Open |
| [openmrs/openmrs-contrib-fhir2-ig](https://github.com/openmrs/openmrs-contrib-fhir2-ig/pull/63) | #63 | macOS build documentation for FHIR2 IG | Open |

## Founder

**Margarita Montañez Davenport**, D.N.Psy., BCHN, CBHP

Weekly contributing author at [America Out Loud](https://www.americaoutloud.news/author/meg-montanez-davenport/)

future.systems.lab@proton.me · [futuresystemslab.io](https://futuresystemslab.io) · [LinkedIn](https://www.linkedin.com/in/margarita-monta%C3%B1ez-davenport-680652226/) · ORCID: [0009-0001-4536-3070](https://orcid.org/0009-0001-4536-3070)

[View Full CV](https://evidence.futuresystemslab.io/cv)
