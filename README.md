<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1E2E52,100:E8600A&height=210&section=header&text=School%20Office%20Admin&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=React%20%C2%B7%20TypeScript%20%C2%B7%20Recharts%20admin%20panel&descSize=18&descAlignY=58&animation=fadeIn" alt="School Office Admin banner" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-18.2-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Recharts-3.x-E8600A?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Create%20React%20App-react--scripts%205-09D3AC?style=for-the-badge&logo=createreactapp&logoColor=white" />
  <a href="https://www.schooloffice.tech"><img src="https://img.shields.io/badge/Product-School%20Office-1E2E52?style=for-the-badge" /></a>
</p>

## 🏫 About

This is the **admin panel (frontend)** of **[School Office](https://www.schooloffice.tech)**, a school management ERP for K-12 schools. It is a single-page app built with **React and TypeScript**, with charts powered by **Recharts**. School staff use it to manage school data, and it talks to the **[SCHOOL-ERP-backend](https://github.com/Muniramm890/SCHOOL-ERP-backend)** REST API.

## 🧱 How it fits together

```mermaid
flowchart LR
    U["👩‍🏫 School staff<br/>principal · accountant · teacher"] --> A

    subgraph A["🖥️ schoolOfficeAdminFront"]
        direction TB
        R["⚛️ React 18 + TypeScript"]
        C["📊 Recharts<br/>charts and analytics"]
    end

    A -->|HTTPS / JSON| B["⚙️ SCHOOL-ERP-backend<br/>Node.js + Express"]
    B --> D[("🗄️ Azure SQL")]
```

## 🧰 Tech stack

| Layer | Technology | Used for |
| :-- | :-- | :-- |
| UI | React 18.2 | Component-based interface |
| Language | TypeScript | Type-safe code |
| Charts | Recharts 3 | Charts and analytics views |
| Tooling | Create React App (`react-scripts` 5) | Dev server, build and tests |
| Backend | [SCHOOL-ERP-backend](https://github.com/Muniramm890/SCHOOL-ERP-backend) | REST API and database access |

## 📁 Project structure

```text
schoolOfficeAdminFront/
├── public/            # Static files and the HTML template
├── src/
│   ├── index.tsx      # Application entry point
│   ├── App.tsx        # Main application component
│   └── …              # Remaining application source
├── package.json       # Scripts and dependencies
├── tsconfig.json      # TypeScript configuration
└── README.md
```

## 🚀 Getting started

**Requirements:** Node.js (18 or newer recommended) and npm.

```bash
# 1. Clone
git clone https://github.com/Muniramm890/schoolOfficeAdminFront.git
cd schoolOfficeAdminFront

# 2. Install dependencies
npm install

# 3. Start the development server (http://localhost:3000)
npm start
```

The admin panel needs the backend running, so start **[SCHOOL-ERP-backend](https://github.com/Muniramm890/SCHOOL-ERP-backend)** first and make sure the panel points to its API address.

| Script | What it does |
| :-- | :-- |
| `npm start` | Runs the app in development mode on port 3000 |
| `npm run build` | Creates an optimised production build in `build/` |
| `npm test` | Runs the test runner |
| `npm run eject` | Ejects from Create React App (one-way) |

<!--
## 📸 Screenshots
Add screenshots to a docs/screenshots folder and show them here:

| Dashboard | Students |
| :-: | :-: |
| ![Dashboard](docs/screenshots/dashboard.png) | ![Students](docs/screenshots/students.png) |
-->

## 🔗 Related repositories

| Repository | Purpose |
| :-- | :-- |
| [SCHOOL-ERP-backend](https://github.com/Muniramm890/SCHOOL-ERP-backend) | Node.js backend and REST API |
| [SchoolOffice](https://github.com/Muniramm890/SchoolOffice) | Product website |

## 📬 Contact

- 🌐 Website: [schooloffice.tech](https://www.schooloffice.tech)
- 📧 Email: [Head@schooloffice.tech](mailto:Head@schooloffice.tech)
- 👤 Developer: [Muni Ram Meena](https://github.com/Muniramm890)

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1E2E52,100:E8600A&height=100&section=footer" alt="footer" />
</p>
