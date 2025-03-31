# Velo Blog Scraper

This is a Streamlit web app that scrapes all blog articles from [velo.com](https://www.velo.com/dk/da/opslagsvaerket), saves them as `.docx` files with embedded images, and lets you download them as a ZIP archive.

## 🚀 Features

- Scrapes paginated blog posts
- Saves content + images into Word documents
- Zips everything and provides a download link

## 🛠 How to Run

### Locally

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Run the app:

```bash
streamlit run app.py
```

### Deploy Online (e.g., Streamlit Cloud)

1. Push this project to a GitHub repository.
2. Go to [https://streamlit.io/cloud](https://streamlit.io/cloud).
3. Create a new app and select `app.py` as the entry point.
4. Deploy and start scraping!

## 📁 Files

- `app.py` – Main Streamlit application
- `requirements.txt` – Python dependencies
