# 学迹 GitHub Pages 公开只读站点

这个文件夹用于发布“全班脱敏只读版”。公开页面没有编辑入口，数据来自 `records.json`。

## 第一次发布

1. 登录 GitHub，新建一个仓库，例如 `xueji`。
2. 将本文件夹中的 `index.html`、`records.json`、`.nojekyll` 上传到仓库根目录。
3. 打开仓库 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. Branch 选择 `main`，目录选择 `/ (root)`，保存。
6. 等待 GitHub 生成地址，通常形式为 `https://你的用户名.github.io/xueji/`。

## 发布或更新学习记录

1. 在电脑上打开教师编辑器 `学迹-教师编辑与只读分享版.html`。
2. 教师登录、完成登记并保存。
3. 进入“历史记录”，点击“导出GitHub数据”。
4. 浏览器会下载一个已经脱敏的 `records.json`。
5. 在 GitHub 仓库中用新文件替换旧的 `records.json` 并提交。
6. 等待片刻后，家长刷新页面即可看到更新。

> 不要把教师编辑器上传到公开仓库；只上传本公开站点文件夹中的文件。

## 自定义域名

购买并持有 `iris33.cn` 后，可在仓库 **Settings → Pages → Custom domain** 中填写域名，再按照 GitHub 提示到域名注册商处设置 DNS。启用 HTTPS 后再将链接分享给家长。

## 隐私

- `records.json` 中的姓名由教师编辑器自动脱敏。
- 页面已设置不允许搜索引擎索引，但任何获得网址的人仍可查看页面内容。
- 发布前建议抽查 `records.json`，确认备注中没有电话号码或其他敏感信息。
