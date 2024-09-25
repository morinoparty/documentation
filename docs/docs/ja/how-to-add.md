# ドキュメントを追加するには

## プラグインを入れ替えた場合

`ja/list`配下にあるサーバーごとのファイルを編集してください。


## プラグインのドキュメントを変更する場合

`ja/plugins`配下にあるプラグインごとのファイルを編集してください。

## プラグインのドキュメントを追加する場合

`ja/plugins`配下に新しいファイルを作成してください。
ファイル名は`/pl`コマンドで表示されるプラグイン名を小文字化したものにしてください。
タイトルは`/pl`コマンドで表示されるプラグイン名をそのまま使ってください。

### 例 : CoreProtect

`/pl`コマンドを実行してください。

```log
/pl

[00:00:00 INFO]: Server Plugins (7):
[00:00:00 INFO]: Bukkit Plugins:
[00:00:00 INFO]:  - CoreProtect, JukeBox, LuckPerms, MineStamp, NoteBlockAPI, ProtocolLib, SlotMachine
```

このようにいくつかのプラグインが表示されます。
`CoreProtect`が表示されたので、`ja/plugins`に`coreprotect.md`というファイルを作成してください。

```markdown
# CoreProtect
## 概要
## 使い方
## コマンド
## 権限
### 管理用
### プレイヤー用
```

このようにファイルを作成した後、内容を記述してください。
