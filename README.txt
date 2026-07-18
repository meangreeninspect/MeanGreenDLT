MEAN GREEN DUCT LEAKAGE iPAD WEB APP

FILES
- index.html: Main editable web form
- manifest.webmanifest: Home Screen app settings
- service-worker.js: Caches the form after it is hosted and opened
- icons/: iPad Home Screen icons
- Mean_Green_Logo.png: Clean company logo

HOW TO USE ON AN iPAD
1. Upload this entire folder to a secure HTTPS web host.
2. Open the hosted index.html address in Safari.
3. Tap Safari's Share button.
4. Tap "Add to Home Screen."
5. Name it "Mean Green DLT" and tap Add.

IMPORTANT
- Opening index.html directly from the Files app may allow basic form use, but Home Screen installation,
  persistent storage, file uploads, and PDF generation work most reliably from a hosted HTTPS address.
- The PDF generator currently loads pdf-lib from an online CDN, so an internet connection is required
  when generating a report unless that library is later bundled locally.
- Draft text fields save on the device. For browser security, uploaded attachments must be selected again
  after closing or reloading the app.
