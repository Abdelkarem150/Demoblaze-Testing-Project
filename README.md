# 🧪 Demoblaze Testing Project

A complete **Manual Testing Portfolio Project** for [Demoblaze](https://www.demoblaze.com) — a demo e-commerce website.  
This project covers the full manual testing lifecycle: test planning, test case design, test execution, and bug reporting.

---

## 📋 Project Overview

| Item | Details |
|---|---|
| **Website Under Test** | [demoblaze.com](https://www.demoblaze.com) |
| **Testing Type** | Manual Testing |
| **Tool** | Jira, Excel |
| **Total User Stories** | 20 |
| **Total Test Cases** | 52 |
| **Total Bugs Found** | 9 |
| **Sprints** | 4 |

---

## 📁 Project Structure

```
Demoblaze-Testing-Project/
│
├── Demoblaze_All_Test_Cases_Updated.xlsx   # 52 Test Cases with Actual Results & Status
├── Demoblaze_Bug_Reports.xlsx              # 9 Bug Reports with full details
│
└── Bug-Screenshots/                        # Evidence screenshots for each bug
    ├── BUG-001 — Broken image icon
    ├── BUG-002 — Previous button on page 1
    ├── BUG-003 — Undefined product URL
    ├── BUG-004 — Guest cart (x2 screenshots)
    ├── BUG-005 — Credit card accepts letters
    ├── BUG-006 — Credit card 38 digits
    ├── BUG-007 — Expired year accepted
    ├── BUG-008 — Name field accepts numbers
    └── BUG-009 — Contact form empty submit
```

---

## 🗂️ Sprints Breakdown

| Sprint | User Stories | Focus Area |
|---|---|---|
| Sprint 1 | US-01 → US-05 | Authentication & Home Page |
| Sprint 2 | US-06 → US-10 | Navigation, Product Details & Cart |
| Sprint 3 | US-11 → US-15 | Checkout, Validation & Static Pages |
| Sprint 4 | US-16 → US-20 | Session, Security & Responsiveness |

---

## 🐛 Bug Summary

| Bug ID | TC ID | Title | Severity |
|---|---|---|---|
| BUG-001 | TC-014 | Broken image icon shown instead of placeholder | Minor |
| BUG-002 | TC-020 | Previous button works on first page | Medium |
| BUG-003 | TC-023 | Invalid URL shows "undefined" data | High |
| BUG-004 | TC-026 | Guest can add to cart without authentication | High |
| BUG-005 | TC-034 | Credit card field accepts letters | High |
| BUG-006 | TC-035 | Credit card accepts more than 16 digits | High |
| BUG-007 | TC-036 | Expired card year accepted without validation | High |
| BUG-008 | TC-037 | Name field accepts numeric-only input | Medium |
| BUG-009 | TC-042 | Contact form submits with all fields empty | Medium |

### 🔍 Key Observation
A recurring pattern of **zero input validation** was identified across multiple forms (Checkout, Contact, Cart) — indicating a systemic validation issue rather than isolated bugs.

---

## ✅ Test Execution Summary

| Status | Count |
|---|---|
| ✅ Pass | 39 |
| ❌ Fail | 13 |
| **Total** | **52** |

---

## 🛠️ Tools Used

- **Jira** — Project management, Sprint planning, Bug tracking
- **Excel** — Test case documentation
- **Chrome DevTools** — Bug investigation and simulation
- **GitHub** — Version control and portfolio hosting

---

## 👤 Author

**Abdelkarem Fathi**  
Junior QA Tester  
🔗 [GitHub Profile](https://github.com/Abdelkarem150)
