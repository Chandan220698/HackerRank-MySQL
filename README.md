# HackerRank-MySQL

### 1. [Revising the Select Query I](https://www.hackerrank.com/challenges/revising-the-select-query/problem?isFullScreen=true)
> Query all columns for all American cities in the CITY table with populations larger than 100000. The CountryCode for America is USA.
  `SELECT * FROM CITY WHERE population > 100000 AND countrycode = 'USA';`
### 2. [Revising the Select Query II](https://www.hackerrank.com/challenges/revising-the-select-query-2/problem?isFullScreen=true)
> Query the NAME field for all American cities in the CITY table with populations larger than 120000. The CountryCode for America is USA.
> `SELECT name FROM CITY WHERE countrycode = 'USA' AND population > 120000;`
### 3. [Select All](https://www.hackerrank.com/challenges/select-all-sql/problem?isFullScreen=true)
> Query all columns (attributes) for every row in the CITY table.
> `SELECT * FROM City;`
### 4. [Select By ID](https://www.hackerrank.com/challenges/select-by-id/problem?isFullScreen=true)
> Query all columns for a city in CITY with the ID 1661.
> `SELECT * FROM City WHERE id = 1661;`
