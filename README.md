# B2B Service Management Portal 🚀

![Project Status](https://img.shields.io/badge/Status-In%20Development-yellow)
![Laravel](https://img.shields.io/badge/Laravel-11%2B-red)
![PHP](https://img.shields.io/badge/PHP-8.3%2F8.4-blue)
![Filament](https://img.shields.io/badge/Admin-FilamentPHP-orange)
![Frontend](https://img.shields.io/badge/Frontend-React%20%2B%20Inertia-cyan)

## 📖 Introduction

**B2B Service Management Portal** is a comprehensive web application designed for B2B service providers to streamline their operations. It connects service providers with their corporate clients through a centralized platform.

This system allows the administration to manage contracts, upload daily reports, and track client interactions, while providing a dedicated portal for clients to view their reports, feedback directly, and receive automated notifications.

## ✨ Key Features

### 🏢 For Admin & Staff (Internal Portal)
- **Organization Management:** Manage client profiles, tax info, and contact details.
- **Contract Lifecycle:** - Digital contract storage.
  - **Automated Alerts:** Daily cron jobs to scan and notify Sales/Directors about expiring contracts (30 days, 7 days, Overdue).
- **Report Distribution:** Securely upload reports (PDF/Excel) for specific clients.
- **Role-Based Access Control (RBAC):** Granular permissions for Super Admin, Sales, and Accountants.

### 🤝 For Clients (Customer Portal)
- **Private Dashboard:** Secure login to view only their own organization's data.
- **Document Repository:** Search and download reports by date/category.
- **Interactive Feedback:** Comment directly on reports to ask questions or request clarifications.
- **Notification Hub:** Real-time updates via Email and System Notifications when new reports arrive.

## 🛠 Tech Stack

- **Backend:** Laravel Framework (PHP 8.4).
- **Admin Panel:** FilamentPHP v3 (Livewire based).
- **Client Frontend:** ReactJS + Inertia.js + Tailwind CSS (shadcn/ui).
- **Database:** MySQL 8.0.
- **File Storage:** Local/S3 (Secure private storage).
- **Automation:** Laravel Task Scheduling (Cron jobs).

## 📸 Screenshots

*(Add your screenshots here later)*

| Admin Dashboard | Client Portal |
|:---:|:---:|
| ![Admin Dashboard](https://via.placeholder.com/600x400?text=Admin+Dashboard+Screenshot) | ![Client Portal](https://via.placeholder.com/600x400?text=Client+Portal+Screenshot) |

## 🚀 Installation & Setup

Follow these steps to set up the project locally:

### Prerequisites
- PHP >= 8.3
- Composer
- Node.js & NPM
- MySQL

### Steps

1. **Clone the repository**
   ```bash
   git clone [https://github.com/your-username/b2b-service-manager.git](https://github.com/your-username/b2b-service-manager.git)
   cd b2b-service-manager
