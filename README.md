# Remote Jobs Scraper

This Python script scrapes the latest remote developer jobs from [Remote OK](https://remoteok.com) and outputs job data such as title, company, tags, and links. It’s built using `requests`, `BeautifulSoup`, and `pandas`.

## Features

- Scrapes job listings from Remote OK
- Extracts:
  - Job Title
  - Company Name
  - Tags (skills/technologies)
  - Job URL
- Saves the data to a CSV file (`remote_jobs.csv`)
- Ready for automation or notifications

## Setup

1. Clone the repository

```bash
git clone https://github.com/Omeraluf/Remote-jobs-scraper
cd remote-jobs-scraper
```

2. Create a virtual environment (optional but recommended)
```bash
python -m venv venv
```

3. Activate the virtual environment
```bash
source venv/bin/activate \ venv/Scripts/activate
```

4. Install the required dependencies
```bash
pip install -r requirements.txt
```

5. Run the Script
```bash
python main.py
```

## Project Structure

```bash
remote-jobs-scraper/
├── scraper.ipynb        # Main scraping notebook (Jupyter)
├── remote_jobs.csv      # Output CSV with job listings
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation
├── LICENSE              # Open-source license
├── .gitignore           # Files to exclude from Git
└── venv/                # Python virtual environment (excluded from Git)
```

## Future Ideas
 * Add filters for tags and salary
 * Send Emails \ Telegram \ Whatsapp updates for new jobs
 * Build a bootstrap based website to view scraped jobs in a clean UI