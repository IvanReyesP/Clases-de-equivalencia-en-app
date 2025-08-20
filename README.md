# 🚗 Vehicle Reservation App - QA Testing Project

## 📋 Project Description
In this project, I designed and executed **functional and UI test cases** for a **vehicle reservation web application**.  
To optimize test coverage, I applied the **Equivalence Partitioning technique**, identifying valid and invalid input ranges and creating test scenarios that validated the application’s logic.

---

## 🎯 Objectives
- Ensure the correct functionality of the **vehicle reservation workflow**.  
- Validate both **valid and invalid inputs** to check system robustness.  
- Evaluate the **user interface consistency and usability**.  
 

---

## 🛠️ Tools & Technologies
- ✅ **Test Design:** Equivalence Partitioning, Test Cases, Checklists   
- ✅ **Documentation:** Excel / Google Sheets  
- ✅ **Environment:** Web application (QA testing environment)  

---

## 🔍 Testing Approach
- Designed **equivalence classes** to optimize input validation tests.  
- Created **functional test cases** for reservation process, date selection, vehicle availability, and booking confirmation.  
- Designed **UI test cases** for layout, responsiveness, and error messages.  
- Executed both **positive and negative test scenarios**.  

---

## 📊 Sample Test Cases
| ID | Test Scenario | Input | Expected Result | Status |
|----|---------------|-------|-----------------|--------|
| TC-01 | Reservation with valid date | Start: 05/20/2025 – End: 05/25/2025 | Reservation confirmed | ✅ Passed |
| TC-02 | Reservation with invalid date range | Start: 05/25/2025 – End: 05/20/2025 | Error message displayed | ✅ Passed |
| TC-03 | Reservation with empty fields | Start: [Empty] – End: [Empty] | Validation error | ⚠️ Bug reported |

---

## 🐞 Findings
- Incorrect validation for some invalid date ranges.  
- UI alignment issues in reservation confirmation screen.  
- Missing error message for empty vehicle selection field.  

---

## 📌 Conclusion
This project allowed me to strengthen my **QA testing skills**, applying structured test design techniques like **Equivalence Partitioning**, ensuring **high coverage with fewer test cases**, and improving the reliability of the vehicle reservation app.  

---

