# AI Spell Checker using Python and Gemini AI

## 📌 Project Overview

This project is an AI-powered spell checker developed using Python and Google's Gemini Flash API. It corrects spelling mistakes in user-provided text while preserving the original meaning of the sentence.

## ✨ Features

- Corrects spelling mistakes using AI.
- Accepts user input.
- Provides corrected text as output.
- Uses Google's Gemini Flash model through an API.
- Runs in a Jupyter Notebook.

## 🛠️ Technologies Used

- Python
- Google Gemini API
- Google Gen AI Python SDK
- Jupyter Notebook
- Python virtual environment (`venv`)

## 📂 Project Structure

```text
SpellChecker/
├── SpellChecker.ipynb
├── requirements.txt
├── README.md
├── .gitignore
└── .env (local only; not uploaded)
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Aishwarya11-cyber/Python-AI-Spell-Checker.git
cd Python-AI-Spell-Checker
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```powershell
.\venv\Scripts\Activate.ps1
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Configure the Gemini API key

Create a `.env` file in the project directory and add:

```text
GEMINI_API_KEY=your_api_key_here
```

Replace `your_api_key_here` with your own Gemini API key.

**Important:** Never upload your API key or `.env` file to GitHub.

### 5. Run the project

Open `SpellChecker.ipynb` in VS Code or Jupyter Notebook, select the project's Python environment, and execute the cells.

## 🧪 Example

**Input:**
```text
I hav a beautifull book.
```

**Output:**
```text
I have a beautiful book.
```

## 🎯 Objective

The objective of this project is to demonstrate how generative AI can be integrated into a Python application using an API to perform text correction.

## 👩‍💻 Author
Aishwarya Singh

