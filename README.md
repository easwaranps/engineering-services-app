# IMSE EMS — Employee Management System

Web applications for IMSE Tech Services Pvt Ltd.

## Live URLs
- **Main App** (office, accounts, directors): https://easwaranps.github.io/imse-ems/
- **Field App** (technicians on-site):       https://easwaranps.github.io/imse-ems/field_app.html

## Features
- Staff management with multi-document attachments
- Director expense tracking with FIFO reimbursement ledger
- Multi-user concurrent editing with conflict resolution
- Google Drive sync (no separate database)
- GST-aware expense tracking with ITC integration
- Field technician work-log capture (mobile-friendly)

## Hosting
GitHub Pages serves the HTML files directly. No build step.
All data is stored in the user's Google Drive.

## Updating
1. Replace `index.html` or `field_app.html` with the new version
2. Commit
3. GitHub Pages redeploys automatically in ~60 seconds
