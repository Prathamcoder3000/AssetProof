# AssetProof

### Real-World Asset Verification & Tokenization Platform

AssetProof is a Hyperledger Fabric-based platform for registering, verifying, valuing, digitally representing, transferring, and tracking real-world assets through their complete lifecycle.

The platform is designed to support multiple asset types such as **land, commodities, and invoices**, while maintaining a trusted and traceable digital record of each asset.

---

## Problem Statement

**PS-01 — Real-World Asset Tokenization Platform**

Build a platform on Hyperledger Fabric that takes a real-world asset from **registration to retirement**.

The platform should ensure that assets are:

- Registered with unique identities
- Verified using supporting evidence
- Valued before digital representation
- Represented digitally on a permissioned blockchain
- Governed through controlled ownership transfers
- Traceable through their complete lifecycle
- Retirable while preserving historical records

---

## Key Features

### 1. Multi-Asset Support
Supports different real-world asset categories using a common asset framework:

- Land
- Commodities
- Invoices

### 2. Asset Registration & Verification
Creates unique asset records and allows authorized users to verify asset information and supporting evidence.

### 3. Asset Fingerprint
Generates a SHA-256 cryptographic fingerprint from verified asset information and supporting evidence to help detect changes to the registered record.

### 4. Asset Valuation & Tokenization
Records the verified asset value and creates a blockchain-based digital representation only after required validation steps are completed.

### 5. Digital Asset Passport & QR Verification
Provides a complete digital profile containing asset identity, owner, value, verification status, fingerprint, lifecycle status, and digital asset information.

### 6. Smart-Contract Ownership Transfer & Lifecycle Governance
Uses Hyperledger Fabric chaincode to control ownership transfers and valid lifecycle transitions.

### 7. Immutable Provenance & Asset Protection
Maintains a traceable history of important asset and ownership events while preventing invalid operations on inactive or retired assets.

### 8. Role-Based Access Control
Provides controlled access for different participants such as asset owners, verifiers, buyers, and auditors.

### 9. Asset Search & Filtering
Allows users to quickly find assets using asset ID, asset type, owner, verification status, and lifecycle status.

### 10. Tamper-Evident Document Verification
Uses document hashing to compare supporting evidence and identify changes to registered documents.

---

## Asset Lifecycle

```text
Registration
     ↓
Verification
     ↓
Fingerprint Generation
     ↓
Valuation
     ↓
Tokenization
     ↓
Active Ownership
     ↓
Ownership Transfer
     ↓
Retirement
