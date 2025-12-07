# n8n Workflow – Chat Message to AI Agent using Google Gemini Chat Model

+ Create a new workflow and save it in n8n
+ Add the trigger node **"When chat message received"** to capture user messages from a chat source
+ Connect the chat trigger to the **AI Agent** node
+ Add a **Google Gemini Chat Model** node below the AI Agent
+ Connect the Gemini Model to the AI Agent’s **Chat Model** input
+ Configure the Google Gemini Model with:
  - API Key / Credentials
  - Model type (Gemini 1.0, Gemini Pro, etc.)
  - Temperature, Max Tokens, and response settings
+ Configure the AI Agent:
  - System prompt / instructions
  - Input mapping: pass the chat message into the agent prompt
  - Optional memory and tools (leave empty if not needed)
+ Test the workflow using the **Execute workflow** button
+ Send a test chat message to see the AI Agent respond using the Gemini model
+ Once validated, activate the workflow to automate chat responses

# Screenshot
<img width="1722" height="566" alt="Screenshot 2025-11-21 115517" src="https://github.com/user-attachments/assets/0cc0ef61-80f8-49f0-beaa-be3a62f74e13" />
