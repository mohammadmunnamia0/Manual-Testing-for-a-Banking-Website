# 🧪 Online Banking Website Testing Documentation

## 📄 Overview
This repository contains the testing documentation for the **Online Banking Website** project. The QA effort focuses on ensuring functional accuracy, usability, and cross-browser compatibility while maintaining a secure and user-friendly experience.

---

## 🧭 Project Information

| Field | Details |
|--------|----------|
| **Project Name** | Online Banking Website |
| **Author** | Md. Munna Mia |
| **Last Updated** | 07 October 2025 |
| **Testing Tools Used** | JIRA (for Bug Tracking) |
| **Automation Tools** | Not Used |
| **Test Environment** | Windows 8+, Office 2013+, MS Exchange, Chrome/Edge browsers |
| **Website Under Test** | [https://parabank.parasoft.com/](https://parabank.parasoft.com/) |

---

## 🎯 Objectives

The primary testing objectives are:
- Validate **functional** and **non-functional** requirements.  
- Identify and report defects, inconsistencies, and usability issues.  
- Ensure that all features meet client quality specifications.  
- Eliminate major bugs before go-live to ensure production stability.  

---

## 🧩 Scope of Testing

### Functional Testing
- Register a new user account.  
- Log in with valid credentials.  
- Validate account details, balance, and transaction history.  
- Test fund transfer and bill payment functionality.  
- Verify all hyperlinks and buttons are working as expected.  

### Usability Testing
- Evaluate overall UI clarity and intuitiveness.  
- Check if navigation is smooth and logical.  
- Confirm error messages are clear and helpful.  
- Test responsiveness across devices (desktop, tablet, mobile).  

### Cross-Browser Testing
- Test on **Chrome** and **Edge** browsers.  
- Verify consistent functionality and layout.  

---

## 🧱 Test Methodology

### Approach
The project follows the **Agile Methodology**, enabling iterative development, feedback collection, and continuous improvement of features based on test outcomes and user feedback.

### Test Levels
1. **Functional Testing** – Core operations validation.  
2. **Usability Testing** – UI/UX feedback and improvements.  
3. **Cross-Browser Testing** – Ensuring stable performance across browsers.

### Bug Triage
- Define resolution type for each bug.  
- Prioritize bugs and set resolution timelines.  
- Conduct follow-ups until all critical bugs are resolved.

### Test Completeness Criteria
- 100% test coverage achieved.  
- All manual and automated cases executed.  
- All open bugs resolved or scheduled for next release.  

---

## 📦 Test Deliverables
- ✅ Test Plan  
- ✅ Test Cases  
- ✅ Requirement Traceability Matrix  
- ✅ Bug Reports  
- ✅ Test Strategy  
- ✅ Test Metrics  
- ✅ Customer Sign-Off  

---

## 🧰 Test Environment

| Component | Description |
|------------|-------------|
| **OS** | Windows 8 and above |
| **Software** | MS Office 2013+, MS Exchange |
| **Browsers Tested** | Google Chrome, Microsoft Edge |
| **Tools** | JIRA for defect tracking |

---

## 🐞 Key Bug Summary

| Bug ID | Title | Status | Priority | Reported By | Description |
|--------|--------|---------|-----------|--------------|-------------|
| [JST1-6](https://tasnimsumona.atlassian.net/browse/JST1-6) | Wrong Input Is Accepted | In Progress | Medium | Md. Munna Mia | While registering an account, invalid data is being accepted. |

**Additional Findings:**
- Users can log in **without registration**.  
- Users can log in using **invalid email/data**.  
- No proper **authorization** validation.  
- **Wrong password** still allows access.  
- Missing or incomplete **error messages**.  
- UI needs improvement (layout, navigation bar, readability).  
- Cross-browser functionality confirmed consistent.  
- Account balance display accurate, but **duplicate accounts** cannot be tested due to restrictions.  

---

## 💡 Usability & Functional Feedback

- **Security Risks**: Major authentication flaws (invalid login, unauthorized access).  
- **Error Handling**: Insufficient validation messages.  
- **UI Issues**: Inconsistent font sizes, unoptimized navigation bar.  
- **Cross-Browser Test Result**: Functionality remains consistent across Chrome and Edge.  
- **Overall Conclusion**: Application requires **UI refinement and stronger input validation** to ensure user safety and data integrity.  

---

## 🧾 Test Case Reference
Each test case corresponds to a functional or usability test step mentioned in the Test Plan.  
They include:
- Input validation  
- Login authentication  
- Transaction verification  
- Cross-browser layout checks  
- Error handling validation  

*(Note: The actual test case sheet includes step-by-step test execution data.)*

---

## 📈 Conclusion

The Online Banking Website shows promise in functionality and data accuracy but currently suffers from:
- Weak security validation.
- Limited UI intuitiveness.
- Lack of informative feedback to users.

### **Recommendations:**
- Enforce strict validation during registration and login.  
- Improve UI for better user experience.  
- Add comprehensive error messages.  
- Enhance authorization mechanisms.  
- Perform additional regression testing after fixes.  

---


