# Legal Request Current Process

This document describes the current manual legal request process and its pain points.
# Current-State Legal Request Process

## Purpose

This document explains the current manual legal request process in a business environment and identifies the main operational pain points.

## Current Process

1. Business team sends legal request by email, chat, or informal message
2. Legal team manually reviews the request
3. Missing information is requested through follow-up emails
4. Priority is decided manually
5. Legal expert works on the request
6. Status updates are shared manually
7. Request is closed without structured KPI tracking

## Current-State Process Flow

```mermaid
flowchart TD
A[Business Team Sends Legal Request] --> B[Email or Chat Message]
B --> C[Legal Team Reviews Request Manually]
C --> D{Information Complete?}
D -->|No| E[Request More Details]
E --> B
D -->|Yes| F[Legal Team Prioritizes Request]
F --> G[Legal Expert Works on Request]
G --> H[Manual Status Update]
H --> I[Request Closed]
