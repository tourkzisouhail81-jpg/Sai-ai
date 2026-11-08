# SAI 1.0

A mobile-friendly multilingual AI chat frontend.

## Included
- Responsive chat UI for phones and desktop
- Arabic, Darija, English, French and Spanish labels
- Chat history stored locally in the browser
- Light/dark theme, copy replies, new chats
- Optional secure backend URL setting

## Important
This GitHub Pages project is a static frontend. Without a secure backend URL it runs in DEMO mode.
Do not put AI provider API keys in `index.html`, browser JavaScript, public GitHub files, or chat messages.
A backend must accept POST JSON `{ "message": "...", "language": "en" }` and return JSON `{ "reply": "..." }`.
The backend should keep provider credentials in server-side encrypted secrets and enforce rate limits and suitable safety controls.
A parent/guardian or project administrator should configure and review any third-party AI service and hosting account.
