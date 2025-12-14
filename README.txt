Seashell Residence WebApp (Free Hosting)

Free hosting options:
1) GitHub Pages (completely free, no credit card)
   - Rename this folder/repo as you like and push to GitHub.
   - In the repo: Settings → Pages → Source: Deploy from a branch (main / root).
   - Your site will be served at: https://<user>.github.io/<repo>.

2) Netlify (free tier)
   - https://app.netlify.com → Add new site → Deploy manually.
   - Drag-and-drop the folder contents. You will get a free *.netlify.app URL.

3) Cloudflare Pages (free tier)
   - https://dash.cloudflare.com → Pages → Create a project.
   - Connect Git or upload the folder. Get a free *.pages.dev URL.

PWA install:
- The app is PWA-ready (manifest + service worker). Host it over HTTPS (all above do).
- Open it on Chrome/Edge/Android/iOS; you'll see "Install app" option (or use browser menu).

Security note:
- Current login is client-side only (sessionStorage). For real security, add a backend auth later.
