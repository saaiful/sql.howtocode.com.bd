# বেসিক এসকিউএল কমান্ড'স

## সিলেক্ট

** `SQL SELECT` সিনট্যাক্স **
```sql
SELECT column_name,column_name
FROM table_name;
```
এবং 
```sql
SELECT * FROM table_name;
```

## ইনসার্ট

** `SQL INSERT INTO` সিনট্যাক্স **

কলামের নাম ছাড়া
```sql
INSERT INTO table_name
VALUES (value1,value2,value3,...);
```
কলামের নাম সহ
```sql
INSERT INTO table_name (column1,column2,column3,...)
VALUES (value1,value2,value3,...);
```

## আপডেট

** `SQL UPDATE` সিনট্যাক্স **
```sql
UPDATE table_name
SET column1=value1,column2=value2,...
WHERE some_column=some_value;
```

## ডিলেট

** `SQL DELETE` সিনট্যাক্স **
```sql
DELETE FROM table_name
WHERE some_column=some_value;
```

## WHERE
**`SQL WHERE` সিনট্যাক্স **
```sql
SELECT field1, field2,...fieldN table_name1, table_name2...
[WHERE condition1 [AND [OR]] condition2.....
```

WHERE এর অপারেটর সমূহঃ

| অপারেটর | বর্ননা |
| -- | -- |
| = | সমান বোঝাতে |
| <> | সমান নয় বোঝাতে  |
| != | সমান নয় বোঝাতে  |
| > | বৃহত্তর  বোঝাতে |
|<| ক্ষুদ্রতর বোঝাতে  |
|>=|বৃহত্তর  অথবা সমান বোঝাতে |
|<=| ক্ষুদ্রতর অথবা সমান বোঝাতে  |
|BETWEEN| দুইয়ের মধ্যে আছে বোঝাতে  |
|LIKE| খোজা বোঝাতে |
|IN| একাধিক সম্ভাব্য মান আছে বোঝাতে |


উদাহরনঃ
```sql
SELECT * FROM Customers
WHERE Country='Bangladesh';
```
```sql
SELECT * FROM Customers
WHERE Id=1;
```

