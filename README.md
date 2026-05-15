<div align="center">
![Ahaar Bonton Banner](Assets/Banner/AhaarBonton%20Banner.png)
 
# 🍛 Ahaar Bonton — আহার বণ্টন
 
### A Surplus Food Redistribution Platform
 
*Connecting Donors, NGOs, and Volunteers to Reduce Food Waste*
 
<br/>
[![Django](https://img.shields.io/badge/Django-6.0.5-092E20?style=for-the-badge&logo=django&logoColor=white)](https://www.djangoproject.com/)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![HTML](https://img.shields.io/badge/HTML5-Frontend-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-Styling-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-Interactivity-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
 
<br/>
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/TajkirHossen-14/Ahaar_Bonton?style=flat-square)](https://github.com/TajkirHossen-14/Ahaar_Bonton/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/TajkirHossen-14/Ahaar_Bonton?style=flat-square)](https://github.com/TajkirHossen-14/Ahaar_Bonton/commits/main)
 
</div>
---
 
## 📖 About the Project
 
**Ahaar Bonton (আহার বণ্টন)** is a web-based platform built to bridge the gap between surplus food and those in need. Every day, enormous amounts of edible food go to waste at restaurants, events, and households — while many people go hungry. This platform provides a structured, community-driven solution to that problem.
 
Donors can post surplus food listings, NGOs can claim and coordinate pickups, and volunteers can register to assist with deliveries — all through a single, unified platform.
 
> *"Ahaar" (আহার) means food, and "Bonton" (বণ্টন) means distribution — together, a name that speaks for itself.*
 
---
 
## ✨ Key Features
 
- 🥘 **Food Donation Listings** — Donors can post surplus food with details like quantity, type, and pickup location
- 🏢 **NGO Dashboard** — NGOs can browse available donations and claim them for redistribution
- 🚴 **Volunteer Management** — Volunteers can register and assist with food pickup and delivery
- 👤 **User Authentication** — Separate registration and profile management for Donors, NGOs, and Volunteers
- 📦 **Delivery Tracking** — Manage and track the status of food deliveries
- 🖼️ **Image Uploads** — Food listings support photo uploads via Pillow
---
 
## 🗂️ Project Structure
 
```
Ahaar_Bonton/
│
├── ahaarbonton/        # Django project settings & URLs
├── core/               # Landing page, homepage, core views
├── food/               # Food listing, donation models & views
├── delivery/           # Delivery assignment & tracking
├── users/              # User registration, login, profiles
│
├── templates/          # HTML templates (shared & per-app)
├── static/             # CSS, JS, and static assets
├── Assets/             # Project assets (banner, logos, etc.)
│
├── manage.py
└── requirements.txt
```
 
---
 
## 🛠️ Tech Stack
 
| Layer | Technology |
|-------|-----------|
| Backend Framework | Django 6.0.5 |
| Language | Python 3.x |
| Database | SQLite (default) |
| Frontend | HTML5, CSS3, JavaScript |
| Image Handling | Pillow 12.2.0 |
| Templating | Django Templates |
 
---
 
## 🚀 Getting Started
 
### Prerequisites
 
- Python 3.10 or higher
- pip
### Installation
 
**1. Clone the repository**
```bash
git clone https://github.com/TajkirHossen-14/Ahaar_Bonton.git
cd Ahaar_Bonton
```
 
**2. Create and activate a virtual environment**
```bash
# Windows
python -m venv venv
venv\Scripts\activate
 
# Linux / macOS
python -m venv venv
source venv/bin/activate
```
 
**3. Install dependencies**
```bash
pip install -r requirements.txt
```
 
**4. Apply migrations**
```bash
python manage.py migrate
```
 
**5. Create a superuser (optional)**
```bash
python manage.py createsuperuser
```
 
**6. Run the development server**
```bash
python manage.py runserver
```
 
Now open your browser and visit **http://127.0.0.1:8000** 🎉
 
---
 
## 👥 User Roles
 
| Role | Description |
|------|-------------|
| 🧑‍🍳 **Donor** | Individuals, restaurants, or businesses that post surplus food |
| 🏢 **NGO** | Organizations that claim food donations and manage distribution |
| 🚴 **Volunteer** | Individuals who help with pickup and delivery of food |
 
---
 
## 🤝 Contributing
 
Contributions are welcome! If you'd like to improve the platform:
 
1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request
 
---
 
## 🙏 Acknowledgements
 
This project was built with the goal of using technology to address real-world food insecurity and reduce waste. Inspired by grassroots food-sharing movements across Bangladesh and beyond.
