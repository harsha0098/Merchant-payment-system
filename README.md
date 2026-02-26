# Merchant Payment System

A Flask-based web application that enables secure peer-to-peer Ethereum transactions. Users can register with their Ethereum wallet credentials, authenticate, and send/receive ETH payments through a simple web interface.

---

## 🚀 Features

* User registration with Ethereum wallet address
* Secure login and authentication
* Send and receive ETH peer-to-peer
* View transaction history
* QR code generation for wallet addresses

---

## 📁 Project Structure

```
├── app.py                 # Main Flask application
├── db_conns.py            # Database connection logic
├── db_view.py             # Database view operations
├── init_db.py             # Initializes database schema
├── qr_gen.py              # QR code generation
├── sample.py              # Sample/testing script
├── static/                # Static files (CSS, images)
├── templates/             # HTML templates (Jinja2)
├── user.db                # SQLite database (auto-generated)
└── .gitignore
```

---

## 🛠️ Prerequisites

* Python 3.8 or higher
* pip (Python package manager)

---

## ⚙️ Installation & Setup

1. **Clone the repository**

```
git clone https://github.com/harsha0098/Merchant-payment-system.git
cd Merchant-payment-system
```

2. **Install dependencies**

If requirements.txt exists:

```
pip install -r requirements.txt
```

If not, install manually:

```
pip install Flask qrcode
```

3. **Initialize the database**

```
python init_db.py
```

4. **Run the application**

```
python app.py
```

5. **Open in browser**

```
http://127.0.0.1:5000
```

---

## 🧠 How It Works

* Users register using their Ethereum wallet address.
* User details are stored in a SQLite database.
* Payments are made by entering the recipient’s wallet address and transaction amount.
* QR codes are generated to simplify wallet address sharing.

---

## 🛡️ Security Note

This project is intended for learning and demonstration purposes only.
For production use, implement:

* Secure private key management
* HTTPS encryption
* Proper blockchain transaction signing
* Input validation and protection against common web vulnerabilities

---

## 🧰 Tech Stack

* Python
* Flask
* SQLite
* Ethereum
* HTML / CSS

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository and submit pull requests.

---

## 📜 License

Add a license file (e.g., MIT License) if you plan to distribute or use this project publicly.
