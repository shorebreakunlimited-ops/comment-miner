# YouTube Comment Miner (Web)

Browser-based niche research tool. Paste competitor YouTube video URLs, get ranked repeated phrases and unmet-need signals from public comments.

**Live site:** https://shorebreakunlimited-ops.github.io/comment-miner/

## How to use
1. Open the link above on your phone or computer.
2. Paste one YouTube video URL per line in the box.
3. Tap **Run miner**.
4. Read the High-signal section first — those are frustrated/wishful phrases like "wish they'd covered" or "does anyone know how to."
5. Paste that section into Claude Pro and ask it to cluster into episode topic ideas.

## Notes
- No install, no API key, no account needed.
- Works best with 5–10 competitor videos per niche.
- If a video has comments disabled, it's skipped automatically.
- The comment source is a public no-key endpoint; if it ever stops responding, the Streamlit or terminal versions (using youtube-comment-downloader) are the reliable fallback.

## Related files (local)
- `comment_miner_v2.py` — terminal version with CSV input and dated markdown reports
- `comment_miner_streamlit.py` — Streamlit web app for Community Cloud deploy
- `COMMENT_MINER_GUIDE.md` — full ELI5 setup guide
- `STREAMLIT_DEPLOY_GUIDE.md` — Streamlit deploy steps

RESEARCH / NOT PRODUCTION-READY