# Automated Data Entry Form In Excel
##The workbook contains two worksheets. First worksheet(Dataform) is the data entry form and second one is the database which have data stored in a structured table. I have created the employee dataform which contains few fields in which drop down enabled using Data validation for Department, Radio button used in Location field , calculated field which is Net Pay and a submit button which records the input (this is achieved using macro). After formatting step over , i copied the labels of the form to another cell within the worksheet, and linked the input fields in the form to their corresponding labels then i created another worksheet(Database) to store the raw data from the dataform, I copied the labels from DataForm work sheet and pasted the transpose into the database worksheet and styled the table.
Now to automate the inputs to Database worksheet, I started recording Macro and inserted sheet rows into the table in Database worksheet and copied the first set of input data from worksheet one and paste a transpose of it in the first row of the table and again back to worksheet one and cleared all the Dataform field, then stopped recording the macro. I inserted a submit button and assigned the program(macro) to it, now with the click of the button the inputs from the DataForm are sent and stored in the Database worksheet. Lastly, I saved the workbook as macro-enabled workbook and added a layer of protection to the DataForm so changes cannot be made on the form except entering data.


##Result
![Worksheet1-DataentryForm](https://github.com/user-attachments/assets/22ce3ba9-4878-4a32-b0d4-92b4a4f64a22)
![Worksheet2-Database](https://github.com/user-attachments/assets/cddbb711-9058-40fb-8415-63da999f3b00)
![Employee_formprotected](https://github.com/user-attachments/assets/31a72dc0-e8bc-4989-a724-75c53bb393f4)


