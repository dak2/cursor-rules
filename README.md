# cursor-rules

## Overview
This repository contains rule definitions for Cursor AI to follow when working with various technologies.  
It acts as a configuration hub that enforces consistent coding patterns and best practices.

## Structure
- `.cursor/rules/` — Directory that houses all rule definition files. Cursor AI automatically reads any `.mdc` files here.  
  - `vibe-activerecord.mdc` — Provides guidelines for using ActiveRecord in Vibe projects.

## Rule Format
- Rules are written in `.mdc` (Markdown-Cursor) files.  
- Rule files may be authored in multiple languages (the current example is in Japanese).

## Current Rules
| File | Scope | Summary |
|------|-------|---------|
| `vibe-activerecord.mdc` | ActiveRecord | Recommended usage patterns and conventions for ActiveRecord within Vibe applications. |

## Usage
1. Keep your rule files in the `.cursor/rules` directory.  
2. Open the project with Cursor AI; the rules are automatically loaded and applied to all AI-assisted tasks.

---
_This repository is maintained to ensure teams follow consistent standards across projects._
