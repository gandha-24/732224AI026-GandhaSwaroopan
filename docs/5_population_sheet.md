# n8n Workflow – Conditional Row Append to Different Google Sheets

+ Create a new workflow in n8n and save it
+ Add the trigger node **"When clicking 'Execute workflow'"** for manual testing
+ Add **Get row(s) in sheet** (Google Sheets - Read) to fetch data from the source sheet
+ Configure the sheet, worksheet, and row range to read the data you need
+ Add an **IF** node to check a specific condition from the sheet data
  - Example: If column value is "Yes" or number > 10 or status = "Approved"
+ Connect **Get row(s) in sheet → IF node**
+ Configure the IF condition based on your logic (string, number, boolean, value match, etc.)
+ Add **Append row in sheet** (Google Sheet 1) for the TRUE condition
+ Add **Append row in sheet1** (Google Sheet 2) for the FALSE condition
+ Connect:
  - IF → TRUE → Append row in sheet
  - IF → FALSE → Append row in sheet1
+ Map the required fields from the input data to each sheet's columns
+ Test the entire workflow with **Execute workflow**
+ Once validated, activate the workflow for automated conditional sheet routing

# Screenshot
<img width="1552" height="858" alt="5" src="https://github.com/user-attachments/assets/16cf1d68-a4ac-43c4-b8ff-c6ba96f959f6" />
