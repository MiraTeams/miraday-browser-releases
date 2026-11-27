# MiraDay Browser 官方下载

打开[最新稳定版](https://github.com/MiraTeams/miraday-browser-releases/releases/latest)，在 **Assets** 中选择适合你操作系统的安装包。首次发布前，下载列表为空。各版本的更新说明和安装包都在[全部版本](https://github.com/MiraTeams/miraday-browser-releases/releases)中。

## 订阅版本更新

登录 GitHub 后，点击本页右上角的 **Watch → Custom → Releases → Apply**。使用 RSS 或 Atom 阅读器时，可以直接订阅[版本更新动态](https://github.com/MiraTeams/miraday-browser-releases/releases.atom)。

## 检查最新版本

[latest.json](https://raw.githubusercontent.com/MiraTeams/miraday-browser-releases/main/latest.json) 提供当前稳定版的标签、发布页和安装包下载地址。`release` 为 `null` 表示目前没有公开稳定版。

## 维护者发布说明

在本仓库创建 Release 草稿，上传安装包并检查文件名后，再发布正式版本。发布、编辑、撤回或删除版本时，GitHub Actions 会重新读取 GitHub 标记的最新稳定版，更新 `main` 分支上的 `latest.json`。

如果在发布之后补传或替换了安装包，请打开[版本清单同步](https://github.com/MiraTeams/miraday-browser-releases/actions/workflows/sync-latest.yml)，点击 **Run workflow**，选择 `main` 并运行。完成后，核对清单中的文件名、字节数和下载链接。
