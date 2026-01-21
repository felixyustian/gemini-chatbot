# Gemini Chatbot (Node.js & Jupyter)

A dual-purpose repository featuring an interactive web-based chatbot powered by Google's Gemini API (Node.js) and a prototyping notebook for experimenting with the model's capabilities.

## 📂 Project Overview

This project provides two main implementations for interacting with Google Gemini:

1.  **Web Application (Node.js)**: A fully functional chatbot with a web frontend (`static/`) and a Node.js backend (`index.js`).
2.  **Experimentation (Jupyter Notebook)**: A detailed notebook (`Gemini_Part_2_Revamped.ipynb`) for testing API calls, refining prompts, and understanding the model's logic before deployment.

## 🚀 Features

* **Google Gemini Integration**: Utilizes Google's Generative AI models for natural language processing.
* **Interactive Web UI**: Clean HTML/CSS/JS frontend for real-time chatting.
* **Custom Prompts**: Structured system instructions located in the `prompts/` directory.
* **Prototyping Environment**: Includes a Jupyter Notebook for testing and development.

## 🛠️ Technology Stack

* **Backend**: Node.js
* **Frontend**: HTML5, CSS3, Vanilla JavaScript
* **Analysis/Prototyping**: Jupyter Notebook (Python)
* **API**: Google Generative AI (Gemini)

## 📋 Prerequisites

* [Node.js](https://nodejs.org/) (v16+ recommended)
* [Python 3.x](https://www.python.org/) & Jupyter (for the notebook)
* **Gemini API Key** from [Google AI Studio](https://aistudio.google.com/)

---

## 🔧 Setup: Web Application (Node.js)

1.  **Install Dependencies**
    ```bash
    npm install
    ```

2.  **Configure API Key**
    * Open `index.js` (or create a `.env` file if supported by the code) and insert your Google Gemini API Key.
    * *Security Note: It is best practice to use environment variables (e.g., `process.env.API_KEY`) rather than hardcoding keys.*

3.  **Run the Server**
    ```bash
    node index.js
    ```

4.  **Access the Chatbot**
    Open your browser and navigate to `http://localhost:3000` (check console for exact port).

---

## 📓 Setup: Jupyter Notebook

1.  **Install Python Dependencies**
    Ensure you have the necessary libraries installed (likely `google-generativeai`):
    ```bash
    pip install google-generativeai notebook
    ```

2.  **Launch the Notebook**
    ```bash
    jupyter notebook Gemini_Part_2_Revamped.ipynb
    ```

3.  **Run Cells**
    Follow the step-by-step instructions inside the notebook to authenticate and test the API.

## 📂 Repository Structure

```text
gemini-chatbot/
├── index.js                      # Main Node.js server
├── package.json                  # Node.js dependencies
├── Gemini_Part_2_Revamped.ipynb  # Prototyping Notebook
├── prompts/                      # System prompts
├── static/                       # Frontend assets (HTML/CSS/JS)
├── notes.md                      # Development notes
└── README.md                     # Documentation
```

## 📄 License
This project is licensed under the GPL-3.0 License. See the LICENSE file for details.
