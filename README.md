# Myths and Pieces pipeline

Settings for Claude threads in the "Social Media Channel" project.

- `.claude/settings.json` lets threads run the approved YouTube upload without a permission prompt:
  `python3 /mnt/project-files/pipeline/yt_upload.py upload <episode_dir>`
  The script reads the refresh token from `pipeline/secrets/yt_refresh_token`, so no secret is in this repo.

Only upload a reel after Stephen has approved it.
