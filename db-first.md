| Name               | Type           | Attributes | Index       |
| ------------------ | -------------- | ---------- | ----------- |
| id                 | BIGINT         | NOT NULL   | PRIMARY KEY |
| card_registration  | BIGINT         | NOT NULL   | UNIQUE      |
| make               | VARCHAR(30)    | NOT NULL   | INDEX       |
| model              | VARCHAR(50)    | NOT NULL   |             |
| color              | VARCHAR(30)    | NULL       |             |
| mileage            | INT            | NOT NULL   | INDEX       |
| fuelType           | VARCHAR(20)    | NOT NULL   | INDEX       |
| price              | DECIMAL(10, 2) | NOT NULL   |             |
| yearOfRegistration | YEAR           | NOT NULL   |             |
| numberOfDoors      | INTEGER        | NULL       |             |
| available          | BOOL           | NOT NULL   | INDEX       |
| description        | TEXT           | NULL       |             |
| dateAdded          | DATETIME       | NOT NULL   |             |
