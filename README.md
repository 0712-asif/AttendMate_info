# AttendMate Web Portal & Legal Documentation

Official web portal, privacy policy, terms of service, and Google OAuth verification assets for [AttendMate](https://github.com/YTFL/AttendMate-Bunk-Calculator-Attendance-Tracker).

## Portal Structure

* **`docs/index.html`**: Main landing page with feature walkthroughs, responsive phone mockups, and Google integration disclosures.
* **`docs/privacy.html` / `docs/privacy.md`**: Complete Privacy Policy explicitly stating Google Calendar and Google Drive integration strictly for personal timetable synchronization and secure backups.
* **`docs/terms.html` / `docs/terms.md`**: Terms of Service governing local-first data usage and third-party integrations.
* **`docs/google77ba7ea073053d7e.html`**: Google Search Console / OAuth site verification file.
* **`docs/screenshots/`**: App walkthrough screenshots.

## GitHub Pages Deployment

This repository is structured for **GitHub Pages** deployment from the `/docs` folder:
1. Go to repository **Settings** &rarr; **Pages**.
2. Under **Build and deployment**, select:
   * **Source**: `Deploy from a branch`
   * **Branch**: `main`
   * **Folder**: `/docs`
3. Save to publish the site at `https://0712-asif.github.io/AttendMate_info/`.
