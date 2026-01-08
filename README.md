# Numeo – QA Automation Engineering Challenge

Welcome 👋  
This challenge is designed to evaluate your **QA automation skills, engineering mindset, and communication ability**.

At Numeo, QA engineers are not “testers on the side” — they are **full owners of quality**, deeply involved in system design, CI/CD, and observability.

Please read this document carefully before starting.

---

## 🎯 Goal

Build a **robust QA automation setup** for a small demo system that includes:
- A **Node.js backend API**
- A **React frontend**
- Intentional edge cases and flaky behavior

We are interested in **how you think**, not just whether tests pass.

---

## 🧩 System Overview

This repository contains (or simulates):

- **Backend**
  - Node.js REST API
  - Authentication (login)
  - CRUD endpoints
- **Frontend**
  - React application
  - Consumes backend APIs
- **Behavior**
  - Async operations
  - Random delays / failures to simulate real-world flakiness

You should treat this system as a **production-like service**.

---

## 🛠️ Your Tasks

### 1. End-to-End (E2E) Automation

Using **Playwright or Puppeteer**:

- Automate critical user flows:
  - Login
  - Happy-path CRUD flow
  - Error scenarios (invalid input, failures, retries)
- Properly handle:
  - Async behavior
  - Waiting strategies (no hard sleeps)
  - Flaky conditions

---

### 2. API Test Suite

- Write automated tests for backend APIs
- Validate:
  - Authentication & authorization
  - Status codes
  - Response payloads
  - Edge cases & failure scenarios

---

### 3. CI Integration

- Configure tests to run automatically in CI
- Tests should:
  - Fail clearly
  - Provide actionable output
- Use GitHub Actions (or equivalent)

---

### 4. Observability Mindset

Quality doesn’t stop at “test passed”.

Add mechanisms to:
- Improve failure visibility
- Make debugging fast and obvious
- Reduce flaky tests

This can include:
- Structured logs
- Screenshots / traces on failure
- Clear test naming & grouping

---

### 5. Code Quality

We care about:
- Clean structure
- Reusability
- Readability
- Maintainability

This is an **engineering challenge**, not just a QA task.

---

## 📹 Video Walkthrough (Mandatory)

Record a **5–10 minute screen-recorded video** where you explain:

- Your overall test strategy
- Why you chose certain tools and patterns
- How you handled flakiness and async behavior
- How this setup would scale in a real production environment

⚠️ **Submissions without a video will not be reviewed.**

---

## 📦 Submission Requirements

Please send:

1. **GitHub repository link**
2. **Screen-recorded video**
3. (Optional) Notes or trade-offs you considered

📩 Send everything to:  
**fozil.numeo@gmail.com**

---

## 🧪 What We Evaluate

We are looking for:

- Strong automation fundamentals
- Engineering mindset (not “checkbox testing”)
- Ownership and attention to detail
- Reliability and stability of tests
- Communication and clarity of thought

We do **not** expect perfection — we expect **thoughtfulness**.

---

## ⏱️ Time Expectations

This challenge is intentionally open-ended.

We recommend spending **no more than 6–8 hours**.  
Focus on **quality over quantity**.

---

## 🚀 Final Notes

- Treat this as a **real production system**
- Make reasonable assumptions and document them
- If something is unclear, **decide and explain your choice**

We’re excited to see how you approach quality engineering.

Good luck — and have fun! 🙌
