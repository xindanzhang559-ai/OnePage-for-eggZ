# 张馨丹个人网站

静态单页作品集，无构建依赖，可直接部署到 GitHub Pages。

## 本地预览

```bash
python3 -m http.server 8000
```

浏览器访问 `http://localhost:8000`。

## 部署到 GitHub 个人主页

1. 在 GitHub 新建仓库，名称必须为：`<你的GitHub用户名>.github.io`。
2. 将本目录内的 `index.html`、`assets/` 等网站文件放到仓库根目录。
3. 提交并推送到 `main` 分支。
4. 在仓库 `Settings → Pages` 中选择 `Deploy from a branch`，分支选择 `main / (root)`。
5. 部署完成后访问：`https://<你的GitHub用户名>.github.io/`。

如果你已有同名主页仓库，请先备份原内容，再覆盖或合并。

## 更新内容

- 页面文案与样式都在 `index.html`。
- 公开仓库不包含个人简历，仅保留邮箱作为联系方式。
- 公开页面默认隐藏手机号、年龄与政治面貌。
- 视觉与响应式规则见 `DESIGN.md`。
