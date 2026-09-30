# TOCA 2 Touring Cars

Private English EU Rev 1 candidate (SLES-01542). Both builds pass setup checks; a headless startup reaches the Codemasters logo. English menus and gameplay remain unverified.
Status, setup instructions and evidence: [T173](https://app.notion.com/p/3e11cf959a4c8119b6d7cf9b19d44f28).

<!-- release-standard:bios -->
**BIOS:** SCPH-5552 (Europe) retail BIOS, 524288 bytes, SHA-256 `1faaa18fa820a0225e488d9f086296b8e6c46df739666093987ff7d8fd352c09`. Supply your own dump; releases do not use OpenBIOS.
<!-- /release-standard:bios -->

## About this project

These ports are developed by a hobbyist (a DevSecOps engineer, not a game
programmer) with substantial AI assistance. What keeps that honest: every
change is validated before it ships - boot gates, hardware-oracle A/B
comparisons (Beetle/DuckStation), deterministic replay probes, and a shared
findings registry that documents failures as carefully as successes. AI
writes most of the code; the evidence discipline decides what survives.
Bug reports welcome - expect them to be investigated the same way.

tl;dr AI writes the code, but I always test it myself before pushing

<!-- framework-pin -->
**Framework:** `psxrecomp` and `recomp-ui` are submodules pinned to test pin F (psxrecomp `a3e5fd892`, recomp-ui `8cf5b08`). Re-point both to pin G at release (PS1B-275). CI: Woodpecker, manual runs (`.woodpecker/`).
<!-- /framework-pin -->
