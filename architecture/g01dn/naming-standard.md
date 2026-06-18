=====================================================================
# G01DN NAMING STANDARD
Version : 1.0

Status  : Active Implementation Standard

Purpose : Naming Conventions Across Repository Systems

=====================================================================

## Overview

This document defines naming rules for all files, folders, and content within the repository.

Its purpose is to ensure clarity, predictability, and long-term consistency across all WAFFLL systems.

---

## Core Principle

Names describe function, not implementation.

A name must remain valid even if technology changes.

---

## Folder Naming Rules

Folders must represent stable conceptual domains.

Preferred:

main-site/
content/
system/
architecture/
docs/

Avoid:

web/
app/
src/
frontend/
backend/

unless strictly required by framework constraints.

---

## File Naming Rules

Files must be:

- lowercase
- hyphen-separated
- descriptive of purpose
- free of ambiguous abbreviations

Examples:

Preferred:

content-standard.md
repo-standard.md
naming-standard.md

Avoid:

ContentStandard.md
cs.md
final_version_really_final.md

---

## Content Naming Rules

Content titles must remain:

- human readable
- stable over time
- independent of formatting system

A title should survive migration between platforms.

---

## Versioning Principle

Standards files are versioned inside the document only.

File names are never used for versioning.

---

## Forbidden Patterns

Do not use:

- technology-based naming
- temporary naming conventions
- emotional naming (“final”, “latest”, “new”)
- duplicated meaning names

---

## Relationship Rule

Naming sits above implementation.

It defines how systems are understood before they are built.

---

## End
