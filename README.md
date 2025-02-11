# Datalytics

## 🫥 REMINDER!
For the initial version of this project, I'll be using a disengaged monolithic structure. For future versions and references, we'll switch it to a microservices architecture (Initially on backend and maybe on frontend).

## 📌 Project Justification
Datalytics is a data analytics platform with Machine Learning that allows users to upload datasets, perform exploratory analysis, and apply predictive models. Its goal is to facilitate data-driven decision-making through interactive and visual tools.

## 📜 User Stories

### 1️⃣ Data Upload and Preprocessing
**As a user**, I want to upload datasets in CSV, Excel, and JSON formats for analysis on the platform.
**Acceptance Criteria:**
- Support for multiple file formats.
- Automatic verification of data structure.
- Dataset preview before uploading.

### 2️⃣ Interactive Data Visualization
**As a data analyst**, I want to visualize my data using interactive charts to detect patterns.
**Acceptance Criteria:**
- Support for bar, line, scatter, and boxplot charts.
- Dynamic filters to adjust visualizations.
- Download charts in PNG and SVG formats.

### 3️⃣ Application of Machine Learning Models
**As a data scientist**, I want to train Machine Learning models on my datasets.
**Acceptance Criteria:**
- Support for regression, classification, and clustering models.
- Model performance evaluation with key metrics.
- Export trained models in pickle format.

## 📌 Functional Requirements
✅ User authentication with JWT.
✅ Dataset upload and preprocessing.
✅ Interactive data visualization.
✅ Implementation of Machine Learning models.
✅ REST/GraphQL API for frontend-backend communication.
✅ Storage in PostgreSQL and MongoDB databases.
✅ Cloud deployment with AWS/GCP using Docker and Kubernetes.

## 🚫 Non-Functional Requirements
✅ Security with authentication and authorization.
✅ Scalability for multiple concurrent users.
✅ Performance optimization for data processing.
✅ Support for deployment in multiple environments.

## 🖥️ Web App Screens
1. **Login / Register** (User authentication).
2. **Main Dashboard** (Panel summarizing uploaded data and trained models).
3. **Data Upload** (Interface for uploading and previewing datasets).
4. **Exploratory Analysis** (Charts and statistical visualization).
5. **Model Training** (Selection and configuration of ML models).
6. **Results and Predictions** (Model deployment and prediction generation).
7. **Analysis History** (List of previously used datasets and models).

## 🎨 UI/UX Design
- **Primary Colors:** Blue (#1E90FF), White (#FFFFFF), Dark Gray (#333333)
- **Typography:** Roboto / Open Sans
- **Minimalist design** focused on accessibility.

## 📅 Development Roadmap
1️⃣ **Week 1-2:** UI/UX design and system architecture.
2️⃣ **Week 3-4:** Backend development with authentication and data upload.
3️⃣ **Week 5-6:** Frontend implementation and data visualization.
4️⃣ **Week 7-8:** ML model integration and optimization.
5️⃣ **Week 9:** Testing and cloud deployment.
---

# Datalytics - Documentation

## 📌 Overview
Datalytics is a web-based data analytics platform that enables users to upload datasets, explore data visually, and apply Machine Learning models. The platform is designed to support data-driven decision-making with a user-friendly interface and powerful backend processing.

## 🚀 Features
- **Dataset Upload:** Support for CSV, Excel, and JSON.
- **Exploratory Data Analysis (EDA):** Interactive visualizations and statistical insights.
- **Machine Learning Model Training:** Regression, classification, and clustering models.
- **Predictions & Results:** Real-time inference and model evaluation.
- **Cloud Deployment:** Scalable architecture using Docker, Kubernetes, and AWS/GCP.

## 📜 Technology Stack
### Backend:
- **Frameworks:** Django, Flask, FastAPI
- **Database:** PostgreSQL, MongoDB, Redis
- **Authentication:** JWT
- **API:** REST/GraphQL

### Frontend:
- **Frameworks:** React.js, Next.js, TailwindCSS
- **State Management:** Redux, Zustand

### Infrastructure:
- **Containers:** Docker
- **Orchestration:** Kubernetes
- **Monitoring:** Grafana, Kibana
- **Deployment:** AWS/GCP

## 🖥️ System Architecture
Datalytics follows a **microservices-based** architecture, ensuring scalability and modularity. The platform consists of:
- **Frontend Service:** React.js + Next.js for UI.
- **Backend Service:** Django/Flask API handling requests and processing data.
- **Machine Learning Service:** Python-based ML model training and inference.
- **Database Layer:** PostgreSQL for structured data, MongoDB for NoSQL needs.
- **Storage Layer:** AWS S3/GCP Cloud Storage for dataset management.
- **Authentication:** JWT-based secure access.

## 📅 Project Structure
```
datalytics/
│── backend/                # Backend with Django/Flask
│   ├── api/                # Business logic and models
│   ├── auth/               # JWT Authentication
│   ├── data_processing/    # Data preprocessing
│   ├── ml_models/          # Machine Learning models
│   ├── database/           # PostgreSQL and MongoDB configuration
│   ├── Dockerfile          # Backend Dockerfile
│   ├── requirements.txt    # Python dependencies
│   ├── main.py             # Main application file (Flask/FastAPI)
│   ├── config.py           # Project configuration
│   └── tests/              # Unit tests
│
│── frontend/               # Frontend with Next.js (React)
│   ├── components/         # Reusable components
│   ├── pages/              # Frontend pages
│   ├── styles/             # Styling with TailwindCSS
│   ├── services/           # API calls
│   ├── public/             # Static assets
│   ├── Dockerfile          # Frontend Dockerfile
│   ├── package.json        # React dependencies
│   ├── next.config.js      # Next.js configuration
│   ├── tailwind.config.js  # TailwindCSS configuration
│   └── tests/              # Frontend tests
│
│── deployment/             # Deployment configuration
│   ├── docker-compose.yml  # Docker orchestration
│   ├── k8s/                # Kubernetes files
│   ├── nginx.conf          # Nginx configuration
│   ├── aws/                # AWS infrastructure
│   ├── gcp/                # GCP infrastructure
│   └── ci-cd/              # CI/CD pipelines
│
└── README.md               # Documentation
```

## 🔥 Setup & Installation
### Prerequisites:
- Node.js & npm/yarn
- Python 3.x & pip
- PostgreSQL & MongoDB
- Docker & Kubernetes

### Backend Setup
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

### Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

### Running with Docker
```bash
docker-compose up --build
```

## 🤝 Contribution Guidelines
- Fork the repository.
- Create a feature branch (`git checkout -b feature-name`).
- Commit your changes (`git commit -m 'Add feature XYZ'`).
- Push the branch (`git push origin feature-name`).
- Create a pull request.

## 📜 License
This project is open-source under the MIT License.

## 📞 Contact
For queries, open an issue or reach out to the maintainers.

---