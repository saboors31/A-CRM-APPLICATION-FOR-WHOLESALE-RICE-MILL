# A-CRM-APPLICATION-FOR-WHOLESALE-RICE-MILL
The Rice Mill CRM Application streamlines wholesale rice mill operations using Salesforce's CRM capabilities. Key features include sales reports, rollup summary fields, cross-object formulas, IsBlank validation rules, and role-based access permissions. This fosters a productive, customer-centric environment, ensuring standards and business growth.


## Features and Functionality


- Reporting and Dashboards:

  - Generate detailed reports and analytics on daily rice production, sales, total income, and customer purchases.
  - View easily understandable data to assist owners in resource allocation and planning for future development.

- Rollup Summary Fields:

  - Summarizes data from child objects to parent objects in a master-detail relationship.
  - Examples: Display the total value of rice supplied from rice details on a related supplier using COUNT, SUM, MIN, and MAX functions.
 
- Cross-Object Formula Fields:

  - Reference fields from another object to calculate and display values.
  - Example: Calculate the total amount to be paid by multiplying the number of rice units by the price per kilogram.

- Validation Rules:

  - Ensure data integrity by applying validation rules, including error messages when invalid data is entered.
  - Example: An ISBLANK formula is used to validate fields, ensuring that mandatory fields are not left blank.

- Permission Sets and Roles:

  - Set up Organization-Wide Defaults (OWD) to restrict data access based on roles.
  - Roles include Owner, Employer, and Worker, with varying levels of access to records.
  - Example: The Owner can view all records, the Employer can view Worker records, and Workers have limited access.

 
## Getting Started


1. Clone the Repository:

   [Git Clone https://github.com/saboors31/A-CRM-APPLICATION-FOR-WHOLESALE-RICE-MILL](https://github.com/saboors31/A-CRM-APPLICATION-FOR-WHOLESALE-RICE-MILL)

   
2. Setup Salesforce Environment:
 - Log in to your Salesforce Developer account.
 - Create custom objects, fields, and relationships as per the application's data model.
 - Implement the rollup summary fields, cross-object formula fields, and validation rules.
 - Configure permission sets and roles according to the provided requirements.
3. Deploy and Test:
 - Deploy the application to your Salesforce environment.
 - Test the application features including reporting, dashboards, and data access controls.
