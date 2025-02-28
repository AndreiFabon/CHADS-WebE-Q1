# CHADS-WebE-Q1

## Path Discovery Challenge (Hackathon - Easy Level)

If you would like to solve it yourself, please follow the link: https://andreifabon.github.io/CHADS-WebE-Q1/

### Description
Welcome to **CHADS-WebE-Q1**, a beginner-friendly web security challenge. Your objective is to **discover the final path** that leads to the flag by analyzing the **source code, console logs, and stylesheets**. 

---

## Steps to Solve

### **Step 1: Solve the Riddle**
**Hint:** _"Look for one line, and there is one thing you change? and what do marbles have to do with anything?"_

- Open **Source Code** Solve the hint and how does the hint connect with the aother question, one whole riddle

---

### **Step 2: Inspect the Source Code for Hints**
**Hint:** _"Why would you log a bunch of random letters in a really weird order?"_

- Open **Developer Tools** (`Right Click > Inspect` or `Ctrl + Shift + I` in Chrome).  
- Go to the **Elements** tab and review the **HTML source code**.  
- Look for **commented hints** or suspicious logs in the code.

🔍 **Goal:** Find a **hashed log entry** hidden in the source code.

---

### **Step 3: Analyze Console Logs to Decode the Message**
**Hint:** _"Inspect > Console – Logs hold secrets."_

- Switch to the **Console** tab in Developer Tools.  
- You will see a **log entry that appears hashed or encoded**.
- Example: 4d79636f646520697320676f6f6420666f7220796f75

- Use an **online decoder** (e.g., Base64, Hex, ROT13) or manual conversion.

🔍 **Goal:** Decode the log entry to reveal a **clue or a partial path**.

---

### **Step 4: Inspect the Stylesheet for the Final Path**
**Hint:** _"Inspect > Styles – Hidden components reveal the way."_

- Navigate to **Sources > style.css** in Developer Tools.  
- Look for:
- Hidden paths inside `display: none;`
- Comments containing URLs or paths
- Obscured IDs or classes referencing hidden locations.

🔍 **Goal:** Find the **final path** that leads to the **flag**.

---

## Challenge Summary
✅ **Step 1:** Solve a Silly little riddle
✅ **Step 2:** Inspect **source code** (`Elements` tab) for hints.  
✅ **Step 3:** Decode the **console log** (`Console` tab).  
✅ **Step 4:** Analyze **style.css** (`Sources` tab) to find the **final path**.  

---

## Rules
- ❌ **No brute force or automated scanners.**
- ✅ **Use only DevTools and manual analysis.**
- 🎯 The **flag format is:** `CHADS{your_flag_here}`  

---

## Good Luck, Have Fun, and Stay CHAD. 🚀🔥