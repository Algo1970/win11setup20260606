## win11setup20260606
win11のセットアップマニュアル

- GoogleChromeのインストール
- Powertoysのインストール

### リモート接続

- リモート接続で使用する場合、インストールしたユーザーでパスワード設定されていない場合あり。
- 管理者権限cmdで、新たにRDP接続用ユーザー作成したほうが早いかも

```
net user
net user username pwd /add
net localgroup "Remote Desktop Users" username /add
```

### sharpkeys (Microsoftストア)

- CapsLock ⇒ leftCRTL

### PowerToys設定（Microsoftストア）

- CTRL+HJKL ⇒ 移動キー


### スタートアップアプリ設定

- タスクマネージャー ⇒ スタートアップアプリ ⇒ OneDrive削除
- 
