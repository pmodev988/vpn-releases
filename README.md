# PMO VPN for Windows

[下载 Windows 0.4.7.0 · Download · ダウンロード](https://github.com/pmodev988/vpn-releases/releases/download/v0.4.7.0/vpn-setup-0.4.7.0-windows.exe) · [版本说明、公开证书及校验文件](https://github.com/pmodev988/vpn-releases/releases/tag/v0.4.7.0) · [全部版本](https://github.com/pmodev988/vpn-releases/releases)

## 中文

0.4.7.0 增加 Windows 10／11 原生 x64 桌面系统安装支持（AMD／Intel，最低 build 10240），修复此前只允许 Windows 11 build 22621 及以上安装的限制。32 位、ARM64、Windows Server 不支持。

邮箱、密码直接在客户端输入；同机单实例，重复点击显示已有窗口。旧客户端运行时可启动安装包，确认后断开 VPN、恢复网络、关闭旧客户端并升级，保留配置，完成后自行重连。

不支持的系统显示具体原因；服务启动失败保留阶段和系统错误号，便于排查。准入与安装维护检查 63 项通过；原生核心测试 104 项通过、21 项跳过。

**当前为试运行自签名版。Windows 10 最终包实机安装、真实登录及联网仍待验收；已报告的另一台 Windows 11 AMD 电脑启动故障仍待复验，不能保证本版已解决该故障。** 自动升级关闭。请在版本页下载公开证书和 SHA256SUMS 核对文件。

## 日本語

0.4.7.0 は Windows 10／11 のネイティブ x64 デスクトップ版（AMD／Intel、build 10240 以降）をインストール対象に追加しました。クライアント内ログイン、単一起動、実行中の確認付き更新を継続し、起動失敗の診断情報を改善しています。

自己署名試用版。Windows 10 実機のインストール・ログイン・通信と、報告済みの Windows 11 AMD 機の障害は未検証です。自動更新は無効です。

## English

0.4.7.0 adds installer admission for Windows 10/11 native x64 desktop systems (AMD/Intel, build 10240+), retaining in-app password login, single-instance operation and confirmed upgrades while running. Startup failures preserve a diagnostic stage and native error code.

Self-signed trial. Final-package Windows 10 installation, real login and traffic remain unverified. The reported Windows 11 AMD startup failure still needs retesting. Automatic upgrades are disabled. Public certificate and checksums are available on the release page.
