# 🏙️ Smart Civic – AI-Powered Civic Complaint System

Smart Civic is an AI-driven web application designed to simplify and modernize the process of civic complaint filing. The system intelligently identifies sanitation issues from images, supports multilingual users, captures location details, and auto-generates properly formatted complaints for municipal authorities.

🏆 **This project was developed during HackQuest 2025**, held at **UIT Allahabad**, where it secured **9th position** among participating teams.

---

## 🚀 Features

- 🧠 **AI-based Image Classification**  
  Detects sanitation issues (garbage, waste, cleanliness problems) using a deep learning model.

- 🌐 **Multilingual Support**  
  Enables citizens to file complaints in multiple languages.

- 📍 **Location Capture**  
  Supports GPS-based and manual location input.

- 📝 **Auto-generated Complaints**  
  Automatically formats complaints suitable for municipal corporations.

- 🖥️ **User-Friendly Web Interface**  
  Simple and accessible UI built for ease of use.

---

## 🏆 Hackathon Recognition

- **Event:** HackQuest 2025  
- **Venue:** United Institute of Technology (UIT), Allahabad  
- **Achievement:** 🥉 Secured **9th Position**  
- **Category:** Smart City / Civic-Tech Solutions  

This project was built under time constraints with a focus on real-world impact, innovation, and scalability for smart city initiatives.

---

## 🏗️ System Architecture

1. User uploads an image of a civic issue  
2. AI model classifies the issue type  
3. User selects language and provides location details  
4. System generates a structured civic complaint  
5. Complaint is ready for submission to authorities  

---

## 🛠️ Tech Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python
- Flask

### Machine Learning
- TensorFlow / Keras  
- MobileNetV2 (Image Classification)

### Other Tools & Libraries
- OpenCV  
- NumPy  
- Google Translate API (for multilingual support)

---

## 📂 Project Structure

Smart_civic/
│
├── static/ # CSS, JavaScript, assets
├── templates/ # HTML templates
├── model/ # Trained ML model
├── app.py # Flask application
├── requirements.txt # Python dependencies
└── README.md

yaml
Copy code

---

## ⚙️ Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/Shrishti-Sonkar/Smart_civic.git
cd Smart_civic
Create a virtual environment (optional but recommended)

bash
Copy code
python -m venv venv
venv\Scripts\activate   # Windows
Install dependencies

bash
Copy code
pip install -r requirements.txt
Run the application

bash
Copy code
python app.py
Open your browser and visit:

cpp
Copy code
http://127.0.0.1:5000
