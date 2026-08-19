# Habib Shahriar Ridoy — GHL & Automation Portfolio

Modern static portfolio for GitHub Pages + a custom domain. No framework or paid hosting required.

## Files
- `index.html` — all sections and structure
- `styles.css` — responsive modern design
- `script.js` — navigation, animations, project modal/filter
- `projects.js` — **daily project database**; edit this file to add projects
- `assets/profile.jpg` — your uploaded profile photo
- `videos/` — optional folder for local OBS MP4 files

## Add a project
Open `projects.js` and copy this pattern:

```js
{
  title: "Real Estate Lead Automation",
  category: ["ghl", "funnels"],
  label: "GHL / FUNNEL",
  description: "Built a complete lead capture and nurture system.",
  tags: ["GHL", "Funnel", "Email", "SMS"],
  videoType: "youtube",
  video: "https://www.youtube.com/embed/YOUR_VIDEO_ID",
  thumbnail: "",
  date: "August 2026"
}
```

OBS Studio options: upload the recording to YouTube as **Unlisted**, Vimeo, or Cloudinary and paste the embed URL. Local MP4 also works with `videoType: "local"` and `video: "videos/file.mp4"`, but avoid huge GitHub files.

## GitHub Pages
1. Create a GitHub repository, e.g. `habib-portfolio`.
2. Upload the entire folder contents.
3. Commit to `main`.
4. GitHub → **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` → Folder: `/ (root)` → Save.
5. Your site will receive a `github.io` URL.

## Custom domain
The user domain was not provided, so no `CNAME` file is included yet. After you know the domain, create a root file named `CNAME` containing only the domain, for example:

```text
www.yourdomain.com
```

Then set the same custom domain under GitHub → Settings → Pages. For DNS, a `www` record normally points to `YOUR-USERNAME.github.io`; for apex/root domains use the current GitHub Pages DNS values shown by GitHub.

## Contact
Email: habibridoy622@gmail.com
Phone: +880 1770721129
WhatsApp: +880 177071129
