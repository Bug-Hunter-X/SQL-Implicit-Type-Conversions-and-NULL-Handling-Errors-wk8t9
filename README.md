# SQL Implicit Type Conversion and NULL Handling Errors

This repository demonstrates common SQL errors related to implicit type conversions and the mishandling of NULL values.  These errors can be tricky to debug, as they might not always throw explicit errors but lead to incorrect query results.

The `bug.sql` file contains examples of queries with these issues. The `bugSolution.sql` file shows how to correct them.

**Key Concepts:**
* **Implicit Type Conversion:** SQL's automatic type conversion during comparisons can have unintended consequences.
* **NULL Values:**  `NULL` represents the absence of a value.  Use `IS NULL` and `IS NOT NULL` to check for them, not equality operators.