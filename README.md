# MongoDB for Data Science at GEM Educa

This repository contains the class materials and practical exercises corresponding to the **MongoDB** module of the Data Science Diploma offered by **GEM Educa**.

**Content:**

* **Basic CRUD Operations:** Examples of the fundamental Create, Read, Update, and Delete (CRUD) operations in MongoDB are included. This covers database and collection creation, document insertion (single and multiple), data querying using various criteria and operators, modification of existing documents, and data deletion.
* **Advanced Queries:** The repository contains examples of more complex queries, including the use of comparison operators (`$gt`, `$lt`, `$in`, `$or`, etc.), regular expression operators for pattern searching in strings (`$regex`), array operators (`$size`, `$filter`), and the use of the `$where` expression for queries based on JavaScript functions.
* **Projections:** Techniques for selecting specific fields in documents during queries are demonstrated, optimizing data retrieval and focusing on relevant information.
* **Text and Numeric Functions:** The use of functions to manipulate data during querying is illustrated, such as converting to uppercase and lowercase (`$toUpper`, `$toLower`), extracting substrings (`$substr`), and rounding and truncating numbers (`$round`, `$trunc`).
* **Sorting and Limiting:** Examples of how to order query results (`.sort()`) and how to limit the number of returned documents (`.limit()`, `.skip()`).
* **Distinct Operations:** It shows how to obtain unique values from a specific field in a collection (`.distinct()`).
* **SQL to MongoDB Conversion:** An important section of the repository is dedicated to translating common SQL queries to their MongoDB equivalents. This facilitates the transition for those with experience in relational databases, covering basic selection, filtering, ordering operations, and the use of `WHERE` clauses and operators like `BETWEEN` and `IN`.
* **Multi-Table Queries (with `$lookup`):** Examples of how to perform "join" or combine operations between collections in MongoDB using the `$lookup` operator within the aggregation framework are presented.
* **Aggregation Framework:** Examples of using MongoDB's powerful aggregation framework for more complex data analysis are included. This covers stages such as `$project` (to reshape documents), `$lookup` (to combine collections), `$match` (to filter documents), `$sort` (to order), `$group` (to group and perform aggregate calculations), among others.
