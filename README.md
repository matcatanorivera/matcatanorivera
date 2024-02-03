From [SQL tutorial].dbo.EmployeeSalary  
SELECT * 
FROM [SQL tutorial].dbo.Employeedemographics 
Inner Join [SQL tutorial].dbo.EmployeeSalary 
ON Employeedemographics.EmployeeID = EmployeeSalary.EmployeeID
