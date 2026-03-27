# Verifiable Credentials (VC)

This directory contains Verifiable Credentials (W3C VC) associated with the identity:

did:web:identity.nvo987.us

These credentials provide machine-verifiable claims about the identity, research activity, affiliations, and publications.

---

## Files

### vc-identity.json
Core identity credential.

- Confirms the existence of the DID
- Links the identity to the subject (person)

---

### vc-researcher.json
Researcher credential.

- Declares role as independent researcher
- Specifies research domains:
  - Decentralized identity
  - Semantic web
  - Artificial intelligence

---

### vc-affiliation.json
Affiliation credential.

- Connects the identity to the organization:
  NVO987 – Culture Visuelle Moderne et Contemporaine

---

### vc-publication.json
Publication credential.

- Links to the publications dataset
- Enables verifiable academic output tracking

---

### presentation.json
Verifiable Presentation.

- Aggregates multiple credentials
- Used for sharing and verification
- Entry point for external verification systems

---

## Purpose

These credentials enable:

- Decentralized identity verification
- Machine-readable trust
- Interoperability with Web3 and AI systems
- Structured academic and research validation

---

## Standards

- W3C Verifiable Credentials Data Model
- JSON-LD
- DID (Decentralized Identifiers)

---

## Verification

Credentials can be verified by:

- Checking issuer: did:web:identity.nvo987.us
- Validating structure against W3C VC
- Verifying signatures (when applied)

---

## Future Extensions

- Cryptographic signatures (Ed25519)
- Linked Data Proofs
- On-chain anchoring
- Integration with AI agents

---
