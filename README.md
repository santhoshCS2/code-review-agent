# AI Code Review Agent

A full-stack application that provides AI-powered code review capabilities with vulnerability detection and fix suggestions.

## 🚀 Features

- **AI-Powered Code Analysis**: Advanced code review using AI models
- **Vulnerability Detection**: Identifies security issues and potential bugs
- **Fix Suggestions**: Provides intelligent code improvement recommendations
- **Modern UI**: Clean React-based frontend interface
- **Fast API Backend**: High-performance Python backend

## 🏗️ Architecture

```
├── backend/          # FastAPI Python backend
│   ├── app/
│   │   ├── models/   # Data models and schemas
│   │   ├── services/ # Business logic services
│   │   ├── utils/    # Utility functions
│   │   └── main.py   # FastAPI application
│   └── requirements.txt
├── frontend/         # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── styles/
│   └── package.json
└── README.md
```

## 🛠️ Tech Stack

### Backend
- **FastAPI** - Modern Python web framework
- **SQLite** - Database
- **Pydantic** - Data validation
- **AI Integration** - Code analysis capabilities

### Frontend
- **React** - UI framework
- **Vite** - Build tool
- **CSS3** - Styling

## 🚀 Quick Start

### Backend Setup
```bash
cd backend
pip install -r requirements.txt
python -m uvicorn app.main:app --reload
```

### Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

## 📝 API Endpoints

- `POST /upload` - Upload code for review
- `GET /report/{id}` - Get analysis report
- `POST /fix` - Get fix suggestions

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.