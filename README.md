# Qlik Application Repository 
# HR Data model (Аружан)(1)(1)
### 
Created By aiok03(No name specified in Profile) at Wed Aug 24 2022 18:45:12 GMT+0600 (Восточный Казахстан)




Sheet Title | Description
------------ | -------------
Calculate the number of managers who supervise 6 or more employees|Calculate the number of MANAGER_ID who supervise 6 or more EMPLOYEES.Please use the following fields and functions in set analysis: EMPLOYEE_ID,MANAGER_ID,count()
Show the list of employees whose name contains letter 'b'|Show the list of employees whose name contains letter 'b' (case insensitive/they will be displayed distributed by COUNTRY_NAME).Please use the following fields and functions in set analysis: EMPLOYEE_ID,FIRST_NAME,concat(),SubStringCount(),lower()
Calculate the number of employees whose salary is equal to the maximum salary for their job position|Calculate the number of employees whose SALARY is equal to the  MAX_SALARY for their job position. Please use the following fields and functions in set analysis: EMPLOYEE_ID,MAX_SALARY,SALARY,rangesum()
Calculate employees quantity with name 'David'|Calculate quantity of employees with FIRST_NAME 'David'. Please use the following fields in set analysis: EMPLOYEE_ID, FIRST_NAME
Calculate the number of employees who was hired on the first day of the month (any month)|Calculate the number of employees who was hired on the first day of the month (any month). Please use the following fields and functions in set analysis: EMPLOYEE_ID, HIRE_DATE, day()
Calculate the number of employees who do not belong to any depatment|Calculate the number of employees with no DEPARTMENT_ID. Please use the following fields in set analysis: EMPLOYEE_ID, DEPARTMENT_ID
Calculate quantity of employees from Marketing or Purchasing departments|Calculate quantity of employees with DEPARTMENT_ID 20 or DEPARTMENT_ID 30. Please use the following fields in set analysis: EMPLOYEE_ID, DEPARTMENT_ID
Calculate the number of employees whose phone number is in format X.X.X.X|Calculate the number of employees whose phone number is in format X.X.X.X Please use the following fields and functions in set analysis: EMPLOYEE_ID, PHONE_NUMBER, SubStringCount()
Calculate the number of employees whose salary is a multiple of 1000|Calculate the number of employees whose SALARY is a multiple of 1000. Please use the following fields and functions in set analysis: EMPLOYEE_ID,SALARY,mod()
Calculate the number of employees from Shipping or Sales department that have bonus|Calculate the number of employees that have not null COMMISSION_PCT and DEPARTMENT_ID=50 or DEPARTMENT_ID=80. Please use the following fields in set analysis: COMMISSION_PCT, DEPARTMENT_ID, EMPLOYEE_ID
Show name of departments with more than 30 employees|Show departments (DEPARTMENT_ID) with more than 30 employees (EMPLOYEE_ID). Please use the following fields and functions in set analysis: EMPLOYEE_ID,DEPARTMENT_ID,DEPARTMENT_NAME,count(),concat()
Calculate quantity of employees whose name is longer than 4 letters|Calculate the number of employees whose FIRST_NAME is longer than 4 letters. Please use the following fields and functions in set analysis: EMPLOYEE_ID,FIRST_NAME,len()
Calculate the number of departments that have 5 or more employees with the same job position|Calculate the number of DEPARTMENT_ID that have 5 or more EMPLOYEE_ID with the same JOB_ID.Please use the following fields and functions in set analysis: EMPLOYEE_ID,JOB_ID,count(),DEPARTMENT_ID
Calculate the number of employees who work as an IT specialist|Calculate quantity of employees with JOB_ID 'IT_PROG'. Please use the following fields in set analysis: EMPLOYEE_ID,JOB_ID
Calculate quantity of employees whose salary is between 8000 and 9000|Calculate the number of employees whose SALARY is in range of 8000 and 9000 (inclusive). Please use the following fields in set analysis: EMPLOYEE_ID, SALARY
Calculate the number of employees whose last letter in name is 'm' and the length of name is longer than 5 characters|Calculate the number of employees whose last letter in FIRST_NAME is 'm' and the length of FIRST_NAME is longer than 5 characters. Please use the following fields and functions in set analysis: EMPLOYEE_ID, FIRST_NAME, right(),len()
Calculate the number of employees with the longest names|Calculate the number of employees with the longest FIRST_NAME.Please use the following fields and functions in set analysis: EMPLOYEE_ID,FIRST_NAME,len(),max()
Calculate the number of employees not reporting to the manager|Calculate the number of employees not reporting to the manager (do not have MANAGER_ID).Please use the following fields in set analysis: EMPLOYEE_ID, MANAGER_ID
Calculate the number of employees whose phone number consists of 12 symbols and ends with number '8'|Calculate the number of employees whose PHONE_NUMBER consists of 12 symbols and ends with number '8'. Please use the following fields and functions in set analysis: EMPLOYEE_ID, PHONE_NUMBER, len(), right()
Calculate the number of employees from Shipping deparment with salary higher 4000$|Calculate the number of employees with DEPARTMENT_ID 50 and SALARY > 4000. Please use the following fields in set analysis: EMPLOYEE_ID,DEPARTMENT_ID,SALARY
Calculate the number of employees from Europe with salary higher 8000|Calculate the number of employees with REGION_NAME 'Europe' and SALARY > 8000. Please use the following fields in set analysis: EMPLOYEE_ID,SALARY,REGION_NAME
Calculate quantity of employees whose last letter of name is 'a'|Calculate the number of employees whose last letter of FIRST_NAME is 'a'. Please use the following fields and functions in set analysis: EMPLOYEE_ID, FIRST_NAME, right()
Find and show the salaries of employees hired in January and with the length of  job_title longer than 15 characters|Find and show the salaries of employees with the HIRE_DATE in January and with the length of  JOB_TITLE longer than 15 characters. Please use the following fields and functions in set analysis: EMPLOYEE_ID, JOB_TITLE, HIRE_DATE, SALARY, len(), sum(), month()
Calculate quantity of employees whose name contains at least 2 letters 'n'|Calculate the number of employees whose FIRST_NAME contains at least 2 letter 'n'. Please use the following fields and functions in set analysis: EMPLOYEE_ID,FIRST_NAME,SubStringCount()
Calculate the number of employees hired in 2008|Calculate the number of employees hired in 2008 (HIRE_DATE). Please use the following fields and functions in set analysis: EMPLOYEE_ID, HIRE_DATE, year()



Branch Name|Qlik application
---|---
main|[https://dev2.datanomix.pro/sense/app/317001e6-8912-45fa-89e2-de433b6f03a7](https://dev2.datanomix.pro/sense/app/317001e6-8912-45fa-89e2-de433b6f03a7)