# Flask utils example project

[![CircleCI](https://circleci.com/gh/Riffstation/flaskutilsexample.svg?style=svg)](https://circleci.com/gh/Riffstation/flaskutilsexample)


## Resources


### Genre

+----------------------+------------------+---------------------------+-----------------------+-----------+
| Field name           | Type             | Description               | Validations           | Read Only |
+======================+==================+===========================+=======================+===========+
| id                   | Integer          | Account identifier        | * Unique              | YES       |
|                      |                  |                           | * Required            |           |
+----------------------+------------------+---------------------------+-----------------------+-----------+
| name                 | character        |                           | * Required            | NO        |
|                      |                  |                           | * Unique for   genre  |           |
+----------------------+------------------+---------------------------+-----------------------+-----------+
| description          | character        |                           |                       | NO        |
|                      |                  |                           |                       |           |
+----------------------+------------------+---------------------------+-----------------------+-----------+



### Artist

+----------------------+------------------+---------------------------+-----------------------+-----------+
| Field name           | Type             | Description               | Validations           | Read Only |
+======================+==================+===========================+=======================+===========+
| id                   | Integer          | Account identifier        | * Unique              | YES       |
|                      |                  |                           | * Required            |           |
+----------------------+------------------+---------------------------+-----------------------+-----------+
| name                 | character        |                           | * Required            | NO        |
|                      |                  |                           | * Unique for artis    |           |
+----------------------+------------------+---------------------------+-----------------------+-----------+
| description          | character        |                           |                       | NO        |
|                      |                  |                           |                       |           |
+----------------------+------------------+---------------------------+-----------------------+-----------+



### Album

+----------------------+------------------+---------------------------+-----------------------+-----------+
| Field name           | Type             | Description               | Validations           | Read Only |
+======================+==================+===========================+=======================+===========+
| id                   | Integer          | Account identifier        | * Unique              | YES       |
|                      |                  |                           | * Required            |           |
+----------------------+------------------+---------------------------+-----------------------+-----------+
| name                 | character        |                           | * Required            | NO        |
|                      |                  |                           | * Unique for artist   |           |
+----------------------+------------------+---------------------------+-----------------------+-----------+
| description          | character        |                           |                       | NO        |
|                      |                  |                           |                       |           |
+----------------------+------------------+---------------------------+-----------------------+-----------+
| artist               | Artist           |                           |                       | NO        |
|                      |                  |                           |                       |           |
+----------------------+------------------+---------------------------+-----------------------+-----------+