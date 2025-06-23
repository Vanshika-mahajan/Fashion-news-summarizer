# Fashion-news-summarizer
# 🧠 Fashion & Entertainment Website Summarizer

This project scrapes content from fashion, Bollywood, Hollywood, and entertainment websites, and uses a **local LLM via Ollama** to generate clear, concise, and engaging summaries.

## ✨ Features

- 🔍 Scrapes web content using `requests` and `BeautifulSoup`
- 🧼 Cleans up irrelevant HTML elements like scripts, images, and styles
- 🧠 Sends cleaned text to a **locally running LLM model** (via [Ollama](https://ollama.com))
- 📄 Generates summaries in **plain text** or **Markdown** format
- 🧑‍🎤 Focused on:
  - Fashion trends
  - Celebrity style
  - TV and movie gossip
  - Pop culture updates

---

## 🚀 Technologies Used

| Tool | Purpose |
|------|---------|
| 🐍 Python | Core programming language |
| 🧼 BeautifulSoup | Web scraping and HTML parsing |
| 🧠 OpenAI (with Ollama backend) | Language model interaction |
| 💻 Jupyter Notebook | Interactive development and testing |
| 🌐 Ollama | Local LLM hosting (like `llama3`) |

---

## 📦 How to Run the Project

### 🔧 Requirements

- Python 3.8+
- [Ollama installed & running locally](https://ollama.com/)
- Model pulled (e.g. `llama3.2`):
- ollama run llama3.2

### 🛠 Installation

```bash
pip install openai requests beautifulsoup4 lxml python-dotenv


### ▶️ Run the Notebook

1. Start Ollama in terminal:  
   ```bash
   ollama run llama3
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open the `.ipynb` notebook and run each cell in order.

---

## 🧪 Example Output

```
🔗 https://www.pinkvilla.com

📄 Summary:
- Kareena Kapoor stuns in a denim jacket at the airport.
- Vogue India highlights trending 90s throwback looks.
- Alia Bhatt attends a wedding in elegant pastels.
```

---

## 📁 File Structure

```
📦 fashion-summarizer/
├── Untitled.ipynb           # Main notebook with scraping + summarization
├── README.md                # Project documentation (this file)
```

---

## 🙋‍♀️ Author

**Vanshika Mahajan**  
> Passionate about Generative AI, fashion-tech, and practical NLP apps.  
> *(Add your LinkedIn, GitHub, or portfolio link here if you want)*

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
