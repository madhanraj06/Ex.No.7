# **Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.**

---

## **Aim**

To develop a prompt-based application using ChatGPT that organizes daily tasks efficiently. This experiment demonstrates how prompts evolve from simple commands to advanced, context-aware interactions, resulting in a personalized AI assistant capable of task management, scheduling, wellness support, and adaptive learning.

---

## **Apparatus Required**

- Python 3.x (optional)  
- ChatGPT Web Interface / OpenAI API  
- CLI or Python Script  
- VS Code / PyCharm  
- GitHub Repository  
- JSON / CSV memory files  
- Internet Connection  

---

## **Procedure**

### **1. Define Application Requirements**

The assistant should:

- Add, edit, delete, prioritize tasks  
- Provide smart scheduling & conflict detection  
- Give wellness tips and micro-break suggestions  
- Handle general queries (weather, summaries, reminders)  
- Learn and adapt using lightweight memory  

---

### **2. Prepare Prompts for Functional Modules**

#### **A. Task Manager Prompts**
- “Add ‘buy groceries’ to my tasks.”  
- “Remind me to submit the assignment at 8 PM.”  
- “Show all high-priority tasks today.”  
- “Delete the task ‘pay electricity bill’.”  
- “Reorder my tasks by urgency.”  

#### **B. Scheduler Prompts**
- “Add a meeting with the team at 9 AM on Wednesday.”  
- “Do I have free time between 2–4 PM today?”  
- “Reschedule yoga session to tomorrow morning.”  
- “Check for conflicts on Friday.”  

#### **C. Wellness Prompts**
- “Give me a quick breathing exercise.”  
- “Suggest a 2-minute recharge break.”  
- “Send me hydration reminders.”  
- “Motivate me to stay productive.”  

#### **D. General Query Prompts**
- “What’s the weather tomorrow at 7 AM?”  
- “Summarize my day in 4 bullet points.”  
- “Overview of my upcoming week?”  
- “Suggest productivity hacks.”  

---

### **3. Simulate User Interaction**

Example CLI-style flow:

User: Add a task to study for the exam at 8 PM.
Assistant: Task added to today’s schedule (8–9 PM). Priority: High.

yaml
Copy code

Conflict handling:

Assistant: You have an event at 7:30 PM. Shall I shift the study session?

yaml
Copy code

---

### **4. Feedback Loop & Adaptation**

The system collects user preferences such as:

- Avoid certain wellness categories  
- Preferred break type (walking / breathing)  
- Recurring event patterns  
- Task naming habits  

Example adaptive response:

Assistant: You prefer walking breaks. Want to take one now?

yaml
Copy code

Stored as JSON memory for future responses.

---

### **5. Optional Memory Integration**

Tracks:

- Frequently repeated tasks  
- Preferred timings  
- Common meeting days  
- Personal productivity habits  

Used to automate suggestions and improve assistant personalization.

---

## **Expected Output**

### **✔ Daily Task Manager**
- Task creation, deletion, editing  
- Prioritization  
- Daily & weekly summaries  
- Task categorization (Work/Personal/Urgent)  

### **✔ Smart Scheduler**
- Conflict detection  
- Optimal slot suggestions  
- Recurring event management  
- Text-based timeline view  

### **✔ Wellness Coach**
- Hydration notifications  
- Micro-break suggestions  
- Motivational lines  
- Optional habit tracking  

### **✔ General Query Handler**
- Weather forecasts  
- Day/Week summaries  
- Productivity improvement tips  
- Intelligent planning suggestions  

---
### **3. Simulate User Interaction**

Below is an example of how the prompt-based assistant behaves during a conversation:

| **User Prompt** | **Assistant Response** |
|-----------------|------------------------|
| Add a task to study for the exam at 8 PM. | ✔ Task added to today’s schedule (8–9 PM). Priority: High. |
| Show all high-priority tasks. | 📌 **High Priority Tasks:**<br>• Study for exam at 8 PM |
| Add a meeting with the project team at 7:30 PM. | 📅 Meeting added at 7:30 PM. |
| Add another event: revision session at 8 PM. | ⚠ **Conflict detected!** You already have an event at 7:30 PM that overlaps. Do you want to reschedule? |
| Yes, shift the revision session to 9 PM. | ✔ Event rescheduled to **9 PM**. |
| Give me a quick wellness tip. | 🚶 Take a 2-minute walk break to refresh your mind! |
| Summarize my tasks for today. | 📝 **Today’s Summary:**<br>• 7:30 PM – Project meeting<br>• 9:00 PM – Revision session |

---
## **Result**

The experiment produced a fully functional prompt-based personal assistant capable of:

- Managing tasks efficiently  
- Scheduling intelligently  
- Supporting wellness habits  
- Adapting via memory-based learning  
- Enhancing productivity through natural-language prompts  

Students learned the importance of structured prompts, modular design, and adaptive AI behavior in real-world personal productivity applications.

