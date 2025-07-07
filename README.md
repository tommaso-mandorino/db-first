# Database auto usate

(esercizio)

## Traccia

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## Risultato

Table: cars

id                | BIGINT         UNSIGNED NOT NULL UNIQUE AUTO_INCREMENT PRIMARY KEY

vin               | CHAR(17)                NOT NULL UNIQUE

license_plate     | CHAR(7)                 NOT NULL UNIQUE

brand             | VARCHAR(50)             NOT NULL

model             | VARCHAR(100)            NOT NULL

production_year   | YEAR                    NOT NULL

registration_date | DATE                    NOT NULL

engine            | VARCHAR(50)                 NULL

power             | SMALLINT       UNSIGNED     NULL

fuel              | VARCHAR(30)                 NULL

transmission      | VARCHAR(30)                 NULL

traction          | VARCHAR(30)                 NULL

color             | VARCHAR(30)                 NULL

body_type         | VARCHAR(30)                 NULL

mileage           | MEDIUMINT      UNSIGNED NOT NULL

price             | DECIMAL(10, 2) UNSIGNED NOT NULL

status            | VARCHAR(30)             NOT NULL

previous_owners   | TINYINT        UNSIGNED NOT NULL

insertion_date    | DATETIME                NOT NULL