# n8n Workflow – When Chat Message Received → AI Agent

+ Create a new workflow in n8n and save it
+ Add the trigger node **"When clicking 'Execute workflow'"** for testing the workflow manually
+ Add the node **"When chat message received"** to capture incoming chat messages
+ Connect the Execute trigger to the Chat Message node for workflow start
+ Add the **AI Agent** node and connect it to the Chat Message node
+ Configure the AI Agent with:
  - Chat Model (example: Gemini, OpenAI, local model, etc.)
  - Memory settings (optional)
  - Tools / Functions if needed
+ Map the chat message input to the AI Agent’s prompt field
+ Add any additional nodes (Send Email, Webhook reply, Notification, etc.) after the AI Agent if needed
+ Test the workflow using **Execute workflow**
+ Activate the workflow once everything responds correctly

#screenshot:
<img width="1688" height="689" alt="2" src="https://github.com/user-attachments/assets/2f0a659c-cd7b-4fc5-b6be-7b8160d2c2e1" />
