# n8n Workflow – Form Submission → AI Agent → Gmail

+ Create a new workflow in n8n and save it
+ Add the trigger node **"On form submission"** to capture user inputs
+ Add the **AI Agent** node and connect it with the form submission node
+ Add a **Google Gemini Chat Model** and link it to the AI Agent as the Chat Model
+ Configure the AI Agent with:
  - System instructions
  - Input mapping from the form fields
+ Add the **Send Email (Gmail)** node
+ Connect AI Agent output to Gmail node to send the AI-generated message
+ Test the workflow by using **"Execute workflow"** button
+ After successful testing, activate the workflow
+ It will automatically send customized AI-generated responses to Gmail whenever a form is submitted

#screenshot:
<img width="1387" height="549" alt="Screenshot 2025-11-21 115554" src="https://github.com/user-attachments/assets/2e841e93-4001-47b0-9d4f-9ba238fee536" />
