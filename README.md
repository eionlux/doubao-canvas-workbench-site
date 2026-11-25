# 豆包无限画布工作台官网

这是可单独推送到 GitHub 的官网发布目录，内容只包含静态网站、便携版下载包和自有域名配置，不包含桌面程序源码或归档文件。

## GitHub Pages

1. 新建 GitHub 仓库并将本目录内容推送到 `main` 分支。
2. 在仓库的 **Settings → Pages → Build and deployment** 中选择 **Deploy from a branch**。
3. 选择 `main` 分支及 `/(root)` 目录并保存。
4. 等待 Pages 部署完成。

仓库根目录的 `CNAME` 已设置为 `hb.cerecin.xyz`。请在域名 DNS 中添加以下 CNAME 记录：

| 类型 | 主机记录 | 指向 |
| --- | --- | --- |
| CNAME | `hb` | `eionlux.github.io` |

DNS 生效后，在 Pages 设置中确认自定义域名并启用 HTTPS。

## 更新下载版本

覆盖 `downloads/doubao-canvas-workbench-portable.zip` 后提交并推送，网站下载按钮会提供新版本。

