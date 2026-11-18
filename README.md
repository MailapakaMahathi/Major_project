\# 🚨 Real-Time Emergency Response System



A full-stack emergency response management platform designed to streamline emergency alert reporting, location tracking, and coordination between police, hospitals, and administrators.



\## 📌 Project Overview



The \*\*Real-Time Emergency Response System\*\* provides a centralized platform for receiving and managing emergency alerts. It enables users to submit SOS alerts with geographical coordinates and emergency details, while designated responders can monitor and manage alerts through role-based dashboards.



The system categorizes emergencies and provides relevant response information to support faster coordination and emergency management.



\## ✨ Key Features



\- \*\*Emergency SOS Alerts:\*\* Submit emergency alerts with device ID, geographical coordinates, message, and emergency type.

\- \*\*Emergency Classification:\*\* Categorizes alerts into medical, accident, attack, robbery, and general emergencies.

\- \*\*Role-Based Dashboards:\*\* Separate dashboards for Police, Hospital, and Admin users.

\- \*\*Location Tracking:\*\* Captures and updates geographical coordinates for emergency monitoring.

\- \*\*Smart Alert Routing:\*\* Provides response information based on emergency categories.

\- \*\*Live Alert Monitoring:\*\* View and manage emergency alerts through dedicated dashboards.

\- \*\*Alert Resolution:\*\* Allows responders to resolve alerts and record resolution details.

\- \*\*Proof Image Upload:\*\* Supports uploading photographic evidence while resolving alerts.

\- \*\*Distance Verification:\*\* Validates responder proximity within 200 metres during the API-based resolution process.

\- \*\*Interactive Maps:\*\* Uses map-based visualization to display geographical information.



\## 🛠️ Technology Stack



\### Frontend

\- React.js

\- JavaScript

\- HTML5

\- CSS3

\- Axios

\- React Router

\- Leaflet

\- React Leaflet

\- Chart.js



\### Backend

\- Python

\- Django

\- Django REST Framework

\- Django CORS Headers

\- GeoPy



\### Database

\- SQLite



\### Development Tools

\- Visual Studio Code

\- Git

\- GitHub

\- Node.js

\- npm



\## 📂 Project Structure



```text

MAJOR\_PROJECT/

│

├── backend/

│   ├── alerts/

│   │   ├── migrations/

│   │   ├── templates/

│   │   ├── models.py

│   │   ├── serializers.py

│   │   ├── views.py

│   │   ├── urls.py

│   │   └── admin.py

│   │

│   ├── backend/

│   │   ├── settings.py

│   │   ├── urls.py

│   │   ├── asgi.py

│   │   └── wsgi.py

│   │

│   ├── manage.py

│   └── requirements.txt

│

├── frontend/

│   ├── public/

│   ├── src/

│   │   ├── components/

│   │   ├── pages/

│   │   ├── App.js

│   │   ├── App.css

│   │   └── index.js

│   │

│   ├── package.json

│   └── package-lock.json

│

└── README.md

```



\## ⚙️ Installation and Setup



\### 1. Clone the Repository



```bash

git clone https://github.com/MailapakaMahathi/Major\_project.git

```



Navigate to the project directory:



```bash

cd Major\_project/MAJOR\_PROJECT

```



\### 2. Backend Setup



Navigate to the backend directory:



```bash

cd backend

```



Create a Python virtual environment:



```bash

python -m venv venv

```



Activate the virtual environment on Windows:



```bash

venv\\Scripts\\activate

```



Install the required dependencies:



```bash

pip install -r requirements.txt

```



Run database migrations:



```bash

python manage.py migrate

```



Create an administrator account:



```bash

python manage.py createsuperuser

```



Start the Django development server:



```bash

python manage.py runserver

```



Backend server:



`http://127.0.0.1:8000/`



\### 3. Frontend Setup



Open another terminal and navigate to the frontend directory:



```bash

cd frontend

```



Install the Node.js dependencies:



```bash

npm install

```



Start the React development server:



```bash

npm start

```



Frontend application:



`http://localhost:3000/`



\## 🔄 System Workflow



1\. An emergency alert is submitted with the device ID, location coordinates, message, and emergency category.

2\. The Django backend validates and stores the alert.

3\. The system assigns response information according to the emergency category.

4\. Police, hospital, and admin dashboards retrieve relevant alerts.

5\. Responders monitor emergency details and location information.

6\. Responders can resolve alerts, with the resolution API supporting distance verification and proof image uploads.



\## 👥 User Roles



| Role | Responsibilities |

|---|---|

| Admin | Monitor and manage all emergency alerts |

| Police | Monitor attack, robbery, and accident alerts |

| Hospital | Monitor medical and accident alerts |



\## 🔐 Security Notes



\- Configure Django's `SECRET\_KEY` using an environment variable.

\- Keep private credentials and environment files out of GitHub.

\- Use appropriate `ALLOWED\_HOSTS` and CORS settings for deployment.

\- Disable Django debug mode in production.

\- Configure authentication and access permissions appropriately before deployment.



\## 🚀 Future Enhancements



\- Real-time notifications for emergency responders.

\- GPS-based nearest responder identification.

\- Integration with ambulance and emergency service providers.

\- SMS and email alert notifications.

\- Advanced emergency analytics and reporting.

\- Enhanced authentication and role-based access control.



\## 👩‍💻 Author



\*\*Mailapaka Mahathi\*\*



GitHub: \[@MailapakaMahathi](https://github.com/MailapakaMahathi)



\---



⭐ If you find this project interesting, feel free to explore the repository and its implementation.



\*\*Developed as a Major Project.\*\*

