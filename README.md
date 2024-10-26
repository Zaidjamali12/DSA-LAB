# DSA-LAB
CREATE TABLE St_info (
    St_no nchar(10) PRIMARY KEY,
    Adm_date DATE,
    St_name TEXT,
    St_age INT,
    St_address TEXT
);
CREATE TABLE Courses (
    C_no nchar(10) PRIMARY KEY,
    C_name TEXT,
    C_teacher TEXT,
    C_credit_hours INT
);
INSERT INTO St_info (St_no, Adm_date, St_name, St_age, St_address) VALUES
('23BSAI01', '2022-09-01', 'NAJAF ALI', 20, 'DAD0'),
('23BSAI67', '2022-09-01', 'HAIDER ALI', 19, 'SAKRAND'),
('23BSAI38', '2022-09-01', 'MUHAMMAD ZAID JAMALI', 19, 'NAWAB SHAH');
INSERT INTO Courses (C_no, C_name, C_teacher, C_credit_hours) VALUES
('PF', 'PROGRAMMING FUNDAMENTAL', 'MRS.MUHAMMAD OWAIS REHMANI', 3),
('CF', 'COMPUTER FUNDAMENTAL', 'SIR ZEESHAN RASOOL', 4),
('LA', 'LINEAR ALGEBRA', 'AJEEB- UR- REHAMAN', 3);

SELECT * FROM St_info;
SELECT * FROM Courses;

