# n8n Workflow – Append Google Sheet Row & Send Email on New Entry

+ Create a new workflow and save it in n8n
+ Add the trigger node **"On form submission"** to capture user responses
+ Connect the form submission node to **"Append row in sheet"** (Google Sheets)
+ Configure the Google Sheet:
  - Select Spreadsheet
  - Select Worksheet
  - Map form fields to sheet columns automatically
+ Test the sheet append using **Execute workflow**
+ Add a **Google Sheets Trigger** node (rowAdded) to monitor when a new row is added
+ Connect the Sheets Trigger to **"Send a message"** (Gmail)
+ Configure Gmail to send notification emails containing:
  - Form data
  - Timestamp
  - Any custom message
+ Test workflow again using **Execute workflow**
+ Once successful, activate the workflow for automatic operations

# Screenshot
<img width="1920" height="844" alt="4" src="https://github.com/user-attachments/assets/46f29a18-b3d1-4ec7-9f08-a211ba9b9872" />
