# 求职手账 · Career Journal

卡片式求职进度管理网页。无需安装依赖、无需 API Key。

## 运行

解压后双击 `index.html` 即可打开。也可以运行 `python -m http.server 8000` 后访问 http://localhost:8000。

## 功能

- 岗位卡片、进度时间线、统计、搜索与筛选
- 点击卡片编辑 JD、招聘链接、面试日期与备注
- 新增岗位、页面内确认删除
- JSON 备份导入与导出

## 数据说明

初始内容均为演示岗位。数据保存在浏览器 localStorage，不会同步到服务器或 GitHub。不同域名、浏览器及本地文件通常使用不同存储；迁移前请导出 JSON，再在新页面导入。

## GitHub Pages

将本目录中的 index.html 和 README.md 上传到仓库根目录。
在仓库 Settings → Pages → Build and deployment 中选择 Deploy from a branch，分支 main，目录 / (root)，保存后等待部署。

## 修改

全部 HTML、CSS 和 JavaScript 都在 index.html 中。CSS 位于 style 标签，交互与示例数据位于 script 标签。
