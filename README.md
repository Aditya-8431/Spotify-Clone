Spotify Web Player (clone)

An educational, static HTML/CSS clone of Spotify’s web player showcasing a left navigation/library sidebar, scrollable main content with horizontal card galleries (Trending, Featured), and a fixed bottom music player. Built for learning responsive layout, flexbox, and custom scroll behavior — a UI demo, not affiliated with Spotify.

How to run

1. Open `index.html` in a modern browser, or run a local server:

```powershell
python -m http.server 8000
# then open http://localhost:8000
```

Notes

- This is a frontend UI exercise. No backend or audio streaming is included.
- If you preview and content is hidden behind the fixed player, edit `style.css` and set `.main-content { height: calc(100vh - 70px); }`.
