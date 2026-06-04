# Legal Request Form UX Design

This document explains the user-friendly design of a legal request intake form.

## Purpose

This document explains the user experience design of a digital legal request intake form.

The goal is to make legal support easier for non-legal business users by using simple language, structured fields, dropdown menus, and clear guidance.

## Design Goal

The legal request form should help business users submit complete and useful information without needing legal expertise.

A well-designed form reduces:

- Missing information
- Repeated follow-ups
- Manual clarification
- Incorrect routing
- Delays in legal review

## Proposed Form Fields

| Field | Field Type | Purpose |
|---|---|---|
| Requester Name | Text field | Identify requester |
| Business Unit | Dropdown | Understand department |
| Request Type | Dropdown | Route request correctly |
| Business Impact | Dropdown | Understand importance |
| Urgency Level | Dropdown | Support prioritization |
| Required Deadline | Date field | Manage SLA and timeline |
| Description of Request | Long text | Capture context |
| Attachment Upload | File upload | Include contracts or documents |
| Risk Indicator | Dropdown | Identify sensitive requests |
| Personal Data Involved? | Yes/No | Identify GDPR or privacy relevance |

## Request Type Options

- Contract review
- Vendor agreement
- Data protection / GDPR question
- Debt collection process question
- Compliance policy support
- Customer communication review
- General legal guidance

## UX Principles

| Principle | Application |
|---|---|
| Simple language | Avoid complex legal terms |
| Guided input | Use dropdowns and examples |
| Mandatory fields | Ensure important information is captured |
| Clear routing | Request type decides legal queue |
| Transparency | Show expected response time |
| Confirmation | Send automatic submission confirmation |
| Accessibility | Keep layout simple and readable |

## Example Help Text

| Field | Example Help Text |
|---|---|
| Request Type | Choose the option that best describes your request |
| Business Impact | Explain how this request affects your team or customer |
| Urgency Level | Select urgent only when there is a real business deadline |
| Personal Data Involved? | Select yes if customer, employee, or partner personal data is included |

## Expected User Journey

```mermaid
flowchart TD
A[Business User Opens Form] --> B[Select Request Type]
B --> C[Complete Required Fields]
C --> D[Upload Supporting Documents]
D --> E[Review Information]
E --> F[Submit Request]
F --> G[Receive Confirmation]
G --> H[Track Status Through Updates]
