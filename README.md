# YMH-Browser Releases

这里是 YMH-Browser 的公开发布仓库，只提供面向最终用户的安装包、校验文件和版本说明，不包含源码、代理配置、Hub 凭据或本地用户数据。

## 当前版本

- 最新版本：v1.6.4
- Windows 安装包：[YMH-Browser-Setup-1.6.4.exe](https://github.com/tryle17/YMH-Browser-Releases/releases/download/v1.6.4/YMH-Browser-Setup-1.6.4.exe)
- SHA256 校验文件：[YMH-Browser-Setup-1.6.4.exe.sha256](https://github.com/tryle17/YMH-Browser-Releases/releases/download/v1.6.4/YMH-Browser-Setup-1.6.4.exe.sha256)
- 版本说明：[v1.6.4 Release](https://github.com/tryle17/YMH-Browser-Releases/releases/tag/v1.6.4)

当前仓库只保留最新可升级版本。应用内更新检查会读取最新 Release，并根据当前平台选择对应的安装包。

## 安装与升级

1. 下载最新的 YMH-Browser-Setup-<version>.exe。
2. 可选下载同名 .sha256 文件，并在安装前校验安装包的 SHA256。
3. 运行安装程序，按向导完成安装或升级。
4. 已安装用户也可以在应用内打开“检查更新”，下载完成后选择“立即安装”。

升级会保留本地实例、代理、书签和浏览器用户数据。升级前仍建议关闭正在运行的浏览器实例，并保留本地备份。

## 发布内容

公开仓库仅包含 Windows 安装程序、对应的 SHA256 校验文件和面向最终用户的版本说明。源码和开发约束保存在私有源码仓库 [tryle17/YMH-Browser](https://github.com/tryle17/YMH-Browser)。

## 使用边界

请仅在拥有合法授权的账号、网站和测试环境中使用。IP 信誉、TLS/JA3、行为风控和服务端策略可能影响第三方网站结果，任何浏览器指纹配置都不应被理解为对特定网站通过率的保证。

## 问题反馈

反馈时请提供应用版本、操作系统、可复现步骤和不包含敏感信息的日志。请勿提交代理订阅、节点凭据、Hub token、repo key、Cookie 或本地用户数据。
