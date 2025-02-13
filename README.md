# ChatCotz-Bot

## 📌 Overview
This project is a simple chatbot designed to respond to user queries using predefined responses from a dataset. The chatbot processes input questions and matches them with the most relevant answer. It is implemented in Python using Jupyter Notebook and utilizes an Excel dataset for question-response mapping.

## 🚀 Features
- **Rule-based responses**: Matches user input with predefined responses.
- **Excel dataset integration**: Stores and retrieves responses from an external `.xlsx` file.
- **User-friendly interface**: Provides a simple way to interact with the chatbot.
- **Customizable responses**: Easily extendable by updating the dataset.

## 📂 Project Structure
```
📁 ChatCotz-Bot
│── 📄 Chatbot.ipynb  # Jupyter Notebook containing the chatbot logic
│── 📄 QUESTION RESPONSE CHATBOT.xlsx  # Dataset with predefined Q&A
│── 📄 README.md  # Documentation
```
## 📊 Dataset
`QUESTION RESPONSE CHATBOT.xlsx` contains a list of questions and answers used for the chatbot. You can adjust or add data as needed.

## 🛠️ Requirements
Ensure you have the following dependencies installed:
- Python 3.9 or later
- Jupyter Notebook
- Pandas
- Tkinter
- Rapidfuzz

## 🔧 How to Run
1. **Clone repository**
   ```bash
   git clone https://github.com/mrzlsyf/ChatCotz-Bot.git
   cd ChatCotz-Bot
   ```
2. **Install dependencies**
   Make sure you have installed Python and Jupyter Notebook.  For the additional libraries needed, install with:
   ```bash
   pip install pandas tk rapidfuzz
   ```
3. Open the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
4. Load and run the `Chatbot.ipynb` file.
5. Interact with the chatbot by entering a question.

## 📌 How It Works
- The chatbot loads predefined question-response pairs from the Excel file.
- When a user inputs a question, it searches for the best matching response.
- The chatbot returns the corresponding response if found; otherwise, it provides a default fallback answer.

## 🎯 Future Enhancements
- Implement **NLP-based matching** for better response accuracy.
- Develop a **GUI-based interface** for better user interaction.
- Expand the dataset with more diverse queries.
- Integrate with **AI models** for intelligent responses.

## 🤝 Contributing
Feel free to fork this repository, suggest improvements, or submit pull requests!

---
🚀 *Happy Coding!*
