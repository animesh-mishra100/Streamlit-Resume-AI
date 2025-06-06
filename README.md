
# 💼 AI-Powered Resume Evaluator

An intelligent, cloud-deployed application that evaluates your resume against a job description using Google’s Gemini 2.0 LLM. It scores your resume, identifies skill gaps, and gives actionable suggestions for improvement — all through a simple Streamlit interface hosted on AWS EC2.

---

## 🚀 Features

- 🔍 **Smart Resume-Job Matching**  
  Compares your resume with a job description using semantic understanding (not just keywords!).

- 📊 **Score & Feedback**  
  Provides a match score (out of 100), highlights missing technical skills, and gives detailed improvement suggestions.

- ☁️ **Cloud Deployed**  
  Hosted on AWS EC2 using Ubuntu AMI, ensuring fast, global access.

- 🧠 **Powered by Gemini 2.0**  
  Uses Google DeepMind’s LLM for accurate, human-like evaluation and recommendations.

---

## 🛠️ Tech Stack

- **Frontend**: [Streamlit](https://streamlit.io)  
- **Backend**: [Gemini 2.0 API](https://deepmind.google/technologies/gemini) via Google Generative AI SDK  
- **Cloud Hosting**: AWS EC2 (Ubuntu 20.04)  
- **Language**: Python 3.10+

---

## 📂 Project Structure

```
Resume-AI/
├── app.py               # Streamlit app interface
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---

## ⚙️ How to Run Locally

1. **Clone the repo**

```bash
git clone https://github.com/your-username/resume-ai.git
cd resume-ai
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Set your Gemini API key**

Create a `.env` file or set the key directly in your script:

```bash
export GOOGLE_API_KEY="your-key-here"
```

4. **Run the app**

```bash
streamlit run app.py
```

---

## 🌐 Deployed on AWS

This app is deployed on an AWS EC2 instance running Ubuntu. To replicate:

- Launch an EC2 instance
- Open ports 22 (SSH) and 8501 (Streamlit)
- Use Git and SCP to upload files
- Install dependencies and run the app

---

## 📚 References

1. [Gemini 2.0 Documentation](https://deepmind.google/technologies/gemini)  
2. [Amazon EC2 Docs](https://docs.aws.amazon.com/ec2)  
3. [Streamlit Docs](https://docs.streamlit.io)  

---

