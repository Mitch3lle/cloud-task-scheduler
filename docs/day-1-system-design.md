# Day 1 – System Design

## 📌 Goal
Define the structure and purpose of the Daily Productivity Tracker system before implementation.

---

## 🧠 Problem Statement
The system is designed to help students and employees reduce screen-time and improve productivity by tracking daily tasks and generating productivity scores.

---

## 🏗️ System Definition

**System Name:** Daily Productivity Tracker (API-Based Serverless)

**Trigger:**
- User submits tasks via API (morning)
- Scheduled evaluation at 8 PM

**Process:**
- Store user-submitted tasks
- At scheduled time, evaluate completion status
- Calculate productivity score

**Output:**
- Stored daily productivity record
- Cloud logs for execution tracking

---

## 🔄 High-Level Flow
User → API → Storage → Scheduled Lambda → Processing → Results

---

## 🧩 Key Design Decision
I chose a controlled complexity approach:
- One API for task submission
- One scheduled process for evaluation
- Simulated completion logic (initial version)

This keeps the focus on cloud architecture rather than frontend complexity.

---

## 📚 What I Learned
- How to translate an idea into a system design
- Importance of defining inputs, processes, and outputs
- Basics of event-driven architecture

---

## ⚠️ Notes / Challenges
- Initial idea included real user tracking, but complexity was reduced to ensure completion and focus on cloud fundamentals.
