# Professional Local Form + Excel Storage

This project provides a polished local form to collect:

- First name
- Last name
- Email
- Company

When submitted, entries are saved to a local Excel workbook (`data/submissions.xlsx`).

## Run locally

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Start the app:

   ```bash
   python app.py
   ```

3. Open in browser:

   ```
   http://127.0.0.1:5000
   ```

## Output data

- File location: `data/submissions.xlsx`
- Sheet name: `Form Submissions`
- Columns: Submitted At, First Name, Last Name, Email, Company
