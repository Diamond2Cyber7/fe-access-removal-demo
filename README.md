# FE Access Removal Automation Demo

This project demonstrates a simplified version of an automation tool designed to remove Financial Edge NXT access from users and generate an audit-ready report.

---

## Problem

Managing system access at scale can be:
- Time-consuming
- Error-prone
- Difficult to audit

In real-world environments, removing access across hundreds of users requires:
- Manual navigation
- Repeated actions
- Verification of results

---

## Solution

This demo simulates an automation workflow built with Node.js that:

- Iterates through a list of users
- Determines if Financial Edge access exists
- Removes access (simulated)
- Generates a structured Excel report

---

## Features

- ✅ Automated user processing
- ✅ Conditional logic for access removal
- ✅ Excel report generation
- ✅ Color-coded results (green = success)
- ✅ Frozen headers for usability
- ✅ Clean, structured output

---

## Project Structure

├── demo.js
├── report-generator.js
├── sample-data.json
├── output/
└── README.md

---

## How to Run

1. Install dependencies:


npm install

2. Run the demo:


npm start

3. View the generated report:


./output/fe_demo_report.xlsx

---

## Example Output

| User Name  | Initial Status | Result |
|-----------|--------------|--------|
| Jane Doe  | Had FE Access | ✅ Success |
| John Smith | No FE Access | ⏭ Skipped |

---

## Notes

- This is a **demo version** with mock data
- No real user or system information is included
- Designed for demonstration and portfolio purposes only

---

## Real-World Impact

In a production scenario, this type of automation can:
- Reduce multi-day tasks to minutes
- Improve consistency and accuracy
- Provide audit-ready reporting
- Minimize operational risk

---

## Author

Built by Diamond Wilson  
Application Administrator | Automation Enthusiast
