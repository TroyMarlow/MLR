# Major League Rugby Schedule Scraper and Calendar Generator

This repository contains a script to scrape the Major League Rugby schedule and generate an `.ics` file for calendar subscription. The `.ics` file is updated monthly using GitHub Actions.

## Files
- `schedule_scraper.py`: Python script to scrape the schedule and generate the `.ics` file.
- `.github/workflows/update_schedule.yml`: GitHub Actions workflow to automate updates.

## How to Use
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python schedule_scraper.py
   ```

The `.ics` file will be generated and hosted in this repository.

## Automation
The schedule is updated automatically on the first day of every month using GitHub Actions.
