# StudyFlow · Android Releases

这是 StudyFlow 的**公开 APK 更新发布仓库**。仅用于发布已经签名并验证的安装包、版本记录和校验值；StudyFlow 的源代码和签名私钥不在此仓库。

## 更新方式

在 StudyFlow Android App 中打开 **设置 → 应用更新 → 检查新版**。更新检查使用本仓库公开的 GitHub Releases，下载完成后会校验 APK 包名、签名、版本号，再请求 Android 系统确认安装。

## 发布规范

- 发布标签形如 `v1.0.11`、`v1.0.12`；**末尾数字需要与 APK 的递增 versionCode 对应**。
- 发布内容必须附上使用相同固定密钥签署的 `.apk` 文件。
- 不要在此仓库提交 `.jks`、密钥密码或 GitHub API 令牌。
- 安装过旧 Debug 签名包的用户，无法直接覆盖安装固定签名的正式版；卸载会删除本地数据，请先备份。

源代码仓库是私有的：`StudyFlow-Android`。

