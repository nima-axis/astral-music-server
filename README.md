# 🎵 ASTRAL MUSIC SERVER

YouTube Audio Backend for ASTRAL MUSIC App.

## Endpoints

| Method | Path | Description |
|--------|------|-------------|
| GET | `/` | Health check |
| GET | `/search?q=song+name` | Search songs |
| GET | `/stream?url=YT_URL` | Get audio stream URL |
| GET | `/info?url=YT_URL` | Get song info |
| GET | `/download?url=YT_URL` | Get MP3 download URL |

## Deploy on Railway

1. Fork this repo
2. Connect to Railway
3. Deploy ✅
