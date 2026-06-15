# Kernel Notes

一个静态个人博客首页，可部署到 GitHub Pages 或 Netlify。

## GitHub Pages

1. 新建 GitHub 仓库，例如 `personal-blog`。
2. 上传本目录下的全部文件。
3. 打开仓库 `Settings -> Pages`。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/root`。
6. 保存后访问 GitHub 生成的 Pages 地址。

## Netlify

1. 登录 Netlify。
2. 选择 `Add new site -> Deploy manually`。
3. 拖入整个 `personal-blog` 文件夹。
4. 等待部署完成，Netlify 会生成公网地址。

也可以连接 GitHub 仓库自动部署。当前项目不需要构建命令，发布目录是项目根目录。
