CUSTODY LEDGER - INSTALL GUIDE

This folder is the whole app. Put it on any web host (it must be https), open the
address, then install it. Nothing you log is ever sent to the host. The host only
serves the app file. Your records stay on your own device.

STEP 1. PUT IT ONLINE (pick one, about 3 minutes)

A) Netlify Drop (easiest)
   1. Go to app.netlify.com/drop
   2. Drag this whole folder onto the page.
   3. Create a free account when asked, so the site is not deleted after an hour.
   4. Copy the https address it gives you. You can rename it in Site settings.

B) GitHub Pages
   1. Create a new repository and upload the contents of this folder.
   2. Settings, then Pages, then deploy from the main branch.
   3. Your address is https://YOURNAME.github.io/REPONAME/

C) Cloudflare Pages: create a project and upload this folder.

Tip: the address is not secret, so use a name that does not mention custody.

STEP 2. INSTALL ON IPHONE
   1. Open the address in Safari (not Chrome).
   2. Tap Share, then Add to Home Screen, then Add.
   3. Open it from the new icon. Do this BEFORE you log anything. The installed app
      has its own storage, separate from Safari.

STEP 3. INSTALL ON MAC
   Safari (macOS Sonoma or later): File, then Add to Dock.
   Chrome or Edge: click the install icon in the address bar.

STEP 4. KEEP BACKUPS (important)
   The Mac and the iPhone do not sync. Each keeps its own record.
   - Settings, then Export backup, every couple of weeks.
   - To move a record between devices: Export backup on one, Import backup on the other, choose Merge.
   - Use a passphrase when asked if the file will be emailed or stored in the cloud.

UPDATING
   Replace index.html with the new version, change VERSION in sw.js (for example
   cl-v2), and upload again. Devices pick up the new copy the next time they open it
   with a connection. Your data is not affected by updates.

NOT LEGAL ADVICE
   Ask your attorney what your court accepts.
