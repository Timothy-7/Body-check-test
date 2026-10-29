# 身体小笺｜九种体质自测

适配手机端的单页问卷，浅色莫兰迪风格、大字排版。一题一页，可返回修改，完成后显示九维度反馈并下载报告。

## GitHub Pages 发布

1. 新建或选择你自己的 GitHub 仓库。GitHub Free 可使用公开仓库部署 Pages。
2. 将本目录内的 `index.html`、`.nojekyll`、`README.md` 上传到仓库根目录，并提交到 `main` 分支。不要把整个压缩包直接上传，也不要在根目录外再套一层文件夹。
3. 打开仓库 `Settings → Pages`。
4. 在 `Build and deployment` 下选择 `Source: Deploy from a branch`。
5. 分支选择 `main`，文件夹选择 `/(root)`，点击 `Save`。如果实际默认分支不是 main，选择实际分支。
6. 等待部署成功，在 Pages 设置页打开 GitHub 显示的实际网站链接。当前没有绑定仓库，因此本包不预填一个假定已上线的地址。

后续更新只需替换 `index.html` 并提交到发布分支，GitHub Pages 会重新发布。本页不依赖服务器程序或安装依赖，不使用以 `/` 开头的内部资源路径，可放在项目仓库子路径下。

## 文件说明

- `index.html`：完整网页，样式、问卷和计算逻辑均已内嵌，可直接在浏览器打开。
- `.nojekyll`：以静态文件方式发布。
- `README.md`：本发布说明，不参与问卷计算。

## 内容与数据

页面已移除“试算版”及“待审核”说明；保留题目来源、计分方式及“不能替代医生诊断”的提示。移除界面标记不改变问卷来源或评分算法，不代表获得官方认证。

本问卷使用所提供的改写题目。答案与分数只在当前浏览器内计算，不上传或长期保存，不收集姓名、电话。下载的报告保存在使用者设备中。仓库中没有真实顾客答卷、网站密码或发布凭据。

GitHub 官方配置说明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
