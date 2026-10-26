POSTURE GUARDIAN — EMERGENCY MOBILE UPDATE

This version fixes the navigation/JavaScript errors and restores the live camera/AI monitor.

Publish update to existing GitHub Pages repository:
1. Open https://github.com/diyadthakur/posture-guardian-demo
2. Add file > Upload files.
3. Upload the updated index.html from this folder to repository root. If prompted to replace the existing file, confirm.
4. Commit changes. Wait for Pages to redeploy.
5. On iPhone, close the Home Screen web app completely, reopen it, and refresh if needed.

If the previous version remains cached, open the published URL in Safari and refresh. The iPhone Home Screen icon and existing repository URL do not need to change.

Features: consent onboarding, goal selection, working Home/Monitor/My goals/Privacy/About navigation, live Face Landmarker, optional Pose Landmarker shoulder estimates, calibration, in-app prompts, movement reminders, stop controls.

Limitations: this is a student proof of concept. Shoulder-level signal is an estimate of visible left/right shoulder height, not validated shoulder-rounding detection. Notifications outside the app and reliable background camera monitoring are not implemented. Internet is required to load MediaPipe libraries and models.
