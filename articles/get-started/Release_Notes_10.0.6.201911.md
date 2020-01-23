---
# required metadata

title: What's new or changed in 10.0.6.201911 for RSM Accelerators
description: This topic describes features in 10.0.6.201911 for RSM Accelerators
author: RSM Product & Strategy
manager: Tawnya Propp
ms.date: 12/3/2019
ms.topic: article
ms.prod: 
ms.service: dynamics-ax-applications
ms.technology: 
ms.locale: en-us
ms.search.region: Global
ms.search.scope Operations
ms.dyn365.ops.version: AX 7.0.0
ms.search.validFrom: 2019-12-1
ms.search.industry: cross

---

# Release Notes for 10.0.6.201911
## CCM 10.0.201911
### - Tier Commission Pricing
- <div>A new commission documentation system is now made available for grower contracts. This approach allows for the use of tiers based on&nbsp; sales unit price in order to determine commission percent or fixed amounts. Depending on the price basis selected for the line (Commission or Fixed amount) a new user interface is enabled to structure commissions or fixed amounts based on sales line unit prices.<br></div>
### - Third-party adjustments
- <div>With this new enhancement is now possible to generate third party invoice journals before settlement operations are executed. Additionally, a new inquiry screen has been implemented to provide visibility on the state of third party payments and their state with regards to settlement operation executions.<br></div>
### - Inventory Management Screen
- <div>The Power BI report for inventory forecasting has been enhanced with an automatic refresh process that update the visualization in a periodic fashion. Additionally, the report has been enlarge in order to facilitate the analysis of data presented in the visualizations.</div>
### - Settlement Pool Workbench
- <div>The new settlement pool workbench is platform that leverages existing settlement pool definitions; the platform uses the criteria contained in pool definitions to retrieve and classify all receipts based on a date range and provide a consolidated and classified view. Each of the records presented contain receipts that comply with the criteria set in underlying pool definitions; actions can be taken to generate and post settlement pools from the settlement pool workbench. This platform automates what will otherwise be a manual process of settlement pool creation for each pool definition.</div>
### - Batch number generation
- <div>This modification enables the possibility to include receipt information into automatically created batch numbers. This facilitates relating batch numbers to CCM receipt numbers through the tracking number group 'reference no' property throughout the product life cycle in the system.</div>
### - Receive/Deliver now quantities are not exploding to component lines
- <div>The fields receive now and delivery now were modified to provide component quantities based on formulations. This modification applies to sales orders and purchase orders and provides quantities for component items based on formulations.</div>
### - Transfer journals for storage tank items
- <div>This feature will enable a tank to hold several batches when items are transferred into it. When the feature is enabled action can be taken on the original batches in the event updates to the butterfat concentration needs to take place.&nbsp;</div>
### - Reset batch order with explosion items not collapsing
- <div>During estimation formula items are retrieved and explosion items are broken out into components. The modification related to this feature remove such components when the status is reset.</div>
### - Skim inline explosion expansion
- <div>In the dairy industry, it is necessary to have explosion items show their components during transactions. The skim inline explosion expansion feature provides a functionality whereby such items show their components during purchase orders, sales orders, production orders and transfer journals.</div>
### - Changes
- <div>Improvements and countermeasures were added to harden the product, and minimize human error occurrences. The settlement page was updated to dynamically hide unneeded tabs according to settlement type selections; the settlement journal generated was reviewed by SMEs and modified to better document COGS variances. Average pricing implementation was simplified to use none (no average pricing of any sort) or item (using items as grouping entities in price average calculations). Countermeasures were created to avoid premium adjustments for third party vendors. Commission tax group in contracts was rendered unnecessary and removed. A warning system was created to avoid date mismatches between contracts and adjustments.</div>
## OCR 10.0.201911
### - Architecture improvements
- <div>Minor changes to the OCR integration allows for more streamlined code and process within Dynamics. OCR setup now references basic document types and allows for use of the built in SharePoint engine.</div>
## PSS 10.0.201911
### - Service import
- <div>The service import feature, can be used to import services directly from the ProShip service instead of requiring the ProShip xml configuration file from the ProShip installation. This simplifies the process for the ProShip service setup.<br></div>
### - Payload reviewing for sent/received ProShip XML
- <div>This functionality will enable users to obtain request and response XML files from communication exchanges between customers and the ProShip service. These instruments can be analyzed to derive reasons for unwanted behaviors or results.<br></div>
### - Return Service assignment
- <div>This new functionality can be used when a potential return is expected; in such case, after identifying and indicating what shipping service should be used for returns, after the shipping label and other documents are printed as usual, another call to the ProShip service is made and a new return label is printed that can then be used in the shipping process.</div>
## ITH 10.0.201911
### - Inventory hold enhancements
- <div>The inventory hold accelerator has been enhanced with the capability to place items with the desire degree of granularity (from warehouse to license plate) on hold. The existing inventory blocking is used to place such items on hold based on results of executed traces. An inquiry page has been implemented to provide visibility blocking state on items and dimensions so processed.</div>
## RTG 10.0.201911
## AFI 10.0.201911
### - Initial pullback
- <div>This accelerator will facilitate the extraction, auditing and automatic creation of payment invoices using standards of the banking industry. This platform uses metadata to help interpret flat and hierarchical text documents sent by banks and containing customer payment information. The records so interpreted will be presented in a workbench for auditing, manual update and eventual automatic generation of payment invoices to settle customer pending invoices. The use of metadata allow for the interpretation of different types of formats; currently Lockbox and ACH have been successfully tested.</div>
## TPM 10.0.201911
### - Field enhancements
- <div>The ability to inherit products and customers based on hierarchies has been implemented. This new feature can be used in active funds and trade allowance agreements to automatically reflect additions to customer and item hierarchies into customers and items grids for these documents.</div>
## SPP 10.201911
### - Item substitution
- <div>This software extension to the D365FO platform enables replacing items in sales orders based on predefined settings. During sales order generation, the item substitution screen can be executed in a similar fashion as how the reservation screen is triggered. When the screen is launched, the sales order customer and the line item are used to scan the previously defined relations and construct the list of potential items. This list is then presented to the user for selection, once substitution items are selected, and the substitution approved, the lines will be automatically copied into the sales order lines with the selected quantities and dimensions. As part of this operation, delivery reminders for original items are automatically updated or cancel based on substitute item quantities.</div>
### - Enhancements
- <div>Sales prorate has been modified to use the ship date in the selection criteria. Additionally, delivered quantities have been excluded from demand values used to calculate differences. Multi-line transactions and order line cancellations were reviewed and improved.</div>
