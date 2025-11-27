# SOP - Setup, Automation & Monetization

1. Create Google Sheet with columns:
   id, title, description, reward, time_min, url, source, tags, affiliate

2. Publish the sheet (File -> Publish to web) and copy the sheet ID.

3. Update `src/components/MicroTaskHub.jsx` with your SHEET_ID.

4. Make.com scenario:
   - Scheduler: every 2 hours
   - HTTP GET modules to fetch offer pages
   - HTML parser to extract title, desc, reward
   - Formatter to clean fields and set uuid
   - Google Sheets > Add row (map fields)

5. Monetization:
   - Add affiliate links into `affiliate` column
   - Add Google AdSense script in index.html template
   - Sell $7 starter bundle via Gumroad (link in header)
