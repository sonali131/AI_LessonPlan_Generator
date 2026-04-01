# 📚 AI Lesson Plan Generator

✨ An AI-powered web application that helps teachers instantly generate lesson plans, quizzes, worksheets, and classroom activities using advanced language models.

---

## 🌐 Live App  
👉 https://aileappnplangenerator-3dyppewud7av7rze6g8cja.streamlit.app/

---

## ✨ Features

- 🧠 AI-based Lesson Plan Generator  
- 📅 Weekly Teaching Planner  
- 📝 Worksheet Generator  
- 🎯 Quiz Generator (MCQs)  
- 🎲 Classroom Activities Generator  
- 📂 Upload Syllabus → Auto Lesson Planning  
- 💾 Save & View Lessons  
- 📄 Download as PDF & PPT  
- 🔐 User Authentication (Login/Signup)  

---

## 🛠️ Tech Stack

### Frontend
- Streamlit  

### Backend
- Python  

### Database
- MongoDB Atlas  

### AI Model
- LLaMA (via Groq API)  

### Libraries
- PyMongo  
- LangChain  
- ReportLab  
- python-pptx  
- PyPDF2  
- bcrypt  

---

## 📂 Project Structure
AI_LessonPlan_Generator/
│── app.py
│── requirements.txt
│── runtime.txt
│── .env (ignored)
│── .gitignore
│── README.md
│── config.toml

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/sonali131/AI_LessonPlan_Generator.git
cd AI_LessonPlan_Generator
```
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Setup Environment Variables

Create a .env file:

MONGO_URI=your_mongodb_connection_string
GROQ_API_KEY=your_groq_api_key
4️⃣ Run Locally
streamlit run app.py
☁️ Deployment (Streamlit Cloud)
Push code to GitHub
Go to Streamlit Cloud
Select your repo
Set:
Main file: app.py
Add secrets:
MONGO_URI="your_mongo_uri"
GROQ_API_KEY="your_api_key"
Click Deploy 🚀
🎯 Use Cases
👩‍🏫 Teachers creating lesson plans
🏫 Schools automating curriculum planning
📚 EdTech platforms
🎓 Students preparing structured notes

📸 Screenshots (Optional)

Add screenshots here for better UI showcase
<img width="953" height="444" alt="Screenshot 2026-03-29 122829" src="https://github.com/user-attachments/assets/56aac0c2-1ee1-4824-abcb-acee4380b0e1" />
<img width="950" height="431" alt="Screenshot 2026-03-29 122921" src="https://github.com/user-attachments/assets/43315bea-c81e-4d08-abbc-d7d092471c38" />
<img width="949" height="412" alt="Screenshot 2026-03-29 122952" src="https://github.com/user-attachments/assets/f6fdf565-c993-46d0-9669-f50a76b46e97" />
<img width="950" height="412" alt="Screenshot 2026-03-29 123014" src="https://github.com/user-attachments/assets/cc8dd55c-9ce9-479c-8766-d8813768795c" />
<img width="949" height="440" alt="Screenshot 2026-03-29 123049" src="https://github.com/user-attachments/assets/97406eca-2444-4d01-863f-541ae77297ef" />


🔒 Security Note
Sensitive data like API keys and DB credentials are stored securely using:
.env (local)
Streamlit secrets (cloud)

👩‍💻 Author
Sonali Mishra
💡 MCA Student | AI/ML | Full Stack Enthusiast | AI Automation

⭐ Support

If you like this project:

⭐ Star this repo
🍴 Fork it
📢 Share with others
🚀 Future Improvements
📊 Analytics Dashboard
👥 Multi-user roles (Admin/Teacher)
🌍 Multi-language support
📱 Mobile responsive UI
🤖 More AI models integration

🔥 Made with AI + ❤️ + Innovation
