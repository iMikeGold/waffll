=====================================================================
# G01DN CONTENT STANDARD
Version : 1.0.0
Status  : Active Implementation Standard
Purpose : Structuring, Lifespan, and Integrity of Content
=====================================================================

## Overview

This document defines how content must be structured and preserved.

Content is treated as the most permanent layer in the system.

---

## Core Principle

Content is the source of truth.

Everything else is a transformation of content.

---

## Content Independence Rule

Content must not depend on:

- UI structure
- frontend frameworks
- database schemas
- API design

It must remain portable across systems.

---

## Structure Rule

Content must be:

- modular
- reusable
- clearly scoped
- context-independent

---

## Content Types

The system recognises:

- narrative content
- technical content
- philosophical content
- operational content
- reference content

---

## Lifecycle Principle

Content should:

- evolve slowly
- accumulate value over time
- remain valid long-term
- outlive implementation layers

---

## Storage Rule

Content must live in:

content/

and never be mixed with:

system/
main-site/
architecture/

---

## Transformation Rule

Content is transformed into:

- interface pages
- documentation
- publications
- media outputs

but is never overwritten by them.

---

## Integrity Rule

No interface layer may modify canonical content directly.

All changes must originate in content/.

---

## End
