# 🚀 n8n Automation Workflows Showcase

[![n8n](https://img.shields.io/badge/n8n-Automation-blue?style=flat-square)](https://n8n.io/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![CSV](https://img.shields.io/badge/CSV-Data-success?style=flat-square)](https://en.wikipedia.org/wiki/Comma-separated_values)
[![License](https://img.shields.io/github/license/MaheenGitHub/automation-demo-workflows?style=flat-square)](LICENSE)


Welcome to my **n8n Automation Workflows Showcase** — a curated collection of automation workflows demonstrating my skills in web scraping, workflow automation, data extraction, and productivity solutions.

> ⚠️ **Note:** This is a public demo version. Full workflows are private and available upon request.

---

## Current Workflows

### 1️⃣ Web Scraping: Link Extractor

This workflow automatically extracts **useful links from any webpage**, filters out social media links, JavaScript placeholders, and duplicate URLs, and exports a **clean CSV output**.

**Demo Screenshot:**
![Workflow Screenshot](web-scraping/workflow-screenshot.png)

**Sample Output CSV:**
[Download CSV](web-scraping/sample-output.csv)

**Partial Demo JSON:**

```json
{
  "nodes": [
    {
      "name": "Manual Trigger: Demo",
      "type": "n8n-nodes-base.manualTrigger"
    },
    {
      "name": "HTTP Request: Demo",
      "type": "n8n-nodes-base.httpRequest"
    }
  ]
}
```

**Skills Highlighted:** `n8n`, `JavaScript`, `HTTP Requests`, `Data Automation`

---
### 2️⃣ Website Monitoring: Lahore Board Update Monitor

This workflow automatically monitors the **BISE Lahore website** for new updates such as results, date sheets, or exam announcements.  
It performs **scheduled checks**, detects newly published links, and sends a notification when new updates appear.

**Demo Screenshot:**  
![Workflow Screenshot](LahoreBoard_Website_Monitor/workflow_screenshot.png)

**Sample Output CSV:**  
[Download Image](LahoreBoard_Website_Monitor/sample_output.png)

**Partial Demo JSON:**

```json

{
  "nodes": [
    {
      "name": "Schedule Trigger",
      "type": "n8n-nodes-base.scheduleTrigger"
    },
    {
      "name": "HTTP Request",
      "type": "n8n-nodes-base.httpRequest"
    },
    {
      "name": "Compare & Extract",
      "type": "n8n-nodes-base.code"
    },
    {
      "name": "Discord Bot",
      "type": "n8n-nodes-base.discord"
    }
  ]
}
```

**Skills Highlighted:** `n8n`, `JavaScript`, `Web Monitoring`, `Automation`, `Change Detection`

---

### 3️⃣ Future Workflows

* Lead generation from business directories
* Data cleaning & transformation pipelines
* Government portal automation

> Each new workflow will be added to this repo in the same structured format.

---

### ⚙️ How to Use

1. View **workflow screenshots** and **demo GIFs**.
2. Download **sample output** files to see output examples.
3. Request full workflow JSON files if needed for collaboration or demonstration.

---

### 💡 Key Takeaways

* Automates repetitive tasks to **save time & improve efficiency**
* Generates structured, usable outputs from raw data
* Demonstrates professional workflow design & automation expertise
* Portfolio-ready showcase for freelance clients and recruiters

---

### Contribution

Liked this Repo? **Star ⭐ it**. 



### Author
**Maheen Fatima**  
- [LinkedIn](https://www.linkedin.com/in/maheenfatimaa)
- [View my Upwork Profile](https://www.upwork.com/freelancers/~017a150168182cf524?mp_source=share)



### License

This project is licensed under the MIT License.

---


