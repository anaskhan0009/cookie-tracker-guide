# Cookie & Tracker Guide — How Web Tracking Works & How to Stop It

An interactive explainer of the invisible economy running inside your browser: **first-party vs third-party cookies**, session vs persistent cookies, fingerprinting, and exactly **what profile an ad network builds about you** — demonstrated live, with your own toggles. Then it walks you, step by step, through blocking third-party cookies in Chrome, Firefox, Safari, Edge and Brave, with a personal cleanup task list to track the job.

**Live Demo:** https://anaskhan0009.github.io/cookie-tracker-guide/

## Features

- **Local account system** — sign up / log in on this device (passwords stored only as salted SHA-256 hashes, never plain text), continue as guest, per-account data separation, account deletion, and Export / Import of your records as JSON
- **Full record manager (CRUD)** — create, view, edit and delete your own saved records; the core tool works fully without an account, signing in unlocks saving for tracker-cleanup tasks, with a live progress bar (done / total)
- **'Build a tracker profile' demo** — toggle the signals trackers collect and read the profile they assemble, no name required
- **Per-browser walkthroughs** — exact menu paths to block third-party cookies and clear stored data
- **Honest limits** — why blocking cookies helps but fingerprinting means it does not make you invisible

## How to Use

1. Toggle the tracker signals and read the profile an ad network builds about you.
2. Pick your browser and follow the blocking walkthrough step by step.
3. Sign up (or continue as guest) and add one cleanup task per browser you use.
4. Mark tasks Done and watch your cleanup progress reach 100%.

## Why Cookies Deserve Ten Minutes of Your Attention

Third-party cookies let a single ad network follow you across thousands of unrelated sites, quietly assembling interests, habits, location and buying intent into a profile that is bid on in real time. You cannot opt out of being interesting to advertisers — but in ten minutes per browser you can cut off their main supply line. This guide shows you how, and keeps score while you do it.

## Ethical Use

This is a **defensive, educational tool** — it only ever helps you understand and improve your own security. Nothing here can be used to attack, track or deceive anyone else.

## Tech

Single self-contained `index.html` — HTML, CSS, vanilla JavaScript, WebCrypto (salted SHA-256 password hashing), localStorage persistence. No servers, no tracking, no external requests.

---

Built by **Dinal Studios** — free cyber security tools and web apps.
GitHub: https://github.com/anaskhan0009
