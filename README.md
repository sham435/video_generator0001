# Video Generator Website

Static website for the TikTok app review. Hosted on GitHub Pages.

## Deploy to GitHub Pages

```bash
# 1. Create a new repo on GitHub: video_generator0001
# 2. Push the website files:
cd /Users/sham4/linkedin_post/website
git init
git add .
git commit -m "Website for TikTok app review"
git remote add origin https://github.com/sham435/video_generator0001.git
git push -u origin main

# 3. Enable GitHub Pages:
#    - Go to repo Settings → Pages
#    - Source: Deploy from a branch
#    - Branch: main, folder: / (root)
#    - Save

# 4. Site will be live at:
#    https://sham435.github.io/video_generator0001/
```

## Files

| File | Purpose |
|------|---------|
| `index.html` | Homepage with app description, features, TikTok scope explanations |
| `privacy.html` | Privacy Policy (linked from homepage) |
| `terms.html` | Terms of Service (linked from homepage) |
| `favicon.png` | App icon (must match TikTok developer portal icon) |
| `style.css` | Shared stylesheet |

## TikTok Review Checklist

- [x] App icon on website matches TikTok developer portal
- [x] Privacy Policy accessible from homepage (header + footer)
- [x] Terms of Service accessible from homepage (header + footer)
- [x] Website is a fully developed site (not a landing/login page)
- [x] Each TikTok scope explained (Login Kit, Share Kit, User Info)
- [x] Scopes match what the app actually requests
- [ ] Demo video showing end-to-end TikTok flow (see DEMO_GUIDE.md)
