# 🤖 DevFest Registration AI Agent

Welcome to the **DevFest Registration AI Agent**! This project demonstrates how to build a conversational AI agent using **Gemini** (Google's generative AI) and **Google Sheets** to automate and streamline event registration for DevFest.

## 🌟 Project Highlights

- Conversational agent powered by **Gemini**
- Collects user registration details via natural dialogue
- Stores responses directly into a **Google Sheet**
- Demonstrates prompt engineering and API integration
- Built entirely in a **Jupyter Notebook** for easy experimentation

## 🧰 Technologies Used

| Tool              | Purpose                                  |
|-------------------|-------------------------------------------|
| Gemini API        | Conversational AI and prompt handling     |
| Google Sheets API | Data storage and retrieval                |
| Python            | Core scripting and API orchestration      |
| Jupyter Notebook  | Interactive development environment       |

## 📦 Setup Instructions
### Install dependencies

Make sure you have Python 3.8+ installed, then run: 
 pip install -r requirements.txt
### Configure Google Sheets API
Go to Google Cloud Console

Create a new project and enable the Google Sheets API

Create credentials for a Service Account

Download the credentials.json file and place it in your project directory

Share your target Google Sheet with the service account email (found in the credentials)

### Set up Gemini API
Visit Google AI Studio to generate your Gemini API key

Add the key to your environment or directly into the notebook: 
```
GEMINI_API_KEY = "your-api-key-here"
```
### Run the notebook
Launch Jupyter and open the notebook: 
```
jupyter notebook DevFest_Reg_AI_Agent.ipynb
```

### 🧠 How It Works
The user interacts with the agent via text prompts.

Gemini generates responses and asks for registration details.

Once collected, the data is validated and written to a Google Sheet.

The agent confirms successful registration.

### 📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

### 🙌 Acknowledgments
Inspired by DevFest and Google’s Gemini API

Built with ❤️ by Saudatu

### Clone the repository
```bash
git clone https://github.com/Saudii81/devfest_ai_agent.git
cd devfest_ai_agent
```
You can copy this directly into your repo’s `README.md` file. Let me know if you’d like to add a badge, screenshot, or demo link next!
