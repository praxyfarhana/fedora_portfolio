
# My Outreachy Internship Fedora-Ramalama Portfolio

This repository hosts my contribution portfolio for the **Outreachy Internship** with the **Fedora Community**. It documents my journey in developing an SLM/LLM using **Ramalama RAG**, based on Fedora RPM Packaging Guidelines.

## Live Portfolio

You can view the live, hosted version of this portfolio here:
**[https://praxyfarhana.github.io/fedora\_portfolio\_outreachy/](https://www.google.com/search?q=https://praxyfarhana.github.io/fedora_portfolio_outreachy/)**

-----

## 🛠 Project Overview

The focus of this contribution period is exploring document processing and retrieval-augmented generation (RAG) within the Fedora ecosystem. Key highlights include:

  * **Docling Implementation:** Deep dive into document parsing, multilingual OCR, and format conversions (JSON, HTML, Markdown).
  * **Technical Troubleshooting:** Resolved critical `std::bad_alloc` memory crashes during multi-PDF parsing.
  * **Ramalama & RAG:** Leveraging Fedora RPM guidelines to build efficient Small Language Models (SLM).

## 📂 Repository Structure

  * `index.html`: The main landing page for the GitHub Pages site.
  * `styles.css`: Custom styling for the portfolio interface.
  * `images/`: Contains profile pictures and project screenshots.
  * *(Add any scripts or sample data folders here)*

-----

## 📝 Contribution Milestones

### 1\. Pre-requisite Tasks

Completed essential community setup including the **Fedora Account System (FAS)** and initial community engagement via blog posts.

### 2\. Docling Exploration

  * **Environment Setup:** Configured Python virtual environments on **Fedora (WSL)**.
  * **Format Comparison:** Analyzed performance and output quality across various Docling export formats.
  * **Bug Resolution:** Documented and fixed memory allocation errors encountered during high-volume document processing.

### 3\. Community Engagement

Active participation in the Fedora Discussion forums and technical blogging on Medium to help other newcomers.

-----

## 👩‍💻 About the Author

**Farhana Agufa**

  * Data Scientist & Python Specialist
  * Cloud Computing Enthusiast
  * Open Source Contributor

-----

## 🛠 How to Run Locally

If you want to view the code on your local machine:

1.  Clone the repository:
    ```bash
    git clone https://github.com/praxyfarhana/fedora_portfolio_outreachy.git
    ```
2.  Open `index.html` in any web browser.

-----

### 💡 Note for Mentors

This portfolio is a living document. It will be updated regularly throughout the Outreachy contribution period to reflect new technical tasks, code snippets, and project outcomes.

-----

### ⚠️ A Small Fix for your `index.html`

In the code you provided, your image source is a **local Windows path**:
`src="C:\Users\MAYKISH\Desktop\..."`

**This will not work on GitHub Pages** because GitHub doesn't have access to your "C:" drive. You should change that line in your `index.html` to a relative path:

```html
<img src="images/Farhana_png.png" alt="Profile Picture">
```

*(Make sure the folder in your GitHub repo is named `images` and the file is inside it\!)*
