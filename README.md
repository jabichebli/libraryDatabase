# Library Database

Created by **Jason Abi Chebli**  
© 2025 Jason Abi Chebli. All rights reserved.

## Description
<div style="text-align: justify;">This project focused on designing a robust database system for the ReadMore Community Library (RCL), which provides library services to Local Government Agencies (LGAs). The database is structured to manage key information, including data related to LGAs, their branches, and the managers overseeing these branches. The design incorporated best practices in database development, starting with a detailed conceptual model, followed by data normalization, and culminating in a functional logical model and schema. The goal was to create an efficient, scalable database that supports RCL's operations while ensuring data integrity and usability.</div>

## Client Brief
[Brief Pt.1](https://github.com/jabichebli/libraryDatabase/blob/main/Brief%20pt.1.pdf)  

[Brief Pt.2](https://github.com/jabichebli/libraryDatabase/blob/main/Brief%20pt.2.pdf)

## Database Assumptions
[Assumptions](https://github.com/jabichebli/libraryDatabase/blob/main/rcl_assumptions.pdf)

## Database Conceptual Model
<div style="text-align: justify;">The conceptual model was the first step in the design process. I created an Entity Relationship Diagram (ERD) using crow's foot notation to visually represent the core entities involved in the ReadMore Community Library's operations. This model includes entities such as Local Government Agencies (LGAs), branches, and managers, and defines their relationships, attributes, and the cardinality of those relationships. The conceptual model serves as the foundation for the database design, ensuring clarity in understanding the library's operational structure before moving into detailed design stages. The ERD does not include surrogate keys, ensuring the focus remains on the logical structure of the data.</div>

[Conceptual Model](https://github.com/jabichebli/libraryDatabase/blob/main/rcl_conceptual.pdf)

## Database Normalisation
<div style="text-align: justify;">  To ensure the integrity and efficiency of the database, I performed data normalization, moving through the stages of <strong>UNF</strong>, <strong>1NF</strong>, <strong>2NF</strong>, and <strong>3NF</strong>. This process eliminated redundancy and ensured that each data attribute was appropriately linked to the correct entities. The normalization process was critical in creating a solid foundation for the subsequent design steps.  </div>

[Normalization](https://github.com/jabichebli/libraryDatabase/blob/main/rcl_normalisation.pdf)

## Logical Model
<div style="text-align: justify;"> After completing the conceptual model and normalization, I proceeded to design the logical model, which provides a more detailed representation of the data relationships and constraints. This model ensures that all relations are in <strong>3NF</strong>, defining candidate keys, ensuring data integrity, and aligning with business rules. The logical model forms the blueprint for the physical database. The logical model was developed in Oracle RDBMS, which allowed me to create the necessary code to define and implement the database. This includes tables, constraints, and relationships, ensuring that the database structure is efficient and scalable. </div>

[Logical Model](https://github.com/jabichebli/libraryDatabase/blob/main/rcl_logical.pdf)
[Oracle RDBMS Code](https://github.com/jabichebli/libraryDatabase/blob/main/rcl_model.zip)

## SQL Schema
<div style="text-align: justify;"> The SQL schema file contains the commands to create the database structure, including all tables and relationships based on the logical model. It has been thoroughly tested to ensure compatibility with Oracle SQL.</div>  

[Schema](https://github.com/jabichebli/libraryDatabase/blob/main/rcl_schema.sql)  

[Schema Output](https://github.com/jabichebli/libraryDatabase/blob/main/rcl_schema_output.txt)

## Feedback
If you have any feedback, suggestions, or questions about the database developed, feel free to [contact me](https://jabichebli.github.io/jabichebli/contact.html). Your input is valuable and will help improve my understanding of database design and development.
