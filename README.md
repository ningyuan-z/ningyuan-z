# 宁天歌的个人主页

推送到 `main` 分支后,GitHub Actions 会自动把网站部署到 GitHub Pages。

## 第一次使用

1. 把照片复制到 `images/Sky_And_Ning_Tage.jpg`(文件名大小写要完全一致)。
2. 在 GitHub 新建一个仓库,然后在本文件夹执行:

   ```bash
   git init
   git add .
   git commit -m "first commit"
   git branch -M main
   git remote add origin https://github.com/你的用户名/仓库名.git
   git push -u origin main
   ```

3. 打开仓库的 Settings → Pages,把 Source 选为 **GitHub Actions**。
4. 在 Actions 标签页等部署完成,网址是 `https://你的用户名.github.io/仓库名/`。

之后每次修改并 `git push`,网站都会自动更新。
