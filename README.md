# 筑途坊 · 作品索引

记录我借助 Codex 制作的应用、网站和工具。

作品介绍：[筑途坊 · 我的作品](https://www.zhutufang.cn/works/)。

## Android 应用

| 作品 | 介绍 | 项目与源码 | 安装包与历史版本 |
| --- | --- | --- | --- |
| 温故 | [把经验放进锁屏](https://www.zhutufang.cn/articles/wengu-experience-wallpaper/) | [wengu-android](https://github.com/wangsir9825/wengu-android) | [0.3.0 试用版与历史 APK](https://github.com/wangsir9825/wengu-android/releases/tag/v0.3.0) · [网盘下载](https://pan.baidu.com/s/1-ZV3McrNwXdkg2V2Bq14pg?pwd=pzu7)（提取码 pzu7） |

## 网站与 Web 应用

后续作品在此登记。

## 桌面应用

| 作品 | 介绍 | 项目与源码 | 下载与版本 |
| --- | --- | --- | --- |
| 简下载 | [下载文件的 Windows 小工具](https://www.zhutufang.cn/articles/acb6c6dd-5be6-4a96-9639-1493095004b3/) | [simple-downloader](https://github.com/wangsir9825/simple-downloader) | [v1.0.1 · Windows x64](https://github.com/wangsir9825/simple-downloader/releases/tag/v1.0.1) · [网盘下载](https://pan.baidu.com/s/11t7p4yhzz8izw1T3-enDpg?pwd=db8t)（提取码 db8t） |

## 工具与自动化

后续作品在此登记。

## 仓库管理规则

- 每件作品建立独立仓库，分别管理源码、Issues、更新说明和 Releases。
- 仓库名称使用小写英文与连字符；例如 `wengu-android`。
- Android 应用可使用 `android-app` 主题，网站使用 `web-app`，桌面应用使用 `desktop-app`，工具使用 `developer-tools`；所有作品统一添加 `zhutufang` 主题。
- 本仓库只维护总目录和发布规则，各作品的源码保存在各自仓库。
- 作品 README 记录用途、平台、网站介绍、下载方式、构建步骤和当前版本状态。

## 发布规则

1. 采用 `v主版本.次版本.修订版本` 标签，例如 `v1.0.0`；测试版可使用 `v1.1.0-beta.1`。
2. 使用 GitHub Releases 上传 APK 和对应版本的更新说明；保留已经发布的历史版本。
3. APK 文件名包含作品名、版本和平台，例如 `wengu-v1.0.0-android.apk`。
4. 同一份安装包备份到百度网盘，保存对应的更新说明和 SHA-256 校验值。
5. 百度网盘的最新版文件夹保留当前公开版本并标注试用状态；旧 APK 在历史版本目录按版本号命名，多附件版本使用独立版本文件夹。
6. 网站下载地址指向当前公开版本下载入口，项目首页指向对应 GitHub 仓库。

每次发布前，整理可公开的源码与安装包。签名密钥、密码、API 密钥和个人运行数据不进入公开仓库。
