# 🚌 SRMSS — Smart Route Management and Scheduling System

A comprehensive **bus fleet and route management dashboard** built for transport companies and depot managers. SRMSS covers everything from route planning and driver management to real-time GPS tracking, ticketing, fuel logging, maintenance records, and reporting — all through a modern, colorful React interface.

---

## ✨ Features

| Module | Description |
|---|---|
| 🔐 Authentication | Login/logout with role-based access control |
| 📊 Dashboard | Real-time stats, charts, alerts, and recent schedules |
| 🗺️ Route Management | CRUD for routes with stop sequences |
| 🚍 Bus Fleet | Bus inventory with QR code generation |
| 👨‍✈️ Driver Management | Driver profiles with license expiry tracking |
| 📅 Scheduling | Trip scheduling linking routes, buses, and drivers |
| 📡 Live Tracker | Real-time GPS bus tracking on an interactive map |
| 🎫 Tickets | Passenger ticket booking with fare calculation |
| ⛽ Fuel Logs | Fuel consumption tracking per bus |
| 🔧 Maintenance Logs | Maintenance records and scheduling |
| 📈 Reports | Multi-type report generation with PDF export |
| 👤 Admin Users | User account management with role-based permissions |

---

## 🛠️ Tech Stack

- **Frontend:** React 19, TypeScript, Vite
- **Routing:** React Router DOM v7
- **Styling:** Tailwind CSS
- **Charts:** Recharts
- **Icons:** Lucide React
- **i18n:** i18next + react-i18next
- **Backend (planned):** Supabase (database, auth, real-time)
- **Maps:** Google Maps (embedded iframe)
- **Linting:** ESLint + TypeScript ESLint

---

## 📁 Project Structure

```
src/
├── components/
│   ├── base/          # Reusable UI components (StatCard, etc.)
│   └── feature/       # Layout, Sidebar
├── i18n/              # Internationalization config & locales
├── mocks/             # Mock data (buses, drivers, routes, etc.)
├── pages/
│   ├── dashboard/
│   ├── routes/
│   ├── buses/
│   ├── drivers/
│   ├── schedules/
│   ├── tracker/
│   ├── tickets/
│   ├── fuel-logs/
│   ├── maintenance-logs/
│   ├── reports/
│   ├── admin-users/
│   └── login/
└── router/            # Route definitions
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/srmss.git
cd srmss

# Install dependencies
npm install
```

### Development

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Lint & Type Check

```bash
npm run lint
npm run type-check
```

---

## 🗺️ Pages & Routes

| Path | Page |
|---|---|
| `/login` | Login |
| `/dashboard` | Main Dashboard |
| `/routes` | Route Management |
| `/buses` | Bus Fleet |
| `/drivers` | Driver Management |
| `/schedules` | Trip Scheduling |
| `/tracker` | Live Bus Tracker |
| `/tickets` | Ticket Booking |
| `/fuel-logs` | Fuel Logs |
| `/maintenance-logs` | Maintenance Logs |
| `/reports` | Reports |
| `/admin-users` | Admin User Management |

---

## 🗄️ Database Schema (Supabase — planned)

- `routes` — Route definitions
- `route_stops` — Individual stops per route
- `buses` — Bus fleet inventory
- `drivers` — Driver profiles
- `schedules` — Trip assignments
- `tickets` — Passenger records
- `fuel_logs` — Fuel consumption records
- `maintenance_logs` — Maintenance records
- `admin_users` — System accounts
- `bus_locations` — Real-time GPS data

---

## 📦 Development Phases

- [x] **Phase 1** — Login Page + Dashboard
- [x] **Phase 2** — Routes + Buses
- [x] **Phase 3** — Drivers + Schedules
- [x] **Phase 4** — Live Tracker + Tickets
- [x] **Phase 5** — Fuel Logs + Maintenance Logs
- [ ] **Phase 6** — Reports + Admin Users + Final Polish

---

## 📄 License

This project is private. All rights reserved.
