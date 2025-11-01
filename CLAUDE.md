# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This repository manages legal terms of service and contracts for 株式会社オノコム (Onocomm Corporation). It maintains:
- A base contract (`contract_jp.md`) that applies to all services
- Individual service-specific contracts in the `services/` directory
- Complete version history and change tracking

## Repository Structure and Naming Conventions

### Directory Layout

```
terms-of-service/
├── contract_jp.md                    # Current base contract (applies to all services)
├── contract-jp-history.md            # Base contract change history
├── archive/                          # Historical versions of base contract
│   └── v[N]_YYYY-MM-DD.md           # Past versions (v1, v2, v3, v4)
├── CHANGELOG.md                      # Unified change history (all services)
└── services/                         # Individual service contracts
    └── [service-id]/                 # One directory per service
        ├── [service-id]-contract.md  # Current contract
        ├── [service-id]-history.md   # Service-specific change history
        └── archive/                  # Future versions will go here
```

### Strict Naming Convention

**Critical**: All files MUST follow this pattern: `[service-id]-[document-type].md`

- Service identifiers: `aws-support`, `aws-build`, `mail-virus-check`
- Document types: `contract`, `history`, `terms`
- Examples:
  - `aws-support-contract.md` (NOT `contract.md`)
  - `aws-support-history.md` (NOT `HISTORY.md`)
  - `mail-virus-check-terms.md` (for regulations, not contracts)

**Exception**: The base contract uses `contract_jp.md` (underscore) and `contract-jp-history.md` (hyphen).

### Archive vs. History Files

- **archive/**: Contains past complete versions of contracts (`v1_YYYY-MM-DD.md`, `v2_YYYY-MM-DD.md`)
- **history files** (`*-history.md`): Markdown documents explaining what changed between versions
- History files are stored at the SAME LEVEL as their corresponding contracts (not in archive/)

## Document Types

### Contracts vs. Terms

- **契約約款** (contract): Use `-contract.md` suffix
- **利用規約** (terms/regulations): Use `-terms.md` suffix

Example: `mail-virus-check-terms.md` uses "terms" because it's an optional add-on service regulation, not a standalone contract.

### Non-Contract Documents

In addition to legal contracts and terms, this repository contains procedural documents:

- **application.md**: Lists application forms for various service-related procedures
  - Not a legal contract, but a reference guide for users
  - Contains Google Forms URLs for account applications, domain requests, certificate issuance, etc.
  - Should be updated when new application forms are added or URLs change

## Adding New Service Contracts

When adding a new service contract:

1. Create directory: `services/[service-id]/`
2. Create files:
   - `[service-id]-contract.md` or `[service-id]-terms.md`
   - `[service-id]-history.md`
   - `archive/` (initially empty)
3. Update `README.md`:
   - Add to repository structure diagram
   - Add service description section
   - Add to change history links
4. Update `CHANGELOG.md`:
   - Add to legend (凡例)
   - Add entry for the new version
   - Add to related documents section

## Historical Name Changes

**Important**: The base contract was renamed in 2025:
- Old: "オノコムクラウドサービス契約約款" (Onocomm Cloud Service Contract)
- Current: "オノコムサービス契約約款" (Onocomm Service Contract)

When working with older documents (pre-2025):
- Update references to use current terminology: "オノコムサービス契約約款" or "基本約款"
- Add explanatory notes in the history file about the name change
- See `services/mail-virus-check/mail-virus-check-terms.md` (lines 81-83) for example

## Document Formatting Standards

### Contract Headers

Every contract/terms file must include:
```markdown
# [サービス名]

**制定日**: YYYY年MM月DD日
**版**: 第N版
```

### Version History Table

Include at the bottom of each contract:
```markdown
## 改訂履歴

| 版 | 施行日 | 主な変更内容 |
|---|---|---|
| 第1版 | YYYY年MM月DD日 | 初版制定 |
```

### History File Structure

History files follow this structure:
```markdown
# [サービス名] 変更履歴

## 第N版 - YYYY年MM月DD日

### [変更の種類]

#### 主要な特徴
...
```

## Cross-Referencing

- Base contract is referenced as "基本約款" in service contracts
- Individual service contracts specify that the base contract applies to items not covered
- CHANGELOG.md uses abbreviations: `[基本約款]`, `[AWS サポート]`, `[AWS 構築]`, `[メールウイルス]`

## Git Repository

This is a Git repository on the `main` branch. All contract changes should be committed with descriptive messages indicating the version and nature of changes.
