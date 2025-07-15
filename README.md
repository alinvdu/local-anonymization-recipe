# 🛡️ Simple Anonymization Recipe with Ollama & Python Jupyter Notebooks

Worried about sharing sensitive data with Cloud LLMs? Skip the hassle of manual text parsing and resource-heavy solutions. With this quick recipe, you can **anonymize your data locally** using an LLM model on your machine—powered by Ollama and Python Jupyter Notebooks. Clean up your text *before* using ChatGPT or any Cloud LLM, all while keeping your data private!

---

## 🚀 Steps to Get Started

1. **🔗 Download Ollama**  
   Head to the [Ollama website](https://ollama.com/download/mac) and grab the installer for your operating system (for MacOS, use the provided link).

2. **💾 Install & Set Up Ollama**  
   - Install Ollama.  
   - Open your **Terminal** and run:  
     ```bash
     ollama pull llama3
     ```
     _(This will download the Llama 3 model locally)_

3. **📓 Run the Anonymization Notebook**  
   - Open `anonymize.ipynb` in Jupyter Notebook.  
   - Input your data and run the cells to quickly anonymize your text!
