# Democracy / Stakeholder Association Contract Verification

**Contract:** `0xf51b553f58fceb239d0c38ef44cda49ae6523848`
**Deployer:** `0x11cc55d554af0762fbeaf1b36906f6e345c9e95e`
**Block:** 919,852
**Date:** January 29, 2016
**Language:** Solidity
**Status:** Exact bytecode match (byte-for-byte creation TX)

## What This Is

A deployment of the ethereum.org "Stakeholder Association" DAO tutorial contract. A German-speaking developer tested the official Ethereum governance tutorial, deploying it with a custom "NurTesting" governance token (German: "just testing"). They actively used the contract, submitting and voting on proposals.

## Source

**File:** `Association.sol`
**Base:** [ethereum.org DAO tutorial](https://github.com/ethereum/ethereum-org) - "Stakeholder Association" section
**Key difference from the simplified Mist DAO version:** includes the canonical `if (minimumSharesForVoting == 0) minimumSharesForVoting = 1;` zero-guard in the constructor.

## Compiler

- **Version:** `soljson-v0.1.5+commit.23865e39.js`
- **Optimizer:** Enabled

## Constructor Arguments

| Arg | Value |
|-----|-------|
| sharesAddress | `0x12b06fe665f2ba537cc9f87e6cf8f79e2d00b482` (NurTesting token) |
| minimumSharesForVoting | 500 |
| minutesForDebate | 10 |

## Proof

| Field | Value |
|-------|-------|
| On-chain address | `0xf51b553f58fceb239d0c38ef44cda49ae6523848` |
| Creation TX | `0x27ec2f293017eafe97429aa1051098736e3f2c7a95f6911303bc0c7a001b5a8d` |
| Block | 919,852 |
| Runtime | 3,275 bytes |
| Differences | **0** (exact creation TX match) |
