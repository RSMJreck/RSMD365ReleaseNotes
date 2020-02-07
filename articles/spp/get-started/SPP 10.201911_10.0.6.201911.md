# Release Notes for 10.0.6.201911
## SPP 10.201911
### - Item substitution
- <div>This software extension to
the D365FO platform enables replacing items in sales orders based on predefined
settings.&nbsp;During sales order generation, the item substitution screen can be
executed in a similar fashion as how the reservation screen is triggered. When
the screen is launched, the sales order customer and the line item are used to
scan the previously defined relations and construct the list of potential
items. This list is then presented to the user for selection, once substitution
items are selected, and the substitution approved, the lines will be automatically copied into the sales order lines with the selected quantities
and dimensions. As part of this operation, delivery reminders for original items are automatically updated or cancel based on substitute item quantities.</div>
### - Enhancements
- <div>Sales prorate has been modified to use the ship date in the selection criteria. Additionally, delivered quantities have been excluded from demand values used to calculate differences. Multi-line transactions and order line cancellations were reviewed and improved.</div>
