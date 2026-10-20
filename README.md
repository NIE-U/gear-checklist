# 装备清单

面向户外装备整理的纯静态网页，支持 7 类装备的新增、编辑、删除、文本导入、CSV 导出和长图导出。

## 在线访问

GitHub Pages 发布后地址为：

`https://<GitHub用户名>.github.io/gear-checklist/`

## 数据说明

- 不设账号、数据库或后端。
- 每位访客的清单只保存在自己浏览器的 `localStorage` 中，刷新后仍保留。
- 不同访客、浏览器或设备之间的数据不会同步。
- 清理浏览器数据、换设备或换浏览器前，请先使用页面内的“导出 CSV”或“导出长图”保存备份。

## 修改页面

直接修改 `index.html`，然后提交并推送：

```powershell
git add index.html README.md
git commit -m "Update gear list"
git push
```

GitHub Pages 通常会在 1 分钟左右自动重新部署。修改页面代码不会清除访客已保存在浏览器里的清单。

## 发布配置

- 发布分支：`main`
- Pages 目录：仓库根目录 `/`
- 入口文件：`index.html`
- 页面不需要构建步骤，也不依赖外部 CDN。
