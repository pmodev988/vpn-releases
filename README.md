# PMO VPN for Windows

[下载 Windows 0.4.3.0 · Download · ダウンロード](https://github.com/pmodev988/vpn-releases/releases/tag/v0.4.3.0) · [全部版本 · All releases · すべてのリリース](https://github.com/pmodev988/vpn-releases/releases)

## 中文

当前版本 **0.4.3.0，试运行自签名版**。本仓库提供 Windows 安装包、公开签名证书和 SHA-256 校验文件，支持 Windows 11 x64（内部版本 22621 或更新）。安装需要管理员权限。

本版修复手动升级后，旧版本更新记录导致客户端在登录前显示“连接配置未就绪／安全校验失败”的问题。退出托盘中的旧客户端后运行新版安装包。

内置签名接入配置，服务端继续使用已部署的 0.3.2。使用前仍需在 OPS 开通账户、策略和额度。新版安装后的真实登录、生产隧道、撤权及断网恢复尚待验收，自动升级关闭。Windows 可能提示未知发布者或 SmartScreen 警告，请核对摘要和证书指纹。

## 日本語

**0.4.3.0 は自己署名付き試用版**です。Windows 11 x64、ビルド 22621 以降に対応し、管理者権限でインストールします。インストーラー、公開署名証明書、SHA-256 チェックサムを提供します。

手動更新後に古い更新記録が残り、ログイン前に接続設定や安全性の検証エラーが出る問題を修正しました。タスクトレイから旧クライアントを終了してから、新しいインストーラーを実行してください。

署名済み接続設定を同梱し、サーバーは配置済みの 0.3.2 を継続使用します。利用前に OPS でアカウント・ポリシー・利用枠の設定が必要です。更新後の実ログイン、本番トンネル、権限取消、切断からの復旧は未検証です。自動更新は無効です。Windows の警告が出る場合がありますので、ハッシュと証明書を確認してください。

## English

**0.4.3.0 is a self-signed trial release** for Windows 11 x64, build 22621 or later. Installation requires administrator approval. This repository provides the installer, public signing certificate and SHA-256 checksums.

This version fixes stale update records preventing startup before login after a manual upgrade. Exit the old client from the system tray before running the new installer.

Signed connection settings are embedded; deployed server version 0.3.2 is retained. Accounts, policies and budgets must be provisioned in OPS. Real login after installation, production tunnels, revocation and outage recovery remain unaccepted. Automatic upgrades are disabled. Windows may show warnings for the self-signed publisher; verify the hash and certificate.
