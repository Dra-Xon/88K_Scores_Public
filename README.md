# DraXon_Space

这是一次测试。架构更新中！

* <a href="https://draxon.space/" target="_blank" rel="noopener noreferrer">点我进入网站</a>

站点部署在域名根目录，VitePress 的 `base` 为 `/`。站内资源使用根路径，不绑定具体域名；本地目录结构保持不变。

在 `VitePress/` 中运行 `npm run docs:build` 更新 `Web/`，运行 `npm run docs:preview` 在 4174 端口预览。发布流程直接使用已提交的 `Web/`，因此内容或源码变更后需要一并提交构建产物。
