
# Sentiment Analysis ChatBot 🤖
*A GenAI-powered chatbot for advanced Twitter sentiment analysis*

---

## 🚀 Overview
The **Sentiment Analysis ChatBot** was built for the **GenAI Chatbot Competition**, leveraging **Google Gemini API**, **Twikit**, and **Machine Learning models** to analyze tweets and provide **real-time public sentiment insights**.

Our chatbot offers **two powerful modes of analysis**:  
1. **Topic-Based Analysis** → Enter a topic, and **Gemini AI** will analyze recent tweets to give a deep understanding of public opinion.  
2. **Sentiment-Based Analysis** → Input a single tweet, and our **ML models** classify it as **Positive**, **Negative**, or **Neutral**.

> 🌐 **Live Demo:** [Try it here](https://Fire-pixel19.github.io/sentiment-analysis-chatbot/)

---

## 🌟 Features
- **Real-time Twitter Data Scraping** using **Twikit**.
- **Two Modes of Analysis**:
  - *Topic-Based Analysis* → Context-aware insights via **Gemini AI**.
  - *Sentiment-Based Analysis* → Machine Learning predictions using Logistic Regression & Random Forest.
- **Automated Data Cleaning Pipeline** – Filters spam, ads, and irrelevant tweets.
- **Gemini AI Sarcasm Handling** – Understands satire and complex sentiment nuances.
- **Fully Responsive Web Interface**, deployable via **GitHub Pages**.

---

## 🛠️ Tech Stack
| Technology | Purpose |
|------------|---------|
| **[Google Gemini API](https://ai.google.dev/)** | Topic-based sentiment insights |
| **[Twikit](https://github.com/dmytrostriletskyi/twikit)** | Live Twitter scraping |
| **Python (Flask)** | Backend logic |
| **HTML, Tailwind CSS, JavaScript** | Frontend UI |
| **Pandas, NumPy** | Data preprocessing |

---

## 🔧 System Workflow
```
User Input (Tweet / Topic)
          │
          ▼
     Twikit Scraper
          │
          ▼
    Data Cleaning & Filtering
          │
 ┌────────┴────────┐
 │                 │
 ▼                 ▼
Gemini API     ML Models (LR, RF)
 │                 │
 ▼                 ▼
Topic Insights   Sentiment Label
          │
          ▼
       Web Output
```

---

## ⚡ Getting Started (Local Development)

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/<your-username>/sentiment-analysis-chatbot.git
cd sentiment-analysis-chatbot
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Configure API Keys**
Create a `.env` file in the root directory and add:
```
GEMINI_API_KEY=your_gemini_api_key_here
```

### **4️⃣ Run Locally**
```bash
python app.py
```
Your app will run at: **http://127.0.0.1:5000/**

---

## 🌐 Deployment on GitHub Pages
We’ve configured this project so it can be **hosted directly on GitHub Pages**, making it easy to share with judges or anyone online.

### **Steps:**
1. Push all code to a **GitHub repository**.
2. Go to **Settings → Pages**.
3. Under *Deploy from branch*, select the `main` branch and `/root` folder.
4. Wait for deployment → You’ll get a link like:  
   ```
   https://<your-username>.github.io/sentiment-analysis-chatbot/
   ```
5. Update the **Live Demo** link in this README.

---

## 🌐 Project Structure
```
📂 sentiment-analysis-chatbot
│
├── 📂 static            # CSS, JS, images
├── 📂 templates         # HTML files
├── 📂 models            # Pretrained ML models
├── 📂 scripts           # Data scraping & cleaning scripts
│
├── app.py               # Main backend application
├── requirements.txt     # Dependencies
├── .env.example         # Example environment config
└── README.md            # Project documentation
```

---

## 🎥 Live Demo & Screenshots
- 🌐 **Live Demo:** [Click Here](https://Fire-pixel19.github.io/sentiment-analysis-chatbot/)
- *Screenshots Coming Soon!*

---

## 🏆 Competition Context
This project was created for the **GenAI Chatbot Competition**, showcasing **Generative AI’s ability to analyze real-time social data** and derive meaningful sentiment insights.

---

## 👨‍💻 Team
| Name | Role |
|------|------|
| **Yash** | Machine Learning & Backend Developer |
| *Teammate 2* | Frontend Developer |
| *Teammate 3* | Data Engineer |

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

### 🌟 Star this repo if you like it!
> Help us grow by giving a ⭐ on GitHub!
