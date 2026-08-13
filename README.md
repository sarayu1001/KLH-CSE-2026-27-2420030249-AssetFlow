# AssetFlow – AI-Powered Enterprise IT Asset Management Platform with Intelligent Asset Tracking & Lifecycle Monitoring

## Team Members

| S. No. | University ID | Name                  |
| ------ | ------------- | --------------------- |
| 1      | 2420030249    | Anakala Sarayu        |
| 2      | 2420030269    | Manduri Varshitha     |
| 3      | 2420030468    | Nidumolu Veda Samhita |
| 4      | 2420090076    | Sushmita Sallam       |

## Supervisor

**Ms. G Lavanya**

## Abstract

AssetFlow – AI-Powered Enterprise IT Asset Management Platform with Intelligent Asset Tracking & Lifecycle Monitoring is a web-based enterprise application designed to simplify and automate the management of organizational IT assets throughout their complete lifecycle.

Organizations manage a large number of assets such as laptops, desktops, servers, networking devices, and other IT equipment. Maintaining accurate asset records, monitoring asset assignments, tracking maintenance activities, and identifying assets approaching replacement can become difficult when these activities are handled manually. AssetFlow addresses these challenges through a centralized platform for efficient asset registration, tracking, assignment, monitoring, and lifecycle management.

The platform enables administrators and authorized users to register IT assets, maintain asset information, assign assets to employees or departments, track asset status, and monitor asset lifecycle events. The system provides centralized visibility into available, assigned, under-maintenance, and retired assets.

AssetFlow is developed using modern Software Engineering practices. The application follows an Agile development approach with requirements organized into user stories and development activities managed through a prioritized product backlog. Jira is used for task and sprint management, while Git and GitHub are used for version control and collaborative development.

The backend is implemented using Spring Boot 3 and provides RESTful APIs for asset management and business operations. React.js is used to develop the interactive frontend, while PostgreSQL is used as the relational database for storing asset and user information.

Docker is used to containerize application components, providing a consistent development and deployment environment. The system is designed with a modular and scalable architecture that can be extended with intelligent asset monitoring and AI-powered capabilities for asset lifecycle analysis, maintenance prediction, and decision support.

Overall, AssetFlow provides a centralized, scalable, and intelligent solution for enterprise IT asset management, helping organizations improve asset visibility, reduce manual effort, optimize asset utilization, and make better lifecycle management decisions.

## Objectives

* Centralize IT asset information in a single platform.
* Track assets throughout their complete lifecycle.
* Manage asset assignment to employees and departments.
* Monitor asset status and availability.
* Maintain accurate asset records and history.
* Reduce manual effort involved in asset management.
* Provide intelligent insights for asset lifecycle management.
* Improve asset utilization and operational efficiency.
* Provide a scalable and maintainable enterprise application.

## Key Features

### Asset Management

* Register new IT assets.
* Update and maintain asset information.
* View complete asset details.
* Search and filter assets.
* Categorize assets based on type and status.

### Asset Tracking

* Track asset assignment and ownership.
* Monitor current asset status.
* Track available, assigned, maintenance, and retired assets.
* Maintain asset lifecycle history.

### Employee and Department Management

* Manage employees and departments.
* Assign assets to employees or departments.
* View assets associated with specific users or departments.

### Lifecycle Monitoring

* Monitor asset acquisition and assignment.
* Track maintenance activities.
* Identify assets approaching end-of-life.
* Manage asset retirement and replacement.

### Intelligent Asset Management

* Analyze asset lifecycle information.
* Generate intelligent insights from asset data.
* Support maintenance and replacement decisions.
* Provide data-driven asset management recommendations.

## Technologies Used

### Frontend

* React.js

### Backend

* Java
* Spring Boot 3
* REST APIs

### Database

* PostgreSQL

### DevOps & Development

* Git
* GitHub
* Docker

### Project Management

* Jira

### AI / Intelligent Components

* AI-powered asset lifecycle analysis
* Intelligent asset tracking
* Predictive asset monitoring and recommendations

## System Architecture

The AssetFlow application follows a layered web application architecture:

```text
Users
  |
  v
React.js Frontend
  |
  v
Spring Boot 3 REST APIs
  |
  v
Business Logic / Asset Management Services
  |
  v
PostgreSQL Database
```

Docker is used to containerize the application components and provide a consistent environment for development and deployment.

## Project Structure

```text
AssetFlow/
│
├── src/
│   ├── frontend/
│   └── backend/
│
├── docs/
│
├── data/
│
├── results/
│
├── reports/
│
└── README.md
```

## Setup Instructions

### Prerequisites

Make sure the following software is installed:

* Java 21 or compatible Java version required by the project
* Node.js and npm
* PostgreSQL
* Git
* Docker
* GitHub account

### Clone the Repository

```bash
git clone https://github.com/sarayu1001/KLH-CSE-2026-27-2420030249-AssetFlow.git
cd KLH-CSE-2026-27-2420030249-AssetFlow
```
