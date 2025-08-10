Simple SQL Example: Creating and Querying a Students Table

This SQL script demonstrates the basic operations of:

Creating a table named Students

Inserting sample data into the table

Retrieving and displaying the data


Steps to Run

1. Create the table by running:

CREATE TABLE Students (
    ID INT,
    Name VARCHAR(50),
    Age INT
);


2. Insert data into the table using:

INSERT INTO Students (ID, Name, Age) VALUES
(1, 'Alice', 20),
(2, 'Bob', 22),
(3, 'Charlie', 19);


3. Query the table to see the data:

SELECT * FROM Students;



Expected Output

ID	Name	Age

1	Alice	20
2	Bob	22
3	Charlie	19
