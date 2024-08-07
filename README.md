# Audiobook Creation Project

## Objective
The goal of this project is to scrape text content from specific web pages and convert it into an audiobook using text-to-speech technology.

## Steps Involved
1. **Web Scraping**: Extract text content from multiple chapters of a book from specified URLs.
2. **Text Processing**: Clean and format the extracted text for audio conversion.
3. **Text-to-Speech Conversion**: Convert the formatted text into an audio file using a text-to-speech tool.

## Detailed Steps

### 1. Web Scraping
- **Tools**: Python, `requests`, `BeautifulSoup`
- **URLs**: Provided for each chapter (e.g., `https://fast.novelupdates.net/book/invincible-divine-sword/chapter-1-martial-soul-world`, `https://fast.novelupdates.net/book/invincible-divine-sword/chapter-2-2-grandpas-favoritism`, etc.)
- **Target Element**: HTML `div` with class `col-xs-12`
