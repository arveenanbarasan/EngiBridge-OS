# EngiBridge OS

**End-to-End Enterprise Construction Operating System & Automated ESG Ledger**

*Notice: The core algorithms, proprietary schemas, and full source code for this platform are currently closed-source. This repository serves as an architectural overview and technical showcase of the system's design and capabilities. Live deployment: [app.engibridge.com](https://app.engibridge.com/)*

## Overview

EngiBridge OS is an independent, full-stack engineering project built to unify fragmented construction workflows into a single workspace. Developed to test modern full-stack software architecture against real civil engineering, commercial margin, and sustainability bottlenecks, the platform connects site-level scheduling directly with live financial controls and automated Scope 1, 2, and 3 carbon accounting.

## Core System Architecture & Features

### 1. Predictive Project Management
Synchronizes interactive Gantt and Kanban project schedules directly with daily site diaries. Integrates AI-assisted forecasting logic to detect critical-path slippage early and surface timeline delays before they cascade across subcontractor packages.

### 2. Granular Commercial Hub
A real-time financial control ledger engineered to lock project budgets and track exact material supply breakdowns. Centralizes line-item cost visibility, Variation Orders (VOs), and progress payment certificates to protect commercial margins.

### 3. Automated ESG Carbon Ledger
Generates audit-ready Scope 1, 2, and 3 carbon emissions data automatically from procurement and material logs. Eliminates manual spreadsheet entry and reduces greenwashing risks by tying sustainability metrics directly to physical site inputs.

### 4. Governance & Workforce Compliance Shield
Real-time credential and safety tracking for site licenses, CIDB/safety passports, and worker permits. Features automated 30-day advance expiry alerts to prevent regulatory lapses on active sites.

## Technical Stack & Security Design

* **Frontend Architecture:** React, Next.js, TypeScript, Tailwind CSS (modular Bento Grid UI designed for low-friction field and office usability).
* **Backend & Database:** Supabase (PostgreSQL), Edge Functions, and RESTful API integrations.
* **Security & Multi-Tenancy:** Strict Role-Based Access Control (RBAC) and PostgreSQL Row-Level Security (RLS) policies separating Main Contractors, Subcontractors, Commercial Directors, and Safety/QA Officers.
