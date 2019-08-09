# SQL

CREATE TABLE student (
    student_id INT,
    name VARCHAR(20),
    major VARCHAR(20),
    PRIMARY KEY(student_id)
);

CREATE TABLE student (
    student_id INT,
    Member VARCHAR(20),
    Amount INT(50),
    Description VARCHAR(30),
    Status VARCHAR(30),
    
    PRIMARY KEY(student_id)
);

INSERT INTO `student`(`student_id`, `Member`, `Amount`, `Description`, `Status`) VALUES (1, 'Linnea Nilsson', 8.00, 'MMA - drop in fees', '27/07/2019')




INSERT INTO `student`(`student_id`, `Member`, `Amount`, `Description`, `Status`) 
	VALUES 
    	(2, 'Madeline John', 8, 'MMA - drop in Fees', '27/07/2019, PAID'),
        (3, 'Sarah Purcell', 8, 'MMA - drop in Fees', '20/07/2019, PAID'),
        (4, 'Goncalo Mendonca', 8, 'MMA - drop in Fees', '20/07/2019, PAID'),
        (5, 'Shaun McDaid', 8, 'MMA - drop in Fees', '20/07/2019, PAID'),
        (6, 'Sarah Purcell', 8, 'MMA - drop in Fees', '15/07/2019, PAID'),
        (7, 'Goncalo Mendonca', 8, 'MMA - drop in Fees', '13/07/2019, PAID'),
        (8, 'Felipe De Carvalho', 16, 'MMA - drop in Fees', '20/07/2019, PAID'),
        (9, 'Peter Moore', 30, 'MMA - month membership Fees', '06/07/2019, PAID'),
        (10,'Paul Killeen', 8, 'MMA - drop in Fees', '06/07/2019, PAID'),
        (11, 'Sarah Purcell', 8, 'MMA - drop in Fees', '06/07/2019, PAID')
