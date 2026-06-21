# 📧 Cold Mail Automator (AI Powered)

An AI-powered Cold Email Generator that automatically extracts job postings from a given URL and generates personalized cold emails using LLMs and a vector-based portfolio matching system.

Built using **LangChain, Groq Llama 3.1, ChromaDB, and Streamlit**.

---

## 🚀 Features

- 🔗 Extract job details directly from career pages (web scraping)
- 🤖 AI-powered job parsing using LLM (Llama 3.1 via Groq)
- 📄 Automatically generates professional cold emails
- 🧠 Vector database (ChromaDB) for portfolio matching
- 🔍 Finds relevant portfolio links based on required skills
- 🎯 Simple and interactive Streamlit UI

---

## 🏗️ Tech Stack

- Python 🐍
- Streamlit
- LangChain
- Groq API (Llama 3.1)
- ChromaDB (Vector Database)
- BeautifulSoup / WebBaseLoader
- Pandas
- NumPy

---

## 📁 Project Structure
ColdEmailgeneratortool/
│
├── app/
│ ├── chains.py # LLM logic (job extraction + email generation)
│ ├── portfolio.py # Vector DB + skill matching
│ ├── utils.py # Helper functions
│
├── main.py # Streamlit frontend
├── requirements.txt
├── .env # DO NOT PUSH TO GITHUB
└── README.md


---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Cold-Mail-Automator.git
cd Cold-Mail-Automator


### 2. Create virtual environment
python -m venv venv
Activate environment

Windows

venv\Scripts\activate

Mac/Linux

source venv/bin/activate
3. Install dependencies
pip install -r requirements.txt
4. Setup environment variables

Create a .env file in the root directory:

GROQ_API_KEY=your_groq_api_key_here
5. Run the application
streamlit run main.py


### 🧠 How It Works
User enters a job posting URL
Web scraper extracts job description
LLM extracts structured job data:
Role
Skills
Experience
Description
Portfolio system matches skills using ChromaDB
AI generates a personalized cold email
Output is displayed in Streamlit UI
📌 Example Usage

Input
https://jobs.example.com/software-engineer
Output
Extracted job role
Required skills
Matching portfolio links
Generated cold email

🔐 Security Best Practices

Never upload .env file to GitHub
Store API keys in environment variables
Rotate keys if exposed
Use .gitignore properly
🚀 Future Improvements
📬 Email sending automation (SMTP / Gmail API)
📄 Resume parsing feature
🔄 Batch job processing
🌐 React frontend upgrade
📊 Analytics dashboard
👨‍💻 Author

Devi Jetta

GitHub: https://github.com/Devi09781
LinkedIn: https://www.linkedin.com/devijetta/
⭐ Support

If you like this project:

⭐ Star the repository
🍴 Fork it
🤝 Contribute



