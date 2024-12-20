# Banking System

## Overview
The Banking System project is designed as a robust, secure, and efficient SQL Server database solution that supports core banking operations. This project leverages industry-standard tools and technologies to manage financial transactions, customer data, and reporting needs for a banking environment.
<br><br>
The Banking System integrates features such as account management, transaction processing, reporting, and data transformation, all while adhering to best practices in database administration and security.

<br>

## Key Features
- <b>Efficient Database Management</b>: Built using SQL Server 2016, providing scalability, performance, and reliability.
- <b>Custom T-SQL Procedures</b>: Implementation of complex business logic using Transact-SQL (T-SQL).
- <b>Data Integration</b>: Automated data movement and transformation using SQL Server Integration Services (SSIS).
- <b>Dynamic Reporting</b>: Rich reporting features utilizing SQL Server Reporting Services (SSRS) for real-time insights.
- <b>Automation and Maintenance</b>: Administrative tasks automated using PowerShell scripts.

<br>

## Tools & Technologies
1. T-SQL
    - Core language for database querying and procedural logic.
    - Used for creating stored procedures, triggers, functions, and views to support the banking system's operations.
    - Ensures optimized query performance and secure data handling.

2. SQL Server 2016
    - Relational database engine chosen for its robustness, security, and performance.
    - Features utilized include:
        - High Availability (HA) and disaster recovery (DR) with Always On Availability Groups.
        - Transparent Data Encryption (TDE) to secure sensitive financial data.
        - Advanced indexing strategies to handle large volumes of transactional data efficiently.

3. SQL Server Integration Services (SSIS)
   - Automates ETL (Extract, Transform, Load) processes for seamless data integration.
   - Utilized for importing/exporting data across systems and maintaining data consistency.
   - Supports automated batch jobs for regular updates.
  
4. SQL Server Reporting Services (SSRS)
    - Provides detailed, real-time financial and operational reports.
    - Enables management to make informed decisions using interactive dashboards and parameterized reports.

5. PowerShell
    - Automates routine administrative tasks such as backups, user account management, and database performance monitoring.
    - Enhances productivity by scheduling and executing scripts for database health checks and maintenance.

<br>

## Usage
- Day-to-Day Operations:
  - Use the IMS dashboard to monitor inventory levels, restocking needs, and sales trends.
  - Schedule daily/weekly reports to keep stakeholders informed.

- Data Integration:
  - Automate data imports from external systems using pre-configured SSIS packages.

- Advanced Reporting:
  - Leverage SSRS to customize and drill down into specific inventory metrics.
 
<br>

## Directory Structure
```graphql
Banking_System\
├── T-SQL_Scripts\
│   ├── Schema\
│   ├── Procedures\
│   ├── Triggers\
├── SSIS_Packages\
├── SSRS_Reports\
├── PowerShell_Scripts\
├── Documentation\
│   ├── UserGuide.pdf
│   ├── ArchitectureDiagram.png
```

<br>

## Contact
For issues, feature requests, or further information, please contact:
<br><br>

Project Maintainer: Chaanyah Laborde <br>
Email: chaanyahlaborde@gmail.com <br>
LinkedIn: [Chaanyah Laborde](https://www.linkedin.com/in/claborde/)
