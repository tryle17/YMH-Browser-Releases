# YMH-Browser Releases

这里是 YMH-Browser 的公开发布仓库，只提供面向最终用户的安装包、校验文件和版本说明，不包含源码、代理配置、Hub 凭据或本地用户数据。

## 当前版本

- 最新版本：v1.5.6
- 发布日期：2026-08-12
- Windows 安装包：[YMH-Browser-Setup-1.5.6.exe](https://github.com/tryle17/YMH-Browser-Releases/releases/download/v1.5.6/YMH-Browser-Setup-1.5.6.exe)
- SHA256 校验文件：[YMH-Browser-Setup-1.5.6.exe.sha256](https://github.com/tryle17/YMH-Browser-Releases/releases/download/v1.5.6/YMH-Browser-Setup-1.5.6.exe.sha256)
- 版本说明：[v1.5.6 Release](https://github.com/tryle17/YMH-Browser-Releases/releases/tag/v1.5.6)

当前仓库只保留最新可升级版本。应用内更新检查会读取最新 Release，并根据当前平台选择对应的安装包。

## 安装与升级

1. 下载最新的 YMH-Browser-Setup-<version>.exe。
2. 可选下载同名 .sha256 文件，并在安装前校验安装包的 SHA256。
3. 运行安装程序，按向导完成安装或升级。
4. 已安装用户也可以在应用内打开“检查更新”，下载完成后选择“立即安装”。

升级会保留本地实例、代理、书签和浏览器用户数据。升级前仍建议关闭正在运行的浏览器实例，并保留本地备份。

## 1.5.6 更新内容

- 修复 fingerprint-chromium 148 默认搜索引擎设置失败的问题，按内核返回的真实 engine id 选择 Bing。
- 修复更新弹窗点击“立即下载”无反馈的问题，补充下载中、失败、重试和立即安装状态。
- 同步 Hub 服务权限和运行版本，member / sync_member 可以搜索并安装已发布插件，owner 保留发布管理权限。
- 重写源码仓库和发布仓库根 README，补充实际安装、升级、实例、代理、内核、Hub 和插件商店说明。

## 发布内容

公开仓库仅包含：

- Windows 安装程序；
- 与安装程序对应的 SHA256 校验文件；
- 面向最终用户的版本说明。

源码和开发约束保存在私有源码仓库 [tryle17/YMH-Browser](https://github.com/tryle17/YMH-Browser)。浏览器内核使用 [adryfish/fingerprint-chromium](https://github.com/adryfish/fingerprint-chromium/releases) 的预编译发行版。

## 使用边界

请仅在拥有合法授权的账号、网站和测试环境中使用。IP 信誉、TLS/JA3、行为风控和服务端策略可能影响第三方网站结果，任何浏览器指纹配置都不应被理解为对特定网站通过率的保证。

## 问题反馈

反馈时请提供应用版本、操作系统、可复现步骤和不包含敏感信息的日志。请勿提交代理订阅、节点凭据、Hub token、repo key、Cookie 或本地用户数据。
