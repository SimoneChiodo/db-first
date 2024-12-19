# Car table

| name            | type        | attributes                          | key     | note                    |
| --------------- | ----------- | ----------------------------------- | ------- | ----------------------- |
| id              | BIGINT(20)  | NOT NULL - AUTOINCREMENT - UNSIGNED | PRIMARY |                         |
| license_plate   | CHAR(7)     | NOT NULL - UNIQUE                   |         |                         |
| brand           | VARCHAR(50) |                                     |         |                         |
| model           | VARCHAR(50) |                                     |         |                         |
| production_year | DATE        |                                     |         |                         |
| conditions      | CHAR(1)     | NULL                                |         | "n" => new; "u" => used |
| price           | INT         | NULL - UNSIGNED                     |         |                         |
