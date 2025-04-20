```markdown
# ♻️ E-waste Bot

**E-waste Bot** is a conversational AI assistant built using `pydantic-ai` and `groq`, designed to educate and guide users about electronic waste management, recycling, and creative reuse ideas. It features session-based memory and real-time web search integration to deliver dynamic, intelligent responses.

---

## 🌟 Features

- 🔁 **Session-Based Memory** – Maintains context across the conversation.
- 🌐 **Web Search Integration** – Fetches real-time information using Tavily.
- 🤖 **Role-Based Prompting** – Custom system prompts for contextual relevance.
- 💡 **Creative Reuse Suggestions** – Offers unique upcycling ideas for e-waste.
- 🖥️ **Interactive Streamlit UI** – Clean, responsive frontend experience.

---

## 🗂️ Project Structure

E-waste-Bot/
│
├── .env                  # Environment variables (API keys)
├── .gitignore            # Git ignore rules
├── .python-version       # Python version spec
├── pyproject.toml        # Project metadata and dependencies
├── README.md             # Project documentation
├── test.py               # CLI chatbot script
├── search.py             # Tavily tool testing
└── app.py                # Streamlit web app

---

## 🛠️ Requirements

- **Python** 3.13+
- **pydantic-ai** 0.0.24+
- **streamlit** 1.0.0+
- **python-dotenv** 1.0.1+

---

## 🚀 Installation

1. **Clone the repository**

```bash
git clone https://github.com/karan4533/E-waste-Bot.git
cd E-waste-Bot
```

2. **Create and activate a virtual environment**

```bash
python -m venv .venv

# On Windows
.venv\Scripts\activate

# On macOS/Linux
source .venv/bin/activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

_Or using [uv](https://github.com/astral-sh/uv) (recommended):_

```bash
uv sync
```

4. **Set up environment variables**

Create a `.env` file in the root directory and add your API keys:

```env
GROQ_API_KEY=<your-groq-api-key>
TAVILY_API_KEY=<your-tavily-api-key>
```

---

## 💬 Usage

### ▶️ Run the CLI Chatbot

```bash
python test.py
```

### 🖥️ Launch the Streamlit Web App

```bash
streamlit run app.py
```

---

## 📌 Notes

- Ensure your `.env` is correctly configured with valid keys.
- The chatbot uses Tavily to fetch real-time web results.
- This project is part of a broader educational initiative on sustainable tech.

---

## 👤 Author

Made with ❤️ by [@karan4533](https://github.com/karan4533)

---

```

Would you like me to add GitHub badges (Python version, license, etc.) at the top or include a **Contributing** section for collaborators?
