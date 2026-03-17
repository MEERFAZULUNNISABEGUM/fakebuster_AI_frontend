# 🛡️ FakeBuster AI – Cybersecurity Threat Detection Platform (Frontend)

FakeBuster AI is an **AI-powered cybersecurity dashboard** designed to detect and analyze modern digital threats including **phishing emails, malicious URLs, and deepfake media**.

This repository contains the **Streamlit frontend interface** that communicates with the **FastAPI backend** to perform real-time threat analysis and visualization.

The platform provides an **interactive security operations dashboard** that enables users to scan content, visualize risks, and understand potential cyber threats using AI models.

---

# 🚀 Features

## ⚡ System Dashboard

A real-time overview of the platform’s security operations including:

* Total scans performed
* Threats blocked
* Deepfake media detected
* Average trust score
* Live threat activity feed
* Threat detection charts

---

## 📧 Email Phishing Detection

Analyzes email content using NLP techniques to detect phishing patterns such as:

* Urgency indicators
* Credential harvesting attempts
* Suspicious keywords
* Social engineering tactics

The system returns:

* Risk score
* Risk level
* AI explanation
* Suspicious keyword highlights

---

## 🔗 Malicious URL Scanner

Evaluates URLs for potential threats including:

* Typosquatting
* Suspicious redirects
* Newly registered domains
* SSL certificate issues

Results include:

* Domain risk score
* SSL status
* Domain age
* Detected threat patterns

---

## 📸 Deepfake Detection

Uploads images or videos and analyzes them using AI models to detect media manipulation.

The system performs:

* Frame extraction
* Artifact detection
* Facial consistency analysis
* Authenticity scoring

Output includes:

* Authenticity score
* Deepfake detection result
* Detected anomalies
* Frame-level authenticity graph

---

## 🛡️ Trust Score Analysis

Aggregates multiple threat signals to calculate an **overall trust index**.

Displays:

* Organization trust score
* Security posture gauge
* Tactical security recommendations

---

## 📈 Threat Intelligence Analytics

Provides insights into historical threat data including:

* Detection trends
* Severity distribution
* Simulated global attack origins map

---

## 🔐 Authentication System

Custom **HTML + CSS authentication interface** embedded in Streamlit.

Includes:

* User registration
* Login authentication
* Password strength indicator
* Modern UI with animated design
* API integration with backend

---

# 🧠 Tech Stack

### Frontend

* **Streamlit** – Interactive web interface
* **Plotly** – Data visualization
* **Pandas** – Data processing
* **HTML / CSS / JavaScript** – Custom authentication UI
* **Requests** – API communication

### Backend (Connected System)

The frontend communicates with a **FastAPI backend** which performs:

* Phishing detection using NLP models
* URL threat classification
* Deepfake detection models
* Trust score calculation
* User authentication system

---

# 📂 Project Structure

```
frontend/
│
├── app.py                # Main Streamlit application
├── README.md             # Project documentation
└── requirements.txt      # Python dependencies
```

---

# ⚙️ Installation

## 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/fakebuster-ai-frontend.git
cd fakebuster-ai-frontend
```

---

## 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Start the Streamlit application

```bash
streamlit run app.py
```

The application will run on:

```
http://localhost:8501
```

---

# 🔌 Backend Connection

The frontend communicates with the backend API at:

```
http://localhost:8000
```

Endpoints used:

| Endpoint           | Purpose                  |
| ------------------ | ------------------------ |
| `/detect/email`    | Phishing email detection |
| `/detect/url`      | URL threat detection     |
| `/detect/deepfake` | Deepfake media analysis  |
| `/trustscore`      | Global trust score       |
| `/auth/register`   | User registration        |
| `/auth/login`      | User authentication      |

Ensure the backend server is running before launching the frontend.

---

# 📊 Example Workflow

1️⃣ User logs into the system
2️⃣ Uploads or pastes suspicious content
3️⃣ Frontend sends request to backend API
4️⃣ AI models analyze the input
5️⃣ Results are visualized in the dashboard

---

# 🛡️ Use Cases

* Cybersecurity awareness tools
* Email phishing analysis
* Deepfake media detection
* Enterprise threat monitoring
* Hackathon cybersecurity projects
* Security operations dashboards

---

# 📸 Demo Screens

The interface includes:

* Cybersecurity command dashboard
* Email threat analysis panel
* URL inspection tool
* Deepfake detection interface
* Trust score analytics
* Global threat intelligence map

---

# 👨‍💻 Author

Developed as part of a **Cybersecurity AI Hackathon Project**.

Built using **modern AI threat detection concepts and interactive security dashboards**.

---

# ⭐ Future Improvements

* Real-time threat feed integration
* VirusTotal API integration
* Advanced deepfake detection models
* User threat history tracking
* Organization-level analytics
* Cloud deployment support

---

# 📜 License

This project is for **educational and research purposes**.
