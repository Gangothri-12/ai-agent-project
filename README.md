
# 🤖 AI Agent Web UI

This project sets up a browser-based AI Agent using Playwright and Gemini API. It provides a simple and interactive interface to run intelligent agents directly from your browser.

---

## 📦 Requirements

- Python 3.11
- Git
- curl
- uv (a fast Python package/dependency manager)
- Gemini API Key (from Google AI Studio)

---

## 🚀 Setup Instructions

### 1. Install Dependencies
```bash
pip3 install browser-use
playwright install
```

### 2. Clone the Project
```bash
mkdir ai-agent
cd ai-agent
git clone https://github.com/browser-use/web-ui
cd web-ui
```

### 3. Install uv and Create Virtual Environment
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
uv venv --python 3.11
source .venv/bin/activate
```

### 4. Install Requirements
```bash
uv pip install -r requirements.txt
```

### 5. Start the Web UI
```bash
python webui.py --ip 127.0.0.1 --port 7788
```

Open your browser and go to: [http://127.0.0.1:7788](http://127.0.0.1:7788)

### 6. Add Gemini API Key

- Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
- Copy your Gemini API key
- Paste it into the browser UI when prompted

### 7. Run Agent

Click **Run Agent** on the interface to start your AI agent.

---

## 📁 Project Structure

```
ai-agent/
└── web-ui/
    ├── webui.py
    ├── requirements.txt
    ├── static/
    └── templates/
```

---

## 🧠 Features

- Local web interface for AI agents
- Browser automation using Playwright
- Uses Gemini API for AI power

---

## 📄 License

This project is licensed under [MIT License](LICENSE).
