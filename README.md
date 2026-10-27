# Announce IQ

**Your campus, your community**

Announce IQ is a browser-based prototype for a centralized, interest-based university announcement platform. It is intended to help students discover campus announcements relevant to their interests, department, year, and eligibility.

> **Prototype status:** This is a demonstration project using sample content. It is not a production service and should not be used for real student records, credentials, or official announcements.

## Problem

Campus notices may be distributed across different departments and channels. Students can miss opportunities that are relevant to them, especially when notices are difficult to discover outside their own department.

## Current prototype features

- Demo access for Student, Dean, Faculty, and Admin roles
- Interest setup and sample announcement feed
- Search, category/department filters, and sorting
- Announcement details and optional registration links
- Save/revisit announcements during the active page session
- Publisher form with audience and interest tags
- Demo questions/replies, notifications, and account-request/approval interactions

## Technology

- HTML
- CSS
- Client-side JavaScript
- Browser `localStorage` for selected demo interactions

No framework or package installation is required to run the current prototype.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Use one of the demo accounts below to explore the prototype.

### Demo accounts

| Role | Username | Password |
|---|---|---|
| Student | `student` | `student123` |
| Dean | `dean` | `dean123` |
| Faculty | `faculty` | `faculty123` |
| Admin | `admin` | `admin123` |

These are **public demo credentials embedded in the client-side prototype**, not secure accounts. Never use real passwords or personal information.

## Known limitations

- Authentication is hard-coded in client-side JavaScript and is not secure.
- The app has no shared backend or database.
- Sample announcements are demonstration data.
- Newly published announcements are only added to the current browser session and are not broadcast to other users.
- Saved announcements are held in memory and may not persist after a reload.
- Some other demo interactions use browser `localStorage`, which is local to the browser profile and is not shared across devices.
- Notifications are in-app demo interactions, not real email or push notifications.
- No production deployment, institutional authentication, security review, or accessibility audit is claimed by this repository.

## Suggested next steps

1. Add a backend API and database for shared announcement storage.
2. Replace demo login with approved institutional authentication and server-side role permissions.
3. Persist saved announcements and implement tested data retention.
4. Add consent-based email/push notifications if required.
5. Add automated tests, responsive/accessibility checks, and deployment documentation.
6. Collect authentic user/peer feedback and record test outcomes.

## Team

- Payal Priya
- Priyanka Jadhav
- Gouri Jaiswal

Project Design, BCS3711 / BAI3711, Academic Year 2026–27.

## Links

- Live demo:https://announce-iq-college-announcements.vercel.app/
- Demo video: https://youtu.be/ghWKp0ZRcDw
