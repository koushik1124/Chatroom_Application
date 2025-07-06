# 💬 Chatroom Application (Python + Tkinter + Sockets)

A multi-user chatroom application built in **Python**, using **socket programming** for networking and **Tkinter** for the client GUI. This is a desktop-based application where multiple users can chat in real time through a server.

---

## 🚀 Features

- Real-time communication using TCP sockets
- GUI chat interface built with Tkinter
- Handles multiple clients via threading
- Simple command-line usage

---

## 🛠️ Technologies Used

- Python Standard Library:
  - `socket`
  - `threading`
  - `argparse`
  - `tkinter`
  - `sys`, `os`

---

## 📁 Project Structure

Chatroom_Application/
│
├── client.py # GUI-based chat client using Tkinter
├── server.py # Multi-client chat server using sockets
├── README.md # Project overview and instructions

## ✅ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/koushik1124/Chatroom_Application.git
cd Chatroom_Application
**2. Run the Server**
Start the server in one terminal window:
bash
python server.py
**3. Run a Client**
In a separate terminal window:
bash
python client.py
