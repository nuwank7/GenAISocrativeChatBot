# 🎓 Socrative Chatbot for Universities

This repository contains the source code and deployment guide for a **Socratic-style AI chatbot** designed for use within a **university or educational institute**. The chatbot engages students in guided, question-driven learning rather than simply providing answers — promoting **critical thinking** and **deep understanding** of concepts.

---

## ✨ Key Features

- 💬 **Socratic Dialogue**: Asks students questions to guide their thinking and learning process.
- 🧠 **Context Awareness**: Remembers conversation history to build coherent, intelligent conversations.
- 🔐 **Institution-Hosted**: Runs securely within the university's infrastructure (on-prem or cloud).
- 🎯 **Customizable**: Tailor to specific subjects, academic levels, or teaching styles.
- 🧑‍🏫 **Instructor Tools**: Includes optional logging and feedback for teachers to track student progress.

---

## 🏫 Use Cases

- Virtual teaching assistant for undergraduate courses  
- Self-guided revision or assessment preparation  
- Support for flipped classroom models  
- Learning companion for research-based education

---

## 🛠️ Tech Stack

- **Backend**: Python / Node.js (flexible based on integration)  
- **LLM Integration**: OpenAI / Azure OpenAI / Custom LLMs  
- **Frontend**: Web chat interface (React or HTML/JS)  
- **Hosting**: University servers or cloud (AWS, Azure, GCP)  
- **Security**: University SSO (OAuth2/SAML support)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+ (or Node.js 18+)  
- OpenAI API key (or equivalent LLM backend)  
- Docker (optional for containerized deployment)

### Installation

```bash
git clone https://github.com/your-org/socratic-chatbot.git
cd socratic-chatbot
pip install -r requirements.txt
```

### Running Locally

```bash
export OPENAI_API_KEY=your-api-key
python app.py
```

Visit `http://localhost:5000` to chat with the bot.

---

## 🧩 Customization

You can:

- Configure the **tone and questioning style** in `config/behavior.json`  
- Add **subject-specific prompts** in `prompts/`  
- Enable **analytics and instructor feedback** features in `settings.py`

---

## 📚 Example Conversations

```plaintext
Bot: What do you understand by "recursion" in programming?  
Student: It’s when a function calls itself.  
Bot: That’s correct. Why might that be useful? Can you think of a situation where recursion simplifies a problem?
```

```plaintext
Bot: Why do you think democracies often have checks and balances?  
Student: To prevent abuse of power.  
Bot: Good point. Can you explain how this is implemented in a typical government?
```

```plaintext
Bot: You mentioned Newton’s third law. Can you apply it to a real-life example outside of physics class?  
Student: Maybe jumping off a boat?  
Bot: Exactly — what happens to the boat when you jump forward?
```

---

## 🔒 Security & Privacy

This chatbot is designed for **self-hosted deployment**, ensuring:

- Student data stays within the institution  
- Compliance with local data protection and university policies  
- No third-party tracking or external data exposure  

---

## 🤝 Contributing

We welcome contributions from the academic and open-source communities!

1. Fork the repository  
2. Create your feature branch: `git checkout -b feature/YourFeature`  
3. Commit your changes: `git commit -m 'Add some feature'`  
4. Push to the branch: `git push origin feature/YourFeature`  
5. Open a pull request  

See `CONTRIBUTING.md` for more detailed guidelines.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE.md). You are free to use, modify, and distribute it with attribution.

---

## 📬 Contact

For deployment, collaboration, or support inquiries, please contact:  
**Centre of Excellence for AI – SLIIT**  
📧 [nuwan.k@sliit.lk](mailto:nuwan.k@sliit.lk)

---
