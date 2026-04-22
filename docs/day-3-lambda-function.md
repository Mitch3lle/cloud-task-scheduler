# Day 3 – AWS Lambda Function Implementation

## 📌 Objective
Create and deploy the first serverless compute function using AWS Lambda to process productivity tasks.

---

## ⚙️ Service Used
Amazon Web Services (AWS Lambda)

---

## 🧠 Function Overview
The Lambda function simulates task completion and calculates a productivity score based on randomly generated results.

---

## 💻 Core Logic
- Accepts a list of tasks via event input
- Simulates task completion status
- Calculates productivity score
- Returns structured JSON output

---

## 🧪 Test Input
{
  "tasks": [
    "Study AWS",
    "Complete assignment",
    "Avoid social media"
  ]
}

 📊 Output Example
-Task completion status (true/false)
-Total tasks processed
-Productivity score (%)
-Timestamped result

🧠 Key Learnings
-AWS Lambda execution model (stateless compute)
-Event-driven input handling
-Cloud logging via CloudWatch
-Structuring backend logic in serverless systems

⚠️ Challenges
-Understanding event input structure
-Debugging via CloudWatch logs instead of local terminal

🚀 Outcome
A working serverless function capable of processing input data and returning computed results.
