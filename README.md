# 🦙 LLaMA Text Summarizer

A simple text summarization app using the **LLaMA model via Ollama**, powered by **FastAPI** (backend) and **Streamlit** (frontend). Run everything locally and summarize large chunks of text in seconds.

---

## 🔍 Overview

- 🔁 Summarize long text using LLaMA locally  
- ⚡ FastAPI backend to interact with the model  
- 🎨 Streamlit frontend for user interaction  
- 🧪 LLM runs locally using [Ollama](https://ollama.com)

---

## 🛠️ Tech Stack

- 🦙 **LLaMA** (via Ollama)  
- 🚀 **FastAPI** – RESTful backend  
- 🖥 **Streamlit** – Interactive frontend UI  
- 🗂 **Git/GitHub** – Version control & collaboration


---
# 📁 Project Structure
```
text-summarizer-llama/
├── backend/
│   └── main.py
├── frontend/
│   └── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## ⚙️ Setup Instructions

### Step 1: Environment Setup

```
$ python -m venv venv

# On Windows
$ venv\Scripts\activate

# On macOS/Linux
$ source venv/bin/activate
```

#### Install dependencies:

```
$ pip install -r requirements.txt
```

### Step 2: Install & Run Ollama

Download Ollama and install it.

#### Start Ollama and pull the LLaMA model:

```
$ ollama pull llama2
```

#### Run the App
Start the backend using FastAPI:

```
$ uvicorn backend.main:app --reload
```

Start the frontend using Streamlit:

```
$ streamlit run frontend/app.py
```

#### Then open the app in your browser, enter any text, and get a clean summary powered by LLaMA.


---
## 📃 License

This project is licensed under the MIT License.
Feel free to use, modify, and share with attribution.

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

---

## 🌐 Author
#### Hardik Sankhla

