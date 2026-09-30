# Courier Management System (Salesforce)

A professional Salesforce-based Courier Management System for managing customers, shipments, delivery agents, branches, delivery updates, invoicing, automation, security, and reporting.

## Project Overview

This project implements a courier-management workflow on Salesforce using custom objects, relationships, validation rules, record-triggered automation, role-based access, reports, and dashboards.

## Core Modules

- Customer Management
- Shipment Management
- Delivery Agent Management
- Branch Management
- Delivery Tracking Updates
- Invoice Management
- Automated Shipment Status Updates
- Validation and Data Quality Controls
- Role/Profile-based Access
- Reports and Dashboards

## Data Model

The solution uses six custom objects:

- `Customer__c`
- `Shipment__c`
- `Delivery_Agent__c`
- `Branch__c`
- `Delivery_Update__c`
- `Invoice__c`

## Automation

`Auto_Update_Shipment_Status` is a record-triggered Flow designed to update shipment status based on delivery-update activity.

## Documentation

- [Project Documentation](docs/PROJECT_DOCUMENTATION.md)
- [Object Model](salesforce/metadata/OBJECT_MODEL.md)
- [Automation](salesforce/flows/AUTO_UPDATE_SHIPMENT_STATUS.md)

## Source

The original project documentation is preserved under `source/`.

## Technology

Salesforce CRM, Custom Objects, Relationships, Validation Rules, Record-Triggered Flow, Profiles/Roles, Reports, and Dashboards.

## Repository Structure

```text
.
├── docs/
├── salesforce/
│   ├── flows/
│   └── metadata/
├── source/
├── .gitignore
├── LICENSE
└── README.md
```

## Future Scope

Potential extensions include mobile tracking, GPS integration, SMS notifications, and AI-assisted delivery optimization.
