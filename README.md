# WeMeet Tombstone Page

This repository contains the static tombstone page for WeMeet, displayed when the service is discontinued.

## Purpose

This page serves as a farewell message to users after WeMeet BV discontinues its operations on September 1, 2025. It provides:

- Official announcement of service discontinuation
- Information about data handling and refunds
- Contact details for final questions
- Both Dutch and English versions of the message

## GitHub Pages Setup

To deploy this page using GitHub Pages:

1. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

2. **Custom Domain Setup** (for DNS redirection):
   - In the "Pages" settings, add your custom domain (e.g., `wemeet.nl`)
   - Create a `CNAME` file in the repository root with your domain name
   - Update your DNS settings to point to GitHub Pages:
     - Create a CNAME record pointing to `[username].github.io`
     - Or use A records pointing to GitHub's IP addresses

3. **DNS Configuration**:
   ```
   Type: CNAME
   Name: @
   Value: [your-github-username].github.io
   ```

## File Structure

```
/
├── index.html          # Main HTML page
├── style.css           # Styling with WeMeet brand colors
├── assets/
│   └── wemeet-logo.svg # WeMeet logo
└── README.md           # This file
```

## Brand Colors Used

- Primary Blue: `#009FE3`
- Text Color: `#3D3D3D`
- Background: `#FAFAFA`
- Light Gray: `#F6F6F6`

## Contact

For questions until August 31, 2025: [help@wemeet.nl](mailto:help@wemeet.nl)

---

© 2025 We Meet BV
