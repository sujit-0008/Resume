# Ringbook — offline call sheet for cold calling

A phone app (installable web app) for calling through paper lists.

- **Photo → numbers**: snap a paper list or pick a screenshot; it reads names + numbers, you check them, then save.
- **Paste / type / CSV import** for lists from WhatsApp, Excel or another device.
- Numbers are saved **only inside the app** (phone storage) — never in your contacts, never in the cloud.
- **Call, Text or WhatsApp** in one tap. After each call it asks *how did it go?* and records the time.
- Statuses: New, No answer, Call later (with reminder time), Interested, Not interested, Wrong number.
- **"They called me back"** button logs inbound calls.
- **Start calling** mode: one person at a time, big Call button, auto-advances after you log the result.
- Lists (one per paper sheet), search, today's tally, full history per person.
- Export CSV, full backup / restore.

## Put it on your phone
1. Host the `dialer/` folder on any HTTPS host (e.g. GitHub Pages: Settings → Pages → this branch).
2. Open the URL on your phone → browser menu → **Add to Home screen**.
3. Open once with internet so the photo reader downloads; after that it works offline.
