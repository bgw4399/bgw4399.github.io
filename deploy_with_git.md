# Deploy With Git

Use this after creating the public repository `bgw4399.github.io`.

```powershell
cd "C:\Users\bgw4399\Desktop\배진우 취준 폴더\output\github-pages"
git init
git add .
git commit -m "Build portfolio homepage"
git branch -M main
git remote add origin https://github.com/bgw4399/bgw4399.github.io.git
git push -u origin main
```

Do not paste a token into the remote URL. Use GitHub Desktop, browser authentication, or `gh auth login`.
