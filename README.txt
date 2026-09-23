NIGHTFLIX VIDEO WEBSITE

1. Put your video entries in:
   videos/videos.json

2. Example:
[
  {
    "title": "My Video",
    "url": "https://drive.google.com/file/d/FILE_ID/view?usp=sharing",
    "category": "Anime",
    "year": "2026",
    "description": "Optional description"
  }
]

3. Google Drive:
   - Upload the video to Drive.
   - Share it so the intended viewers can access it.
   - Copy the file's sharing URL.
   - Paste that URL into videos.json.

4. Deploy:
   Upload the whole folder to GitHub and import the repository into Vercel.

IMPORTANT:
Google Drive is not a guaranteed high-volume video CDN. Large files, traffic limits,
permissions, or Drive policies can cause playback problems. For a public site with
many viewers, use a video hosting/storage service intended for web streaming.
