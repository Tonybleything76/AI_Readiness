---
name: "🐞 QA Bug Report"
about: Report a bug found during internal QA testing
title: "[QA BUG] <short summary>"
labels: ["qa", "bug"]
assignees: ""
---

## 🐞 Bug Description
<!-- A clear and concise description of the bug -->
Example: "Assessment form crashes when selecting Likert scale value on Question 5"

---

## ✅ Steps to Reproduce
1. Go to `/assessment`
2. Select Org: "Demo Org A"
3. Answer first 5 questions
4. See error when clicking "Next"

---

## 📷 Screenshots / Logs
<!-- Add screenshots, screen recordings, or console/log snippets -->
- Screenshot:
- Console Log:
- Server Log (if relevant):

---

## 🎯 Expected Behavior
<!-- What should have happened? -->
Example: "Page should advance to Question 6 smoothly without errors."

---

## 💻 Environment
- Browser: [e.g. Chrome 116]
- Device: [e.g. MacBook Pro, Windows 10]
- Environment: Development (MemStorage) / Staging (Postgres)
- Test Account: SuperAdmin / Editor

---

## 📋 Severity
- [ ] 🚨 Blocker – Cannot continue core workflow
- [ ] ⚠️ Major – Breaks a key feature
- [ ] 🛠️ Minor – Annoying but doesn’t block usage
- [ ] 💅 Cosmetic – UI/UX issue only

---

## 🔁 Reproducibility
- [ ] Always
- [ ] Sometimes
- [ ] Rarely

---

## 📌 Additional Notes
<!-- Add any extra context here -->
