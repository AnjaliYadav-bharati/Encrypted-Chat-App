# 🔐 Encrypted Chat Application (Python + AES Encryption)

A secure multi-client chat application built using **Python Sockets** and **AES Encryption (EAX Mode)**.  
This project was developed as part of the **SyntecXHub Internship Program**.

---

## 🚀 Features

- 🔒 AES-128 encryption for all chat messages  
- 📡 Multi-client chat server  
- 🧵 Threaded message receiver  
- 🟪 Jupyter Notebook–friendly client (non-blocking input)  
- 📄 Full project report included as PDF  
- 💻 Clean, modular, secure code  
- 📊 Architecture diagram included

---

## 📁 Project Structure


---

## 🧠 Technologies Used

- **Python 3**
- **Socket Programming**
- **AES Encryption (PyCryptodome)**
- **Threading**
- **Jupyter Notebook**

---

## 🔐 AES Encryption Details

The application uses:

- AES in **EAX mode**  
- 16-byte symmetric key  
- Nonce + Tag + Ciphertext format  
- Base64 encoded messages  
- Tamper detection (integrity check)

This ensures **confidentiality + message integrity**.

---

## 🧱 Architecture Diagram

If you uploaded your PNG, this will show automatically:

![Architecture Diagram](diagram.png)

---

## ▶️ How to Run the Project

### **1️⃣ Install Dependencies**


---

### **2️⃣ Start the Server**

Open `server.ipynb` and run all cells.

Server starts automatically on:



---

### **3️⃣ Start the Client**

Open `client.ipynb` and run all cells.

To send a message:


---

### **4️⃣ Run Multiple Clients**

Open additional Jupyter tabs → run `client.ipynb` again.  
All clients will receive messages securely.

---

## 🛡 Security Notes

- All messages are end-to-end encrypted using AES  
- EAX mode prevents tampering  
- Shared symmetric key used  
- New nonce generated for every message  
- For production systems: use RSA key exchange  

---

## 📌 Future Enhancements

- AES-256 support  
- RSA public key exchange  
- Graphical UI (Tkinter / PyQt)  
- Database for message history  
- Cloud-hosted server  
- Android version  

---

## 👩‍💻 Author

**Anjali Yadav**  
Telecommunication & Network Engineering Student  
Secure Chat App Project — SyntecXHub Internship   

---

# Encrypted-Chat-App
Secure Encrypted Chat Application using Python Sockets and AES Encryption (Internship Project)
