# 1. README file create karo
touch README.md

# 2. README stage karo
git add README.md

# 3. README commit karo
git commit -m "Add project README"

# 4. Main branch set karo
git branch -M main

# 5. GitHub repository connect karo
git remote add origin https://github.com/USERNAME/my-portfolio.git

# 6. GitHub par push karo
git push -u origin main

# 7. Version tag create karo
git tag -a v1.0.0 -m "First portfolio release"

# 8. GitHub par tag push karo
git push origin v1.0.0

# 9. Tags check karo
git tag

# 10. Remote repository check karo
git remote -v