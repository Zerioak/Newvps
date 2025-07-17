# VPS 24/7 GitHub Setup 🚀

✅ **How it works:**
- Run workflow → VPS starts, restores backup, installs pm2 + playit.
- New SSH link generated → pushed to repo & sent to Discord.
- Backup saved (`.backup/manual-vps.zip` + `.backup/manual-vps-latest.zip`).

## ⚙️ Setup Steps:
1. Create Discord webhook → copy URL.
2. In GitHub → Settings → Secrets → New secret:
   - Name: `DISCORD_WEBHOOK_URL`
   - Value: your webhook URL
3. Manual run: Go to Actions → 'Create VPS' → Run workflow.

## 🔁 Backup:
- Each run saves current data to `.backup/` folder.
- Restore automatically on next run.

## 📌 SSH:
- Find SSH link inside `links/manual-vps.txt`.
- Also sent to your Discord.

## ❤️ By ChatGPT custom script.
