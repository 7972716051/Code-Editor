# Code-Editor
The goal of this project is to create an online Code Editor that allows users to write, edit, and execute code in real-time. The editor should support multiple programming languages and offer essential features for an enhanced user experience.

How It Works (Flow Summary)

Step 1: User opens the web app → sees the editor interface.
Step 2: Writes code → selects a language → clicks Run.
Step 3: Code is sent to backend (/run) → executed using the respective compiler/interpreter → output returned.
Step 4: User can Save the snippet locally → stored in snippets/ folder.
Step 5: Later, user can Load saved snippets or Delete them.

✅ Everything happens locally — no online database or server needed.

Technologies Used:
Component	Technology
Frontend	HTML, CSS, JavaScript
Editor	ACE Editor / CodeMirror
Backend	Node.js + Express.js
Code Execution	Node.js child_process
Local Storage	JSON files (snippets folder)

