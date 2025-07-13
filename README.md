# Resume Parser and Job Matcher 🧠⚙️

An AI-powered automation project built using **n8n** and **OpenAI**, designed to parse resumes and intelligently match them with relevant job descriptions. This tool simplifies recruitment by extracting key candidate information and ranking applicants based on job-fit criteria.

## 🚀 Features

- 📄 Parses resumes in PDF/Word format to extract:
  - Name
  - Contact details
  - Skills
  - Work experience
  - Education
- 🧠 Uses **OpenAI API** for semantic skill and experience matching.
- 🧰 Custom matching algorithm scores candidates based on job descriptions.
- 🔁 Built with **n8n** for seamless workflow automation.
- ✉️ Sends automated email notifications to candidates and recruiters.
- 🌐 Webhook support for real-time integration with third-party platforms.

## 🛠 Tech Stack

- [n8n](https://n8n.io/) – Workflow automation
- [OpenAI API](https://platform.openai.com/) – AI-based semantic analysis
- Regex – Text extraction and structuring
- JavaScript / Python – For scripting inside n8n (optional)
- Email + Webhook nodes – For notifications and integrations

## 🧩 How It Works

1. **Resume Input**: Resume is received via upload form, email, or webhook.
2. **Parsing**: Resume content is extracted and cleaned using regex.
3. **AI Matching**: OpenAI compares resume data with job descriptions.
4. **Scoring**: A score is generated based on skills and experience match.
5. **Notification**: Results are sent via email or API response.

## 📁 Folder Structure (If applicable)

