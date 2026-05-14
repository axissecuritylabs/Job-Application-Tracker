# Axis Job Application Tracker

A browser-based job application tracker built and distributed by Axis Security Solutions as part of the Career Services resource suite. The tracker helps active job seekers log every application, score how thoroughly they tailored their resume for each one, monitor status across the full hiring lifecycle, and arrive at coaching sessions with data their consultant can act on.

The entire tracker runs from a single HTML file. No installs, no accounts, no backend. Data saves locally to the user's browser.

Link: https://axissecuritylabs.github.io/Job-Application-Tracker

---

## What this tracker does

- Logs every application with role, company, posting URL, location, source platform, submission platform, and resume version used.
- Scores each application against the Axis Tailoring Scorecard, a 100-point diagnostic across four categories (Keyword Alignment, Summary and Positioning, Bullets and Accomplishments, Submission Quality).
- Tracks status changes over time (Applied, Under Review, Phone Screen, Interview, Offer, Rejected, No Response) with timestamped notes for each update.
- Visualizes a 30-day application target progress bar, weekly cadence chart, and tailoring score distribution.
- Provides a Coaching View tab with a conversion funnel, source analysis, and behavioral insights designed to be reviewed during Axis coaching sessions.
- Exports a print-ready PDF report for client and consultant review.

---

## How to use it

1. Open the live tracker via the GitHub Pages link (see Hosted Version below) or download `index.html` and double-click to open it in any modern browser. Chrome, Edge, Firefox, and Safari are all supported.
2. The tracker opens with demo data pre-loaded for a fictional client named John Doe. Use this to explore the layout before logging your own applications.
3. Click **+ Log Application** on any tab to add a new entry. Fill in every field, work through the Tailoring Scorecard honestly, and save.
4. Update status as recruiters respond, screens are scheduled, or rejections come in. Add notes to every status change so the audit trail stays useful.
5. Before each coaching session, log all applications since the last session, review the Coaching View, and export a PDF report to bring to the call.

Full client documentation is included in `Axis Job Application Tracker Client User Guide.pdf`.

---

## The four tabs

| Tab | Purpose |
|---|---|
| Dashboard | Home view. Five performance stats, five most recent applications, weekly cadence chart, and 30-day target progress. |
| Application Log | Full searchable history of every application, filterable by status and tailoring score. |
| Timeline | Chronological card view with full detail per application including notes, keywords, resume version, and status history. |
| Coaching View | Session-ready analytics for use during Axis coaching sessions. Conversion funnel, score distribution, source breakdown, behavioral insights. |

---

## Why tailoring is scored

The Tailoring Scorecard is the most important feature in the tracker. Applications scoring below 40 percent rarely advance past ATS screening. Applications scoring 70 percent or above consistently outperform lower-scored submissions even when the candidate's background is comparable. The score gap explains most of the "I applied to 50 roles and heard nothing" situations Axis sees in client coaching.

Score bands:

- **Strong:** 70 to 100 percent
- **Moderate:** 40 to 69 percent
- **Weak:** below 40 percent

The scorecard is a diagnostic tool, not a test. Clients are expected to check only the items they actually completed. Honest low scores produce useful coaching conversations. Inflated scores hide the actual reason applications are not converting.

---

## The 30 to 45 day interview window

Axis benchmarks a 30 to 45 day timeline to first interview for clients who meet three conditions simultaneously:

1. Consistent weekly application volume of 8 to 12 targeted roles.
2. Deliberate tailoring scoring 70 percent or above on the scorecard.
3. Correct platform selection on every submission (Workday and Taleo require DOCX, most others accept text-based PDF, LinkedIn Easy Apply is avoided when possible).

Excelling at two of these while failing the third extends the timeline materially. The tracker is designed to make all three measurable.

---

## Privacy

All data entered into the tracker is saved to the user's browser local storage on their device. Nothing is transmitted to any server. Axis Security Solutions does not have access to client tracker data unless the client exports a PDF and shares it, or shows the tracker on screen during a session.

Data is browser-specific and device-specific. Opening the file in a different browser or on a different machine will not surface previous entries. Clients are advised to keep the file in a consistent cloud location and always open it in the same browser.

---

## Hosted version

The tracker is hosted via GitHub Pages at:(https://axissecuritylabs.github.io/Job-Application-Tracker/)

Hosting it here resolves rendering issues that occur when the HTML file is sent as an email attachment and the receiving client strips, sandboxes, or fails to parse the embedded styles and scripts. Opening the live link in any modern browser produces a clean, fully functional tracker.

---

## File contents

| File | Description |
|---|---|
| `index.html` | The tracker itself. Single self-contained HTML file with embedded CSS and JavaScript. |
| `Axis Job Application Tracker Client User Guide.pdf` | Full client documentation covering setup, logging, the scorecard, file format guidance per ATS platform, status workflow, and coaching session prep. |
| `README.md` | This file. |

---

## Support

Axis clients with questions about the tracker, the scorecard, or how to interpret their data should contact their Axis Security Solutions consultant directly.

