# InterviewAI 🎯
### AI-Powered Interview Preparation Platform

InterviewAI is an AI-powered interview preparation platform designed to help candidates prepare for job interviews through personalized interview strategies, resume analysis, and AI-generated interview questions.

The platform analyzes candidate information and job descriptions to generate relevant interview insights, helping users identify skill gaps and prepare more effectively.

---

## 🚀 Features

- **AI-Powered Interview Preparation:** Generate personalized interview preparation strategies using AI.
- **Resume Analysis:** Upload your PDF resume to provide context for interview preparation.
- **Quick Self-Description:** Generate an interview report without uploading a resume.
- **Job Description Analysis:** Customize interview preparation based on the target job description.
- **Interview Match Score:** Get an AI-generated assessment of your profile against the job requirements.
- **Technical Interview Questions:** Generate relevant technical questions for interview practice.
- **Skill Gap Identification:** Identify areas that may require improvement.
- **PDF Generation:** Generate and download interview preparation reports.
- **User Authentication:** Secure user registration and login functionality.
- **Interview History:** Access previously generated interview reports.

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- JavaScript
- CSS / SCSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Multer
- PDF Parsing

### AI Integration
- Google Gemini API
- Google GenAI SDK

### Tools & Platforms
- Git
- GitHub
- VS Code
- MongoDB Atlas

---

## 📂 Project Structure

```text
InterviewAI/
│
├── Backend/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   └── services/
│   │
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── Frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── index.html
│
├── .gitignore
└── README.md
```

---

## ⚙️ Installation & Setup

Follow these steps to run InterviewAI locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Shivangkishoreshukla/InterviewAI.git
```

### 2. Navigate to the Project

```bash
cd InterviewAI
```

### 3. Backend Setup

Navigate to the backend directory:

```bash
cd Backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file inside the Backend directory:

```env
PORT=3000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_GENAI_API_KEY=your_gemini_api_key
```

Add your own credentials. Never upload your `.env` file to GitHub.

Start the backend:

```bash
npm run dev
```

The backend should run at:

```text
http://localhost:3000
```

### 4. Frontend Setup

Open another terminal and navigate to the frontend directory:

```bash
cd InterviewAI/Frontend
```

Install dependencies:

```bash
npm install
```

Start the frontend:

```bash
npm run dev
```

Open the local URL provided by Vite, usually:

```text
http://localhost:5173
```

---

## 🔐 Environment Variables

The backend requires the following environment variables:

| Variable | Description |
|---|---|
| `PORT` | Backend server port |
| `MONGO_URI` | MongoDB Atlas connection string |
| `JWT_SECRET` | Secret used for JWT authentication |
| `GOOGLE_GENAI_API_KEY` | Google Gemini API key |

**Security Note:** Keep all API keys, database credentials, and secrets private. Use environment variables in production.

---

## 🧠 How It Works

1. Register or log in to the platform.
2. Upload your resume or provide a self-description.
3. Enter the target job description.
4. Submit the information for AI analysis.
5. InterviewAI processes the information using the AI service.
6. Receive a personalized interview preparation report.
7. Review technical questions and identified skill gaps.
8. Generate and download your interview report as a PDF.

---

## 📸 Screenshots

_Add screenshots of the application here._

Suggested screenshots:

- Dashboard
- Interview preparation form
- AI-generated interview report
- Technical questions and skill gaps
- Downloaded PDF report

---

## 🌐 Deployment

Deployment configuration:

| Component | Platform |
|---|---|
| Source Code | GitHub |
| Frontend | Vercel |
| Backend | Render |
| Database | MongoDB Atlas |

Deployment links will be added once the application is hosted.

---

## 🔮 Future Improvements

- AI-powered mock interview sessions.
- Voice-based interview practice.
- Real-time answer evaluation.
- Personalized learning recommendations.
- Interview performance analytics.
- Support for additional AI models.

---

## 👨‍💻 Author

**Shivang Kishore**

GitHub: [@Shivangkishoreshukla](https://github.com/Shivangkishoreshukla)

Project: [InterviewAI](https://github.com/Shivangkishoreshukla/InterviewAI)

---

## 📄 License

This project builds upon an existing codebase. Preserve the original license and required attribution. Check the repository's applicable license before redistributing or relicensing the project.