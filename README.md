# Smart Construction & Demolition (C&D) Waste Governance Platform

An end-to-end civic platform for Construction & Demolition (C&D) waste management, geo-tagged field verification, automated jurisdictional routing, and circular economy tracking.

---

## 🚀 Key Features

- **Citizen & Contractor Portal**: Submit C&D pickup requests with live GPS geolocation, address auto-detection, material categorization, and camera photo capture.
- **Automated Jurisdiction Engine**: Dynamic 6-tier routing engine that automatically dispatches requests to the appropriate urban local body (Municipal Corporation, Town Panchayat, or Gram Panchayat) and assigns the dedicated ward inspector based on PIN code.
- **Field Inspector Audit Console**: On-site verification dashboard for assigned inspectors to perform physical audits, log tonnage, upload geotagged proof, and approve or schedule clearance.
- **Municipal Officer Command Center**: High-level administrative dashboard for municipal commissioners and panchayat officers to monitor SLAs, track disposal compliance, issue digital clearance certificates, and view real-time enforcement analytics.
- **Resilient Backend & Offline Support**: Express/Node.js backend with dual persistence (Cloud DB & local disk fallback) and high-accuracy reverse geocoding.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, Modern Vanilla JavaScript (ES6+), Tailwind CSS
- **Backend**: Node.js, Express
- **Database**: Cloud PostgreSQL / JSON Persistence Engine
- **Geolocation**: High-precision OpenStreetMap Nominatim reverse geocoding proxy with GPS fallback

---

## 📂 Project Structure

```
├── citizen.html       # Citizen / Contractor Pickup Booking Portal
├── inspector.html     # Field Inspector Verification & Audit Portal
├── officer.html       # Municipal Officer Command Center & Certificate Desk
├── dashboard.html     # Public Civic Analytics & Monitoring Console
├── auth.html          # Unified Role-Based Authentication
├── server.js          # Backend API & Geocoding Routing Server
├── database.json      # Local Database Cache & Configuration
└── lib/
    └── supabase.js    # Database Client & Schema Mappings
```

---

## 🏃 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm

### Installation & Run

1. Clone the repository:
   ```bash
   git clone https://github.com/gargieyogish/MBA_GSSS.git
   cd MBA_GSSS
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the application:
   ```bash
   node server.js
   ```

4. Open in browser:
   - **Citizen Portal**: `http://localhost:8000/citizen.html`
   - **Inspector Portal**: `http://localhost:8000/inspector.html`
   - **Officer Portal**: `http://localhost:8000/officer.html`
   - **Login**: `http://localhost:8000/auth.html`

---

## 📜 License
This project is licensed under the MIT License.
