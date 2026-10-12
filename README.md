
# WIP Management & Production Control System

**A database-driven manufacturing application for tracking production progress, work-in-progress balances, and finished goods movement.**

Built with **Appsmith, Supabase, PostgreSQL, and REST APIs**, this project demonstrates how manufacturing workflows can be represented in a structured business application.

## Overview

Manufacturing operations require reliable visibility into material issuance, production progress, quality losses, and finished goods. When these activities are difficult to track across production stages, reconciling quantities and identifying outstanding work becomes more challenging.

The WIP Management & Production Control System was developed to address this operational challenge by bringing work-in-progress records and production tracking into a central application.

The project applies practical manufacturing knowledge to business application development, with a focus on data visibility, quantity tracking, and operational control.

## Business Problem

A manufacturing team needs to answer important operational questions:

- How much material has been issued against a sales order?
- How much production has been completed?
- How many pieces or how much weight has been scrapped, resized, or returned?
- What quantity remains in work-in-progress?
- Which production stages require further processing?

This project provides a structured application for monitoring these activities and making production information easier to review.

## Key Capabilities

- **WIP issuance tracking** — maintain visibility into material issued for production.
- **Sales order monitoring** — associate production records with relevant customer and order information.
- **Production stage tracking** — organize manufacturing activity across relevant departments.
- **Quantity reconciliation** — monitor processed, scrapped, resized, and returned quantities where applicable.
- **WIP balance visibility** — help identify outstanding quantities during production.
- **Database-backed operations** — use Supabase and PostgreSQL to store and retrieve operational records.
- **Interactive business interface** — use Appsmith to present production information in structured tables and workflows.

## Manufacturing Workflow

The application reflects an aluminium manufacturing environment with production stages including:

1. Anodizing
2. Pretreatment
3. Powder Coating
4. Packing

The workflow reflects different processing routes depending on the product finish, rather than treating every order as an identical production sequence.

## Technology Stack

| Technology | Role |
|---|---|
| Appsmith | Application interface, tables, and user interactions |
| Supabase | Backend platform and database access |
| PostgreSQL | Relational storage for operational records |
| REST API | Communication between the application and backend |

## Application Architecture

The application follows a straightforward client-to-database architecture:

**User → Appsmith interface → REST API → Supabase/PostgreSQL**

1. Users interact with production records through the Appsmith interface.
2. Application queries retrieve or update data through the Supabase REST API.
3. PostgreSQL stores the underlying operational records.
4. Retrieved data is displayed to support production monitoring and quantity reconciliation.

This structure demonstrates the integration of a business application interface with a relational database and API-based data access.

## Skills Demonstrated

- Business process analysis
- Manufacturing workflow modelling
- Relational database concepts
- SQL and PostgreSQL fundamentals
- REST API integration
- Data-driven application development
- Operational quantity tracking and reconciliation
- Translating practical business requirements into software workflows

## Technology Demonstration

**Live application walkthrough:**  
[Watch the WIP Tracker demonstration](https://www.loom.com/share/8bfa3fccfa574576a6ed1c230f98c2ca)

The walkthrough demonstrates the application interface and selected production-tracking workflows.

## Project Context

This portfolio project draws on practical exposure to aluminium manufacturing and quality control. That experience informed the operational problems explored in the application, while Appsmith and Supabase were used to implement the software solution.

The project demonstrates an interest in ERP systems, manufacturing applications, inventory management, and business process automation.

## Intended Applications

The concepts demonstrated in this project are relevant to:

- ERP and application support
- Manufacturing information systems
- Inventory and warehouse management
- Junior ERP implementation and functional support
- Business systems analysis
- Database-backed internal business applications

## Project Status

Developed as a practical portfolio project to demonstrate manufacturing workflow understanding and business application development skills.
