# 磊哥电视 APK 构建脚本
# 请先在 GitHub 上创建仓库，然后运行以下命令

# 1. 初始化 Git（如果还没有）
git init
git add .
git commit -m "磊哥视频 v1.0 - 初始配置"

# 2. 推送到 GitHub（替换为你自己的仓库地址）
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin release

# 3. 在 GitHub 上触发构建
# 访问: https://github.com/YOUR_USERNAME/YOUR_REPO/actions
# 点击 "Build APK" -> "Run workflow"

# 4. 下载 APK
# 构建完成后，在 Actions 页面下载 leanback-arm64_v8a.apk