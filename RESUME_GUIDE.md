# Resume Setup Guide

## How to Add Your Resume

1. **Convert your resume to PDF format** (if not already)
   - Open your resume in Word/Google Docs
   - Go to File → Save As → PDF
   - Or File → Download → PDF Document

2. **Rename the PDF file**
   - Name it exactly: `Nikhil_Resume.pdf`

3. **Place the file in the portfolio root folder**
   - Copy `Nikhil_Resume.pdf` to: `PORTFOLIO/nikhil-portfolio/`
   - It should be in the same folder as `index.html`

## File Location:
```
PORTFOLIO/nikhil-portfolio/
├── index.html
├── style.css
├── script.js
├── Nikhil_Resume.pdf  ← Your resume goes here
└── images/
```

## Features:

### Navigation Bar:
- **Resume Button** - Opens PDF preview in new tab
- Icon changed to PDF icon (instead of download)

### Dedicated Resume Section:
- Large PDF icon with gradient background
- Two action buttons:
  - **Preview Resume** - Opens PDF in browser (new tab)
  - **Download PDF** - Downloads the file directly
- Shows file format and last updated date

## Testing:

1. Add your `Nikhil_Resume.pdf` file
2. Open `index.html` in browser
3. Click the "Resume" button in navigation → Should open PDF preview
4. Scroll to Resume section
5. Click "Preview Resume" → Opens in new tab
6. Click "Download PDF" → Downloads the file

## Tips:

- Keep PDF file size under 2MB for faster loading
- Ensure PDF is not password protected
- Use a professional resume template
- Update the "Updated Dec 2025" text in HTML if needed

## Troubleshooting:

**If PDF doesn't open:**
- Check file name is exactly `Nikhil_Resume.pdf`
- Check file is in the correct folder
- Try opening the HTML file from a local server
- Some browsers block local file access - upload to web hosting

**If download doesn't work:**
- The download attribute works best on hosted websites
- For local testing, right-click → Save As works too
