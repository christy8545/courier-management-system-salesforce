# Salesforce Object Model

## Objects

- Customer__c
- Shipment__c
- Delivery_Agent__c
- Branch__c
- Delivery_Update__c
- Invoice__c

## Relationships

```text
Customer__c 1 ──── * Shipment__c
Delivery_Agent__c 1 ──── * Shipment__c
Branch__c 1 ──── * Delivery_Agent__c
Shipment__c 1 ──── * Delivery_Update__c
Shipment__c 1 ──── * Invoice__c
```

See the full project report for field-level definitions and configuration steps.
