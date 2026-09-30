# Auto Update Shipment Status

**Flow:** `Auto_Update_Shipment_Status`

**Type:** Record-Triggered Flow

**Trigger Object:** `Delivery_Update__c`

**Trigger:** When a delivery-update record is created.

## Logic

1. A new `Delivery_Update__c` record is created.
2. The Flow identifies the related `Shipment__c` through `Shipment__c`.
3. The Flow updates `Shipment__c.Status__c`.
4. The value is copied from `Delivery_Update__c.Status__c`.

```text
Delivery_Update__c created
          │
          ▼
Find related Shipment__c
          │
          ▼
Set Shipment.Status__c
          │
          ▼
Shipment status synchronized
```
