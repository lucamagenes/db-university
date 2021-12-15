1. SELECT COUNT(id) as `students_number`, year(`enrolment_date`) FROM `students` GROUP BY `enrolment_date`
2. SELECT COUNT(*) as `teachers_number`, `office_address` FROM `teachers` GROUP BY `office_address`
3. SELECT avg(`vote`) as `average_vote`, `exam_id` FROM `exam_student` GROUP BY `exam_id`
4. SELECT COUNT(`id`) as `degrees_number`, `department_id` FROM `degrees` GROUP BY `department_id`