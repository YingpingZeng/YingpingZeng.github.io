# zengyingping.github.io

个人简历页面 / Personal Homepage — 部署于 GitHub Pages

🔗 **访问地址**: https://zengyingping.github.io

---

## 部署步骤（首次设置）

### 1. 创建 GitHub 仓库

1. 登录 GitHub，点击右上角 **+** → **New repository**
2. Repository name 填写：`zengyingping.github.io`（必须完全一致）
3. 选择 **Public**
4. 点击 **Create repository**

### 2. 上传文件

将本仓库中所有文件（至少包含 `index.html`）上传到新建的仓库中：

```bash
cd /home/sl/workspace/zengyingping.github.io
git init
git remote add origin https://github.com/YingpingZeng/zengyingping.github.io.git
git add .
git commit -m "Initial commit"
git branch -M main
git push -u origin main
```

或者直接在 GitHub 网页上点击 **Add file → Upload files** 拖入文件。

### 3. 启用 GitHub Pages

1. 进入仓库 → **Settings** → 左侧 **Pages**
2. **Source** 选择：`Deploy from a branch` → `main` → `/ (root)`
3. 点击 **Save**
4. 等待 1-2 分钟，页面会自动发布

---

## 本地预览

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# 或用 Python 简单服务器
python3 -m http.server 8080
# 然后访问 http://localhost:8080
```

---

## 自定义内容

直接编辑 `index.html` 即可修改页面内容。以下几个地方需要你填写真实信息：

| 位置 | 说明 |
|------|------|
| `<title>` | 页面标题 |
| `meta description` | SEO 描述 |
| `tagline` | 个人简介 |
| `about` 段落 | 关于我正文 |
| `timeline` 区块 | 工作/研究经历 |
| `edu-card` 区块 | 学校名称和时间 |
| `contact-item` | 真实邮箱地址 |

---

## 技术栈

- 纯 HTML + CSS，无框架依赖
- Google Fonts: **Inter** + **JetBrains Mono**
- 深色主题，适配移动端
- 全部静态文件，可直接托管

---

> 如果遇到问题，欢迎提 Issue 或直接联系 [@YingpingZeng](https://github.com/YingpingZeng)。
