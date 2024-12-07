# Banking System

## Overview
The Banking System project is designed as a robust, secure, and efficient SQL Server database solution that supports core banking operations. This project leverages industry-standard tools and technologies to manage financial transactions, customer data, and reporting needs for a banking environment.
<br><br>
The Banking System integrates features such as account management, transaction processing, reporting, and data transformation, all while adhering to best practices in database administration and security.

<br>

## Key Features
- Efficient Database Management: Built using SQL Server 2016, providing scalability, performance, and reliability.
- Custom T-SQL Procedures: Implementation of complex business logic using Transact-SQL (T-SQL).
- Data Integration: Automated data movement and transformation using SQL Server Integration Services (SSIS).
- Dynamic Reporting: Rich reporting features utilizing SQL Server Reporting Services (SSRS) for real-time insights.
- Automation and Maintenance: Administrative tasks automated using PowerShell scripts.

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

## Installation & Setup
### Prerequisites

- SQL Server 2016 installed on the server.
- Basic knowledge of T-SQL, SSIS, SSRS, and PowerShell scripting.
- Administrative permissions to execute scripts and manage the SQL Server instance.

### Steps
1. Clone or download the project repository.
2. Restore the provided .bak file for the initial database setup.
3. Execute the T-SQL scripts for schema creation, stored procedures, and data seeding.
4. Import SSIS packages for ETL processes using SQL Server Data Tools (SSDT).
5. Deploy SSRS reports via the Report Manager portal.
6. Schedule PowerShell scripts for automated tasks using Windows Task Scheduler.

<br>

## Directory Structure
```graphql
BankingSystem/
├── T-SQL_Scripts/
│   ├── Schema/
│   ├── Procedures/
│   ├── Triggers/
├── SSIS_Packages/
├── SSRS_Reports/
├── PowerShell_Scripts/
├── Documentation/
│   ├── UserGuide.pdf
│   ├── ArchitectureDiagram.png
```

<br>

## Contact
For issues, feature requests, or further information, please contact:

Project Maintainer: Chaanyah Laborde
Email: chaanyahlaborde@gmail.com
LinkedIn: [Chaanyah Laborde](https://www.linkedin.com/in/claborde/)
