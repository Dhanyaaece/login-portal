# Ledger — Modern Payroll & Attendance Portal

A modern, high-performance, single-page enterprise payroll and attendance management system with dynamic dark-mode styling, real-time calculations, day-wise attendance tracking, customizable overtime/shift rules, bulk updates, and instant CSV/PDF export.

![Ledger Preview](https://img.shields.io/badge/status-active-emerald?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)

---

## 🌟 Key Features

- 💼 **Comprehensive Payroll Management**: Automated real-time calculations for gross pay, net pay, PF, ESI, TDS, professional tax, allowances, and bonuses.
- 📅 **Day-wise Attendance & Shifts**:
  - Daily tracking matrix for full month days (1–31)
  - Status options: Present (P), Absent (A), Half Day (HD), Paid Leave (PL), Weekly Off (WO), Holiday (H)
  - Color-coded attendance chips with quick keyboard / click toggle
  - Overtime calculation with custom shift multiplier rates
- 🔍 **Dynamic Filtering & Search**:
  - Filter by Department (Engineering, Design, HR, Sales, Operations, Finance, etc.)
  - Filter by Employment Type (Full-time, Contract, Part-time, Intern)
  - Filter by Payment Status (Paid, Pending, Processing)
  - Instant live keyword search across employee name, email, role, and ID
- ⚡ **Bulk Actions**:
  - Bulk mark attendance (All Present, All Weekly Off, etc.)
  - Bulk approve payroll & mark as paid
  - Bulk export selected or all records to CSV and printable payslips
- 📊 **Executive Dashboard Metrics**:
  - Total Payroll Expense summary
  - Average Attendance Rate tracker
  - Department breakdown and distribution charts
  - Pending approval count and payout projections
- 🎨 **Modern Glassmorphism UI**:
  - Sleek dark theme with vibrant accents and micro-animations
  - Fully responsive across desktop, tablet, and mobile displays
  - Toast notifications and interactive modals

---

## 🚀 Getting Started

This application is built as a self-contained, high-performance web app with zero required build steps.

### Option 1: Direct File Launch
Simply open [`index.html`](file:///d:/ui-login%20portal/index.html) in any modern web browser:
```bash
# Windows
start index.html

# Mac
open index.html

# Linux
xdg-open index.html
```

### Option 2: Local HTTP Server
Run with any local dev server:
```bash
# Using Python
python -m http.server 3000

# Using Node.js (npx serve)
npx serve .
```
Then visit `http://localhost:3000` in your browser.

---

## 📁 Project Structure

```text
├── index.html        # Complete application (HTML structure, CSS design system & JavaScript logic)
├── .gitignore        # Git ignore rules for node_modules and IDE files
└── README.md         # Documentation & feature overview
```

---

## 🛠️ Technology Stack

- **Frontend**: HTML5, Vanilla CSS3 (Custom Glassmorphism Design System, CSS Variables, Flexbox/Grid)
- **Logic**: Modern Vanilla JavaScript (ES6+), LocalStorage state persistence
- **Typography & Icons**: Inter / Google Fonts, Lucide SVG Icons
- **Exporting**: Native CSV formatting & Browser Print Engine for payslips

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
