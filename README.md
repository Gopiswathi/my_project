# my_project
## Project Description
This repository contains a CSV file `data/emails.csv` that stores email records for support and subscription queries. The CSV file can be updated manually on GitHub or automatically using a Python script via the GitHub API.

## File Structure
- `data/emails.csv` - Contains email data in CSV format.
- `README.md` - Project information.
- `update_emails.py` - Optional Python script to automate CSV updates (if using).

## CSV Columns
- `sender` - Email sender
- `subject` - Subject of the email
- `body` - Email content
- `sent_date` - Date and time the email was sent

## Usage

### Option 1: Update manually
1. Open the repository on GitHub.
2. Navigate to `data/emails.csv`.
3. Click the **Edit** button (pencil icon) to modify the CSV content.
4. After editing, scroll down and click **Commit changes**.

### Option 2: Update using Python script
1. Make sure Python 3 is installed on your machine.
2. Install the `requests` library (if not installed):
   ```bash
   pip install requests
