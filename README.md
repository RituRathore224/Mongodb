# Mongodb
A MongoDB NoSQL assignment covering CRUD operations, aggregation, joins, array queries, and nested document analysis
The main goal of this assignment is to practice how MongoDB handles data in a flexible document-oriented format. Instead of using tables and rows like a relational database, this project uses collections of documents that store information about students, faculty members, courses, enrollments, and student activities. The assignment demonstrates how MongoDB can be used to manage both simple and complex data operations efficiently.

The project begins with the creation of a database in MongoDB Compass and the insertion of sample JSON documents. After setting up the database, several queries are written to solve different analytical and operational problems. These queries cover filtering, projection, aggregation, joins, updates, deletions, array operations, nested document conditions, and advanced grouping logic.

Data Collections Used
The assignment is organized around the following collections:

Students: Stores student details such as name, department, skills, attendance, and academic records.

Faculty: Contains information about faculty members and the courses they teach.

Courses: Stores course titles, IDs, and credits.

Enrollments: Links students to courses and stores marks.

Activities: Stores extra-curricular participation details such as seminar and hackathon records.

These collections are used together to simulate a realistic educational data system where information is distributed across multiple documents and collections.

Database Setup in MongoDB Compass
The first part of the assignment focuses on setting up the database in MongoDB Compass. The steps include:

Connecting MongoDB Compass to the local MongoDB server or Atlas URI.

Creating a new database named MONGODBPROJECT.

Creating the initial collection, such as Students.

Verifying that the database and collection were created successfully.

Inserting sample JSON documents into the collections.

This section helps build a clear understanding of how to start working with MongoDB from scratch.

Query and Analysis Tasks
The assignment includes a variety of MongoDB queries that gradually increase in difficulty.

1. Complex Filters and Projections
The first set of questions focuses on finding specific students based on conditions such as attendance percentage and skills. It also includes extracting only the required fields, such as student name and department. This helps practice filtering documents with multiple conditions.

2. Joins and Aggregations
The next section uses $lookup and $group to combine data from different collections. For example, one query shows each student’s enrolled courses, while another calculates the number of students enrolled in each course and the average marks. This section demonstrates how MongoDB can perform relational-style analysis even though it is a NoSQL database.

3. Grouping, Sorting, and Limiting
This part focuses on finding top-performing students and analyzing departments. It includes sorting by average marks, limiting results to the top 3 students, and counting how many students belong to each department. These queries are useful for ranking and summary reports.

4. Update, Upsert, and Delete Operations
The assignment also includes data modification tasks. These involve updating attendance for students who won hackathons, deleting old activity records, and using upsert to insert or update a course record depending on whether it already exists. This section shows how MongoDB supports full CRUD functionality.

5. Array and Operator Usage
Several questions focus on working with array fields, such as finding students who know Python but not C++. This section helps practice operators that work with multi-value fields and array-based conditions.

6. Subdocuments and Nested Conditions
The assignment also includes nested document queries, such as finding students who scored above a certain mark in a subject only if they belong to a specific department. This demonstrates how MongoDB can handle deeply structured data.

7. Advanced Aggregation Challenge
The final section is the most advanced and combines multiple collections and grouping levels. It asks for faculty-wise student lists along with average marks per student. This part shows how MongoDB aggregation pipelines can be used for detailed analytical reporting.

Key Learning Outcomes
By completing this assignment, the following MongoDB concepts are practiced and understood:

Creating databases and collections in MongoDB Compass.

Inserting and managing JSON documents.

Writing filter queries with multiple conditions.

Using projections to display selected fields only.

Performing joins with $lookup.

Using $group, $sort, and $limit for aggregation.

Updating, deleting, and upserting documents.

Working with arrays, subdocuments, and nested conditions.

Building advanced aggregation pipelines for analytical queries.

Conclusion
This MongoDB assignment provides a complete hands-on introduction to NoSQL database operations. It combines basic setup tasks with advanced querying techniques, making it useful for learning both the structure and the power of MongoDB. The project also demonstrates how to work with multiple related collections and apply aggregation pipelines to solve real data analysis problems in an educational environment.
