[README_Mobile_Setup.txt](https://github.com/user-attachments/files/33978904/README_Mobile_Setup.txt)
POSTURE GUARDIAN — MOBILE WEB APP QUICK SETUP

WHAT THIS IS
A mobile-friendly web-app version of the existing live AI prototype. It includes a Home Screen web-app manifest and icons. It is not a native App Store app. The AI library and model load from the internet.

PART A — PUBLISH IT WITH GITHUB PAGES (FREE)
1. On your Windows laptop, open https://github.com and sign in/create an account.
2. Click the + menu (top right) > New repository.
3. Name it: posture-guardian-demo
4. Choose Public (GitHub Pages free hosting works with a public repository). Do not put personal/private files in it. This is a student demo, not a place to store health data.
5. Create repository.
6. Click Add file > Upload files.
7. Open the folder from this ZIP and upload ALL files inside it: index.html, manifest.json, icon-192.png, icon-512.png.
8. Click Commit changes.
9. Open repository Settings > Pages.
10. Under Build and deployment, choose Deploy from a branch. Branch: main; folder: /(root). Click Save.
11. Wait a minute or two and refresh the Pages screen. It should show a URL similar to https://YOUR-USERNAME.github.io/posture-guardian-demo/.
12. Open that URL on the laptop first. Confirm the page loads. Then open the same HTTPS URL in Safari on the iPhone.

PART B — ADD IT TO IPHONE HOME SCREEN
1. Open the published URL in Safari (not inside an in-app browser).
2. Tap Share.
3. Choose Add to Home Screen. If offered, turn on Open as Web App.
4. Tap Add. Find the Posture Guardian icon on your Home Screen and open it.
5. Tap Start camera & AI and approve camera access. Keep internet connected while the AI library/model loads.

PART C — DEMO CHECKLIST
- Open the Home Screen icon.
- Tap Start camera & AI; grant camera access.
- Wait for the face landmarks/readings to appear.
- Sit in a comfortable neutral position and tap Calibrate baseline.
- Gently change head position and observe the experimental proxy.
- If needed for a short demo, choose the 2-second duration and a threshold that makes a prompt easier to demonstrate. Explain that these are demonstration settings, not clinically validated thresholds.
- Tap Stop session at the end; this stops the camera stream.

TROUBLESHOOTING
- Camera does not start: use Safari, make sure the site is HTTPS, tap the page/site settings and allow Camera, then reload.
- AI does not load: check internet, reload, and try again. This page imports MediaPipe from a CDN and downloads its model from Google-hosted storage.
- Black camera preview: close other apps using the camera; check iOS Settings > Safari > Camera (menu wording can vary); reload and grant permission.
- GPU/model error: some devices/browsers may not support the current GPU delegate. This is a prototype limitation; report it honestly rather than claiming it works on every phone.
- Page not found: check that index.html, manifest.json and both icons were uploaded to the repository root and that Pages is deployed from main / (root).

HONESTY / PRIVACY NOTES FOR PRESENTATION
- This is a student proof-of-concept, not a validated medical device.
- The proxy is based on facial landmarks and is not a direct cervical-spine angle or shoulder measurement.
- The page does not intentionally record or upload video; camera access is requested only after the user presses Start. The third-party AI library/model are downloaded from external hosts.
- GitHub Pages makes the website publicly accessible. Do not include passwords, personal records, or private user data in the repository.
