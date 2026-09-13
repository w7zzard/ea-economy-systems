<div align="center">

# 💊 EA Economy Systems

### Economy • Inventory • Processing • Crafting • Conversion • Progression

Developed by **W7zzard**  
Built for **East Atlanta Stories**

![FiveM](https://img.shields.io/badge/FiveM-Cfx.re-black?style=for-the-badge)
![Lua](https://img.shields.io/badge/Lua-Development-black?style=for-the-badge&logo=lua)
![JavaScript](https://img.shields.io/badge/JavaScript-Development-black?style=for-the-badge&logo=javascript)
![SQL](https://img.shields.io/badge/SQL-Database-black?style=for-the-badge&logo=mysql)

</div>

---

## Overview

**EA Economy Systems** represents the economy, item processing, inventory logic, conversion systems, and progression-based reward architecture used across **East Atlanta Stories**.

These systems are designed to support a controlled in-game economy instead of random or unbalanced money/item generation. Development focuses on realistic item flow, server-side validation, progression, inventory integration, and long-term economic stability.

This repository serves as a public technical case study.

Production source code, configuration, credentials, database structure, and proprietary implementation remain private.

---

# Core Responsibilities

My development work across the East Atlanta economy includes:

- Economy architecture
- Item processing systems
- Inventory integration
- Conversion logic
- Crafting flows
- Server-side reward validation
- Shop configuration
- Progression balancing
- Gang package distribution
- Persistent item state
- SQL-backed data logic
- Exploit-resistant reward handling
- Economy troubleshooting
- Missing item investigations

---

# Economy Design Goals

The economy is developed with a focus on:

- Controlled item generation
- Balanced player earnings
- Multi-stage processing
- Inventory consistency
- Meaningful progression
- Server-side validation
- Reduced exploit opportunities
- Long-term economic sustainability

The goal is to make the economy feel active and rewarding without allowing systems to become broken or inflationary.

---

# Inventory Integration

Economy systems are tightly connected to the server inventory framework.

This includes handling for:

- Raw materials
- Processed materials
- Packaged items
- Stackable items
- Usable items
- Shop items
- Reward items
- Conversion outputs

Consistency in item naming, stacking behavior, and conversion flow is important to prevent broken crafting or duplicate inventory states.

---

# Item Processing Systems

East Atlanta Stories uses multi-stage item processing flows.

These systems can include:

- Raw input collection
- Conversion steps
- Ingredient validation
- Quantity checks
- Item removal
- Output generation
- Inventory return
- Database-backed persistence

This creates a more realistic economy loop than simply giving players a final item instantly.

---

# Conversion Logic

Economy systems can support quantity conversions such as:

```text
Kilo → Ounces → Grams
Pounds → Grams
Raw Material → Processed Material
Processed Material → Packaged Product
