# ERPNext-iSuperaps-Integration
iSuperaps integration for ERPNext

iSuperaps is a free Advanced Planning and Scheduling software. This project was built to integrate iSuperaps with ERPNext

iSuperaps integration for ERPNext

1 Import data from ERPNext .

  1.1 Import basic data tables item, buffer, workstation, BOM, operation, and sales orders from ERPNext

  1.2 Sync the inv between ERPNext and iSuperaps,The real-time inventory quantity table for ERPNext is bin

  1.3 Sync the status of manufacturing orders / purchase orders / outsourcing orders between ERPNext and iSuperaps.

2 Export the manufacturing orders / purchase orders / outsourcing orders from iSuperaps to ERPNext.

(Integrate use intermediate database/Excel file as a data transfer intermediary, create all APS data/order tables and ERP purchase order/production order/subcontracting order tables in the intermediate database/Excel file, and  a orderno mapping table  between APS orders and ERP orders .)



