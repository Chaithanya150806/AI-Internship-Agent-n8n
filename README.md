# AI-Internship-Agent-n8n
# 🚀 AI Internship Analysis Agent

An AI-powered internship analysis and recommendation system built using **n8n**, **LLMs**, and **Gmail Automation**.

This workflow automatically analyzes internship opportunities, evaluates their relevance to a Computer Science student interested in AI, Python, C++, and Cybersecurity, generates a match score, identifies required skills, and delivers a detailed report via email.

---

## 📌 Project Overview

Finding relevant internships often requires manually reading job descriptions, comparing requirements with personal interests, and deciding whether to apply.

This project automates that process using AI.

The workflow:

1. Receives internship information.
2. Sends the information to an AI model.
3. Generates:
   - Internship summary
   - Match score
   - Required skills
   - Personalized recommendation
4. Formats the response.
5. Creates an email report automatically.

---

## 🏗 Workflow Architecture

```text
Manual Trigger
      │
      ▼
 Internship Data
      │
      ▼
    AI Agent
      │
      ▼
 Email Formatter
      │
      ▼
 Gmail Draft
```

---

## ⚙️ Technologies Used

| Technology | Purpose |
|------------|----------|
| n8n | Workflow Automation |
| OpenAI / LLM | Internship Analysis |
| JSON | Data Exchange |
| Gmail API | Email Automation |
| Prompt Engineering | AI Instructions |
| GitHub | Version Control |

---

## ✨ Features

### Internship Analysis

- Company identification
- Role extraction
- Location extraction
- Match score generation
- Skills identification
- Personalized recommendations

### AI-Powered Evaluation

The AI evaluates internships based on:

- AI relevance
- Python relevance
- C++ relevance
- Cybersecurity relevance
- Learning opportunities
- Career growth potential

### Email Automation

Automatically generates:

- Internship report
- Match analysis
- Required skills list
- Career recommendations

and delivers it through Gmail.

---

## 📊 Sample Input

```json
{
  "company": "NVIDIA",
  "role": "AI Research Intern",
  "location": "Hyderabad"
}
```

---

## 📈 Sample Output

```text
Company: NVIDIA

Role: AI Research Intern

Location: Hyderabad

Match Score: 88/100

Required Skills:
- Python
- C++
- Deep Learning
- CUDA
- Machine Learning

Recommendation:
Strongly recommended for students interested in AI and high-performance computing.
```

---

## 🎯 Learning Outcomes

Through this project, I learned:

### n8n Fundamentals

- Workflow Design
- Node Connections
- Data Flow Management

### Data Handling

- JSON Structures
- Dynamic Expressions
- Variable Mapping

### Artificial Intelligence

- AI Agents
- Prompt Engineering
- LLM Integration

### Automation

- Email Automation
- Gmail Integration
- Workflow Execution

---

## 🚀 Future Improvements

### Version 2

- Analyze multiple internships automatically
- Internship ranking system
- Consolidated email reports

### Version 3

- Real internship APIs
- Daily scheduled execution
- Automatic internship discovery

### Version 4

- Resume Matching Agent
- Resume Score Generation
- Resume Improvement Suggestions
- One-click Application Assistance

### Version 5

- Telegram Notifications
- WhatsApp Notifications
- Multi-Agent Architecture

---

## WorkFlow 

<img width="1911" height="903" alt="image" src="https://github.com/user-attachments/assets/bd20a596-64b4-4a8a-aed4-c0594d9d5faa" />

```

---

## 💼 Resume Description

Built an AI-powered Internship Analysis Agent using n8n, LLMs, and Gmail automation to evaluate internship opportunities, generate match scores, identify required skills, and automatically deliver personalized reports through email.

---


## ⭐ Project Status

Current Version: v1.0

Status: Functional MVP

Next Goal:
Transform the system into a fully automated internship discovery and recommendation platform.
