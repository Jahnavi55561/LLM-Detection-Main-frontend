# LLM Hallucination Detection & Correction Framework — Frontend

A web-based frontend for the **LLM Hallucination Detection & Correction Framework**, designed to analyze text, identify potentially unsupported or contradicted statements, and display verification results through a user-friendly interface.

## 🚀 Features

- **Text Analysis:** Submit text for hallucination detection and verification.
- **Sentence-Level Results:** View individual sentence analysis and verification status.
- **Evidence-Based Verification:** Display supporting evidence when provided by the backend.
- **Hallucination Correction:** Present corrected or improved text when supported by the backend.
- **AI Chatbot:** Interact with the application's chatbot.
- **Analysis History:** View previous analysis results when supported by the backend.
- **Statistics Dashboard:** Display analysis statistics and result summaries.
- **Responsive UI:** Access the interface from desktop and mobile browsers.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- REST API integration
- Vercel for frontend deployment
- Render for backend hosting

## 📁 Project Structure

```text
frontend-vercel/
├── index.html
├── style.css
├── script.js
└── README.md
```

## ⚙️ Backend Configuration

The frontend communicates with the backend through HTTP API requests.

Backend URL:

`https://llm-detection-main.onrender.com`

The API base URL is configured in `script.js`.

Make sure the backend is running, the API endpoints match the frontend requests, and CORS allows requests from the deployed frontend domain.

## 🌐 Deployment on Vercel

1. Upload the frontend files to a GitHub repository.
2. Sign in to [Vercel](https://vercel.com/).
3. Select **Add New Project**.
4. Import the frontend GitHub repository.
5. Choose **Other** as the framework preset, if prompted.
6. Deploy the project.
7. Open the generated Vercel URL and test the application.

No frontend build step is required for this plain HTML, CSS, and JavaScript setup.

## 🧪 Testing

Test the deployed application with:

- A factual paragraph.
- A paragraph containing an incorrect claim.
- Multiple sentences with a mixture of correct and incorrect claims.
- A chatbot question.
- Analysis history, if available.

Verify that the frontend displays the backend responses correctly.

## 🔒 Notes

- Do not put API keys, passwords, or other secrets in frontend JavaScript.
- Keep the backend API URL updated if the backend address changes.
- The frontend depends on the backend for analysis and other server-side functionality.

## 👨‍💻 Project Information

**Project:** LLM Hallucination Detection & Correction Framework

**Frontend Hosting:** Vercel

**Backend Hosting:** Render

---

*This repository contains the frontend interface for the LLM Hallucination Detection & Correction Framework.*
