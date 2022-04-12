---
title: "Car Renting System"
collection: projects
type: "Database system project"
permalink: /projects/car-renting-system
venue: "Github: (https://github.com/kennylui/car-renting-system/)"
date: 2022-04-13
location: "Hong Kong"
---

This is a car renting java application project using MySQL DBMS via JDBC API.
There are 5 data files in total, which are user categories, users, car categories, cars and renting records.
All of them are stored in txt file format.
For system fuctions,
there are 3 interfaces that the user can choose.
Administrator, User and Manager. Each operators can perform serveral operations.

First of all, the administrator can
- create table schemas in the database
- delete table schemas in the database
- load data into database from a dataset
- show number of records in each table

Next, the user can
- search for cars by 3 ways
1. by call number which is an exact matching
2. by car names which is a partial matching
3. by company which is also a partial matching
- user can show all renting record of a specific user

Finally, the manager can
- rent a car copy
- return a car
- list all unreturned car copies which are rented in a specific period
