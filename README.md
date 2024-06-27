# ERPNext-iSuperaps-Integration
iSuperaps integration for ERPNext

iSuperaps is a free Advanced Planning and Scheduling software. This project was built to integrate iSuperaps with ERPNext

1 Export data from ERPNext to iSuperaps.

  1.1 ERPNext integration program exports basic data tables item, buffer, workstation, BOM, operation, and sales orders to APS

2 Generate the plan in iSuperaps.

3 Import the manufacturing orders / purchase orders / outsourcing orders from iSuperaps to ERPNext.

  3.1 APS work orders, purchase orders, and outsourcing orders must have ERPno and status fields in their tables

  3.2 ERPNext integration program will create a new Purchase Order/Work Order document based on the data in the corresponding APS table, and write back the ERPno and status fields


4 Sync the inv between ERPNext and iSuperaps.

  4.1 The real-time inventory quantity table for ERPNext is bin

5 Sync the status of manufacturing orders / purchase orders / outsourcing orders between ERPNext and iSuperaps.

  5.1 ERPNext integration program write back the status field of the APS corresponding table



