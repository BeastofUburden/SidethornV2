
Sidethorn — WhimsyGoth (Private PWA)
====================================

This is an invite-only Progressive Web App intended for two users: Brian and Darlene.
Passphrase: Myrotic

How it works:
- Open index.html in a browser (or host on GitHub Pages / Netlify).
- On first use, enter the passphrase "Myrotic".
- Choose a profile (Brian or Darlene). That profile becomes locked to that browser/device.
- Add tasks for your profile. Mark complete by tapping the checkbox.
- When both profiles have zero incomplete tasks, the shared streak increases.
- Data stored in localStorage; this is intentionally lightweight and offline-first.

To host:
- Upload the folder contents to GitHub Pages or Netlify. Keep the repo private if you wish.

Notes:
- This is a privacy-light implementation (simple passphrase gate). For stronger privacy or server-backed sync, we can add Firebase/Supabase with authentication.
