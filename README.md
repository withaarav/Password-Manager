🔐 MyPass – Simple Password Manager

A lightweight command-line password manager built in Python to securely store and retrieve credentials.

🚀 Overview

MyPass is a minimal yet functional password manager that allows users to:

* Store login credentials for different services
* Retrieve saved passwords instantly
* Copy passwords directly to clipboard for quick use

Designed as a practical project to explore file handling, data storage, and user interaction in Python.

⸻

✨ Features

* 🔑 Save passwords with associated service and email
* 🔍 Retrieve stored credentials easily
* 📋 Auto-copy passwords to clipboard using pyperclip
* 💾 Persistent storage using JSON
* ⚡ Fast and simple CLI interface

⸻

🛠 Tech Stack

* Python 3
* JSON (for data storage)
* pyperclip (clipboard functionality)

⸻

📂 Project Structure

MyPass/
│── main.py
│── data.json
│── pyproject.toml
│── poetry.lock

⸻

⚙️ Installation & Setup

1. Clone the repository:
    git clone https://github.com/withaarav/mypass.git
    cd mypass
2. Install dependencies:
    pip install pyperclip
3. Run the program:
    python main.py

⸻

💡 How It Works

Credentials are stored in a local JSON file.

Each entry contains:

* Website name
* Email/username
* Password

Example structure:

{
“example”: {
“email”: “user@example.com”,
“password”: “securepassword123”
}
}

⸻

🎯 Why I Built This

I built MyPass to understand:

* File handling in Python
* Structuring real-world CLI tools
* Managing user data efficiently

This project is part of my journey into building practical and secure applications.

⸻

⚠️ Disclaimer

This is a learning project and NOT intended for production use.
Passwords are stored locally and are not encrypted.

⸻

🚀 Future Improvements

* Add encryption for stored passwords
* Build a GUI version
* Add cloud sync support
* Add master password authentication

⸻

🤝 Contributing

Feel free to fork the repo, improve features, or suggest enhancements!

⸻

📬 Contact

GitHub: https://github.com/withaarav
