# 我们的婚礼 · 待办清单

这是一个不依赖外部 CDN 的 GitHub Pages 静态网页，数据来自《备婚清单_待办事项总表.xlsx》。

## 页面功能

- 108 条事项，保留原表中的阶段、任务、关联方、准备内容和备注
- 事项看板：搜索、阶段筛选、关联方筛选、状态筛选
- 状态可改为「未开始 / 进行中 / 已完成」，浏览器本地保存
- 统一时间轴：以 2026-12-12 为终点，所有事项共用一条时间轴
- 关联方总览、阶段进度、JSON 导入导出
- 手机和电脑自适应，不依赖外部 CDN

## GitHub Pages 路径

将 `index.html` 放到 `ylyang/ylyang.github.com` 仓库 `master` 分支的 `wedding-todo/` 目录后，页面路径为：

`https://ylyang.github.io/wedding-todo/`

GitHub Pages 需要在仓库设置中选择 `master` 分支作为发布源。纯静态页面的状态保存在每个浏览器本地；多人实时同步需要再接入数据库或协作后端。
