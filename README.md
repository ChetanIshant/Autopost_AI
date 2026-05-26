# Autopost_AI

# AutoPost AI — LinkedIn Content Automation Platform

A full-stack AI-powered web application that automates the creation, scheduling, 
and publishing of professional LinkedIn posts.

## 🚀 Live Demo
[autopostgenerator.onrender.com](https://autopost-ai-i78p.onrender.com)

## 📌 Features
- AI-generated LinkedIn posts using Groq Cloud API (LLaMA 3.3 70B)
- Automated image generation via Pollinations AI API
- Natural language scheduling — e.g. "Post about AI on Friday at 9 AM"
- End-to-end LinkedIn publishing via OAuth 2.0 and LinkedIn API
- Support for personal profiles and company pages
- Automated post scheduling using Supabase pg_cron and Edge Functions
- Dashboard to manage, edit, and delete scheduled posts

## 🛠️ Tech Stack
| Layer | Technology |
|-------|-----------|
| Backend | Python Flask |
| Frontend | HTML, Tailwind CSS, JavaScript |
| Database | Supabase (PostgreSQL) |
| AI Text | Groq Cloud API (LLaMA 3.3 70B) |
| AI Image | Pollinations AI API |
| Auth | LinkedIn OAuth 2.0 |
| Scheduler | Supabase pg_cron + Edge Functions |
| Deployment | Render |

## ⚙️ Setup & Installation

1. Clone the repository
   git clone https://github.com/ChetanIshant/Autopost_AI.git
   cd Autopost_AI

2. Install dependencies
   pip install -r requirements.txt

3. Configure environment variables
   cp .env.example .env
   # Fill in your API keys in .env

4. Run the application
   python app.py

## 🔑 Environment Variables
GROQ_API_KEY=your_groq_api_key
LINKEDIN_CLIENT_ID=your_linkedin_client_id
LINKEDIN_CLIENT_SECRET=your_linkedin_client_secret
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key

## 👨‍💻 Author
Chetan Urf Ishant
