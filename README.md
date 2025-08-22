# Medibot-AI Doctor Bot

A smart, conversational **AI-powered medical assistant** built with Flask and LangChain. Empowering users with accurate, fast, and private health guidance in a secure, intuitive environment.

---

## ✨ Features

- **Symptom Interpretation**  
  Utilizes LLM embeddings to understand user input and provide context-aware responses.

- **Deprecation-Ready Setup**  
  Replaces the deprecated `HuggingFaceEmbeddings` with the updated `langchain-huggingface` package.

- **Clean Architecture**  
  Backend with Flask, helper modules for embeddings and response management, and a responsive chat frontend with styled message bubbles preserving line breaks.

- **Local-First & Secure**  
  Runs entirely on your machine via WSL and Miniconda — no external servers required, keeping your data private.

---

## ⚡ Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/NeerajSuriya/Medibot-AI_Doctor_Bot.git
   cd Medibot-AI_Doctor_Bot
Create and activate your Conda environment

conda create -n medibot python=3.10
conda activate medibot


Install the dependencies

pip install -r requirements.txt


Install the updated embeddings support

pip install --upgrade langchain-huggingface

🚀 Setup & Run

Accept Terms of Service (TOS) for required Conda channels (if prompted):

conda config --set channel_priority flexible
conda tos accept --override-channels --channel https://repo.anaconda.com/pkgs/main
conda tos accept --override-channels --channel https://repo.anaconda.com/pkgs/r


Start the Flask backend

python app.py


Interact with your AI medical assistant
Visit http://127.0.0.1:8000 in your browser and start chatting!

💬 Usage & UI

Feel free to tweak the greeting message in the frontend. Some polished examples you could use:

👩‍⚕️ “Hi, I’m Dr. Ava – your AI Medical Assistant. How can I help you today?”
🤖 “Hello, I’m MediGPT – your trusted Health Bot. What would you like to know?”

These help make the experience welcoming and professional right from the start.

📂 Project Structure
Medibot-AI_Doctor_Bot/
├── app.py
├── src/
│   └── helper.py
├── static/
│   ├── styles.css
│   └── script.js
├── templates/
│   └── index.html
├── requirements.txt
└── README.md

🤝 Contributing

Contributions are welcome! To get involved:

Fork the repo

Create a feature branch (git checkout -b feature/symptom-logging)

Commit your enhancements (git commit -m "Add symptom logging")

Push (git push origin feature/symptom-logging)

Submit a Pull Request

Let’s make healthcare AI safer and more accessible together!

📜 License

This project is licensed under the MIT License — feel free to use, modify, and share! (Add a LICENSE file if not already present.)

👨‍💻 Contact

Built with ❤️ by Neeraj Suriya.
Questions? Feel free to open an issue or drop me a message on GitHub!