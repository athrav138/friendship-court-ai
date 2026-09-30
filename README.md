# ⚖️ Friendship Court AI

**An AI-powered virtual courtroom that turns silly friend arguments into entertaining cases!**

Friendship Court AI provides a fun, structured way to settle lighthearted debates among friends. Using advanced AI models, it steps in as an impartial judge to interrogate the parties, analyze the "evidence," pass a verdict, handle appeals, and even issue harmless, fun consequences for the losing side!

![Friendship Court AI Diagram](./Friendship%20Court%20Ai%20-%20Diagram.jpeg)

---

## ✨ Features

- **🏛️ Virtual Courtroom:** Settle arguments in a fun and structured AI-driven environment.
- **🤖 AI-Powered Questioning:** The AI Judge actively interrogates both sides to gather all the necessary facts.
- **🔍 Evidence Analysis:** Submit your side of the story and let the AI weigh the evidence before making a decision.
- **📜 Fair Verdicts:** Get an unbiased (and highly entertaining) verdict based on the arguments presented.
- **⚖️ Appeals System:** Unhappy with the verdict? File an appeal and see if the AI will reconsider its decision.
- **🎲 Harmless Consequences:** The losing party is assigned a fun, harmless consequence to officially settle the dispute.

## 🛠️ Tech Stack

### Frontend
- **Framework:** [Next.js (React)](https://nextjs.org/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Animations:** [Framer Motion](https://www.framer.com/motion/)
- **Icons:** [Lucide React](https://lucide.dev/)
- **Language:** TypeScript

### Backend
- **Framework:** [FastAPI](https://fastapi.tiangolo.com/) (Python)
- **AI Integration:** Google Generative AI (Gemini)
- **Data Validation:** Pydantic
- **Server:** Uvicorn

---

## 🚀 Getting Started

Follow these instructions to set up the project locally on your machine.

### Prerequisites

Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v18 or higher)
- [Python](https://www.python.org/) (v3.8 or higher)
- A Google Gemini API Key

### 1. Clone the repository

```bash
git clone https://github.com/athrav138/friendship-court-ai.git
cd friendship-court-ai
```

### 2. Backend Setup (FastAPI)

Navigate to the backend directory and set up the Python environment:

```bash
cd backend
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

**Environment Variables:**
Create a `.env` file in the `backend` directory and add your Google Gemini API key:
```env
GEMINI_API_KEY=your_google_gemini_api_key_here
```

**Run the Backend:**
```bash
uvicorn main:app --reload
```
The backend API will be available at `http://localhost:8000`.

### 3. Frontend Setup (Next.js)

Open a new terminal window, navigate to the frontend directory, and install the dependencies:

```bash
cd frontend
npm install
```

**Run the Frontend:**
```bash
npm run dev
```
The frontend application will be available at `http://localhost:3000`.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/athrav138/friendship-court-ai/issues) if you want to contribute.

## 📄 License

This project is licensed under the MIT License.
