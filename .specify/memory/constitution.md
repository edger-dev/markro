<!--
---
Version change: none → 1.0.0
Modified principles:
- [PRINCIPLE_1_NAME] → Modular
- [PRINCIPLE_2_NAME] → Core-First
- [PRINCIPLE_3_NAME] → Quality-Code
Added sections:
- Core Principles
- Governance
Removed sections:
- [PRINCIPLE_4_NAME]
- [PRINCIPLE_5_NAME]
- [SECTION_2_NAME]
- [SECTION_3_NAME]
Templates requiring updates:
- ✅ /home/yjpark/projects/edger-dev/markro/.specify/templates/plan-template.md
- ✅ /home/yjpark/projects/edger-dev/markro/README.md
Follow-up TODOs: none
---
-->
# Markro Constitution

## Core Principles

### Modular
The logic should be separated to modules, which can be implemented and tested individually, the exposed API should be clean and well designed, make the whole system easy to maintain, flexible, and extensible

### Core-First
The core features are having first priority, these are mainly pure functions, with well defined input and output, user interface will be built on top of the core, may provide multiple ways for interaction, e.g. CLI, GUI, MCP...

### Quality-Code
The codebase should have high quality, having good observability with well designed metrics, logging, test cases, etc. it should have high performance, and more importantly, should be easy to read and maintain

## Governance
All PRs/reviews should verify compliance with the constitution.

**Version**: 1.0.0 | **Ratified**: 2025-10-03 | **Last Amended**: 2025-10-03
