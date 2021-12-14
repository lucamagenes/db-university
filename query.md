1. SELECT * FROM `students` WHERE YEAR(`date_of_birth`) = '1990'
2. SELECT * FROM `courses` WHERE `cfu` > '10'
3. SELECT * FROM `students` WHERE YEAR(`date_of_birth`) < '1991'
4. SELECT * FROM `courses` WHERE `year` = '1' AND `period` = 'I semestre'
5. SELECT * FROM `exams` WHERE `date` = '2020-06-20' AND `hour` BETWEEN '13:59%' AND '24%'
6. SELECT * FROM `degrees` WHERE `level` = 'magistrale'
7. SELECT COUNT(`id`) FROM `departments`
8. SELECT COUNT(`id`) FROM `teachers` WHERE `phone` IS NULL