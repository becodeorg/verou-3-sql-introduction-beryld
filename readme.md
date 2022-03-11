### Must Have

/*1*/

SELECT * FROM groups;

/*2*/

SELECT email, name as learner_name FROM learners WHERE ID='1';
SELECT name as learner_name, email from learners LIMIT 1;

/*3*/


UPDATE groups  SET start_date = date_add(start_date, INTERVAL 2 month) WHERE id='1';

/*4*/

alter table groups add status text;

/*5*/

DELETE FROM learners WHERE id='3' ; 

### Nice to have


### Doable