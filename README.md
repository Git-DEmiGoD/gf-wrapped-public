# 💌 Girlfriend Wrapped

A personalised anniversary "Spotify Wrapped" style gift.

## Hosting on GitHub Pages

1. Create a new **private** repo on GitHub (keep it private — it's personal!)
2. Run these commands:
```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git branch -M main
git push -u origin main
```
3. Go to repo **Settings → Pages → Source: main branch / root**
4. Your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`

## File structure
```
index.html        ← the whole experience
assets/
  *.mp3           ← audio tracks
  *.mp4           ← compressed videos
  *.jpg / *.heic  ← photos
```

## Notes
- Music auto-starts on first tap (browser requirement)
- Swipe left/right or tap left/right half of screen to navigate
- Arrow keys work on desktop
- 🎵 button top-right to toggle music
