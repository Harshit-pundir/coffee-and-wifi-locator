# ☕ Cafe WiFi Directory

A Flask web application that allows users to add and browse cafes with ratings for coffee, WiFi, and power outlets. Designed to help remote workers and students find the perfect spot to work or relax.

## 🚀 Features

- Add new cafes with:
  - Cafe Name
  - Location (Google Maps URL)
  - Opening and Closing Time
  - Coffee ☕️, WiFi 💪, and Power 🔌 ratings
- View a list of all added cafes in a styled table
- Data stored in a CSV file
- Built with Flask, Bootstrap, and WTForms


## 📂 Project Structure

project/
│
├── app.py # Main Flask app
├── templates/ # HTML templates
│ ├── base.html
│ ├── index.html
│ ├── add.html
│ └── cafes.html
│
├── static/
│ └── styles.css # Custom CSS (optional)
│
├── cafe-data.csv # Data storage (acts like a mini database)
├── requirements.txt # Python dependencies
└── README.md


## 🛠️ Tech Stack

- Python
- Flask
- Flask-WTF
- Flask-Bootstrap
- HTML + Bootstrap

## 💡 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/cafe-wifi-directory.git
cd cafe-wifi-directory

2. Install Requirements
bash
Copy
Edit
pip install -r requirements.txt
3. Run the App
bash
Copy
Edit
python app.py
Open http://127.0.0.1:5000 in your browser.

