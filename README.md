🔹 Features
📊 Real-time monitoring of CPU, RAM, and disk usage
🐳 Docker & Kubernetes tracking (active containers, logs)
📡 Database health check (PostgreSQL, MongoDB, MySQL)
🔔 Custom alerts for performance thresholds
📈 Interactive charts for system analytics
🔧 Tech Stack

Frontend
⚛️ React (UI)
🎨 Tailwind CSS (Styling)
📊 Recharts (Data visualization)

Backend
🐍 Django REST Framework (API)
⚡ Flask (Microservices)
🟠 Celery + Redis (Task scheduling)

DevOps & Databases
🐳 Docker (Containerization)
☸️ Kubernetes (Orchestration)
🛢️ PostgreSQL, MongoDB, MySQL (Databases)
🚀 Getting Started
1️⃣ Clone the Repository

git clone https://github.com/your-username/InfraMonitor.git  
cd InfraMonitor  

2️⃣ Run the Backend

cd backend  
python -m venv env  
source env/bin/activate  # Windows: env\Scripts\activate  
pip install -r requirements.txt  
python manage.py migrate  
python manage.py runserver  

3️⃣ Run the Frontend

cd frontend  
npm install  
npm start  

4️⃣ Run with Docker (Optional)

docker-compose up --build  

📡 Future Enhancements
✅ Multi-user authentication for secure dashboard access
✅ Grafana integration for advanced visualizations
✅ Support for AWS/GCP cloud monitoring
