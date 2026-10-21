# StreamScraper Pro v4.6 - AI Language & Stream Validator Engine

StreamScraper Pro is an advanced web-scraping and directory ingestion tool powered by Gemini AI. It allows you to parse scattered streaming directories (such as `https://fmhy.net/video#streaming-sites`), manage custom provider search routing patterns, validate server audio tracks (Hindi, English, Japanese, Dual Audio), check stream quality (1080p, 4K), and export clean Python BeautifulSoup scraper scripts.

---

## Features

- **Gemini AI Directory Ingestion**: Automatically parse 50+ scattered streaming site links from raw HTML DOM dumps or Markdown lists.
- **Provider-Specific Native Routing**: Custom URL route pattern mapping (`{query}` and `{slug}` variables) for accurate streaming endpoint generation.
- **AI Audio Language Validator**: Filters out dead streams or incompatible audio setups by verifying server track compatibility before returning working URLs.
- **Automated Unit & Integration Tests**: Built-in test suite verifying system integrity, URL generation, and audio track filters.
- **Python Script Exporter**: Export standalone BeautifulSoup Python scripts for both AI directory crawlers and provider-specific smart audio scrapers.

---

## Local Setup & Installation

Follow these steps to run the application locally on your computer:

### 1. Clone the Repository
Open your terminal and clone your GitHub repository:
```bash
git clone https://github.com/rajmgs/streamscraper-pro.git
cd streamscraper-pro
```

### 2. Run the Application
Since StreamScraper Pro is built as a self-contained, high-performance HTML/JS application with Tailwind CSS and FontAwesome, you do not need complex Node.js or Python backend servers to view the dashboard!

Simply open **`stream_scraper.html`** in any modern web browser (Google Chrome, Brave, Firefox, Edge):
- **Mac:** Double-click `stream_scraper.html` or run `open stream_scraper.html`
- **Windows:** Double-click `stream_scraper.html` or open it in your browser.
- **Linux:** Run `xdg-open stream_scraper.html`

*(Optional)* If you prefer running a local development server (e.g., to test Python export scripts):
```bash
# Using Python 3 built-in HTTP server
python3 -m http.server 8080
```
Then open `http://localhost:8080/stream_scraper.html` in your browser.

---

## Pushing to GitHub

To push these files to your GitHub repository, execute the following commands in your project root:

```bash
git init
git add stream_scraper.html README.md
git commit -m "Initial commit: StreamScraper Pro v4.6 AI Audio Engine & Setup"
git branch -M main
git remote add origin https://github.com/rajmgs/streamscraper-pro.git
git push -u origin main
```

---

## License
MIT License. Free to use for personal and development purposes.