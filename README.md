# NotesMaker

# Automated Note Generation Using Ollama & Mistral

## 📌 Project Overview
This project automates the creation of structured notes using **Ollama** and the **Mistral** language model. It reads a `.txt` file containing topics separated by commas, sends each topic as a prompt to the Mistral model, and generates well-organized notes.

## 🚀 Features
- Read topics from a `.txt` file
- Generate detailed notes using the Mistral model via **Ollama**
- Print notes directly in the output or save them to a file (`generated_notes.txt`)
- Simple, flexible, and easy to use

## 🛠️ Requirements
- Python 3.x
- Ollama installed locally
- Mistral model available in Ollama
- A `.txt` file with topics separated by commas

## 📖 How to Run
1. Install Ollama and ensure the **Mistral** model is available.
2. Create a file `topics.txt` with topics like:
   ```
   AI, Blockchain, Quantum Computing
   ```
3. Run the script:
   ```bash
   python generate_notes.py
   ```
4. View notes either in the output or in `generated_notes.txt`.

## 🧠 About the Mistral Model
Mistral is an advanced **Large Language Model (LLM)** designed for efficiency and high-quality text generation. It excels in understanding complex topics, structuring information, and creating meaningful summaries.

## 📂 File Structure
```
📂 Project Folder
 ├── topics.txt    # Input topics file
 ├── generate_notes.py  # Python script to process topics
 ├── generated_notes.txt  # (Optional) File where notes are saved
 ├── README.md  # Documentation for the project
```

## 🏗️ Future Enhancements
- Implement batch processing for efficiency
- Improve prompt engineering for optimized note generation
- Explore additional AI models for specialized topics

## 💡 Credits
Developed by [Your Name] using **Ollama + Mistral**.

```

---

### 📌 GitHub Repository Description
```
Automated Note Generation using Ollama & Mistral 🤖
📌 This project uses **Ollama** and the **Mistral** model to generate structured notes from a given list of topics in a `.txt` file. It supports both **printed output** and **file saving**.
🚀 Fast, efficient, and easy to use!

