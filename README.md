# 🛡️ ScammerLedger

A transparent, automated system that indexes **confirmed Discord scammer listings** from a trusted server and publishes them as a **public, read-only dataset** for safety and moderation tools.

---

## Overview

ScammerLedger maintains a continuously updated ledger of confirmed scam-related Discord accounts in a structured, machine-readable format.

A private indexing service monitors a controlled Discord channel and publishes **data only** (not code, not secrets) to this repository for public consumption.

---

## What ScammerLedger Does

- Monitors a trusted scam-report channel on Discord
- Parses confirmed scammer entries
- Automatically removes entries marked as resolved or incorrect
- Publishes structured JSON files to this repository
- Maintains a clean, auditable Git history

This repository acts **only as a data feed**.

---

## What ScammerLedger Does NOT Do

- ❌ No auto-banning
- ❌ No real-time enforcement
- ❌ No moderation decisions
- ❌ No hidden or private blacklist

ScammerLedger **does not take action on users**.  
It only provides **public, auditable information**.

---

## Data Source Rules

- Data originates from a **moderator-controlled Discord channel**
- Only explicitly listed and confirmed entries are indexed
- Entries marked with strikethrough (`~~`) are treated as **removed / proven legit**
- The Discord channel is the **single source of truth**

---

## Data Format

Each entry is stored as a JSON object:

```json
{
  "name": "@username",
  "id": "123456789012345678",
  "reason": "Reason for listing"
}
