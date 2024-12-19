# Car table

| name            | type        | attributes                          | key     | note                    |
| --------------- | ----------- | ----------------------------------- | ------- | ----------------------- |
| id              | BIGINT(20)  | NOT NULL - AUTOINCREMENT - UNSIGNED | PRIMARY |                         |
| license_plate   | CHAR(7)     | NOT NULL - UNIQUE                   |         |                         |
| brand           | VARCHAR(50) | NOT NULL                            |         |                         |
| model           | VARCHAR(50) | NOT NULL                            |         |                         |
| color           | VARCHAR(50) | NOT NULL                            |         |                         |
| fuel_type       | VARCHAR(30) | NOT NULL                            |         |                         |
| production_year | YEAR        | NOT NULL                            |         |                         |
| doors_number    | INT         | NOT NULL - UNSIGNED                 |         |                         |
| transmission    | VARCHAR(30) | NOT NULL                            |         |                         |
| conditions      | CHAR(1)     | NULL                                |         | "n" => new; "u" => used |
| mileage         | INT         | NULL - UNSIGNED                     |         |                         |
| price           | INT         | NULL - UNSIGNED                     |         |                         |
