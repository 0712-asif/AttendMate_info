# Privacy Policy

**Last Updated & Effective:** October 31, 2026

**AttendMate** ("we," "our," or "the App") is committed to protecting your privacy. This Privacy Policy explains how we collect, process, and protect your information when you use our mobile application, including attendance tracking, location & geofencing services, Google Calendar synchronization, and Google Drive cloud backup features.

> **Important Notice:**
> AttendMate integrates with Google Calendar and Google Drive strictly for personal timetable synchronization and secure backups. We do not use your Google data for any other purpose.

---

## 1. Information We Process

AttendMate operates on a **local-first architecture**. All your personal data, schedule information, and app preferences remain stored strictly on your device in a secure private database. We process:

- **Timetable & Attendance Schedules:** Subject names, acronyms, slot times, instructor names, and attendance records created or imported by you.
- **Location & Geofencing Data:** Optional classroom/campus geographic coordinates (latitude, longitude, geofence radius, and location names) configured by you for automated attendance reminders and proximity verification.
- **Google Account & Cloud Storage Credentials:** Your Google profile email address and OAuth tokens, used strictly to authenticate and sync events directly with your Google Calendar, and to maintain an optional encrypted cloud backup in your personal Google Drive.

---

## 2. Location & Geofencing Privacy

If you enable location features and grant location permissions:
- **On-Device Processing:** Location coordinates and geofences are evaluated solely on your physical device to trigger localized attendance verification and reminders when entering or leaving designated classroom areas.
- **Zero Remote Storage or Tracking:** Your location data is **never** transmitted to remote servers, uploaded to cloud databases, shared with third parties, or used for location tracking or advertising.
- **Permission Control:** Location permissions (including precise location and optional background location for auto-detection) are completely optional. You can grant or revoke these permissions at any time via your device settings or disable geofencing inside the App.

---

## 3. Google Calendar & Google Drive Data Use

**AttendMate integrates with Google Calendar and Google Drive strictly for personal timetable synchronization and secure backups.**

To provide these features, the App requests permission for the following OAuth scopes:
- `https://www.googleapis.com/auth/calendar.events` (view and edit events on your calendars).
- `https://www.googleapis.com/auth/drive.file` (view and manage Google Drive files and folders opened or created with this app).

### Google Calendar Sync
We use calendar access exclusively for:
- Creating calendar events for your classes, timetables, and special lectures inside your selected Google Calendar.
- Automatically updating, rescheduling, or deleting events in your calendar to match changes you make inside the App.
- Excluding specific holiday dates and cancellations using iCalendar recurrence exclusion rules (`EXDATE`).
- **Scope Boundary:** AttendMate does **not** read, inspect, or modify any personal, business, or unrelated third-party events on your calendar.

### Google Drive Cloud Backup
We use Google Drive access exclusively for:
- Storing a single user-controlled backup file (`attendmate_cloud_backup.json`) directly in your personal Google Drive storage once daily at midnight (or upon manual user trigger).
- Restoring your attendance records and configurations when you sign in or request a cloud restore.
- **Scope Boundary:** AttendMate strictly utilizes the least-permissive `drive.file` scope. The App **only** accesses files created by AttendMate itself; it has **zero access** to your other files, photos, documents, or folders in Google Drive.
- **No Third-Party Intermediaries:** All communications occur directly between your device and official Google APIs. No intermediary servers are involved.

---

## 4. Data Sharing & Third-Party Access

**Your data is private.** We do not share, sell, rent, or monetize your personal information, location data, calendar events, or email address with any third parties or remote analytics services.
- **No Remote Servers:** The App does not operate proprietary backend servers that store your data.
- **Direct API Communication:** Google OAuth authentication tokens and API requests are transmitted directly between your device and Google's official API endpoints.

---

## 5. Compliance with Google API Services User Data Policy (Limited Use)

AttendMate's use and transfer of information received from Google APIs to any other app will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements:
- We **do not** transfer, disclose, or sell Google user data to third parties, data brokers, or advertising networks.
- We **do not** use Google user data for serving advertisements, retargeting, or promotional profiling.
- We **do not** use Google user data to develop, train, or improve generalized Artificial Intelligence (AI) or Machine Learning (ML) models.
- Human access to your Google user data is prohibited, except if required by applicable law or to resolve security incidents with your explicit consent.

---

## 6. Security & Data Protection Mechanisms

We implement industry-standard security measures to protect your data on-device and in transit:
- **Encryption in Transit:** All network communication with Google APIs occurs over secure HTTPS (SSL/TLS 1.2 or TLS 1.3).
- **On-Device Security:** Google OAuth credentials and sensitive preferences are stored securely using Android's hardware-backed Keystore and encrypted storage mechanisms.
- **Application Sandboxing:** Your local SQLite database containing timetables, attendance history, and geofence locations is protected by system-level Android application sandboxing and Linux user isolation.
- **No Remote Server Retention:** Because there are no backend servers, your data cannot be exposed in remote database breaches.

---

## 7. Access Revocation and Data Deletion

You retain complete control over your data:
- **Google Account Disconnect:** You can disconnect your Google Account at any time in the App settings under Google Integrations, which immediately purges all stored OAuth tokens from your device.
- **Revoking Google Permissions:** You can revoke the App's access anytime via [Google Account Security](https://myaccount.google.com/permissions).
- **Location Permission Revocation:** You can revoke location access at any time through Android system settings.
- **Local Data Erasure:** Uninstalling the App or selecting "Clear App Data" in app settings permanently deletes all local attendance, timetable, and location data from your device.
- **Cloud Backup Deletion:** You can delete your cloud backup file at any time directly through Google Drive or by turning off cloud backup in the App.

---

## Contact Developer

If you have any questions or feedback regarding this Privacy Policy, please contact:
- **Developer:** Chukkaluru Asif
- **Email:** [chukkaluruasif@gmail.com](mailto:chukkaluruasif@gmail.com)
- **Portal:** [https://attendmate.app](index.html)
