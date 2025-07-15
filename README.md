# 🛡️ Simple Anonymization Recipe with Ollama & Python Jupyter Notebooks

You don't have to paste senstitive data into Cloud LLMs & you don't have to manually parse your text which is resource intensive. Instead, with this little recipe you can use a local LLM model with Ollama, and Python Jupyter Notebook to clean that data before using it with ChatGPT or your preferred Cloud LLM.

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
