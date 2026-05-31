<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=700&size=45&duration=2500&pause=600&color=FFD60A&center=true&vCenter=true&width=700&lines=Syzaar%2B" alt="Syzaar+" />

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=888888&center=true&vCenter=true&width=750&lines=Workforce+Performance+%26+Productivity+Analytics;Computer+Vision+%7C+Django+%7C+AI-Powered;Smart+Monitoring+for+Industrial+Environments" alt="Subtitle" />

<br>

![Python Version](https://img.shields.io/badge/Python-3.12-3776AB.svg?style=for-the-badge&logo=Python)
![Django Version](https://img.shields.io/badge/Django-5.0-092E20.svg?style=for-the-badge&logo=Django)
![OpenCV](https://img.shields.io/badge/OpenCV-4.8-5C3EE8.svg?style=for-the-badge&logo=OpenCV)
![License](https://img.shields.io/badge/License-MIT-FFD60A.svg?style=for-the-badge)
![Status](https://img.shields.io/badge/UI-Completed-4CC9F0?style=for-the-badge)
![AI](https://img.shields.io/badge/AI_Engine-In_Development-FF006E?style=for-the-badge)

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

</div>

## Overview

**Syzaar+** is a next-generation workforce performance and productivity analytics platform designed for industrial and manufacturing environments. The platform converts raw visual data captured from IP camera infrastructure into structured, actionable business intelligence — enabling facility managers to optimize workforce activity, reduce operational inefficiencies, and uphold quality standards.

The user interface and experience layer are fully developed and production-ready. The AI-powered detection engine — built on computer vision and deep learning technologies — is currently under active development and will be progressively integrated into the platform.

---

## Core Features

| Feature | Description | Status |
|---------|-------------|--------|
| 📍 **Zone Management** | Define, configure, and manage specific work zones via an intuitive drag-and-drop interface. Isolate analysis to areas of operational significance. | ✅ Complete |
| 🧠 **AI Activity Recognition** | Automatically detect active versus idle workforce states, flagging anomalies and prolonged inactivity in real time using advanced algorithms. | ⏳ In Development |
| 📹 **Multi-Camera Integration** | Native support for up to 10 simultaneous IP camera streams with automatic device discovery and unified monitoring. | ✅ Complete |
| 🤖 **Per-Zone AI Models** | Assign dedicated, fine-tuned AI models to individual zones for maximum detection accuracy across diverse operational tasks. | ⏳ In Development |
| 📊 **Data & Reporting** | Capture frame-by-frame performance data and export comprehensive reports in standard formats including Excel for further analysis. | ✅ Complete |
| 🖥️ **Modern UI/UX** | A fully responsive, dynamic interface with live visual labeling and at-a-glance operational insights. | ✅ Complete |

---

## Technology Stack

| Layer | Technologies |
|-------|-------------|
| **Backend** | Python 3.12, Django 5.0 |
| **Frontend** | HTML5, CSS3, JavaScript |
| **Database** | SQLite 3 (Development), PostgreSQL (Production) |
| **Computer Vision** | OpenCV 4.8 |
| **AI / ML** | TensorFlow / PyTorch *(Planned)* |

---

## Screenshots

<div align="center">

### Zone Configuration Interface
![Zone Configuration](Project_Picture/Image%20(2).png)

### Dashboard Overview
![Dashboard UI](Project_Picture/Image%20(7).png)

</div>

---

## Project Structure

```
Syzaar+/
│
├── Config/                     # Project configuration
│   ├── settings.py
│   └── urls.py
│
├── Detection_App/              # Core application module
│   ├── admin.py
│   ├── forms.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
│
├── static/                     # Static assets
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/                  # HTML templates
│   ├── base.html
│   ├── landing.html
│   ├── login.html
│   ├── overview.html
│   ├── camera_management.html
│   ├── zone_configuration.html
│   └── reports.html
│
├── db.sqlite3
└── manage.py
```

---

## Installation

### Prerequisites

- Python 3.12 or higher
- Git

### Setup

**1. Clone the repository**
```bash
git clone https://github.com/Amin-Moniry/syzaar-plus.git
cd syzaar-plus
```

**2. Create and activate a virtual environment**

Windows:
```bash
python -m venv venv
.\venv\Scripts\activate
```

macOS / Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

**4. Apply database migrations**
```bash
python manage.py makemigrations
python manage.py migrate
```

**5. Create a superuser account**
```bash
python manage.py createsuperuser
```

**6. Start the development server**
```bash
python manage.py runserver
```

The application will be available at `http://127.0.0.1:8000/`

---

## Dependencies

```
Django>=5.0.0
opencv-python>=4.8.0
Pillow>=10.0.0
numpy>=1.24.0
```

---

## Usage

1. Navigate to `http://127.0.0.1:8000/` and log in with your superuser credentials
2. Access the admin panel at `http://127.0.0.1:8000/admin/` for camera and zone configuration
3. Use the dashboard to monitor operational zones, review activity data, and generate reports

---

## Roadmap

- [ ] AI-powered workforce activity recognition
- [ ] Dedicated AI model assignment per zone
- [ ] Enhanced real-time analytics engine
- [ ] Advanced reporting and export features
- [ ] Mobile application support
- [ ] Third-party system integrations

---

## Contributing

Contributions are welcome. Please follow the standard workflow:

1. Fork the repository
2. Create a feature branch — `git checkout -b feature/YourFeature`
3. Commit your changes — `git commit -m 'Add YourFeature'`
4. Push to the branch — `git push origin feature/YourFeature`
5. Open a Pull Request with a clear description of the changes

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for full details.

**© 2026 Amin Moniry (AminTivanix2) — All Rights Reserved**

---

## Contact & Support

<div align="center">

| Channel | Link |
|---------|------|
| 📧 Email | [amintivanix2@gmail.com](mailto:amintivanix2@gmail.com) |
| 💻 GitHub | [Amin-Moniry](https://github.com/Amin-Moniry) |
| 📱 Telegram | [@amintivanix2](https://t.me/amintivanix2) |
| 🌐 Website | [allin1wrench.ir](https://allin1wrench.ir) |
| 🐛 Issues | [GitHub Issues](https://github.com/Amin-Moniry/syzaar-plus/issues) |

</div>

---

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=700&size=20&duration=3000&pause=1000&color=FFD60A&center=true&vCenter=true&width=700&lines=Built+with+%E2%9D%A4%EF%B8%8F+by+Amin+Moniry+(AminTivanix2);Transforming+Industrial+Operations+Through+AI;Smart+%7C+Scalable+%7C+Reliable" alt="Footer" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=FFD60A&height=120&section=footer&fontColor=240046" width="100%"/>

</div>
