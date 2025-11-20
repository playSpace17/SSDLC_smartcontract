
## Intro
This document provides a brief overview of the formal specification for a zk-based electronic voting system. It summarizes the purpose, scope, and the use of formal methods to ensure reliability and security in smart-contract-driven voting environments.

## Purpose
Defines the core goals of applying formal specification to a smart-contract voting system, including prevention of invalid votes, double voting, and leakage of vote content.

## Terminology
Covers essential terms such as voter, Merkle tree, ZK proof, ballot, system state, safety, and liveness.

## Why Formal Methods
Explains the relevance of TLA+ in modeling smart contract behavior and verifying correctness before deployment.

## System Specification Overview
Summarizes the overall flow of the voting system: initialization, registration, key generation, voting, verification, tallying, and publishing.

## State Transitions
Provides a high-level explanation of how the system moves between phases.

## Verification & Tallying
Describes the simplified process of verifying encrypted ballots and tallying only validated votes.

## Finalization
Outlines how results are published once all ballots are validated and tallied.
