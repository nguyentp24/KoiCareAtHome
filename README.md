<!-- KoiCareAtHome — GitHub project README -->

<div align="center">

# 🐟 KoiCareAtHome

### Koi Pond & Fish Care Management Platform

A full-stack web application that helps koi enthusiasts manage ponds, track fish growth, monitor water quality, and make informed day-to-day care decisions.

<p>
  <img alt="React" src="https://img.shields.io/badge/React-18-149ECA?style=for-the-badge&logo=react&logoColor=white" />
  <img alt="Vite" src="https://img.shields.io/badge/Vite-5-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img alt="ASP.NET Core" src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-3-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
</p>

**Frontend:** Deployed on Vercel · **Backend:** Cloud deployment pending

[Source Code](https://github.com/namt-fptu/SWP391_KoiCareAtHome) · [Architecture Explorer](https://gitdiagram.com/namt-fptu/swp391_koicareathome)

<!-- Add your actual deployed frontend URL once available:
[Live Frontend Demo](https://YOUR-PROJECT.vercel.app)
-->

</div>

---

## Overview

**KoiCareAtHome** is a web-based koi care management system developed as part of **SWP391 — Software Development Project**. It brings together essential koi-keeping tasks in one place: recording pond information, managing individual fish profiles, following growth over time, tracking water conditions, and using care-related calculators.

The application also includes dedicated interfaces for pond owners, shops, and administrators, supporting different workflows within a shared platform.

## Description

Maintaining a healthy koi pond requires keeping track of multiple factors, including fish development, pond specifications, feeding requirements, and water quality. Managing these details across notes and spreadsheets can make routine care difficult.

KoiCareAtHome addresses this problem through a centralized dashboard and structured workflows. Pond owners can organize information about their ponds and koi, review changes over time, and use the application's calculators and water-parameter guidance. Shop and administrator interfaces extend the system with product, content, reference-data, and account-management screens.

## Project Information

| Item | Details |
| --- | --- |
| Project | KoiCareAtHome — Koi Care Management System |
| Course | SWP391 — Software Development Project |
| Institution | FPT University |
| Project type | Academic full-stack web application |
| Repository | [namt-fptu/SWP391_KoiCareAtHome](https://github.com/namt-fptu/SWP391_KoiCareAtHome) |
| Current hosting | Frontend on Vercel; Backend not yet publicly deployed |

> **For recruiters:** The frontend has been deployed, but the backend is not yet hosted publicly. Features that require API access may not work in the online frontend demo until the backend deployment and database configuration are complete. The source code is available for technical review.

## Screenshots

Screenshots of the application will be added after the relevant pages are captured. Suggested views include the landing page, pond dashboard, koi profiles, water parameter tracking, shop management, and admin dashboard.

<!--
To display actual screenshots, create a screenshots/ folder in the repository,
add the image files, and uncomment/update the references below:

![Landing Page](screenshots/landing-page.png)
*Landing page and navigation*

![Pond Dashboard](screenshots/pond-dashboard.png)
*Pond owner overview*

![Koi Management](screenshots/koi-management.png)
*Koi profiles and growth tracking*

![Water Parameters](screenshots/water-parameters.png)
*Water quality monitoring*

![Shop Dashboard](screenshots/shop-dashboard.png)
*Shop management interface*

![Admin Dashboard](screenshots/admin-dashboard.png)
*Administration dashboard*
-->

## Features

### Core Features — Pond Owners

1. **Pond Management**
   - Maintain pond names, images, dimensions, depth, and volume.
   - Record technical specifications such as drain count and pump capacity.
   - Organize fish information by pond.

2. **Koi Fish Management & Growth Tracking**
   - Manage koi profiles, including name, image, breed, age, sex, appearance, size, weight, origin, and current pond.
   - Update growth records and review development trends with charts.
   - Access koi-related reference information.

3. **Water Quality Monitoring**
   - Record water temperature, salinity, pH, dissolved oxygen, NO2, NO3, and PO4.
   - Follow changes in pond conditions over time.
   - Review recommendations when recorded parameters are outside expected ranges.

4. **Care Calculators**
   - Estimate feeding quantities based on koi growth and care needs.
   - Calculate pond salt requirements.

5. **Insights & Learning Resources**
   - Access statistics, reports, blogs, and informational content about koi care.

### Additional Workflows

**Shop interface**
- Shop overview and profile screens.
- Product and post management screens.
- VIP package and payment-history interfaces.

**Administrator interface**
- Administration dashboard and user-management screens.
- Management interfaces for koi varieties and growth standards.
- Water-parameter standards, posts, and posting packages.

**Authentication & access**
- Sign-in and sign-up screens.
- Role-aware frontend routing for `PondOwner`, `Shop`, and `Admin`.
- Axios-based API integration with bearer-token support.

> Feature descriptions reflect the repository's documented scope and frontend routes. Availability of complete end-to-end workflows depends on backend services and configuration.

## Tech Stack

### Frontend

![React](https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Ant Design](https://img.shields.io/badge/Ant_Design-0170FE?style=flat-square&logo=antdesign&logoColor=white)

- **React 18 & Vite 5** — component-based user interface and frontend tooling.
- **React Router** — client-side navigation and role-aware routes.
- **Tailwind CSS, Ant Design & Sass** — layout, components, and styling.
- **Axios & TanStack React Query** — HTTP requests and server-state management.
- **Zustand** — client-side state management.
- **Chart.js / react-chartjs-2** — data visualizations and statistics.
- **Firebase SDK** — included in the frontend dependencies.

### Backend

![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![C%23](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)

- **ASP.NET Core / C#** — backend application and API layer.
- **HTTP API** — used by the React frontend for data and authentication workflows.
- **Database** — requires local or hosted backend database configuration; exact database engine and setup should be verified in the backend project.

### Development & Hosting

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

- **Git & GitHub** — version control and source management.
- **Vercel** — frontend hosting.
- **Visual Studio / VS Code** — local development.

## Architecture

```mermaid
flowchart TD
    U[User / Web Browser] --> FE[React + Vite Frontend]
    FE -->|Axios / HTTP API| BE[ASP.NET Core Backend]
    BE --> DB[(Configured Database)]

    FE --- UI[Role-based Screens: PondOwner / Shop / Admin]

    classDef frontend fill:#e9f7f5,stroke:#0d9488,color:#134e4a
    classDef backend fill:#eff6ff,stroke:#2563eb,color:#1e3a8a
    class FE,UI frontend
    class BE,DB backend
```

The frontend is a React single-page application. Its routes separate pond-owner, shop, and administrator experiences. The backend provides the application API and connects to the configured database.

**Deployment note:** The frontend is hosted on Vercel; the backend and its database still require cloud hosting before the full application can be demonstrated online.

## Project Structure

```text
SWP391_KoiCareAtHome/
├── BE/
│   └── SWP391.KoiCareSystemAtHome.Fa24/   # .NET backend solution/projects
├── FE/
│   ├── public/                           # Static assets
│   ├── src/
│   │   ├── component/                   # Domain UI components and dashboards
│   │   ├── config/                      # API configuration (Axios)
│   │   ├── page/                        # Pages and role-specific layouts
│   │   ├── routes/                      # Route helpers
│   │   ├── App.jsx                      # Application routes
│   │   └── main.jsx                     # React application entry point
│   ├── index.html
│   ├── package.json
│   └── vite.config.js
└── README.md
```

## Building and Usage

### Prerequisites

- **Git**
- **Node.js 18+** and **npm** for the Vite frontend
- A **.NET SDK** compatible with the backend project's target framework
- A configured **database** and any required backend service settings

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/namt-fptu/SWP391_KoiCareAtHome.git
cd SWP391_KoiCareAtHome
```

**2. Start the frontend**

```bash
cd FE
npm ci
npm run dev
```

Open the URL displayed by Vite in the terminal (typically `http://localhost:5173`).

To create a production frontend build:

```bash
npm run build
npm run preview
```

**3. Run the backend locally**

1. Open `BE/SWP391.KoiCareSystemAtHome.Fa24/` in Visual Studio or locate its solution and Web API `.csproj` file.
2. Install the .NET SDK version required by that project.
3. Set up the database and required configuration values in a secure, local-only configuration source.
4. Restore dependencies, select the API startup project, and run it.
5. Confirm the backend's listening address before connecting the frontend.

> The exact backend start command and database initialization steps depend on the `.csproj`, startup project, and database configuration. They are intentionally not guessed here.

### API Configuration

The frontend's Axios configuration in the original repository is located at:

```text
FE/src/config/axios.jsx
```

The checked-in version uses `http://localhost:5088/api/` as its API base URL. To use a deployed backend, update the configuration to reference the public HTTPS API address, ideally through a Vite environment variable such as `VITE_API_BASE_URL`.

Example for a frontend that has been updated to read that variable:

```env
VITE_API_BASE_URL=https://your-api-host.example.com/api/
```

Do not commit passwords, database connection strings with credentials, private keys, or other secrets. Variables exposed through Vite's `VITE_` prefix are bundled into client-side code and must not contain sensitive values.

## Deployment Status

| Component | Current status | Notes |
| --- | --- | --- |
| Frontend | **Deployed** | Hosted on Vercel; add the actual public link above |
| Backend API | **Not yet deployed** | Currently requires a local or separately configured environment |
| Database | **Cloud setup not yet confirmed** | Required for end-to-end API functionality |
| Full online demonstration | **In progress** | Will be available after backend integration |

## Next Steps

- Deploy the ASP.NET Core API and configure its database securely.
- Connect the Vercel frontend to the hosted API through an environment-based URL.
- Add real application screenshots and a public demo link to this README.
- Document backend-specific prerequisites and exact startup instructions.

---

<div align="center">

**KoiCareAtHome** · SWP391 — Software Development Project

[Back to top](#-koicareathome)

</div>
