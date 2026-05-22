# 📊 Django CRM Dashboard

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Django](https://img.shields.io/badge/Django-4.2-green)
![MySQL](https://img.shields.io/badge/MySQL-8.0-orange)
![Chart.js](https://img.shields.io/badge/Chart.js-4.0-red)
![License](https://img.shields.io/badge/License-MIT-yellow)

A full-featured **CRM (Customer Relationship Management)** web application with client management, project tracking, invoicing, and analytics dashboard built with Django.

## ✨ Features

- 👥 Client & contact management
- 💼 Project tracking with milestones
- 🧾 Invoice generation (PDF export)
- 💬 Notes & activity timeline per client
- 📊 Analytics dashboard with Chart.js
- 🔔 Follow-up reminders & notifications
- 🔐 User authentication & permissions
- 📁 File attachments per client/project
- 📤 Export data to Excel/CSV

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Django 4.2 |
| Database | MySQL 8.0 |
| Frontend | Bootstrap 5 + Chart.js |
| Auth | Django built-in + 2FA |
| Reports | ReportLab (PDF) + openpyxl |
| Task Queue | Celery + Redis |

## 🚀 Quick Start

```bash
git clone https://github.com/rashedkhanrubel-spec/django-crm-dashboard
cd django-crm-dashboard
pip install -r requirements.txt
cp .env.example .env
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

## 📁 Project Structure

```
django-crm-dashboard/
├── apps/
│   ├── clients/         # Client & contact management
│   ├── projects/        # Project & milestone tracking
│   ├── invoices/        # Invoice generation
│   ├── dashboard/       # Analytics & charts
│   └── notifications/   # Reminders & alerts
├── templates/           # HTML templates
├── static/              # CSS, JS, images
├── manage.py
└── requirements.txt
```

## 📬 Contact

Built by [Md Rashed Khan](https://www.freelancer.com/u/rashedkhanrubel) — Available for CRM & business application projects.

