# CareerTracker Pro
A standalone web app for tracking job applications. Paste job descriptions and automatically extract company info, roles, deadlines, and more.

## Features
- **Smart Extraction** - Paste job descriptions to auto-extract company, role, dates, location, compensation, and work authorization
- **Inline Editing** - Update status and term fields directly in the table
- **Export to CSV** - Download all applications as Excel-compatible CSV
- **Statistics Dashboard** - View application counts by status
- **Auto-Save** - All data persists in browser localStorage

## Tech Stack
```
Frontend:
- React 18 (via CDN)
- Tailwind CSS (via CDN)
- Babel Standalone (JSX transformation)
- JavaScript (no build process)

Backend:
- None (fully client-side)
- localStorage for data persistence
```

## Quick Start
1. Download `Job-Tracker.html`
2. Double-click to open in any browser
3. Start tracking immediately

## Usage

**Add Application:**
1. Enter platform name (LinkedIn, Handshake, etc.)
2. Paste full job description
3. Click "Add Application"

**Tracked Fields (12 total):**
Company • Platform • Role • Term • Date Applied • Status • Location • Compensation • Job Type • Work Auth • Opens Date • Closes Date

**Managing:**
- Update status via dropdown
- Edit term field inline
- Delete with trash icon
- Export via "Download as Excel" button

## Output
- **File:** `Job_Applications_[Date].csv`
- **Format:** CSV (Excel-compatible)
- **Contains:** All applications with 12 fields each

## Notes
- Single HTML file - works offline
- No installation or npm required
- Data stored in browser localStorage
- Export regularly for backup
- Compatible with Chrome, Firefox, Safari, Edge
