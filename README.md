# Remote Jobs Scraper

This Python script scrapes the latest remote developer jobs from [Remote OK](https://remoteok.com) and outputs job data such as title, company, tags, and links. It’s built using `requests`, `BeautifulSoup`, and `pandas`.

## Features

- Scrapes job listings from Remote OK
- Extracts:
  - Job Title
  - Company Name
  - Tags (skills/technologies)
  - Job URL
- Saves the data to a CSV file (`jobs.csv`)
- Ready for automation or notifications

## Setup

1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/remote-jobs-scraper.git
cd remote-jobs-scraper
```

2. Create a virtual environment (optional but recommended)
```bash
python -m venv venv
```

3. Activate the virtual environment
```bash
source venv/bin/activate
```

4. Install the required dependencies
```bash
pip install -r requirements.txt
```

5. Run the Script
```bash
python main.py
```
