# I have used scalar subqueries, correlated subqueries, and subqueries with IN, EXISTS, and = operators.

A scalar subquery - It is a subquery that returns exactly one value (one row and one column).

A correlated subquery - It is a subquery that depends on a value from the outer query. It is executed once for each row in the outer query.

Used IN Subquery to Check if a value exists within a list of values returned by a subquery.

Used EXISTS Subquery to check whether the subquery returns any rows. It returns TRUE if at least one row is returned.

