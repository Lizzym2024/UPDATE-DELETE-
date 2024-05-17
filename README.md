# UPDATE-DELETE-
DELETE STATEMENTS

INSERT TABLE employee(name,title,age,salary) VALUES("Kevin Krier",52,128000.00);
INSERT INTO employee (name, title, age, salary)VALUES ("Richard Cooper", "assistant principal",46, 88000.00);
INSERT INTO employee  (name, title, age, salary) VALUES ("Heather Erhardt", "teacher",34, 38000.00);

DELETE from employee where title = "principal";
DELETE from employee where name LIKE "J%”;
DELETE from employee where salary < 50000;
DELETE from employee;

UPDATE STATEMENTS

UPDATE employee SET title “Programmer” where name = “Mark Vukovic”;
UPDATE employee SET age “30” where age = “Jonie Weber”;
UPDATE employee SET salary “76020.20” where salary = “Dirk Smith”;
UPDATE employee SET name “Potsy Weber” where name = “Postie Weber”;
