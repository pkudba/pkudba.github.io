# pkudba.github.io 个人主页

这是一个可直接部署到 GitHub Pages 的静态主页模板。

## 1) 仓库命名（关键）

你当前 GitHub 用户名是 `pkudba`，所以个人主页仓库应命名为：

`pkudba.github.io`

对应主页地址是：

`https://pkudba.github.io`

如果你一定要使用 `https://dba.github.io`，必须拥有 GitHub 用户名 `dba`（或拥有名为 `dba` 的组织主页权限）。

## 2) 本地文件

- `index.html`：主页主文件（已做好移动端适配）。

## 3) 发布步骤

1. 在 GitHub 创建一个公开仓库：`pkudba.github.io`。
2. 把本地项目推送到这个仓库。
3. 进入仓库 `Settings -> Pages`。
4. 在 `Build and deployment` 中选择：
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`，目录选 `/ (root)`
5. 保存后等待 1-3 分钟，再访问 `https://pkudba.github.io`。

## 4) 快速推送命令

```bash
git init
git config user.email "scncdba@gmail.com"
git add .
git commit -m "feat: init personal homepage"
git branch -M main
git remote add origin https://github.com/pkudba/pkudba.github.io.git
git push -u origin main
```

## 5) 你可以先改这几处

- `index.html` 里的 `scncdba@gmail.com`
- `GitHub` 链接（目前是 `https://github.com/pkudba`）
- “项目 A/B/C”内容
- “关于我”介绍文案
