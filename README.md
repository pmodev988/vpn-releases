# PMO VPN for Windows

[下载 Windows 0.4.5.0 · Download · ダウンロード](https://github.com/pmodev988/vpn-releases/releases/tag/v0.4.5.0) · [全部版本](https://github.com/pmodev988/vpn-releases/releases)

## 中文

0.4.5.0 修复登录框输入被后台状态查询打断的问题。客户端直接输入邮箱和密码，不打开外部浏览器。

旧客户端正在运行时也可启动新安装包，选择升级并确认。安装器会断开 VPN、恢复网络、关闭旧客户端，完成后重新打开；配置保留，需要自行点击连接。取消确认不执行升级。支持 Windows 11 x64（22621及以上）。

当前为试运行自签名版，附公开证书及 SHA256SUMS。界面与安装故障测试通过；最终包实机升级、生产登录、隧道及恢复仍待验收。OPS 接入配置仍需完成。自动升级关闭。

## 日本語

0.4.5.0 はバックグラウンドの状態確認でログイン入力が中断される問題を修正します。メールアドレスとパスワードをクライアント内で入力します。

実行中でも新しいインストーラーを起動できます。確認後、VPNを切断してネットワークを復元し、クライアントを終了・更新・再起動します。設定を保持し、自動接続はしません。Windows 11 x64対応の自己署名試用版です。実機更新と本番接続の検証は未完了です。自動更新は無効です。

## English

0.4.5.0 fixes login fields losing focus during background status polling. Enter email and password directly in the client.

Run the new installer while the client is open. After confirmation it disconnects VPN, restores networking, closes the client, upgrades and reopens it. Settings are retained; reconnect manually. Cancelling leaves the installation unchanged. Self-signed trial for Windows 11 x64. UI and fault-injection tests passed; actual installation and production tunnel acceptance remain pending. OPS provisioning is required; automatic updates are disabled.
