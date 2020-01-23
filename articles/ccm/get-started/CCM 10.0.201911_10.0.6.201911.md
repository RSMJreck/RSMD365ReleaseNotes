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
### - Bugs
- <div>Improvements and countermeasures were added to harden the product, and minimize human error occurrences.The settlement&nbsp; page was updated to dynamically hide unneeded tabs according to settlement type selections; the settlement journal generated was reviewed by SMEs and modified to better document COGS variances. Average pricing implementation was simplified to use none (no average pricing of any sort) or item (using items as grouping entities in price average calculations).Countermeasures were created to avoid premium adjustments for third party vendors. Commission tax group in contracts was rendered unnecessary and removed. A warning system was created to avoid date mismatches between contracts and adjustments.</div>
