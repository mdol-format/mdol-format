STATUS: DRAFT / IN PROGRESS

# Markdown Object Language (MDOL) Specifications

## Overview

Markdown Object Language is a simple nested object notation language based on the markdown format.
It can be used for storing object data, structures, schemas, or configuration data.

## Structure

MDOL outputs a recursively nested object.

At every level, the object can have any number of keys, which are not necessarily unique.

If a key at a level is duplicate, the key is considered to be an array key.

!!!TODO!!!
- nesting
- starting depth
- heading vs lists



## Syntax and Grammar

!!!TODO!!!



## Format

!!!TODO!!!




## Markdown Compatibility

### Markdown Backwards Compatibility

- Headings ``# Heading``
- Unnumbered Lists ``- Item`` or  ``* Item`` or  ``+ Item``
- Numbered lists ``1. Item``

### Extensions to markdown:

- Comment-lines via ``// comment `` 
- Comment-blocks via ``/* comment */``

## Conventions

### Root Heading

The first heading (if any) describes the file contents or type.

### Preferred Shorthand

Use un-numbered lists without bullets for repeated entries, use heading for main sections.

### File Ending

Official file ending for objects: ``.mdo``
Official file ending for configurations: ``.mdc``
