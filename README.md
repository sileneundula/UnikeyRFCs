# UnikeyRFCs
An Open Standard For Universal Keys

## Server Style

A server is located that stores the keys with their information, derivations, and more.

## Key Types

### 0x00 (Standard)
- ED25519 (Signing)
- ECIES over Curve25519 (Encryption)

### 0x01 (PQ)
- SPHINCS+ (Signing)
- ECIES over Curve25519 (Encryption)

## UniversalKey

UniversalKey can be used to login to any site using digital signatures.

## SLAB METHOD

The SLAB Method allows only a certain portion of information to be displayed to the other party.
