
## Task 1: Find the data types and modes of the columns

![[Pasted image 20260907224545.png]]

![[Pasted image 20260907224628.png]]

## Task 2: Find the error in the query

![[Pasted image 20260907225319.png]]

![[Pasted image 20260907225452.png]]

## Task 3: Understand the array and STRUCT data types

![[Pasted image 20260907225944.png]]

![[Pasted image 20260907230122.png]]

## Task 4: Search the number of users had viewed a product

![[Pasted image 20260907231109.png]]

![[Pasted image 20260907231158.png]]

![[Pasted image 20260907231402.png]]

using unnest to unnest nested rows, in this case, a row repeated (array) mode of record/struct data elements type

![[Pasted image 20260907232406.png]]

Only tree rows with action view_element realted to the product Google Dino Game

![[Pasted image 20260907232918.png]]

Column geo is nullable mode

![[Pasted image 20260907233238.png]]

Items is REPEATED mode

![[Pasted image 20260907233313.png]]

- Both are RECORD type, but the difference is important in the MODE type
- REPEATED means that items can have nested rows in a single row of it's column
- To access to the column names of the RECORD in a REPEATED mode column, need to use the UNNEST function

