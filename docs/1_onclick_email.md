
# 🚀 n8n Workflow – Send Gmail Message on Manual Trigger

## 📌 Problem Statement  
The objective of this workflow is to automatically **send an email through Gmail** whenever the user manually executes the workflow in n8n.  
This project demonstrates the basics of automating tasks using triggers and Gmail integration inside n8n.

---

## 🛠️ Step-by-Step Process  

### **1. Create a New Workflow**
- Log in to your n8n Cloud / Self-Hosted instance.
- Click **“New Workflow”** from the dashboard.

---

### **2. Add Manual Trigger**
- Drag and drop the **Manual Trigger** node.
- This node helps you test the workflow by manually executing it using the "Execute Workflow" button.

---

### **3. Add Gmail Node**
- Click the **+** button and add a **Gmail → Send Email** node.
- Connect the Manual Trigger node to Gmail.
- Configure the Gmail node:
  - **Authentication:** Connect your Gmail account via OAuth
  - **To:** Receiver email address
  - **Subject:** Custom subject text
  - **Message:** Email body text

---

### **4. Execute the Workflow**
- Click **“Execute Workflow”**.
- The workflow sends an email using Gmail.
- You can check the logs panel for success status.

---

## 🖼️ Implementation Screenshot

<img width="1920" height="1020" alt="Screenshot 2025-11-23 111957" src="https://github.com/user-attachments/assets/e611885b-9542-4e11-a4d1-761ae5b9d404" />

---

## 📤 Output Screenshot  
- The email should appear in the recipient's inbox.
- n8n logs will show each executed node and confirm success.

> *(You can add your output screenshot here later.)*

---

## 📘 Summary / Learning Outcome  

By completing this workflow, you’ve learned:

### ✔️ Concepts Learned
- How to build workflows in n8n  
- How to use the Manual Trigger node  
- How to configure and connect Gmail API  
- How to execute and test automations  

### 🎯 Skills Gained
- Automation design  
- API integration basics  
- Workflow debugging using n8n logs  

---

If you want, I can also:
- Add a **project architecture diagram**
- Add **GitHub badges**
- Format this as a **professional report**
- Write your **LinkedIn post** for this project

Just tell me! 🚀
