<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:010d12,50:00B4D8,100:010d12&height=220&section=header&text=SYZAAR%2B&fontSize=72&fontAlign=50&fontAlignY=55&fontColor=ffffff&animation=fadeIn&desc=Workforce%20Performance%20and%20Productivity%20Analytics&descAlign=50&descAlignY=75&descSize=16&v=1" width="100%"/>


<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&weight=700&size=20&duration=4000&pause=800&color=00B4D8&center=true&vCenter=true&width=700&height=40&lines=%E2%96%B6+COMPUTER+VISION+%7C+DJANGO+%7C+AI-POWERED;%E2%97%8F+SMART+MONITORING+FOR+INDUSTRIAL+ENVIRONMENTS;%E2%96%B6+WORKFORCE+PERFORMANCE+%26+PRODUCTIVITY+ANALYTICS"/>

<br/>

<a href="#"><img src="https://img.shields.io/badge/%E2%96%B6+PYTHON-3.12-00B4D8?style=for-the-badge&labelColor=010d12&logo=python&logoColor=00B4D8"/></a>
<a href="#"><img src="https://img.shields.io/badge/%E2%96%B6+DJANGO-5.0-00B4D8?style=for-the-badge&labelColor=010d12&logo=django&logoColor=00B4D8"/></a>
<a href="#"><img src="https://img.shields.io/badge/%E2%97%88+OPENCV-4.8-00B4D8?style=for-the-badge&labelColor=010d12&logo=opencv&logoColor=00B4D8"/></a>
<a href="LICENSE"><img src="https://img.shields.io/badge/%E2%96%A3+LICENSE-MIT-0077A8?style=for-the-badge&labelColor=010d12"/></a>
<a href="#"><img src="https://img.shields.io/badge/%E2%96%B2+UI-COMPLETE-00B4D8?style=for-the-badge&labelColor=010d12"/></a>
<a href="#"><img src="https://img.shields.io/badge/%E2%96%B2+AI+ENGINE-IN+DEVELOPMENT-005f73?style=for-the-badge&labelColor=010d12"/></a>

<br/><br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

</div>

---

<div align="center">

## `◈` Overview

</div>

<div align="center">

**Syzaar+** is a next-generation workforce performance and productivity analytics platform designed for industrial and manufacturing environments. The platform converts raw visual data captured from IP camera infrastructure into structured, actionable business intelligence — enabling facility managers to optimize workforce activity, reduce operational inefficiencies, and uphold quality standards.

The user interface and experience layer are fully developed and production-ready. The AI-powered detection engine — built on computer vision and deep learning technologies — is currently under active development and will be progressively integrated into the platform.

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

<div align="center">

## `◈` Core Features

<small>

| <sub>`▶` Feature</sub> | <sub>Description</sub> | <sub>Status</sub> |
|:----------------------:|:----------------------:|:-----------------:|
| <sub>Zone Management</sub> | <sub>Define, configure, and manage work zones via drag-and-drop. Isolate analysis to areas of operational significance.</sub> | <sub>✅ Complete</sub> |
| <sub>AI Activity Recognition</sub> | <sub>Detect active versus idle workforce states and flag anomalies in real time using advanced computer vision algorithms.</sub> | <sub>⏳ In Development</sub> |
| <sub>Multi-Camera Integration</sub> | <sub>Native support for up to 10 simultaneous IP camera streams with automatic device discovery and unified monitoring.</sub> | <sub>✅ Complete</sub> |
| <sub>Per-Zone AI Models</sub> | <sub>Assign dedicated, fine-tuned AI models to individual zones for maximum detection accuracy across diverse tasks.</sub> | <sub>⏳ In Development</sub> |
| <sub>Data & Reporting</sub> | <sub>Capture frame-by-frame performance data and export comprehensive reports in Excel and standard formats.</sub> | <sub>✅ Complete</sub> |
| <sub>Modern UI/UX</sub> | <sub>A fully responsive, dynamic interface with live visual labeling and at-a-glance operational insights.</sub> | <sub>✅ Complete</sub> |

</small>

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

<div align="center">

## `◈` Technology Stack

| <sub>Layer</sub> | <sub>Technologies</sub> |
|:----------------:|:-----------------------:|
| <sub>**Backend**</sub> | <sub>Python 3.12 · Django 5.0</sub> |
| <sub>**Frontend**</sub> | <sub>HTML5 · CSS3 · JavaScript</sub> |
| <sub>**Database**</sub> | <sub>SQLite 3 (Development) · PostgreSQL (Production)</sub> |
| <sub>**Computer Vision**</sub> | <sub>OpenCV 4.8</sub> |
| <sub>**AI / ML**</sub> | <sub>TensorFlow / PyTorch *(Planned)*</sub> |

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

<div align="center">

## `◈` Screenshots

<img src="Project_Picture/Image%20(2).png" width="80%"/>

*`▶` Zone Configuration Interface — drag-and-drop zone definition*

<br/>

<img src="Project_Picture/Image%20(7).png" width="80%"/>

*`▶` Dashboard Overview — live operational insights and activity monitoring*

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

## `◈` Project Structure

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=13&duration=3000&pause=999999&color=00B4D8&center=false&vCenter=true&width=480&height=28&lines=%E2%96%B6+Repository+layout+%E2%80%94+Syzaar%2B"/>

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

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

## `◈` Installation

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=13&duration=3000&pause=999999&color=00B4D8&center=false&vCenter=true&width=480&height=28&lines=%E2%96%B6+Prerequisites%3A+Python+3.12+or+higher+%C2%B7+Git"/>

![Step](https://img.shields.io/badge/01-Clone_the_Repository-00B4D8?style=flat-square&labelColor=010d12)

```bash
git clone https://github.com/Amin-Moniry/syzaar-plus.git
cd syzaar-plus
```

![Step](https://img.shields.io/badge/02-Create_Virtual_Environment-00B4D8?style=flat-square&labelColor=010d12)

**Windows**
```bash
python -m venv venv
.\venv\Scripts\activate
```
**macOS / Linux**
```bash
python3 -m venv venv
source venv/bin/activate
```

![Step](https://img.shields.io/badge/03-Install_Dependencies-00B4D8?style=flat-square&labelColor=010d12)

```bash
pip install -r requirements.txt
```

![Step](https://img.shields.io/badge/04-Apply_Migrations-00B4D8?style=flat-square&labelColor=010d12)

```bash
python manage.py makemigrations
python manage.py migrate
```

![Step](https://img.shields.io/badge/05-Create_Superuser-00B4D8?style=flat-square&labelColor=010d12)

```bash
python manage.py createsuperuser
```

![Step](https://img.shields.io/badge/06-Start_Dev_Server-00B4D8?style=flat-square&labelColor=010d12)

```bash
python manage.py runserver
```

The application will be available at `http://127.0.0.1:8000/`

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

## `◈` Usage

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=13&duration=3000&pause=999999&color=00B4D8&center=false&vCenter=true&width=520&height=28&lines=%E2%96%B6+Access+%C2%B7+Configure+%C2%B7+Monitor"/>

1. Navigate to `http://127.0.0.1:8000/` and log in with your superuser credentials.
2. Access the admin panel at `http://127.0.0.1:8000/admin/` for camera and zone configuration.
3. Use the dashboard to monitor operational zones, review activity data, and generate reports.

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

## `◈` Roadmap

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=13&duration=3000&pause=999999&color=00B4D8&center=false&vCenter=true&width=460&height=28&lines=%E2%96%B6+Planned+for+upcoming+versions"/>

- [ ] AI-powered workforce activity recognition
- [ ] Dedicated AI model assignment per zone
- [ ] Enhanced real-time analytics engine
- [ ] Advanced reporting and export features
- [ ] Mobile application support
- [ ] Third-party system integrations

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

## `◈` Contributing

1. Fork the repository via the **Fork** button on GitHub.
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit with a descriptive message: `git commit -m "Add: brief description"`
4. Push to your fork: `git push origin feature/your-feature-name`
5. Open a **Pull Request** against the `master` branch with a clear description of the changes.

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

<div align="center">

## `◈` License

This project is distributed under the **MIT License**.

See the [LICENSE](LICENSE) file for full details.

`©` 2026 Amin Moniry (AminTivanix2) — All Rights Reserved

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

<div align="center">

## `◈` Contact

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=14&duration=2000&pause=400&color=00B4D8&center=true&vCenter=true&width=500&height=30&lines=%E2%96%B6+Reach+out+through+any+channel+below"/>

<br/>

[![Issues](https://img.shields.io/badge/◈_ISSUES-Bug%20Report-005f73?style=for-the-badge&labelColor=010d12&logo=githubactions&logoColor=00B4D8)](https://github.com/Amin-Moniry/syzaar-plus/issues)

[![GitHub](https://img.shields.io/badge/◈_GITHUB-Amin--Moniry-00B4D8?style=for-the-badge&labelColor=010d12&logo=github&logoColor=00B4D8)](https://github.com/Amin-Moniry)

[![Website](https://img.shields.io/badge/◈_WEBSITE-allin1wrench.ir-00B4D8?style=for-the-badge&labelColor=010d12&logo=firefox&logoColor=00B4D8)](https://allin1wrench.ir)

[![Telegram](https://img.shields.io/badge/◈_TELEGRAM-@amintivanix2-00B4D8?style=for-the-badge&labelColor=010d12&logo=telegram&logoColor=00B4D8)](https://t.me/amintivanix2)

[![Email](https://img.shields.io/badge/◈_EMAIL-amintivanix2%40gmail.com-00B4D8?style=for-the-badge&labelColor=010d12&logo=gmail&logoColor=00B4D8)](mailto:amintivanix2@gmail.com)

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<div align="center">

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&weight=700&size=16&duration=3500&pause=900&color=00B4D8&center=true&vCenter=true&width=700&height=40&lines=%E2%96%B6+Engineered+by+Amin+Moniry+%28AminTivanix2%29;%E2%97%8F+Transforming+Industrial+Operations+Through+AI;%E2%96%B6+Smart+%C2%B7+Scalable+%C2%B7+Reliable"/>

<br/>

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:010d12,50:00B4D8,100:010d12&height=160&section=footer&text=Thanks%20For%20Visiting&fontSize=32&fontAlign=50&fontAlignY=55&fontColor=ffffff&animation=fadeIn" width="100%"/>

</div>
