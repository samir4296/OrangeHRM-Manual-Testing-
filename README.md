# OrangeHRM Manual Testing Project

A complete manual testing project for the [OrangeHRM](https://opensource-demo.orangehrmlive.com) demo web application, covering core HR system modules using industry-standard QA practices.

---

## 📋 Project Overview

| Item | Details |
|------|---------|
| **Tester** | Mohammed Samir |
| **Date** | March 2026 |
| **Type** | Manual Black-Box Testing |
| **Environment** | Demo / Staging |
| **Browser** | Firefox on Mac |

---

## 🎯 Objectives

- Verify core modules function correctly as per requirements
- Identify and document bugs with clear reproduction steps
- Ensure proper validation messages for invalid inputs
- Validate edge case handling across the application
- Deliver a full test summary with pass/fail results

---

## 🗂️ Modules Tested

| Module | Features Covered |
|--------|-----------------|
| Login | Valid/invalid login, empty fields, forgot password |
| Dashboard | Page load, Quick Launch, navigation menu |
| Leave | Apply, validate, list, entitlement, cancel, approve |
| PIM (Employee) | Search, add, edit, delete employee |
| Admin | User management, add/edit/delete users |
| Recruitment | Vacancies, candidates |
| My Info | Personal details, contact details |
| Logout | Session termination |

---

## 🛠️ Testing Techniques

- **Equivalence Partitioning** — valid and invalid input groups
- **Boundary Value Analysis** — testing at the edge of input limits
- **Negative Testing** — invalid data, empty fields, wrong formats
- **Exploratory Testing** — unscripted testing to uncover unexpected bugs

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `TEST_PLAN_OrangeHRM.md` | Full test plan document |
| `OrangeHRM_Manual_Testing.xlsx` | Test cases, results, bug report & summary |

---

## 📊 Test Summary Results

| Metric | Count |
|--------|-------|
| Total Test Cases | 50 |
| ✅ Pass | 49 |
| ❌ Fail | 1 |
| 🚫 Blocked | 0 |
| 🐛 Bugs Found | 1 |
| **Pass Rate** | **98%** |

---

## 🐛 Bug Severity Scale

| Level | Description |
|-------|-------------|
| 🔴 Critical | Application crash or complete feature failure |
| 🟠 Major | Feature broken but workaround exists |
| 🟡 Minor | Small functional or UI issue |
| ⚪ Trivial | Cosmetic issue or suggestion |

---

## ⚠️ Out of Scope

- Performance testing
- Security / penetration testing
- Mobile responsiveness testing
- Database-level testing
- Third-party integrations
