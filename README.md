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

javac -d build/classes src/chatting/application/*.java


### 🚀 Run Server

java -cp build/classes chatting.application.Server

### 💻 Run Client

java -cp build/classes chatting.application.Client
#### ⚠️ Make sure to run the Server first before starting the Client.


### 👨‍💻 Author - Sk Mustak Ahammed


## 📜 License

### This project is licensed under the MIT License – see the LICENSE file for details.
MIT License

#Copyright (c) 2025 Sk Mustak Ahammed

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.