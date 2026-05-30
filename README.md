# ProjectPulse

## Transforming Project Communication into Operational Intelligence

ProjectPulse is an AI-powered operational intelligence agent that transforms fragmented project communication into actionable project insights using Microsoft Copilot Studio, Power Automate, Outlook, and SharePoint Online.

## Problem Statement

Project managers and leadership teams often struggle to understand project health because critical information is scattered across:

- Email conversations
- Attachments
- Customer escalations
- Status updates
- Internal discussions

Important operational signals such as risks, unresolved actions, customer concerns, and escalation indicators remain buried in unstructured communication.

As projects grow in complexity, stakeholders spend significant time reviewing emails and documents to understand project status and emerging risks.


## Solution

ProjectPulse continuously monitors project communication and converts it into structured operational intelligence.

The solution:

- Ingests project emails and attachments
- Extracts project identifiers
- Organizes content into project repositories
- Enriches communication with risk and escalation metadata
- Enables natural language project intelligence queries
- Supports project managers and leadership with actionable insights

## Conceptual Solution Flow

The diagram below illustrates how ProjectPulse transforms project-related communication into operational intelligence using Outlook, Power Automate, SharePoint Online, and Copilot Studio.
<img width="1536" height="1024" alt="ConceptualDiagram" src="https://github.com/user-attachments/assets/43008424-eefa-4312-a7cd-a10754dcb45a" />


## Architecture

## Architecture


## Architecture

```text
Project Communication
(Emails + Attachments)
              │
              ▼
      Outlook Mailbox
              │
              ▼
      Power Automate
              │
      ┌───────┼────────┐
      │       │        │
      ▼       ▼        ▼
Project ID  Metadata  Attachment
Extraction Enrichment Processing

              │
              ▼
     SharePoint Repository
      (Project Knowledge Hub)

      ┌────────┬─────────┬─────────┐
      │        │         │         │
      ▼        ▼         ▼         ▼
 Project   Risk      Email      Supporting
 Files     Level     Type       Documents

              │
              ▼
      Copilot Studio Agent

              │
      ┌───────┼─────────────┐
      │       │             │
      ▼       ▼             ▼
 Project   Risk &       Executive
 Summary   Escalation   Insights
            Analysis

              │
              ▼
      Operational Intelligence
```




## Example Questions

Project managers can ask:

- Tell me about Project P-1045
- Why is Project P-1045 considered high risk?
- What customer concerns remain unresolved?
- Which emails contributed to delivery risk?
- Generate an executive project update
- What operational blockers currently exist?

## Why It Matters

Organizations do not suffer from lack of information.

They suffer from fragmented project communication spread across emails, attachments, escalations, and status updates.

ProjectPulse transforms this fragmented communication into structured operational intelligence, helping teams identify risks earlier and improve project visibility.


## What Makes ProjectPulse Different?

Traditional copilots retrieve information.

ProjectPulse enriches project communication with operational metadata such as:

- Risk Level
- Email Type
- Escalation Indicators
- Project Identifiers

before AI reasoning occurs.

This enables users to understand project health and operational risk instead of simply searching documents.


## Solution Screenshots

### Outlook Project Email

### Power Automate Processing Flow

### SharePoint Intelligence Repository

### Copilot Studio Risk Analysis

### Executive Summary Generation


## Demo Video

Video walkthrough: Coming soon
