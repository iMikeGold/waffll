=====================================================================
# G01DN IMPLEMENTATION PROTOCOL
Version : 1.0.1

Status  : Active Implementation Standard

Purpose : Repository Organisation & Interface Separation

=====================================================================

## Overview

This document defines the operational structure used within this repository.

It exists to enforce consistency, reduce architectural drift, and ensure long-term maintainability.

---

## Repository Layers

Repositories must be separated into clear functional domains.

architecture/
    System standards, rules, and structural definitions.

content/
    Source material and canonical information.

main-site/
    Public-facing interface implementation.

system/
    Logs, experiments, snapshots, and internal state.

docs/
    Human-readable documentation.

---

## Interface Principle

Public interfaces must remain independent of internal structure.

Interfaces consume content and present experiences.

Internal organisation must not dictate public navigation or URL structure.

---

## Source of Truth Principle

Content is the canonical source of information.

Code is a rendering layer only.

Changing frameworks or implementation technologies must not require rewriting content.

---

## Naming Principle

Folder names must describe function, not technology.

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

unless strictly required by a framework.

---

## Future Compatibility Principle

Repository structure must be designed for long-term evolution.

Unused or empty directories are permitted if they represent stable conceptual domains.

Short-term convenience must not override structural clarity.

---

## Information Flow

content
  ↓
interface
  ↓
implementation
  ↓
user experience

---

## Layer Relationship

G01DN Standard
  ↓
Repository Structure
  ↓
WAFFLL Implementation
  ↓
main-site Interface

---

## End
