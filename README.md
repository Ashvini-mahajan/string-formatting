# string-formatting
this repository  explains string formatting in python with simple clear example .it covers how to display text ,numbers ,tables in well structured format using different string formatting techniques.
row_line = "+----------+----------+----------+"

print(row_line)
print("| {:<8} | {:<8} | {:<8} |".format("ID", "Name", "Age"))
print(row_line)
print("| {:<8} | {:<8} | {:<8} |".format(1, "Alice", 22))
print(row_line)
print("| {:<8} | {:<8} | {:<8} |".format(2, "Bob", 25))
print(row_line)
print("| {:<8} | {:<8} | {:<8} |".format(3, "Charlie", 30))
print(row_line)

+----------+----------+----------+
| ID       | Name     | Age      |
+----------+----------+----------+
| 1        | Alice    | 22       |
+----------+----------+----------+
| 2        | Bob      | 25       |
+----------+----------+----------+
| 3        | Charlie  | 30       |
+----------+----------+----------+
