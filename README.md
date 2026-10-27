# FastPrintImposer-releases

快印拼版助手 V2 的**安装包**（只放安装包，不含源代码）。

- 店里电脑打开软件会读这里最新发布里的 `latest.json`，有新版本就提示更新。
- 下载：右边 **Releases** 里最新的 `FastPrintImposerV2-版本号-windows-x64-setup.exe`。

## 打包（维护用）

打包在这个公开仓库里进行（公开仓库的 GitHub Actions 不限时间）：
**Actions → Build FastPrintImposer V2 → Run workflow**，填源代码分支（正式版 `main`），要发给店里电脑就勾“发布”。
打包时用只读密钥 `SOURCE_TOKEN` 临时取私有仓库的源代码，打完随打包机销毁，不存进本仓库。
