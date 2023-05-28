<p align="center">
  <img alt="PAutoBot" style="width: 128px; max-width: 100%; height: auto;" src="./docs/pautobot.png"/>
  <h1 align="center">🔥 PⒶutoBot 🔥</h1>
  <p align="center" style="font-size:18px">Private AutoGPT Robot - Your private task assistant with GPT!</p>
</p>

- **Ask questions** to your documents without an internet connection, using the power of LLMs. 100% private, no data leaves your execution environment at any point. You can ingest documents and ask questions without an internet connection! Engine developed based on [PrivateGPT](https://github.com/imartinez/privateGPT).
- **Automate tasks** easily with PAutoBot plugins. Easy for everyone!

![PAutoBot](./docs/screenshot.png)

**The supported extensions are:**

- `.csv`: CSV,
- `.docx`: Word Document,
- `.doc`: Word Document,
- `.enex`: EverNote,
- `.eml`: Email,
- `.epub`: EPub,
- `.html`: HTML File,
- `.md`: Markdown,
- `.msg`: Outlook Message,
- `.odt`: Open Document Text,
- `.pdf`: Portable Document Format (PDF),
- `.pptx` : PowerPoint Document,
- `.ppt` : PowerPoint Document,
- `.txt`: Text file (UTF-8),

## I. Installation

### 1. Backend

- Python 3.10 or higher.
- Install dependencies:

```shell
cd pauto-backend
pip install -r requirements.txt
```

- Run the backend:

```shell
uvicorn main:app --reload --port 5678
```

### 2. Frontend

- Node.js 16.0.0 or higher.
- Install dependencies:

```shell
cd pauto-frontend
npm install
```

- Run the frontend:

```shell
npm run dev
```

Go to <http://localhost:3000/> to see the app.