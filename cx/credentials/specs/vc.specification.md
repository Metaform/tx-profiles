# Catena-X Verifiable Credential Profile Specification

This document defines the Catena-X Verifiable Credential Profile used
with [The Identity and Trust Protocol (IATP)](https://github.com/eclipse-tractusx/identity-trust).

## 1. Interoperable Credential Data Model and Encodings

Verifiable Credentials (VC) are based on the [W3C VC Data Model](https://www.w3.org/TR/vc-data-model/#dfn-holders).
The interoperable encoding format for VCs and Verifiable Presentations (VP) is JWT as detailed in the previous
specification.

VCs MUST contain an `issuanceDate` and MAY `expirationDate`. JWTs MUST contain an `iat` claim equal to
the `issuanceDate` and an `exp` equal to the `expirationDate`, if present.

## 2. Interoperable Credential Types

The following credential types MUST be supported by participants.

### 2.1. The `BpnCredential` Type

### 2.2. The `DismantlerCredential` Type

### 2.3. The `MembershipCredential` Type

### 2.4. Framework Credential Types

#### 2.4.1. The `BehaviorTwinCredential` Type

#### 2.4.2. The `PcfCredential` Type

#### 2.4.3. The `QualityCredential` Type

#### 2.4.4. The `ResiliencyCredential` Type

#### 2.4.5. The `Credential` Type

#### 2.4.6. The `SustainabilityCredential` Type

#### 2.4.7. The `TraceabilityCredential` Type

