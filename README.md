📇 Contact Book Web App

A modern, fully functional contact management web application built with Python Flask and vanilla JavaScript. This project was developed as part of my internship at **CodSoft**.

![Python](https://img.shields.io/badge/python-3.8+-blue)
![Flask](https://img.shields.io/badge/flask-2.0+-orange)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-completed-success)

---

## 📋 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Live Demo](#-live-demo)
- [Screenshots](#-screenshots)
- [Installation](#-installation)
- [How to Use](#-how-to-use)
- [API Endpoints](#-api-endpoints)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)
- [Acknowledgments](#-acknowledgments)

---

## ✨ Features

- ✅ **Add Contact** - Add new contacts with name, phone, email, and address
- ✅ **View Contacts** - Display all saved contacts in a clean list
- ✅ **Search Contacts** - Search by name or phone number
- ✅ **Update Contact** - Edit and update contact details
- ✅ **Delete Contact** - Remove contacts with confirmation
- ✅ **Contact Statistics** - View total contacts and recent additions
- ✅ **Data Persistence** - Saves contacts using LocalStorage (or JSON file with backend)
- ✅ **Responsive Design** - Works on desktop, tablet, and mobile
- ✅ **Modern UI** - Beautiful glass-morphism design with dark theme

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Python 3.8+** | Backend server |
| **Flask 2.0+** | Web framework |
| **HTML5** | Structure |
| **CSS3** | Styling & animations |
| **JavaScript (ES6)** | Frontend logic & interactivity |
| **LocalStorage API** | Data persistence |


## 📦 Installation

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

### Step-by-Step Guide

**1. Clone the repository**
```bash
git clone https://github.com/yourusername/contact-book.git
cd contact-book
2. Create a virtual environment (optional but recommended)

bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install dependencies

bash
pip install flask
4. Run the application

bash
python app.py
5. Open your browser

text
http://localhost:5000
🎯 How to Use
Adding a Contact
Fill in the contact details:

Full Name (required)

Phone Number (required)

Email (optional)

Address (optional)

Click "Save Contact" button

Contact appears in the list instantly

Viewing Contacts
All contacts are displayed in the right panel

Each contact shows: Name, Phone, Email, Address

Statistics show total contacts and recent additions

Searching Contacts
Type a name or phone number in the search box

Click the search button or press Enter

Matching contacts are displayed instantly

Editing a Contact
Click the ✏️ Edit button on any contact

Update the details in the modal popup

Click "Update" to save changes

Deleting a Contact
Click the 🗑️ Delete button on any contact

Confirm deletion in the popup

Contact is removed instantly

🔧 API Endpoints
Method	Endpoint	Description
GET	/api/contacts	Get all contacts
POST	/api/contacts	Add a new contact
PUT	/api/contacts/<id>	Update a contact
DELETE	/api/contacts/<id>	Delete a contact
GET	/api/contacts/search?q=	Search contacts
Example API Request
POST /api/contacts

json
{
  "name": "John Doe",
  "phone": "+1 234 567 8900",
  "email": "john@example.com",
  "address": "123 Main St, City"
}
Response

json
{
  "id": 1,
  "name": "John Doe",
  "phone": "+1 234 567 8900",
  "email": "john@example.com",
  "address": "123 Main St, City"
}
📂 Project Structure
text
contact-book/
│
├── app.py                 # Flask backend
├── templates/
│   └── index.html         # Main HTML with CSS & JS
├── contacts.json          # JSON data storage (auto-generated)
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
🧪 Testing
Test the contact book with these scenarios:

Test Case	Action	Expected Result
Add Contact	Fill all fields, click Save	Contact appears in list
Add Contact (missing fields)	Leave Name blank	Error message
Search	Type "John" in search	Shows matching contacts
Edit	Click Edit, update phone	Phone number updated
Delete	Click Delete, confirm	Contact removed
Stats	Add multiple contacts	Count updates
🤝 Contributing
Contributions are welcome! Here's how:

Fork the repository

Create a feature branch (git checkout -b feature/AmazingFeature)

Commit changes (git commit -m 'Add AmazingFeature')

Push to branch (git push origin feature/AmazingFeature)

Open a Pull Request

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

👩‍💻 Author
Your Name

LinkedIn: https://www.linkedin.com/posts/pragna-kamisetti-38464232a_python-flask-webdevelopment-ugcPost-7473358028218486785-LxGF/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFMIO5QBnrbhcuqBhOGclieUEGzycCpckgw 

Portfolio: Your Portfolio

🙏 Acknowledgments
CodSoft - For providing this internship opportunity

Flask Community - For the amazing web framework

Open Source Community - For endless learning resources

📧 Contact
Have questions or suggestions? Feel free to reach out!

Email: your.email@example.com

LinkedIn: Your LinkedIn

⭐ Show Your Support
If you found this project helpful, please give it a ⭐ on GitHub!

📊 Project Status
https://img.shields.io/badge/status-completed-success
https://img.shields.io/github/last-commit/yourusername/contact-book
https://img.shields.io/github/repo-size/yourusername/contact-book

Made with ❤️ for CodSoft Internship

text

---

## 📁 **requirements.txt**

```txt
Flask==2.3.3
