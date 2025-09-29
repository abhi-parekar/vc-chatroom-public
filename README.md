# Text Shield Chatroom - Public Repository

## 🚀 Project Overview

Text Shield Chatroom is a secure real-time communication platform that enables safe online messaging among users. This public repository contains the community-friendly components of the project. The system features automated abuse detection using machine learning and keyword filtering to prevent cyberbullying and inappropriate content in real-time.

## ✨ Key Features

- **Real-time Chat Communication** - Users can send and receive messages instantly in defined chat rooms
- **Automated Abuse Detection** - Messages are automatically screened using machine learning models and keyword filters
- **Message Blocking and Feedback** - Abusive messages are blocked before delivery with immediate sender notification
- **User-Friendly Interface** - Simple login with room ID and username, clean chat interface
- **Session Management** - Users can start new chat sessions, exit gracefully, and manage room joining
- **Chat History Management** - Save conversation history to files and clear chat windows
- **Multi-User Support** - Supports multiple users across different devices on the same network

## 🛠 Technology Stack

- **Programming Language**: Python 3.x
- **GUI Framework**: Tkinter (built-in Python GUI library)
- **Networking**: Socket Programming (Python's socket module)
- **Machine Learning**: scikit-learn
- **Model Serialization**: joblib
- **Text Processing**: Regular Expressions (re module)
- **File Operations**: OS module
- **Additional Libraries**: threading, datetime (Python standard library)

## 📁 Repository Structure

```
text-shield-chatroom/
├── src/
│   ├── client.py          # Client-side GUI application
│   ├── server.py          # Server implementation
│   ├── text_classifier.py # Abuse detection module
│   └── utils.py           # Utility functions
├── models/
│   ├── trained_model.pkl  # Pre-trained ML model
│   └── vectorizer.pkl     # Text vectorizer
├── data/
│   └── keyword_filter.txt # Abusive keywords list
├── docs/
│   ├── setup.md          # Installation guide
│   └── user_guide.md     # User manual
└── tests/
    ├── test_client.py    # Client tests
    ├── test_server.py    # Server tests
    └── test_classifier.py # ML model tests
```

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or newer
- Standard Python libraries (Tkinter, socket, os, re)
- scikit-learn
- joblib

### Installation

```bash
# Clone the repository
git clone https://github.com/abhi-parekar/vc-chatroom-public.git
cd vc-chatroom-public

# Install required packages
pip install scikit-learn joblib

# Run the server
python src/server.py

# Run the client (in a new terminal)
python src/client.py
```

### Basic Usage

1. Start the server by running `python src/server.py`
2. Launch the client application with `python src/client.py`
3. Enter a Room ID and Username to join a chat session
4. Start messaging with real-time abuse detection
5. Use Save Chat to export conversation history
6. Use Clear Chat to clean the display
7. Click Exit to leave the chatroom

## 🛡 Abuse Detection System

The system employs a hybrid approach for detecting inappropriate content:

- **Machine Learning Classification**: Trained scikit-learn model for context-based detection
- **Keyword Filtering**: Regular expression-based pattern matching for explicit terms
- **Real-time Processing**: Messages are filtered before delivery to recipients
- **User Feedback**: Blocked messages trigger immediate warnings to senders

## 📋 Requirements

### Hardware Requirements
- Processor: Intel Core i7/i9 or AMD Ryzen 7/9
- RAM: 16GB or higher
- Storage: 512GB or higher
- Network: Wireless LAN adapter

### Software Requirements
- Operating System: Windows 10/11
- Python Interpreter: Python 3.8 or newer
- Editor/IDE: VSCode, Sublime Text, or IDLE
- Network Configuration: Open TCP port (default 12345)

## 🔗 Related Repository

- **Private Repository**: [vc-chatroom-private](https://github.com/abhi-parekar/vc-chatroom-private) - Contains complete implementation with advanced features and proprietary algorithms

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Contact

For technical support or questions about this project, please create an issue in this repository.

---

**Note**: This public repository contains the community version of the Text Shield Chatroom project. The complete implementation with advanced features is available in the private repository for authorized personnel only.
