# PostgreSQL-database-queries

Please consider the following tables and schema for your queries.
## public.campaign:


student_id character varying(64)


source character varying(200)


campaign character varying(200)


## public.students:



id character varying(64)


country character varying(3)


section character varying(50)


classes_booked numeric(10,2)


classes_attended numeric(10,2)


1) Please write a query: How many students came through which source? Can you filter
for students who have come with big_savings?

2) A)Please write a query: That shows the difference between class attendance (pls use
the % based definition below) for ‘big_savings’ campaigns vs ‘i_love_langauges’
campaigns?
Class attendance= classes_attended/classes_booked (%)
