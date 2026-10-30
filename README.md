# Northbridge Utilities Upgrade Database

## Overview

A personal document-control and governance sandbox containing 1,000 document records and six supporting tables.

The project demonstrates relational information modelling, metadata definitions, asset relationships, review and approval tracking, permission definitions and controlled vocabularies in a CDE-oriented environment.

This is a portfolio demonstrator, not a production EDMS or operational CDE.

## Seven-table architecture

| Layer | Tables |
|---|---|
| Core records | Documents; Assets |
| Governance and control | Workflows; Access Roles; Audit Events |
| Metadata and standards | Data Dictionaries; Picklists |

## Relationships

- Documents link to Assets, Workflows, Access Roles and Audit Events.
- Workflows also link to Access Roles.
- Data Dictionaries link to Picklists.

The implementation uses linked records, lookups, rollups, formulas and managed metadata fields.

## Completed quality-improvement activity

Reconciled the Picklists reference against actual dropdown settings.

Verified 16 entries across five lists:
- Document Status: 4
- Asset Condition: 3
- Workflow State: 4
- Access Role Permission: 4
- Access Role Scope: 1

Resolved missing options, inconsistent values, and corrected structural schema links to ensure full referential integrity across the asset tracking lifecycle.
