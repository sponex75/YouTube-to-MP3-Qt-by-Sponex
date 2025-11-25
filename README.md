<p align="center">
  <img src="assets/cover.svg" alt="YouTube to MP3 (Qt) — by Sponex"/>
</p>

<h2 align="center">YouTube to MP3 (Qt) — by Sponex</h2>

<p align="center">
  A fast, modern YouTube-to-MP3 desktop app built with Python, yt-dlp, ffmpeg, and Qt (PySide6).
</p>

- Clean native UI with queue, progress, speed, ETA, size
- Supports multiple inputs (URLs or searches)
- Exact video download for YouTube URLs; top-result for plain searches
- Artist/channel filter
- Duplicate protection (session + persistent archive)
- Library tab lists downloaded tracks; double-click to open

## Setup (Windows)

1) Create venv and install deps:
```powershell
python -m venv .venv
.venv\Scripts\pip install -r requirements.txt
```

2) ffmpeg
- Already bundled under `tools/ffmpeg`. No extra setup needed.

3) Run the app:
```powershell
.venv\Scripts\python qt_app.py
```

## Usage

- Paste YouTube URLs to download that exact video to MP3.
- Paste plain text to search (e.g. "artist - song") — the top result is downloaded.
- Enter multiple lines or comma-separated values to queue many items at once.
- Use the artist/channel filter to restrict downloads to a specific uploader.
- See progress (percent, speed, ETA, size) in the queue.
- Library tab shows downloaded tracks; double-click to open.

## CLI (optional)

You can also use the CLI downloader:
```powershell
.venv\Scripts\python main.py "https://www.youtube.com/watch?v=VIDEO_ID" --bitrate 320
```

## Donate / Support

If this project helps you, consider supporting development:

- Donate link: https://www.paypal.com/donate?business=viorelstanculet1234%40outlook.com&no_recurring=0&currency_code=USD

Made by Sponex. © 2025


