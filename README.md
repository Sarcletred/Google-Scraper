# Google-Scraper
A simple Google Scraping extension to scrape google

Google Maps Scraper – Chrome Extension
A simple Chrome extension to scrape business data from Google Maps and export it as a CSV file.
Developed by Gagana Sree.

📌 Features
Scrapes business details from Google Maps search results.

Displays extracted data in a clean, tabular format.

Allows exporting the results as a .csv file.

Modern UI using Poppins font with a purple & orange theme.

📂 Project Structure
bash
Copy
Edit
📦 GoogleMapsScraper
 ┣ 📜 manifest.json         # Chrome extension manifest file
 ┣ 📜 popup.html            # Extension UI (this file)
 ┣ 📜 popup.js              # Main scraping & UI logic
 ┣ 📜 styles.css (optional) # Custom styles (currently inline in HTML)
 ┗ 📜 README.md              # Project documentation
🚀 How to Install
Download or clone this repository.

Open Google Chrome and go to:

arduino
Copy
Edit
chrome://extensions/
Enable Developer Mode (toggle in top-right corner).

Click "Load unpacked" and select the project folder.

The Google Maps Scraper icon will appear in your Chrome toolbar.

🛠 How to Use
Open Google Maps and search for a business category or location (e.g., coffee shops in New York).

Click the Scrape Google Maps button in the extension popup.

Wait for the scraper to collect the results.

Enter a file name in the input field.

Click Download as CSV to save the data locally.

📊 Data Collected
The scraper extracts:

Business Name

Address

Phone Number (if available)

Website (if available)

Ratings & Reviews (if available)

⚠ Disclaimer
This tool is for educational and personal use only. Scraping Google Maps may violate Google’s Terms of Service. Use responsibly.

