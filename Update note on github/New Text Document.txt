@echo off
cd /d D:\YourObsidianVault
git add -A
git commit -m "Auto backup on %DATE%"
git push
