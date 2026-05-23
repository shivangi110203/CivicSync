# CivicSync

CivicSync is a full-stack civic engagement and issue resolution platform designed to bridge the communication gap between citizens and government authorities. The platform enables users to report civic issues such as potholes, garbage overflow, water leakages, road blockades, and electricity failures using geo-tagged locations and image uploads.

With features like real-time issue mapping, community participation, issue tracking, and emergency alerts, CivicSync promotes transparency, accountability, and faster civic problem resolution.

---

# Features

- Geo-tagged civic issue reporting
- Real-time Google Maps integration
- Community upvoting and commenting
- Issue lifecycle tracking (Open → Under Review → Resolved)
- Emergency alert notification system
- Government dashboard for issue management
- Responsive and user-friendly interface

---

# Tech Stack

## Frontend
- React.js
- Next.js
- Vite
- Material UI

## Backend
- Django
- Django REST Framework

## Database
- PostgreSQL

## APIs & Services
- Google Maps API
- Cloudinary

---

# How to Run the Project

## Frontend Setup

1. Navigate to the frontend directory:

```bash
cd Frontend
Install dependencies:
npm install
Start the frontend server:
npm run dev

Frontend will run on:

http://localhost:3000
Backend Setup
Navigate to the backend directory:
cd Backend
Create virtual environment:
python -m venv venv
Activate virtual environment:
Windows
venv\Scripts\activate
macOS/Linux
source venv/bin/activate
Install dependencies:
pip install -r requirements.txt
Navigate to Django project folder:
cd hack24
Apply migrations:
python manage.py migrate
Run backend server:
python manage.py runserver 8001

Backend will run on:

http://127.0.0.1:8001/
Admin Access

To create a Django admin superuser:

python manage.py createsuperuser

Then access admin panel at:

http://127.0.0.1:8001/admin/
Project Description

CivicSync transforms traditional civic complaint systems into an interactive, transparent, and community-driven platform. Citizens can submit complaints with images and precise GPS-based locations, while government officials can monitor, update, and resolve issues through a dedicated management dashboard.

The platform integrates Google Maps for real-time issue visualization and includes community engagement features such as upvoting and commenting to help prioritize critical problems. An emergency alert system further keeps citizens informed about road blockades, water supply disruptions, and other urgent public issues.

By combining modern web technologies with civic participation, CivicSync aims to create smarter, more responsive communities.

Contributors
Shivangi Sharma
