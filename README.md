# mysql
mysql
CREATE TABLE EMPLOYEE
(EMP_NO NUMBER(4),
EMP_NAME VARCHAR2(50),
EMP_SAL NUMBER(9,2) ,
EMP_COMM NUMBER(7,2),
DEPT_N NUMBER(3));
CREATE TABLE SUPPLIER
(EMP_NO NUMBER(4),
EMP_NAME VARCHAR2(50),
EMP_SAL NUMBER (9,2));




-- insert some values
INSERT INTO EMPLOYEE VALUES (101,'SMIRTH'," " ,80000,120);
INSERT INTO EMPLOYEE  VALUES (102,'SNEHAL',160000,300,125);
INSERT INTO EMPLOYEE VALUES (103,'ADAMA',110000,0,120);
INSERT INTO EMPLOYEE VALUES (104,'AMAN'," ",300000,115); 
INSERT INTO EMPLOYEE VALUES (105,'ANITA',5000000,50000,110);
INSERT INTO EMPLOYEE VALUES (106,'SNEHA',2400000,24500,110);
INSERT INTO EMPLOYEE VALUES (107,'ANAMIKA'," " ,29075,130);
INSERT INTO SUPPLIER VALUES (108,'ANOJ',2000);
INSERT INTO SUPPLIER VALUES (109,'PRIYA',3000);
INSERT INTO SUPPLIER VALUES (110,'VAISH',4000);

-- fetch some values
--SELECT EMP_NAME FROM EMPLOYEE WHERE EMP_NAME LIKE 'A_a%';
--SELECT EMP_NO,EMP_NAME,EMP_SAL FROM EMPLOYEE WHERE EMP_NAME LIKE 'ma_';
--SELECT EMP_NO,EMP_NAME,EMP_SAL,EMP_COMM,DEPT_NO,HIRE_DATE FROM EMPLOYEE LIKE 'n_' AND EMP_COMM IS NOT NULL;
--SELECT EMP_NO,EMP_NAME,EMP_SAL,EMP_COMM,DEPT_N FROM EMPLOYEE WHERE EMP_NAME  LIKE '__r%' AND EMP_COMM IS NULL;
SELECT EMP_NO,EMP_NAME,EMP_SAL FROM EMPLOYEE;
