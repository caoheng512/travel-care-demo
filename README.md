# 安心旅养演示前端

这是一个单文件静态演示页，用于展示短期旅居康养、短期照护、AI 需求匹配、顾问联系、拼团详情和转发邀请流程。

## 本地预览

直接打开 `index.html` 即可预览。

也可以在当前目录启动静态服务：

```bash
python3 -m http.server 8765 --bind 127.0.0.1
```

然后访问：

```text
http://127.0.0.1:8765/
```

## GitHub Pages 部署

推送到 GitHub 后，本仓库包含的 GitHub Actions 会自动发布到 GitHub Pages。

首次使用时，需要在 GitHub 仓库的 `Settings -> Pages` 中选择 `GitHub Actions` 作为发布来源。
