# cafeteria-menu-display
# 🍽 Cafeteria Menu Display Portal

A ServiceNow-based application designed to simplify the creation, approval, and publication of daily and weekly cafeteria menus across an organization.

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Modules Implemented](#modules-implemented)
- [How It Works](#how-it-works)
- [Demo Video](#demo-video)
- [Documentation](#documentation)
- [Team](#team)
- [Future Scope](#future-scope)

---

## 📖 About the Project

The Cafeteria Menu Display Portal provides a digital interface to manage cafeteria menus in an organization. Administrators can create, update, and publish menus with an approval workflow, while employees can conveniently view current and upcoming meals.

It helps streamline communication, reduce manual effort, and enhance overall cafeteria engagement.

---

## 🚀 Key Features

- Create and publish daily/weekly menus
- Approval workflow before publishing
- View upcoming meals and dietary details
- Maintain historical menu records
- Employee self-service access to menus
- Custom UI actions for admin workflows
- Reporting dashboard for menu analytics

---

## 🛠 Technology Stack

| Component        | Technology           |
|------------------|----------------------|
| Platform         | ServiceNow           |
| UI Development   | Service Portal       |
| Logic & Flow     | Workflows, UI Policies, UI Actions |
| Data Storage     | Custom Tables        |
| User Interface   | Catalog Items, Record Producer |
| Reporting        | Reports & Dashboards |

---

## 🧩 Modules Implemented

1. 🎯 Studio – Created scoped application and design workspace
2. 🗃 Table – Custom table to store menu records
3. 📝 Service Catalog – Menu submission via catalog form
4. 📊 Report – Meal tracking and reporting by week
5. 🔘 UI Action – “Publish” button for menu items
6. 🧪 Testing – Verified workflows, forms, and visibility

---

## ⚙ How It Works

1. Admin logs into the ServiceNow instance.
2. New menu entries are submitted through a catalog form.
3. A workflow routes menu for approval.
4. Upon approval, the menu is published to the portal.
5. Employees view the live menu and navigate by date or meal type.
6. Admins can track menu history via reports.

---

## 🎬 Demo Video

📺 Watch the live demo here: [Demo Video Link](https://drive.google.com/drive/folders/1-L70jXSwVGIi2_ZTYFlNJAB-n6xgi3mc)

---

## 📚 Documentation

📄 Project documentation with screenshots and technical steps:  
👉 [Download Project Documentation](https://drive.google.com/drive/folders/1m3dnsFuORw_NeDsl-Q7IjMBNFVtMm4zb)

---
## 🔮 Future Scope

- Integration with HR calendars and holidays
- Feedback and meal rating system
- Nutritional info with calorie tracker
- QR-code menu boards for display
- Mobile-friendly responsive UI
