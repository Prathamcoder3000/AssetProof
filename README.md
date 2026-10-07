# AssetProof

### Real-World Asset Verification & Tokenization Platform

> **Verified Assets. Trusted Ownership.**

AssetProof is a **Hyperledger Fabric-based platform** that brings real-world assets into a trusted digital lifecycle — from **registration and verification to valuation, tokenization, ownership transfer, provenance, and retirement**.

It is designed to support multiple asset classes such as **land, commodities, and invoices** through a common, permissioned asset framework.

---

## 🎯 Problem Statement

### PS-01 — Real-World Asset Tokenization Platform

Real-world assets often involve fragmented records, manual verification, unclear ownership transitions, and limited traceability across their lifecycle.

AssetProof addresses this by creating a **permissioned digital representation of an asset** and governing its lifecycle through Hyperledger Fabric smart contracts.

The platform enables assets to be:

- Registered with a unique identity
- Verified using supporting evidence
- Given a cryptographic fingerprint
- Valued before tokenization
- Digitally represented on a permissioned blockchain
- Transferred through controlled ownership workflows
- Tracked through complete provenance history
- Retired without losing historical records

---

## 🚀 Key Features

### 1. Multi-Asset Support
A common asset framework supporting:

- 🏞️ Land
- ⛏️ Commodities
- 📄 Invoices

### 2. Asset Registration & Verification
Creates unique asset records and allows authorized participants to verify asset details and supporting evidence before the asset progresses through the lifecycle.

### 3. Asset Fingerprint
Generates a **SHA-256 cryptographic fingerprint** from verified asset information and supporting evidence, creating a tamper-evident identity for the digital asset record.

### 4. Asset Valuation & Tokenization
Records verified asset valuation and creates a blockchain-based digital representation only after required verification and validation steps are completed.

### 5. Digital Asset Passport & QR Verification
Provides a complete digital profile containing:

- Asset identity
- Asset type
- Owner
- Verified value
- Verification status
- SHA-256 fingerprint
- Digital asset ID
- Lifecycle status
- Ownership history

### 6. Smart-Contract Ownership Transfer
Hyperledger Fabric chaincode governs ownership transfers by validating conditions such as:

- Current owner authorization
- Asset verification
- Active lifecycle status
- Eligible new owner
- Valid transfer state

### 7. Immutable Provenance
Maintains a chronological record of important asset events including registration, verification, valuation, tokenization, ownership transfer, and retirement.

### 8. Role-Based Access Control
Provides controlled access for different participants such as:

- Asset Owner
- Verifier
- Buyer
- Auditor

### 9. Asset Search & Filtering
Enables users to quickly locate assets using:

- Asset ID
- Asset type
- Owner
- Verification status
- Lifecycle status

### 10. Tamper-Evident Document Verification
Uses cryptographic hashing of supporting documents to detect changes between the registered evidence and later verification.

---

## 🔄 Asset Lifecycle

```text
┌──────────────┐
│  Registration│
└──────┬───────┘
       ↓
┌──────────────┐
│ Verification │
└──────┬───────┘
       ↓
┌────────────────────┐
│ Fingerprint        │
│ Generation         │
└──────┬─────────────┘
       ↓
┌──────────────┐
│  Valuation   │
└──────┬───────┘
       ↓
┌──────────────┐
│ Tokenization │
└──────┬───────┘
       ↓
┌──────────────────┐
│ Active Ownership │
└──────┬───────────┘
       ↓
┌────────────────────┐
│ Ownership Transfer │
└──────┬─────────────┘
       ↓
┌──────────────┐
│   Retirement │
└──────────────┘
