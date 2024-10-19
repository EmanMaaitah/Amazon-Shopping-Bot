# OBJECTIVE 
 Recognize about Data Table Extraction, get to know how to deal with selectors (target, ancher, strict, fuzzy) and options in Ui Explorer.

## MANUALLY
1) Go to the Amazon website
2) Looking for the products
3) Get the information.
   
# TECHNICAL REQUIREMENTS
## UI Automation Activities
1) [Input Dialog](https://docs.uipath.com/activities/other/latest/workflow/input-dialog)
2) [Use Application/Browser](https://docs.uipath.com/activities/other/latest/ui-automation%22/n-application-card)
3) [Type Into](https://docs.uipath.com/activities/other/latest/ui-automation%22/type-into)

# PROCEDURES
1) Insert the Input Dialog activity and select the input type (Text Box), save it in a string variable.
   ![image](https://github.com/user-attachments/assets/6841bdf0-7281-4940-b743-95b3efcab46a)

2) Use Application/Browser> Type Into> Keyboard Shortcuts
   
   ![image](https://github.com/user-attachments/assets/e5b80b21-5651-441e-95d1-e1bad2e975a9)

3) Extract Table Data > Output Data Table (To transfer the data from data table type to String) > Message Box

   ![image](https://github.com/user-attachments/assets/b98c3f74-547a-4aa9-af7d-f9d3b8087813)


5) Write Range Workbook (to fill the data table into Excel Sheet)

   
# Results

 To watch the robot run and the results, [click here](https://drive.google.com/file/d/18AATNTOcax-Nqxo-4vLV9djU5p9aIB8Z/view?usp=sharing)

# CONCLUSION
 * There is two types in studion(Modern design, Classic desgin)
 * The difference between get text and extraction data table that you can store data base in data table format.
 * The difference between Strict and Fuzzy selectors that the Strict search for the exact target, Fuzzy search for the matches targets whichhas a similler attributes
 * When you save adata in a csv format you can print it in a message box.
