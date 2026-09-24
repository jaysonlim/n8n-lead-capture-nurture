# Lead Capture & Nurture Automation (n8n)

![Workflow](workflow.png)

## What it does
1. **Form submission** – a visitor fills out a contact form
2. **Spam filter** – submissions with no message get logged to a Spam tab
3. **Save lead** – real leads are added to Google Sheets
4. **Notify me** – I get an instant email alert
5. **Auto-reply** – the lead gets a thank-you email right away
6. **Follow-up** – a check-in email goes out 1 day later

## Why it matters
Most small businesses lose leads because they reply too slowly. This workflow responds instantly, logs every lead, and follows up automatically, with no manual work.

## Tools used
n8n · Google Sheets · Gmail

## How to use
1. Import `lead-capture-nurture.json` into n8n
2. Connect your Google Sheets and Gmail credentials
3. Replace `YOUR_SHEET_ID` and `your-email@example.com` with your own
4. Create a Google Sheet with `Name`, `Email`, `Message` headers, plus a `spam` tab
5. Publish the workflow and share the form's Production URL
