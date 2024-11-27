# **Vehicle Maintenance System (VMS)**

## **Overview**

The Vehicle Maintenance System (VMS) is a software solution designed to streamline and automate the management of vehicle fleet maintenance. It helps organizations schedule routine maintenance, track service history, manage spare parts inventory, and ensure compliance with safety and regulatory standards. This project aims to reduce operational costs, minimize vehicle downtime, and enhance overall fleet performance.

---

## **Features**

- **Maintenance Scheduling**:
  Automates the scheduling of vehicle maintenance to prevent downtime and extend vehicle lifespan.
  
- **Service History Tracking**:
  Logs and tracks detailed service records for every vehicle in the fleet.

- **Inventory Management**:
  Monitors spare parts inventory and provides alerts for low stock levels.

- **Reporting and Analytics**:
  Offers insights into maintenance costs, vehicle performance, and fleet efficiency.

- **Integration**:
  Supports integration with third-party systems like accounting software and GPS tracking tools.

- **Role-Based Access Control**:
  Provides secure access to system features based on user roles (Fleet Managers, Mechanics, Admins).

---

## **Technology Stack**

- **Frontend**: React.js
- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **Testing**: JUnit, Mocha, and JMeter
- **Version Control**: Git and GitHub
- **Deployment**: Docker and Kubernetes

---

## **Project Structure**

```plaintext
VMS_Project/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── src/
│   ├── config/
│   └── package.json
│
├── database/
│   ├── schema/
│   └── seeds/
│
├── docs/
│   ├── Requirements.md
│   ├── ProjectSchedule.md
│   ├── RiskRegister.md
│   ├── IssueRegister.md
│   └── TestingPlan.md
│
├── README.md
└── .gitignore
