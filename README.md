
````markdown
# 📄 LLM-Based PDF Summarizer & Notes Generator

This project automates the process of **extracting, cleaning, and summarizing** content from PDF files using **Large Language Models (LLMs)** via **LangChain** and **Google Generative AI**.  
It then formats the output into a well-structured **Word document (DOCX)** with optional images — perfect for creating study notes, research summaries, or concise reports.

---

## 🚀 Features

- 📘 **PDF Text Extraction** – Uses `pdfminer.six` to extract readable text from PDF files.  
- 🧹 **Text Cleaning** – Removes unwanted symbols, whitespace, and page artifacts.  
- 🧩 **Automatic Sectioning** – Organizes text into logical sections based on headings or patterns.  
- 🧠 **AI Summarization** – Summarizes each section using **LangChain** + **Google Generative AI**.  
- 📝 **Formatted Output** – Generates a clean `.docx` document with structured summaries.  
- 💾 **Easy Export** – Automatically saves and offers a download link for the final document.

---

## 🧰 Requirements

Install the required dependencies before running the notebook:

```bash
pip install pdfminer.six langchain langchain_google_genai python-docx
````

You can also install them directly from within the notebook:

```python
!pip install pdfminer.six langchain_google_genai python-docx langchain
```

---

## ⚙️ Usage

1. **Upload the PDF** you want to summarize.
2. **Run the notebook** cells in order.
3. The notebook will:

   * Extract and clean text from the PDF.
   * Split it into sections.
   * Generate AI-based summaries for each section.
   * Export a formatted `.docx` file.
4. **Download your summarized document** when prompted (usually named `final_notes_with_images_new.docx`).

---

## 🧠 Tech Stack

* **Python 3**
* **LangChain** – for building summarization chains
* **Google Generative AI** – for large language model summarization
* **pdfminer.six** – for PDF text extraction
* **python-docx** – for document creation and formatting

---

## 📂 Output Example

Example output file:

```
final_notes_with_images_new.docx
```

A neatly formatted summary document with each PDF section condensed into short, readable notes.

---

## 🧾 License

This project is open source and available under the [MIT License](LICENSE).


