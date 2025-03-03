# ChatBot

# 🚀 Backend & Semantic Search Implementation  

## 📌 Overview  
This project implements a **scalable backend** with **semantic search capabilities** for user profile retrieval. It leverages **Django** for API development, **Pinecone** for vector-based search, and is deployed on **AWS EC2 and Vercel** for a robust, production-ready environment.  

## 🔧 Technologies Used  
### Backend  
- **Django & Django REST Framework (DRF)** – API development  
- **PostgreSQL** – Database storage  
- **Redis** – Caching  
- **Celery** – Background task processing  
- **Pinecone** – Vector database for semantic search  
- **Langchain & OpenAI Embeddings** – NLP-based query handling  

### Frontend  
- **React.js** – User interface development  
- **Vercel** – Frontend deployment  

### Deployment  
- **AWS EC2** – Backend hosting  
- **Vercel** – Frontend hosting  
- **Docker** – Containerization  

## ⚡ Features  
- **Optimized Database Schema**: Denormalized schema for reduced query latency  
- **Semantic Search Integration**: Uses **Pinecone** for efficient vector-based retrieval  
- **REST API**: Exposes endpoints for CRUD operations and advanced search queries  
- **Scalability**: Supports large-scale data retrieval with minimal latency  
- **Authentication & Authorization**: Secure API access with JWT-based authentication  
- **Asynchronous Task Processing**: Celery for handling background tasks efficiently  

## 🛠️ Setup Instructions  
### Prerequisites  
- Python (>=3.9)  
- PostgreSQL  
- Redis  
- Node.js (for frontend)  
- Docker (optional for containerization)  

### Backend Setup  
1. Clone the repository  
2. Set up a virtual environment and install dependencies  
3. Configure environment variables for database and API keys  
4. Run migrations and start the Django server  

### Frontend Setup  
1. Navigate to the frontend directory  
2. Install dependencies using npm/yarn  
3. Start the development server  

## 🚀 Deployment  
- Backend: **AWS EC2 with Docker**  
- Frontend: **Vercel**  
- Database: **PostgreSQL** hosted on AWS RDS  
- Vector Storage: **Pinecone**  



## 📌 Future Enhancements  
- Implement **real-time search ranking**  
- Add **multi-language support** for semantic queries  
- Optimize indexing strategy for larger datasets  

---
