MASTER PLANNER — iPhone-native (PWA)

WHAT THIS IS
- A phone-optimized web app version of your planner with larger tap targets.
- Checkmarks + any prices you enter persist on your iPhone (saved locally).
- Works offline after first load (service worker cache).

HOW TO USE ON IPHONE (NO APP STORE)
1) Put this folder somewhere you can host it (required):
   - Easiest: upload the folder contents to any simple web host, e.g.:
     * GitHub Pages
     * Netlify
     * Vercel
     * Any website hosting you already have
2) Open the hosted URL in Safari on iPhone.
3) Tap Share -> Add to Home Screen.
4) Launch from the new icon. It will run in standalone app mode.

LOCAL TEST (COMPUTER)
- If you want to preview on desktop:
  1) Install Python
  2) In this folder, run: python -m http.server 8080
  3) Open http://localhost:8080

NOTES
- Safari requires HTTPS for full PWA features (offline + Add to Home Screen works best on HTTPS).
- If you change files, bump CACHE_NAME in sw.js or clear website data in iOS Settings.

SOURCE
Content imported from your PDF binder.