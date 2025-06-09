| Name               | Type           | Attributes | Index       |
| ------------------ | -------------- | ---------- | ----------- |
| carRegistration    | INT            | NOT NULL   | PRIMARY KEY |
| make               | VARCHAR(30)    | NOT NULL   | INDEX       |
| model              | VARCHAR(50)    | NOT NULL   |             |
| color              | VARCHAR(30)    | NULL       |             |
| mileage            | INT            | NOT NULL   | INDEX       |
| fuelType           | VARCHAR(20)    | NOT NULL   |             |
| price              | DECIMAL(10, 2) | NOT NULL   |             |
| yearOfRegistration | YEAR           | NOT NULL   |             |
| numberOfDoors      | CHAR(5)        | NULL       |             |
| available          | BOOL           | NOT NULL   | INDEX       |
| description        | TEXT           | NULL       |             |
| dateAdded          | DATETIME       | NOT NULL   |             |
