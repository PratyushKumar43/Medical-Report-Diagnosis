# 🏥 Medical Report Diagnosis System# 🏥 Medical Report Diagnosis System



[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/downloads/)![Medical Diagnosis Banner](/assets/thumbnail.png)

[![FastAPI](https://img.shields.io/badge/FastAPI-0.104+-green.svg)](https://fastapi.tiangolo.com/)

[![MongoDB](https://img.shields.io/badge/MongoDB-6.0+-brightgreen.svg)](https://www.mongodb.com/)A comprehensive **AI-powered medical diagnosis platform** built with FastAPI that enables healthcare professionals to upload medical reports, extract insights using advanced AI, and generate accurate diagnoses through intelligent document analysis and retrieval-augmented generation (RAG).

[![Streamlit](https://img.shields.io/badge/Streamlit-1.28+-red.svg)](https://streamlit.io/)

---

An intelligent **AI-powered medical diagnosis platform** that leverages advanced machine learning and natural language processing to analyze medical reports and provide accurate diagnostic insights. Built with FastAPI backend, MongoDB database, and Streamlit frontend for seamless healthcare document analysis.

## 📸 Application Screenshots

---

| Feature                                   | Screenshot                                          |

## 🎯 Overview| ----------------------------------------- | --------------------------------------------------- |

| **Home Page**                             | ![Home Screenshot](/assets/homepage.png)            |

This comprehensive medical diagnosis system combines the power of artificial intelligence with modern web technologies to assist healthcare professionals in analyzing medical reports. The platform uses **Retrieval-Augmented Generation (RAG)** with **LLaMA 3** through Groq API to provide contextually accurate medical diagnoses based on uploaded PDF reports.| **Patient Dashboard - Report Upload**    | ![Upload Screenshot](/assets/patientDashboard.png)  |

| **Doctor Dashboard - Diagnosis View**    | ![Diagnosis Screenshot](/assets/doctorDahboard.png) |

### Key Highlights

- 🤖 **AI-Powered Diagnosis** using state-of-the-art LLM technology📄 **Sample PDF Report:** [Download Sample Report](/assets/sample-report.pdf)

- 🔐 **Secure Role-Based Access** for doctors and patients

- 📄 **Advanced PDF Processing** with text extraction and chunking📄 **Project Documentation:** [View Project Report](/assets/ProjectReport.pdf)

- 🔍 **Vector Search** capabilities with Pinecone integration

- 📊 **Comprehensive Dashboard** for report management📊 **Application Flow Diagram:** [View Flow](/assets/applicationFlow.png)

- 🏥 **Healthcare-Focused** design and workflow

🧠 **RAG Architecture Diagram:** [View RAG System](/assets/RAGDiagram.png)

---

---

## 🚀 Core Features

## 🚀 Core Features

✅ **Role-based Authentication** (Doctor / Patient)

✅ **Role-based Authentication** (Doctor / Patient)

✅ **PDF Report Upload** with secure file handling

✅ **PDF Report Upload** with secure file handling

✅ **Text Extraction & Chunking** from PDFs using advanced parsing

✅ **Text Extraction & Chunking** from PDFs using advanced parsing

✅ **AI Diagnosis Generation** using **Groq LLaMA 3** integration

✅ **AI Diagnosis Generation** using **Groq LLaMA 3** integration

✅ **Vector Storage with Pinecone** for RAG retrieval and semantic search

✅ **Vector Storage with Pinecone** for RAG retrieval and semantic search

✅ **MongoDB Integration** for user, report, and diagnosis records management

✅ **MongoDB Integration** for user, report, and diagnosis records management

✅ **Role-based Access Control** for viewing and requesting diagnoses

✅ **Role-based Access Control** for viewing and requesting diagnoses

✅ **Real-time Processing** with progress tracking and notifications

✅ **Real-time Report Processing** with progress tracking

✅ **Medical History Management** for comprehensive patient care tracking

✅ **Medical History Management** for comprehensive patient care

✅ **Secure File Storage** with organized directory structure and encryption

✅ **Secure File Storage** with organized directory structure

---

---

## 🛠 Tech Stack

## 🛠 Tech Stack

### Backend

- **Framework:** FastAPI (Python)- **Backend Framework:** FastAPI

- **Database:** MongoDB (Document Storage)- **Database:** MongoDB (Document Storage)

- **Vector DB:** Pinecone (Semantic Search & RAG)- **Vector Database:** Pinecone (Semantic Search & RAG)

- **AI/LLM:** Groq API (LLaMA 3 Model)- **AI/LLM Integration:** Groq API (LLaMA 3 Model)

- **Authentication:** JWT Token-based Security- **PDF Processing:** PyPDF2 (Text Extraction)

- **Authentication:** JWT Token-based Authentication

### Frontend- **File Handling:** Secure upload and storage system

- **Framework:** Streamlit- **Environment Management:** Python 3.10+

- **UI Components:** Custom healthcare-focused interface- **Frontend:** Streamlit (Client Application)

- **File Upload:** Drag-and-drop PDF support

---

### Processing & AI

- **PDF Processing:** PyPDF2 (Text Extraction)## 📂 Project Structure

- **Text Processing:** Advanced chunking and preprocessing

- **Vector Embeddings:** Semantic text representation```

- **RAG System:** Contextual information retrievalMedical-Diagnosis/

├── assets/                          # Static assets and documentation

### Infrastructure│   ├── applicationFlow.png          # Application workflow diagram

- **Environment:** Python 3.10+│   ├── coreModules.png             # Core modules architecture

- **File Storage:** Secure local storage with UUID naming│   ├── doctorDahboard.png          # Doctor dashboard screenshot

- **API Documentation:** OpenAPI/Swagger integration│   ├── homepage.png                # Homepage screenshot

│   ├── patientDashboard.png        # Patient dashboard screenshot

---│   ├── ProjectReport.pdf           # Comprehensive project report

│   ├── RAGDiagram.png              # RAG system architecture

## 📂 Project Structure│   ├── report1.pdf                 # Sample medical report 1

│   ├── sample-report.pdf           # Sample medical report 2

```│   └── thumbnail.png               # Project thumbnail

Medical-Diagnosis/├── client/                         # Frontend Streamlit application

├── 📁 assets/                          # Static assets and documentation│   ├── app.py                      # Main Streamlit application

│   ├── 🖼️ applicationFlow.png           # Application workflow diagram│   └── requirements.txt            # Client dependencies

│   ├── 🖼️ coreModules.png              # System architecture overview├── server/                         # FastAPI backend server

│   ├── 🖼️ doctorDahboard.png           # Doctor dashboard interface│   ├── main.py                     # Main FastAPI application entry point

│   ├── 🖼️ homepage.png                 # Application homepage│   ├── auth/                       # Authentication module

│   ├── 🖼️ patientDashboard.png         # Patient portal interface│   │   ├── hash_utils.py          # Password hashing utilities

│   ├── 📋 ProjectReport.pdf            # Comprehensive project documentation│   │   ├── models.py              # Authentication data models

│   ├── 🖼️ RAGDiagram.png               # RAG system architecture│   │   └── route.py               # Authentication API routes

│   ├── 📄 report1.pdf                  # Sample medical report│   ├── config/                     # Configuration settings

│   ├── 📄 sample-report.pdf            # Demo medical document│   │   └── db.py                  # Database connection configuration

│   └── 🖼️ thumbnail.png                # Project preview image│   ├── diagnosis/                  # AI diagnosis module

├── 📁 client/                          # Frontend Streamlit application│   │   ├── query.py               # LLM query processing

│   ├── 🐍 app.py                       # Main Streamlit application│   │   └── route.py               # Diagnosis API endpoints

│   └── 📋 requirements.txt             # Frontend dependencies│   ├── models/                     # Database models

├── 📁 server/                          # FastAPI backend server│   │   └── db_models.py           # MongoDB document schemas

│   ├── 🐍 main.py                      # FastAPI application entry point│   └── reports/                    # Report management module

│   ├── 📁 auth/                        # Authentication & authorization│       ├── route.py               # Report upload/management APIs

│   │   ├── 🐍 hash_utils.py            # Password hashing utilities│       └── vectorstore.py         # Pinecone vector operations

│   │   ├── 🐍 models.py                # Auth data models & schemas├── uploaded_dir/                   # Secure file storage directory

│   │   └── 🐍 route.py                 # Authentication API endpoints│   ├── 62716efb-ed47-4952-a8a4-647d97c88440_sample-report.pdf

│   ├── 📁 config/                      # System configuration│   └── 7ef28b5f-90f7-4c70-b669-14c6e275e640_report1.pdf

│   │   └── 🐍 db.py                    # Database connection setup├── main.py                        # Project main entry point

│   ├── 📁 diagnosis/                   # AI diagnosis processing├── pyproject.toml                 # Project configuration

│   │   ├── 🐍 query.py                 # LLM query processing logic├── requirements.txt               # Python dependencies

│   │   └── 🐍 route.py                 # Diagnosis API endpoints└── README.md                      # Project documentation

│   ├── 📁 models/                      # Database models

│   │   └── 🐍 db_models.py             # MongoDB document schemas```

│   └── 📁 reports/                     # Report management system

│       ├── 🐍 route.py                 # Report upload/management APIs---

│       └── 🐍 vectorstore.py           # Pinecone vector operations

├── 📁 uploaded_dir/                    # Secure file storage## ⚙️ Setup Instructions (Local Development)

│   ├── 📄 62716efb-...sample-report.pdf  # Uploaded medical reports

│   └── 📄 7ef28b5f-...report1.pdf        # (UUID-named for security)### 1️⃣ Clone the Repository

├── 🐍 main.py                          # Project main entry point

├── ⚙️ pyproject.toml                   # Project configuration & metadata```bash

├── 📋 requirements.txt                 # Python dependenciesgit clone <your-repository-url>

└── 📖 README.md                        # This documentation filecd Medical-Diagnosis

``````



---### 2️⃣ Create Virtual Environment



## ⚡ Quick Start```bash

python -m venv venv

### Prerequisitessource venv/bin/activate   # On Linux/Mac

- Python 3.10 or highervenv\Scripts\activate      # On Windows

- MongoDB instance (local or cloud)```

- Pinecone account and API key

- Groq API key for LLaMA 3 access### 3️⃣ Install Dependencies



### 1️⃣ Clone Repository```bash

pip install -r requirements.txt

```bash```

git clone <your-repository-url>

cd Medical-Diagnosis### 4️⃣ Configure Environment Variables

```

Create a `.env` file in the root directory and add the following configuration:

### 2️⃣ Environment Setup

```env

```bash# Database Configuration

# Create virtual environmentMONGO_URI=mongodb://localhost:27017/

python -m venv venvDB_NAME=medical_diagnosis



# Activate environment# Pinecone Vector Database

# On Windows:PINECONE_API_KEY=your_pinecone_api_key

venv\Scripts\activatePINECONE_INDEX_NAME=medical-reports

# On macOS/Linux:PINECONE_ENV=your_pinecone_environment

source venv/bin/activate

```# AI/LLM Configuration

GOOGLE_API_KEY=your_google_api_key

### 3️⃣ Install DependenciesGROQ_API_KEY=your_groq_api_key



```bash# File Upload Configuration

pip install -r requirements.txtUPLOAD_DIR=./uploaded_dir

```API_URL=http://localhost:8000



### 4️⃣ Environment Configuration# Security

SECRET_KEY=your_secret_key_for_jwt

Create a `.env` file in the root directory:ALGORITHM=HS256

ACCESS_TOKEN_EXPIRE_MINUTES=30

```env```

# Database Configuration

MONGO_URI=mongodb://localhost:27017/### 5️⃣ Run the Backend Server

DB_NAME=medical_diagnosis

```bash

# Vector Database (Pinecone)uvicorn server.main:app --reload

PINECONE_API_KEY=your_pinecone_api_key_here```

PINECONE_INDEX_NAME=medical-reports-index

PINECONE_ENV=your_pinecone_environmentBackend API will be available at: **[http://127.0.0.1:8000](http://127.0.0.1:8000)**



# AI/LLM Services### 6️⃣ Run the Frontend Client (Optional)

GROQ_API_KEY=your_groq_api_key_here

GOOGLE_API_KEY=your_google_api_key_here```bash

cd client

# Application Settingsstreamlit run app.py

UPLOAD_DIR=./uploaded_dir```

API_URL=http://localhost:8000

Frontend application will be available at: **[http://localhost:8501](http://localhost:8501)**

# Security Configuration

SECRET_KEY=your-super-secret-jwt-key-here---

ALGORITHM=HS256

ACCESS_TOKEN_EXPIRE_MINUTES=30## ▶️ API Endpoints



# Optional: Additional Settings### Authentication Endpoints

DEBUG=True| Method | Endpoint           | Description                    | Auth Required |

LOG_LEVEL=INFO| ------ | ------------------ | ------------------------------ | ------------- |

MAX_FILE_SIZE=10485760  # 10MB in bytes| POST   | `/auth/signup`     | Register a new user            | No            |

```| POST   | `/auth/login`      | User authentication & token   | No            |

| GET    | `/auth/me`         | Get current user profile       | Yes           |

### 5️⃣ Launch Application

### Report Management Endpoints

#### Start Backend Server| Method | Endpoint              | Description                     | Auth Required |

```bash| ------ | --------------------- | ------------------------------- | ------------- |

uvicorn server.main:app --reload --host 0.0.0.0 --port 8000| POST   | `/reports/upload`     | Upload medical report (PDF)     | Yes           |

```| GET    | `/reports/list`       | Get user's uploaded reports     | Yes           |

| GET    | `/reports/{report_id}`| Get specific report details     | Yes           |

#### Start Frontend Client (New Terminal)| DELETE | `/reports/{report_id}`| Delete a medical report         | Yes           |

```bash

cd client### Diagnosis Endpoints

streamlit run app.py --server.port 8501| Method | Endpoint                      | Description                    | Auth Required |

```| ------ | ----------------------------- | ------------------------------ | ------------- |

| POST   | `/diagnosis/from_report`      | Generate AI diagnosis          | Yes (Doctor)  |

### 6️⃣ Access Application| GET    | `/diagnosis/by_patient_name`  | Get patient diagnosis history  | Yes (Doctor)  |

| GET    | `/diagnosis/my_diagnoses`     | Get user's diagnosis history   | Yes           |

- **Backend API:** [http://localhost:8000](http://localhost:8000)

- **API Documentation:** [http://localhost:8000/docs](http://localhost:8000/docs)### Health Check

- **Frontend Interface:** [http://localhost:8501](http://localhost:8501)| Method | Endpoint    | Description        | Auth Required |

| ------ | ----------- | ------------------ | ------------- |

---| GET    | `/health`   | API health check   | No            |

| GET    | `/docs`     | Interactive API docs| No            |

## 📡 API Reference

---

### 🔐 Authentication Endpoints

## 🏗️ System Architecture

| Method | Endpoint        | Description                | Request Body                    |

|--------|-----------------|----------------------------|---------------------------------|### Core Modules Overview

| POST   | `/auth/signup`  | Register new user          | `{username, email, password, role}` |![Core Modules](/assets/coreModules.png)

| POST   | `/auth/login`   | User login & get token     | `{username, password}`          |

| GET    | `/auth/profile` | Get current user info      | *Requires JWT token*            |### RAG (Retrieval-Augmented Generation) System

| PUT    | `/auth/profile` | Update user profile        | `{email, full_name, ...}`       |The application implements a sophisticated RAG system that:



### 📄 Report Management1. **Document Processing**: Extracts and chunks text from uploaded PDF reports

2. **Vector Embedding**: Creates semantic embeddings using advanced NLP models

| Method | Endpoint                | Description                | Access Level    |3. **Vector Storage**: Stores embeddings in Pinecone for efficient similarity search

|--------|-------------------------|----------------------------|-----------------|4. **Contextual Retrieval**: Finds relevant medical information for diagnosis queries

| POST   | `/reports/upload`       | Upload medical report PDF  | Patient/Doctor  |5. **AI Generation**: Uses retrieved context with LLaMA 3 to generate accurate diagnoses

| GET    | `/reports/`             | List user's reports        | Patient/Doctor  |

| GET    | `/reports/{report_id}`  | Get specific report        | Owner/Doctor    |### Application Workflow

| DELETE | `/reports/{report_id}`  | Delete report              | Owner only      |![Application Flow](/assets/applicationFlow.png)

| GET    | `/reports/search`       | Search reports by criteria| Doctor only     |

---

### 🧠 AI Diagnosis

## 🔮 Future Enhancements

| Method | Endpoint                     | Description                    | Access Level |

|--------|------------------------------|--------------------------------|--------------|- 🔐 **Enhanced JWT Authentication** with refresh tokens

| POST   | `/diagnosis/generate`        | Create AI diagnosis            | Doctor only  |- 📊 **Advanced Analytics Dashboard** for medical insights

| GET    | `/diagnosis/patient/{id}`    | Get patient's diagnoses        | Doctor only  |- 🖼️ **Multi-format Support** (Images, DICOM, X-rays)

| GET    | `/diagnosis/my-diagnoses`    | Get own diagnoses              | Patient      |- 🏥 **Hospital Integration** APIs

| PUT    | `/diagnosis/{diagnosis_id}`  | Update diagnosis               | Doctor only  |- 📱 **Mobile Application** development

| GET    | `/diagnosis/export/{id}`     | Export diagnosis report        | Owner/Doctor |- 🤖 **Multiple AI Model Support** (GPT-4, Claude, etc.)

- 📈 **Real-time Monitoring** and logging

### 🔧 System Endpoints- 🌐 **Multi-language Support** for global accessibility

- 🔍 **Advanced Search** and filtering capabilities

| Method | Endpoint     | Description              | Access Level |- 📋 **Report Templates** and standardization

|--------|--------------|--------------------------|--------------|

| GET    | `/health`    | System health check      | Public       |---

| GET    | `/stats`     | Application statistics   | Admin        |

| GET    | `/docs`      | API documentation        | Public       |## 🚨 Important Notes



---- Ensure all required environment variables are properly configured

- This system is designed for educational and research purposes

## 🏗️ System Architecture- Always validate AI-generated diagnoses with qualified medical professionals

- Maintain proper data privacy and HIPAA compliance in production environments

### RAG (Retrieval-Augmented Generation) Pipeline- Regular backups of MongoDB and vector databases are recommended



```mermaid---

graph TB

    A[PDF Upload] --> B[Text Extraction]## 📜 License

    B --> C[Text Chunking]

    C --> D[Vector Embedding]This project is licensed under the **MIT License**. See the LICENSE file for details.

    D --> E[Pinecone Storage]

    F[Diagnosis Query] --> G[Vector Search]---

    E --> G

    G --> H[Context Retrieval]## 🤝 Contributing

    H --> I[LLaMA 3 Generation]

    I --> J[Diagnosis Response]Contributions, issues, and feature requests are welcome! Feel free to check the issues page and submit pull requests.

```

---

### Application Workflow

## 📧 Support

1. **User Authentication:** Secure login with JWT tokens

2. **Report Upload:** PDF processing and text extractionFor technical support or questions about the project, please create an issue in the repository or refer to the project documentation.
3. **Vector Processing:** Text chunking and embedding generation
4. **Storage:** Documents stored in MongoDB, vectors in Pinecone
5. **Diagnosis Request:** Doctor initiates AI diagnosis
6. **RAG Processing:** Relevant context retrieval from vector store
7. **AI Generation:** LLaMA 3 generates diagnosis based on context
8. **Result Delivery:** Formatted diagnosis presented to user

---

## 🧪 Testing & Development

### Running Tests
```bash
# Install test dependencies
pip install pytest pytest-asyncio httpx

# Run all tests
pytest

# Run with coverage
pytest --cov=server tests/
```

### Development Mode
```bash
# Backend with auto-reload
uvicorn server.main:app --reload --log-level debug

# Frontend with auto-refresh
streamlit run client/app.py --server.runOnSave true
```

### Database Setup
```bash
# Start MongoDB (if using Docker)
docker run -d -p 27017:27017 --name mongodb mongo:latest

# Initialize database (optional)
python scripts/init_db.py
```

---

## 🔧 Configuration Options

### Environment Variables Reference

| Variable | Description | Required | Default |
|----------|-------------|----------|---------|
| `MONGO_URI` | MongoDB connection string | ✅ | - |
| `DB_NAME` | Database name | ✅ | - |
| `PINECONE_API_KEY` | Pinecone API key | ✅ | - |
| `GROQ_API_KEY` | Groq API key for LLaMA 3 | ✅ | - |
| `SECRET_KEY` | JWT signing key | ✅ | - |
| `UPLOAD_DIR` | File upload directory | ❌ | `./uploads` |
| `MAX_FILE_SIZE` | Max upload size (bytes) | ❌ | `10MB` |
| `DEBUG` | Debug mode | ❌ | `False` |

---

## 🚀 Deployment

### Docker Deployment
```bash
# Build image
docker build -t medical-diagnosis .

# Run container
docker run -p 8000:8000 --env-file .env medical-diagnosis
```

### Production Considerations
- Use environment-specific `.env` files
- Configure reverse proxy (nginx/Apache)
- Set up SSL certificates
- Implement proper logging and monitoring
- Regular database backups
- Security headers and CORS configuration

---

## 🛡️ Security Features

- **JWT Authentication:** Secure token-based authentication
- **Role-Based Access:** Doctor/Patient permission levels
- **File Upload Security:** Type validation and size limits
- **Data Encryption:** Sensitive data encryption at rest
- **API Rate Limiting:** Prevent abuse and DoS attacks
- **Input Validation:** Comprehensive request validation
- **HIPAA Compliance Ready:** Healthcare data protection standards

---

## 📊 Performance & Monitoring

### Metrics Tracked
- API response times
- File upload/processing duration
- Database query performance
- AI model inference latency
- User activity and engagement

### Optimization Features
- Asynchronous processing for large files
- Database indexing for fast queries
- Vector search optimization
- Caching for frequently accessed data
- Connection pooling for database efficiency

---

## 🔮 Future Roadmap

### Short-term (Next Release)
- [ ] **Enhanced UI/UX** with modern design system
- [ ] **Batch Report Processing** for multiple file uploads
- [ ] **Export Functionality** (PDF, Word, Excel)
- [ ] **Email Notifications** for diagnosis completion
- [ ] **Advanced Search** with filters and sorting

### Medium-term (3-6 months)
- [ ] **Multiple AI Models** (GPT-4, Claude, Gemini)
- [ ] **Image Analysis** for X-rays and scans
- [ ] **Mobile Application** (React Native/Flutter)
- [ ] **Real-time Collaboration** for medical teams
- [ ] **Integration APIs** for hospital systems

### Long-term (6+ months)
- [ ] **Machine Learning Pipeline** for custom model training
- [ ] **Telemedicine Integration** with video consultation
- [ ] **Multi-language Support** for global accessibility
- [ ] **Blockchain Integration** for secure record keeping
- [ ] **IoT Device Integration** for real-time health monitoring

---

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Development Guidelines
- Follow PEP 8 style guide for Python code
- Write comprehensive tests for new features
- Update documentation for API changes
- Use meaningful commit messages
- Test on multiple Python versions

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## ⚠️ Disclaimer

This application is designed for educational and research purposes. Always consult with qualified healthcare professionals for medical decisions. The AI-generated diagnoses should be used as supplementary information only and not as a replacement for professional medical advice.

---

## 📞 Support & Contact

- 🐛 **Bug Reports:** [Create an Issue](../../issues)
- 💡 **Feature Requests:** [Create an Issue](../../issues)
- 📖 **Documentation:** [Wiki Pages](../../wiki)
- 💬 **Discussions:** [GitHub Discussions](../../discussions)

---

<div align="center">

**Made with ❤️ for Healthcare Innovation**

*Empowering medical professionals with AI-driven diagnostic insights*

</div>