# TX Internship

Project and documentation for student internship in TX Services 2022 "Travel Application".

### Brief description of travel application

Application will be used by employees to request and office managers (OM) to process daily allowance and travel expenses. 

#### Prepayment of daily allowances

Before business trip, employee creates request for daily allowances prepayment with exact dates of his/hers business trips. OM team checks if everything is ok 
(number of days i.e. calculated per diem). OM team add additional inputs, such as middle exchange rate, CC, correct amount per diem depending on the travel destination.
The completed form is converted to PDF format and uploaded to Docusign for representative’s signature. 
Signed form is sent to payroll provider for daily allowance's prepayment.

#### Travel expenses

When the business trip is done, expenses need to be claimed within 5 days after the business trip is finished, at the latest. Employee needs to fill out travel expense form
and attach receipts. OM team provides necessary inputs (middle exchange rate of the date when the border is crossed, checks if all the claims on the form are matching the attached receipts).
The completed form is converted to PDF format and sent for e-signatures both to employee and company's representative via docusign tool.
Once signed by both parties, the form is sent to our payroll provider for the final refund to the employee.

### Repositories

Type | Link til repo | Beskrivelse
--- |----------------------------------------------------------------------------| ---
Frontend | [React App](https://github.com/nenad-kosanovic-tam/tx-internship-fe)       | User interface for the application process for Travel Application
Backend | [Spring Boot App](https://github.com/nenad-kosanovic-tam/tx-internship-be) | Backend services providing API for Travel Application

Overview of the summary of the modules:

![Overview of the summary of the modules](https://github.com/nenad-kosanovic-tam/tx-internship/blob/master/Documentation/Travel%20application.png)

