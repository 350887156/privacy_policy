# 隐私政策托管方案

## 📄 已生成的文件

| 文件 | 路径 | 用途 |
|------|------|------|
| **中文版** | `LEGAL/Privacy_Policy_CN.md` | 中国大陆用户 |
| **英文版** | `LEGAL/Privacy_Policy_EN.md` | 国际用户 |

---

## 🌐 托管方案选择

### 方案 A: GitHub Pages (推荐 ⭐⭐⭐⭐⭐)

**优点**:
- ✅ 免费
- ✅ 自定义域名
- ✅ HTTPS 自动启用
- ✅ 版本控制
- ✅ 易于更新

**步骤**:

1. **创建 GitHub 仓库**
   ```bash
   cd /Users/sclea/.openclaw/workspace/AuraTime
   git init
   git add LEGAL/
   git commit -m "Add privacy policy"
   git remote add origin https://github.com/yourusername/auratime.git
   git push -u origin main
   ```

2. **启用 GitHub Pages**
   ```
   GitHub 仓库 → Settings → Pages
   → Source: Deploy from branch
   → Branch: main
   → Folder: / (root)
   → Save
   ```

3. **访问 URL**
   ```
   https://yourusername.github.io/auratime/privacy-cn.html
   https://yourusername.github.io/auratime/privacy-en.html
   ```

4. **转换为 HTML** (可选，让页面更美观)
   ```bash
   # 使用 pandoc 转换 Markdown 为 HTML
   pandoc LEGAL/Privacy_Policy_CN.md -o privacy-cn.html
   pandoc LEGAL/Privacy_Policy_EN.md -o privacy-en.html
   ```

**推荐 URL**:
```
https://auratime.app/privacy
https://auratime.app/privacy-cn
```

---

### 方案 B: 自有网站 (如果你有域名) ⭐⭐⭐⭐

**优点**:
- ✅ 专业域名 (auratime.app)
- ✅ 完全控制
- ✅ 品牌一致

**步骤**:

1. **创建网页**
   ```html
   <!-- 在网站上创建 /privacy 页面 -->
   <!-- 复制 Privacy_Policy_CN.md 内容 -->
   ```

2. **上传到网站**
   ```bash
   # 根据你使用的网站平台
   - WordPress: 创建新页面
   - Vercel/Netlify: 添加 HTML 文件后部署
   - 传统 hosting: FTP 上传
   ```

3. **URL 示例**
   ```
   https://www.auratime.app/privacy
   https://www.auratime.app/privacy-cn
   https://www.auratime.app/privacy-en
   ```

---

### 方案 C: Notion (快速方案 ⭐⭐⭐)

**优点**:
- ✅ 5 分钟搞定
- ✅ 无需技术
- ✅ 自动托管

**步骤**:

1. **创建 Notion 页面**
   ```
   打开 Notion → 新建 Page
   → 粘贴 Privacy_Policy_CN.md 内容
   → 点击 Share → Publish to web
   ```

2. **获取 URL**
   ```
   https://notion.site/your-page-id
   ```

3. **自定义域名** (可选，需付费)
   ```
   https://auratime.notion.site/privacy
   ```

**缺点**:
- ❌ Notion 域名不够专业
- ❌ 可能在国内访问慢

---

### 方案 D: Google Docs (不推荐 ⭐⭐)

**优点**:
- ✅ 简单

**缺点**:
- ❌ 域名不专业
- ❌ 国内可能无法访问
- ❌ Apple 审核可能不认可

**不推荐使用**

---

### 方案 E: 第三方隐私政策生成器 ⭐⭐⭐

**服务**:
- [TermsFeed](https://termsfeed.com)
- [PrivacyPolicies.com](https://privacypolicies.com)
- [iubenda](https://iubenda.com)

**优点**:
- ✅ 专业模板
- ✅ 自动更新
- ✅ 合规保证

**缺点**:
- ❌ 付费 ($10-30/月)
- ❌ 依赖第三方

---

## 🎯 推荐方案

### 最佳实践 (推荐)

```
1. 使用 GitHub Pages 托管
2. 绑定自有域名 (auratime.app)
3. 创建两个页面：
   - https://www.auratime.app/privacy (英文)
   - https://www.auratime.app/privacy-cn (中文)
```

### 快速上线 (如果没域名)

```
1. 使用 GitHub Pages
2. URL: https://yourusername.github.io/auratime/privacy
3. 后续再绑定自定义域名
```

---

## 📝 App Store Connect 配置

### 填写隐私政策 URL

1. **登录 App Store Connect**
   ```
   https://appstoreconnect.apple.com
   ```

2. **选择你的 App**
   ```
   My Apps → AuraTime
   ```

3. **填写信息**
   ```
   App Information → Privacy Policy URL
   → 粘贴：https://www.auratime.app/privacy-cn
   ```

4. **保存**

---

## 🔧 快速部署脚本

### 使用 GitHub Pages

```bash
#!/bin/bash
# deploy-privacy.sh

# 1. 转换为 HTML
pandoc LEGAL/Privacy_Policy_CN.md -o docs/privacy-cn.html
pandoc LEGAL/Privacy_Policy_EN.md -o docs/privacy-en.html

# 2. 创建 index.html (自动跳转)
cat > docs/index.html << EOF
<!DOCTYPE html>
<html>
<head>
  <meta http-equiv="refresh" content="0; url=privacy-cn.html">
  <title>AuraTime Privacy Policy</title>
</head>
<body>
  <p>Redirecting to <a href="privacy-cn.html">Privacy Policy (中文)</a>...</p>
  <p>Or go to <a href="privacy-en.html">Privacy Policy (English)</a></p>
</body>
</html>
EOF

# 3. 提交到 gh-pages 分支
git add docs/
git commit -m "Deploy privacy policy to GitHub Pages"
git subtree push --prefix docs origin gh-pages

echo "✅ Privacy policy deployed!"
echo "URL: https://yourusername.github.io/auratime/"
```

---

## ✅ 检查清单

提交 App Store 前确认：

- [ ] 隐私政策已托管到可公开访问的 URL
- [ ] URL 使用 HTTPS
- [ ] 页面在大陆可访问 (如果面向中国用户)
- [ ] 内容包含中英文版本
- [ ] 包含联系方式 (email)
- [ ] 包含 Last Updated 日期
- [ ] 在 App Store Connect 填写了正确的 URL

---

## 📧 联系方式配置

在隐私政策中，我们使用了：

```
Email: support@auratime.app
Website: www.auratime.app
```

**确保**：
- ✅ 这个 email 有人定期查看
- ✅ 网站可以访问 (或暂时用 GitHub URL)

---

## 🚀 立即行动

### 最快方案 (5 分钟)

```bash
# 1. 创建 GitHub 仓库
cd /Users/sclea/.openclaw/workspace/AuraTime
git init
git add LEGAL/
git commit -m "Add privacy policy"

# 2. 推送到 GitHub
# (先创建仓库，然后)
git remote add origin https://github.com/yourusername/auratime.git
git push -u origin main

# 3. 启用 GitHub Pages
# GitHub 仓库 → Settings → Pages → 启用

# 4. 获取 URL
# https://yourusername.github.io/auratime/LEGAL/Privacy_Policy_CN.md
```

### 专业方案 (需要域名)

```
1. 购买域名 (如 auratime.app)
2. 使用 Vercel/Netlify 托管
3. 绑定域名
4. 获得专业 URL: https://auratime.app/privacy
```

---

**选择适合你的方案，然后告诉我，我帮你部署！** 🚀
