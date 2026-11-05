# Midas Lead Intake

An n8n workflow that takes agency leads from a form to an AI-drafted follow-up and a CRM row, built for Midas Marketing.

## The flow, in order

1. Form Trigger receives the lead.
2. Edit Fields normalizes name, contact, and need.
3. An AI Agent step drafts the first follow-up in the agency's voice.
4. A Google Sheets node appends the lead and the draft to the intake sheet.

## Status

Built and running on n8n Cloud. The AI drafting step is in draft tuning.

## What it replaced

Manual inbox triage of new leads.

This repo is design and workflow documentation only. No credentials, no keys, no personal data.

© 2026 Razi Ismail. All rights reserved. Showcase material: architecture and documentation only.
