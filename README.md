# Rangotsav — Campus Event Registration

A colorful, responsive event registration app built with HTML, CSS, Bootstrap 5, and vanilla JavaScript.

## Run
Open `index.html` in a modern browser. The layout and registration flow work without a build step. Bootstrap and Google Fonts load from their CDNs; event photography uses Unsplash image URLs, so those assets need internet access.

## Roles
- Participant: create an account, sign in, and register for multiple events. Each email can create one account, and each participant can register once per event.
- Admin: sign in with `admin@rangotsav.in` / `admin123` to see the full registration list.

## Session storage
Accounts, the active sign-in, and registrations are stored in `sessionStorage`, scoped to the current browser tab session. They clear when that session ends. This is a front-end demonstration, not a secure production authentication system; do not use real passwords or sensitive data.

## Event details
The six event names, dates, and time slots are sample demo content and can be edited in `app.js`. Venue: SIC C.R. Reddy College of Engineering, Eluru.
