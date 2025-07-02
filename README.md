# 💬 Java Chatting Application

A simple **Java Swing-based Client-Server Chatting Application** that enables two-way communication between a client and a server over a local network. Built with AWT, Swing, and Socket programming.

---

## 📦 Features

- 🔌 Server-Client communication using `Socket` and `DataStreams`
- 🪟 GUI built with Java Swing (JFrame, JPanel, JTextField, JButton)
- 📤 Send and receive messages in real-time
- 💡 Easy to run using NetBeans or VS Code

---

## 🛠 Technologies Used

- Java (JDK 8+)
- Java AWT & Swing for UI
- Socket Programming (`java.net.Socket`, `ServerSocket`)
- NetBeans / Visual Studio Code

---

## 📁 Project Structure

CHATTING APPLICATION/
├── src/chatting/application/
│ ├── Server.java # Server-side GUI and socket handling
│ └── Client.java # Client-side GUI and socket handling
├── build/ # Compiled classes
├── icons/ # Image icons used in GUI
├── nbproject/ # NetBeans project files
├── test/ # Test files (if any)
├── build.xml # Ant build script
├── manifest.mf # Manifest file for JAR
└── README.md # Project documentation


---

## 🔧 How to Run

### 🖥️ Compile
```bash
javac -d build/classes src/chatting/application/*.java

🚀 Run Server

java -cp build/classes chatting.application.Server

💻 Run Client

java -cp build/classes chatting.application.Client
⚠️ Make sure to run the Server first before starting the Client.

# 👨‍💻 Author- Sk Mustak Ahammed

# 📜 License
This project is for learning and educational purposes only.