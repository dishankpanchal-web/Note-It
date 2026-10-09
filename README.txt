MEETING NOTES - installable app (PWA)

Install needs the files served over HTTPS (browsers only allow install/offline from a real web address).
Easiest free options:
 1. Netlify Drop (app.netlify.com/drop): unzip, drag the folder in -> you get an https link.
 2. GitHub Pages or Cloudflare Pages: upload these files, enable Pages.
Then on the phone:
 - Android: open the link in Chrome -> tap Install (or menu -> Install app).
 - iPhone/iPad: open the link in Safari -> Share -> Add to Home Screen.
After the first load the app opens offline (notes, edit, export, on-device summary).
Live speech recognition itself still needs internet (phone browsers send audio to the speech service).
AI summary / "Fix languages with AI" only exist inside the Claude-hosted version; here the on-device summary is used.
